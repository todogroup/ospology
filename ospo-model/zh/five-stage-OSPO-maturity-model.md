# 组织 OSPO 模型分类标准

我们希望这是一份动态文件，旨在建立 OSPO 模型的分类标准并确定有助于不同组织学习和实施的关键组件（模式）。

社区可以对`五阶段 OSPO 成熟度模型`进行颠覆式贡献，以更好地满足特定垂直行业和/或地区的需求。

> 如果您想做出贡献，请提交 PR。


## OSPO 模型 1 —— 五阶段 OSPO 成熟度模型

> 完整研究可以查阅 [OSPO 的演进](https://linuxfoundation.org/tools/the-evolution-of-the-open-source-program-office-ospo/) 
> 
> 欲了解更多 OSPO 特点、组织架构和角色相关信息，请查看[深入了解 OSPO](https://www.linuxfoundation.org/tools/a-deep-dive-into-open-source-program-offices/)

随着 OSPO 的激增和普及，这些专项也日趋成熟。通过把 OSPO 领导者和专家的对话与 OSPO 调研结果相结合，我们建立了一个 OSPO 成熟度模型，以描述 OSPO 的典型演进过程。请注意，*一刀切并不适合所有情况*。事实证明，该模型在那些最初没有*传统上*在其*日常运营*中实施开源的环境中效果更好。此外，组织的规模和类型也会影响 OSPO 的成熟程度。在规模较大的组织中，多个业务部门可能会制定不同的开源策略，每个部门都有不同的技术文化；而纯数字化的技术公司更有可能在早期消费 OSS 并为其做出贡献，也更有可能接触到开源技术和理念。


![LFResearch_OSPO_报告_图2](https://user-images.githubusercontent.com/43671777/167606513-18cb999e-8d01-4807-a23e-2ad5f6ec85f7.jpg)

**揭秘 OSPO 模型**

此外，每个阶段都是累积性的。这意味着，在跨级推进时，OSPO 也要承担上一级的任务和责任。

例如，一旦 OSPO 涵盖了与开源合规和安全（级别 1）相关的所有必需任务，该 OSPO 可能已准备好迁移到级别 2。
现在，该 OSPO 应该负责第一级的开源法律责任以及与传播 OSS 文化和生态系统参与（第二级）相关的法律责任。

## 0️⃣ 阶段 0： 临时采纳开源

如今，几乎所有的组织都在使用 OSS。他们采纳和开始使用 OSS 的方式各不相同。他们可能将 OSS 作为产品或工具中的模块或类库，或者作为供应商产品栈的关键部分，或者支持供应商提供的服务。开发人员可能将 OSS 用于快速原型开发或微服务和小型应用程序。开发人员还经常采用 OSS 开发工具，如集成开发环境（IDE），或构建在 GitHub 和 GitLab 等开源平台之上的工具。现代云原生应用几乎默认使用开源系统进行容器编排、可观测性、数据存储、消息通信等。对于前端应用程序，开发人员非常依赖开源库和框架。RedHat 报告称，“90% 的 IT 领导者都在使用企业级开源”。Synopsys 等软件成分分析供应商表示，超过 75% 的代码库包含开源组件。

换句话说，几乎每个组织都在使用开源。然而，最早的采用形式是临时性的，由开发人员使用现成的工具和技术解决问题。这种“临时采用”通常意味着很少考虑默认情况之外的许可证合规，也很少考虑使用开源和分发使用开源组件构建的产品的长期影响。在大多数情况下，少数工程师会积极寻求开源，而工程团队的其他人员可能会偶然使用开源，但不会将其活动视为依赖开源。因此，企业既没有一个专注于开源的集中式团队，也没有为企业制定最高级别的开源战略。这些都是至关重要的，因为一旦采用，这些开源组件就会默认成为组织软件供应链的一部分，这就更有必要采取战略措施。


## 1️⃣ 阶段 1： 提供 OSS 合规、清单和开发者教育

一般来说，当一个组织意识到其员工正在使用开源产品和代码，几乎涉及所有工程和开发部门及职能部门时，就会组建一个 OSPO。这种使用通常是内部使用，而不是作为向客户或用户提供的产品或服务的一部分。实际上，任何拥有大量 IT 服务能力和先进的在线系统或应用程序为中心的组织都会使用开源，因为开源在整个技术栈中无处不在，从 Linux 服务器和 MySQL 数据库到 NodeJS 和 Python 等编程语言以及 React 和 Vue.js 等前端框架。

在这一早期阶段，各组织通常为 OSPO 使用许多不同的名称。例如，IBM 公司最初将其计划性开源工作称为 "开源指导委员会"。不过，在所有情况下，处于第一阶段的组织都认识到 OSS 是其业务和技术战略的重要组成部分。他们知道 OSS 项目的安全实践与专有软件公司的不同。例如，OSS 项目的披露规则往往比专有项目的披露规则更严格。因此，他们必须明确自己的法律和安全风险。降低风险的策略包括谨慎许可、开发人员教育和严格盘点。


### 管理法律风险和许可

一个组织的法律团队或技术领导往往会启动 OSPO 的第一阶段的推进工作，以确保其员工（以及承包商、供应商等）都按照许可条款使用 OSS ，并确保该组织的 OSS 消费不会使其面临法律风险。目前使用中的 OSS 许可证有几十种。在 2020 年的调查中，受访者将合规性列为大型企业 OSPO 的最大收益，而合规在中型企业仍然是第二大收益。公司一开始通常会有很多困惑。

尽管 OSS 用户一直在考虑法律合规性，但一些 OSS 贡献者还是设计了新的许可证，以阻止大型云提供商基于开源项目创建专有服务。其中最著名的是 Affero 通用公共许可证 (AGPL)。公司可以使用根据该许可证条款发布的 OSS 向客户提供专有软件即服务（SaaS），但如果 AGPL 条款没有明确区分内部和外部交付，OSS 的创建者可能有理由起诉公司违反许可证规定。许多企业还在业务单元之间建立了内部财务结算系统，进一步模糊了付费服务和内部服务之间的界限。

### 教育开发者

To maintain compliance, organizations in Stage 1 of OSPO maturity create education programs to help their developers decide when to use OSS in creating new products or services. “Many developers who are not educated in open source think that because they are not purchasing software, there is no license involved because they didn’t sign a contract,” said Suzanne Ambiel, director of open source marketing and strategy at VMware. “Open source software may be free—as in priceless—it can also be costly if used in a noncompliant way. [OSS] always comes with a license. One of the most important roles of any OSPO is to make sure developers understand the implications of different license choices.”
为保持合规性，处于 OSPO 成熟度第一阶段的组织应制定教育计划，帮助其开发人员决定何时在创建新产品或服务时使用开放源码软件。"VMware 公司开源营销和战略总监 Suzanne Ambiel 说："许多没有接受过开源教育的开发人员认为，因为他们没有购买软件，所以不涉及许可证，因为他们没有签署合同。"开放源码软件可能是免费的，也可能是无价的，但如果以不合规的方式使用，成本也可能很高。[开放源码软件]总是附带许可证的。任何 OSPO 最重要的职责之一就是确保开发人员了解不同许可证选择的影响。

Through developer education, senior management often acknowledges the value and importance of OSS. In such programs, developers learn:
通过开发人员教育，高级管理层往往会承认开放源码软件的价值和重要性。在这些项目中，开发人员可以学到

* The nuances of different license types
* The formal approval processes for introducing new OSS products 
* The real risks of noncompliant OSS consumption, including the usage of OSS products from projects or code without formal licenses
* The use of contributor license agreements (CLAs) to cover an organization’s developers who contribute to open source
* 不同许可证类型的细微差别
* 引入新的开放源码软件产品的正式审批程序
* 消费不合规开放源码软件的实际风险，包括使用来自项目的开放源码软件产品或没有正式许可证的代码
* 使用贡献者许可协议 (CLA) 来覆盖为开放源码做出贡献的组织开发人员

Sometimes the organization introduces a formal CLA policy at this stage. It may also provide guidance on judging the health of OSS projects as part of its criteria for deciding which OSS to use in the organization’s technology stack or infrastructure. 
有时，组织会在这一阶段引入正式的 CLA 政策。作为决定在组织的技术堆栈或基础设施中使用哪些开放源码软件的标准的一部分，它还可能为判断开放源码软件项目的健康状况提供指导。

### 盘点软件清单

Developers may deploy OSS ad hoc without cataloging their efforts systematically. The legal team and technology leadership tend to push for an inventory of all OSS in use in an organization. Such an inventory itemizes OSS in organization’s code repositories (e.g., GitHub, GitLab) and systems. 
开发人员可能会临时部署开放源码软件，而不对其工作进行系统编目。法律团队和技术领导层倾向于推动编制组织内使用的所有开放源码软件清单。这种清单将组织代码库（如 GitHub、GitLab）和系统中的开放源码软件逐项列出。
Stage 1 organizations set up specific software inventory processes to create an organization-wide software bill of materials (SBOM). With this inventory,the legal team—usually working with the OSPO team—can continuously monitor OSS usage and flag legal, security, or other project risks. With a detailed SBOM, technology leadership such as a chief technology officer (CTO) or chief information officer (CIO) can identify and closely monitor the most business-critical uses and preserve organizational security.
第一阶段的组织建立了特定的软件库存流程，以创建全组织范围的软件物料清单（SBOM）。有了这份清单，法律团队（通常与 OSPO 团队合作）就可以持续监控开放源码软件的使用情况，并提示法律、安全或其他项目风险。有了详细的 SBOM，首席技术官（CTO）或首席信息官（CIO）等技术领导层就可以识别并密切监控最关键的业务用途，维护组织安全。


**本阶段建议参与的 OSS 社区列表**

| 横向技能 | 项目 / 社区 |
| --- | --- |
| 合规 | Open Chain |
| 安全 | OpenSSF |
| | SPDX |

> 你想列出其他开源社区吗？请提交 PR

## 2️⃣ 阶段 2： 布道 OSS 应用和生态参与

After organizations recognize the value of OSS and the need for compliance, education, and an SBOM, they begin to realize the economic benefits of OSS usage and seek to expand it. OSPOs in Stage 2 create such internal mechanisms as ambassadors who promote usage of approved OSS products, educational programs on good OSS hygiene, and technical training or tuition reimbursement for skill building and certification in OSS. With these initiatives, an organization can grow its use of OSS and amplify its message that OSS is not only important but desirable and preferable to proprietary software products. 

Employee education includes laying out best practices in interacting with OSS projects such as how to request features, file bug reports, and contribute basic code. During this stage, the organization strengthens its collaborative muscle and experiences the social life of an OSS project and community. At this point, the OSPO communicates to employees and managers the importance of contributing to and not merely consuming OSS. This outreach includes advocating for and driving event sponsorships, booking project leads and maintainers as speakers or panelists in public coding forums, and securing organizational resources (e.g., talent, funding) to mission-critical OSS projects. 

For organizations, active and visible participation yields multiple benefits: better visibility, better reputation, more attractive employer. To this end, many non-tech organizations purchase booths. at prominent OSS events to interact more with those communities and recruit developers who enjoy working in OSS ecosystems. Technology companies active in open source may extend education programs to customers who want to interact with OSS communities and vendors.

As they advance in Stage 2, organizations begin incentivizing their developers to work on OSS projects critical to their operations, to the degree that developers become highly active contributors or primary maintainers. To technology organizations, employing a contributor to a prominent OSS project is a valuable investment: most of their contributors to, say, the Linux kernel—the core component of the Linux operating system and the critical interface between computer hardware and software—are full-time employees (FTEs) whose job is to write code for Linux. 

Outside the technology sector, fewer organizations can assign FTEs to open source work, but they are doing it. For example, both Comcast and Bloomberg have employees working full-time on OSS projects. In this stage of the life cycle, OSPOs begin exploring how to streamline processes for developers to consume OSS. Such developer efficiency may include simplifying CLAs, adding OSS with acceptable license types to ticketing systems for fast approval, promoting reuse of OSS architecture and software in place (a variation on inner-sourcing), and standardizing library selection and open source development tools, thereby blending OSPO and platform operations duties.

Usually in Stage 2 of the OSPO maturity cycle (or sometimes in Stage 1, if the company is a software or core technology company), OSPOs begin to streamline and optimize open outbound source contributions for their developers. The process of requesting and getting approval for outbound participation is usually ad hoc and painful in the early days

**本阶段建议参与的 OSS 社区列表**

| Horizontal Skills | Project / Community |
| --- | --- |
| Community Health and metrics | CHAOSS |
| Internal OS Culture | InnerSource Commons |

> 你想列出其他开源社区吗？请提交 PR

### 3️⃣ 阶段 3： 发起开源项目和发展社区

At Stage 3, organizations initiate and then host or act as primary sponsors of OSS projects. They will dedicate one or more FTEs to a project, and they accept responsibility for nurturing a project community and ensuring its health. They don’t confuse this level of organizational commitment with individual employees who decide to open-source their projects. In Stage 3, organizational leaders support incubating and launching open source projects into the public sphere because they understand how these projects benefit their organization. Such projects tend to offer better performance and economics on crucial capabilities that may be noncore to the organization’s value proposition but critical to its technology infrastructure. 

In addition, organizations that create and launch open source projects establish broad credibility in the open source community; the possibility of working on open source technology is attractive to many developers.  Most of the OSPOs we spoke with cited recruitment of new engineering talent and retention of existing talent as a key motivation of the open source effort.

Supporting a project with FTEs and funding is true skin in the open source game. Organizations that cross this threshold and successfully launch multiple open source projects develop internal resources and processes that can incubate and ensure the success of these projects post launch. OSPOs are more than just gatekeepers and mentors for project formation and launch; they educate project creators on the requirements for cultivating a healthy open source ecosystem, and they coach project leads to prepare them for a more public leadership role required of an OSS project. 

As an OSS organization matures, its OSPO develops internal processes, playbooks, checklists, tooling, and other mechanisms to vet, organize, and operate open source projects and to prepare and coach their leaders. Some OSPOs prefer to launch projects with the assistance of the major open source foundations or collaboratives such as the TODO Group to enhance capabilities or provide infrastructure, tactical assistance, and other resources. This preference is less resource intensive but cedes control of a project to a broader community.

**本阶段建议参与的 OSS 社区列表**

| Horizontal Skills | Project / Community |
| --- | --- |
| Community Health and metrics | CHAOSS |
| Project-specific and and Umbrella Foundations | Linux Foundation |
| | CNCF |
| | Eclipse Foundation |
| | Apache Foundation |


> 你想列出其他开源社区吗？请提交 PR

### 4️⃣ 阶段 4： 成为战略决策合作伙伴

At this maturity stage, the OSPO becomes a strategic partner for technology decisions, helping to guide choices and shape long-term commitments to projects. At Stage 4, the CTO and other technology leaders consult the OSPO and its leadership on which open source technologies to rely on and which decision criteria to use in judging open source projects. Because major open source technology choices tend to generate significant secondary and tertiary costs and affect upstream and downstream technologies as well as hiring plans, the choice of open source projects becomes a major business decision. 

In broad terms, OSPOs provide three types of strategic guidance in Stage 4. First, the OSPO advises the CTO and technology leadership on which open source technologies to adopt or remove from the organization’s technology stack. Given the many OSS options today—with most major categories of software featuring dozens of choices as shown in Figure 2—the OSPO can provide insights into OSS trends such as popularity of different languages, designs of APIs, or capabilities of different NoSQL databases. In this role, the OSPO becomes an internal technology consultant to the CTO and the in-house expert on OSS. 

In a second type of strategic guidance, OSPOs take the lead on benchmarking what constitutes an acceptable OSS project. The OSPO often evaluates the behavior and performance of the project, especially changes in license type that limit usage, or abrupt shifts in the project roadmap, to determine whether a project manager has the best interests of the community in mind. Most OSPOs rely on back-of-the-envelope 
metrics to evaluate project behavior such as:

* Which type of license does it have?
* What is its code of conduct, and what are the consequences for breaking it?
* What is its governance structure, and does this structure ensure independence?
* How long does it take to respond to pull requests or bug filings?
* How frequently does the project ship new versions?
* Does one party (company or organization) or a whole community control the project?
* How many contributors does the project have? How has that number changed over time?

A third type of guidance is helping organizations understand and navigate project politics, such as maintaining a neutral stance when multiple influential actors are attempting to steer a project, or illuminating the latent political considerations of community members. At a higher plane, OSPOs can help companies maintain a neutral posture on techno-nationalism and bridge political differences by cultivating personal and working relationships that transcend national boundaries and political realms. Increasingly, this value extends to the work of foundations and nonprofits, as those realms become important neutral spaces in open source.

**本阶段建议参与的 OSS 社区列表**

| 横向技能 | 项目 / 社区 |
| --- | --- |
| 社区健康和指标 | CHAOSS |
| 特定项目与伞式基金会 | Linux 基金会 |
| | CNCF |
| | Eclipse 基金会 |
| | Apache 基金会 |


> 你想列出其他开源社区吗？请提交 PR
