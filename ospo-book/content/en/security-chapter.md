---
title: "Chapter 4: Security"
status: Completed
weight: 60
---

- [Introduction](#introduction)
- [Training & Education](#training-and-education)
- [Key steps](#key-steps)
- [Ways to Assess the Security of Open Source Software](#ways-to-assess-the-security-of-open-source-software)
- [Resources](#resources) - `📚 Continue Here`

## **Introduction**

Open source software is a key part of the software supply chain. It is therefore directly in the scope of an OSPO to facilitate establishing means for securing the open source software supply chain. This includes, among other tasks:

* enabling development teams to assess the security posture of open source software included in products,
* fostering the engagement of development teams in upstream projects to support improving their security posture, and
* adopting secure software development best practices in open source projects driven, maintained, or contributed to by the company.

This chapter provides pointers to material which support OSPOs and open source developers in applying secure software development and supply chain best practices, both downstream as well as upstream.

In some ways, security is simply a requirement like any other requirement. However, many software developers and their managers received inadequate training and education about security. In addition, security is about countering intelligent adversaries, and it's generally an emergent property (it isn't usually isolated to a single place).

Fixing security issues after-the-fact is often costly, so it’s wiser to take steps to prevent them, reduce their likelihood or impact, and be prepared if an incident happens anyway. It’s important to plan for resources (including money and time) to address security from the beginning. Open source software has a potential security advantage (it can undergo mass peer review and better meets a security principle called “open design”), however, not all potentials are realized.


## **Training & Education**

Many software developers and their managers don’t know what they need to know about security. This lack of knowledge often leads to many problems. Here are some key areas that are necessary to know and pointers to some free OpenSSF courses that can help. You don’t necessarily need to take these free OpenSSF courses. What’s important is to ensure that those involved in software development know what they need to know.

Managers of software developers (open or closed source) should have at least some training in how to manage the development of secure software. This includes knowing basic terminology. It also includes how to perform risk management, continuously consider security (“secure by design”), ensure all environments resist attack, evaluate risks early, and manage stakeholder expectations. Managers need to know what topics their developers need to know (to ensure developers are adequately educated and trained). Those managers who haven't had such training should consider taking the free Open Source Security Foundation ([OpenSSF](https://openssf.org)) course *[Security for Software Development Managers (LFD125)](https://training.linuxfoundation.org/training/security-for-software-development-managers-lfd125/).*

Anyone who develops software should take a course on how to develop secure software. This includes how to develop secure software during requirements, architectural design, implementation, verification, and distribution. This especially includes how to evaluate third-party software. Developers should know the common types of vulnerabilities as identified in the [OWASP Top Ten](https://owasp.org/www-project-top-ten/) (for web applications) and the [CWE Top 25](https://cwe.mitre.org/top25/) (across all software), and also know how to systemically prevent them. They should also know how to secure environments and manage vulnerability reports. Those who haven’t taken such a course should consider taking the free OpenSSF course *[Developing Secure Software (LFD121)](https://training.linuxfoundation.org/training/developing-secure-software-lfd121/)*.

Managers and developers must know the laws or regulations that they must comply with. Anyone who develops software that may be deployed in the European Union (EU), or manages those developers, needs to learn the basics of the EU Cyber Resilience Act (CRA). This includes understanding the scope of what the CRA covers, the CRA’s various roles (such as manufacturer and OSS steward), and the obligations the CRA places on those roles. We note the CRA in particular because it has a very broad scope along with steep penalties for non-compliance. If you need to learn this, you should consider taking the free OpenSSF course *Understanding the European Union (EU) Cyber Resilience Act (CRA) (LFEL1001)*.


## **Key steps**

For developing your own software:

1. Review the OpenSSF *[Concise Guide for Developing More Secure Software](https://best.openssf.org/Concise-Guide-for-Developing-More-Secure-Software )*, which provides a set of guides and links to more information.
2. Work to meet the [OpenSSF Baseline](https://baseline.openssf.org/), a short list of security-related criteria in development.
3. Earn an [OpenSSF Best Practices badge](https://www.bestpractices.dev/) for your open source project. At least earn “passing”. Plan and roadmap to eventually earn silver & gold.
4. Improve your [OpenSSF Scorecard](https://github.com/ossf/scorecard) measure. This is primarily used to evaluate other software, but it’s useful for self-evaluation too.

Nearly all software development today reuses other software. You need to select and use that software wisely. Here are some ways to help assess that:

1. Apply the [Concise Guide for Evaluating Open Source Software](https://best.openssf.org/Concise-Guide-for-Evaluating-Open-Source-Software) when evaluating OSS for reuse.
2. *Double-check* software names before using them. One of the most common attacks is “typosquatting” where malicious software is released with *almost* the correct name.
3. Use [OpenSSF Scorecard](https://github.com/ossf/scorecard) to measure software before bringing it in.

Protect your environments, including those for development, build, test, and distribution:

1. Use multi-factor authentication (MFA) so it’s harder for attackers to authenticate as authorized users.
2. Secure your build environment. See [OpenSSF SLSA](https://slsa.dev/) for more information.

Integrate *automated* tools in your continuous integration (CI) pipeline to detect some vulnerabilities as changes are made:



1. Use different kinds of tools, as different ones can find different vulnerabilites. See this [Guide to Security Tools](https://github.com/ossf/wg-security-tooling/blob/main/guide.md#readme).
2. In new projects  (“green field”), maximize detection of potential issues. In existing projects (“brown field”), slowly enable detection starting with the most critical issues (otherwise the reports will be too long to use).
3. Enable tools to detect reused components with known vulnerabilities

It’s important to be prepared for vulnerability reports, since they *can* happen to anyone. Provide clear public instructions on how to report vulnerabilities. OSS projects should consider the OpenSSF [Guide to implementing a coordinated vulnerability disclosure process for open source projects](https://github.com/ossf/oss-vulnerability-guide/blob/main/maintainer-guide.md#readme).

## **Ways to Assess the Security of Open Source Software**


```
✅ Assessment
```

We’ve noted some ways to assess the situation earlier. This includes:

1. [OpenSSF Baseline](https://baseline.openssf.org/)
2. [OpenSSF Best Practices badge](https://www.bestpractices.dev/)
3. [OpenSSF Scorecard](https://github.com/ossf/scorecard)
4. Your CI pipeline results (which may indicate security issues). This includes Software Component Analysis (SCA) results, showing which reused components have known vulnerabilities.

Perhaps most importantly, ensure that your software developers and their managers have the understanding necessary to develop secure software. The OpenSSF courses listed above all offer digital badges to show that the learner has successfully completed the course. Most other courses offer similar mechanisms to provide evidence that learners can apply the material.


## **Resources**


```
📚 Continue Here

```

* Concise Guide for Developing More Secure Software: [https://best.openssf.org/Concise-Guide-for-Developing-More-Secure-Software](https://best.openssf.org/Concise-Guide-for-Developing-More-Secure-Software) 
* Concise Guide for Evaluating Open Source Software: [https://best.openssf.org/Concise-Guide-for-Evaluating-Open-Source-Software](https://best.openssf.org/Concise-Guide-for-Evaluating-Open-Source-Software)
* [Security for Software Development Managers (LFD125)](https://training.linuxfoundation.org/training/security-for-software-development-managers-lfd125/)
* [Developing Secure Software (LFD121)](https://training.linuxfoundation.org/training/developing-secure-software-lfd121/)
