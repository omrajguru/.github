# Contributing

I build things that last. Every project under this org exists to solve a real problem with precision and care. If you want to contribute, these are the standards I hold myself to, and the same ones I hold every contribution to.

Read this fully before opening an issue or writing a single line of code.

---

## Before You Write Code

Open an issue first. Describe the problem clearly. I review ideas before they become pull requests. A well-framed problem statement saves time for both of us and ensures your effort goes in the right direction.

If you are fixing a small and obvious bug, a PR is fine without a prior issue. For anything larger, start the conversation first.

---

## What Gets Merged

I accept contributions that:

- Solve a specific, clearly defined problem
- Fit the scope and direction of the existing project
- Arrive with clean, readable, and purposeful code
- Include tests where the logic has any meaningful complexity
- Respect the existing architecture and patterns of the codebase

I return or reject contributions that add complexity without purpose, duplicate functionality that already exists, or break existing behavior without a strong and documented reason.

A well-scoped contribution that does one thing well is always worth more than a large PR that tries to do everything at once.

---

## AI-Generated Code

I use AI tools in my own workflow. You can use them too. These rules apply without exception:

**You are fully responsible for every line you submit, AI-generated or not.**

- Review AI output the same way you would review code from a developer you are responsible for. Read it line by line. Understand it fully before submitting.
- AI-generated code that introduces security vulnerabilities, silent failures, untested edge cases, or logic that the submitter cannot explain will be rejected immediately.
- Declare in your PR description if significant portions of the code were AI-assisted. This is a professional standard, not a penalty.
- Copy-pasted AI output that has clearly never been reviewed or understood is grounds for immediate rejection and may result in restricted contribution access.
- AI is a tool for acceleration, not a replacement for understanding. If you cannot explain why the code works, it is not ready to submit.

The product has to keep working. That is the standard that overrides everything else.

---

## Code Standards

Write code you can read out loud and explain to someone else.

- Name variables, functions, and files with clarity. The name should describe the purpose, not the implementation.
- Keep functions focused on one responsibility. If a function needs a long comment to explain what it does, it is doing too much.
- Comments explain why a decision was made, not what the code is doing. The code itself should communicate the what.
- Handle errors explicitly and visibly. Silent failures are unacceptable. If something goes wrong, the system should say so clearly.
- Avoid premature optimization. Write clear code first. Optimize only when there is a measured reason to do so.
- Follow the conventions already established in the codebase. Consistency matters more than personal preference.

---

## Commits

Use clear, present-tense commit messages that describe exactly what changed.

**Good:**
```
Add rate limiting to the authentication endpoint
Fix null reference in user profile loader
Refactor payment processor to separate concerns
```

**Avoid:**
```
fix stuff
wip
updates
misc changes
```

One logical change per commit. If your commit message requires the word "and" to describe what changed, split it into two commits.

---

## Pull Requests

- Link the issue your PR addresses in the description.
- Describe what changed, why it changed, and how you verified it works.
- Keep PRs tightly scoped. One problem, one PR.
- Add screenshots or recordings for any UI changes.
- Expect thorough review. I read code carefully and I expect you to engage with feedback seriously.
- A PR that sits unresponsive to review comments for more than two weeks will be closed. You can reopen it when you are ready.

---

## Issues

- Search before opening. Duplicate issues slow everything down.
- Be specific. A vague issue report is impossible to act on and will be closed.
- Bug reports must include: steps to reproduce, your environment, expected behavior, and actual behavior.
- Feature requests must include: the problem you are trying to solve, why existing solutions are insufficient, and what you expect the outcome to feel like.

---

## The Standard

Quality over volume. A single well-reasoned contribution that improves the product is worth more than ten that add noise. I take the time to review seriously, and I ask you to contribute with the same seriousness.

If you engage with the codebase with care and intention, I will engage with your contribution the same way.

Ideas are always welcome. Execution is where the bar is high.
