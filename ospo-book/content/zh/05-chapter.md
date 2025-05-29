---
title: "第5章：开源安全管理"
status: Completed
weight: 60
---

- [总体介绍](#总体介绍)
- [培训与教育](#培训与教育)
- [关键举措](#关键举措)
- [应用到您的组织](#应用到您的组织)
- [资源和脚注](#资源和脚注)

## 总体介绍

> 提示：本章节使用到了开源安全基金会（OpenSSF）的专业知识，并得到TODO Group的支持。

开源软件是软件供应链的重要组成部分。因此，OSPO开源办公室的重要职责之一就是协助实现开源软件供应链的安全性，包括如下的任务：

- 协助开发团队评估他们在产品中使用的开源软件的安全性
- 鼓励开发团队向开源上游项目提交贡献，提升其安全性
- 在公司维护、贡献或主导的开源项目中，遵循软件研发安全的最佳实践

本章节包含对OSPO开源办公室和开源软件开发者的有用资源，用于实施软件研发安全和供应链管理的最佳实践，包括他们引入和自己研发的软件。

在某个意义上，安全就是另一种功能需求。然而，很多软件研发者和他们的管理者都未得到足够的安全培训。另外安全也是涉及抵御机密窃取的攻击，这依赖与整个系统的协同工作，不仅仅是其中一环。

事后的安全问题修复常常成本高昂。较好的做法是预防安全问题，减少其概率和影响面，并为某环节出错的情况做好准备。在早期就对安全体系投入时间和财务资源是非常重要的。开源软件能够具备安全优势，因为它允许广泛的同行评审和遵循开放涉及的原则，但这些优势并不是自动就到来。

## 培训与教育

很多软件研发人员和管理者不知道为何他们需要理解安全。这些认知的缺乏常常导致问题。这里给出一些需要理解的关键领域，以及有助解决问题的OpenSSF开源机构免费课程的链接。这些课程不是强制的，但每位软件研发的从业者能获取合适的培训是非常重要的事情。

管理者（包括开源和闭源软件项目）应当理解如何管理安全的软件研发，包括理解掌握基本的安全术语，管控风险，如何把安全嵌入软件设计，如何确保全部软件环境的安全，如何预先识别风险，以及给相关方一个清晰的预期。管理者还应该知晓他们的研发人员应该学习什么安全知识。若管理者们尚未接受培训，他们可以参加开源安全基金会（OpenSSF）的免费培训 “软件研发管理者的安全培训 Security for Software Development Managers (LFD125)” [^1] 。

软件研发人员应该参加软件安全开发课程。包括如何在软件的规划、设计、编码、测试和发布各个阶段嵌入安全能力。软件研发人员还应该了解如何评估第三方软件，他们应当理解常见的被攻击点（Web应用的OWASP前十攻击点 [^2]、通用软件的CWE前25攻击点 [^3]、这些攻击点的规避方法）他们也应对知晓如何确保研发环境的安全性，如何应对安全披露报告。若他们未接受这些培训，可以参加开源安全基金会（OpenSSF）的免费培训 “开发安全软件Developing Secure Software (LFD121)” [^4]

软件研发人员和管理者都必须理解他们需要遵循的法律和监控条例。例如，所有设计在欧盟（EU）使用软件的相关方，都应当了解欧盟《网络弹性法案》（CRA, Cyber Resilience Act），这包含知晓该法案的适用面，法案定义的不同参与角色（例如制造商、开源管理者）和法律义务。由于CRA法案覆盖了较大的适用面和较强的惩罚性，受法案约束的相关方可以参加开源安全基金会（OpenSSF）的免费培训 “理解欧盟《网络弹性法案》Understanding the European Union (EU) Cyber Resilience Act (CRA) (LFEL1001)” [^5]

## 关键举措

**研发您的自有软件：**

1. 评估开源安全基金会OpenSSF的《Concise Guide for Developing More Secure Software》指引文档，文档中提供了实用资源 [^6]。

2. 致力于达到开源安全基金会OpenSSF的安全基线，其包含的安全检查项清单 [^7]。

3. 获取开源安全基金会OpenSSF的安全实践徽章，从“达标 passing”开始，并规划依次实现“银标 silver”或“金标 gold” [^8]。

4. 改进您项目的开源安全基金会OpenSSF安全评分表 Scorecard 得分，这个评分表常常用来评估外部外部项目，也可以为您评估您自己的项目 [^9]。

**大部分现代软件重用了外部软件，选用开源组件需严谨：**

1. 使用开源软件简要评估 [^10]。 

2. 仔细检查软件名称以规避“近似名称”攻击（恶意软件包使用与可信软件包近似的名称）。

3. 使用开源安全基金会OpenSSF安全评分表 Scorecard，在引入外部软件时先评估其安全评分表得分。

**保护你的软件环境，包括研发、构建、测试和分发环境：**

1. 使用多因素认证（MFA），增大攻击者访问难度。

2. 安全加固您的构建环境，请参考开源安全基金会OpenSSF发布的SLSA规范作为指引 [^11]。

**在您的持续集成流水线中使用自动化工具，提早发现安全问题：**

1. 使用多类型工具，每一种工具可以发现不同的安全问题，请参考 the Guide to Security Tools [^12]。

2. 对新建类型的项目（绿地项目），要执行全部安全检测。对存量类型项目（棕地项目），以最重要的安全检测为启动，确保检测报告的可管控。

3. 对复用组件，启用安全工具来检测已知的攻击点。 

为安全风险披露报告做好准备，任何项目都会面对这种情况。要告知人们如何提交安全风险点。开源项目需要评估开源安全基金会OpenSSF的指引，实施安全风险披露流程 [^13]。

## 如何在您的组织机构中实施

提升您所在组织机构的开源安全水平不仅仅是使用工具，也涉及到企业文化和日常工作流程。启动工作之一是灌输这个安全理念，安全是全部人的责任而不仅仅是小团队的工作。领导者需清晰地表达软件安全研发的重要性，为这个工作提供持续的支持、资源投入和对相关责任团队的认可。

软件安全实践应纳入日常的研发工作，而不是分离的独立工作。例如，替换掉安全检测只会偶尔执行一次的模式，改为常态化的CI/CD流水线中执行漏洞扫描和生成安全打分卡的模式。这会让软件安全成为您团队认同的理念和纳入预期。

培训和教育应常态化定期执行，而不是一次性工作。研发人员和管理者应被鼓励学习软件安全研发的基础知识，包括开源安全基金会OpenSSF的免费和其他课程。要确保您的团队知晓安全非常重要，并会获得认可，这会构建长期的兴趣和责任感。

对安全改进的开放心态是非常有用的，要鼓励团队跟踪和分享他们的任务进展，例如获得最佳实践徽章，或提升他们的安全打分卡成绩。这会带来相互帮助和改进的积极团队文化，而不是发生错漏时的相互指责。

最后，要支持持续的改进。软件安全不是一劳永逸的工作，它始终在变化。要设置常态化的风险评估时间计划，更新工具和实践流程，分享您团队的经验，让研发团队可以自主和预先决定研发流程中的安全工作，而不是在最后阶段或发生问题时才实施。

通过构建责任共担文化、在日常工作中嵌入安全任务、投入资源学习、鼓励开放、持续改进等工作，您的组织机构可以实现开源软件安全开发和使用的实质性提升。

## 资源和脚注

### 资源

- OpenSSF: https://openssf.org
- OWASP: https://owasp.org/
- CWE: https://cwe.mitre.org/index.html

### 脚注

[^1]: Open Source Security Foundation OpenSSF course *Security for Software Development Managers (LFD125)*
 https://training.linuxfoundation.org/training/security-for-software-development-managers-lfd125/.

[^2]: OWASP Top Ten for web apps: https://owasp.org/www-project-top-ten/

[^3]: CWE Top 25 for general software: https://cwe.mitre.org/top25/

[^4]: OpenSSF course Developing Secure Software (LFD121): https://training.linuxfoundation.org/training/developing-secure-software-lfd121/

[^5]: https://training.linuxfoundation.org/express-learning/understanding-the-eu-cyber-resilience-act-cra-lfel1001/

[^6]: Concise Guide for Developing More Secure Software: https://best.openssf.org/Concise-Guide-for-Developing-More-Secure-Software

[^7]: https://baseline.openssf.org/

[^8]: OpenSSF Best Practices badge https://www.bestpractices.dev/

[^9]: OpenSSF Scorecard: https://github.com/ossf/scorecard

[^10]: Concise Guide for Evaluating Open Source Software: https://best.openssf.org/Concise-Guide-for-Evaluating-Open-Source-Software

[^11]: OpenSSF SLSA: https://slsa.dev/

[^12]: Guide to Security Tools: https://github.com/ossf/wg-security-tooling/blob/main/guide.md#readme

[^13]: OpenSSF Guide to implementing a coordinated vulnerability disclosure process:
https://github.com/ossf/oss-vulnerability-guide/blob/main/maintainer-guide.md#readme
