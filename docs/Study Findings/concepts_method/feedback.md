---
layout: default
title: Feedback mechanisms and testing in the projects
has_children: false
parent: Design Methodology
grand_parent: Expanded Study Findings
nav_order: 2
---
Missing formatting and introduction
{: .label .label-red .float-right }
# Feedback mechanisms and testing in the projects
Introduction here
{: .fs-6 .fw-300 }
---

In the two projects it seems that there is no formal testing being done. However, after some initial discussion on the topic some findings did suggest that testing is going on, just not in an organized manner. One contributor in Jellyfin said that “We don't have A-B testing or any sort of usage tracking to get information on how users do things, so we mostly fly blind until someone raises an issue.” (Interview #1, Jellyfin). This makes sense when considering the open nature of the projects. Testing is normally conducted as part of design when an internally developed product has to be verified in the intended setting or to receive feedback for iteration. However when considering this, it would seem that FLOSS projects are rather unique in that testing is an ongoing process where anyone can file a bug report. This of course requires that the testers are running the latest version, which most won't if the product is used in daily use where the goal most often is stability. However, it does seem like most of the developers all are running the latest build in their day to day use to do real-time iterative testing. One developer accounted how he does not “(...) do any specific testing. It's more just, you know, me using our home and then, you know, seeing what I think about it, any changes or not.” (Interview #5, Jellyfin). Another said that after testing developers in between “(...) a wider user base who uses unstables see the changes right away and can also provide feedback.” (Interview #5, Jellyfin). In other words, it would seem that a cycle of testing starts with a change being made, the developers testing the change by deploying it in their home systems, then merging to the main branch and then getting feedback from the user of the most recent unstable release. Then of course, these changes eventually end up in the stable release where yet another user group gets to do a round of bug finding and reporting.

In rare cases developers have also gotten outside help when testing. One developer explains how “(...) for usability. I know we had some people reach out to their colleagues and say, ‘Hey, can you take a look at this?’” (Interview #2, Jellyfin). Additionally, domain experts have been used briefly for specialized problems such as for making sure that colorblind people could operate the software without issue (Interview #2, Jellyfin). It does also seem, with regards to getting testers on board that the project does publically say when they are needed. One developer explained how “(...) we do sort of posts like before every, before every major release saying, inviting testers to come on and test.” (Interview #6, Jellyfin). There are also examples of certain features that are heavily dependent on outside help, and the log files and feedback from users. One such example happened when “(...) We (The Jellyfin developers) apparently broke live TV, but we don't really have a lot of our, like the core developers using live TV.” (Interview #2, Jellyfin). In this case live TV functionality requires specific hardware and therefore requires users with said hardware, meaning that this feedback mechanism described above does work. However it also indicates that it does come with quite large risks such as completely breaking functionality without a single developer knowing.  

---
Discuss 
{: .label .label-green .float-right }
## Summary
<br/>
*