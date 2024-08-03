---

layout: col-sidebar
title: OWASP Auto DevSecOps
tags: example-tag
level: 2
type: code
pitch: A very brief, one-line description of your project

---

DevSecops is a python package that can be used at CI/CD for SAST and DAST.  I am using opensource scanners in a serverless style. No need to host sonarqube or purchase semgrep pro. I am also writing own semgrep rules, that will be maintained over the time by community. 

it will work something like 
`pip install devsecops`
$devsecops sast --all --slack-token <> --output report.pdf

### Road Map
v0.0.1 - SAST, Secret Detection, DAST using the opensource tools and custom scripts. Slack Integration.  (Completed)

v0.0.2 - Differential Scan, JIRA integration, Github Action (In Progress)

v0.0.3 - Trivy support to perform Dependency Scan. 

v0.0.4 - Dastardly support
