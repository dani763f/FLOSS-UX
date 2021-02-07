---
layout: default
title: Current resource intensive tasks and goals
has_children: false
parent: Resource and Project Management
grand_parent: Expanded Study Findings
nav_order: 2
---

# Current resource intensive tasks and goals
Change title
{: .label .label-red .float-right }

Another consideration that emerged from the findings was that a project's history will affect its resource allocation and focus, especially in what could be considered the early life of the project. A difference can be seen between Taskcafe and Jellyfin with this in mind. Jellyfin has inherited a lot of code from Emby that still is a major challenge to fully document, understand and update. Even though the project size is vastly different between the two as well, it does seem like this notion would hold true for most projects. Several contributors in Jellyfin voices their opinion that for instance the underlying database had been an issue since day one (Interview #2 and #7, Jellyfin). Even those who did not mention the database specifically mentioned and verified that the legacy code is currently the largest overarching project in the project (interview #8, Jellyfin). This notion also holds true for design elements. One participant noted that “(...) "Unlike the new client, where we're building everything from the ground up, the old client has still all the design aesthetics that we inherited from Emby.” (Interview #5, Jellyfin). This will no doubt limit the options of the developers with regards to improving the user experience and might also be limiting their own ideas for design as they are provided a high fidelity design aesthetic to improve upon. 
Taskcafe which is a completely new project does not suffer from this, and has as a product never been in the maintenance and repair phase that Jellyfin is facing. This finding seems to verify the importance of having discussions about the choice of legacy code, and it's inevitable impact on how easy it is for new contributors to join the project and for adding new features. This especially rings true for design contributions that might not necessarily contemplate the situation in the underlying code, and as a result might be considered a change too difficult to implement or consider. With the above in mind it can be seen how the founder of Taskcafe has the freedom to completely overhaul the user interface between releases as a product of iteration. When asked what exactly had changed, the developer from Taskcafe said that “The entire app ‘shell’ has changed from the original design” (Interview #3, Taskcafe).

In summary, it would seem that whether or not a project is a fork of another project determines the need for good documentation as for instance Jellyfin focused on by documenting the API (Interview #2, Jellyfin). Without the necessary documentation and understanding of the inherited code, getting support from new contributors is increasingly more difficult as a lot of time has to be spent reverse engineering the code base. In addition, any possible design contributions or discussions had in a project state where general maintenance is the current goal will likely impose on what is currently possible with regards to the backend.
