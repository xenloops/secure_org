# Maturing the Security Program

These are tasks that should be undertaken to reach the three maturity levels according to the [OWASP SAMM](https://owaspsamm.org). In fact, these are largely taken from the SAMM, rephrased from questions to statements.

# Governance
## Strategy and Metrics
### Create and Promote
| Level | Task |
|:--:|--|
| 1 | Do you understand the enterprise-wide risk appetite for your applications? |
| 2 | Do you have a strategic plan for application security and use it to make decisions? |
| 3 | Do you regularly review and update the Strategic Plan for Application Security? |
### Measure and Improve
| Level | Task |
|:--:|--|
| 1 | Do you use a set of metrics to measure the effectiveness and efficiency of the application security program across applications? |
| 2 | Did you define Key Performance Indicators (KPI) from available application security metrics? |
| 3 | Do you update the Application Security strategy and roadmap based on application security metrics and KPIs? |
## Policy and Compliance
### Policy and Standards
| Level | Task |
|:--:|--|
| 1 | Do you have and apply a common set of policies and standards throughout your organization? |
| 2 | Do you publish the organization's policies as test scripts or run-books for easy interpretation by development teams? |
| 3 | Do you regularly report on policy and standard compliance, and use that information to guide compliance improvement efforts? |
### Compliance Management
| Level | Task |
|:--:|--|
| 1 | Do you have a complete picture of your external compliance obligations? |
| 2 | Do you have a standard set of security requirements and verification procedures addressing the organization's external compliance obligations? |
| 3 | Do you regularly report on adherence to external compliance obligations and use that information to guide efforts to close compliance gaps? |
## Education and Guidance
### Training and Awareness
| Level | Task |
|:--:|--|
| 1 | Do you require employees involved with application development to take SDLC training? |
| 2 | Is training customized for individual roles such as developers, testers, or security champions? |
| 3 | Have you implemented a Learning Management System or equivalent to track employee training and certification processes? |
### Organization and Culture
| Level | Task |
|:--:|--|
| 1 | Have you identified a Security Champion for each development team? |
| 2 | Does the organization have a Secure Software Center of Excellence (SSCE)? |
| 3 | Is there a centralized portal where developers and application security professionals from different teams and business units are able to communicate and share information? |

# Design
## Threat Assessment
### Application Risk Profile
| Level | Task |
|:--:|--|
| 1 | Do you classify applications according to business risk based on a simple and predefined set of questions? |
| 2 | Do you use centralized and quantified application risk profiles to evaluate business risk? |
| 3 | Do you regularly review and update the risk profiles for your applications? |
### Threat Modeling
| Level | Task |
|:--:|--|
| 1 | Do you identify and manage architectural design flaws with threat modeling? |
| 2 | Do you use a standard methodology, aligned on your application risk levels? |
| 3 | Do you regularly review and update the threat modeling methodology for your applications? |
## Security Requirements
### Software Requirements
| Level | Task |
|:--:|--|
| 1 | Do project teams specify security requirements during development? |
| 2 | Do you define, structure, and include prioritization in the artifacts of the security requirements gathering process? |
| 3 | Are vendors aligned with standard security controls and software development tools and processes that the organization utilizes? |
### Supplier Security
| Level | Task |
|:--:|--|
| 1 | Do stakeholders review vendor collaborations for security requirements and methodology? |
| 2 | Do vendors meet the security responsibilities and quality measures of service level agreements defined by the organization? |
| 3 | Are vendors aligned with standard security controls and software development tools and processes that the organization utilizes? |
## Secure Architecture
### Architecture Design
| Level | Task |
|:--:|--|
| 1 | Do teams use security principles during design? |
| 2 | Do you use shared security services during design? |
| 3 | Do you base your design on available reference architectures? |
### Technology Management
| Level | Task |
|:--:|--|
| 1 | Do you evaluate the security quality of important technologies used for development? |
| 2 | Do you have a list of recommended technologies for the organization? |
| 3 | Do you enforce the use of recommended technologies within the organization? |

# Implementation
## Secure Build
### Build Process
| Level | Task |
|:--:|--|
| 1 | Is your full build process formally described? |
| 2 | Is the build process fully automated? |
| 3 | Do you enforce automated security checks in your build processes? |
### Software Dependencies
| Level | Task |
|:--:|--|
| 1 | Do you have solid knowledge about dependencies you're relying on? |
| 2 | Do you handle 3rd party dependency risk by a formal process? |
| 3 | Do you prevent build of software if it's affected by vulnerabilities in dependencies? |

## Secure Deployment
### Deployment Process
| Level | Task |
|:--:|--|
| 1 | Do you use repeatable deployment processes? |
| 2 | Are deployment processes automated and employing security checks? |
| 3 | Do you consistently validate the integrity of deployed artifacts? |
### Secret Management
| Level | Task |
|:--:|--|
| 1 | Do you limit access to application secrets according to the least privilege principle? |
| 2 | Do you inject production secrets into configuration files during deployment? |
| 3 | Do you practice proper lifecycle management for application secrets? |

## Defect Management
### Defect Tracking
| Level | Task |
|:--:|--|
| 1 | Do you track all known security defects in accessible locations? |
| 2 | Do you keep an overview of the state of security defects across the organization? |
| 3 | Do you enforce SLAs for fixing security defects? |
### Metrics and Feedback
| Level | Task |
|:--:|--|
| 1 | Do you use basic metrics about recorded security defects to carry out quick win improvement activities? |
| 2 | Do you improve your security assurance program upon standardized metrics? |
| 3 | Do you regularly evaluate the effectiveness of your security metrics so that its input helps drive your security strategy? |

# Verification
## Architecture Assessment
### Architecture Validation
| Level | Task |
|:--:|--|
| 1 | Do you review the application architecture for key security objectives on an ad-hoc basis? |
| 2 | Do you regularly review the security mechanisms of your architecture? |
| 3 | Do you regularly review the effectiveness of the security controls? |
### Architecture Mitigation
| Level | Task |
|:--:|--|
| 1 | Do you review the application architecture for mitigations of typical threats on an ad-hoc basis? |
| 2 | Do you regularly evaluate the threats to your architecture? |
| 3 | Do you regularly update your reference architectures based on architecture assessment findings? |
## Requirements Testing
### Control Verification
| Level | Task |
|:--:|--|
| 1 | Do you test applications for the correct functioning of standard security controls? |
| 2 | Do you consistently write and execute test scripts to verify the functionality of security requirements? |
| 3 | Do you automatically test applications for security regressions? |
### Misuse/Abuse Testing
| Level | Task |
|:--:|--|
| 1 | Do you test applications using randomization or fuzzing techniques? |
| 2 | Do you create abuse cases from functional requirements and use them to drive security tests? |
| 3 | Do you perform denial of service and security stress testing? |
## Security Testing
### Scalable Baseline
| Level | Task |
|:--:|--|
| 1 | Do you scan applications with automated security testing tools? |
| 2 | Do you customize the automated security tools to your applications and technology stacks? |
| 3 | Do you integrate automated security testing into the build and deploy process? |
### Deep Understanding
| Level | Task |
|:--:|--|
| 1 | Do you manually review the security quality of selected high-risk components? |
| 2 | Do you perform penetration testing for your applications at regular intervals? |
| 3 | Do you use the results of security testing to improve the development lifecycle? |

# Operations
## Incident Management
### Incident Detection
| Level | Task |
|:--:|--|
| 1 | Do you analyze log data for security incidents periodically? |
| 2 | Do you follow a documented process for incident detection? |
| 3 | Do you review and update the incident detection process regularly? |
### Incident Response
| Level | Task |
|:--:|--|
| 1 | Do you respond to detected incidents? |
| 2 | Do you use a repeatable process for incident handling? |
| 3 | Do you have a dedicated incident response team available? |
## Environment Management
### Configuration Hardening
| Level | Task |
|:--:|--|
| 1 | Do you harden configurations for key components of your technology stacks? |
| 2 | Do you have hardening baselines for your components? |
| 3 | Do you monitor and enforce conformity with hardening baselines? |
### Patching and Updating
| Level | Task |
|:--:|--|
| 1 | Do you identify and patch vulnerable components? |
| 2 | Do you follow an established process for updating components of your technology stacks? |
| 3 | Do you regularly evaluate components and review patch level status? |
## Operational Management
### Data Protection
| Level | Task |
|:--:|--|
| 1 | Do you protect and handle information according to protection requirements for data stored and processed on each application? |
| 2 | Do you maintain a data catalog, including types, sensitivity levels, and processing and storage locations? |
| 3 | Do you regularly review and update the data catalog and your data protection policies and procedures? |
### System Decommissioning / Legacy Management
| Level | Task |
|:--:|--|
| 1 | Do you identify and remove systems, applications, application dependencies, or services that are no longer used, have reached end of life, or are no longer actively developed or supported? |
| 2 | Do you follow an established process for removing all associated resources, as part of decommissioning of unused systems, applications, application dependencies, or services? |
| 3 | Do you regularly evaluate the lifecycle state and support status of every software asset and underlying infrastructure component, and estimate their end of life? |


