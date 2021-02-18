# JFrog Pipelines Quickstart: Maven Build

Sources for [Pipeline Example: Maven Build](https://www.jfrog.com/confluence/display/JFROG/Pipeline+Example%3A+Maven+Build)

## Prerequisites

- Integrations
  - tsuyo_github: GitHub
  - artifactory: Artifactory
- Repos
  - libs-snapshot-local (maven/local)
    - Handle Snapshots
  - jcenter (maven/remote)
    - URL: https://jcenter.bintray.com
  - libs-snapshot (maven/virtual)
    - includes: libs-snapshot-local, jcenter