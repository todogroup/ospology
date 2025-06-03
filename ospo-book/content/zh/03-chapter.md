---
title: "第3章：建立 OSPO"
status: Completed
weight: 50
---

- [概述](#introduction)
- [从战略出发](#starting-with-strategy)
- [设计您的开源项目办公室（OSPO）](#designing-your-ospo)
- [使用成熟度模型评估开源项目办公室（OSPO）](#using-maturity-models-for-ospos)
- [在组织的应用](#applying-this-to-your-organization)
- [潜在问题及解决方案](#possible-problems-and-how-to-overcome-them)
- [参考资料和脚注](#resources-and-footnotes)

## 概述

开源项目办公室（OSPO）可以非常多样化，因此花时间设计一个能够实现您组织目标的OSPO非常重要。

本章首先将帮助您确定战略，以便为规划组织应开展的工作及OSPO的结构提供基础。

然后，本章将探讨如何设计和构建一个稳定且强大的OSPO，使其能够涵盖组织所需的与开源相关的任务和职责。

最后，本章将介绍成熟度模型，作为一种理解当前和未来需求变化时，什么适合您的OSPO的方法。

## 从战略出发

### 如何设计战略

> 对于开源项目办公室（OSPO）的个人而言，有效地向C级高管传达开源战略需要深刻理解行业格局，并与首席执行官（CEO）和首席财务官（CFO）的关键考量保持一致。这种一致性要求清晰理解公司的总体战略，并识别开源领域中能够推动组织实现其战略目标的技术。
>
> Victor Lu 和 Rob Moffat 的演讲《战略——FINOS 成熟度模型的最终目标》 [^1]

开源项目办公室（OSPO）通过创建和维护涵盖以下方面的框架来实现这一目标：战略、治理、合规性和社区参与。OSPO的战略专注于将其组织在项目、产品、服务和内部基础设施中的开源使用、贡献和合规活动与其整体组织目标保持一致。

战略在具体主题及其对您的组织和内部人员的影响上达成高层次的共识。

创建您的战略时需要考虑的事项：

1. **创建战略文档：** 一个好的做法是将此战略记录在开源战略文档中[^2]。该指南会逐步引导您完成整个过程。
2. **了解您组织的目标：** 如前一章所述，您需要了解组织的目标及其当前对开源的参与情况。
3. **考虑背景：** 在制定OSPO的战略和设计时，在考虑人员、技术和预算之前，您有几种不同的方式来决定其结构和在组织架构图中的位置。TODO小组制作了一份优秀的指南，名为《深入探讨OSPO》[^3]，其中解释了有关OSPO结构和运营的所有必要信息。
4. **审查示例OSPO的结构：** 要概览OSPO的潜在活动，您可以查看OSPO思维导图[^4]。这概述了OSPO生态系统中的主要职责、角色、行为和团队规模。

## 设计您的开源项目办公室（OSPO）

### 确定您的OSPO应管理的内容

要做得好，OSPO需要了解组织是如何运作的。了解公司的目标有助于OSPO在使用开源时做出明智的选择。例如，在商业环境中，OSPO可能会查看以下领域，以确定开源如何融入其中：

![组织架构](/images/organization-architecture.png)

由于每个组织在其价值观、业务驱动因素和文化方面都是独特的，因此提供具体的内容具有挑战性。然而，回答以下问题可以帮助有效地构建文档：

- 哪些开源技术对您组织的目标和产品路线图当前和未来是重要的？
- 哪些开源项目直接或间接地发展或影响这些技术和您组织的目标？
- 哪些具体的最佳实践可以最好地培育一个可持续的开源生态系统？
- 组织的哪些流程有改进的空间？
- 开源如何支持这些改进？
- 如何让员工成为开源的倡导者？
- 如何有效地向管理层传达信息以获得他们的理解？

花时间了解OSPO可以在哪些方面增加价值，将有助于您识别出利益相关者是谁。

### 确定您的OSPO的利益相关者

在企业的某些常见部分，OSPO可能会找到其利益相关者。利益相关者是指所有会受到您工作影响的人。OSPO 花瓣图（OSPO Flower Diagram）有助于可视化不同的利益相关者群体。每个花瓣代表一个特定的利益相关者群体，并与该群体相关的具体活动相联系。OSPO花图还可以帮助您映射与每个利益相关者群体使用的具体沟通渠道、文档和其他材料。

根据您组织的复杂性和OSPO可用的资源，这些花瓣可以变得更加细化，并包括具有不同名称的额外花瓣。

![ospoflower](/images/ospo-flower.png)
[ospoflower.pdf](/pdfs/ospoflower-seconddraft-1.pdf)

- **个人贡献者**： 这一分区代表OSPO将在组织内部合作的人员，重点是从个人角度出发，关注开源贡献的内在和外在动机。这可能涉及文化或观点的改变以及具体行动，如建立导师计划等活动。
- **管理层**： 在这一分区中，OSPO专注于战略，并找到开源与整体业务/组织战略之间的协同点。管理者面临独特的挑战，利用开源的优势可以帮助他们有效克服这些挑战。
- **法务**： 这一分区代表开源相关的法律方面。它涉及理解和管理与组织内开源项目相关的法律要求和义务，确保合规并减少法律风险。
- **业务**： 这一分区关注OSPO如何确保组织结构中的各个部分紧密结合。它包括在不同的业务/团队单元之间分享最佳实践，促进协作和知识传递。
- **开源生态系统**： 这一分区代表组织外部更广泛的开源社区和项目生态系统。OSPO与这个生态系统互动，其中包括其他组织、项目和个人，以交流想法、合作并为更大的开源社区做出贡献。
- **开源项目办公室（OSPO）**： 这一分区代表OSPO自身的内部运作。OSPO内的人员合作并协调组织内的所有开源活动。他们总览各项活动，确保顺利运行，并为参与开源的其他利益相关者提供指导和支持。

### 与外部监管机构合作

外部监管机构未包含在“花图”（flower diagram）中，因为这是一个特殊情况。

各类外部监管机构对组织的政策与流程具有影响和塑造作用。其核心职能是确保组织在法律合规性、伦理规范及行业特定准则方面达到要求。常见的外部监管机构包括：

- 政府机构 ：政府机构制定并执行对组织产生影响的法律法规。
- 行业监管机构 ：多数行业设有自身的监管机构或专业协会，负责制定组织需遵循的指南与标准。
- 消费者保护机构 ：消费者保护机构确保组织向消费者提供公平且安全的产品或服务。

若希望开源在组织内部实现成功与可持续发展，不仅需与开源社区协作，亦须与外部监管机构建立合作关系。此类协作有助于在制定影响开源生态系统的政策时，确保对开源原则的准确认知。其核心目标在于通过充分理解开源及其社区的影响，共同作出基于充分认知的决策。因此，建议开源项目办公室（OSPO）考虑制定与监管机构沟通的具体方案，并明确界定其在政策制定过程中的角色定位。

## 使用成熟度模型评估开源项目办公室（OSPO）

### 成熟度模型简介  

组织对开源的参与通常处于从“战术性”到“战略性”的连续区间。成熟度模型可帮助您判断组织内不同部门在此区间中的具体定位，并据此开展关于其是否处于合理阶段的讨论。  

存在多种开源成熟度模型：既有通用型模型，也有针对特定场景的专用模型。例如面向政府、非政府组织（NGO）、企业等不同主体的模型，以及适用于各类组织的版本与子版本分类体系。  

> **注**：成熟度模型常被视为对OSPO或开源参与方式发展的指导性框架。这可能使人误认为提升成熟度层级始终是更优选择，但需注意应根据OSPO整体或各职能模块的实际需求，判断适宜的成熟度层级。并非所有模块均需高度发展——部分模块可能已通过现有成熟度层级实现所需价值，无需进一步升级。若成熟度模型不适用于您的OSPO，可考虑改用能力模型或其他替代方案。

### 成熟度模型示例  

每种成熟度模型略有差异，但均以组织对开源的参与程度为核心评估维度，从战术性、非主动性的参与逐步过渡到战略性、主动性的参与。  

#### 成熟度模型 1 - Dr. Ibrahim H 提出的开源参与采纳模型 [^5]：  

* **否认阶段（Denial）**：未使用或无意识使用开源软件  
* **使用阶段（Consumption / Usage）**：被动使用开源软件（OSS）  
* **参与阶段（Participation）**：与开源社区互动协作  
* **贡献阶段（Contribution）**：对开源项目进行务实性贡献  
* **领导阶段（Leadership）**：通过战略性参与开源以驱动业务价值  

![opensourceinvolvementmodel](/images/opensourceinvolvementmodel.png)

#### 成熟度模型 2 - Carl-Eric 提出的企业开源采纳五阶段模型 [^6]：  

* **偶然阶段（Accidental）**：组织在未察觉的情况下使用开源软件  
* **重复阶段（Repetitive）**：已建立消费与贡献的流程框架，但贡献行为具有偶发性  
* **主导阶段（Directed）**：在关键开源项目中积极主动参与  
* **协作阶段（Collaborate）**：通过开源协作创造业务价值  
* **引领阶段（Prevail）**：使用开源来影响业务和技术的战略领域

![osmm-carl](/images/osmm-carl.png)

#### 成熟度模型 3 - TODO Group 提出的 OSPO 成熟度模型 [^7]：  

* **阶段 0（Stage 0）**：临时采用开源（Adopting Open Source Ad Hoc）  
* **阶段 1（Stage 1）**：提供开源合规性、SBOM清单及开发者教育  
* **阶段 2（Stage 2）**：推广开源使用及生态系统参与  
* **阶段 3（Stage 3）**：主导开源项目并培育壮大社区  
* **阶段 4（Stage 4）**：成为战略决策合作伙伴

![OSPO Maturity Model](/images/ospo-maturity-model.jpg)

## 在组织中的应用  

以下建议基于 **成熟度模型 3 - TODO Group 提出的 OSPO 成熟度模型**，说明如何利用前述理念与建议构建您的开源项目办公室（OSPO）。  

### 使用简化检查清单  

TODO OSPO 检查清单 [^8] 为初创期与成熟期的 OSPO 提供了一套简化的通用里程碑指南，旨在应对前述 OSPO 成熟度模型各阶段的挑战。请注意，OSPO 可根据组织需求删除、新增或修改该清单的部分内容。  

### 应用成熟度模型  

在熟悉开源成熟度模型后，可基于其框架制定战略并规划实施路径。  

由 TODO Group 与 OpenChain 支持的 **OSPO Japan Local Meetup Working Group** 正在开发一份简化的《开源项目办公室常见问题指南》（Frequently Asked Questions, FAQ）。该指南针对 OSPO 成熟度模型的 0 至 4 阶段，分类解答各阶段核心问题，并明确 OSPO 在不同层级中的角色定位。  

以下是一些来自他们工作的亮点，以激发您的灵感：

![ospo-role](/images/ospo-role.png)
![benefits-of-oss](/images/benefits-of-oss.png)



在规划 OSPO 时，与以下人员开展一对一沟通极具价值：  
- 直接在日常工作中使用开源软件的部门管理者、高管及员工/合同制人员  
- 战略规划涉及开源项目（包括许可证合规、安全漏洞管理等）的相关决策者  

通过此类沟通获取的洞察，可用于定义组织特有的开源驱动因素，并将其映射到组织内开源可创造价值的具体领域。此举亦有助于在 OSPO 正式成立前，即在全组织范围内建立对开源工作的支持基础。  

建议结合 OSPO 成熟度模型，将上述驱动因素与组织内的不同活动类型进行关联映射，同时建立第二个维度分类体系，按成熟度模型的 0-4 阶段对各驱动因素进行归类。此框架可作为与利益相关方沟通时的核心参考依据。  

> **注**：您可通过该小组成员在 Qiita 平台发表的文章 [^9]，获取其工作成果的日文与英文双语摘要。  

在规划OSPO时，与不同团队的管理者、高层管理人员以及日常工作中使用开源软件的员工/合同工进行一对一的对话非常有帮助，尤其是那些战略规划涉及处理开源项目（包括许可证合规、安全漏洞管理等）的团队。通过此类沟通获取的洞察，可用于定义组织特有的开源驱动因素，并将其映射到组织内开源可创造价值的具体领域。

此举亦有助于在 OSPO 正式成立前，即在全组织范围内建立对开源工作的支持基础。  

通过使用OSPO成熟度模型并在其中创建第二个分类，将这些动机根据不同的阶段进行分类，从而将这些动机与组织内的不同活动类型进行映射。在与利益相关者互动和沟通时，以此作为参考。


举个例子：

<img width="942" alt="activityparticipationcategorization" src="/images/activityparticipationcategorization.png">

## 可能遇到的问题及应对方法  

### 问题  

在创建开源项目办公室（OSPO）过程中，您将会遇到很多问题，并需根据新信息不断调整计划。组织内部对开源的理解与价值认知存在明显不一致，导致混乱与潜在风险。  

### 建议  

确保投入时间识别所有利益相关方，并理解其动机。通过制定并公开开源宣言、原则及网站，促进全组织与子公司对价值观、原则与目标的统一认知。建立并强化全组织范围内对开源的共识性理解，将为 OSPO 奠定稳定而坚实的基础。  

## 资源与脚注  

### 资源  

- TODO Group《对外开源软件指南》：https://todogroup.org/resources/guides/a-guide-to-outbound-open-source-software/  
- TODO Group《参与开源社区指南》：https://todogroup.org/resources/guides/participating-in-open-source-communities/  
- DevOps 使用能力模型而非成熟度模型：https://octopus.com/blog/devops-uses-capability-not-maturity  
- 保时捷开源网站：https://opensource.porsche.com/  
- 开源项目办公室（OSPO）的演进历程：https://linuxfoundation.org/tools/the-evolution-of-the-open-source-program-office-ospo/  
- OSPO 101 培训模块 - OSPO 与您的组织：https://github.com/todogroup/ospo-career-path/tree/main/OSPO-101/module3  

### 脚注

[^1]: 战略 - FINOS 成熟度模型终局：https://osr.finos.org/docs/presentations/strategy  

[^2]: 开源战略文档制定指南：https://todogroup.org/resources/guides/setting-an-open-source-strategy/  

[^3]: OSPO深度研究报告：https://www.linuxfoundation.org/research/a-deep-dive-into-open-source-program-offices  

[^4]: OSPO 思维导图：https://todogroup.org/resources/mindmap/  

[^5]: Dr. Ibrahim H，《企业开源指南》：https://www.linuxfoundation.org/research/guide-to-enterprise-open-source  

[^6]: Carl-Eric：https://web.archive.org/web/20240419100823/https  ://debricked.com/blog/what-is-open-source-maturity-model/  

[^7]: TODO Group 成熟度模型：https://github.com/todogroup/ospology/blob/main/ospo-model/en/five-stage-OSPO-maturity-model.md  

[^8]: TODO Group OSPO 检查清单：https://github.com/todogroup/ospology/blob/main/ospo-model/en/ospo-checklist.md  

[^9]: OSPO Japan Local Meetup Working Group 工作成果双语摘要（Qiita文章）：https://qiita.com/owada-k/items/017d1b98d0e437766bd0  