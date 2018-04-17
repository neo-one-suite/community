# Community membership

**Note:** This document is in progress

This doc outlines the various responsibilities of contributor roles in NEO•ONE.

| Role | Responsibilities | Requirements | Defined by |
| -----| ---------------- | ------------ | -------|
| member | active contributor in the community | sponsored by 2 reviewers.  multiple contributions to the project. | NEO•ONE GitHub org member. |
| reviewer | review contributions from other members | history of review and authorship | [OWNERS] file reviewer entry. |
| approver | approve accepting contributions | highly experienced and active reviewer + contributor | [OWNERS] file approver entry|
| owner | set direction and priorities for the project | demonstrated responsibility and excellent technical judgement for the project | [OWNERS] file *owners* entry |

## New contributors

[New contributors](.github/CONTRIBUTING.md) should be welcomed to the community by existing members, helped with PR workflow, and directed to
relevant documentation and communication channels.

## Established community members

Established community members are expected to demonstrate their adherence to the principles in this
document, familiarity with project organization, roles, policies, procedures, conventions, etc.,
and technical and/or writing ability. Role-specific expectations, responsibilities, and requirements
are enumerated below.

## Member

Members are continuously active contributors in the community.  They can have issues and PRs assigned to them.
Members are expected to remain active contributors to the community.

**Defined by:** Member of the NEO•ONE GitHub organization

### Requirements

- Enabled [two-factor authentication](https://help.github.com/articles/about-two-factor-authentication) on their GitHub account
- Have made multiple contributions to the project or community.  Contribution may include, but is not limited to:
    - Authoring or reviewing PRs on GitHub
    - Filing or commenting on issues on GitHub
    - Contributing to community discussions (e.g. meetings, Discord, email discussion
      forums, Stack Overflow)
- Actively contributing to the project.
- Sponsored by 2 reviewers. **Note the following requirements for sponsors**:
    - Sponsors must have close interactions with the prospective member - e.g. code/design/proposal review, coordinating
      on issues, etc.
    - Sponsors must be reviewers or approvers.
- Send an email to *contact@neo-one.io* with:
   - CC: your sponsors on the message
   - Subject: `REQUEST: New membership for <your-GH-handle>`
   - Body: GitHub handles of sponsors
   - Body: List of contributions (PRs authored / reviewed, Issues responded to, etc)
- Have your sponsoring reviewers reply confirmation of sponsorship: `+1`
- Wait for response to the message
- Have read the [contributing guide](https://neo-one.io/docs/en/contributing.html)

Example message:

```
To: contact@neo-one.io
CC: <sponsor1>, <sponsor2>
Subject: REQUEST: New membership for <your-GH-handle>
Body:

Sponsors:
- <GH handle> / <email>
- <GH handle> / <email>

List of contributions:
- <PR reviewed / authored>
- <PR reviewed / authored>
- <PR reviewed / authored>
- <Issue responded to>
- <Issue responded to>

```

### Responsibilities and privileges

- Responsive to issues and PRs assigned to them
- Responsive to mentions
- Active owner of code they have contributed (unless ownership is explicitly transferred)
  - Code is well tested
  - Tests consistently pass
  - Addresses bugs or issues discovered after code is accepted
- They can be assigned to issues and PRs.

**Note:** members who frequently contribute code are expected to proactively perform code reviews and work towards
becoming a primary *reviewer*.

## Reviewer

Reviewers are able to review code for quality and correctness.
They are knowledgeable about both the codebase and software engineering principles.

**Defined by:** *reviewers* entry in the [OWNERS] file.

**Note:** Acceptance of code contributions requires at least one approver in addition to the assigned reviewers.

### Requirements

- member for at least 3 months (may be waived in certain circumstances)
- Primary reviewer for at least 5 PRs to the codebase
- Reviewed or merged at least 20 substantial PRs to the codebase
- Knowledgeable about the codebase
- Sponsored by an approver
  - With no objections from other approvers
  - Done through PR to update the [OWNERS] file
- May either self-nominate or be nominated by an approver.

### Responsibilities and privileges

- Code reviewer status may be a precondition to accepting large code contributions
- Responsible for project quality control via code reviews.
  - Focus on code quality and correctness, including testing and factoring
  - May also review for more holistic issues, but not a requirement
- Expected to be responsive to review requests.
- Assigned PRs to review related to area of expertise
- Assigned test bugs related to area of expertise
- Granted "read access" to NEO•ONE repo
- May get a badge on PR and issue comments

## Approver

Code approvers are able to both review and approve code contributions.  While code review is focused on
code quality and correctness, approval is focused on holistic acceptance of a contribution including:
backwards / forwards compatibility, adhering to API and flag conventions, subtle performance and correctness issues,
interactions with other parts of the system, etc.

**Defined by:** *approvers* entry in the [OWNERS] file.

### Requirements

- Reviewer of the codebase for at least 3 months
- Primary reviewer for at least 10 substantial PRs to the codebase
- Reviewed or merged at least 30 PRs to the codebase
- Nominated by an owner
  - With no objections from other owners
  - Done through PR to update the [OWNERS] file

### Responsibilities and privileges

- Approver status may be a precondition to accepting large code contributions
- Demonstrate sound technical judgement
- Responsible for project quality control via code reviews
  - Focus on holistic acceptance of contribution such as dependencies with other features, backwards / forwards
    compatibility, API and flag definitions, etc
- Expected to be responsive to review requests
- Mentor contributors and reviewers
- May approve code contributions for acceptance

## Owner

Owners are the technical authority for the NEO•ONE project.  They *MUST* have demonstrated
both good judgement and responsibility towards the health of the project. Owners *MUST* set technical
direction and make or approve design decisions for the project - either directly or through delegation
of these responsibilities.

**Defined by:** *owners* entry in the [OWNERS] file.

### Requirements

- Deep understanding of the technical goals and direction of the project
- Deep understanding of the technical domain of the project
- Sustained contributions to design and direction by doing all of:
  - Authoring and reviewing proposals
  - Initiating, contributing and resolving discussions (emails, GitHub issues, meetings)
  - Identifying subtle or complex issues in designs and implementation PRs
- Directly contributed to the project through implementation and / or review
- Nominated by 2 owners
  - With no objections from other owners
  - Done through PR to update the [OWNERS] file

### Responsibilities and privileges

- Make and approve technical design decisions for the project.
- Set technical direction and priorities for the project.
- Define milestones and releases.
- Mentor and guide approvers, reviewers, and contributors to the project.
- Ensure continued health of project
  - Adequate test coverage to confidently release
  - Tests are passing reliably (i.e. not flaky) and are fixed when they fail
- Ensure a healthy process for discussion and decision making is in place.
- Work with other project owners to maintain the project's overall health and success holistically
- Approve contribution rewards

[OWNERS]: OWNERS

### TODO:

 - Add code review guidelines
 - Add community expectations guidelines
