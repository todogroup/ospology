
<a href="https://ospobook.todogroup.org/"><img src="https://img.shields.io/badge/OSPO%20Book-Website-dark green?labelColor=3E9492&style=flat" alt="OSPO Book"/></a>

# 👋 Welcome to Open Source (Program) Office Book

* **Authors and co-authors (individuals):** [contributor's list](AUTHORS.md)
* **Desired mid-release Date:** August 2023 ✅
* **Desired mid-publication Date:** September 2023 ✅
* **Desired full release Date:** August 2024 ⏳
* **Desired full printed version Date:** September 2024 ⏳


> 🐣 If you are new to the project, please scroll down to `Newcommers - START HERE` and read [CONTRIBUTING.md](ospo-book/CONTRIBUTING.md)


> 👉 Ready to contribute? check the [2024 Roadmap](https://todogroup.org/blog/ospo-book-2024-roadmap/)

## 🧩 Project Description

Open source software is increasingly being adopted by organizations of all sizes and industries, making it essential for organizations to have a clear and well-defined open source strategy and operations. This guide aims to help organizations understand the value of having an Open Source Program Office (OSPO) within their organization and provide a step-by-step guide on how to create and implement an OSPO.

The guide will be aimed at organizations of all sizes and industries, including those just starting their open source journey as well as those looking to streamline and improve their existing open source operations. It will provide practical, actionable advice and real-world examples to help organizations streamline their open source operations and achieve their goals.
## 🙋‍♀️ Project Teams

|      | General   | Infra Team       | Content Team         | Review Team                 |
|-----------|-----------|------------------|------------------|-----------------------------|
| **Chair (2024)** | @anajsana    | @cjyabraham  |    @CsatariGergely                   | @alice-sowerby
| **Co-chair (2024)** | @jerpelea           | @anajsana, @koozz, @CsatariGergely            | @jimjag , @anajsana                        | @zhiqiang-yu 
| **Description** | moderates monthly calls, prepares agenda items and checks progress done | team involved in project infrastructure and website development | team involved in content creation | team involved in reviewing existing content and references |


## 🎯 Goals

The guide will cover the following topics:

1. Understanding the value of Open Source Program Offices: The guide will explore the reasons why organizations need to foster an OSPO within their organization, including increased transparency, efficiency, and innovation, and provide insight into how organizations can create an OSPO depending on their sector and region.
2. Involvement in Open Source Program Operations: The guide will provide practical tips and best practices for organizations looking to be involved in open source program operations on a daily basis, including what constitutes a minimum viable OSPO, how to create and implement an open source strategy, and a deep dive into OSPO responsibilities.
3. Measuring Success and Impact: The guide will provide guidance on how to measure the success and impact of an OSPO, including how to track and measure key performance indicators and use metrics to drive continuous improvement.


## 🐣 Newcomers - START HERE

Below is a list of resources that will help you become familiar with the process and workflow of the OSPO book project:

- **[GOVERNANCE.md](ospo-book/GOVERNANCE.md)** includes the contributor ladder
- **[Chapters](ospo-book/chapters)** contains the table of contents **outlining the main objectives of each chapter**, along with the taxonomy used and a glossary
- **[Docs](ospo-book/docs)** includes the questions for interviews, aspirational roadmap for this year and a release checklist

If you would like to start making your first contributions, we recommend [subscribing to the mailing list and introducing yourself to the group](https://lists.todogroup.org/g/ospo-book-project). The introduction can include a brief bio, your location, and how you would like to contribute to the project.

Content Contributors can help on multiple chapters or focus on one only. All these contributions are equally important and help foster a thriving community. The titles of each chapter are a rough draft to get started. The community refines and improves them through the OSPO Book Mailing list discussions, PR reviews and contributor's calls conversations.

## 💬 Communication Channels

* Mailing List with interested contributors: [Join ospo-book-project](https://lists.todogroup.org/g/ospo-book-project)
* One monthly sync call ( AMER/ EMEA and APAC/EMEA-friendly timezone) with agenda to follow up: Sent via mailing list

## 💚 Community Needs

- Create an easy-to-understand guide on everything organizations need to know on open source program offices
- Build an OSPO wiki page (combine public and existing OSPO resources and give them an order)
- Develop a collective and strategic voice to work on *missing links* required to make a comprehensive OSPO book
- Proactively search for and invite representatives from open source bodies helping organizations to streamline open source as collaborators: This includes open source leaders working in OSPOs but also individuals participating in open source communities and projects specialized and helping the open source movement within organizations across different sectors

## 📊 Methodology

The guide will be structured in a user-friendly and practical manner, making it easy for organizations to follow and implement. The methodology will consist of the following steps:

1. Research: The guide will be based on extensive research and analysis of best practices and case studies from organizations across different sectors and regions.
2. Expert Input: The guide will also include input from experts in the field of open source and Open Source Program Offices, ensuring that the advice and guidance provided are up-to-date and relevant.
3. Case Studies: The guide will include real-world examples and case studies from organizations that have successfully implemented an OSPO, providing practical insights and lessons learned.
4. Actionable Advice: The guide will provide actionable advice and steps that organizations can take to create and implement an OSPO, including templates, checklists, and practical tips.
5. Continuous Improvement: The guide will be reviewed and updated regularly to ensure that the advice and guidance provided

The methodology will be designed to help organizations streamline their open source operations and achieve their goals, providing a comprehensive and practical guide that can be used to create and implement an Open Source Program Office.

## 📖 Existing Literature & Resources


* The book will include a review of existing literature and resources on open source and Open Source Program Offices, including reports, articles, whitepapers, and books.

* The book will also provide a list of essential resources that organizations can use to further their understanding of open source and OSPOs, including online courses, webinars, and industry events.

* Additionally, the book will highlight key organizations and initiatives that are leading the way in open source and OSPOs, providing organizations with a network of resources and support as they navigate their open source journey.

This section will provide organizations with a comprehensive overview of the existing literature and resources available on open source and OSPOs, making it easy for them to access the information and support they need to create and implement an OSPO successfully.

## 👩‍⚖️ License & Attribution Notice

This work is licensed under the Creative Commons Attribution 4.0 International License. The authors of this work, Ana Jiménez Santamaría and Chris Aniszczyk, and co-authors made substantial contributions to its content and development. Also, the [co-authors](AUTHORS.md) collaborated with the authors and provided input, references, feedback, suggestions, and advice on the book's outline and content. When attributing this work, please reference the [authors](AUTHORS.md) that appear in this list.

## Setting up a local instance

To improve the OSPO Book site itself, install a local copy. Note you must have [npm](https://www.npmjs.com/) and [Hugo](https://gohugo.io/) installed.

```
git clone https://github.com/todogroup/ospology/
cd ospology
git submodule update --init --recursive
cd ospo-book
npm install
```

Then run the site using `npm run serve`. To have the site run locally with a functioning local search, run `npm run serve:with-pagefind`.
