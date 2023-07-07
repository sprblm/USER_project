# Part 3. Design

## Design Practices and Workflows: How do SROSS without specific design capacity practice “design”? 

### Projects' openness to design depends upon how they think of the impact and usefulness of new features being implemented.

When projects discussed how they approach incorporating design work into the maintenance of their software, many, understandably, spoke to a principle interest in the relevance and usefulness of the improvements. Some projects are concerned with prioritizing design and new feature work that will be more welcoming to a wider range of users and contributors, while others are more interested in the efficiency and relevance of the proposed update to the existing user community.

This ranged from assessments that presented as a kind of cost/benefit analysis, to concern that an improvement would markedly improve a user or contributor’s experience with the tool. These considerations have significant overlap with the governance and prioritization models that projects employ, as deciding upon scope and relevance in OS projects often falls back on how decisions are made in the project at large.

*“There's a bunch of these kinds of things where it's like, trying to get a new API through means convincing people like there is a reason why we should add this new function and add this new test…And that means that we have to convince people this is actually going to be useful.”*

### Projects use various systems to track and complete design work; some integrate more “typical” design workflows, while others utilize tracking systems like Github that mirror how they handle technical issues. 

Following the fact that very few projects have trained UX/UI designers on staff, few projects referred to use of more expected design processes, like sharing prototypes and feedback on prototypes, unless they had a designer on staff or in a consulting role. More often, projects referred to having text-based conversations about design issues in community channels like Discord or in Github. These projects said that they handle design issues as they do technical issues, using voting systems and replies to track relevance and status updates. 

Design issues are often competing for developers’ time with perceived “critical” feature implementation or basic software functionality, often without agreed processes for handover collaboration processes between designers and developers. Few projects mentioned paying specific attention when prioritizing issues to design concerns. Some were intentional about making sure there is adequate time and thought allotted for critical design choices, and these projects were those who acknowledged that it is easy for design work to be overlooked or “missed.” 

### Most commonly, maintainers in SROSS projects understand design as a feature of their codebase itself: how can they make the software as easily maintained/contributed to as possible? Critically, some such maintainers practice the same concept but don’t understand it as “design work.”

*“Design means making sure you have what we call clean code, so making sure that the code is readable, the code conforms to best practices.”*

Many programmers who maintain these projects are understandably most familiar and concerned with the design of their codebase. Logically, to them, “doing design” in their project means *“structuring your software in a way that others and your future self can understand and build on and work with.”* Not only is this good for the tool and those working on it, but doing a good job at code design has an added bonus of making your project more appealing to potential contributors. These efforts help make projects “more welcoming” when potential contributors can understand the code and find the information they need to make contribution decisions. So while we may call these efforts a kind of usability practice for code contributors, few if any developers used the word “usability” to describe their code work. Many did, however, call these practices their “design” work. Outside of the code itself, participants referenced documentation as a critical aspect of this pipeline.

### While software design is a critical piece of design work undertaken by these projects, too much of a focus on the user-as-fellow-programmer can obscure the utility of UX/UI and broader usability work within SROSS projects.

*“There are users and then there are developer-users that are then maintainer-users, and then contributor users. And I think a lot about the different overlapping user types of open source.”*

Participants were clear that the concepts of usability and design within these projects are slippery, especially when users can also be contributors, and some (but not all) also have similar technical proficiencies to the maintainers. While we heard a lot about projects needing to improve language barriers between disciplines, users and developers, and designers and maintainers, there is also an interesting phenomenon that occurs when many of the users, contributors, and maintainers do “speak the same language”: how can SROSS projects develop an understanding of the nuances between the design of the code and how users interact with the software – even when there is overlap between those two categories?

One designer who works with these types of projects shared that they felt there is a “misconception that” what they do “is software design,” when their practice doesn’t involve the code design at all. On the other hand, some maintainers are actively trying to bridge the gap between code design and more typical UI design. One project maintainer shared that they’re interested in building a GUI for their project to increase usability for people who don’t know how to code. In the meantime, they are choosing to structure the code in a way that almost looks like a GUI. This person explained that they *“tried to picture what people will need as far as inputs and how to structure the configuration files for our software”* and chose to structure *“input files in a way that almost looks like a GUI, where it's like, here's an item, here's an item, here's an item.”* In a way, this maintainer is trying to create a GUI-like experience for users of their command-line dependent project.

**Our recommendation/s:**

- **Designers valuing academic processes:** How can we view 'peer review' 'replicability' and community discussion as critical to design and user-centered design work?

