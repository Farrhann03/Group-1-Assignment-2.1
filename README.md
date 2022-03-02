# Group-1-Assignment-2.1

Group discussion 2.1

Group members:
Yvonne
Daniel Tan
Alex
Amy
Farhan

# GIT & CLI: Assignment

## Brief

This is a research assignment where students will be given time for research and put into group for discussion.

Version control tools are plenty and have wide range of practices. This research assignment aims to help learners expand their choice of version control tools (Part 1) and being acquainted with the branching strategies best practices in the industry (Part 2).

| Time    | Item          |
| ------- | ------------- |
| 40 mins | Self readings |
| 10 mins | Q&A           |
| 10 mins | Break         |
| 30 mins | Discussion    |
| 30 mins | Presentation  |

Group 1 (Flappy team)
Team members 
- Alex
- Yvonne
- Amy 
- Daniel
- Farhan

### Part 1

Problem Statement: GIT is not the only version control tool in the industry.

[Reference Link](https://www.softwaretestinghelp.com/version-control-software/) or search online with key word "Version Control Tool".

Discussion Points:

1. What are the version control tools used in the industry?

- Git
- CVS
- SVN
- Mercurial
- Monotone
- Bazaar
- TFS
- VSTS
- Perforce Helix Core
- IBM Rational ClearCase
- Revision Control System
- Visual SourceSafe (VSS)
- CA Harvest Software Change Manager
- PVCS
- darcs

1. Why are they being used?

- Version control is important to keep track of changes — and keep every team member working on the right version. You should use version control software for all code, files, and assets that multiple team members will collaborate on.

It needs to do more than just manage and track files.

### Part 2

Problem Statement: Branching strategy varies largely across companies’ practices and there are not fixed way of doing this.

Reference Links:

- https://launchdarkly.com/blog/git-branching-strategies-vs-trunk-based-development/
- https://www.gitkraken.com/learn/git/best-practices/git-branch-strategy
- https://www.creativebloq.com/web-design/choose-right-git-branching-strategy-121518344


Discussion Points:

1. How many branching strategies are there? What are they?

- Master // Main
- Feature branch // Topic branch
- Release branch
- Hotfix branch
- Develop branch // Integration branch

- A way for a team to write, merge and ship code in the context of a version control system for example like Git.


1. Which branching strategy looks the most practical for you personally?

- Feature branch seems the most practical to me personally if working in a smaller group cause there's not much opened branches before merging everything.

1. Consider the following scenarios, recommend a branching strategy suitable for the scenario, and explain why?
   a. Startup with less than 5 developers
   - Hotfix branch, is easier to control since there are lesser team members and it's easier to manage the pushes within the group.
     b. Startup with multiple small team of developers (3 teams of 3 developers)
   - Develop branch, having a develop branch will ease the control within the teams before actually pushing it to the main/master branch.
     c. Startup with no specific team make up. It’s just a group of 8 developers.
   - Feature branch, it will be easier to manage the number of pushes from the number of developers directly to main before merging everything together.
     d. SME with multiple small team of developers (4 teams of 3 developers)
   - Develop branch, likewise to 3 teams of 3 developers, having a develop branch will be easier to a manage the developers code before merging to main.
     e. MNC & Banking with multiple large team of developers (10 teams of 12 developers)
   - Release branch, due to the amount of teams and members having a secondary develop branch before even merging to main makes it easier to control and manage code.


