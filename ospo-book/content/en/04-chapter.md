---
title: "A Deep Dive into Day-to-Day Operations"
status: To be Done
weight: 60
---

## WG Meetings Workflow

Brainstorming Session ✅

- Objective: Identify and list of OSPO responsibilities 
- Process: Open floor for participants to contribute ideas/share experiences 
- Outcome: Compiled list of responsibilities to be further explored 

Discussion on Scenarios Session ⏳

- Objective: Share and discuss common issues faced by open source professionals in managing day-to-day operations.
- Process: Participants share experiences and examples
  
Formulating Recommendations Session ⏳

- Objective: Develop recommendations based on shared scenarios
- Reference Format: OSPO Book Chapter 3 Recommendations
- Process: Group discussion to align on recommendations
- Outcome: Drafted recommendations for common scenarios

---

## Assignments for April 1st Call

* Content team: Complete and improve the content added below based on your input and meeting notes
* Review Team: copyright work. Include new terms that appear in this chapter in the OSPO Glosarry for reference
* Infra team: frequently check for issues and PRs related to infrastructure bugs/feature requests

---

# Introduction

Understanding the day-to-day activities of those managing open source operations within an organization is crucial for several reasons. First and foremost, it sheds light on the fundamental tasks that an OSPO must focus on to ensure the organization's 
technology strategy and aefforts aligns with open source best practices. This knowledge helps to streamline engineering processes and maintain compliance with open source licenses and security measures.

Moreover, it highlights the diverse types of values and key assets (e.g. risk management, resource allocation, training) that an OSPO brings to an organization across their different responsibilities. This way, an organization can better support its OSPO and an OSPO can better support their organization's teams.

# Defining day-to-day Operations


## Daily Operations List (WIP)

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

## Assessing Daily Operations (WIP)

|                                     | Automation in License Compliance | Automation in Security | Measuring Performance | Strategy and its impact in day-to-day operations |
|-------------------------------------|----------------------------------|-----------------------|-----------------------|--------------------------------------------------|
| Fundamental reasons for OSPOs to focus on this task | Streamline license management to facilitate easier discovery of licenses and minimize the approval processes required from developers when using open source tools. | Enable tools and best practices for integrating security measures, such as scorecards, into daily operations | Inform strategic adjustments and operational enhancements | A unified strategy influences daily operations |
| Perceived Value                     | Automation in license compliance reduces manual oversight, accelerates development workflows, and ensures compliance with open source licenses without burdening developers with lengthy approval processes | Automation in security practices and vulnerabilities exploration in open source projects allows effective risk management. | Measuring performance facilitate transparent assessment of the OSPO's effectiveness | Guiding decisions on contributions to open source projects, engagement with community initiatives, and the balancing of organization and community benefits |
| Using Open Source (Scope)           | Explore automation tools that assist developers in organizations in scanning and identifying open source licenses the can use, and speed up the compliance process. | Explore automation tools that assist developers to self-assess security risk on specific projects, without burdening them with lengthy approval processes | TBD (ping CHAOSS OSPO metrics WG to give input on this) | Enable decision makers understand the critical importance of supporting open source projects (and its community) and foundations, and the different ways to offer support |
| Contributing to Open Source (Scope) | Explore automation tools that assist developers in organizations in scanning and identifying open source licenses to projects they would like to contribute as employees, and speed up the compliance process. | Explore automation tools that assist developers to self-assess security risk on projects they would like to contribute as employees, without burdening them with lengthy approval processes | | frameworks that support strategic planning and execution |
| Tools                               | License checker for NPM ecosystem: [https://github.com/onebeyond/license-checker](https://github.com/onebeyond/license-checker) | OSFF Scorecard [https://github.com/marketplace/actions/openssf-scorecard-monitor](https://github.com/marketplace/actions/openssf-scorecard-monitor) | | |


| Personalized support / Q&A Sessions | Advocacy and Education | Community Integration | Business Assessment on Risk Management |
|-------------------------------------|------------------------|-----------------------|--------------------------------------|
| **Fundamental reasons for OSPOs to focus on this task** | Actively involve employees and managers in open source activity engagement. | Advocating for the importance of education in open source and creating resources to support it | Integrate organization's activities effectively with the open source projects and foundations (financial as well as resource support) as well as community dynamics. Map interactions with technical (engineering) versus non-technical teams (business, design team) | Assess risks that the organization is facing, including an overview of the tech stack |
| **Perceived Value** | Increase and improve open source knowledge and expertise across the organization's teams. | Ensure that people are qualified to judge a project (governance models, maturity, etc) and measure the technical debt on an open source project | Allocate effective financial and resource support to critical open source projects that organization's employees use/engages | Assistance in evaluating which open source projects to use and how to prioritize resources effectively |
| **Using Open Source (Scope)** | Answering questions on everything about open source, including license compliance, selecting open source software, and dealing with vendors | Build training and documentation, and assist teams in creating these materials across different teams | How to get sponsorship, run open source events, and integrate effectively with the open source community and its foundations. | E.g.) business assessment to determine whether optimizing SBOMs or focusing on other areas is more beneficial. (dealing with vendor-supplied software, legacy software, proprietary software) |
| **Contributing to Open Source (Scope)** | Answering questions on everything about open source, including license compliance, selecting open source software, and dealing with vendors | Providing knowledge on how to measure the technical debt on an open source project, including maturity models and governance models, is a form of educational advocacy to help projects improve and sustain | How to get sponsorship, run open source events, and integrate effectively with the open source community and its foundations. | E.g.) business assessment to determine whether optimizing SBOMs or focusing on other areas is more beneficial. (dealing with vendor-supplied software, legacy software, proprietary software) |
| **Tools / Services** | Internal developer portals / Issue tracker systems / Chatbots / webinars / AMA sessions / IRC | External open source training and certification courses, customized training courses adapted to the organization's goals | | |




## Recommendations (TBD)

### The OSPO should have secured resources for strategic contributions

- Scope: If the company has strategic targets related to open source, its OSPO should be capable to control resources to
  drive the execution of the strategy.

- Recommendation: To ensure the continuity of contributions needed for the strategy execution the OSPO should either:
    - Have a set of dedicated open source developers
    - Have a budget for company internal development resources asigned to startegic OSPO tasks
    - Have a budget to hire external developers to work on the startegic OSPO tasks 

### Scenario #12

- Scope:

- Recommendation:

## Resources (TBD)

- Materials that we have shared during the calls or related to this chapter
- Materials that we have shared during the calls or related to this chapter
- Materials that we have shared during the calls or related to this chapter

