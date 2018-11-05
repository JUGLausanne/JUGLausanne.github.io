---
layout: post
title: "Leap from Java 8 to Java 11 in Jenkins. Our war story"
speaker: "Oleg Nenashev"
slides: ""
date: 2018-11-14 18:30:00
---

Jenkins, one of the leading open-source automation servers, has not been supporting Java 9 and above since its official release. Over the last year Jenkins contributors were working towards the support of Java 11 (Jenkins JEP-211). Jenkins has a huge and sometimes legacy Java/Groovy/native codebase, includes DSL engines, and depends on many upstream libraries and modules (including ones deleted from Java 11). It was a thorny way, but Java 11 support is almost ready to be released.

In this talk I would like to share our experiences and talk about potential obstacles others may hit while implementing Java 11 support in their projects. What issues have we hit while implementing support of Java 11 in the core? Are modules and deprecations that tricky for a web application (spoiler: no)? How have we enabled building and testing with OpenJDK 11 in our Maven-based pipelines? And how have we retained Java 8 compatibility after all these changes?

The presentation will be in English.

#### Speaker

Affiliation: Jenkins core maintainer, Principal Engineer at CloudBees

R&D and Automation engineer with Hardware/Embedded background. Oleg started contributing to Jenkins in 2012, and became a core maintainer in 2015. He focuses on Jenkins architecture and platform reliability. Oleg holds the Jenkins Ambassador title and organizes community events including Swiss Jenkins Meetup and Google Summer of Code. He also leads the Jenkins Platform SIG and leads the Java 11 compatibility project there. At CloudBees he is focused on making Jenkins cloud-native. Oleg also has a PhD degree in Hardware Engineering and contributes to the LibreCores project.

#### Links

Jenkins website: https://jenkins.io/
Jenkins JEP-211 “Java 11 support in Jenkins”: https://github.com/jenkinsci/jep/tree/master/jep/211
Jenkins Platform SIG: https://jenkins.io/sigs/platform/

#### Media

GitHub: https://github.com/oleg-nenashev/
Twitter: https://twitter.com/oleg_nenashev/
Speakerdeck: https://speakerdeck.com/onenashev
Website/blog: https://oleg-nenashev.github.io/