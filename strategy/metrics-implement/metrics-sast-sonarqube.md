# SonarQube metrics

SonarQube has a well-docmumented API that lends itself to extracting a wide range of metrics without needing to go through the UI. 

The API is documented at []() for the 9.9. LTS version.

For all of the following URLs, we'll use the API endpoints, which are just whichever instance you normally use followed by ```/api``` foillowed by the specific endpoint. Anyplace ```[SQ API URL]``` appears below, replace it wiht that preamble URL. For example, if your regular instance of SonarQube is ```https://scanner.mycompany.com:8443```, the API preamble will be ```https://scanner.mycompany.com:8443/api```, which will then  have the endpoint appended to it.

If going for an overall portfolio (or other multi-project) view, to extract any project-specific data, first get a list of projects in the instance.

## Project inventory

```[SQ API URL]/components/search_projects```

