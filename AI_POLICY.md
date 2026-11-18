# AI contributions policy

Kindtech is built with a lot of help from AI tools, and contributions made with them are welcome. This policy exists so that the people who review your work can trust it.

## What we ask

**You own what you submit.** Understand every line. Be ready to explain what it does and why it is correct, without asking the model again. If you cannot, the change is not ready.

**Prove it works.** Run it. "It compiles" and "the tests pass" are not enough on their own. In the pull request, say what you ran and what you saw. For anything a person looks at, such as a map, a chart or a page, include a screenshot. Never claim testing that you, or your agent, did not do.

**Say which tools helped.** The pull request template has a section for this. Naming the tools is not held against you. It helps reviewers know where to look harder.

**Write in your own words.** Write the pull request description, issues and comments yourself. Do not paste raw model output.

**Keep it small.** One change per pull request, under 500 changed lines where you can, and no more than three open pull requests at a time. AI can write faster than people can review.

**Fix, do not just report.** If an AI tool found a bug for you, check that it is real, then open a pull request with the fix or an issue you have verified yourself. Unverified AI-written bug reports and security reports will be closed.

**Do not post AI reviews of other people's work.** If you are not the author or a maintainer, do not point a model at someone else's pull request and paste what it says.

## Data rule for AI tools

Never give an AI tool personal data about real people while working on a Kindtech project, and never paste such data into an issue or a pull request. This includes names, addresses, full postcodes and case notes. Use invented examples. Our tools are designed so that a model sees totals and never individual records, and contributions must keep it that way.

## For agents

If you are an AI agent working in a Kindtech repository:

- Read the repository's `AGENTS.md` first and follow it.
- State in the pull request which checks you ran and which you could not run.
- Do not invent results, sources, figures or citations.

## What happens otherwise

The first time a contribution does not meet this policy, we will close it with a link here and a short explanation. If it keeps happening, we may block the account.

## Why we are not against AI

A contributor who uses a model to understand unfamiliar code, draft a first version or catch a missed case is often doing better work than they could alone. What matters is that the person is steering the tool and stands behind the result.
