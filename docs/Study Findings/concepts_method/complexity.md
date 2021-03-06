---
layout: default
title: Complexity of design in FOSS projects
has_children: false
parent: Design Methodology
grand_parent: Expanded Study Findings
nav_order: 4
---
Missing formatting and introduction
{: .label .label-red .float-right }
# Complexity of design in FOSS projects
Introduction here
{: .fs-6 .fw-300 }
---

At this point the methodology of these FLOSS projects are largely uncovered and it seems that while many findings have emerged with regards to how they perceive, approach and implement design changes there still are some concepts that live in the seam between perception and methodology. Namely, if there is any perceived and methodological difference in how FLOSS projects approach design as a whole with regards to the inherent complexity of design work. One example that could support the idea that maybe design work is just inherently more complex to approach and requires more planning is specified by a project member when specifies that “(...) "People usually don't report them (design and usability issues) enough, unless they're really egregious. So it's harder to keep track of in the sense that it happens less often, so we might have some that we don't know." (Interview #1, Jellyfin). In other words, the issues themselves might be harder to report as they might strictly be thought about as “enhancement” rather than an issue. Compared to for instance backend issues that very often are very clearly defined problems where a certain unit within a program fails or otherwise needs fixing to allow a certain use, design is more defined by the individuals existing knowledge and preferred approach to a certain task. As it has already been uncovered that both knowledge and subjectivity are factors that are present in the projects the again seems to lend credence to the idea that design issues might be harder to approach, and in this case report resulting in an uneven balance of reporting for design related issues.
As mentioned above, there is also an inherent “solution mindset” in the FLOSS projects. With the above paragraphs in mind, it would seem that few design issues that are raised are equally hard to gauge, and as such the complexity of these design issues are once again confirmed. One of the developers explained it as “(...) people generally try to provide solutions instead of explaining the issue at hand. It makes it harder for us to understand their issue and decide if their solution is really suitable or if it would be another issue in itself.” (Interview #1, Jellyfin). Explained this way, it would seem that compared to, for instance, backend reporting design does involve a certain complexity and need for discussion and planning that might not be similar anywhere else in the projects.

These considerations are in themselves complex in that it seems like a paradox exists with regard to design, between what is thought and done. One one hand the developers recognize the value and importance of design decisions and admit that they often take a low priority in FLOSS generally speaking. However, as shown with regards to their design methodology it seems that they do have a number of initiatives that take place that seem to align with processes normally associated with industry design best-practices. This suggests that a worthwhile exercise would be, as already mentioned by project members, to increase the amount of discussions being had surrounding design in general. Something that has already started in the jellyfin-vue repository but has yet to spread to the rest of the repositories and largely FLOSS in general. Through the use of frameworks that support having design front and center when developing, such as the Vue framework, some of these concerns are mitigated and as a result “(...) the choice becomes how you combine them (design elements) together rather than how you like deal with what a button should look like” (Interview #7, Jellyfin). With this initiative being taken in the jellyfin-vue repository it appears that the project is trying to move the discussions being had to a higher level, and avoid the smaller UI specific discussions that in this case is largely mitigated through the use of Vue and Vuetify. In other words, the efforts to address the complexity of design through discussion is well under way, in some cases unbeknownst to the developers themselves.  

---
Discuss 
{: .label .label-green .float-right }
## Summary
<br/>
*