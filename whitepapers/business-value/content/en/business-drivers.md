---
title: Business Drivers
weight: 15
---
# The mechanics of open source in business

Open source is not a business model per se, but it can play a pivotal role in driving business growth. The ideal scenario is where open source adoption creates a mutually reinforcing cycle, where business success drives open source development, and vice versa.

We will describe the main ways open source can act as a driver of business and then show how these drivers work in different business models.

## Drivers

This section describes how open source can function as a driver of business models. Real-world business models will often use a combination of these drivers or vary how they are used.

### Wide adoption

Open source is a powerful way to achieve adoption for software. The absence of licensing costs and the inherent freedom to use it for any purpose without restrictions makes it an attractive offering for many people. It is easy to integrate for users compared to other licensing models where engineers need to involved other department like procurement, legal, management before having access to the technology.

Open source adoption is often accelerated by network effects, where happy users become promoters, even in other domains or markets, that are not addressed by the original go-to-market strategy. Communication through the community is an effective way to reach a very wide range of potential users.

It also helps adoption that software developed in the public is often of high quality. In a healthy project it benefits from diverse groups of contributors driving up its utility and quality, and is less susceptible to negative impacts of short-term decisions by a controlling company.

Wide adoption opens business opportunities because there is a user base which cares about the software, and it has already proven its relevance and value.

**In short, adoption creates the market on which businesses can build.**

### Shaping a project through contributions

Most open source projects welcome contributions with open arms. This gives everyone the opportunity to take a part in shaping the project by putting in work. This way a project can be adapted to serve the business interests of particular users, especially when these needs are also appealing to others.

It is more effective to spend 20% effort on adapting an existing solution to your use case instead of spending 100% effort on building your completely own solutions.

Open source allows customers to directly implement and add their requirements to the solutions. If done and managed well this avoids over-specialization of the technology and allows to keep using the technology in different contexts.

Even when the original authors are reluctant to contributions, open source licenses always allow to fork the project as a last resort. Then you can develop it independently of the original authors yourself. While this is not a desirable situation it gives a guarantee that changes can not be completely blocked. It also gives the original project an incentive to look for ways how to accommodate contributions.

**In short, contributions give businesses leverage to shape the tools they rely on.**

### Zero license costs

Open source licenses grant free use of the software at zero costs. This is part of the definition of open source. This lowers expenses wherever licensing fees would otherwise add up. It is particularly relevant in models that scale, such as running large numbers of instances where usage-based pricing could otherwise become prohibitive.

Zero license costs also reduce the costs of a software stack used as the base for building further solutions. The value creation shifts upward, while the base layers become a commodity. In these commodity cases, open source often evolves as the predominant solution because it provides the most cost-effective model, especially in highly collaborative development situations.

**In short, zero license costs make scaling economical and move value creation up the stack.**

### Transparency

Open source provides full transparency to a piece of software, because the source code is available to all users and in almost all cases to the general public as well. This is the prerequisite to be able to analyze how the software works and perform an independent assessment of quality of the code, security, and other aspects.

Transparency is crucial in situations where trust in a vendor's statements is not enough. It for example gives everyone the ability to make sure their requirements are met, or it can be used to lay open used algorithms for the scrutiny of a community to ensure fairness and correctness.

This is especially relevant for security. Only if the implementation is open we can verify that the component actually does what it is supposed to do and does not rely on "security by obscurity".

**In short, transparency replaces vendor claims with verifiable trust.**

### Public benefit

Open source by nature serves the public benefit. Everyone can use, share, study, and improve the software. So publishing software as open source is a direct contribution to the commons. It increases the value of resources available to a society.

In many situations it is beneficial to work for the public benefit. It can be based on ethical reasoning, but it also can be required, for example when being funded by public money. In some cases this is even mandated by law.

**In short, open source directly creates public value.**

### Volunteers

A lot of open source software is developed by volunteers. They do that to scratch an own itch, to learn, or to build up personal reputation. Motivations vary, and open source provides an environment to follow them while also offering the opportunity to make a big impact. This can be such a strong motivating factor that it brings together teams of developers which would not be possible to bring together by commercial means.

