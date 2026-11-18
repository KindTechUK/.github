# Contributing to Kindtech

Thank you for wanting to help. Kindtech builds open source data and AI tools for charities, and most of what makes them useful comes from people who know a data source, a charity's question, or a better way to do an analysis.

This guide covers every Kindtech repository. A repository may add its own `CONTRIBUTING.md` or `AGENTS.md` with setup commands and rules that are specific to it. Where they differ from this guide, the repository's own file wins.

## Ways to help

You do not need to write code.

- **Tell us what broke.** An issue with what you did, what you expected and what happened is the most useful thing there is.
- **Tell us what you cannot answer.** If you work at a charity and there is a question your data cannot answer today, open an issue and describe it. Real questions decide what we build next.
- **Add a use case.** Add an example of a charity using AI to the [use cases list](https://github.com/KindTechUK/awesome-charity-ai-use-cases). This needs no code.
- **Add a data source.** Teach the open data package to read another public dataset.
- **Add a worked analysis.** Turn a real charity question into a notebook others can run with their own data.
- **Add a skill.** Package a piece of UK charity know-how so an AI assistant can use it, with tests that show it helps.
- **Improve the docs.** If something confused you, it will confuse the next person.

Issues labelled `good first issue` are small and well described. Issues labelled `help wanted` are ones we would be glad for someone to take.

## Before you start

- **For a bug fix or a docs fix**, open a pull request. You do not need to ask first.
- **For anything new**, open an issue first and say what you want to add and why. We will tell you early whether it fits, which saves you building something we cannot merge.
- **We do not assign issues.** If you want to work on one, say so in a comment and open a pull request when you have something to show.

## Making a change

1. Fork the repository and create a branch.
2. Follow the setup steps in that repository's README or `AGENTS.md`.
3. Keep the change small and about one thing. Aim for under 500 changed lines. Split anything larger.
4. Add or update tests for behaviour you change. Update the docs in the same pull request.
5. Run the repository's tests and checks before you push.
6. Sign off your commits (see below).
7. Open a pull request and fill in the template: what and why, how you tested it, and which tools helped.

We aim to reply to every new issue and pull request within two working days. A full review can take longer.

## Data and privacy rules

These apply everywhere, and a pull request that breaks one will not be merged.

- **No personal data about real people.** Never put a real service user's name, address, full postcode or case details in code, tests, fixtures, docs, issues or pull requests. Use invented people for examples.
- **Public data keeps its licence.** When you add a data source, say where it comes from and which licence it is published under.
- **Tests do not call the network** unless the repository says otherwise. Use small saved samples.

## Sign off your commits

We use the [Developer Certificate of Origin](https://developercertificate.org/). It is a short statement that you wrote the change, or have the right to submit it, under the project's open source licence. There is no separate agreement to sign.

Add the sign-off by committing with `-s`:

```bash
git commit -s -m "fix: handle missing postcode"
```

This adds a `Signed-off-by` line with your name and email to the commit message.

## Using AI tools

AI-assisted contributions are welcome, and we use these tools ourselves. You are responsible for what you submit. Read the [AI policy](AI_POLICY.md) before opening a pull request written with an AI tool.

## Conduct and security

Everyone taking part is expected to follow the [code of conduct](CODE_OF_CONDUCT.md). Report security or privacy problems privately, as described in the [security policy](SECURITY.md).

## Licence

Kindtech code is open source, and each repository's `LICENSE` file says which licence applies. By contributing, you agree that your contribution is released under that licence.
