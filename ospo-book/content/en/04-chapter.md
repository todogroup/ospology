---
title: "Chapter 4: Day-to-Day Operations"
status: Completed
weight: 60
---

- [Introduction](#introduction)
- [Common Activities](#common-activities)
- [Applying This to Your Organization](#applying-this-to-your-organization)
- [Possible Problems and how to Overcome Them](#possible-problems-and-how-to-overcome-them)
- [Resources and Footnotes](#resources-and-footnotes)

## Introduction

Once you have your strategy, you need a plan. Your plan will be to create and execute on a set of regular activities that deliver your strategy. This chapter will help you understand what the range of an OSPO's activities are, and what value each one delivers to your organization.

## Common Activities

An OSPO's day-to-day operations encompass a broad spectrum of activities aimed at enhancing open source engagement and compliance within the organization, including:

- **Direct Open Source Support:** Involves answering questions on all aspects of open source, including license compliance, selecting OSS, and interactions with vendors. It also includes engaging with the community and partners, securing sponsorships, and organizing open source events.

- **Automation Tools:** Creating process automation to support open source policies is important because policies alone may not always be effective. Managers know that their workers won't always follow policy and therefore want effective options to automate use, management, and tracking of open source components. Automation is useful in many areas of open source including license compliance and security.

- **Documentation, Training, and Education:** An OSPO can play a leading role in ensuring that individuals are qualified to assess open source projects for use in the organization and contribute to critical open source projects for the organization. Developing training materials and documentation and/or aiding teams to produce these across different departments are key tasks.

- **Resource Allocation:** There can be a lot of areas that an OSPO can offer value to an organization. Therefore, prioritizing work and allocating resources strategically and tactically is an important activity that will improve the OSPO's impact.

- **Risk Management:** OSPOs are well-placed to take a holistic view of the risk that the organization faces when using open source projects. It's useful for the OSPO to assess the risks by obtaining a comprehensive view of the organization's tech stack. This may include generating SBOMs which allow the OSPO to consider the risks in software from vendors, legacy software, and proprietary software as well as in open source. This is more about a business assessment perspective rather than just data gathering, as risk can only be managed, not eliminated. Optimizing SBOMs is about balancing risks against benefits.

- **Sponsoring Open Source Communities and Foundations:** Your organization depends on open source. The projects in open source are only as healthy as their communities, and you can invest your time and money in supporting communities either directly or through Foundations. These relationships need to be understood and managed with care to achieve outcomes that will benefit the projects and your organization. Sometimes money isn't the best fix for a problem, and fostering a closer partnership and providing development, marketing, or programmatic support is more useful.

- **Measuring Technical Debt:** Providing knowledge on how to measure the technical debt on an open source project helps to determine the risks associated with the project and, when done in collaboration with the project community, is a form of educational advocacy to help projects improve and sustain themselves.

- **Coordinating with Various Parts of the Organization:** It can be helpful to check that you know all your stakeholders, and have the right amount of interaction with them. Take a look at the OSPO flower diagram in Chapter 3 for help mapping interactions.

- **Giving Advice on Open Source Consumption:** The OSPO considers both the strategic view on which open source projects to consume and on the best practice for using the selected projects. The OSPO should provide reference materials and guidance on how the company should select which open source projects it uses and how it manages them. Guidelines and policy can be purely technical or can include considerations based on open source project health and practices, like the *Secure Supply Chain Consumption Framework (S2C2F)*[^1].

## Applying This to Your Organization

### The OSPO MindMap

The OSPO MindMap [^2] is once again a useful tool. You can use it to get an overview of the potential activities of an OSPO. The OSPO MindMap outlines the main responsibilities, roles, behaviors, and team sizes within the ecosystem of an OSPO. As always, this is an input to your work, not a fixed plan to follow. You should adapt it to your needs.


### Activities by Maturity Stage

In the following table, Ibrahim H.'s open source activity engagement model (previously seen in Chapter 2) is used as a map for listing and exploring activities in an OSPO.

#### STAGE: Consumer

| Activities                                                                                                                 | Value for the OSPO                                                                                                                                     | Value for the  Organization                                                                                                                                                                                                                                                                                                                                                                                                        |
| -------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Define open source compliance rules and practices                                                                          | An explicit consensus on the organization's open source compliance rules and practices between the legal and business stakeholders.            | The organization knows that it has a managed approach to the legal aspects of open source consumption, which can be maintained and improved over time. Each company has different aspects of open source compliance, interpretations of licenses and different risk appetite (e.g dealing with regulations). Having well-defined compliance rules and practices is the first step toward deterministic open source compliance                                                                                                                                               |
| Define rules and policies on using open source (criteria for using OSS which relate to open source health)                     | Consumption of open source projects isn't just viewed through the compliance lens, but is considered more holistically and includes the risks associated with unhealthy projects. A consensus is built in the company related to the hygiene of consumed open source components. The organization has clear policies to follow. | Consumed open source projects are lower in risk because they're healthy, fixing security vulnerabilities, implementing new features and release regularly.                                                                                                                                                                                                                                                                                         |
| Define rules and policies on how to contribute to open source (criteria on how to engage in the community, how to transfer rights, Contributor License Agreements) | The OSPO can increase awareness of the two-way relationship with open source projects. Using policies supports a consistent and ethical approach. The organization has clear policies to follow.                                                                                                     | Policies and practices ensure that the organization considers how to jointly build value with open source projects. Contributions made are likely to improve the company's reputation, not damage it.                                                                                                                                                                                                                                                                                                                                 |
| Adopt ISO/IEC 5230 (OpenChain) Compliance                                                                                        |     The OSPO can implement an international, defined standard rather than create one from the ground up.                                                                                                                                               | The organization can demonstrate its compliance with an internationally recognized standard.                                                                                                                                                                                                                                                                                                                          |
| Manage an inventory of  OSS used in the organization                                                                                     |         The OSPO is aware of the surface area of OSS it oversees.                                                                                                                                           | The organization has a base for overall risk management. This is an important tool for dealing with issues relating to specific projects (security problems, license changes, lifecycle issues, etc.)                                                                                                                                                                                                                                           |
| Training on open source awareness                                                                                          |                 Providing training on open source increases visibility of the role of open source, visibility of the OSPO and its value, and improves understanding of how the organization uses and engages with open source.                                                                                                                                   | Increases the competence present in the organization to work with OSS through an awareness of open source value, licensing, and contributions etc.                                                                                                                                                                                                                                                                             |
| Introduce tools for license compliance                                                                                     |                           Provide structure and visibility for licence compliance within the organization, which helps inform management strategy.                                                                                                                         | Automation is essential to be able to address risks with a reasonable amount of effort and measure effectiveness of efforts to improve compliance.                                                                                                                                                                                                                                                                                            |
| Clarify how to support OSS                                                                                |      Ensure that OSS is adopted with appropriate understanding of how it can be supported.                                                                                                                                               | The organization should be aware of the hidden costs of using OSS in production scenarios. External support for open source components can sometimes be bought from a vendor or a service provider. Alternatively, other options are to manage the support yourself with the help of the community (being realistic in considering what a community can be expected to support), or going with the risk of not having support which may be appropriate for scenarios where the risk is low. |

#### STAGE: Participant

| Activities                                     | Value for the OSPO | Value for the Organization                                                                                                     |
| ---------------------------------------------- | -------------- | ----------------------------------------------------------------------------------------------------------------- |
| Financially supporting open source communities | Better relationships with communities, more influence.   | Better stability in the ecosystem and software supply chain that the organization relies on.                                                  |
| Membership of open source organizations       | Membership benefits such as co-marketing, event discounts.  | Engagement with the communities the organization relies on. Potential influence and access to strategically useful information. Supporting the ecosystem.                                 |
| Trying InnerSource                             | Staff in the organization will get hands-on experience with open source methodologies, which builds awareness, understanding, and advocacy.  | The organization will build skills in its workforce that will contribute to better use of, and engagement with, open source projects.  |

#### STAGE: Contributor

| Activities                             | Value for the OSPO | Value for the  Organization                                                                                                                                                      |
| -------------------------------------- | -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Create contribution policy and process | Managing open source contributions becomes easier. | Having clear procedures means that the organization can offer open source contributions in a legally safe way, for open source projects, the organization, and its employees. |
| Qualification of contributors          | Contributors require less oversight and make good ambassadors. | Skilled contributors make better contributions into publicly visible projects. This means less risk to the organization.               |

#### STAGE: Leadership

| Activities                                                                  | Value for the OSPO | Value for the Organization                                                                                                                                                               |
| --------------------------------------------------------------------------- | -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Open sourcing previously proprietary projects                               | The OSPO can reduce the burden on the Engineering (and other) departments. | New opportunities will open up to improve the codebase of a commoditized component through collaboration in public. More strategic involvement in open source. Access to new expertise.                                                                                                           |
| Establish an "upstream first" policy                                        | Offering the organization a way to get more value for the same, or smaller, amount of effort. | The organization can support or even lead open source projects and make them part of the primary value creation of the organization without losing its competitive differences, and while benefiting from the contributions of a whole community.                                                                              |
| Supporting autonomy of contributors and maintainers of open source projects | In-house experts in open source are valuable to the OSPO. | Employing people who are dedicated to only open source work means the organization can strategically strengthen important open source projects in the most organic and effective way. |

## Possible Problems and How to Overcome Them

### Problem

The new OSPO is very slow to make recognizable progress, and doubts about the need for an OSPO creep in.

### Recommendation

As with all new ventures, it's really important to create and maintain a focus on delivering meaningful impact in the short and long term. Short term impact reassures stakeholders that the OSPO is needed and competent, and gives OSPO staff confidence. Long term impact creates sustainable value for the organization and embeds the OSPO securely in the organization. Try to identify something important that can be delivered within the first 3-6 months, while also working on longer term projects that will deliver in 6-12 months, 12-24 months and 2-5 years. Keep the list of active projects short at first to ensure that they're delivered with quality and on time. As confidence in the OSPO grows, it puts you in a stronger position to ask for more resource if you have a strong track record of delivering value.

## Resources and Footnotes

### Resources

- A Guide to Enterprise Open Source: https://www.ibrahimatlinux.com/wp-content/uploads/2022/05/LFR_LFAID_Guide_to_Enterprise_Open_Source_052522.A4.pdf
- A Deep Dive Into Open Source Program Offices: Structure, Roles, Responsibilities, and Challenges: https://8112310.fs1.hubspotusercontent-na1.net/hubfs/8112310/LF%20Research/LFR_LFAID_Deep_Dive_Open_Source_Program_Offices_081922.pdf
- OpenSSF Scorecard: https://github.com/ossf/scorecard
- Software Bill of Materials (SBOMs): https://www.ntia.gov/SBOM
- Computer Emergency Response Team (CERT): https://www.cisa.gov/uscert/

### Footnotes

[^1]: Secure Supply Chain Consumption Framework (S2C2F): https://www.microsoft.com/en-us/securityengineering/opensource/osssscframeworkguide

[^2]: OSPO Mind Map: https://todogroup.org/resources/mindmap/
