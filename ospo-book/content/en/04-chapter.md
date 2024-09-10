---
title: "4 - Day-to-Day Operations"
status: Completed
weight: 60
---


- [Introduction](#introduction)
  - [Assessing Daily Operations using the OSPO MindMap](#assessing-daily-operations-using-the-ospo-mindmap) - `✅ Assessment`
    - [Getting started with OSPO MindMap](#getting-started-with-ospo-mindmap)
    - [OSPO MindMap Limitations](#ospo-mindmap-limitations)
  - [Recommendations](#recommendations)
    - [Scenario #10](#scenario-10)
    - [Scenario #11](#scenario-11)
  - [Resources (TBD)](#resources-tbd) - `📚 Continue Here`

# Introduction

OSPO day-to-day operations encompass a broad spectrum of activities aimed at enhancing open source engagement and compliance within the organization, including:

- **Direct Open Source Support:** Involves answering questions on all aspects of open source, including license
  compliance, selecting open source software, and interactions with vendors. It also includes engaging with the
  community and partners, securing sponsorships, and organizing open source events.
  
- **Automation Tools:** Creating process automation to support open source policies is important because policies alone may not always be effective. Managers know that their workers will not always follow policy and therefore want effective options to automate use, management and tracking of open source components.  Automation is useful in many areas of open source including licence compliance, and security.

- **Documentation, Training, and Education:** An OSPO can play a leading role in ensuring that individuals are qualified to assess open source projects for use in the organization. Developing training materials and documentation and/or aiding teams to produce these across different departments are key
  tasks.

- **Resource Allocation:** There can be a lot of areas that an OSPO can offer value to an organization. Therefore, prioritizing work and allocating resources strategically and tactically is an important activity that will improve the OSPO's impact. 

- **Risk Management:** OSPOs are well-placed to take a holistic view on the risk that the organization faces when using open source projects. It is useful for the OSPO to assess the risks by obtaining a comprehensive view of the organization's tech stack. This may include generating SBOMs which allow the OSPO to  consider the risks in software from vendors, legacy software, and proprietary software as well as in open source. This is more about a business assessment perspective rather than just data gathering, as risk can only be managed, not eliminated. Optimizing SBOMs is about balancing risks against benefits.  

- **Sponsoring Open Source Communities and Foundations:** Your organization depends on open source. The projects in open source are only as healthy as their communities, and you can invest your time and money in supporting communities either directly or through Foundations. These relationships need to be understood and managed with care to achieve outcomes that will benefit the projects and your organization. Sometimes money is not the best fix for a problem, and fostering a closer partnership and providing development, marketing, or programmatic support is more useful. 

- **Measuring Technical Debt:** Providing knowledge on how to measure the technical debt on an open source project helps to determine the risks associated with the project and, when done in collaboration with the project community, is a form of educational advocacy to help projects improve and sustain themselves.

- **Coordinating with Various Parts of the Organization:** It can be helpful to check that you know all your stakeholders, and have the right amount of interaction with them. Take a look at the OSPO flower diagram (Chapter 3) for help mapping interactions.

- **Giving Advice on Open Source Consumption:** The OSPO considers both the strategic view on which open source projects to consume and on the best practice for using the selected projects. The OSPO should provide reference materials and guidance on how the company should select which open source projects it uses and how it manages them. Guidelines and policy can be purely technical or can include considerations based on open source project health and practices, like the [Secure Supply Chain Consumption Framework (S2C2F)](https://github.com/ossf/s2c2f/blob/main/specification/Secure_Supply_Chain_Consumption_Framework_(S2C2F).pdf).

## Assessing Daily Operations using the OSPO MindMap

### Getting Started with OSPO MindMap

To get an overview of the potential activities of an OSPO we offer you the OSPO Mind Map. The OSPO Mind Map outlines the main responsibilities, roles, behaviors, and team sizes within the ecosystem of an OSPO.

### OSPO MindMap Limitations

The contributors to this book have identified challenges in implementing the mind map, particularly in filtering responsibilities based on the organization's level of open source engagement. Because of this, the aim of this chapter is to provide an in-depth classification of these activities, grouped by levels of open source engagement. This book uses Ibrahim H.'s open source activity engagement model — previously seen in Chapter 2 — as it is relatively simple, and is not focused on corporate structures.

| Consumer / User Stage |
| --- |

| Activities                                                                                                                 | Value for the OSPO                                                                                                                                     | Value for the  Organization                                                                                                                                                                                                                                                                                                                                                                                                        |
| -------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Define open source compliance rules and practices                                                                          | An explicit consensus on the organization's open source compliance rules and practices between the legal and business stakeholders.            | The organization knows that it has a managed approach to the legal aspects of open source consumption, which can be maintained and improved over time. Each company has different aspects of open source compliance, interpretations of licenses and different risk appetite (e.g dealing with regulations). Having well-defined compliance rules and practices is the first step toward deterministic open source compliance                                                                                                                                               |
| Define rules and policies on using open source (criteria for using open source software which relate to open source health)                     | Consumption of open source projects is not just viewed through the compliance lens, but is considered more holistically and includes the risks associated with unhealthy projects. A consensus is built in the company related to the hygiene related to consumed open source components. The organization has clear policies to follow. | Consumed open source projects are lower in risk because they are healthy, fixing security vulnerabilities, implementing new features and release regularly.                                                                                                                                                                                                                                                                                         |
| Define rules and policies on how to contribute to open source (criteria on how to engage in the community, how to transfer rights, Contributor License Agreements) | The OSPO can increase awareness of the two-way relationship with open source projects. Using policies supports a consistent and ethical approach. The organization has clear policies to follow.                                                                                                     | Policies and practices ensure that the organization considers how to jointly build value with open source projects. Contributions made are likely to improve the company reputation, not damage it.                                                                                                                                                                                                                                                                                                                                 | 
| Adopt ISO/IEC 5230 (OpenChain) Compliance                                                                                        |     The OSPO can implement an international, defined standard rather than creating one from the ground up.                                                                                                                                               | The organization can demonstrate its compliance with an internationally-recognized standard.                                                                                                                                                                                                                                                                                                                          |
| Manage an inventory of  open source software used in the organization                                                                                     |         The OSPO is aware of the surface area of open source software it is overseeing.                                                                                                                                           | The organization has a base for overall risk management. This is an important tool for dealing with issues relating to specific projects (security problems, license changes, lifecycle issues, etc.)                                                                                                                                                                                                                                           |
| Training on open source awareness                                                                                          |                 Providing training on open source increases visibility of the role of open source, visibility of the OSPO and its value, and improves understanding of how the organization uses and engages with open source.                                                                                                                                   | Increases the competence present in the organization to work with open source software through an awareness of open source value, licensing, and contributions etc.                                                                                                                                                                                                                                                                             |
| Introduce tools for license compliance                                                                                     |                           Provide structure and visibility for licence compliance within the organization, which helps inform management strategy.                                                                                                                         | Automation is essential to be able to address risks with a reasonable amount of effort and measure effectiveness of efforts to improve compliance.                                                                                                                                                                                                                                                                                            |
| Clarify how to support open source software                                                                                |      Ensure that open source software is adopted with appropriate understanding of how it can be supported.                                                                                                                                               | The organization should be aware of the hidden costs of using open source software in production scenarios. External support for open source components can sometimes be bought from a vendor or a service provider. Alternatively, other options are to managed the support yourself with the help of the community (being realistic in considering what a community can be expected to support), or going with the risk of not having support which may be appropriate for scenarios where the risk is low. |

| Participant Stage |
| --- |


| Activities                                     | Value for the OSPO | Value for the Organization                                                                                                     |
| ---------------------------------------------- | -------------- | ----------------------------------------------------------------------------------------------------------------- |
| Financially supporting open source communities | Better relationship with communities, more influence.   | Better stability in the ecosystem and software supply chain that the organization relies on.                                                  |
| Membership of open source organizations       | Membership benefits such as co-marketing, event discounts.  | Engagement with the communities the organization relies on. Potential influence and access to strategically useful information. Supporting the ecosystem.                                 |
| Trying InnerSource                             | Staff in the organization will get hands-on experience with open source methodologies, which builds awareness, understanding, and advocacy.  | The organization will build skills in its workforce that will contribute to better use of, and engagement with, open source projects.  |

| Contributor Stage |
| --- |

| Activities                             | Value for the OSPO | Value for the  Organization                                                                                                                                                      |
| -------------------------------------- | -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Create contribution policy and process | Managing open source contributions becomes easier. | Having clear procedures means that the organization can offer open source contributions in a legally safe way, for open source projects, the organization, and its employees. |
| Qualification of contributors          | Contributors require less oversight and make good ambassadors. | Skilled contributors make better contributions into publicly-visible projects. This means less risk to the organization.               |

| Leadership Stage |
| --- |

| Activities                                                                  | Value for the OSPO | Value for the Organization                                                                                                                                                               |
| --------------------------------------------------------------------------- | -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Open sourcing previously proprietary projects                               | The OSPO can reduce the burden on the Engineering (and other) departments. | New opportunities will open up to improve the codebase of a commoditized component through collaboration in public. More strategic involvement in open source. Access to new expertise.                                                                                                           |
| Establish an “upstream first” policy                                        | Offering the organization a way to get more value for the same, or smaller, amount of effort. | The organization can support or even lead open source projects and make them part of the primary value creation of the organization without losing its competitive differences, and while benefiting from the contributions of a whole community.                                                                              |
| Supporting autonomy of contributors and maintainers of open source projects | In-house experts in open source are valuable to the OSPO. | Employing people who are dedicated to only open source work means the organization can strategically strengthen important open source projects in the most organic and effective way. |

## Recommendations

### Scenario #10

Social Engineering Attack on Upstream xz/liblzma: A [social engineering attack targeted the xz/liblzma](https://research.swtch.com/xz-timeline), an essential open source library. The attack was meticulously planned, gaining trust within the community before executing a malicious attack. This incident was discovered inadvertently by an unrelated project, underscoring the sophistication and stealthiness of such vulnerabilities. The challenge for Open Source Program Offices (OSPOs) lies in identifying and mitigating these vulnerabilities, which are not always apparent until after they occur. Despite existing procedures and policies, OSPOs recognize the need for mechanisms to proactively measure and respond to such threats.

> Recommendation
>
> 1. SBOMs Compliance Ready: Ensure that all software components are documented through Software Bill of Materials (SBOMs). This documentation helps in quickly identifying potentially compromised components once a vulnerability is disclosed.
> 
> 2. Automation Security Checks: Implement automated security checks, such as the OpenSSF Security Scorecard, to continuously evaluate the security posture of projects. This proactive measure can highlight vulnerabilities or anomalies that merit further investigation.
> 
> 3. Having a Computer Emergency Response Team (CERT) within the organization and having the OSPO collaborate closely with them. This specialized team should be equipped with the tools and authority to respond swiftly to security incidents. Pre-existing relationships within the team facilitate rapid internal communication about the severity of incidents.
> 
> 4. Scorecard Management: Keep security and vulnerability scorecards up to date. These scorecards should reflect the latest security checks and assessments, helping in quick decision-making during a crisis.
> 
> 5. Automated Feedback Loops: Develop well-automated feedback loops for bug reporting and fixing. Knowing who is responsible for addressing a particular bug and ensuring that this process is as automated as possible can significantly reduce response times.

### Scenario #11

Licence changes on an Open Source project. OSPOs face the challenge of navigating license changes and assessing software trustworthiness. When [projects like Redis change their terms](https://www.theregister.com/2024/03/22/redis_changes_license/) it can have significant implications for use, distribution, and contribution. OSPOs need to communicate these changes clearly and understand the roles and responsibilities dictated by new license terms. Furthermore, OSPOs are tasked with evaluating the trustworthiness of software, which can vary based on whether a project is maintained by a single vendor or hosted under a foundation. For instance, The [AlmaLinux OS Foundation](https://thenewstack.io/jack-aboutboul-how-almalinux-came-to-be-and-why-it-was-needed/) presents a case where donating a project to a foundation mitigated risks associated with single-vendor governance, thereby enhancing trust in the project.

> Recommendation
>
> 1. Educational Initiatives on License Implications: Develop educational materials and sessions for developers and users within the organization to understand the nuances of different licenses. This understanding will help them make informed decisions when using or contributing to open-source projects.
>
> 2. Explicit License Terms: Work with legal teams to ensure that license terms are as explicit and unambiguous as possible. Clear terms help in avoiding misunderstandings and potential legal conflicts.
> 
> 3. Software Trust Rating System: Implement a system to evaluate and rate the trustworthiness of software, considering factors like governance structure, maintenance practices, and community engagement. Projects hosted under reputable foundations could be rated higher for trustworthiness due to the oversight and governance provided.
> 
> 4. Encourage Foundation Hosted Projects: Advocate for donating projects to foundations to mitigate risks associated with single-vendor control. Highlight successful cases like AlmaLinux to illustrate the benefits of this approach, such as increased trust and community support.
> 
> 5. Stakeholder Engagement in License Decisions: Engage a broad range of stakeholders, including developers, legal advisors, and end users, in discussions about license changes or the adoption of new projects. Their insights can help in making balanced decisions that align with the organization's values and risk tolerance

## Resources (TBD)

- Materials that we have shared during the calls or related to this chapter
- Materials that we have shared during the calls or related to this chapter
- Materials that we have shared during the calls or related to this chapter

