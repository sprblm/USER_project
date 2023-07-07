# Part 2: Project Operations

## Onboarding

### Introduction; What is onboarding, why it is important and what it typically looks like broadly in OSS projects

Onboarding most commonly refers to the intentional structuring of the first interactions that a user has with a tool, service or product. These can broadly include tutorials, guided exploration of the tool, documentation, videos, in-person guidance or annotated screens in the tool that instruct the user regarding functions and locations of information or operations. Onboarding can also be unintentional and therefore, not structured in any particular way other than what was arbitrarily chosen as the ‘first interactions’ crafted, written or built by the calibrator of the tool. 

Regardless of intentional or unintentional onboarding structure, ‘onboarding’ is commonly known as the first interactions and impressions a user has with a tool. Onboarding is touted as a ‘make or break’ part of a user’s relationship to a tool and commercial tools prioritize ‘good’ onboarding experiences. In the commercial world a ‘bad’ onboarding experience could drive users to competing tools and directly lead to lack of income or market share for that tool. Onboarding in open source software broadly isn’t well written about and centers historically on documentation such as ‘installation/setup’ and any supplementary documentation or guides on running the OSS locally for your intended user purpose e.g. processing data. The implicit ‘standards’ of OSS onboarding could include making disparate connected tools/packages simpler to install by combining them into one package or by relying on the user’s knowledge and proficiency in asking questions towards the project maintainers or other wider community members when they run into problems while onboarding and perhaps the most colloquially common method, reading and following the documentation and through trial and error, successfully using the tool.

### Science and Research OSS projects currently value onboarding methods and practices that are in and of the community as opposed to a ‘designed’ onboarding process that is in-situ in the tool

From our research we noted 10+ different interpretations of onboarding. These interpretations largely focussed on some standard way that OSS projects express expectations of onboarding. 

These shared ways of onboarding included:
- *“An ecosystem of resources depending on what you're using the tool for”* A designer from a large cross disciplinary documentation project detailed. *“Communities develop tutorials by themselves for their specific domains. The carpentries independently developed a course. “that's how we've got our onboarding, it's really, each communities onto their own develops a little cluster, journalists got a little cluster also of training, and so on, and the work within their community”* stated a coder at a data storage and transformation project as well as describing both informal video call onboarding tutorials and chats as well as running workshops in the style of carpentries.1 
- A co-lead researcher on a citizen science project expands on the pipeline of ‘onboarding’ to ‘contributor' more clearly by stating that long, time intensive processes of onboarding might not allow for certain users to become contributors. *“We try to avoid having the problem of having people to really onboard them in like a long winded process, because then we will just not get anyone to participate as volunteers. So we try at least to our best to design things in a way that people can onboard themselves in that there's enough how to materials and that it's easy enough to follow along the process that people can learn it quite easily by themselves.”*

This connects to a common way that general OSS invites new contributors through testing and improving the experience of ‘getting started’ as its a process that all users and contributors will likely go through, has variations on the experiences that values difference and inclusion as well as being an accessible topic, ‘being new’ for contributors to expand on.

As included in our Feedback and Knowing your Users chapter, SROSS projects find community convening a multi-beneficial practice in which they can address onboarding, accessibility and usability concerns as well as gather information on how to improve onboarding, connect other with community members that will onboard others or have already created onboarding resources and subsequently build a healthy contributor community ecosystem.


### Onboarding is considered good by default if no user ‘complaints’ are logged. This perspective only comes into question when there is a previously ‘unknown’ researcher specific usage problem with the tool is raised.

Science and Research OSS projects assume that, a 'good onboarding' experience means that users will not have problems using their tool until later in their usage pattern (as early as 1 week later) when the users will typically raise more specific problems related to their own specific research use case using a method of communication available to them (email, issue creation, community call, conversation at event etc.). This places users in an uncertain onboarding space, where they are no longer completely new to the SROSS tool and can operate it in a basic way, yet they may increasingly have specific user problems when trying to achieve the specific needs of their own research utilizing the SROSS tool.

