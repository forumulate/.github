# Security policy

We operate Forumulate as a hosted service, so we are responsible for fixing any
vulnerability on [forumulate.com](https://forumulate.com), on any customer site we serve,
and in any of our public repositories.

## Reporting a vulnerability

**Please do not open a public issue, discussion or forum post.**

Email **[security@forumulate.com](mailto:security@forumulate.com)** with:

- What is affected (a URL, an API endpoint, or a package and version).
- Steps to reproduce, or a proof of concept.
- The impact as you understand it, such as whose data could be read or changed.
- How you would like to be credited, if at all.

You can also use GitHub's **private vulnerability reporting** ("Report a vulnerability"
under the Security tab) on any of our public repositories.

The same contact is published at
[forumulate.com/.well-known/security.txt](https://forumulate.com/.well-known/security.txt).

## What to expect

- We will acknowledge your report and keep you informed while we investigate and fix it.
- We will tell you when the fix is live, and credit you if you want to be credited.
- Please give us reasonable time to fix the issue before you disclose it publicly.

## Scope

In scope:

- forumulate.com and its API (`https://forumulate.com/api`)
- Customer sites served by Forumulate, including custom domains
- Our public packages: `@forumulate/sdk`, `@forumulate/cli`, `@forumulate/mcp`, the
  extension SDK and the official templates

Isolation between organizations is our top priority. Any way to read or change another
organization's data is the most serious kind of finding we can receive.

## Testing rules

- Use only accounts and organizations you own. Do not access, change or delete other
  people's data. If you reach someone else's data by accident, stop and tell us.
- No denial-of-service tests, spam, social engineering or physical attacks.
- Do not run automated scanners at volumes that degrade the service for other customers.

If you follow these rules in good faith, we will not pursue legal action over your research.
