# Security

Please do not open a public issue for a security or privacy problem.

## How to report

Report it privately on the repository concerned. Go to **Security**, choose **Report a vulnerability**, and describe what you found and how to reproduce it. This uses GitHub's private vulnerability reporting, so only the maintainers can see it.

If the repository does not show that option, open an issue that says only that you have a security report to make, with no details. A maintainer will contact you to arrange a private channel.

We aim to acknowledge a report within three working days and to tell you what we plan to do within ten.

## What counts

Kindtech tools are used by charities, often alongside information about people in difficult circumstances. We treat privacy problems as security problems. Examples:

- a way for personal data, such as a full postcode or an address, to reach an AI model or a third party when the tool says it will not;
- a way for a tool to send a credential or an API key to a host other than the one it is for;
- a way for text inside a web page, a dataset or a document to make a tool act on instructions it contains;
- a way to read or change files, or data belonging to another organisation, beyond what the user allowed;
- a dependency with a known vulnerability that affects how we use it.

A repository may add its own `SECURITY.md` with more detail. Where it does, that file applies.

## Please do not

- test against systems or data that are not yours;
- include real personal data in a report. Describe the problem with invented examples.