A solo developer maintainer for an audio processing OSS tool stated:
*“Went through tutorial - was easy and people are citing and using it in paper after some kind of tutorial - 1 day to a week and come back with a specific need - not that they aren’t productive.”*
This version of ‘good’ for onboarding doesn’t take into account a critical component discovered in our research, when the user of an OSS tool moves from ‘getting started’ with basic operations and processes through to a research-specific and potentially unique, new way of using or manipulating the OSS tool. This understanding of ‘good onboarding’ appears to be unmeasured by the project and more of a ‘hunch’ they get from the user patterns - where our data suggests that there are multiple factors involved with users 'persevering’ through an onboarding experience depending on how critical that OSS may be to their own academic or research goals. There are 2 key data points we discovered to support this:

1. The OSS tool may be the only OSS tool open and available or ‘sanctioned’ by the research institution for a researcher's type of study.
2. The OSS may be taught within a course or module and therefore apply to a grade for the researcher.

### Onboarding is difficult or impossible to standardize across science and research OSS tools or by science/research domain in a specific tool due to the unique single-user specific ways that scientists and researchers use an OSS tool for their work.

Once the initial part of onboarding has been experienced, users tend to transition into the specific use case where users either have a unique kind of research topic or process that is using the OSS to explore, or the user is a unique kind of user with specific access needs. 
A co-lead researcher on a citizen science project details the specifics of designing for ‘autistic people’ which is so broad that onboarding can only be anticipated and designed up until a point where then the most appropriate response is for the user to document and contribute their own experiences and resources back to the project so that those experiences might be of use to a similar user in the future.
*“We do see that depending on on the autistic person, they might need some onboarding and that it's really hard to actually design it so that it's easily usable by by every autistic person, let's say in some cases, we found very conflicting wishes of what people would like and it's very hard to account for all of those as often they are like they are diametrically opposed: Some people want it like this, and others want it like that. So somehow we need to agree collectively with the community we are working with, like what's, what's the compromise we make? And sometimes there's maybe no compromise possible.”*

Another participant explains that particular projects will have specific needs that are uniquely theirs and that the ‘builders and maintainers’ of the OSS cannot know this ahead of time. *“For newcomers it requires training. Not training on how to use it. To operate the system is simple, but we don’t know the blueprint — how the system is set up for your particular project is what needs to be made”*

This speaks to an implicit tension communicated by users of science and research software raised which is that their goals and responsibility is to their research purpose, the OSS they use, while valued, are largely to achieve a certain aim or process in the larger academic pursuit of publishing, citations and stability in academia for that individual researcher. It’s understandable that these users as they onboard generally are seeking a specific, unique need for their research goals that the OSS needs to facilitate in the timeframe and effort level that that individual researcher deems as satisfactory.

A developer working on an OSS microbiome bioinformatics platform mentions here that the community focuses on understanding their specific field.

*“This community of people who are working towards some more goals, which is understanding microbiomes and how they impact health in the world. Right.”*

And a developer for a Python based tool speaks to wanting to help researchers focus on research and not code, coming from their own experience.
*“I'm no longer a scientist, right. But I understand how their time is valuable and how hard it is for them to focus on their science. So my goal, as a former scientist, who does code now is to take the code out of the way, like, you don't have to worry about this hurdle of learning, programming and learning how to solve your problem.”*

### Onboarding can be the ‘responsibility’ of professors, peers and universities if that OSS tool is an essential part of an academics course or research

In certain circumstances, as mentioned earlier, onboarding was the responsibility of labs, professors or teachers where 'the OSS' is a critical part of a module, course or similar by the 'student'. The assumption being that it was 'someone else's' (teacher's) responsibility and not that of those that build and maintain the OSS.

n most circumstances, the OSS tool builders and maintainers don’t know what this process of ‘teaching’ the OSS to students and researchers looks like, as offered by a designer working across astronomy focused OSS tools mentioned:
*“I'm not sure how long it takes to learn. I know some universities teach (our OSS tool) some of the search form processes as part of a lab or part of research.”*

Some other astronomy OSS tools and spoken language OSS tool builder and contributors mentioned ‘state of fact’ how certain researchers come to learn and be onboarded onto OSS projects:
*“'Compulsory learning' aka part of your graded studies” and “Professors that teach it in a module”*

