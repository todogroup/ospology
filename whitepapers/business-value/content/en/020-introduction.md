---
title: Background
weight: 10
---
# Background

## Purpose of this guide 

For the people who work in open source program offices and/or are involved in open source, the inability to convince their business counterparts to become more involved is a source of frustration. Open source champions know that their companies are missing out on opportunities to build value for the business, but either they don’t know which arguments to use to convince business stakeholders to invest in open source or they don’t know how to speak the language of business, so their points aren’t understood. This is reflected in the fact that only 36% of organizations have a formal open source strategy, according to research done by the [Linux Foundation](https://www.linuxfoundation.org/hubfs/Research%20Reports/2025GlobalSpotlight_Oct-27-2025%20V4.pdf?hsLang=en).

The goal of this guide is to give open source champions the arguments they need to have more productive conversations with those in the business who aren’t familiar with open source – or those who have misconceptions about what open source is and how businesses can get value from it. 

This guide is primarily focused on the benefits from not just passively using open source software, but also becoming active members of open source communities and/or publishing internal software projects as open source projects. The focus is on companies for whom open source is not a core part of their identity or their strategy. In most organizations, using open source anonymously is uncontroversial – at any rate, everyone does it, whether or not the business stakeholders are aware that it is happening. The fact that open source is used ubiquitously throughout the business world is something that business leaders should be aware of and accept; if nothing else, it’s important to be aware of the organization’s open source usage because there are risks associated with using open source – it’s important to have the software bill of materials (SBOM) and to be aware of legal risks from the licenses as well as the security risks from using software you didn’t write yourself in your software supply chain. 

However, the potential for a true strategic relationship with the open source ecosystem opens up when organizations become active participants in the open source ecosystem, both by becoming active members of open source communities and by creating and maintaining their own projects and communities. 

One thing to note before going further, however, is that maintainers, users and contributors are individuals. While organizations can own repositories and they can own trademarks and copyrights, contributions to open source projects have to come from individuals. It’s individuals who write and commit code, individuals who submit issues, individuals who submit pull requests and individuals who approve them. When you hire someone who’s been involved in open source, as an organization you benefit from the reputation they’ve built over the years in the open source community. Conversely, when an employee who has been involved in a project leaves your organization, they take with them the reputation they’ve built – and they can also take with them commit rights and maintainership of projects. When you’re just downloading and using open source projects this doesn’t matter much, but when the organization begins to contribute to and publish open source software, it can become critical to be aware of and manage. 

## Open source in modern software engineering

Nearly all software engineers use open source software, and most use open source software on a daily basis. 

Research from [Harvard Business School](https://www.hbs.edu/faculty/Pages/item.aspx?num=65230) shows that the value of open source software in the global market is around $8.8 trillion – that is, businesses would have to spend nearly $9 trillion to create and maintain software internally if open source software did not exist. Businesses would have to spend 3.5 times more on engineering if it were not for open source software. 

Open source software is ubiquitous in modern software engineering. Most programming languages are open source, and there are certain parts of the technical stack – libraries, for example – that are nearly always open source. If you use Docker containers, you’re using open source; if you use Go or Java or Python, you use open source. Nonetheless, business stakeholders in non-software companies are not always aware that their organizations use open source at all. 

The fact that using open source software makes engineering teams more productive is not controversial – it amounts to downloading software components and using them for free. But engineering departments can also become more involved in open source communities by contributing back to projects they use regularly and/or publishing their own open source projects. In most engineering departments, using open source software is simply the water that everyone is swimming in. Engineers don’t think much about downloading and using open source software because it is so integrated into their workflow. 

Business leaders, on the other hand, often don’t think about open source because it is so far from their universe. When they do think about open source, it’s often in the context of risk management – ensuring that their organization’s open source usage isn’t leaving them vulnerable to security or compliance problems. 

But a real engagement with open source, one that goes beyond downloading and using it anonymously, can help organizations build a competitive advantage compared to competitors. It requires convincing engineering and business leaders that open source just isn’t something to be consumed, but rather an ecosystem to engage in and an opportunity to build reputation, partnerships and even new revenue streams. This guide is about how to make that happen. 

## What is open source? 

When it comes to open source, there are a lot of misconceptions – even among software engineers. So what exactly is open source? 

Open source software has its roots in the free software movement, which started in the 1970s. Software was the first ‘digital product.’ Long before there were digital music or digital books, you could create a copy of a software program for free, without any impact on the original program. This gave rise to a political philosophy that holds that programmers shouldn’t charge for software, and that software should be a source of empowerment for users. The ‘free’ in the free software movement is a reference to freedom, not to something that costs $0. There are four basic freedoms of the free software movement: 

- Freedom to run the program as you wish, for any purpose
- The freedom to study how the program works, and change it to make it do what you wish
- The freedom to redistribute copies so you can help others
- The freedom to distribute copies of your modified versions to others

The open source software movement takes the philosophy of the free software movement and codifies it, creating a legal framework around free software to make it more palatable to businesses – particularly their legal departments. 

The organization in charge of translating the philosophy of open source software into concrete legal terms is the [Open Source Initiative](https://opensource.org), also known as OSI. All software is released under a software license, and the OSI determines which licenses are open source licenses. You can see the list of OSI-approved licenses [here](https://opensource.org/licenses). 

Open source software is simply software that is released under an OSI-approved license. 

It can be published anywhere, it can be created and maintained by volunteers or employees at hyperscalers, it can be used for good and it can be used for evil. It can be produced by a single individual or a group, it can be a product of collaboration between multiple companies or it can be created entirely by a single company. Open source software is not fundamentally ethically or morally superior to proprietary software; it is a legal framework that can have both advantages and disadvantages. 

If the software is published under an OSI-approved license, it is open source software. Conversely, software that is not published under an OSI-approved license is not open source. 

The above point is important, because there are actors in the ecosystem that have tried to muddy the definition of open source, or have tried to position open source as a spectrum. Open source is not a spectrum; either a piece of software has an OSI-approved license or it does not. Some companies, for example, have software that is ‘source available,’ which allows people to inspect the code, but not to run it themselves without paying a license fee. Source available licences do not meet the OSI criteria, and source available software software is not the same as open source software. Some companies with source available code will claim it is “open” or talk about “openness” in their marketing materials, but that is not the same as open source. Being able to inspect the source code is only one of several criteria that the OSI considers when deciding if a license is open source. 

You can see the full description of the [criteria OSI uses](https://opensource.org/osd) to determine whether or not a particular license meets their criteria here; in a nutshell, a license must meet the following criteria: 


1. Free redistribution. 
2. Availability of source code.
3. Freedom to create derivative works 
4. No discrimination against people or groups 
5. No discrimination against use cases 


Some of these clauses seem straightforward at first glance but in fact are not. For example, open source software can’t be restricted to use cases that the program author considers ‘good.’ Open source software can be used as part of a spyware or cyberwarfare stack for an enemy state; it can be used in weapons technology. Open source software can be used by the software author’s commercial competitors. It’s possible to limit who contributes to the software because contributions require approval from one or more individuals who control the project, called “maintainer” in the open source world, but it is not possible to limit who uses and benefits from the software. 


## Legally open source versus culturally open source 

Much of the confusion around what is and is not open source comes down to the fact that while open source has a legal definition, there is a larger philosophy and culture around open source. There are also a set of common practices related to open source software that are described below. It’s important to note that while these practices are strongly associated with open source, they do not define a piece of software as open source. For example, just because code is available publicly on GitHub does not mean that it is open source code; there are many non-open-source licenses in which the code is public but published under a license that does not meet the OSI’s criteria. Conversely, not all open source software is available on GitHub. It could be available on GitLab, but also for download directly from a website or, if you want to travel back in time, on a floppy disk. 

Here are some of the main pillars of the culture around open source software. Remember, though, that what makes software open source is its license, not the collaborative development model or having the source code publicly available. However, if your goal is to get business benefits from open source, you need to understand the norms around open source, which go way beyond the legal framework of the source code. 

### Collaboration

In most cases, open source software is published in a public repository like GitHub or GitLab. This is a way to both make the code publicly available, and to facilitate collaboration. 

The reason that open source software is so closely associated with platforms like GitHub and GitLab is because collaboration is a core part of open source culture. 

Open source software is used all over the world, and it’s free. While it is certainly not the case in all open source projects, many open source projects really are a collaborative effort. The people who work on the project can be a mixture of volunteers and people who are paid for their work on open source; they can be employees at companies that compete with each other. They can live all over the world, have different skill sets and vastly different economic realities. There can be one maintainer or several maintainers; the level of engagement with the project can vary drastically while still remaining a communal effort. 

When software developers think about open source software, they often think about projects like Linux – projects that are created exactly as described above, with a huge network of people who find a way to work together in spite of vastly different realities. 

Collaboration can be both a strength and a weakness of open source. When it works well, you get input from people with a wide variety of use cases for the software, with each person contributing according to his or her strengths. This makes it possible for the software to be developed much more quickly; it also means that bugs are caught and fixed quicker. 

On the other hand, collaboration is not always easy and there are downsides. Open source projects can suffer from being pulled in a million different directions; they can also get bogged down with poor-quality code submissions, comments or issues that are opened that don’t make sense or are redundant and waste time, and differing opinions about how to solve the same problem. 

Collaboration is considered part of the ‘spirit’ of open source. But the idea that all open source projects are the product of collaboration among otherwise unconnected developers is largely a myth. There are many open source projects that are created, developed and maintained by a single individual; there are many open source projects that are created and maintained by multiple people who work at the same organization, so that the effect is no more ‘collaborative’ than any other piece of software that is developed internally. 

### Transparency 

A second pillar of open source culture is transparency. In an ‘ideal’ open source world, this means that everything about the project is done in the open: Issues are raised publicly, there is public discussion about the roadmap, and the code is developed incrementally, in the open. Technical decisions can and should be made transparently. 

Clearly at least a minimal amount of transparency is necessary for open source software to be open source, given that the code must be publicly available. However, it’s entirely possible to publish an open source project under an OSI-approved license without being transparent about the development process. In the open source world this is called a code dump; when the code is written entirely internally and then the finished product is published under an open source license. A code dump is a pejorative term; it is considered not at all in the spirit of open source. The reality is that even among open source projects, there is a spectrum of transparency around the development process. Sometimes companies will do the actual development in the repository but all discussions about the code happen behind closed doors, for example. Transparency will always be a spectrum, but generally speaking the ‘spirit’ of open source is to be as transparent as possible. 

Transparency can be uncomfortable, particularly for companies. Many companies hesitate to publish open source software precisely because they are worried about airing their dirty laundry, or about the world seeing their less-than-perfect engineering practices. True transparency also goes along with collaboration – if you are transparent about how decisions are being made, you are also opening yourself up to input from users; and that input might be criticism. This full transparency also makes it easier for new contributors to be onboarded, because they can see how past decisions were made and incorporate that information into how they approach their own work with the project. 

### Community

The expectation in open source projects is not just that individuals are going to collaborate, it is that they are also going to bond with each other and become a community. 

In conversations around open source, there will invariably be talk of community. So what exactly does this mean? 

Just as collaboration is one of the core values in open source philosophy, so is community. For an open source idealist, the goal isn’t just to build great software that solves a real problem; it is also to bring together like-minded people to work together and interact with each other. At its best, open source is not just about software, it is about the humans who make software. 

Community can take many different forms. The most basic form in an open source project is on a coding platform like GitHub, in the form of both discussions and issues. These are ways for developers to talk about bugs they find in the software, to discuss additional functionality that should be added to the project and to consider different ways to solve technical problems. 

In many open source projects, there’s also a Slack or Discord group for project users to connect with each other, ask questions, and support each other. Sometimes this is referred to as “the community.”

The most successful examples of community building in open source projects happen when the project maintainers are able to bring people together in real life to collaborate and learn from each other. Sometimes these are small local meetups, sometimes these are large conferences.
 
Just like with collaboration and community, however, you do not need to build a community in order to publish an open source software. And communities do not happen by magic; if you do not make a concerted effort to build the community, it’s not likely (although not impossible) that one will coalesce around the project you create. 

In fact, communities do not make sense for all projects. So while community building is a core value in open source, not all open source projects will have a community and not all open source projects would even benefit from a community. 

## Pull box: Different levels of engagement inside a community


In an open source project, there are a variety of levels of engagement in the community (as with in any community).

### Users

In any open source community, the vast majority of people are simply anonymous users. One of the challenges for the maintainers of open source projects is that there is so little information about these people – other than statistics about downloads, it’s often hard to know what’s going on. 

It’s also hard to know if people who download the project even use it, or if there are users who downloaded the software from other channels. This lack of information about 95% of the users of the open source project is a source of frustration for creators and maintainers; and while it’s possible to get some metrics, for the most part you have to accept that you won’t have much visibility into this part of the community. 

### People who ask questions and report bugs

It’s generally less than 5% of the anonymous users who end up interacting with the community in any way. But someone who logs in to the Slack or Discord group just to ask questions is participating in the community; he or she is giving clues to potential problems with the user experience or the documentation as well as identifying themselves and giving you information about how they use the software. 

These active community members are often overlooked when talking about open source communities, because there is so much focus on contributors, especially code contributors. It’s also why there is no shorthand term for project users who are active in the community but not contributors. 

### People who answer questions

In healthy open source communities, there is a type of community member who is incredibly valuable but often overlooked: people who are out there giving free support to others. In other words, those who are active in discussions and who answer others’ questions. 

These people may or may not contribute to the project in the sense of contributing code or documentation, but they are providing an incredible service to the project and the community. There’s no short-hand term for these people, but these are the people who build a community around a project – even more so than those who are contributing code or documentation. 

### Contributors 

Contributors are people who contribute concretely to the project’s development. In the open source ecosystem, people tend to talk primarily about code contributors, but there are many ways that individuals can contribute to an open source project. It can be by writing documentation, by translating documentation (or translating the UX), writing website copy, by doing a conference talk about the project… or many other things. 

### Maintainers

Maintainers are the individuals who hold the keys to the project. They are the ones who decide what direction to take the project in, what contributions to accept and which ones to reject, which features to prioritize. 

At the moment of creation, the project creator is also the project maintainer, and usually the creator continues to maintain the project for some time after it is first published. In order to ensure project continuity it’s important to recruit additional maintainers. Large projects have multiple maintainers, and having more than one maintainer is an important sign of project health. 

In most cases, maintainers who didn’t originally create the project become maintainers after having made meaningful contributions in the past. They are selected by the existing maintainers, and they are selected as individuals, not as employees of a particular company. For example, a person who is a maintainer while employed at company X who goes to work for company Y will continue to be a maintainer of a project. Conversely, companies can not ask a project to make a new employee a maintainer; that employee has to earn maintainer status as an individual who makes contributions to the project. 



End pull box

## Embracing Open Source Culture

Using open source to build competitive advantage means embracing the cultural norms around open source as well as the legal framework. Simply publishing a piece of code under an open source license generally has limited advantages if it’s not published in a place where people can see it, if you don’t tell anyone about the open source software’s existence and if you don’t build community or collaborate with anyone. 

On the other hand, if you’re going to call a piece of software open source it should meet the legal requirements for open source software. To do otherwise is misleading, and ultimately will hurt your organization’s reputation especially with open source developers. 

The companies that end up getting the most out of open source software are the ones who contribute to and publish open source software, that are active in open source ecosystems while following both the norms in open source communities and the legal framework around open source software. 

