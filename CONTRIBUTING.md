# Contributing to Forumulate

Thanks for helping. This guide applies to every public repository in the
[forumulate](https://github.com/forumulate) organization unless a repository has its own
`CONTRIBUTING.md`.

## What is open, and what isn't

The **hosted product** (the application at [forumulate.com](https://forumulate.com)) is
not open source, and its code is not on GitHub. The **tooling around it** is public, and
issues and pull requests are welcome there:

- [forumulate-js](https://github.com/forumulate/forumulate-js): `@forumulate/sdk`
- [cli](https://github.com/forumulate/cli): `@forumulate/cli`
- [mcp](https://github.com/forumulate/mcp): `@forumulate/mcp`
- [extension-sdk](https://github.com/forumulate/extension-sdk)
- [templates](https://github.com/forumulate/templates)

## Where to report what

| You found... | Go to |
| --- | --- |
| A bug in the SDK, CLI, MCP server, extension SDK or a template | An issue in that repository |
| A bug in the hosted product (the console, a reader page, the API) | [forumulate.com/community](https://forumulate.com/community). You can also open an issue in the closest tooling repo and we will route it |
| A security vulnerability | **Not a public issue.** Follow [SECURITY.md](SECURITY.md) |
| A question about using Forumulate | [forumulate.com/community](https://forumulate.com/community), or see [SUPPORT.md](SUPPORT.md) |
| An outage | Check [forumulate.com/status](https://forumulate.com/status) first |

## Reporting a bug

A good report lets us reproduce it on the first try. Please include:

- The package and version (`npm ls @forumulate/sdk`, `forumulate --version`), plus your
  Node version and OS.
- What you ran, what you expected, and what happened. Paste the exact error.
- For API errors, the HTTP status, the response body and the request id if one was
  returned. `forumulate doctor` output helps too.
- A minimal reproduction if you can.

**Never paste an access token, password or private content.** Revoke any token that ends
up in an issue.

## Pull requests

1. For anything bigger than a small fix, open an issue first so we can agree on the shape
   before you spend time on it.
2. Fork, branch from `main`, and keep each PR to one change.
3. Follow the repository's existing style. Run its lint, typecheck and tests before you push.
4. Add or update tests for behaviour you change, and update the README or docs if usage
   changes.
5. Explain *why* in the PR description, not just what.

By submitting a pull request you agree that your contribution is licensed under the
license of the repository you are contributing to.

## Conduct

Everyone taking part is expected to follow our [Code of Conduct](CODE_OF_CONDUCT.md).
