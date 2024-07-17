---
title: "4 - Day-to-Day Operations"
status: Completed
weight: 60
---


* [Introduction](#introduction)
* [Assessing Daily Operations](#assessing-maturity-of-open-source-program-office) - `✅ Assessment`
* [Recommendations](#recommendations) - `💡 Recommendations`
* [Resources](#resources) - `📚 Continue Here`

# Introduction

Understanding the day-to-day activities of those managing open source operations within an organization is important for several reasons. First and foremost, it sheds light on the fundamental tasks that an OSPO must focus on to ensure the organization's technology strategy and efforts align with open source best practices. This knowledge helps to streamline engineering processes and maintain compliance with open source licenses and security measures.

OSPO day-to-day operations encompass a broad spectrum of activities aimed at enhancing open source engagement and compliance within the organization, including:

- **Personalized Technical Support:** Involves answering questions on all aspects of open source, including license
  compliance, selecting open source software, and interactions with vendors. It also includes engaging with the
  community and partners, securing sponsorships, and organizing open source events.
  
- **Automation tools:** Efficiency in process automation is key because policies alone may not always be effective as
  they are not always followed. Managers are usually seeking effective options for automation tooling, including for
  security automation and reporting, such as the integration of scorecards.

- **Documentation, Training, and Education:** Crucial to ensure that individuals are qualified to assess projects.
  Developing training materials and documentation and aiding teams to produce these across different departments are key
  tasks.

- **Resource Allocation:** Requires a strategic approach to prioritize effectively.

- **Risk Management:** Involves assessing the risks the organization faces. Obtaining a comprehensive view of the
  organization's tech stack, such as generating SBOMs, and considering software from vendors, legacy software, and
  proprietary software is crucial. This is more about a business assessment perspective rather than just data gathering.
  Decisions need to be made on whether to optimize SBOMs or to allocate time to other areas.

- **Sponsoring Open Source Communities and Foundations:** Providing insights into the dynamics and complexities of open
  source governance and models is part of this.

- **Measuring Technical Debt:** In open source projects requires understanding maturity and governance models.

- **Coordinate with Various Parts of the Organization:** Map interactions with teams based on the OSPO flower diagram,
  distinguishing between technical questions (engineering) and non-technical questions (business, design team).

- **Advise on open source consumpiton** define a set of advices about how the company should select what open source is
  consumed and how the consumption is made. Advices can be purely technical or considerations based on open source
  project health and practices, like the
  [Secure Supply Chain Consumption Framework (S2C2F)](https://github.com/ossf/s2c2f/blob/main/specification/Secure_Supply_Chain_Consumption_Framework_(S2C2F).pdf).

## Assessing Daily Operations

### Getting started with OSPO MindMap

To get an overview of the potential activities an OSPO can handle, we recommend first examining the OSPO Mind Map. The OSPO Mind Map outlines the main responsibilities, roles, behaviors, and team sizes within the ecosystem of an Open Source Program Office.

### OSPO MindMap Limitations

The contributors to this book have identified challenges in implementing the mind map, particularly in filtering responsibilities based on the organization's level of open source engagement. Because of this, the aim of this chapter is to provide an in-depth classification of these activities, grouped by levels of open source engagement. This book uses Ibrahim H.'s open source activity engagement model—previously seen in Chapter 2—as it is less complex and not focused on corporate structures.

| Consumer / User Stage |
| --- |

| Activities                                                                                                                 | Value for OSPO                                                                                                                                     | Value for Org                                                                                                                                                                                                                                                                                                                                                                                                        |
| -------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Define open source compliance rules and practices                                                                          | Facilitate the definition of the organization's open source compliance rules and practices between the legal and business stakeholders.            | Each company has different aspects of open source compliance, interpretations of licenses and different risk appetite (e.g dealing with regulations). Having well-defined compliance rules and practices is the first step toward deterministic open source compliance                                                                                                                                               |
| Rules, and policies on using open source (criteria for using open source software, open source health)                     | A consensus built in the company related to the hygiene related to consumed open source components. The organization has clear policies to follow. | Consumed open source projects are healthy, fixing security vulnerabilities, implementing new features and release regularly.                                                                                                                                                                                                                                                                                         |
| Rules, and policies on contributing open source (criteria on how to engage in the community, how to transfer rights, CLAs) | The organization has clear policies to follow.                                                                                                     | Policies and practices ensure that there are no contributions risking company value.                                                                                                                                                                                                                                                                                                                                 |
| ISO/IEC 5230 (OpenChain) Compliance                                                                                        |                                                                                                                                                    | Clear rules how to deal with open source software following an industry accepted standard                                                                                                                                                                                                                                                                                                                            |
| Inventory of used open source software                                                                                     |                                                                                                                                                    | Base for overall risk management. Important tool to be able to deal with concrete issues of specific projects (security problems, license changes, lifecycle issues, etc.)                                                                                                                                                                                                                                           |
| Training on open source awareness                                                                                          |                                                                                                                                                    | Create essential competence in organization to deal with open source software. Awareness for fundamentals of open source licensing, etc.                                                                                                                                                                                                                                                                             |
| Introduce tools for license compliance                                                                                     |                                                                                                                                                    | Automation is essential to be able to address risks with a reasonable amount of effort. Appropriate tools help with that.                                                                                                                                                                                                                                                                                            |
| Clarify how to support open source software                                                                                |                                                                                                                                                    | For using open source software in production scenarios, appropriate support is necessary. For open source there are several options, buying it from a vendor or a service provider, doing the support yourself with the help of the community (being responsible here what to expect from a community), or also going with the risk of not having support for scenarios where the risk of not having support is low. |

| Participant Stage |
| --- |


| Activities                                     | Value for OSPO | Value for Org                                                                                                     |
| ---------------------------------------------- | -------------- | ----------------------------------------------------------------------------------------------------------------- |
| Financially supporting open source communities |                | Contribute to stability of ecosystem, the organization relies on                                                  |
| Memberships in open source organizations       |                | Engaging in the communities the organization relies on. Supporting the ecosystem.                                 |
| Trying InnerSource                             |                | Practicing open source methodologies in the protected space of the organization. Introducing open source culture. |

| Contributor Stage |
| --- |

| Activities                             | Value for OSPO | Value for Org                                                                                                                                                      |
| -------------------------------------- | -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Create contribution policy and process |                | Having clear procedures how the organization can do open source contributions in a legally safe way, for open source projects, the organization, and its employees |
| Qualification of contributors          |                | Making sure that contributors have the knowledge and skills they need to act on behalf of the company in the public space of an open source project.               |

| Leadership Stage |
| --- |

| Activities                                                                  | Value for OSPO | Value for Org                                                                                                                                                               |
| --------------------------------------------------------------------------- | -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Open sourcing previously proprietary projects                               |                | Get the benefits of strategic involvement in and with open source                                                                                                           |
| Establish an “upstream first” policy                                        |                | Lead open source projects and make them part of the primary value creation of the organization                                                                              |
| Supporting autonomy of contributors and maintainers of open source projects |                | Having people being dedicated to only open source work, the organization can strategically strengthen important open source projects in the most organic and effective way. |

## Recommendations

### Scenario #11

Social Engineering Attack on Upstream xz/liblzma: A social engineering attack targeted the xz/liblzma, an essential open source library. The attack was meticulously planned, gaining trust within the community before executing a malicious attack. This incident was discovered inadvertently by an unrelated project, underscoring the sophistication and stealthiness of such vulnerabilities. The challenge for Open Source Program Offices (OSPOs) lies in identifying and mitigating these vulnerabilities, which are not always apparent until after they occur. Despite existing procedures and policies, OSPOs recognize the need for mechanisms to proactively measure and respond to such threats.

> Recommendation
>
> 1. SBOMs Compliance Ready: Ensure that all software components are documented through Software Bill of Materials (SBOMs). This documentation helps in quickly identifying potentially compromised components once a vulnerability is disclosed.
> 
> 2. Automation Security Checks: Implement automated security checks, such as the OpenSSF Security Scorecard, to continuously evaluate the security posture of projects. This proactive measure can highlight vulnerabilities or anomalies that merit further investigation.
> 
> 3. Having a Computer Emergency Response Team (CERT) within the organization and having the OSPO collaborate closely with them. This specialized team should be equipped with the tools and authority to respond swiftly to security incidents. Pre-existing relationships within the team facilitate rapid internal communication about the > > severity of incidents.
> 
> 4. Scorecard Management: Keep security and vulnerability scorecards up to date. These scorecards should reflect the latest security checks and assessments, helping in quick decision-making during a crisis.
> 
> 5. Automated Feedback Loops: Develop well-automated feedback loops for bug reporting and fixing. Knowing who is responsible for addressing a particular bug and ensuring that this process is as automated as possible can significantly reduce response times.

### Scenario #12

OSPOs face the challenge of navigating license changes and assessing software trustworthiness. As projects like Redis have shown, altering license terms can have significant implications for use, distribution, and contribution. These changes needs clear communication and understanding of the roles and responsibilities dictated by new license terms. Furthermore, OSPOs are tasked with evaluating the trustworthiness of software, which can vary based on whether a project is maintained by a single vendor or hosted under a foundation. For instance, The Almalinux Foundation presents a case where donating a project to a foundation mitigated risks associated with single-vendor governance, thereby enhancing trust in the project.

> Recommendation
>
> 1. Educational Initiatives on License Implications: Develop educational materials and sessions for developers and users within the organization to understand the nuances of different licenses. This understanding will help them make informed decisions when using or contributing to open-source projects.
>
> 2. Explicit License Terms: Work with legal teams to ensure that license terms are as explicit and unambiguous as possible. Clear terms help in avoiding misunderstandings and potential legal conflicts.
> 
> 3. Software Trust Rating System: Implement a system to evaluate and rate the trustworthiness of software, considering factors like governance structure, maintenance practices, and community engagement. Projects hosted under reputable foundations could be rated higher for trustworthiness due to the oversight and governance provided.
> 
> 4. Encourage Foundation Hosted Projects: Advocate for donating projects to foundations to mitigate risks associated with single-vendor control. Highlight successful cases like Almalinux to illustrate the benefits of this approach, such as increased trust and community support.
> 
> 5. Stakeholder Engagement in License Decisions: Engage a broad range of stakeholders, including developers, legal advisors, and end-users, in discussions about license changes or the adoption of new projects. Their insights can help in making balanced decisions that align with the organization's values and risk tolerance

## Resources (TBD)

- Materials that we have shared during the calls or related to this chapter
- Materials that we have shared during the calls or related to this chapter
- Materials that we have shared during the calls or related to this chapter