Contributing voluntarily also gives a lot of freedom to follow your own interests and work in your own pace, because it doesn't come with the obligations of a paid assignment. This can open the room for experiments which would not be commercially viable.

Many volunteers will even contribute to projects which serve as the base of a business of somebody else. They do so if they have the feeling that they get something in return, for example that the software they contribute to is well maintained and their efforts are multiplied, or that they can address their own needs by contributing corresponding features.

Volunteer contributions can be a delicate element of a business model. Volunteers owe nothing to a business exploiting their volunteer work, and unfair treatment of volunteers might not only harm a community but also seriously affect the reputation of a business. If done right, they can be a powerful multiplier of good will and a source of valuable contributions.

While volunteers are the backbone of many open source projects, it's important to acknowledge the challenges of sustaining engagement. This can be especially taxing when a project is in high use with corresponding load and demands towards maintainers from commercial entities without compensating them adequately.

An example are commercial entities trying to outsource their requirements to volunteer contributors without providing the necessary assistance. We have seen cases, where maintainers have closed their projects or get frustrated when they get asked by downstream users to adapt their security protocols to fit into the processes of the companies. We can only advise companies to not do this.

**In short, respectful engagement with volunteers adds value beyond payroll.**

## Business models

In this section we look at concrete business models which use open source in some way to drive the business. We will use the drivers defined in the section above to explain how this is achieved.

### Support and maintenance

Selling commercial support and maintenance for open source projects. This includes guarantees for security updates and other services, like a support hotline, required for business to operate open source within an environment with service levels and similar requirements.

Open source opens the market for other competitors to provide support which makes it more attractive for customers compared to offerings where they are bound to a single vendor when choosing a specific solution and technology.

Drivers:

* Model directly scales with *adoption*. The more adoption, the more need for support and maintenance of these projects.
* Model relies on *contributions*, so that fixes can be made on the timeline of the required support. To keep this economical they need to go back to the projects.
* *Zero license costs* are a factor because range of support only depends on own ability to deliver not on the accessibility of the software supported. Scales well to large number of support offerings.

Examples:

* Linux Distributions: RedHat, SUSE, Canonical

### Packaging

Not all software is easy to consume. Offering packaging for users who are not willing or capable of making the effort to install software from sources or similar activities, can be an attractive business proposition, especially for popular products.

As a specific variant offering open source solutions in the app stores of the big platform providers can be a source of income.

Drivers:

* Income directly scales with *adoption*

Examples:

* Chainguard, Bitnami, Anaconda

### Professional services, custom development

Adapt and extend open source software to meet specific individual requirements.

Drivers:

* Key factor is *contributions* which allows to offer custom development for all open software. Model depends on expertise, not on availability of underlying software. To keep it economical contributions need to get back into the projects.
* *Adoption* is also a factor because it defines the size of the potential market.

### Hosting, Software as a Service

Running software as a service is associated with constant work and attention and incurs running costs. It requires expertise with the specific software as well as with hosting software in general. Many people and organizations don't have the time or expertise or are willing to manage the risks associated with this. Providing this as a service for a subscription fee is a valid and popular business that often scales better if one entity handles the hosting for multiple customer instead of each customer building up the environment and knowledge to run it by themselves.

Drivers:

* *Adoption* defines the size of the market
* *Zero licensing costs* allows to set up this model for software you didn't develop yourself.

Examples:

* Wordpress
* Aiven offering managed data services
* Instructure with Canvas
* Cloud providers offering managed open source based services

### Development with a shortcut

Offer complex tailored software solutions based on mostly an open source stack. Tailoring and development only is needed for a small layer defining the product or service. Is like custom development, but with the shortcut that most of the code already exists.

This might be especially interesting with new AI software development capabilities.

Drivers:

* *Zero license costs* are the main driver, because this gives the majority of the software stack for free.

Examples:

* Almost all software developed today. According to studies, 70 % of software are open source components.

### Open Core

