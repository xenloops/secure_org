# SonarQube metrics

SonarQube has a well-docmumented API that lends itself to extracting a wide range of metrics without needing to go through the UI. Keep in mind, of course, that the API will only expose data that you would be able to reach through the UI given your login or API key permissions. All data are returned in JSON.

The application is documented for various versions at the following links:
* [9.9 LTA](https://docs.sonarsource.com/sonarqube/9.9)
* [Latest release](https://docs.sonarsource.com/sonarqube/latest)
* API: [Your SonarQube instance]/web_api

For all of the following URLs, we'll use the API endpoints, which are just whichever instance you normally use followed by ```/api``` foillowed by the specific endpoint. Anyplace ```[SQ API URL]``` appears below, replace it with that preamble URL. For example, if your regular instance of SonarQube is ```https://scanner.mycompany.com:9000```, the API preamble will be ```https://scanner.mycompany.com:9000/api```, which will then  have the endpoint path appended to it.

In the following URLs, some variables that your script need to supply are:

* ```PROJ_KEY```: The key for a project. This is the same as the project's name, assuming the project hasn't been renamed.
* ```PROFILE_KEY```: The key for a quality profile.

#### Overall data

These endpoints might be of interest. They're self-explanatory once you've read the SonarQube documentation referenced above.

* ```[SQ API URL]/languages/list```
* ```[SQ API URL]/qualityprofiles/export```
* ```[SQ API URL]/qualitygates/list```

For the projects using a specific profile (useful to confirm that teams are using the correct profiles and not getting away with vulnerabilities), use:

* ```[SQ API URL]/qualityprofiles/projects?key=[PROFILE_KEY]```

This endpoint gives all the built-in metrics that SonarQube tracks, and that are exposed by the API.

* ```[SQ API URL]/metrics/search```



If going for a portfolio (or other multi-project) view, to extract any project-specific data, first get a list of projects in the instance. Either of the following two works for this.

#### Project inventory

```[SQ API URL]/components/search_projects```

Returns:

      "organization": "my-org-1",
      "id": "directory-uuid",
      "key": "directory-key",
      "qualifier": "DIR",
      "name": "Directory Name",
      "project": "project-key"


#### Project last analysis

```[SQ API URL]/projects/search?projects=[PROJ_KEY]```

Returns:

      "organization": "my-org-1",
      "id": "project-uuid-1",
      "key": "project-key-1",
      "name": "Project Name 1",
      "qualifier": "TRK",
      "visibility": "public",
      "lastAnalysisDate": "2017-03-01T11:39:03+0300",
      "revision": "cfb82f55c6ef32e61828c4cb3db2da12795fd767"

Perform a substring on ```lastAnalysisDate``` to get just the date.




