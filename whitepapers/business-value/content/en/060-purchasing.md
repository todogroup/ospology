---
title: Buying Open Source
weight: 60
---

# Buying Open Source

When organizations evaluate software, purchasing decisions are often influenced by licensing fees, vendor reputation, available support, and long-term operating costs. Open source software should be considered part of this process rather than treated as a separate category simply because its source code is publicly available.

Choosing open source does not necessarily mean that an organization must manage everything internally or rely entirely on community support. Businesses can purchase professional services, managed solutions, and commercial support while continuing to benefit from open source software.

The important question is whether the solution meets the organization's requirements and provides sustainable value over time. Open source and proprietary solutions should be assessed for their respective strengths, cost structures, and risks.

The value of open source in purchasing is not limited to the absence of a license fee. An open source license grants the purchaser specific rights: to use the software for any purpose, to study how it works, to modify it within the terms of the license, and to redistribute it. These rights can change the purchasing calculation. An organization may adapt the software to its own requirements, contribute improvements upstream to influence the project's direction, and, where a healthy ecosystem exists, choose among multiple providers and support arrangements. Exercising these options requires capability and engagement. Not every project has healthy governance, multiple providers, or an active contributor community, so purchasing decisions should assess the specific ecosystem around the project rather than assume these benefits.

## Including Open Source in Procurement

Procurement teams should evaluate open source and proprietary solutions against the same business requirements. These may include functionality, reliability, security, scalability, support availability, compliance, and total cost.

An open source solution may be available without a licensing fee, but organizations should still consider the resources required to deploy, operate, maintain, and support it.

Depending on their internal capabilities, businesses may choose among common approaches such as:

- Use and maintain the software internally.
- Purchase professional support from a service provider.
- Use a managed or hosted offering.
- Engage consultants for implementation, integration, or customization.
- Purchase additional enterprise services where available.

The choice depends on the organization's technical expertise, operational requirements, risk tolerance, and budget. The list above is illustrative rather than exhaustive, and organizations may combine several approaches, for example by self-managing core infrastructure while purchasing support for critical components or engaging a provider for specific operational tasks.

These purchasing choices represent the demand side of the business models described in [The mechanics of open source in business]({{< relref "050-mechanics-of-OS-in-business#business-models" >}}). Depending on their requirements, organizations may select a provider whose offering follows a suitable business model. The chapter explains the offering side: how providers create and monetize services and products around open source projects. Common open source business models include support and maintenance subscriptions, managed hosting, professional services, open core, and dual licensing, each of which shapes what a purchaser can buy and what responsibilities remain with the organization.

## Choosing Services Around Open Source

Organizations do not always need to build internal expertise for every technology they adopt. They may choose to work with external providers for implementation, maintenance, hosting, and support.

However, selecting a provider requires more than comparing service prices. Procurement teams should understand what the agreement actually covers.

For example, a support contract may include security updates, technical assistance, and defined response times. A managed hosting agreement may also cover infrastructure operations, monitoring, backups, and maintenance.

Before purchasing these services, organizations should clarify:

- What responsibilities remain with the organization?
- What services and maintenance activities are included?
- Are response times and service availability defined in a service-level agreement (SLA)?
- How are security vulnerabilities and critical updates handled?
- Can the organization move to another provider if requirements change?
- Does the provider actively work with the specific upstream project?
- Can the provider demonstrate relevant upstream contributions, code reviews, issue discussions, or security fixes?
- Are the people maintaining the software employed by the provider, the upstream project, or another organization?
- Does the provider explain how it reports defects and submits fixes upstream?

A clear understanding of these responsibilities helps avoid unexpected operational costs and dependencies.

Certifications, partner relationships, and service-level agreements can help assess a provider, but they do not show the full picture of its relationship with the software. Open source projects offer publicly visible evidence that purchasers can examine, such as contribution history, issue and pull-request activity, code reviews, security work, and release participation. This evidence can help distinguish a provider that actively helps maintain the upstream project from one that only packages or resells the software. It should complement, not replace, an assessment of service quality and contractual commitments.

