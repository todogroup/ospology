---
title: "Chapter 5: Managing Open Source Security"
status: Completed
weight: 60
---

- [Introduction](#introduction)
- [Training and Education](#training-and-education)
- [Key Steps](#key-steps)
- [Applying This to Your Organization](#applying-this-to-your-organization)
- [Footnotes and Resources](#footnotes-and-resources)

## Introduction

> NOTE: This chapter has been developed through the expertise of Open Source Security Foundation (OpenSSF) representatives, with support from the TODO Group

Open source software is an important part of the software supply chain. Because of this, it is part of an OSPO’s responsibility to help secure the open source software supply chain. This includes tasks such as:

- Helping development teams assess the security of the open source software they use in products.

- Encouraging development teams to contribute to upstream open source projects to help improve their security.

- Following secure software development best practices in open source projects that the company maintains, contributes to, or leads.

This chapter includes useful resources to help OSPOs and open source developers apply secure software development and supply chain best practices - both in the software they use and the software they create.

In some ways, security is just like any other requirement. However, many software developers and their managers have not received enough training in security. Also, security is about defending against intelligent attackers, and it often depends on how the entire system works together — not just on one part.

Fixing security problems later is often expensive. It is better to prevent them, reduce their chances or impact, and be prepared in case something still goes wrong. It’s important to plan from the beginning and allocate resources (such as time and money) to handle security properly. Open source software can have a security advantage because it allows for mass peer review and follows the principle of “open design”—but these benefits don’t happen automatically.


## Training and Education

Many software developers and managers don’t know what they need to know about security. This lack of knowledge often causes problems. Here are some key areas to understand, along with links to free OpenSSF courses that can help. These specific courses are not required, but it is important that everyone involved in software development gets the right training.

Managers (of both open and closed source projects) should understand how to manage secure software development. This includes knowing basic security terms, how to manage risks, how to build security into the design, how to protect all environments, how to identify risks early, and how to set clear expectations with stakeholders. Managers should also understand what their developers need to learn. If they haven’t been trained yet, they can take the free OpenSSF course Security for Software Development Managers (LFD125).
 Open Source Security Foundation ([OpenSSF](https://openssf.org)) course *[Security for Software Development Managers (LFD125)](https://training.linuxfoundation.org/training/security-for-software-development-managers-lfd125/).

Developers should take a course on secure software development. This includes how to build secure software during planning, design, coding, testing, and release. Developers also need to know how to evaluate third-party software. They should understand common vulnerabilities (like those in the OWASP Top Ten for web apps and CWE Top 25 for general software) and how to avoid them. They should also know how to secure development environments and respond to vulnerability reports. If they haven't had this training, they can take the free OpenSSF course Developing Secure Software (LFD121).
 [OWASP Top Ten](https://owasp.org/www-project-top-ten/) (for web applications) and the [CWE Top 25](https://cwe.mitre.org/top25/) (across all software),  OpenSSF course *[Developing Secure Software (LFD121)](https://training.linuxfoundation.org/training/developing-secure-software-lfd121/)


Both developers and managers must understand any laws or regulations they need to follow. For example, anyone involved in software that may be used in the European Union (EU) should understand the EU Cyber Resilience Act (CRA). This includes knowing what the CRA applies to, the different roles it defines (such as manufacturer or open source steward), and the legal responsibilities it creates. Because the CRA covers a wide range and includes strong penalties, those who need to understand it can take the free OpenSSF course Understanding the European Union (EU) Cyber Resilience Act (CRA) (LFEL1001).

## Key Steps

For developing your own software:

1. Review the OpenSSF Concise Guide for Developing More Secure Software, which links to practical resources

1. Work to meet the OpenSSF Baseline, a short list of security checks

1. Earn an OpenSSF Best Practices badge for your project. Start with “passing” and plan to achieve “silver” or “gold” over time

1. Improve your OpenSSF Scorecard score. While this is often used to evaluate other projects, it can also help you measure your own

[Concise Guide for Developing More Secure Software](https://best.openssf.org/Concise-Guide-for-Developing-More-Secure-Software )
[OpenSSF Baseline](https://baseline.openssf.org/)
[OpenSSF Best Practices badge](https://www.bestpractices.dev/)
[OpenSSF Scorecard](https://github.com/ossf/scorecard) 

Most modern software reuses other software. Choose and use open source components carefully. Here’s how:

1. Use the Concise Guide for Evaluating Open Source Software

2. Double-check software names to avoid “typosquatting” attacks (where malicious packages have names similar to trusted ones)

3. Use the OpenSSF Scorecard to evaluate software before using it

[Concise Guide for Evaluating Open Source Software](https://best.openssf.org/Concise-Guide-for-Evaluating-Open-Source-Software)
[OpenSSF Scorecard](https://github.com/ossf/scorecard)

Protect your environments, including development, build, test, and distribution:

1. Use multi-factor authentication (MFA) to make it harder for attackers to gain access.
2. Secure your build environment. See [OpenSSF SLSA](https://slsa.dev/) for more guidance.

Use automated tools in your continuous integration (CI) pipeline to catch security issues early:

1. Use multiple types of tools, as each may find different problems (see the Guide to Security Tools)

1. For new projects (“green field”), enable all security checks. For older projects (“brown field”), start with the most important checks so the reports are manageable

1. Enable tools that detect known vulnerabilities in reused components


[Guide to Security Tools](https://github.com/ossf/wg-security-tooling/blob/main/guide.md#readme).

Prepare for vulnerability reports — they can happen to any project. Clearly explain how people can report vulnerabilities. Open source projects should review the OpenSSF Guide to implementing a coordinated vulnerability disclosure process.
(https://github.com/ossf/oss-vulnerability-guide/blob/main/maintainer-guide.md#readme).

## Applying This to Your Organization
Improving the security of open source software in your organization is not just about using tools. It also requires changes in culture and daily work processes. One of the first steps is to build a mindset where security is everyone’s responsibility, not just the job of a small team. Leaders should clearly communicate that secure software development is important and support this with time, resources, and recognition for those who work on it.

Security practices should be part of everyday development work, not something separate. For example, instead of running security checks only once in a while, make tools like scorecards and vulnerability scans part of your regular CI/CD pipeline. This helps make security a normal and expected part of how your team builds software.

Training and education should happen regularly, not just once. Developers and managers should be encouraged to learn the basics of secure software development. This can include free OpenSSF courses and other programs. Make sure your teams know that learning about security is important and will be recognized. This builds long-term interest and responsibility.

It also helps to be open about security progress. Encourage teams to track and share their progress on goals like earning Best Practices badges or improving their Scorecard results. This creates a positive environment where teams help each other and improve together, instead of feeling blamed when something goes wrong.

Lastly, support continuous improvement. Security is not something you finish—it’s always changing. Set up regular times to review risks, update tools and practices, and share what your teams have learned. Give teams the freedom to make decisions about security early in the development process, not just at the end or after a problem happens.

By creating a culture of shared responsibility, adding security into everyday work, investing in learning, encouraging openness, and improving over time, your organization can make real progress in securing the open source software it builds and uses.


## Footnotes and Resources

### Footnotes

### Resources
- Concise Guide for Developing More Secure Software: [https://best.openssf.org/Concise-Guide-for-Developing-More-Secure-Software](https://best.openssf.org/Concise-Guide-for-Developing-More-Secure-Software) 
- Concise Guide for Evaluating Open Source Software: [https://best.openssf.org/Concise-Guide-for-Evaluating-Open-Source-Software](https://best.openssf.org/Concise-Guide-for-Evaluating-Open-Source-Software)
- [Security for Software Development Managers (LFD125)](https://training.linuxfoundation.org/training/security-for-software-development-managers-lfd125/)
- [Developing Secure Software (LFD121)](https://training.linuxfoundation.org/training/developing-secure-software-lfd121/)
