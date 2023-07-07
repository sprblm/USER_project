# Part 2: Project Operations

## Feedback and Knowing your Users

### Introduction

Projects learn about users’ needs via online and in-person venues where both creators and developers gather already, such as forums, issue trackers, and conferences. Rarely, there were mentions of formal methods like usability testing or surveys which are also used by user experience professionals. This way of learning about users is direct and easy to integrate, but might also lead to only knowing about specific parts of user communities.

### User Experience methods are rarely used

Methods that user experience professionals use are often derived from psychology or anthropology. With these methods, professionals derive results like a report, slide decks and archetypal representations of situations (use-cases and scenarios) or users (personas, target groups). If a project follows a formal process for knowing users, these results are passed on from specialized user researchers to designers and managers. Even for professional designers, these formal processes are an idealization: Practice is messier. However, user experience design professionals know how they would like their process to look like. They also emphasize the importance of a professional distance from users: “You [the designer/researcher/dev] are not the user” is a slogan.
In our research, some projects used such formal methods, however, they were in a clear minority. The two methods that are used to get to know users are surveys and usability tests. Seven of our participants mentioned using surveys to learn about their users. How the surveys were seen was varied: “we've tried running surveys, but I think they haven't, like massively worked…” Two participants regularly conducted surveys - one of them likening them to a census - but neither stated what decisions came out of the results.

Usability tests were the other formal method that was mentioned. In a usability test, people are asked to do tasks.The person leading the test makes notes or records their actions, particularly when people get stuck or experience other problems. The test is done with several participants to see if problems repeat. Three people mentioned doing usability tests; one of them talked in depth about tests and seemed to strive to have a process that would be seen as “good” by user experience professionals. However, even that person mentioned that many tests are makeshift and use easily available testers like students, a practice UX professionals call “Guerilla Testing,” methods that are also used by professionals, but are not seen as the ideal way to test software.

### Developers know “the community” directly, not through research and abstractions.

To learn about their users, projects rarely use methods of UX professionals, but other means that do not generate abstract representations but allow to relate to users in a direct way by communication:  Calls, training and conferences as well as web forums, email, issue trackers and online chats.

All these communication methods are also used by software developers for writing software and participating in internet communities.They are thus not means of communicating with the users exclusively. In these online  communities, there are different roles and capabilities: Users who are co-developers are rare, but often  there are engaged users that know the software well. They try to figure out how to use the software, and if they are unable to do so due to limitations of the software, they voice their needs to the developers via different channels. 

There is a strong focus on what people on these channels say they need. As one interview participant said:
*“[we] see ourselves essentially having like a set of stakeholders, as opposed to necessarily [a] set of users. So we have some users that are people that just want to do something, right, they want to do some science, they want to do some research and, and the system, the software that we build may enable them to do that.”*

The “community need” was the strongest pressure on software development in our survey, even slightly larger than the obvious “research need.”

![chart-what-other-pressures-drive-your-projects-work](https://assets.digitalocean.com/articles/alligator/boo.svg "chart-what-other-pressures-drive-your-projects-work")


### Communication channels are structured around the activities of developers

Of the different communication channels used, the closest to the software development are issue trackers. An issue tracker is an online platform, where problems can be described, listed and assigned to developers to work on a bug or feature. Since they are a vital part of coordinating software development, they are integrated in developer-focussed platforms like github. Software users might create issues directly.  Sometimes,  project members also translate mails or forum posts into an issue on their platform and thus make it more likely to influence the software itself.  That this translation happens also points to the fact that writing issues is a skill that people might need to learn, as one participant pointed out: Not all ways to write about a problem lead to a “good” issue. 

Other means of communicating are less development-centric. E-Mail, forum software like discourse and chat groups are common tools of web-based communities in general.Users post problems there or help other users of the software  solve their problems. Some of the tools used have been around a long time (like mailing lists) and others are newer (like discourse or slack.) These tools are probably more accessible to users without socialization in open source software communities. 

Working in web-based communities does not exclude face-to-face communication. Synchronous communication opportunities include: 

- Software training allows users to meet project teams in person. 
- Conferences help project members learn how people use the software in their research and to socialize. 
- Regular calls allow for remote but synchronous communication with users. 

This means that people in the peripheral community of users will usually not be heard. For the users at the center of the software development community, these modes of dialogue are natural. For peripheral or less-technical users, these modes might seem hard to understand or inconvenient – if they know of them at all. 

### Knowing users directly: Quantitative evidence

The pattern of knowing users but not using formal methods or designating separate roles for design also shows in our quantitative data:.

Only few projects mentioned thew worked with UX/UI designers:

![has-your-team-ever-included-a-designer](https://assets.digitalocean.com/articles/alligator/boo.svg "has-your-team-ever-included-a-designer") 

This matches our observation that most projects did not use methods of UX professionals to get to know their users. “Knowing users well” for UX professionals usually implies a process of research: conducting data via interviews, observations, and surveys. They synthesize this data and create formal abstractions like “personas”, “scenarios” or “user journeys”, genres of documents that summarize what they learned about users. None of our projects had such research and representations. If at all, they used low-resource methods of testing existing parts of the software.

However, despite usually not having a single project member tasked with learning about users, most projects had the impression they know their users well. Not a single participant in our survey answered “No” to the question: “Do you feel you have a good sense of who the users of your project are?” 

![do-you-have-a-good-sense-of-who-the-users-of-your-project-are](https://assets.digitalocean.com/articles/alligator/boo.svg "do-you-have-a-good-sense-of-who-the-users-of-your-project-are")

### Conclusion

The idea of what it means to “know users” is very different between UX professionals and Open Source research software creators: Getting to know the user via tools that were used anyway as part of software development and online communities was far wider spread than the methods of UX professionals.

Knowing the user by means of direct communication and as part of the community of users has several advantages over the abstracted methods of UX professionals.The typical OS research software interactions with users:
- are ongoing, 
- not bound to a specific functional role,
- does not depend on formal abstractions

However, the direct way of knowing users also has its shortcomings. Most importantly, these methods only allow for knowing users that are close enough to the project, have the time to be active in forums, on github, or even go to a conference. Being part of “the community”, the users visible to developers of open source research software, takes time and resources. Thus, the methods to know users might have a bias towards the most active and privileged users, whereas beginners or people with little time or money at their hands might never be known to the people creating the software. 


**Our recommendation/s:**
- **Expect existing, direct ways to know users:** It is likely that developers in a project know their very active users well despite not using formal user research methods but direct communication.
- **Participate in existing community spaces:** Active users and developers will often communicate via mailing lists, community forums and open community calls. Participate to understand how the community works.
- **Use UX methods to represent a wider community of users:** Direct methods of communication often only represent the most active community members. UX methods can help to understand beginners, occasional users and users who do not have time and resources to participate.