## Purchasing Decisions and Open Source Sustainability

Open source projects need ongoing maintenance. Developers and maintainers spend time reviewing contributions, fixing defects, addressing security vulnerabilities, improving documentation, and supporting users.

Businesses that depend on open source software can help create a more sustainable ecosystem through their purchasing decisions.

For example, an organization may purchase commercial support from a company that employs maintainers or contributes improvements to the upstream project. This can provide both operational support to the organization and resources for the continued development of the software.

However, this relationship should not be assumed. A company selling a service based on open source software does not necessarily contribute financially or technically to the original project. Open source licenses generally do not require purchasers or commercial providers to contribute improvements or fund upstream development. The license grants rights; it does not impose a funding or contribution obligation. Organizations that expect a provider to contribute upstream should make that expectation explicit during evaluation and, where appropriate, in the contract.

Organizations interested in supporting sustainability can look for evidence such as:

- Contributions to upstream repositories, including accepted fixes, feature work, documentation, and code reviews.
- Participation in issue discussions, security response, release preparation, and other maintenance activities.
- Employment or financial support for project maintainers.
- Participation in project governance and community activities.
- Public commitments to security and long-term maintenance.
- Transparent policies for submitting fixes and improvements upstream.
- Foundation membership or sponsorship, which may indicate commitment to the project's ecosystem.

These indicators support judgement rather than replace it. Foundation membership or sponsorship can signal commitment, but it does not by itself demonstrate that a project is healthy or that the member has meaningful influence over its direction.

Purchasing decisions can therefore consider not only the service being delivered but also the provider's relationship with the software ecosystem on which the service depends.

## Evaluating Total Cost of Ownership

One of the most important considerations in software procurement is the difference between the initial acquisition cost and the cost of operating a solution over time.

Total Cost of Ownership (TCO) provides a broader view by considering the expenses associated with acquiring, deploying, maintaining, and eventually replacing a solution over a defined period. This applies to both open source and proprietary software.

For both open source and proprietary solutions, TCO typically includes:

- Implementation, migration, and integration.
- Infrastructure, hosting, and storage.
- Technical support and maintenance.
- Internal engineering and administration effort.
- Security assessments and compliance activities.
- Training and onboarding.
- Upgrades, customization, and future migration or exit costs.
- Renewal and subscription price increases.
- Downtime, operational risk, and business disruption.
- Provider dependency and the constraints it can introduce.

For open source software, procurement teams should also understand how responsibilities and costs are divided between the organization, the upstream project, and any service provider involved. A provider may take responsibility for activities such as hosting, maintenance, updates, and support, reducing the operational work visible to the customer. However, the underlying dependencies and the cost of changing providers should still be considered.

A solution with no initial licensing fee may still require considerable investment in internal expertise and infrastructure. On the other hand, a commercial offering may have recurring fees but reduce the operational responsibilities of the organization.

Open source development can distribute development and maintenance costs across multiple consumers and contributors, since different organizations may fund staff, contribute code and documentation, or pay for support without each bearing the full cost alone. This collaborative economic model is sometimes described as "coopetition" (cooperative competition) or "gaining by sharing", where organizations compete in the market but collaborate on shared foundational technology. This is an important economic characteristic of open source, but it does not mean the software has zero cost. Shared costs can also create a collective-action problem: if no participant funds upstream maintenance, the shared asset may degrade over time. Organizations may choose to invest in internal expertise or upstream development as an alternative to paying recurring proprietary licensing fees, but this is a strategic trade-off rather than a guaranteed saving. Open source is not always cheaper, and TCO comparisons should apply the same assumptions and evaluation period to all options under consideration.

### Example: Choosing a Database

Consider an organization deciding how to operate a database. It could evaluate several approaches.

