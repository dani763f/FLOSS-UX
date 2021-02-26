---
layout: default
title: Iterations and prototyping
has_children: false
parent: Design Methodology
grand_parent: Expanded Study Findings
nav_order: 3
---
Missing content, requires image formatting
{: .label .label-red .float-right }
# Iterations and prototyping
Introduction here
{: .fs-6 .fw-300 }

---

With regards to how these projects handle reiteration and prototyping, some structure have been discovered in the two projects. While the projects largely make it seem like there are no structured prototyping methods in place, and that no agreed upon methodology is in use with regards to for instance mockups some structured activities do already take place. Jellyfin’s primary way of informing design decisions seems to be by using existing design as inspirational material. This way of informing design was also mentioned by the developer from Taskcafe when he said that he “(...) research the different way others have designed similar components” (Interview #3, Taskcafe). The way this is structured in Jellyfin is mostly by using pinned issues that contain a large amount of inspirational material such as screenshots or video examples from popular media platforms such as Netflix, Disney+ or Amazon Prime.  

![Design references](/FLOSS-UX/images/prototype_examples.png)  

> *Figure - The UI & UX reference pinned issue in jellyfin-web with an example from Disney+*  

This way of working shows that the project sees the need for keeping such design references stored and accessible in an organized way, however this requires using the GitHub issue functionality in an unintended way. In other words, this way of working supports the idea that GitHub as a platform could be more powerful in certain ways as confirmed by many of the developers (Interview #7, #3, #5). As mentioned earlier, the GitHub discussions module is a new addition to the project that seeks to solve some of these issues. With the above way of working it does look like the intended use of the discussions module would solve some of these roundabout ways of working with GitHub.
One such way would be to record design rationale and foster discussions surround design as proposed by some of the developers (Interview #1, #6). From a methodological standpoint, it would seem that the new Vue client is spearheading this new design centric way of working. Here, the developers already are proposing design changes, while presenting reasons and ideas for the change, while providing screenshots to show before and after the change has been implemented. It does seem however as this is a very new way of working that some people are yet to discover the functionality and its use as seen when one user commented “I wasn't aware of these ‘discussion’ areas of Github. This is good.” (Jellyfin-Vue - ‘Lazy Loading #272’, n.d.). Additionally, it seems that not every design issue is being had here, as some still exist in the issues tab, which seems to suggest that the definition of what constitutes a discussion rather than an issue is still not clearly defined in the project.  

![Examples of Discussion](/FLOSS-UX/images/discussion_examples.png)  

> *Figure XX - Example of design issues being discussed both in issues (right) and discussions (left)*  

In summary, structured activities are already taking place in the Jellyfin project, however it does seem that jellyfin-vue is the testing ground for this new way of working and that adoption is still something that is being worked out as what constitutes a discussion or an issue is being worked out between the contributors.  

---
Discuss 
{: .label .label-green .float-right }
## Summary
<br/>
* Developers are quick to discount their own inititives when it comes to prototypes and the testing of them.
* The most used methodology that spans both of the surveyed projects, is using and compiling inspiration from established proprietary or FLOSS solutions that serve a similar purpose.
* Most of the current ways of gathering inspiration relies on using GitHub functionality in unintended ways.  