What this largely leads to is a deferred responsibility for the user’s onboarding being placed on people that are likely to not have as informed understanding of the OSS. However it does support the perspective of ‘users teaching users’ in that the teachers/professors are users as well as their students. This reinforced the community aspect of onboarding and learning.

### Depending on the nature/function of the OSS tool, certain proficiencies are expected from users in order to onboard on to the tool.

The requirement for upfront skills and knowledge is most critical to users when we consider the onboarding processes. Most Science and Research open source software have some barriers to entry, from the highest barriers being using a command line interface and knowledge of one or multiple coding languages and how to interoperate them, to the specific terminology used within certain science and research domains through to a proficiency with commonly used companion tools (e.g. Jupyter notebooks), services (e.g. Github or Gitlab), common open source processes or practices (e.g. read the docs, install packages, access our discourse forum etc.) or typical graphical user interfaces. 

One developer of a Ethnography platform details how users *“Need to know some social science terminology.”*  in order to make the best use of the tool. It’s not unrealistic to think that people would need to know about the specific scientific or research terminology associated with a domain in order to use an OSS tool built for intended use by that domain. However, when we explore the other comments from participants about other expectations of users we begin to find skills and knowledge that is dependent on coding knowledge essential to the operations of the OSS tool or specific OSS tools with their own barriers to entry, such as this participant who designs for astronomy OSS speaking about how the Jupyter notebooks tools is needed to run their OSS tool *“As far as ‘what do I start first’ - need to run a Jupyter notebook to guide into tutorial”.*

We also find that there are data processing related expectations that are not included within an onboarding process. Here a developer of a data analysis and visualization OSS speaks about the users needing to understand what they want their visualizations to be expressed as in order to find the order of operations in the tool to achieve that.

*“You need some knowledge about spatial data and how you look at that …and then …what your goal visualization is, I think [OSS tool] lets you explore some very basic things... I think there's not a huge amount of knowledge that you have to have going in, but you definitely have to be willing to explore and poke around and try a bunch of things and, you know, stuffs not going to work necessarily the first time.”*


### When we see ‘designed’ or ‘user centered’ onboarding experiences, these are best guesses and appear to struggle to understand how to build an onboarding experience that takes into account multiple complex and faceted entry, exit and reentry points to the use of the Science and Research OSS

In our data, we understood that people working on Science and Research OSS were largely uninformed of onboarding as an 'intentionally designed process for users to get started in said tool'. There were a few examples of an intentionally designed onboarding experience. A community manager at an OSS visualization python library speaks about how an clickable ‘ideal’ quickstart process of using the tool was implemented yet users seem to gravitate towards the community led and based tools.
*“So the optimal onboarding is we just revamped the website to have a nice like getting started, click through so they could click through to getting started. And they can see how we draw the first plot in the API we prefer and then we can go next, like the plot type. So the quickstart guide, you know, that's the path we'd like people to take. But like I said, I don't think anyone actually takes it on, StackOverflow seems to be how a lot of people onboard, just jumping from one StackOverflow to another.”*

Absent from this account is the information detailed in above sections about how researchers and scientists often have specific research related purposes they want to achieve as quickly as possible in the OSS tools they use which is perhaps why these users are looking towards the community communication spaces to find similar fields or purposes to their own.

Efforts to improve onboarding through methods that are prevalent in OSS and research like tutorials and documentation appear successful initially, in so much that they exist and are accessed by some users but the projects appear to struggle to truly know how useful they are to users. This designer working on a large, multipurpose research documentation ecosystem and python packages speaks to the time and effort spent on documentation and the simplification of the user experience yet lack of measurement of whether these efforts improve onboarding for users remains a mystery.
*“We spent a lot of time on documentation. And I spent a lot of time simplifying the UX. So to make the onboarding easier, but I don't actually know how much easier it is.”*

On first glance taking a descriptive approach like feature lists can seem to cover the ‘essential’ information a user might need to understand a tool. Here we have a statement from a developer working on a data transformation and augmentation OSS tool, where their documentation is ‘descriptive’ of their own projects' perspectives of the features.
*“Our documentation is really ‘features’ documentation, we don't have onboarding tutorials or anything like that.”* This misses the ways that users might describe the features or how they possibly use them to achieve certain objectives. Which is largely what onboarding hopes to do for users, introduce users to the possibilities.

