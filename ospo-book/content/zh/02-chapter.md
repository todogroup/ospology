---
title: "第2章：开源办公室 OSPO 的价值"
status: Completed
weight: 40
---

- [简介](#introduction)
- [您的OSPO如何增值?](#how-could-your-ospo-add-value)
- [将此应用于您的组织](#applying-this-to-your-organization)
- [OSPO价值示例](#examples-of-the-ospos-value)
- [可能存在的问题以及解决方法](#possible-problems-and-how-to-overcome-them)
- [资源和脚注](#resources-and-footnotes)

## 简介

Your organization probably already has a relationship with open source, even if it's not aware of it. Almost all software produced today includes open source components, or is developed or hosted using open source tools. Even organizations that don't *make* software usually *use* software that contains open source components.
您的企业可能已经和开源息息相关，虽然企业本身可能还没有意识到这一点。今天生产的几乎所有软件都包含开源组件，或者是使用开源工具开发或托管的。即使是不制作软件的组织，通常也会使用包含开源组件的软件。
For many organizations, it's worth considering how actively managing their relationship with open source can bring benefits and reduce risks. As mentioned in the previous chapter, this involves understanding the current use of open source and then assessing how this could be managed better to support organizational goals.
对于许多组织来说，值得考虑的是，积极管理他们与开源的关系可以带来好处并降低风险。如前一章所述，这涉及了解开源的当前使用情况，然后评估如何更好地管理开源以支持组织目标。
This chapter will help you to understand the possible areas where managing open source through an OSPO can bring value to your organization. This will be different for every organization, so knowing your organization's strategy and goals is important.
本章将帮助您了解通过OSPO管理开源可以为您的组织带来价值的可能领域。这对每个组织来说都是不同的，因此了解组织的战略和目标非常重要。
The work of an OSPO is to understand where open source can bring value to its organization, and to actively manage or oversee all related activities.
OSPO的工作是了解开源可以为其组织带来价值的地方，并积极管理或监督所有相关活动。
Every organization will have its own reasons for wanting to start an OSPO, some common reasons given in the *business value of the OSPO report* [^1] are as follows:
每个组织都有自己想要创办OSPO的原因，OSPO报告的商业价值中给出的一些常见原因如下：
- Building standardized processes around open source
- 围绕开源构建标准化流程
- Learning how to approach the open source community
- 学习如何接近开源社区
- Embracing the sustainability of open source projects
- 拥抱开源项目的可持续性
- Managing compliance
- 管理合规性
- Expanding access to open knowledge
- 扩大开放知识的获取
- Improving development velocity
- 提高开发速度
- Mitigating security risks
- 减轻安全风险
## How Could Your OSPO Add Value?
## 如何增值您的OSPO?
### If You Make Software
### 如果你制作软件
This is a common and relatively comprehensive use case for an OSPO. Other organizations may only need to consider a subset of these issues.
这是OSPO的一个常见且相对全面的用例。其他组织可能只需要考虑这些问题的一个子集。
Sometimes, organizational stakeholders assume that their product isn't using any open source components because their end product isn't open source. However, when you look at the entire software supply chain you can see that nearly all software contains open source dependencies or artifacts. If the contributors working on those open source projects decided to leave, the project could become obsolete or a target for security vulnerabilities. This affects any software the organization uses or sells, and could directly impact its reputation, performance, or revenue.
有时，组织利益相关者认为他们的产品没有使用任何开源组件，因为他们的最终产品不是开源的。然而，当你观察整个软件供应链时，你可以看到几乎所有的软件都包含开源依赖关系或工件。如果从事这些开源项目的贡献者决定离开，该项目可能会过时或成为安全漏洞的目标。这会影响组织使用或销售的任何软件，并可能直接影响其声誉、性能或收入。
An OSPO can help by understanding and actively managing use of open source components in your software.
OSPO可以通过了解和积极管理软件中开源组件的使用来提供帮助。
#### How the OSPO Helps
#### OSPO如何提供帮助
- **Managing Vulnerabilities:** Open source projects can be a source of security vulnerabilities in a product that depends upon them. It can be hard to keep track of how open source projects are being used by your organization and to perform risk assessments on the identified projects. When you identify key projects within the organization, you can prioritize securing them by tracking common vulnerabilities and exposures. Often, the Enterprise Architecture team are the ones tracking the open source components of applications and technologies, and OSPOs are there to give subject matter expertise.
-**管理漏洞：**开源项目可能是依赖于它们的产品中安全漏洞的来源。很难跟踪您的组织如何使用开源项目，也很难对已识别的项目进行风险评估。当您确定组织内的关键项目时，您可以通过跟踪常见漏洞和暴露来优先保护它们。通常，企业架构团队负责跟踪应用程序和技术的开源组件，OSPO在那里提供主题专业知识。
- **Understanding Risks in the Supply Chain:** The open source landscape is large and decentralized, and it can be hard to identify who the contributors to individual projects are and to perform risk assessments on the identified projects. These factors can make it challenging for organizations to accurately assess risks and to comprehend the security and quality standards of the software, hardware, data, etc.
-**了解供应链中的风险：**开源环境庞大且分散，很难确定单个项目的贡献者是谁，也很难对确定的项目进行风险评估。这些因素可能使组织难以准确评估风险，并理解软件、硬件、数据等的安全和质量标准。
- **Building Healthy Relationships with Key Open Source Projects:** Commercial organizations that are using open source are often keen to contribute back to the projects they use. However, the pressure to ship features in their own products means that open source contributions may take a back seat when things get busy. Even when it's known that contributing features and bugfixes to upstream is less effort in the long term than to maintain a fork of the project, organisations often optimize for short term benefits and don't spend the extra effort to upstream the changes.
-**与关键开源项目建立健康的关系：**使用开源的商业组织通常热衷于为他们使用的项目做出贡献。然而，在自己的产品中发布功能的压力意味着，当事情变得繁忙时，开源贡献可能会退居二线。即使众所周知，从长远来看，为上游贡献功能和错误修复比维护项目的分支要少，组织也经常为了短期利益进行优化，而不是花费额外的精力来上游进行更改。
- **Supporting and Influencing Key Open Source Projects:** Your organization could be in a good position to provide resources to open source projects. That could be through coding, expertise, or money donations as incentives for fixing common vulnerabilities. It could also be productive to collaborate with industry working groups to address security concerns holistically. Making a plan that aligns with your organizational strategy and provides value to the open source projects is a good way to be a helpful community member.
-**支持和影响关键开源项目：**您的组织可以很好地为开源项目提供资源。这可以通过编码、专业知识或捐款来激励修复常见漏洞。与行业工作组合作，全面解决安全问题也可能富有成效。制定一个与你的组织战略相一致并为开源项目提供价值的计划是成为一个乐于助人的社区成员的好方法。
- **Bridging the Gap Between Regulated Processes and Open Source Processes:** Open source is a dynamic ecosystem whose contributions should occur as smoothly and naturally as possible. The long procurement processes faced in highly regulated environments, such as finance companies and governments, create a barrier to open source contribution and engagement.
-**弥合受监管流程和开源流程之间的差距：**开源是一个动态的生态系统，其贡献应尽可能平稳自然地发生。在金融公司和政府等高度监管的环境中面临的漫长采购过程，对开源贡献和参与造成了障碍。
- **Improving Open Source Literacy to Ensure a High-Benefit, Low-Risk Approach:** The concept of open source may not be taken seriously in other areas of the organization involved in decision-making processes, management, or policy making. This will require constant education and demonstration of the risks and value of open source in the organization.
-**提高开源素养以确保高效益、低风险的方法：**在参与决策过程、管理或政策制定的组织其他领域，开源的概念可能不会被认真对待。这将需要在组织中不断教育和展示开源的风险和价值。
To get the most benefit from open source, and to reduce the risks, organizations must invest in properly managing open source operations on both cultural and practical levels. This is often accomplished through the OSPO, as it fosters committed, cross-functional collaboration within the organization to address open source issues encountered by various teams or departments. The OSPO operates as a center of excellence.
为了从开源中获得最大利益并降低风险，组织必须在文化和实践层面上投资于对开源运营的适当管理。这通常是通过OSPO来实现的，因为它促进了组织内部的跨职能协作，以解决各个团队或部门遇到的开源问题。OSPO是一个卓越的中心。
### If You Deliver Public Services
###如果你提供公共服务
#### How the OSPO Helps
####OSPO如何提供帮助
We see that more public sector organizations are realising the value of an Open Source Program Office to achieve their digital policy goals to better serve their citizens, and to transform their organizations toward achieving these goals.
我们看到，越来越多的公共部门组织正在意识到开源项目办公室的价值，以实现其数字政策目标，更好地为公民服务，并使其组织朝着实现这些目标的方向转型。
Public sector organizations face unique challenges when it comes to managing their open source operations, including the need to comply with strict laws and regulations, and the requirement to provide transparent and accountable operations. An OSPO can help governments and public sector organizations to overcome these challenges.
公共部门组织在管理其开源运营时面临着独特的挑战，包括需要遵守严格的法律法规，以及提供透明和负责任的运营的要求。OSPO可以帮助政府和公共部门组织克服这些挑战。
- **Improving Compliance:** An OSPO helps to ensure that their open source operations are compliant with relevant laws and regulations, including data privacy laws, procurement regulations, and transparency requirements. This helps organizations to avoid costly legal and regulatory challenges and to maintain their reputation as responsible public sector organizations.
-**提高合规性：**OSPO有助于确保其开源运营符合相关法律法规，包括数据隐私法、采购规定和透明度要求。这有助于组织避免代价高昂的法律和监管挑战，并保持其作为负责任的公共部门组织的声誉。
- **Increasing Collaboration:** An OSPO helps to foster collaboration between different departments and with external stakeholders, including other public sector organizations, open source communities, and civil society organizations. This increased collaboration helps organizations to access a wider pool of talent and resources, and to develop better open source solutions.
-**加强合作：**OSPO有助于促进不同部门之间以及与外部利益相关者之间的合作，包括其他公共部门组织、开源社区和民间社会组织。这种增强的协作有助于组织获得更广泛的人才和资源，并开发更好的开源解决方案。
- **Improving Resource Allocation:** An OSPO helps to allocate resources more effectively, ensuring that open source operations are well-supported and that key initiatives are given the resources they need to succeed. This helps organizations to maximize the benefits of open source technology and drive innovation and growth.
-**改善资源分配：**OSPO有助于更有效地分配资源，确保开源运营得到很好的支持，并为关键举措提供成功所需的资源。这有助于组织最大限度地发挥开源技术的优势，推动创新和增长。
- **Improving Service Delivery:** An OSPO helps to improve the delivery of public services, by enabling them to adopt innovative and cost-effective technologies, and to collaborate with external stakeholders to develop better solutions. This helps organizations to provide better services to citizens and to meet the changing needs of their communities.
-**改善服务交付：**OSPO有助于改善公共服务的交付，使他们能够采用创新且具有成本效益的技术，并与外部利益相关者合作开发更好的解决方案。这有助于组织为公民提供更好的服务，并满足其社区不断变化的需求。
The European Commission's Open Source Program Office (OSPO) has launched a new portal that serves as a wiki or knowledge archive, providing up-to-date information on advancements in OSPO-related topics for public administrators. This portal offers a variety of resources, including useful studies, presentations, use cases, guides, and more, to readers interested in learning more about OSPO-related topics. See the Resources section at the end of the chapter for a URL.
欧盟委员会开源项目办公室（OSPO）推出了一个新的门户网站，作为维基或知识档案，为公共管理人员提供有关OSPO相关主题进展的最新信息。该门户网站为有兴趣了解更多OSPO相关主题的读者提供了各种资源，包括有用的研究、演示、用例、指南等。有关URL，请参阅本章末尾的参考资料部分。
### As a Cultural Influence
###作为一种文化影响
In a world governed by software, Open Source Program Offices (OSPOs) serve as powerful cultural catalysts within organizations. Beyond simply managing technical integration of open source solutions, OSPOs fundamentally transform organizational culture by fostering open collaboration, transparency, and innovation.
在一个由软件管理的世界里，开源项目办公室（OSPO）在组织内部起着强大的文化催化剂的作用。除了简单地管理开源解决方案的技术集成外，OSPO还通过促进开放协作、透明度和创新，从根本上改变了组织文化。
As organizations increasingly rely on open source for mission-critical problems — whether social, economic, or technological — the OSPO's cultural influence becomes essential in reshaping mindsets and workflows. This cultural shift enables organizations to move beyond viewing open source as merely a resource to extract value from, toward becoming active, contributing members of the broader open source ecosystem. By embedding open source values and practices throughout an organization, OSPOs cultivate internal champions, establish collaborative norms, and nurture a culture where knowledge sharing thrives.
随着组织越来越依赖开源来解决关键任务问题，无论是社会、经济还是技术问题，OSPO的文化影响力在重塑思维方式和工作流程方面变得至关重要。这种文化转变使组织能够超越将开源仅仅视为从中提取价值的资源，成为更广泛的开源生态系统中积极、有贡献的成员。通过在整个组织中嵌入开源价值观和实践，OSPO培养了内部拥护者，建立了协作规范，并培育了一种知识共享蓬勃发展的文化。
This cultural transformation not only supports risk management and innovation but ensures the sustainability of the open source communities they depend on. Without an OSPO's ongoing cultural influence, organizations risk losing open source expertise, increasing security and legal vulnerabilities, reducing community engagement, and damaging their reputation.
这种文化转型不仅支持风险管理和创新，而且确保了他们所依赖的开源社区的可持续性。如果没有OSPO持续的文化影响力，组织就有可能失去开源专业知识，增加安全和法律漏洞，减少社区参与，并损害其声誉。
Open Source is a silent critical need, and an OSPO's cultural impact is vital to evolve organizational culture and knowledge, helping to build more secure and sustainable OSS.
开源是一种无声的关键需求，OSPO的文化影响对于发展组织文化和知识至关重要，有助于建立更安全和可持续的开源软件。
#### How the OSPO Helps
####OSPO如何提供帮助
- **Acts as a Counselor:** Sometimes a strategic approach just means stepping back and taking the time to think through some of the hard questions about what type of engagement model is right for any particular project or how involved the organization should be in each project. There is also the question of when it makes sense to contribute to an existing project versus creating a new project. An OSPO that is having these strategy-level conversations will be able to provide guidelines to workers at the different teams so that workers don't have to consider the business implications of different open source engagement models every time they try to solve a problem.
-**担任顾问：**有时，战略方法只是意味着退后一步，花时间思考一些难题，比如什么类型的参与模式适合任何特定项目，或者组织应该如何参与每个项目。还有一个问题是，什么时候为现有项目做出贡献与创建新项目是有意义的。正在进行这些战略层面对话的OSPO将能够为不同团队的员工提供指导方针，这样员工在每次尝试解决问题时就不必考虑不同开源参与模式的业务影响。
- **Acts as a Facilitator:** The OSPO also plays a sort of translation role between the organization’s teams and decision makers' interests regarding open source and the needs from the open source community. They also help organizations navigate the cultural, process, and tool changes required to engage with the open source community effectively and in a healthy way.
-**充当协调人：**OSPO还在组织团队和决策者对开源的兴趣以及开源社区的需求之间发挥着某种翻译作用。它们还帮助组织应对有效和健康地与开源社区互动所需的文化、流程和工具变化。
- **Acts as an Advocate:** OSPOs can promote the use of open source and its best practices across different organizational units. This can help organizations realize the benefits of open source as well as engage people to contribute to open source projects or start new ones.
-**充当倡导者：**OSPO可以在不同的组织单位中推广开源及其最佳实践的使用。这可以帮助组织实现开源的好处，并让人们为开源项目做出贡献或开始新的项目。
- **Acts as an Environmentalist:** OSPOs can help organizations support and sustain open source projects in the long term by addressing issues such as security, maintenance, and project health. This can help ensure that open source projects remain healthy in the long term and continue to benefit the wider community.
-**作为一名环保主义者：**OSPO可以通过解决安全、维护和项目健康等问题，帮助组织长期支持和维持开源项目。这有助于确保开源项目长期保持健康，并继续造福于更广泛的社区。
- **Acts as a Gatekeeper:** OSPOs can help enforce open source policies and strengthen open source governance. This can help organizations to ensure compliance and mitigate open source security risks.
-**充当看门人：**OSPO可以帮助执行开源政策并加强开源治理。这可以帮助组织确保合规性并降低开源安全风险。
![ospo-support](/images/ospo-support.png)

### As an Intermediate Step to a Decentralized Open Source Management Model
###作为去中心化开源管理模式的中间步骤
OSPOs help manage open source as an ongoing activity and work to integrate it well into all an organization's units. Some organizations are going a step further to take ownership of the full management of open source within their regular structures and functions. There is an open question related to whether the OSPO would become an intermediate step to achieve this.
OSPO帮助将开源作为一项持续的活动进行管理，并努力将其很好地整合到组织的所有部门中。一些组织正在更进一步，在其常规结构和职能范围内拥有开源的全面管理权。一个悬而未决的问题是，OSPO是否会成为实现这一目标的中间步骤。
The answer depends on how you view the OSPO. Beyond the multiple different structures an OSPO can have, it's fundamentally about its people. An OSPO is a group of open source subject matter experts providing support, knowledge, and management related to all open source activities. These people must be not only retained but also reinforced and effectively financed for the future, as more open source integration is inevitable.
答案取决于你如何看待OSPO。除了OSPO可以拥有的多种不同结构外，它从根本上讲是关于它的人的。OSPO是一组开源主题专家，提供与所有开源活动相关的支持、知识和管理。这些人不仅必须保留，而且必须得到加强，并为未来提供有效的资金，因为更多的开源集成是不可避免的。
In an ideal scenario, open source knowledge, technical expertise, and culture should be integrated as any other employee skill. However, the reality is that this is a long way from happening. Currently, it's challenging to find open source experts who can effectively bridge the gap between open source communities and specific work units (for example: security, legal and business), let alone enough people to place in every part of the business.
在理想情况下，开源知识、技术专长和文化应该像其他员工技能一样整合在一起。然而，现实是，这还有很长的路要走。目前，很难找到能够有效弥合开源社区和特定工作单位（例如：安全、法律和业务）之间差距的开源专家，更不用说在业务的每个部分都有足够的人了。
However, what might change in the coming years is the centralized view of the OSPO. This traditional perception may diminish, leading to more decentralized structures across teams and business units.
然而，未来几年可能会发生的变化是OSPO的集中观点。这种传统观念可能会减弱，导致团队和业务部门之间的结构更加分散。
![ospowork](/images/ospowork.png)

_[Source: OSPOs, key lever for open source sustainability][1](https://speakerdeck.com/anajsana/ospos-a-key-lever-for-open-source-sustainability)_
_[来源：OSPO，开源可持续性的关键杠杆][1](https://speakerdeck.com/anajsana/ospos-a-key-lever-for-open-source-sustainability)_
## Applying This to Your Organization
##将此应用于您的组织
### Assess the Value of Open Source Use
###评估开源使用的价值
Organizations may underestimate how much they already depend on the usage of open source. Several studies analyze the usage of OSS in the industry. For example, the *Synopsys Open Source Security and Risk Analysis Report 2024* [^2] finds that the average software project consists of 77% OSS. Additionally, a *Harvard Business School study* [^3] estimates that the supply-side value of widely-used OSS is $4.15 billion, while the demand-side value is much larger at $8.8 trillion. Moreover, a study by OpenForum Europe [^4] estimates that OSS contributes between €65 to €95 billion to the European Union’s GDP and promises significant growth opportunities for the region’s digital economy.
组织可能低估了他们已经对开源的依赖程度。几项研究分析了OSS在行业中的使用情况。例如，*Synopsys 2024年开源安全和风险分析报告*[2]发现，平均软件项目由77%的OSS组成。此外，哈佛商学院的一项研究估计，广泛使用的开放源码软件的供应方价值为41.5亿美元，而需求方价值要大得多，为8.8万亿美元。此外，欧洲开放论坛的一项研究[4]估计，开放源码软件为欧盟的国内生产总值贡献了650亿至950亿欧元，并为该地区的数字经济带来了巨大的增长机会。
Assess this value for your own organization by taking steps such as:
通过采取以下步骤来评估您自己组织的这一价值：
- Collecting information about what OSS is used by your development and operations teams.
- 收集有关您的开发和运营团队使用什么OSS的信息。
- Getting a clear view of what open source components are in the commercial software you buy or services you use. Ask vendors for what OSS they use, for example by requesting Software Bill of Materials (SBOMs).
- 清楚地了解您购买的商业软件或使用的服务中的开源组件。询问供应商他们使用什么开放源码软件，例如通过请求软件物料清单（SBOM）。
- Assessing the cost savings of current open source use by evaluating what it would cost if you had to replace it with commercial alternatives.
- 通过评估如果必须用商业替代品替换它，它的成本会是多少，来评估当前开源使用的成本节约。
- Evaluating how using existing open source components can increase the speed of innovation or engineering agility.
- 评估如何使用现有的开源组件来提高创新速度或工程敏捷性。

### Consider what Value Your OSPO Might Bring in the Future
###考虑一下你的OSPO在未来可能带来什么价值
The value of an OSPO to your organization may increase over time as strategy and goals of your organization change. Your OSPO should regularly review its value to the organization, and plan to increase its maturity level if needed. More information about OSPO maturity is available in Chapter 3 where the topic of Maturity Models is introduced.
随着组织战略和目标的改变，OSPO对组织的价值可能会随着时间的推移而增加。您的OSPO应定期审查其对组织的价值，并在必要时计划提高其成熟度。关于OSPO成熟度的更多信息，请参阅第3章，其中介绍了成熟度模型的主题。
### Communicate With Stakeholders
###与利益相关者沟通
When communicating the value of your OSPO to your organization, the best route forward is to present the top 2-3 areas of value that are most clearly aligned to organizational strategy. There may be many other areas where the OSPO adds value but research shows that a long list of benefits can weaken the business case rather than strengthen it (you can search for the "Weak Argument Effect" online for more information).  Work on a clear, compelling short value proposition that will cut through, and use it as an anchor for presenting the OSPO in all situations.
在向组织传达OSPO的价值时，最好的前进方向是展示与组织战略最明确一致的前2-3个价值领域。OSPO可能在许多其他领域增加价值，但研究表明，一长串好处会削弱而不是加强商业案例（你可以在网上搜索“弱论证效应”以获取更多信息）。制定一个清晰、引人注目的短期价值主张，该主张将贯穿始终，并将其作为在所有情况下展示OSPO的锚点。
Don't rely on general "good practice" arguments. Though these may be based in truth, they're not usually very compelling and don't help to build strong buy-in across the organization.
不要依赖一般的“良好实践”论点。尽管这些可能是基于事实，但它们通常不是很有说服力，也无助于在整个组织中建立强大的支持。
Don't rely on the value of your OSPO meeting speculative future needs. It's great to be prepared, but unless there is a clear initiative that's about to start which your OPSO can help with, it's better to focus on the value you can deliver here and now.
不要依赖OSPO的价值来满足投机性的未来需求。做好准备是件好事，但除非有一个明确的计划即将开始，你的OPSO可以提供帮助，否则最好专注于你现在可以提供的价值。
## Examples of the OSPO's value
##OSPO价值示例
To illustrate how your OSPO may deliver value to your organization, some example stories can be a great way to build buy-in. Here are two examples where an OSPO could be vitally important:
为了说明你的外包服务提供商如何为你的组织创造价值，一些例子故事可以成为建立认同的好方法。以下是外包服务提供商可能至关重要的两个例子：
### Managing a Vulnerability in the Software Supply Chain
###管理软件供应链中的漏洞
For example: a social engineering attack targeted the xz/liblzma [^5], an essential open source library. The attack was meticulously planned, gaining trust within the community before executing a malicious attack. This incident was discovered inadvertently by an unrelated project, underscoring the sophistication and stealthiness of such vulnerabilities. The challenge for OSPOs lies in identifying and mitigating these vulnerabilities, which are not always apparent until after they occur. Despite existing procedures and policies, OSPOs recognize the need for mechanisms to proactively measure and respond to such threats.
例如：一次社会工程攻击针对的是xz/liblzma[^5]，这是一个重要的开源库。这次攻击经过精心策划，在执行恶意攻击之前赢得了社区的信任。这一事件是由一个无关的项目无意中发现的，突显了此类漏洞的复杂性和隐蔽性。OSPO面临的挑战在于识别和缓解这些漏洞，这些漏洞在发生之前并不总是很明显。尽管有现有的程序和政策，但OSPO认识到需要建立机制来主动衡量和应对此类威胁。
#### How the OSPO Helps

1. **SBOMs Compliance Ready:** Ensure that all software components are documented through automatically generated Software Bill of Materials (SBOMs). This documentation helps quickly to identify potentially compromised components once a vulnerability is disclosed.

2. **Automated Security Checks:** Implement automated security checks, such as the OpenSSF Scorecard [^6], to continuously evaluate the security posture of projects. This proactive measure can highlight vulnerabilities or anomalies that merit further investigation.

3.  **Having a Computer Emergency Response Team (CERT)** within the organization and having the OSPO collaborate closely with them. This specialized team should be equipped with the tools and authority to respond swiftly to security incidents. Pre-existing relationships within the team facilitate rapid internal communication about the severity of incidents.

4. **Scorecard Management:** Keep security and vulnerability scorecards up to date. These scorecards should reflect the latest security checks and assessments, helping in quick decision-making during a crisis.

5. **Automated Feedback Loops:** Develop well-automated feedback loops for bug reporting and fixing. Knowing who is responsible for addressing a particular bug and ensuring that this process is as automated as possible can significantly reduce response times.

### Managing a Licence Change in the Software Supply Chain

 OSPOs face the challenge of navigating license changes and assessing software trustworthiness. When projects like Redis change their terms [^7] it can have significant implications for use, distribution, and contribution. OSPOs need to communicate these changes clearly and understand the roles and responsibilities dictated by new license terms. Furthermore, OSPOs are tasked with evaluating the trustworthiness of software, which can vary based on whether a project is maintained by a single vendor or hosted under a foundation. For instance, The AlmaLinux OS Foundation [^8] presents a case where donating a project to a foundation mitigated risks associated with single-vendor governance, thereby enhancing trust in the project.

#### How the OSPO Helps

1. **Educational Initiatives on License Implications:** Develop educational materials and sessions for developers and users within the organization to understand the nuances of different licenses. This understanding will help them make informed decisions when using or contributing to open source projects.
2. **Explicit License Terms:** Work with legal teams to ensure that license terms are as explicit and unambiguous as possible. Clear terms help in avoiding misunderstandings and potential legal conflicts.
3. **Software Trust Rating System:** Implement a system to evaluate and rate the trustworthiness of software, considering factors like governance structure, maintenance practices, and community engagement. Projects hosted under reputable foundations could be rated higher for trustworthiness due to the oversight and governance provided.
4. **Encourage Foundation Hosted Projects:** Advocate for donating projects to foundations to mitigate risks associated with single-vendor control. Highlight successful cases like AlmaLinux to illustrate the benefits of this approach, such as increased trust and community support.
5. **Stakeholder Engagement in License Decisions:** Engage a broad range of stakeholders, including developers, legal advisors, and end users, in discussions about license changes or the adoption of new projects. Their insights can help in making balanced decisions that align with the organization's values and risk tolerance


## Possible Problems and How to Overcome Them

In this section, you will find a series of real-world scenarios that are encountered in open source management across organizations. For each scenario, you can find recommendations from real-world experiences from open source professionals.

### Problem

There is a lack of understanding about open source practices across the organization.

### Recommendation

It can be hard to demonstrate the value of the OSPO if there is a poor understanding of open source in the organization. Focusing on speaking about your key areas of value and using the power of stories will help you to build understanding quickly in the organization. Sharing real-world stories about how your organization is using open source, and sharing cautionary tales about times an OSPO saved an organization from a risk can help to educate people through easily repeated narratives.

As time goes by, you can start to promote better organizational-wide understanding of open source practices by offering educational workshops, creating accessible resources, and establishing open source champions in different departments to foster a culture of open source literacy.

-----

### Problem

The OSPO's value is seen as a sales profit or marketing tool.

### Recommendation

Because the OSPO has a role in supporting relationships with open source communities and partners, it can be natural for sales and marketing to see some value to them in this engagement.

As an OSPO you can only fulfill your responsibilities by building trust with third parties over time. Set boundaries with sales and marketing and say "no" to things that might reduce your reputation in the ecosystem. Work on building internal understanding of the OSPO as an integral part of the organization's digital, software, or IT strategy, and highlight work that fosters open source best practices, contributes to technological innovation, and supports the overall organization's goals.

-----

### Problem

The OSPO's value is seen as secondary or discretionary, and not as critical for the organization’s core functions.

### Recommendation

The cause of this problem is either that the OSPO isn't aligned with the organization's needs, or that the OSPO isn't communicating its value well. Review the OSPO's value, and plan your communications to highlight how the OSPO enhances key business processes, drives innovation, and directly supports strategic objectives, thereby integrating it as an essential component of the organization's operational framework.

-----

### Problem

The OSPO struggles with gaining executive support and buy-in.

### Recommendation

Executives require a particular type of communication. They need to have a clear picture of the role and value that each part of the orgnization brings. If the message is too detailed or vague, or if the subject is too specialist they can struggle to "get it". As the OSPO, you need to communicate the strategic value of open source and of the work the OSPO does to manage it. Showcasing visible benefits through case studies, success stories, or numerical reports can help to cut through with a clear and simple presentation that demonstrates OSPO initiatives are delivering with key organizational priorities.


## Resources and Footnotes

### Resources

- Log4Shell real vulnerability example: https://en.wikipedia.org/wiki/Log4Shell
- Open source and the software supply chain - John Mark Walker: https://opensource.com/article/16/12/open-source-software-supply-chain
- Strategy: End Game for FINOS Maturity Model - Victor Lu: https://docs.google.com/presentation/d/1jJtR6-fvU-dCrGq_gTm4P1Awv90oCu4RClj1919970A/edit#slide=id.g1ed9ae7029f_0_29
- Securing the Software Supply Chain: The Role of OSPOs - Jessica Marz: https://www.intel.com/content/www/us/en/developer/articles/community/securing-software-supply-chain-the-role-of-ospo.html
- Simple Frequently Asked Questions OSPO Guide - OSPO SWG Japan: https://qiita.com/owada-k/items/017d1b98d0e437766bd0
- The Business Value of the OSPO Report - Linux Foundation: https://www.linuxfoundation.org/research/business-value-of-ospo
- EC Open Source Programme Office - European Commission Joinup: https://joinup.ec.europa.eu/collection/ec-ospo
- Public Services Should Sustain Critical Open Source Software - FOSSEPS: https://joinup.ec.europa.eu/collection/ec-ospo
- How Governments Want to Use OSPOs to Transform Themselves - Sivan Pätsch: https://joinup.ec.europa.eu/collection/open-source-observatory-osor/news/growing-case-ospos-government
- Open Source Security and Risk Analysis Report 2022 - Synopsys: https://www.synopsys.com/software-integrity/resources/analyst-reports/open-source-security-risk-analysis.html
- Open Technology - Scheerder, Jeroen & Koymans: https://www.researchgate.net/publication/254920512_Open_Technology#pf7
- The Pros and Cons of Open Source Software - Khalil Khalaf: https://medium.com/@kylekhalaf/the-pros-and-cons-of-open-source-software-d498304f2a95

### Footnotes

[^1]: Business value of the OSPO report: https://www.linuxfoundation.org/research/business-value-of-ospo

[^2]: Synopsys Open Source Security and Risk Analysis Report 2024: https://www.synopsys.com/content/dam/synopsys/sig-assets/reports/rep-ossra-2024.pdf

[^3]: Harvard Business School study: https://www.hbs.edu/ris/Publication%20Files/24-038_51f8444f-502c-4139-8bf2-56eb4b65c58a.pdf

[^4]: Study by OpenForum Europe: https://openforumeurope.org/publications/study-about-the-impact-of-open-source-software-and-hardware-on-technological-independence-competitiveness-and-innovation-in-the-eu-economy/

[^5]: Social engineering attack targeted the xz/liblzma: https://research.swtch.com/xz-timeline

[^6]: OpenSSF Scorecard: https://scorecard.dev/

[^7]: Redis changes their terms: https://www.theregister.com/2024/03/22/redis_changes_license/

[^8]: AlmaLinux OS Foundation: https://thenewstack.io/jack-aboutboul-how-almalinux-came-to-be-and-why-it-was-needed/
