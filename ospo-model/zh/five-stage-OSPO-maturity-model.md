# 组织 OSPO 模型分类标准

我们希望这是一份动态文件，旨在建立 OSPO 模型的分类标准并确定有助于不同组织学习和实施的关键组件（模式）。

社区可以对`五阶段 OSPO 成熟度模型`进行颠覆式贡献，以更好地满足特定垂直行业和/或地区的需求。

> 如果您想做出贡献，请提交 PR。


## OSPO 模型 1 —— 五阶段 OSPO 成熟度模型

> Full study can be found at [The evolution of the OSPO](https://linuxfoundation.org/tools/the-evolution-of-the-open-source-program-office-ospo/)
> 
> To learn more about OSPO characteristics, structure and roles, please check [A Deep Dive Into OSPO](https://www.linuxfoundation.org/tools/a-deep-dive-into-open-source-program-offices/)

As OSPOs have proliferated and become more common, these programs have matured. By mapping conversations with OPSO leaders and experts to the OSPO survey results, we have developed an OSPO maturity model to describe the typical evolution of OSPOs. Please note that *one size does not fit all*. This model has been proved to work better in those environments where open source was not *traditionally* implemented on its *day-to-day operations* at first. Also, the size and the type of the organization affect how the OSPO matures. In larger organizations, multiple business units might develop different approaches to open source, each with a different technology culture; and pure digital technology companies are far more likely to consume and contribute to OSS early and have greater exposure to open source technologies and concepts.

![LFResearch_OSPO_Report_Fig2](https://user-images.githubusercontent.com/43671777/167606513-18cb999e-8d01-4807-a23e-2ad5f6ec85f7.jpg)

**揭秘 OSPO 模型**

The level of an OSPO is determined by its ability to execute. Also, each stage is cumulative. This means that, when advancing across levels, the OSPO also takes care of the 
tasks and responsibilities from the previous level.

For instance, once an OSPO has covered all the required tasks related with open source compliance and security (level 1), this OSPO might be ready to move to level 2.
Now this OSPO should be taking care of the OS legal responsibilities from level 1 and the ones related with evangelizing OSS culture and ecosystem participation (level 2).

## 0️⃣ 阶段 0： 临时采纳开源

Today, almost all organizations use OSS. How they adopt and initially use it varies. They may use OSS  as a building block or library in a product or 
tool or a key part of a vendor’s product stack or supporting the vendor’s service offering. Developers may use OSS for rapid prototyping or for 
microservices and small applications. Developers also frequently adopt OSS development tools such as integrated development environments (IDEs), 
or tools built on top of open source like GitHub and GitLab. Modern cloud native applications, almost by default, use open source systems for container 
orchestration, observability, data storage, messaging, and more. On the front-end of applications, developers rely heavily on open source libraries and 
frameworks. Red Hat Hat reported that “90% of IT leaders are using enterprise open source.” Software composition analysis vendors like Synopsys determined 
that over 75% of all codebases contained open source components.

In other words, nearly every organization is using open source. However, the very earliest form of adoption is ad hoc, by developers solving problems using 
readily available tools and technologies. This “ad hoc adoption” usually means little thought is given to license compliance outside the defaults or to longer-term 
impacts of consuming open source and distributing products built with open source components. In most of these instances, a few engineers are actively seeking out open source 
while the rest of the engineering organization may use open source coincidentally but does not view its activities as dependent on open source. Consequently, the organization 
has neither a centralized team focused on open source nor a top-level open source strategy for the organization. These are critical because, once adopted, those open source components 
become part of the organization software supply chain by default, which makes a strategic approach all the more imperative.



## 1️⃣ 阶段 1： 提供 OSS 合规、清单和开发者教育

In general, an organization forms an OSPO when it realizes that its people are consuming open source products and code across nearly all engineering and development departments and functions. 
This usage is typically internal, not part of products or services to customers or users. In reality, any organization with a considerable IT function and an advanced online or application-centric 
presence uses open source, because of the ubiquity of open source throughout the technology stack—from Linux servers and MySQL databases to programming languages like NodeJS and Python and front-end frameworks like React and Vue.js.

At this early stage, organizations often use many different names for the OSPO. IBM initially called its programmatic open source efforts the “Open Source Steering Committee,” for example. In all cases, however, organizations in 
Stage 1 recognize that OSS is a key part of their business and technology strategy. They understand that the security practices of OSS projects differ from those of proprietary software companies. For example, disclosure rules 
of OSS projects tend to be stricter than those of proprietary projects. So they must identify their legal and security risks. Risk mitigation strategies include careful licensing, developer education, and rigorous inventory-taking.


### 管理法律风险和许可

An organization’s legal team or technology leaders tend to launch Stage 1 development of an OSPO to ensure that its employees (and contractors, suppliers, etc.) all use OSS according to
its license terms and that the organization’s OSS consumption is not putting it at legal risk. There are dozens of OSS licenses in use. In the 2020 survey, respondents ranked compliance as 
the top benefit of OSPOs of larger companies, and compliance remains the second leading benefit for medium-sized companies. “Companies usually start out with a lot of confusion.

While OSS users have always considered legal compliance, some OSS contributors have designed new licenses to discourage large cloud providers from creating proprietary services based on 
open source projects. The most prominent of these is the Affero General Public License (AGPL). A company might use OSS released under the terms of this license to deliver proprietary 
software-as-a-service (SaaS) to its customers, but the creator of the OSS might have grounds to sue the company for license violation if the AGPL terms do not clearly distinguish between internal 
and external delivery. Many businesses also have internal financial charging systems between units, further blurring the line between a paid service and an internal service. 

### 教育开发者

To maintain compliance, organizations in Stage 1 of OSPO maturity create education programs to help their developers decide when to use OSS in creating 
new products or services. “Many developers who are not educated in open source think that because they are not purchasing software, there is no license 
involved because they didn’t sign a contract,” said Suzanne Ambiel, director of open source marketing and strategy at VMware. “Open source software may 
be free—as in priceless—it can also be costly if used in a noncompliant way. [OSS] always comes with a license. One of the most important roles of any 
OSPO is to make sure developers understand the implications of different license choices.”

Through developer education, senior management often acknowledges the value and importance of OSS. In such programs, developers learn:

* The nuances of different license types
* The formal approval processes for introducing new OSS products 
* The real risks of noncompliant OSS consumption, including the usage of OSS products from projects or code without formal licenses
* The use of contributor license agreements (CLAs) to cover an organization’s developers who contribute to open source

Sometimes the organization introduces a formal CLA policy at this stage. It may also provide guidance on judging the health of OSS projects as part of its criteria for deciding which OSS to use in the organization’s technology stack or infrastructure. 

### 盘点软件清单

Developers may deploy OSS ad hoc without cataloging their efforts systematically. The legal team and technology leadership tend to push for an inventory 
of all OSS in use in an organization. Such an inventory itemizes OSS in organization’s code repositories (e.g., GitHub, GitLab) and systems. 
Stage 1 organizations set up specific software inventory processes to create an organization-wide software bill of materials (SBOM). With this inventory, 
the legal team—usually working with the OSPO team—can continuously monitor OSS usage and flag legal, security, or other project risks. With a detailed SBOM, 
technology leadership such as a chief technology officer (CTO) or chief information officer (CIO) can identify and closely monitor the most business-critical 
uses and preserve organizational security.


**本阶段建议参与的 OSS 社区列表**

| 横向技能 | 项目 / 社区 |
| --- | --- |
| 合规 | Open Chain |
| 安全 | OpenSSF |
| | SPDX |

> Do you want to list other OS communities? please open a PR

## 2️⃣ 阶段 2： 布道 OSS 应用和生态参与

After organizations recognize the value of OSS and the need for compliance, education, and an SBOM, they begin to realize the economic benefits of OSS 
usage and seek to expand it. OSPOs in Stage 2 create such internal mechanisms as ambassadors who promote usage of approved OSS products, educational 
programs on good OSS hygiene, and technical training or tuition reimbursement for skill building and certification in OSS. With these initiatives, an 
organization can grow its use of OSS and amplify its message that OSS is not only important but desirable and preferable to proprietary software products. 

Employee education includes laying out best practices in interacting with OSS projects such as how to request features, file bug reports, and contribute 
basic code. During this stage, the organization strengthens its collaborative muscle and experiences the social life of an OSS project and community. 
At this point, the OSPO communicates to employees and managers the importance of contributing to and not merely consuming OSS. This outreach includes 
advocating for and driving event sponsorships, booking project leads and maintainers as speakers or panelists in public coding forums, and securing 
organizational resources (e.g., talent, funding) to mission-critical OSS projects. 

For organizations, active and visible participation yields multiple benefits: better visibility, better reputation, more attractive employer. 
To this end, many non-tech organizations purchase booths. at prominent OSS events to interact more with those communities and recruit developers 
who enjoy working in OSS ecosystems. Technology companies active in open source may extend education programs to customers who want to interact 
with OSS communities and vendors.

As they advance in Stage 2, organizations begin incentivizing their developers to work on OSS projects critical to their operations, to the degree 
that developers become highly active contributors or primary maintainers. To technology organizations, employing a contributor to a prominent OSS project 
is a valuable investment: most of their contributors to, say, the Linux kernel—the core component of the Linux operating system and the critical interface 
between computer hardware and software—are full-time employees (FTEs) whose job is to write code for Linux. 

Outside the technology sector, fewer organizations can assign FTEs to open source work, but they are doing it. For example, both Comcast and Bloomberg 
have employees working full-time on OSS projects. In this stage of the life cycle, OSPOs begin exploring how to streamline processes for developers to 
consume OSS. Such developer efficiency may include simplifying CLAs, adding OSS with acceptable license types to ticketing systems for fast approval, 
promoting reuse of OSS architecture and software in place (a variation on inner-sourcing), and standardizing library selection and open source development 
tools, thereby blending OSPO and platform operations duties.

Usually in Stage 2 of the OSPO maturity cycle (or sometimes in Stage 1, if the company is a software or core technology company), OSPOs begin to streamline 
and optimize open outbound source contributions for their developers. The process of requesting and getting approval for outbound participation is usually ad hoc 
and painful in the early days

**本阶段建议参与的 OSS 社区列表**

| Horizontal Skills | Project / Community |
| --- | --- |
| Community Health and metrics | CHAOSS |
| Internal OS Culture | InnerSource Commons |

> Do you want to list other OS communities? please open a PR

### 3️⃣ 阶段 3： 发起开源项目和发展社区

At Stage 3, organizations initiate and then host or act as primary sponsors of OSS projects. They will dedicate one or more FTEs to a project, 
and they accept responsibility for nurturing a project community and ensuring its health. They don’t confuse this level of organizational commitment 
with individual employees who decide to open-source their projects. In Stage 3, organizational leaders support incubating and launching open source 
projects into the public sphere because they understand how these projects benefit their organization. Such projects tend to offer better performance 
and economics on crucial capabilities that may be noncore to the organization’s value proposition but critical to its technology infrastructure. 

In addition, organizations that create and launch open source projects establish broad credibility in the open source community; the possibility of 
working on open source technology is attractive to many developers.  Most of the OSPOs we spoke with cited recruitment of new engineering talent and 
retention of existing talent as a key motivation of the open source effort.

Supporting a project with FTEs and funding is true skin in the open source game. Organizations that cross this threshold and successfully launch multiple 
open source projects develop internal resources and processes that can incubate and ensure the success of these projects post launch. OSPOs are more than 
just gatekeepers and mentors for project formation and launch; they educate project creators on the requirements for cultivating a healthy open source 
ecosystem, and they coach project leads to prepare them for a more public leadership role required of an OSS project. 

As an OSS organization matures, its OSPO develops internal processes, playbooks, checklists, tooling, and other mechanisms to vet, organize, and operate 
open source projects and to prepare and coach their leaders. Some OSPOs prefer to launch projects with the assistance of the major open source foundations 
or collaboratives such as the TODO Group to enhance capabilities or provide infrastructure, tactical assistance, and other resources. This preference is less
resource intensive but cedes control of a project to a broader community.

**本阶段建议参与的 OSS 社区列表**

| Horizontal Skills | Project / Community |
| --- | --- |
| Community Health and metrics | CHAOSS |
| Project-specific and and Umbrella Foundations | Linux Foundation |
| | CNCF |
| | Eclipse Foundation |
| | Apache Foundation |


> Do you want to list other OS communities? please open a PR

### 4️⃣ 阶段 4： 成为战略决策合作伙伴

At this maturity stage, the OSPO becomes a strategic partner for technology decisions, helping to guide choices and shape long-term commitments to 
projects. At Stage 4, the CTO and other technology leaders consult the OSPO and its leadership on which open source technologies to rely on 
and which decision criteria to use in judging open source projects. Because major open source technology choices tend to generate significant 
secondary and tertiary costs and affect upstream and downstream technologies as well as hiring plans, the choice of open source projects becomes 
a major business decision. 

In broad terms, OSPOs provide three types of strategic guidance in Stage 4. First, the OSPO advises the CTO and technology leadership on which 
open source technologies to adopt or remove from the organization’s technology stack. Given the many OSS options today—with most major categories of 
software featuring dozens of choices as shown in Figure 2—the OSPO can provide insights into OSS trends such as popularity of different languages, 
designs of APIs, or capabilities of different NoSQL databases. In this role, the OSPO becomes an internal technology consultant to the CTO and the 
in-house expert on OSS. 

In a second type of strategic guidance, OSPOs take the lead on benchmarking what constitutes an acceptable OSS project. 
The OSPO often evaluates the behavior and performance of the project, especially changes in license type that limit usage, or abrupt shifts 
in the project roadmap, to determine whether a project manager has the best interests of the community in mind. Most OSPOs rely on back-of-the-envelope 
metrics to evaluate project behavior such as:

* Which type of license does it have?
* What is its code of conduct, and what are the consequences for breaking it?
* What is its governance structure, and does this structure ensure independence?
* How long does it take to respond to pull requests or bug filings?
* How frequently does the project ship new versions?
* Does one party (company or organization) or a whole community control the project?
* How many contributors does the project have? How has that number changed over time?

A third type of guidance is helping organizations understand and navigate project politics, such as maintaining a neutral stance when multiple influential 
actors are attempting to steer a project, or illuminating the latent political considerations of community members. At a higher plane, OSPOs can help companies 
maintain a neutral posture on techno-nationalism and bridge political differences by cultivating personal and working relationships that transcend national
boundaries and political realms. Increasingly, this value extends to the work of foundations and nonprofits, as those realms become important neutral spaces in open source.

**本阶段建议参与的 OSS 社区列表**

| 横向技能 | 项目 / 社区 |
| --- | --- |
| 社区健康和指标 | CHAOSS |
| 特定项目与伞式基金会 | Linux 基金会 |
| | CNCF |
| | Eclipse 基金会 |
| | Apache 基金会 |


> 你想列出其他开源社区吗？请提交 PR