Offer an open source solution for free and additional proprietary components in a traditional commercial licensing model.

Usually the open source project is controlled by the commercial entity, which also offers the commercial proprietary components.

Model can be challenging, because there is a constant conflict of interests. Putting features into the open source version might alienate paying customers, because they could also get these features for free. Putting features into the commercial version might alienate community users, because it makes their version less useful. So it's a constant balancing act.

Drivers:

* Wide *adoption* is key, because it drives the market need for specific extensions, e.g. for adaption of software in enterprise environments. Only a small amount of free users will be willing to pay for extensions.

Examples:

* GitLab
* Hashicorp was a good example, before it abandoned their open source licensing

### Dual Licensing

Offer the same software under two licenses, an open source version, which can be used for free, but restricts users in non-open scenarios, and a proprietary version, which doesn't have these restrictions, but needs to be paid.

Usually a strong copyleft version is used as open source license in this model. This can be seen as going against the free software idea, because it's not meant to pass on freedoms, but to play into concerns about detrimental effects of strong copyleft to proprietary business.

This model only works, if the vendor of the commercial version has all rights on the open source code as well. This can be challenging in terms of community engagement.

Drivers:

* *Adoption* of the open source version drives the market for possible customers of the proprietary version. Only a small amount of free users will be willing to pay for the proprietary version.

Examples:

* Qt is one of the original examples of this model

### Level market through standardization

In a closed market, where dependencies on vendors are strong, and it's hard to switch vendors because of lack of standardization, open source standards and (reference) implementations can create more openness and choice for customers. So establishing an open source solution increases competition and brings down costs.

Drivers:

* *Transparency* is the base for an open standard.
* *Adoption* is key to make the standard relevant.

Examples:

* Android set market standards for mobile operating systems
* Kubernetes set a standard solution for container-based cloud offerings

### Public Money, public code

Projects funded from public money are required or at least have a moral obligation to provide the results for the benefit of the public as well.

Drivers:

* *Public benefit* is directly aligned with the goal of public funding programs

### Own the platform

Scalable platforms provide a business model where the platform owner provides a market for providers and users of platform services to engage in business and takes a share of the transactions which are mediated via the platform. The more scalable the platform is, the more important it is to drive down the transactional costs. Open source software is mandatory to keep the costs low.

When the platform is the dominant revenue driver, development costs for software are not a relevant contributing factor anymore, because they don't scale with the usage of the software. So it makes not much difference, if the code is proprietary or open source. Huge platforms often publish a lot of open source code, because they can, this creates good will, and it also can play into the standardization business model.

Drivers:

* *Zero licensing costs* enable massive scaling
* *Contributions* make it possible to shape software into a platform product

Examples:

* Automattic with the Wordpress platform
* Public cloud platforms. Open source software dominates the offered services. Even on Microsoft's cloud platform Linux is the dominating operating system.

### Donations

Projects with a large community can bring in enough donations to fund central work, including development which is not done by volunteers. This relies on goodwill of users, but can still be a reliable source for business because it ties into the loyalty of users, which might not be there for commercial businesses.

Donations can also take the form of crowdfunding campaigns.

Drivers:

* *Volunteers* have a compelling story to ask for donations
* The bigger the *adoption* the larger the audience for requests for donations

Examples:

* Primarily not a software project, but Wikipedia bases its operation on donations by a large number of people
* The Document Foundation, the organization behind LibreOffice, gets the majority of their budget through donations
* KDE brings in funding for several developers and other community-funded roles through regular donation campaigns
* Krita successfully funded feature development through a crowdfunding campaign

### Sponsorships

There are open source components which don't have a strong business model supporting its development, but have critical roles in the infrastructure of companies and other organizations, because of their high adoption. For these critical infrastructure there are sources of funding through sponsorships.

Sponsorship can be money given to an organization to fund development, or directly funding developers, sometimes by employing them to work on open source projects.

Drivers:

* Wide *adoption* raises the criticality of a component
* Critical components maintained by *volunteers* are more likely to be in need of sponsorships to be sustainable

