# Application Security Program Metrics

Assessing a typical application security program involves tracking key metrics and Key Performance Indicators (KPIs) to measure its effectiveness, identify areas for improvement, and demonstrate the program's impact on reducing security risks. These metrics and KPIs provide a holistic view of the effectiveness, performance, and impact of an application security program. Regularly monitoring and analyzing these metrics can help organizations make data-driven decisions, prioritize security efforts, and continuously improve their overall security posture.

Each metric should be well-documented, including a description of the sources, measurement coverage, and guidance on its use to explain application security trends. Metrics that are frequently measured, easy or inexpensive to gather, and expressed as a cardinal number or a percentage are best to gather. Metrics should be publicly published by Application security and development teams.

KPIs can be developed after enough data is gathered from the metrics to make informed choices to establish realistic objectives. These should be developed with input from the AppSec team and buy-in from leadership. KPIs should be available to the application teams and include acceptability thresholds and guidance in case teams need to act. KPIs should be reviewed at least annually for their effectiveness and efficiency. Well-defined KPIs make success of the application security program clearly visible.

Ideally, KPIs and metrics ultimately trigger most changes to the application security strategy.

A prioritized list of key metrics and KPIs to consider:

## Must-haves

Since a new AppSec program must pick-and-choose what it does, these are essential metrics to help see the needle moving early on that are relatively easy to gather and won't break a small team.

### Code Coverage
* Metric: Percentage of code covered by security testing tools (SAST, DAST, IAST, etc.).
* Rationale: Gives an indication of custom code security testing coverage.
* Report: Percentage by application/team and in aggregate.
* Sources: Custom code scanning tools and repositories.
* Frequency: Monthly.
* KPI: Strive for a high code coverage percentage to ensure thorough security testing across the application codebase.

### Severity Distribution
* Metric: Distribution of vulnerabilities based on severity level (i.e. low, medium, high, critical).
* Rationale: Shows how much risk organization is exposed to by custom software.
* Report: Numbers by application/team and in aggregate.
* Sources: Security scanning tools.
* Frequency: Weekly.
* KPI: Prioritize fixing high and critical severity vulnerabilities to reduce the overall risk exposure.

### Third-Party Risk Metrics
* Metric: Assessment of security risks associated with external packages/dependencies.
* Rationale: Shows how many new vulnerabilities are introduced by third-party software.
* Report: Numbers by application/team and in aggregate.
* Sources: Dependency scanning tools.
* Frequency: Monthly.
* KPI: Manage and mitigate third-party security risks by monitoring and improving vendor security practices.

### Security Training Effectiveness
* Metric: Rate of completion and performance in security training programs
* Rationale: Shows attendance in and understanding of security related training.
* Report: Percentages: attendance and aggregate assessment scores by training and group.
* Sources: Learning Management System.
* Frequency: Quarterly.
* KPI: Improve security awareness and knowledge among developers and stakeholders through effective training program.

## Should-haves

Once the basic metrics are in place and the AppSec program matures, these provide finer-tuned insight into the AppSec program.

### Rate of New Vulnerabilities
* Metric: Number of new vulnerabilities discovered over time.
* Rationale: Shows how many new vulnerabilities introduced by custom software.
* Report: Numbers by application/team and in aggregate.
* Sources: Custom code scanning tools.
* Frequency: Weekly.
* KPI: Aim to reduce the rate of new vulnerabilities by implementing proactive security measures and continuous improvement practices.

### Remediation latency
* Metric: Average time taken to remediate identified vulnerabilities.
* Rationale: Shows how long vulnerabilities are in environment once known.
* Report: Count/percentage by criticality and time durations per severity by application/team and in aggregate.
* Sources: Security scanning tools.
* Frequency: Monthly.
* KPI: Strive to reduce the time-to-fix metric to enhance the responsiveness of the security team in addressing vulnerabilities.

### Compliance Adherence
* Metric: Security controls and practices compliant with applicable industry standards and regulations.
* Rationale: Shows compliance with applicable regulations.
* Report: Percentage.
* Sources: Security and GRC SMEs.
* Frequency: Annually.
* KPI: Maintain a high level of compliance adherence to meet regulatory requirements and mitigate legal risks.

## Nice-to-haves

These take more work to calculate, but give insight into how well the AppSec program is working.

### False Positive Rate
* Metric: Percentage of reported vulnerabilities that are false positives.
* Rationale: Shows effectiveness of security scanning tools. Helps determine whether specific findings (or classes of findings) should be filtered out of scan results.
* Report: Percentage by tool and finding.
* Sources: Security scanning tools and security SMEs.
* Frequency: Monthly.
* KPI: Keep the false positive rate low to ensure accurate identification of real security issues.

### Secure Software Development Lifecycle (SSDLC)
* Metric: Projects following secure coding practices and incorporating security checkpoints.
* Rationale: Shows adherence of development projects to the application security program.
* Report: Percentage by practice by application/team and in aggregate.
* Sources: Application teams and security SMEs.
* Frequency: Quarterly.
* KPI: Increase the adoption of secure development practices throughout the SSDLC.