The options below differ along two independent dimensions. The **licensing model** describes whether the software is open source or proprietary. The **deployment model** describes whether the organization operates the software itself or relies on a vendor-managed service. These dimensions are independent: a proprietary database can also be self-managed or offered as a managed service, and an open source database can be self-managed or provided as a managed service by a third party. Options A–C illustrate common licensing and deployment combinations. Option D describes a support or staffing arrangement that may complement one of the open source options.

**Option A: Self-managed open source database**

The organization installs and operates an open source database using its own infrastructure and engineering team.

Potential advantages:

- Greater control over configuration and operations.
- Flexibility in choosing infrastructure.
- No separate managed-service fee or proprietary database license fee.

Costs and responsibilities:

- Internal staff time and technical expertise.
- Infrastructure and maintenance.
- Backups, monitoring, and security updates.
- Troubleshooting and availability management.

**Option B: Managed open source database service**

The organization purchases a managed service from a provider offering the open source database.

Potential advantages:

- Reduced infrastructure management responsibilities.
- Access to provider support.
- Managed backups, monitoring, and maintenance, depending on the agreement.
- The possibility of retaining compatibility with the underlying open source database, depending on the service.

Costs and responsibilities:

- Recurring service charges.
- Potential additional charges for storage, usage, or data transfer, including egress fees.
- Dependence on the provider's service terms and capabilities.
- The service may rely on a proprietary control plane, provider-specific APIs, or extensions that are not part of the upstream project, which can affect portability.
- Data migration and exit considerations.

**Option C: Proprietary database**

The organization purchases a proprietary database product or service under a commercial license.

Potential advantages:

- Some products may offer closer integration with other services from the same vendor.
- Depending on the workload, a product may provide performance or functionality that better fits the organization's requirements.
- The vendor may provide an integrated support and maintenance arrangement.

Costs and responsibilities:

- License or subscription fees.
- Dependence on the vendor's pricing, licensing terms, and product roadmap.
- Potential difficulty migrating data or applications to another platform.
- Reliance on the vendor to continue maintaining the features and services on which the organization depends.

**Option D: Employ or contract an upstream maintainer**

The organization hires or contracts a maintainer, or a consultancy that includes upstream maintainers, to support and develop the open source database. This option may complement Option A or Option B rather than replacing them.

Potential advantages:

- Greater insight into, and potential influence over, the project's roadmap and technical direction.
- Access to deep expertise and potentially faster issue resolution.
- Contributions can benefit the upstream project and the wider user community.

Costs and responsibilities:

- Salary, benefits, or contracting fees, which may be significant for specialized expertise.
- Management overhead of employing technical staff or managing a contract.
- The responsibility to ensure the maintainer has the resources and time to balance upstream community work with the organization's specific needs.

Risks:

- If a single organization employs most of the core maintainers of a project, it can concentrate control and create a perception (or reality) of vendor lock-in, even if the software is open source. This dynamic can discourage contributions from other organizations and centralize decision-making. Organizations should evaluate whether the project has a diverse maintainer base or if this arrangement introduces single points of failure.

No option is automatically the least expensive or most suitable. Performance and integration advantages depend on the specific product and workload and should be validated rather than assumed.

The organization should compare these approaches over the same period, taking into account expected usage, staffing requirements, service commitments, licensing, infrastructure, and future migration costs.

## Understanding Vendor Lock-in

Open source licensing can give organizations more freedom to use, modify, and redistribute software, but it does not automatically remove every form of vendor dependency.

Dependency is not inherently undesirable. Organizations depend on software providers, maintainers, infrastructure, and operational expertise in both open source and proprietary environments, and some degree of dependency is unavoidable. The criticality of the dependency matters: a replaceable utility library presents a different risk profile than a core database expected to operate for decades.

The relevant question is whether the organization can manage these dependencies and retain meaningful control over where and how its software is operated, including the ability to change providers, operate the software independently, or migrate data on reasonable terms. Open governance and an ecosystem with multiple service providers can offer choice and competition, but an open source license does not by itself guarantee those conditions.

