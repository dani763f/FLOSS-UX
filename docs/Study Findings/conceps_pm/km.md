---
layout: default
title: Knowledge Management and Platform Considerations	
has_children: false
parent: Resource and Project Management
grand_parent: Expanded Study Findings
nav_order: 3
---
Missing formatting
{: .label .label-red .float-right }
# Knowledge Management and Platform Considerations
Knowledge management is a challenge in any relatively large project, and especially in FLOSS where knowledge in many ways may make or break a project. How does the project communicate the available knowledge to the community? Is it visible what is needed at any given time? This in itself is a difficult task that is worthwhile to understand, also with a focus on design decisions.   
{: .fs-6 .fw-300 }  

---

As FLOSS projects receive and create large amounts of data such as discussion, feedback, bug reports and pull requests to name a few, how this data is stored, accessible and worked with determines a lot about what knowledge is available to the contributors in the project, and how effectively the team solves future problems. As this is a major consideration for how the project is managed several of the contributors in the projects had thoughts on the matter when asked.  

**Type/format of knowledge**|**Knowledge platform/location**|**Knowledge use and value**|**Potential knowledge management issues**
:-----:|:-----:|:-----:|:-----:
Discussions in text, back and forth|Discord, Matrix (Internal/External groups)|Provides possible ideas and acts as a rationale for changes, and future enhancement. Also contains the answers to many questions that are likely asked over and over again.|The type of data is difficult to search and easily create an overview for as it primarily exists in chat channels.
Issue reporting|Github (In Issue templates)|Acts as a centralized location for an issue. Avoids duplicate issues, while allowing for gauging the severity of the issue and its possible solution while being easily accessible. Also supports archiving bugs that might not be easily reproducible on unique hardware.|The issues might not always actually be issues, and require time to correctly label and address. Also, managing huge numbers of issues are increasingly difficult, which hurts the ability to extract useful information.
Feature requests|Fider|Acts as a larger overview of currently most wanted features. Provides an easily read, and democratic overview of the communities wishes at the given time.|Fider might not be found at first glance of the project and as such might require manual intervention from project members.
Download counts (Jellyfin)|Various app stores|The use of this data is rather limited as it only accounts for rather limited data retaining to how many users has at the very least tried or downloaded Jellyfin.|It remains clear that this is not seen as an important motivational factor in the various projects, and as such has a limited impact.

Table - Source of knowledge in the projects, the challenges involved and their importance
{: .fs-3 .fw-300 }  

A portion of these findings were specifically tied to the characteristics of the various platforms used in the project. One contributor said that “We try to avoid long pieces of feedback in chats like the Matrix rooms, because we'd like it to be archived somewhere for future references.” (Interview #1, Jellyfin). The idea of information being lost in Matrix is confirmed in that Matrix is not always as easy to search through as for instance Github.  

![Known issues example](/FLOSSUX/images/knownissues.png)  

Example of the “Known issues” pinned issue
{: .fs-3 .fw-300 }

To take feedback and troubleshooting as an example, on Github the troubleshooting steps, the current progress on a certain issue and related issues can with relative ease be found, shared or referenced. Often, if a certain issue has a fix it will likely be found in the corresponding issue as part of the discussion. This allows both project members and users to be equally aware of what major issues might be going on, even outside of their own silo of code. Furthermore, a status label will show whether or not the issue is open or closed which mitigates the creation of duplicate issues, thereby avoiding them polluting communication channels. Compared to the troubleshooting channel in the Matrix group, information is searchable however this requires quite some creativity to find exactly what a user might be looking for as the layout is chronologically linear resulting in a lot of searching for information. This is especially true given a lot of times has passed since the discussion in question was initially had, since a lot of back and forth will likely have happened since. That being said, the Matrix channels do exist for a reason. The contributor also noted “(...) that it gets confusing for everyone when discussions and legitimate issues are mixed. It creates noise for both purposes and, as such, leads to issues or discussions getting lost.” (Interview #1, Jellyfin).

With regards to Github certain things have been done to try and mitigate these issues of knowledge getting lost or being unstandardized. First and foremost issue templates are being used to standardize the required information to create an issue. Secondly, the use of the platform Fider has been made the default way to handle feature requests in Jellyfin “(...) mostly just because of the upvote system that Fider gave us as well as to try to avoid a very major, like backlog of feature requests in our issues board." (Interview #7, Jellyfin. Lastly, the new addition of “Github discussions” has been implemented into the Jellyfin project.  

![Discussion in Jellyfin-vue](/FLOSSUX/images/discussionsvue.png)  
The discussions feature on GitHub in use in Jellyfin-Vue  
{: .fs-3 .fw-300 }

The discussions tab is a relatively new feature in Github that was implemented while the interviews with the project was ongoing. The feature can be used “(...) for conversations that span across projects or repositories and don't belong in a specific issue or pull request. Instead of opening an issue in a repository to discuss an idea, you can include the entire team by having a conversation in a team discussion.” (About Team Discussions - GitHub Docs, n.d.). This feature had sparked interest in the Jellyfin project when it was still in beta, and now having implemented it the project members hope that it can help in having “(...) everything [...] be centralized in one place, which is helpful.” (Interview #5, Jellyfin). In summary it seems that this new tab in Github could serve as a place for archiving these discussions, and thereby make the knowledge readily available to all project members and users equally. Moreover, it would reduce the need for extra resources spent on managing topics opened as issues that might actually benefit from a discussion instead. These discussions are being had anyway, which is why archival and centralization is of general interest to the project.
Interestingly, the Taskcafe project has done something similar in spite of its smaller size. The founder of the project said that “One of the main reasons I made the Discord, was for a place for users to ask questions on how Taskcafe works without polluting the GitHub issues, which has worked pretty well” (Interview #3, Taskcafe). It would then, with project size in mind, make sense that Taskcafe would be able to make due with just the Discord group whereas Jellyfin’s back and forth communication could benefit from this type of centralization and archival, especially for design decisions where the rationale behind a change might not be immediately clear to another project member, user or new contributor. Even with that in mind, the developer in Taskcafe did express interest in the notion of archiving design rationale some. To being asked about whether or not he records his decision making process in designing he said that “I don't, though looking back I kind of wished I had if for no other reason than curiosity” (Interview #3, Taskcafe). In summary, it would seem that archiving discussions in a place where they are easily accessible for everyone in the project is an overall beneficial idea that is still only getting traction in Jellyfin, and might be absent in many FLOSS projects due to the ad-hoc nature of the work being done.

---
Discuss 
{: .label .label-green .float-right }
## Summary
<br/>
*