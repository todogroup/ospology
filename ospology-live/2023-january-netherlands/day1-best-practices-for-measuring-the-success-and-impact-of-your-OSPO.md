## Best Practices for measuring the success and impact of your OSPO (day1)

We used the GQM approach to structure the information related to goals and metrics. The
result of the second iteration was a list of goals and topics related to that goal. As a
third iteration we managed to compose a list of metrics that can help us to answer some
of the questions.

### Goals and related topics

Goal1. Adopting healthy OSS:
- License compliance
- Helth of Open Source Components
- Assess software in open source is not against patents
- Identify risks in the OSS to be adopted (not security)

Goal2. Improve how OSS is used in your organization:
- Identify the OSS dependencies used by your codebase
- Reduce the risks (security issues not included here)
- Assess that the release of our internal products are using the correct libraries (they
  should be sustainable)

Goal3. Encourage wider use of OSS

Goal4. Attract Talent
- Attract better developers
- Increase number of contributions from my developers in OSS communities

Goal5. More engaged developers:
- Happier developers contributing to OSS projects (motivation)

Goal6. Contributing back
- Open source education: netiquette
- Draft a contribution policy
- Increase contributions from my developers
- Contribute back to be good citizens in OSS

Goal7. Publishing OSS:
- Open-sourcing: license, governance model, CLA

Goal8. Community Growth

## Goals, Questions, Metrics:

As result of the third iteration, we managed to connect goals and metrics for Goal1 and
Goal2. The list below contains: goals, questions that help us to know if the goals are
accomplished, and finally relevant metrics that help us to answer the questions.

Goal1. Adopting healthy OSS:
- Is the community active?
  - metric: active contributors
  - metric: number of PRs, commits, number of questions in forum, etc..
- How many releases does it publish?
  - metric: frequency of the releases
- Is the license compatible with our stack/polices?
  - metric: license declared in the code (obtain through static analysis of the license for that version)
- Are the dependencies healthy?
  - metric: (recurrency)
- Is this stable?
  - metric: size of the community of users
  - metric: number of bug reports
  - metric: lead time for bug reports

Goal2. Improve how OSS is used in your organization (Increase usage):
- What Components+version are being in my organization?
  - metric: depency tree (based on the SBOM)
  - metric: percent of the projects analyzed in your organization
- can the project introduce a compliance risk?
  - metric: is the project using a permissive license?
  - metric: is the project using a copyleft license?
  - metric: percent of the projects analyzed in your organization
