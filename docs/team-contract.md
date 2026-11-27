# Team contract

Agree on this before writing code and commit it through a pull request. The author signs by opening that pull request; **every other member signs by approving it** (GitHub doesn't let you approve your own). Merge only when every approval is in. Revisit it after each milestone.

## Members and roles

Every member writes code. Roles say who leads an area, not who does all of it.

| Name | GitHub | Role(s) | Strength we can rely on | Something I want to learn |
|---|---|---|---|---|
| Osama Bin Mansur | @obmZZ | Team lead / Scrum master |Breaking down features into clear Jira issues, keeping sprint timelines on track, and coordinating check-ins or PR review | Setting up automated CI pipelines or writing backend integration tests|
| Md. Saimon Islam | @Saimon-BsCSE | Backend lead |Designing REST APIs, database schemas, and server-side operational and business logic| Dockerizing services or connecting frontend components to live API endpoints|
| Khaled Mahmud Shihab | @ | Frontend lead |Building responsive UI layouts, component state management, and styling | Writing end-to-end UI tests or debugging backend API error handling|

## Communication

- Main channel (e.g., a Messenger or Discord group): Whatsapp Group
- We reply to teammates within: 1hr
- Decisions are recorded in: Pull requests
- Help from the instructor: through GitHub **Help request** issues

## Meeting rhythm

- Sprint length: (2 weeks; the Jira sprints follow it)
- Weekly planning: Wednesday; 10pm
- Short check-ins: ( Monday and Thursday, 10 minutes)
- Weekly status report in `reports/YYYY-MM-DD.md`, written by: All Members (rotates weekly)

## Definition of Done

A Jira issue is done only when:

- [✓] The acceptance criteria pass
- [✓] Tests are written or updated and pass (and CI is green, once you add CI in Class 7)
- [✓] The pull request is reviewed and approved by another member, then merged
- [v] Documentation is updated where needed (and `CHANGELOG.md`, from Class 8)
- [✓] The Jira issue is moved to Done with the pull request linked

## When things go wrong

1. Missed deadline or silence: the team lead messages the member within 24 hours.
2. Still unresolved after 48 hours: discuss it at the next meeting and record the agreed action in the weekly report.
3. Still unresolved: open a **Help request** issue for the instructor, with facts (dates, Jira issues, pull requests), not feelings.

Disagreements about design are settled with evidence: a quick prototype, a measurement, or an ADR.

## AI use agreement

Within the course policy:

- Fundamentals first: no AI-generated code in work that is meant to show your own understanding.
- When AI helps, say so in the pull request (which tool, for what) and in the README's "AI use" section.
- Every member can explain every line they submit; anything you cannot explain is rewritten.
- Never paste secrets, keys or personal data into an AI tool.

Our extra rules: …

## Signatures
Osama 
Saimon
Shihab

The author opens the pull request that adds this file; every other member approves it before it is merged. Date agreed: …
