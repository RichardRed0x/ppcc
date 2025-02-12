---
title: "FOSS Governance"
date: 2019-09-11T12:26:15Z
draft: false
weight: 60
description: ""
---
![](/foss-governance.jpg)

The defining feature of FOSS governance is the fact that the product is **commons-based and equally accessible to all parties**. There is relatively little friction involved in forking a codebase and taking two versions of a piece of software in different directions. The ownership of Intellectual Property (IP), which determines who is allowed to develop and exploit proprietary software, has only limited significance. In FOSS projects IP considerations are typically limited to the ownership of non-vital assets such as names/trademarks, domains and hosting services (i.e. control of servers and GitHub maintainer accounts).

FOSS governance is archetypally a case of a group of developers communicating and coordinating informally following "[rough consensus](https://en.wikipedia.org/wiki/Rough_consensus)". In some studies of the top 25 GitHub repositories (by star count) from [2016](https://livablesoftware.com/transparency-democracy-open-source-not-thought/)[^1] only one explained how its governance worked in any detail, with 62% saying nothing at all about this. In [2018](https://opensource.com/open-organization/18/4/new-governance-model-research) [^2]the same method was replicated and 5 projects were found to explain their governance processes, and there was a greater tendency to offer a document which was tailored to onboarding new contributors - but still many projects had no description of their governance processes whatsoever. 

Governance tends to be an afterthought for FOSS projects, as it only becomes a significant issue if the project reaches a certain scale. When the number of participants is small and everyone knows everyone else, conflict is easier to manage. Most FOSS projects never reach a scale where the lack of formal governance causes any problems.

There is a cost to implementing (and documenting) formal governance, and so informal governance is likely much more efficient for small projects. When a project reaches a scale where it is more likely to have unresolved contentious issues, it is also more difficult to add in a new form of governance, because doing so with legitimacy would require buy-in from all existing participants. One natural way for informal governance to scale is by effectively nominating whoever holds the most sway in the process as a "[benevolent dictator for life](https://en.wikipedia.org/wiki/Benevolent_dictator_for_life)" - being acknowledged by participants as someone who has the personal authority, usually based on respect earned from their contributions, to dictate the resolution of contentious issues.

In the case of unresolved contentious issues within a FOSS community, the lack of a strong barrier to forking means that it happens fairly regularly. Given that all the code for both forks will remain open source, a fork doesn't have to mean the end of collaboration between the two groups. Beneficial changes can be pulled in from the other fork(s) - although doing so can involve considerable effort. In particular, where the project that was forked from is large and active, keeping up with the changes as a "downstream" fork can be difficult. This [piece on the history of Debian and Ubuntu](https://mako.cc/writing/to_fork_or_not_to_fork.html)[^3] by Benjamin Mako Hill affirms that it is best where possible to avoid a fork because of the increased coordination costs and possible duplication of effort. Hill recognizes significant benefits to forking in the degree of customization it offers, with software "one size never fits all" and with FOSS the capacity to adapt and hone it for a particular use is one of its strengths. Mako Hill calls for better tools to facilitate ongoing relationships between forks.

For most FOSS projects, governance is minimized because most of the volunteer participants in the project do not want to spend their time engaging in lengthy discussions. For maintainers of a project making group decisions about its future is part of the more general task of coordinating contributions, which can become burdensome for projects with many contributors. 

## References

[^1]: Cabot, J. (2016, January 15). *Transparency and Democracy in open source: Not what you thought*. Livable Software. https://livablesoftware.com/transparency-democracy-open-source-not-thought/
[^2]: Canovas, J. (2018) *Projects that make their rules explicit would see more participation*. Opensource.Com.  https://opensource.com/open-organization/18/4/new-governance-model-research
[^3]: Hill, B. M. (2005). *To Fork or Not To Fork: Lessons From Ubuntu and Debian: Benjamin Mako Hill*.  https://mako.cc/writing/to_fork_or_not_to_fork.html