---
title: "SNAP Analyses"
date: 2018-04-16T10:10:59-04:00
type: page
draft: false
---
## Activity name
SNAP Analyses

## Participants
- Platform Architect
- Customer's Application Developers

## Guidance
A SNAP analysis is a technical breakdown and analysis of an application, to better understand the level of effort and risk involved with modernizing the application.  This detailed analysis requires the input of the application's technical leader or owner, and should be done for each application that was determined to be a candidate for Application Transformation.

Although each development framework and language will have different characteristics to evaluate, there are some general topics to consider:

- Source code repository layout
- Runtime requirements
- External dependencies
- Required libraries and middleware
- Size of application
- Session state management
- Startup and shutdown times
- Native calls
- Logging and monitoring

Many of these concerns are addressed in the [12-factor methodology](http://12factor.net).  There are templates that can be used for [Java applications](https://docs.google.com/spreadsheets/d/181G2b2hgjDMNOGmet8YhoM-d17_bp5czfDBURkpN1Xo/edit?usp=sharing) and [.NET applications](https://docs.google.com/spreadsheets/d/1w3F3eYirqGFFsQ39GKCBTtBredByNNyT-EQ2iHjJrWc/edit?usp=sharing); other languages and frameworks should be analyzed against the [12-factor methodology](http://12factor.net).

## Outcome
A detailed analysis document of each application considered to be a candidate for Application Tranformation.

---
< [Previous]({{< ref "portfolio.md" >}}) | [Next]({{< ref "services.md" >}}) >
