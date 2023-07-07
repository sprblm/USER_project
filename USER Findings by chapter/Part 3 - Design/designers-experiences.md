# Part 3. Design

## Designers’ experiences working with SROSS projects

### Introduction

Designers already work on open source research software, although this is not a common role. When talking to these designers, we learned about their methods to make design work in the structure of the projects, and how they manage their professional identities in a context in which design is not expected or seen as essential.

### Designers in projects often need to justify design and educate others about the need for it to get buy-in

If there are designers in teams working on Open Source Research Software, they are often tasked not only with their design work, but also with educating the team on how design is done and why it's relevant. This is needed, since design is usually a late addition to projects, after other practices, like collaboration on code, have been established. Without educational work, design would remain an activity that is not seen to be relevant in practice. 
For this, designers need to balance both making design an activity in its own right while not being perceived as threatening or opposing existing practices in the project. Designers employed different methods to do this:

- Presenting design as a “blank slate” without preconceived opinions
- Suggest design activities that do not need a lot of resources, like lightweight usability testing of existing ideas
- Demonstrating the usefulness of design in the context of an ongoing project
- Getting involved in existing discussions rather than opening up new ones

All these methods involve being not threatening and working in existing structures to build small wins that demonstrate that design can be a helpful contribution. 

Designers also tried to manage their identity and distanced themselves from values and activities which are seen as “bad ‘in open source projects: “Polishing” (iterating in small steps with strong care for details), “superficiality” (strong care for immediate visual aesthetics), “maximizing clicks” (tracking user actions and compare them to goals) are such activities do distance oneself from. 

Still, many struggled with achieving a mutual understanding. Designers wished for a “common language” which they tried to work towards by explaining terminology and educating team members. However, even shared terms did not necessarily translate into a lived design practice when working on the software.

Ideas about open source development and the design process can easily come into conflict. Design, with its abstractions and explicit negotiations is thought to happen before building software, as a participant said they *“…needed to educate about design as a step in the process before you start building things”.* This can be at odds with a code-focussed culture in open sources software: *“…it was also a learning process for me to understand that this open source community won't do what the designer tells them to do, they'll just do whatever they want to do.…they will try to build that feature, that feature will not look like the prototypes look, but they will be there.”*

Despite their strategy to be non threatening to existing conventions, designers also tried to advocate to allocate resources to design work. Designers can’t cast their design into code themselves and thus need to secure support from developers. As one designer said: *“I have to, like, lobby if I want people to do design work that they're not already working on.”* However, with many other tasks that developers can do and find urgent, it is often difficult to get the design-related work done and convince others to prioritize it: *“…I don't think that they think it's valueless, but it's definitely not important enough to, like, plan around or to like, take action on.”* The reason for not focussing on design was usually framed as either a constraint of “time” or “resources”. 

### Late introduction of design often needs risky and resource-intensive changes

Improvements to design need code changes, and changing or adding code can lead to ripple effects that influence other functions which then also need code changes. 

Two people directly framed larger design changes as leading to *“rebuilding the entire project”* or the project *“[needing] a complete overhaul”*, for which *“the potential cost / risk is humungous”*. Even if the needed changes would not be as absolute as stated here, the trade-off still applies: “It still works” and thus there is the question if it is beneficial to change and worth the change of established structures for an uncertain future. The prospect of finding out that such a large change is needed might be unsettling for a project. As a participant suggested: *“They probably want feedback on how to make their product better,”* but *“[might be a] little concerned to find out that there are major usability issues associated with it that will take a huge amount of unwinding and refactoring to resolve.”* and thus don’t engage with questions of design. 

When projects were built around initial concerns of developers or scientists, their code is geared towards the changes that designers suggest. Thus, the designer’s suggestion might mandate larger changes to the code. Such deep changes to code of projects need a lot of effort and thus are seen as “too big/too late to fix” in many cases.

Such big changes are particularly difficult in an open-source mode of working: They need overarching changes which are, by definition, hard to do in a modular way. Yet working on isolated parts of the code makes it possible for single developers to collaborate efficiently. 

An in-depth code change might also affect the existing community of users who are largely fine with the state of the software. The existing community of users gathered around how the software currently works. Doing substantial changes might lead to complaints or even anger of existing community members. As described in the section on “knowing users”, projects know the users who engage a lot with the project and write on mailing lists and issue trackers. These users already can use the software and would be affected by deeper changes that do not benefit them in the short term but actually might upset their workflows.

### Conclusion

Designers in open source research software projects struggle to get buy-in for their suggestions– and with that also have troubles to legitimize themselves and their role. Often, a designer role seems to have been a concern introduced late in ongoing projects—if at all. This means technological and cultural structures that have grown established over years do not cater to designerly concerns. A designer can easily be seen as causing problems as their concerns might disrupt processes that have been working well for years in the past. Thus, when entering the existing structures derived from cultures of research and open source software, their main approach is to be non-threatening to existing concerns and practices, to demonstrate the value of design and to work towards a “common language” for mutual understanding. Despite these efforts, for many it remains difficult to reconcile design work with their project's practices.

Designerly concerns might also be hard to integrate into long-grown code structures that cater to needs of deeply engaged experts or coders. Code changes to cater towards the concerns of designers can be large and thus might be a risky investment of time or break compatibility with previous versions of the software. In addition, the existing community which is best known by the project’s creators does often not benefit a lot as they gather around the software as-it-is and thus can cope with the state of things, but might have workflows that would be upset by changes. 

**Our recommendation/s:**

- **Expect challenges:** Introducing a design role in an established open source research software project is not trivial for the project in general and for the designer in particular.
- **Collaborate closely and clarify expectations:** As mutual understanding and a common language is a strong concern, projects who introduce a design role should plan for close collaborative work between roles, including time and activities to clarify mutual expectations and needs.
- **Plan for code changes:** Improvements in design usually need changes in code. This means that a designer can’t be just added to an ongoing project in the assumption that they will provide a layer of design on top of whatever is currently done.