Examples:

* Linux Foundations's Alpha-Omega project
* Sovereign Tech Agency
* Git maintainers employed by Google
* curl maintainer employed by wolfSSL

### Advertising

If open source software or platforms are so wide-spread that they become attractive targets for advertising, this can be a source of income, which can sustain a business.

Drivers:

* Model depends on a high *adoption*

Examples:

* Mozilla is mostly financed by an advertising deal with Google
* Android as platform gives Google direct access to customers to use their advertising-based business model

## Shaping open source projects to drive the business

To use open source effectively as a business driver, the corresponding open source projects need to align with how they are supposed to work as drivers. Projects need certain traits that support this, for example in terms of licensing, governance model, technical architecture, characteristics of the community members etc. This linkage matters because business models such as support, SaaS, or open core rely on projects being shaped in a way that actually enables the drivers they depend on.

Mozilla has published ["A Framework For Purposeful Open Source"](https://blog.mozilla.org/wp-content/uploads/2018/05/MZOTS_OS_Archetypes_report_ext_scr.pdf), which defines a set of open source archetypes. These archetypes describe how a project is shaped to achieve certain goals. This is a useful perspective when deciding how to shape a project when starting it from scratch or which existing ones to engage with to achieve business goals.

The Mozilla paper defines a list of benefits of open source, which are then reflected in the archetypes, although there is no clear-cut direct mapping. There will always be a combination of benefits, archetypes, and business drivers.

The table below links the business drivers introduced above with the archetypes benefits identified by Mozilla and indicates which archetypes are most likely to realize them. This table is some guidance, not a formula. Even the original authors of the Mozilla paper emphasize that most projects in practice will display a mix of the phenomenologically described archetypes.

| Business driver | Related archetypes benefits | Archetypes most aligned |
|-----------------|-----------------------------|-------------------------|
| Wide adoption | - Lead a standardization effort  <br> - Establish product reputation  <br> - Establish brand & credibility  <br> - Stop competitors from early dominance  <br> - Improve market acceptance by reducing proprietary risk | B2B Open Source, Mass Market, Multi-Vendor Infrastructure |
| Shaping a project through contributions | - Amplify/expand developer base  <br> - Improve product quality (“quality ratchet”)  <br> - Provide a framework for collaborating with partners | Wide Open, Controlled Ecosystem, Multi-Vendor Infrastructure |
| Zero license costs | - Reduce vendor risk / independence  <br> - Improve market acceptance (insurance against lock-in)  <br> - Public benefit (commoditization of base layers) | Trusted Vendor, Upstream Dependency |
| Transparency | - Provide transparency to customers & partners  <br> - Increase insight into competitors’ or partners’ strategy  <br> - Establish product reputation (trust through openness) | Multi-Vendor Infrastructure, Trusted Vendor, Wide Open |
| Public benefit | - Public benefit (commons)  <br> - Strengthen organizational brand & credibility | Specialty Library, Trusted Vendor |
| Volunteers | - Amplify/expand developer base  <br> - Increase developer hiring pool  <br> - Improve developer morale & retention  <br> - Engage with users | Wide Open, Mass Market, Controlled Ecosystem |

## Addendum: Why open source is not a business model

Software is not a business model. It is an object of business. You can sell it, lend it, provide services for it, get paid to develop it. But software itself is not a business model.

In the same sense open source software is not a business model either.

But open source is more than just the artifact of software under an open source license. It's also a development model, an approach for collaboration. It is a culture of how people can interact to produce software effectively, how they develop a common understanding of process, working and governance models, and how they do this with great fun and purpose.

This culture of open source can be an invaluable asset to many business models, because it is of significant effect, it aligns with what makes many businesses strong, and it has a positive effect on the humans involved with its production.

But also this aspect is not a business model in itself. While collaboration is at the core of many business models, it still depends on what the collaboration creates, how it interacts with the market and how the subject of collaboration plays with the intricacies of the market to provide a sustainable way to make money.

So, open source is not a business model. But there are plenty of business models which become better when they make intelligent use of open source.
