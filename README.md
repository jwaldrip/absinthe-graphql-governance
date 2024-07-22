# Absinthe GraphQL Governance

## Objective

The objective of this repository is to establish a sustainable governance and maintenance framework for the Absinthe GraphQL library that balances the leadership of the BDFL (Ben Wilson) with a democratic and community-driven approach.

## Governance Structure

### Maintainers Committee

**Selection and Addition of Maintainers:**

- Maintainers will be nominated by the BDFL and added immediately or by existing maintainers and approved by a majority vote.
- Maintainers can be removed by a two-thirds majority vote of the committee if they fail to meet responsibilities or violate the code of conduct.

**Responsibilities of Maintainers:**

- Be active within the last 30 days in any of the following responsibilities:
  - Review and comment on issues posted to any of the Absinthe organization repositories.
  - Respond and participate in issues posted to the chat channel(s).
  - Compose proposals for future releases based on community submissions.
  - Gather votes on proposals and moderate discussions on proposals.

## Proposal Process

### Drafting, Reviewing, and Implementing Proposals

Inspired by Tezos, the governance process follows a cadenced approach where changes are proposed, discussed, agreed upon, and implemented.

**Proposal Period:**

- Contributors can submit proposals as pull requests (PRs) to the `absinthe-graphql/governance` repository and to the `exploration` branch.
- Proposals are added as a Markdown file to the `/proposals` directory with a filename of `[github-username]-[proposal-name]-MM-DD-YYYY.md`.

**Review and Discussion Period:**

- Proposals are open for community feedback and discussion in the PR thread.
- A designated review period (e.g., 2 weeks) ensures adequate time for feedback.

**Voting Period:**

- After the review period, maintainers will create a request for voting comment on the thread.
- Github reactions will be used to collect positive and negative votes.
- A 2:1 positive to negative feedback ratio is required for the vote to pass and for the proposal to move into the implementation phase.

**Implementation Period:**

- Approved proposals are assigned to contributors for implementation.
- Implementation progress is tracked publicly in the PR thread.

**Adoption Period:**

- When all the associated work/tasks are completed, a maintainer will move the proposal into the `/adopted` folder of the governance repository.

**Continuous Improvement:**

- Regular retrospectives can help identify bottlenecks and areas for refinement.

## Additional Considerations

- **Transparency:** All discussions and decisions should be public and well-documented.
- **Inclusivity:** Encourage participation from a diverse range of contributors.
- **Adaptability:** The process should be flexible enough to accommodate changes in the community and project needs.
- **Tooling:** Consider using tools like GitHub Actions to automate parts of the process.

## Release Management

### Cadence and Process

**Release Cadence:**

- Regular releases will be released on the first Tuesday of each quarter.
- Additional releases are aligned with the last two major Elixir and OTP releases to ensure compatibility and stability.
- Library Versioning will be in line with Semver.

**Process:**

- A release manager is appointed for each release cycle.
- Release notes are prepared, highlighting new features, bug fixes, and breaking changes.
- Pre-release versions are shared for community testing before the final release.

**Automation:**

- Continuous Integration/Continuous Deployment (CI/CD) pipelines are established to automate testing, building, and deployment.
- Tools like GitHub Actions or CircleCI are used to ensure seamless integration, review, and deployment processes.

## Version Support

**Supporting Older Elixir/OTP Versions:**

- Support for older Elixir/OTP versions is maintained for the last two major Elixir releases and the corresponding OTP versions.
- Deprecated versions receive critical bug fixes and security patches only.

## Dispute Resolution

**Handling Disputes:**

- Disputes are first addressed through direct discussion among the involved parties.
- If unresolved, a mediator from the maintainers committee is appointed.
- Persistent disputes are resolved by a majority vote of the maintainers committee.

## Code of Conduct

- Adhere to a code of conduct that promotes respect, inclusivity, and constructive collaboration.
- Violations are handled by a code of conduct committee with transparent processes.

## Education and Advocacy

**Programs:**

- A better website to contain richer documentation, guides, and blog.
- Regular webinars, workshops, and conference talks to educate and advocate for Absinthe.
- Community-driven documentation and tutorial projects.
- Active presence on social media and community forums.
- A directory of companies using Absinthe to build trust.

## Public Communication

**Chat:**

- Elixir Slack in #absinthe-graphql
- Elixir Discord in #absinthe

**Live:**

- Monthly community calls for updates and Q&A sessions.

## Sponsorship Opportunities

**Opportunities:**

- Companies and/or individuals will be listed as contributors and ranked based on the amount of their contribution to the libraries.
- Companies can financially sponsor features, events, or community initiatives.
- Financial contributions are welcomed via GitHub Sponsors.

**Utilization:**

- Funds are used for bounties on bugs and features, community events, and infrastructure costs.
- The committee will appoint a treasurer to handle all financial transactions.
