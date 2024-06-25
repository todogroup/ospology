---
title: "2 - The Value of Open Source Program Offices"
status: Completed
weight: 40
---

- [Open Source is All About Integration](#open-source-is-all-about-integration)
  - The Value of an OSPO
  - Reasons Behind Starting an OSPO
  - Reasons Behind Sustaining an OSPO
- [Assessing Value of Open Source Activity](#assessing-value-of-open-source-activity) - `✅ Assessment`
- [Recommendations](#recommendations) - `💡 Recommendations`
- [Resources](#resources) - `📚 Continue Here`

## Open Source is all about Integration

Organizations of various types – including end-user companies, software vendors, universities, and public administrations – maintain a relationship with open source. To responsibly manage software and hardware, content, and other aspects of technology, organizations must engage with open source. This involves finding ways to integrate such culture and operations into their IT strategy and technology and AI stacks. Establishing an organizational structure is a crucial first step to solidify commitment. This is where an Open Source Program Office (OSPO) becomes important. It helps organizations to achieve their objectives and overcome challenges related to open source.

> 💡 OSPOs put the focus on _integration_, not _isolation_

### Supply Chain and Open Source

Sometimes, organizational stakeholders may assume that their product isn't using any open source projects because their end product is proprietary. However, when you look at the [entire software supply chain](https://opensource.com/article/16/12/open-source-software-supply-chain) you can see that your proprietary software contains open source dependencies or artifacts. If the contributors working on those open source projects were to leave, the project could become obsolete or a target for security vulnerabilities. This, affect the proprietary software the organization uses or sells, directly impacting its reputation, performance, or revenue.

#### Common challenges when managing open source integration

Organizations may encounter issues when managing open source components that are integrated into their technology infrastructure. If these issues are ignored or neglected, they can lead to mid-term and long-term innovation bottlenecks and security vulnerabilities. It’s important to understand the unique factors that make open source different.

- **Vulnerability management can be hard:** Open source projects can be a source of security vulnerabilities in a product that depends upon them. It can be hard to keep track of how open source projects are being used by your organization to perform risk assessments on the identified projects. When you identify key projects within the organization, you can prioritize securing them by tracking common vulnerabilities and exposures. Often, the Enterprise Architecture team are the ones tracking the open source components of applications and technologies, and OSPOs are there to give subject matter expertise.

- **It can take a lot of work to understand the complexity of the open source supply chain:** The open source landscape is large and decentralized, and it can be hard to identify who the contributors to individual projects are. These factors can make it challenging for organizations to accurately assess risks and to comprehend the security and quality standards of the software, hardware, data, etc.

- **There can be a tension between the need to ship product features and the need to contribute back to open source:** Commercial organizations that are using open source are often keen to contribute back to the projects they use. However, the pressure to ship features in their own products mean that open source contributions may take a back seat when things get busy.

- **It takes time and planning to collaborate effectively with the community and industry:** Your organization could be in a good position to provide resources to open source projects. That could be through coding, expertise, or money donations as incentives for fixing common vulnerabilities ([see Log4Shell real vulnerability example](https://en.wikipedia.org/wiki/Log4Shell)). It could also be productive to collaborate with industry working groups to address security concerns holistically. Making a plan that aligns with your organization strategy and provides value to the open source projects is a good way to be a helpful community member. 

- **Your organization’s procurement may never be fully met when you adopt open source components:** Open source is a dynamic ecosystem whose contributions should occur as smoothly and naturally as possible. The long procurement processes faced in highly regulated environments, such as finance companies and governments, create a barrier to open source contribution and engagement.

- **Your colleagues may lack understanding of open source::** The concept of open source may not be taken seriously in other areas of the organization involved in decision-making processes, management, or policy making. This will require constant education and demonstration of the risks and value of open source in the organization.


To fully overcome these challenges, organizations must invest in properly managing open source operations on both cultural and practical levels. The *how* of accomplishing this is often through the OSPO, as it fosters committed, cross-functional collaboration within the organization to address open source issues encountered by various teams or departments.

> 💡 OSPOs foster cross-functional collaboration

But how exactly can an OSPO enable cross-functional collaboration? Why and how does this cross-functional collaboration aid in achieving the organization's goals? Additionally, why is this cross-functional collaboration essential for the creation and long-term sustainability of an OSPO within the organization?

### OSPO value perception

In both sections, the emphasis is on the different responsibilities of an OSPO to help manage open source as an ongoing activity and be well integrated into all organization's units. More and more organizations are integrating open source into their regular structures and functions and there is an open question related to whether the OSPO would become an intermediate step to achieve this.

The answer depends on how you view the OSPO. Beyond the multiple structures the term "OSPO" can imply, it is fundamentally about its people. If we consider the OSPO as a group of open source subject matter experts providing support, knowledge, and management for this integration, this talent must be not only maintained but also reinforced and effectively financed for the future, as more open source integration is inevitable.

In an ideal scenario, open source knowledge, technical expertise, and culture should be integrated as any other employee skill. However, the reality is that this is far from true. Currently, it is challenging to find open source experts who can effectively bridge the gap between open source communities and specific work units (e.g., security, legal, business).

What might change in the coming years is the centralized view of the OSPO. This traditional perception may diminish, leading to more decentralized structures across teams and business units.

![ospowork](https://user-images.githubusercontent.com/43671777/232471414-8ea7c899-a13c-47de-bafe-836830525d02.png)

_[Source: OSPOs, key lever for open source sustainability](https://speakerdeck.com/anajsana/ospos-a-key-lever-for-open-source-sustainability)_

### The reasons behind starting an OSPO

Integrating open source into an organization's infrastructure and operations is a vast field that encompasses various angles and objectives. The [business value of the OSPO report](https://www.linuxfoundation.org/research/business-value-of-ospo) explains some of the reasons shared by open source leaders across different industries and organization sizes.

- Building standardized processes around open source
- Learning how to approach the open source community
- Embracing the Sustainability of open source Projects
- Managing compliance
- Expanding access to open knowledge
- Improving development velocity
- Mitigating security risks

### The reasons behind sustaining open source operations through an OSPO

Stopping the work of an OSPO could have significant negative impacts on those organizations that use open source (directly or indirectly) at any level, including loss of open source expertise, increased security and legal risks, reduced community engagement, and damage to reputation.

> 💡 _Open Source is a silent critical need_

An OSPO needs to be an ongoing initiative within an organization in order to evolve its culture and open source knowledge, helping the organization to contribute to and build more secure open-source software, as well as improving the sustainability of open-source projects.

The different roles and pillars of support of an OSPO shared below can help readers understand why it should be viewed as a critical area to maintain and nurture within an organization, rather than just a pet project with an expiration date.

- **Acts as a Counselor:** Sometimes a strategic approach just means stepping back and taking the time to think through some of the hard questions about what type of engagement model is right for any particular project or how involved the organization should be in each project. There is also the question of when it makes sense to contribute to an existing project versus creating a new project. An OSPO that is having these strategy-level conversations will be able to provide guidelines to workers at the different teams so that workers do not have to consider the business implications of different open source engagement models every time they try to solve a problem.

- **Acts as a Facilitator:** The OSPO also plays a sort of translation role between the organization’s teams and decision makers' interests regarding open source and the needs from the open source community. They also help organizations navigate the cultural, process, and tool changes required to engage with the open source community effectively and in a healthy way.

- **Acts as an Advocate:** OSPOs can promote the use and/or contribution of open source and best practices across different organizational units. This can help organizations realize the benefits of open source as well as engaging people to contribute to open source projects or start new ones.

- **Acts as an Environmentalist:** OSPOs can help organizations support and sustain open source projects in the long term by addressing issues such as security, maintenance, and project health. This can help ensure that open source projects remain healthy in the long term and continue to benefit the wider community.

- **Acts as a Gatekeeper:** OSPOs can help enforce open source policies and strengthen open source governance. This can help organizations to ensure compliance and mitigate open source security risks.

![ospo-support](https://github.com/todogroup/ospology/assets/43671777/f96cd4a1-0315-4a0e-8de3-2da59378a57b)

### Interlude

#### A perspective of open source in public administrations

We can see that [more public sector organizations are realising the value of an Open Source Programme Office](https://joinup.ec.europa.eu/collection/open-source-observatory-osor/news/growing-case-ospos-government) to not only achieve their digital policy goals to better serve their citizens but also to transform their organizations toward achieving these goals.
Public sector organizations face unique challenges when it comes to managing their open source operations, including the need to comply with strict laws and regulations, and the requirement to provide transparent and accountable operations. An OSPO can help governments and public sector organizations to overcome these challenges.

- Improved Compliance: An OSPO helps to ensure that their open source operations are compliant with relevant laws and regulations, including data privacy laws, procurement regulations, and transparency requirements. This helps organizations to avoid costly legal and regulatory challenges, and to maintain their reputation as responsible public sector organizations.

- Increased Collaboration: An OSPO helps to foster collaboration between different departments and with external stakeholders, including other public sector organizations, open source communities, and civil society organizations. This increased collaboration helps organizations to access a wider pool of talent and resources, and to develop better open source solutions.

- Better Resource Allocation: An OSPO helps to allocate resources more effectively, ensuring that open source operations are well-supported and that key initiatives are given the resources they need to succeed. This helps organizations to maximize the benefits of open source technology, and to drive innovation and growth.

- Improved Service Delivery: An OSPO helps to improve the delivery of public services, by enabling them to adopt innovative and cost-effective technologies, and to collaborate with external stakeholders to develop better solutions. This helps organizations to provide better services to citizens, and to meet the changing needs of their communities.

The European Commission's Open Source Program Office (OSPO) has launched a new portal that serves as a wiki or knowledge archive, providing up-to-date information on advancements in OSPO-related topics for public administrators. This portal offers a variety of resources, including useful studies, presentations, use cases, guides, and more, to readers interested in learning more about OSPO-related topics. Check `📚 Continue Here` at the end of this chapter.

#### A broader view of open source

By extending the concept of _open_ to encompass (for instance) open research, design, or access, we can identify additional benefits that these practices bring to organizations. This broader view of openness is gaining traction in academic and public sectors, where terms other than open source are sometimes used instead, such as [open technology](https://www.researchgate.net/publication/254920512_Open_Technology#pf7) or open work. However, since these terms are not as well-known among organizations, many of them still use open source as a term to indicate activities beyond software.

For an OSPO it can be a challenge where to put boundaries on what topics to cover and to focus on. While values and general procedures are similar for different topics put under the umbrella of open, other aspects can differ significantly, such as legal or technical questions. The OSPO should strike a balance here and be clear about what it has the resources and expertise to cover and what it has to delegate to other parts of the organization. It still will be a point of contact.

For example, many people will not see a difference between open data and open source software and approach the OSPO for questions about open data. However, many organizations will have specific functions and roles for data governance the OSPO can then refer to. 

![opensourceswiss-knife](https://github.com/todogroup/ospology/assets/43671777/402151df-1c98-42e3-99cc-c1377ff8ca60)
Source: Khalil Khalaf - The Pros and Cons of Open Source Software

> Note: You may have noticed that in this book, when referring to open source, we also include other kinds of open initiatives beyond software, such as hardware, data, etc.

## Assessing the value of open source usage (also called consumption)

`✅ Assessment`

Organizations may underestimate how much they already depend on the usage (also called consumption) of open source. Several studies analyze the usage of open source software in the industry. For example, the [Synopsys Open Source Security and Risk Analysis Report 2024](https://www.synopsys.com/content/dam/synopsys/sig-assets/reports/rep-ossra-2024.pdf) finds that the average software project consists of 77% open source software. Additionally, a [Harvard Business School study](https://www.hbs.edu/ris/Publication%20Files/24-038_51f8444f-502c-4139-8bf2-56eb4b65c58a.pdf) estimates that the supply-side value of widely-used open source software is $4.15 billion, while the demand-side value is much larger at $8.8 trillion. Moreover, a [study by OpenForum Europe](https://openforumeurope.org/publications/study-about-the-impact-of-open-source-software-and-hardware-on-technological-independence-competitiveness-and-innovation-in-the-eu-economy/) estimates that open source software contributes between €65 to €95 billion to the European Union’s GDP and promises significant growth opportunities for the region’s digital economy.

Assess this value for your own organization by taking steps such as:

- Collect information about open source software used by your development and operations teams
- Get clarity about composition of commercial software you buy or services you use, ask vendors for what open source software they use, e.g. by requesting Software Bill of Materials (SBOMs)
- Assess value by evaluating what costs would occur by using alternative proprietary solutions and components
- Take factors such as speed of innovation or engineering agility into account

This is an example of the activities an organization will perform at the consumer stage in the open source maturity model. This naturally leads to the next step to the participant stage:

![opensourceinvolvementmodel](https://user-images.githubusercontent.com/43671777/232468143-cde69525-7adb-4399-96d3-fa63f056b942.png)

## Assessing value of open source contributions

`✅ Assessment`

Despite an organization might be aware of the general problems, responsibility and benefits that contributing to open source provides, identifying specific key motivators to move people to take action (create activity) and prioritize open source is a tough task. In this section, we will assess a 4-step process for communicating the value of contributing to open source and going beyond, which the OSPO can use when working with the different teams that engage with open source. (Source: [ospo-book mailing list discussion](https://lists.todogroup.org/g/WG-ospo-book-project/message/18))

## Step one: Assess open source activity engagement

Get familiar with maturity models of open source adoption. These levels describe how open source is used in an increasingly effective fashion to drive value and address organization's needs. One of the distinguishing factors for the different maturity levels is how open source contribution and creation are handled in an organization.

For instance, a typical maturity model of corporate open source adoption looks like this (see this example by [Dr. Ibrahim H](https://www.linuxfoundation.org/research/guide-to-enterprise-open-source)):

* Denial - No or unconscious use of open source
* Consumption / Usage - Passive use of open source software
* Participation - Engagement with open source communities
* Contribution - Pragmatic contributions to open source projects
* Leadership - Strategic involvement with open source to drive business value

![opensourceinvolvementmodel](https://user-images.githubusercontent.com/43671777/232468143-cde69525-7adb-4399-96d3-fa63f056b942.png)

## Step two: Identify  and categorize the benefits of open source activities for your organization

Once you have a certain familiarity with open source adoption models, the next natural question to ask is _What are the benefits of open source activities for the organization?_

The OSPO Japan Local Meetup Working Group, supported by the TODO Group and OpenChain, meets on the fourth Friday of every month. The group has been developing a simple frequently asked questions (FAQ) guide about OSPOs. This guide aims to answer questions at each step of the OSPO maturity model, which categorizes different open source activities from stage 0 to 4, and outlines the role of the OSPO at each level.

![benefits-of-oss](https://github.com/todogroup/ospology/assets/43671777/73acdc21-058e-406c-b01f-967074d25c1b)

![ospo-role](https://github.com/todogroup/ospology/assets/43671777/8dbcf056-446c-489d-9b40-07fc2a8c331c)

> You can find a summary of their work in both Japanese and English [in this Qiita article written by one of its members](https://qiita.com/owada-k/items/017d1b98d0e437766bd0)


## Step three: Initiate conversations and define unique motivators

Have 1:1 conversations with managers, high-level executives, and workers/contractors from different teams that use open source in their day-to-day operations, or whose strategy involves dealing with open source projects (in terms of licenses, security vulnerabilities). Use the insights from these conversations to define the organization's unique motivators and map them to areas within the organization where open source brings value

## Step four: Map motivators with different activity types across the organization

Create a second division that categorizes each of these unique motivators according to the different stages within the previously mentioned OSPO model, or a similar model as referenced in step 2.
As an example, below is a possible categorization, proposed by one of the contributors to this book

<img width="942" alt="activityparticipationcategorization" src="https://user-images.githubusercontent.com/43671777/232468402-bb4a4d49-a6d6-4c74-8d21-88c6be3c2c13.png">

## Recommendations

`💡 Recommendations`

In this section, you will find a series of real-world scenarios that are encountered in open source management across organizations. For each scenario, you can find recommendations from real-world experiences from open source professionals.

### Scenario #5
There is a lack of understanding about open source practices across the organization

> Recommendation: Promote organizational-wide understanding of open source practices through the OSPO by offering educational workshops, creating accessible resources, and establishing open source
> champions in different departments to foster a culture of open source literacy

### Scenario #6
An OSPO is seen as a Sales Profit or Marketing Tool

> Recommendation: Ensure that the OSPO is recognized as an integral part of the organization's digital, software, or IT strategy, rather than as a sales profit or marketing tool.
> Emphasize its role in fostering open source best practices, contributing to technological innovation, and supporting the overall organization's IT / Digital development plan.

### Scenario #7
An OSPO is seen as an added value and not as direct support for the core organization’s areas and functions

> Recommendation: Highlight how the people behind the OSPO with expertise in open source can enhance key business processes, drive innovation, and directly support strategic objectives,
> thereby integrating it as an essential component of the organization's operational framework

### Scenario #8
An OSPO struggles with gaining executive support and buy-in
> Recommendation: communicate the strategic value of open source through the OSPO, showcasing tangible benefits through case studies or success stories, and aligning its initiatives with key organizational priorities.

### Scenario #9
An OSPO has a technical focus and forgets about open source culture
> Recommendation: Embrace the full spectrum of open source culture, which includes transparency, diversity, and cooperation. Encourage the organization to foster an environment where these values are actively promoted and practiced

## Resources

`📚 Continue Here`

- [Open source and the software supply chain - John Mark Walker](https://opensource.com/article/16/12/open-source-software-supply-chain)
- [Strategy: End Game for FINOS Maturity Model - Victor Lu](https://docs.google.com/presentation/d/1jJtR6-fvU-dCrGq_gTm4P1Awv90oCu4RClj1919970A/edit#slide=id.g1ed9ae7029f_0_29)
- [Securing the Software Supply Chain: The Role of OSPOs - Jessica Marz](https://www.intel.com/content/www/us/en/developer/articles/community/securing-software-supply-chain-the-role-of-ospo.html)
- [Simple Frequently Asked Questions OSPO Guide - OSPO SWG Japan](https://qiita.com/owada-k/items/017d1b98d0e437766bd0)
- [The Business Value of the OSPO Report - Linux Foundation](https://www.linuxfoundation.org/research/business-value-of-ospo)
- [EC Open Source Programme Office - European Commission Joinup](https://joinup.ec.europa.eu/collection/ec-ospo)
- [Public Services Should Sustain Critical Open Source Software - FOSSEPS](https://joinup.ec.europa.eu/collection/ec-ospo)
- [How Governments Want to Use OSPOs to Transform Themselves - Sivan Pätsch](https://joinup.ec.europa.eu/collection/open-source-observatory-osor/news/growing-case-ospos-government)
- [Open Source Security and Risk Analysis Report 2022 - Synopsys](https://www.synopsys.com/software-integrity/resources/analyst-reports/open-source-security-risk-analysis.html)
- [Open Technology - Scheerder, Jeroen & Koymans](https://www.researchgate.net/publication/254920512_Open_Technology#pf7)
- [The Pros and Cons of Open Source Software - Khalil Khalaf](https://medium.com/@kylekhalaf/the-pros-and-cons-of-open-source-software-d498304f2a95)