A managed service may rely on proprietary management tools, provider-specific APIs, or data formats that make migration difficult. Custom integrations and operational processes can also create dependencies, even when the underlying software is open source.

Before choosing a provider, organizations should consider:

- Whether data can be exported in documented, usable formats.
- Whether the service relies on proprietary extensions or interfaces.
- Whether the software can be operated with another provider or on the organization's own infrastructure.
- What migration assistance, fees, and technical work would be required to leave.
- Whether the contract clearly defines data ownership and deletion at the end of the service.

These questions help organizations understand the difference between having access to source code and having a practical ability to change providers.

Exit planning may include the possibility of forking the software. While forking a complex project is a significant undertaking, having a credible exit option—such as the internal capability to operate and maintain a fork, or contractual terms that preserve access to source code, data, and configuration needed to continue independently—can actually reduce the likelihood of needing to fork. Credible exit options encourage providers and upstream projects to resolve problems collaboratively, as they know the organization has viable alternatives.

## Governance and Project Structure

Licensing and governance are separate considerations. An open source license does not by itself determine how a project is governed, who controls its development, or how downstream users can influence its direction. The project's business model can shape its governance, and governance in turn affects the relationship between the project and the organizations that depend on it.

Purchasers should investigate questions such as:

- What business model, if any, supports the project's development and maintenance, and does it appear sustainable over the organization's expected period of use?
- Who has commit rights and decision-making authority?
- Are maintainers and committers primarily employed by one vendor, or can people from different organizations participate?
- Is the roadmap developed publicly, and can downstream users influence priorities?
- Are design decisions supported by a documented standards or technical decision-making process?
- Can users participate in technical discussions, working groups, or governance bodies?
- Who owns the project's trademarks, and what does that indicate about control of the project's name and identity?

A project's trademark ownership can provide a useful clue about who controls its identity and how the project is organized. Missing or unclear information about trademark ownership may also be worth investigating. These signals should be considered alongside the project's documented governance and actual decision-making practices.

Common arrangements include:

- **Single-vendor-controlled projects.** One company employs most of the maintainers, controls the roadmap, and may offer commercial editions or hosted services. The license may still be open source, but decision-making can be concentrated. Purchasers should understand the company's incentives and how much influence other contributors have.
- **Foundation-governed projects.** Some foundations provide governance structures intended to support neutrality and allow multiple organizations to participate in decision-making. The degree of neutrality and the influence of member companies vary between foundations, and membership alone does not guarantee independence.
- **Other arrangements.** Some projects use a technical steering committee, a community-elected leadership model, or informal governance with concentrated funding.

Governance is not simply a question of whether a project is controlled by a company or a foundation. The practical level of openness, participation, and influence matters. The InnerSource Commons Governance Levels pattern provides one useful way to think about different degrees of project governance and participation. The Mozilla report on open source software archetypes also discusses how different business and organizational models can affect project sustainability.

An open source license does not automatically guarantee neutral governance, a vendor-independent business model, or multiple competing providers. Some companies operate commercial businesses around open source software while retaining significant control over project direction. This is not inherently a problem, but purchasers should understand the arrangement, the project's decision-making process, and the risks of concentrated control.

## Understanding CAPEX and OPEX

Procurement decisions also affect how an organization plans and manages its expenditure.

**Capital Expenditure (CAPEX)** generally refers to spending on assets expected to provide benefits over multiple accounting periods.

**Operating Expenditure (OPEX)** generally refers to the recurring costs associated with operating a business.

For example, purchasing physical infrastructure that will be used for several years may be treated as capital expenditure. Recurring payments for managed hosting, subscriptions, and support services may be treated as operating expenditure.

This distinction can influence how organizations choose between open source and proprietary solutions. Building internal expertise, implementing an open source solution, or developing capabilities around an existing project may require more upfront investment than purchasing a proprietary service through an annual subscription. The subscription may require less initial investment but create recurring operating costs.

On the other hand, an organization that invests in its own infrastructure and technical capabilities may have different costs over the longer term. The right approach depends on the organization's needs, resources, and financial strategy.

