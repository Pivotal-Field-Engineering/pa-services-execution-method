---
title: "CI / CD Pipelines"
date: 2018-04-16T10:10:10-04:00
type: page
draft: false
---
## Activity name
CI / CD Pipeline Tooling

## Participants
- Platform Architect
- Customer's Development Teams
- _Customer's DevOps / Release Engineering Team_
- _Customer's Architecture Team_

## Guidance
Prior to beginning an Application Transformation, you need to ensure that the customer has the appropriate CI / CD automation tooling in place.  Customers are free to use whatever products they'd like, but will need the following tools:

- Version control (Git, Subversion, TFS)
- Artifact repository (Nexus, Artifactory)
- Dependency management (Maven, Ivy, NuGet, NPM)
- Build tool (Maven, MSBuild)
- CI server (Jenkins, TFS, TeamCity)
- Code and test analysis

You also need to ensure that the customer has a mature practice for building, testing, and deploying code through different environments.  Part of the Application Transformation will be to immediately leverage these tools and practice in the refactoring effort.

## Outcome
A list of CI / CD automation tooling in place, as well as the customer's release engineering practice.

---
< [Previous]({{< ref "services.md" >}})