And finally, this developer working on an OSS microbiome bioinformatics platform speaks to the difficulty users would likely have if introductory tutorials did not exist. Suggesting that users may get stuck even before a unique research use case. *“We have introductory tutorials, and they would have a pretty hard time finding their way around without those.”*

### Onboarding becomes a critical part of science and research OSS if their focus becomes inviting a broader scientific community to the usage of their tools as the OSS project matures

We found that the origins of most Scientific and Research OSS starts out as a component or the focus of an individual, group or lab's research. There are other ways SROSS starts such as part of an organization or company that support functions important to publishing research, such as data visualization but typically, OSS is made to a specific research purpose and that typically means small numbers of people in the project at the initialization.
As a project grows and gains users is when we see the people who build and maintain that OSS become more concerned with an ‘onboarding process’. Now there are more than the amount of people a single person can feasibly personally onboard and this needs to become systematized to an extent which requires understanding user motivations for use of the OSS that may or may not match their own as the builder of the OSS.
A community manager for an organization that funds and supports multiple OSS for science details when it becomes difficult to onboard new users.
*“Projects who really want to apply best practices for something like interoperability or things like that, the inherent effect of that is that your code base becomes much more complex, which then makes it more difficult to onboard new folks.”*
Here we discover a critical point in science and research OSS’s life cycle in when there is a very tangible reason to think about users, usability and the experience of using their tool beyond their own personal experience and what part of the tool (onboarding) it directly relates to.

### Conclusion

In our data, we understood that people working on SROSS were largely uninformed of the definition of onboarding as an 'intentionally designed process for users to get started'. Onboarding was the responsibility of labs, professors or teachers where 'the OSS' is a critical part of a module, course or similar by the 'student'. The assumption being that it was 'someone else's' (teacher's) responsibility and not that of those that build the OSS. The other types of people that are responsible for onboarding/training mentioned were the 'community' that supports each other or the 'resources' like documentation, tutorials or other content that people have created to 'help others get started'.

The uncertainty of what constitutes onboarding tools is raised across multiple comments and summarized with this comment by a designer who works across multiple python based scientific and research OSS *“We have a YouTube channel with some videos. I don't know if I totally consider those onboarding tools.”*

Onboarding is thought of as important when paired critically with a tool’s need for new user adoption, citation or popularity.
There’s also an unclear understanding of what users ‘really do’ when first interacting with their own particular science and research OSS tools which seems informed by the perspectives and experiences of the people we spoke to and the other that are configuring and building the OSS tools and how much they lean towards an OSS interpretation of the users of their OSS tool. Some onboarding behaviors are contradictory, such as this comment from a community manager for a data visualization OSS tool, about starting by hacking and not reading the documentation.
*“Nobody reads the manual. Everybody starts by hacking, and programming first, I try to do the thing. And then when they realize they can't do the thing, they may be going look, the docs, but then Well, it's just Google search, like, you know, search advice type of answer. So I think, I think a lot of this is just like a general reflection of how folks learn to code.”*
Which may be true for more coder, developer aligned users but isn’t the universal experience of users of science and research OSS where they are either ‘taught’ by other academics, by the documentation or the wider community.

**Our recommendation/s:**

- **Understanding what onboarding efforts exist across an existing community for the OSS:** This can help a Science and Research OSS project team to focus their user centered practice on gathering those examples from the community and collecting them in a space that is user centered.
- **Exploration of any software tool is somewhat expected of users as they onboard into it:** A ‘designed’ onboarding process might understand that many users may come in without an idea of how to achieve a particular visualization or not know what kind of visualization is best for their data and guide them through that discovery process. It seems, though Science and Research OSS expects this prior knowledge of their users or that they discover their answer via the community or documentation.
- **Onboarding is a complicated process that includes a myriad or different possible uses beyond the initial operations:** Supporting Science and Research OSS projects to stay external user-centered as they grow beyond the initial builders of the tool is a critical point in the adoption of ‘good’ design processes for onboarding which then lead to a key success metric across most science and research OSS which is more diverse users with diverse scientific focuses using and contributing to their tool.


1 -  [Carpentries](https://carpentries.org/) teach foundational coding and data science skills to researchers worldwide.