The accounting treatment depends on the nature of the expenditure, applicable accounting standards, and the organization's financial policies. Internal expertise or software development effort should not automatically be classified as capital expenditure.

Simplistic classifications can be misleading. Not all perpetual licenses are treated as capital expenditure, and not all subscriptions are treated as operating expenditure. The classification depends on the facts of the arrangement, the applicable accounting standards, and the organization's financial policies, so procurement teams should involve finance and accounting early rather than infer the treatment from the licensing model.

Considering CAPEX and OPEX alongside TCO helps decision-makers understand both the overall financial commitment and how costs are distributed over time.

## A Practical Procurement Checklist

Before selecting an open source solution or service provider, organizations should consider the following areas.

**1. Licensing and usage rights**

Understand the software license, including the permissions and obligations associated with using, modifying, and distributing the software. Seek legal review where necessary.

**2. Project health**

Review the project's recent release history, maintainer and contributor activity, issue and security-report handling, documentation, governance, and published maintenance plans. Look for a clear security policy and evidence that important fixes are addressed. A large number of contributors alone does not guarantee project health; the organization should also understand whether maintenance depends heavily on a small number of people.

**3. Security and compliance**

Evaluate vulnerability reporting, security updates, dependency management, and compliance requirements. Public source code provides an opportunity for inspection, but does not automatically guarantee security.

**4. Support and service commitments**

Check the provider's expertise, support availability, escalation process, and service-level agreements. Make sure responsibilities are clearly defined.

**5. Vendor independence and portability**

Understand whether the organization can change providers, operate the software independently, and migrate its data without unreasonable disruption or cost. Check for proprietary extensions, provider-specific APIs, undocumented data formats, and contractual restrictions that could make an exit difficult.

**6. Total Cost of Ownership**

Compare acquisition, implementation, infrastructure, support, staffing, and exit costs over a defined period. Apply the same evaluation period and assumptions when comparing alternatives.

**7. Ecosystem sustainability**

Where relevant, consider whether the selected provider contributes to the upstream project or supports the people responsible for maintaining it. Look for verifiable evidence rather than relying only on marketing claims.

**8. Switching and exit planning**

Plan for how the organization could leave the arrangement before committing to it. Consider switching costs, data migration effort and usable export formats, the effort of implementing a replacement, loss of provider-specific features and integrations, re-training requirements, contract termination terms, data extraction or egress fees, and how operations would continue during a migration. This complements the TCO analysis by focusing on the cost and feasibility of ending the arrangement rather than operating it.

These considerations help procurement teams assess both immediate business requirements and the long-term implications of their choices.

## Further Reading

- [Public Procurement of Open Source Software — European Commission, Open Source Observatory](https://interoperable-europe.ec.europa.eu/collection/open-source-observatory-osor/public-procurement-open-source-software)
- [OSI Approved Licenses — Open Source Initiative](https://opensource.org/licenses)
- [FinOps Framework — FinOps Foundation](https://www.finops.org/framework/)
- [InnerSource Commons Governance Levels pattern](https://github.com/InnerSourceCommons/InnerSourcePatterns/blob/main/patterns/2-structured/governance-levels.md)
- [Mozilla open source software archetypes report](https://blog.mozilla.org/wp-content/uploads/2018/05/MZOTS_OS_Archetypes_report_ext_scr.pdf)
- [Coopetition — Wikipedia](https://en.wikipedia.org/wiki/Coopetition)
- [Forking and exit strategies (video discussion)](https://www.youtube.com/watch?v=1I3_ruFIteI)

## Conclusion

Open source should be part of normal software procurement discussions. Organizations may choose to procure, adopt, and deploy open source solutions, purchasing professional services and operational support where needed.

A good purchasing decision goes beyond comparing license fees. By evaluating licensing, project health, security, provider commitments, total cost of ownership, and long-term portability, businesses can make informed procurement decisions that deliver value to their organizations while contributing to a more sustainable open source ecosystem.
