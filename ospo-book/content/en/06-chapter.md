---
title: "Chapter 6: Using Metrics in your OSPO"
status: Completed
weight: 70
---

- [Introduction](#introduction)
- [Using Metrics to Communicate the Impact of Your OSPO](#using-metrics-to-communicate-the-impact-of-your-ospo)
- [If You Manage Open Source Projects](#if-you-manage-open-source-projects)
- [A Case of Organizational Impact](#a-case-of-organizational-impact)
- [Case Study: Using Health Metrics to Guide Open Source Intake and Strategy](#case-study-using-health-metrics-to-guide-open-source-intake-and-strategy)
- [Footnotes and Resources](#footnotes-and-resources)
  

## Introduction

> NOTE: This chapter has been developed through the collective expertise of [CHAOSS open source project](https://chaoss.community/) and participants from the CHAOSS [OSPO Metrics Working Group](https://github.com/chaoss/wg-ospo), with support from the TODO Group.

Metrics are an important part of any modern organization. When used effectively, they offer a valuable way to track the impact of your team and its projects. For an OSPO, metrics not only support planning and measuring the impact of its work—they also provide deeper insight into the open source projects the organization depends on.

In the past, it might have been acceptable to know little about key open source projects. But that’s no longer a sustainable approach as the regulatory and security landscape around open source continues to evolve. As we deepen our understanding of the open source projects that matter to us, community metrics become essential tools. In this chapter, we’ll explore how to place those metrics in context and how, together, they can offer better insights to guide strategic decisions across an organization.

There are several reasons why organizations need visibility into open source projects. For example:
* The organization is using open source and wants to track contributions to key projects.
* The organization participates in an open source ecosystem and needs to identify potential risks and offer support where necessary.
* The organization wants to contribute to the sustainability of open source software—especially the software that’s critical to its business.
* The organization must stay compliant with upstream license requirements and respond to security issues that could affect operations.

### The Goal-Question-Metric framework
Metrics for metrics' sake benefit no one. Consider these metrics: 
* The average age of issues is 10.3 days. 
* The total number of pull requests was 121 last month. 
* We had 3 new companies join our community over the past 15 days. 

Without context, these metrics provide no insight, so it's important to ensure that you use a framework like "goal-question-metric" to give you metrics that support your goals instead of working against them. 

CHAOSS advocates for using the GQM because it is a structured method for deriving metrics that align with organizational goals. It involves three key steps:

#### Goals
Identify and understand your organizational goals. These can vary significantly but typically include objectives like recruiting talent or enhancing community engagement.

#### Questions
Break down these goals into specific, actionable questions. For example, to assess recruitment efforts, one might ask, “Who are important contributors?” or “How many did we help hire?”

#### Metrics
Develop metrics to answer these questions. Metrics should be operational and data-driven, such as the number of contributions by name, hiring successes, or project activity levels. Some good data points, like the number of commits (on a software project), may not be relevant to the question you need to answer.

### Understanding the  Role of Open Source Community Metrics

It's worth taking a moment to understand how open source community metrics support the other types of metrics that organizations are familiar with. Open source community metrics provide OSPOs with tangible ways to measure the influence, effectiveness, and strategic value of their open source initiatives. 

By tracking contributions, engagement levels, and collaboration across projects, OSPOs can assess how well their organization is participating in and supporting the open source ecosystem.

These metrics help demonstrate the impact of open source work on broader business goals such as accelerating innovation, reducing development costs, attracting talent, and increasing product visibility. Metrics also provide insight into community health and sustainability, highlighting whether a project is gaining traction, fostering collaboration, and attracting active users and contributors.

By tying community metrics to organizational KPIs, OSPOs can showcase the value of open source beyond code, such as improved product feedback loops, faster time to market, stronger developer relations, and enhanced technical credibility. This playbook provides guidance for OSPOs to track, analyze, and communicate those metrics effectively, translating open source participation into measurable business impact.

## Using Metrics to Communicate the Impact of Your OSPO

Metrics play an important role in communicating impact. Following the goal-question-metric approach here are four goals that OSPOs can consider, and questions to go with them. 

<img width="750" alt="CHAOSS Health Impacts" src="https://github.com/user-attachments/assets/f13b8fd0-8342-4a90-b5cb-d533c6454801" />
   
### 1: Partner Impact

**Goal** 

Understand how open source collaboration fosters strategic partnerships that can enhance market insight, strengthen vendor relationships, and create shared value beyond individual technologies.

**Commentary** 

Open source project work is premised on collaboration, a collaboration that often involves unexpected partnerships. These partnerships are aimed at developing non-differentiating technologies that each partner needs, yet does not necessarily have the resources or inclination to produce alone. Open source projects bring together organization members to work together in the pursuit of shared problems and this proximity can result in benefits beyond any one shared open source technology. Improved open source partnerships can have positive secondary effects, including stronger ties with upstream vendors, improved understanding of market rival positions, and direct interaction with downstream users.

**Questions**
* What other companies are involved in our open source projects of interest?
* What other companies are involved in our pull requests?
* How are other companies involved in our pull requests?
* What is the composition of involved companies as our vendors, rivals, and customers? 

**Metrics**

Consider what data are available to you to be able to answer these questions, and what other information you would need to feel confident in what it would mean to your goals if the number goes up or down. 

### 2: Community Impact

**Goal**

Evaluate how employee engagement in open source communities reflects organizational support, strengthens individual skill development, and enhances the organization's presence and influence in key projects.

**Commentary**

There are ways that an organization can support community engagement by employees (e.g., contribution guidelines, intellectual property management, and license support). Support will often include why the community is important to your organization -- including a time and prioritization component in how much time an employee spends in external/upstream work. companies can observe employees as good citizens for reasons of personal and organizational gain, and help employees understand their importance in bridging between the organization and the community. 

**Questions**
* What percentage of employee contributions are merged?
* What percentage of employee issues are closed without conversation?
* How many of our employees have maintainer or leadership roles in key open source projects?
* Have upstream contributions helped modernize tech skills for employees?
* Which projects do our employees make over 50% of the contributions?

**Metrics**

Consider what data are available to you to be able to answer these questions, and what other information you would need to feel confident in what it would mean to your goals if the number goes up or down.

###  3: Ecosystem Impact

**Goal**

Monitor and contribute to the health and resilience of open source ecosystems to ensure long-term viability, reduce risk, and support the strategic sustainability of key dependencies.

**Commentary**

Working with open source is never easy as rival corporations may dominate upstream projects that your organization is interested in, upstream projects may unexpectedly change licenses, and contributor agreements, whether individual or organizational, can be complex to understand and adhere to. Clearly, such challenges can be overcome and often include strategic engagement with the projects your organization aims to benefit from. Open source ecosystems are economic and social systems comprising different companies, motivations, and requirements intended to support production and demands. In an effort to ensure the efficiency and durability of any open source ecosystem, companies must not only monitor the ecosystem's long-term viability but also engage within the ecosystem when problems are identified and stabilization is required. 

**Questions**
* What percentage of our suppliers provide open source software bills of material?
* What is the long-term viability of the open source projects we rely on?
* What is the risk to the ecosystem if an open source project becomes unviable?

**Metrics**

Consider what data are available to you to be able to answer these questions, and what other information you would need to feel confident in what it would mean to your goals if the number goes up or down.

### 4: Organizational Impact

**Goal**

Align open source engagement with internal governance, security, and product development to maximize the value of open source within organizational strategy and operations.

**Commentary**

Engagement with open source communities includes working in the upstream to effectively use open source software in organizational products. In this, there is a need to monitor the intake of open source software for infosec, legal, and engineering reasons. Companies can establish software intake processes, working with teams to either technically track or socially consider issues related to open source intake. Organization impact can also include working downstream with projects and companies that rely on your organizational products. This can include working to gain a clearer picture of  the open source that is in your shipped products. Organizations can work in securing and regulating their own internal open source processes in an effort to improve product development activities. 

**Questions**
* What characteristics does an organization inspect related to inbound open source software? 
* What product-level software and infrastructure contains open source software dependencies? 
* How is OSPO strategy aligned with organizational strategy and departmental objectives?
* How often is OPSO strategy used to guide business decision making processes?
* How does the use of open source influence organizational value?

**Metrics**

Consider what data are available to you to be able to answer these questions, and what other information you would need to feel confident in what it would mean to your goals if the number goes up or down.

## If You Manage Open Source Projects
For organizations that create and manage their own open source projects, or are closely involved in managing them, there is a series of metric-related CHAOSS [Practitioner Guides](https://chaoss.community/about-chaoss-practitioner-guides/) to guide you through identifying the right metrics for a selection of use cases.


## A Case of Organizational Impact

Absolutely! Here's a more scannable version of the case study, with subheadings and bullet points to improve readability and highlight key takeaways:

---

## Case Study: Using Health Metrics to Guide Open Source Intake and Strategy

### Introduction
As OSPOs evolve, metrics become more than just communication tools — they guide improvements to the open source projects an organization relies on. 

#### Why Project Health Matters

Open source project health is crucial for reducing risk, ensuring reliability, and making informed sourcing decisions. Health assessments can help organizations:

- Avoid risky or unmaintained dependencies  
- Decide whether to adopt, contribute to, or replace a project  
- Align open source use with internal engineering and business goals  

#### Building a Practical Health Framework

A study by Linåker et al. (2024) condensed 107 health-related indicators into 21 key aspects, grouped under themes like:

- **Community productivity and stability**
- **Governance and orchestration**
- **Development processes and outputs**

Each aspect included specific attributes to support analysis tailored to a project’s complexity, lifecycle stage, and strategic relevance.

### Example: Global Automotive Manufacturer

The same study also showcases how one global automotive manufacturer used health assessments to strengthen its open source strategy.

#### Implementing Health Checks in Practice

The organization implemented a lightweight, two-part process:

1. **Intake Health Checks**  
   - Manual reviews using standardized checklists  
   - Supported by semi-automated tooling  
   - Tailored questions focused on key health indicators  

2. **Ongoing Monitoring**  
   - Automated scans of existing dependencies  
   - CI/CD pipeline integration to flag issues early  
   - Follow-up manual inspections as needed  

#### Supporting Tools & Resources

To support their work, the organization leveraged open source tools like:

- **CHAOSS GrimoireLab and Augur** for collecting and analyzing community metrics  
- **OpenSSF Scorecards** for standardized security and project health checks  

#### Enabling Organizational Buy-In

- Regular workshops introduced teams to the process  
- Feedback loops ensured continued refinement  
- Health assessments were embedded in standard dev and QA practices  

#### Outcomes and Lessons

By operationalizing project health metrics, the OSPO:

- Reduced risk from unmaintained or vulnerable dependencies  
- Improved strategic alignment across teams  
- Contributed to upstream sustainability where needed  

This case highlights how metrics-driven intake processes help OSPOs move from reactive tracking to proactive strategy — benefiting both the organization and the wider open source ecosystem.

## Footnotes and Resources

### Resources

- [CHAOSS Practitioner Guides](https://chaoss.community/about-chaoss-practitioner-guides/)
- Linåker, J., Olsson, T., & Papatheocharous, E. (2024). How to Assess the Health of Open Source Software dependencies in an Organization's Intake Process: Insights from an Interview-survey and Case Study. Under review in a Software Engineering journal.
- [Linåker, J., Papatheocharous, E., & Olsson, T. (2022). How to characterize the health of an Open Source Software project? A snowball literature review of an emerging practice. In the 18th International Symposium on Open Collaboration. DOI](https://doi.org/10.1145/3555051.3555067)
- Lumbard, K., Germonprez, M., and Goggins, S. (2023). An Empirical Investigation of Social Comparison and Open Source Community Health, Information Systems Journal, 34(2), 499-532.
