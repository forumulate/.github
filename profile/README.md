# Forumulate

**Docs, forum and blog on one platform: one sign-in, one search, one permission model.**

Forumulate is a hosted alternative to running GitBook and Discourse side by side. You get
documentation with versioning and change requests, a community forum, and a blog, plus
roadmaps, changelogs, status pages, FAQs and more, as spaces in one organization. Readers
sign in once, search finds everything, and roles apply across all of it. We run it, so
there is nothing for you to deploy. Use our address or bring your own domain.

[Get started](https://forumulate.com/guides/getting-started) · [forumulate.com](https://forumulate.com)

## Build with Forumulate

Every operation is in a public OpenAPI document at `https://forumulate.com/api/openapi.json`.
These repositories are the tooling around it:

| Repository | What it is | Install |
| --- | --- | --- |
| [forumulate-js](https://github.com/forumulate/forumulate-js) | `@forumulate/sdk`, the typed JavaScript/TypeScript client | `npm i @forumulate/sdk` |
| [cli](https://github.com/forumulate/cli) | `@forumulate/cli`, Forumulate from your terminal, including `forumulate doctor` | `npm i -g @forumulate/cli` |
| [mcp](https://github.com/forumulate/mcp) | `@forumulate/mcp`, an MCP server for Claude and other agents | `npx -y @forumulate/mcp` |
| [extension-sdk](https://github.com/forumulate/extension-sdk) | Build extensions: verify signed requests, respond with declarative UI, call the API | see the repo |
| [templates](https://github.com/forumulate/templates) | The official space templates for docs, forums and blogs | see the repo |

[![npm @forumulate/sdk](https://img.shields.io/npm/v/@forumulate/sdk?label=%40forumulate%2Fsdk)](https://www.npmjs.com/package/@forumulate/sdk)
[![npm @forumulate/cli](https://img.shields.io/npm/v/@forumulate/cli?label=%40forumulate%2Fcli)](https://www.npmjs.com/package/@forumulate/cli)

## Links

- **Guides:** [forumulate.com/guides](https://forumulate.com/guides). Start with the [developer quickstart](https://forumulate.com/guides/developer-quickstart).
- **API reference:** [forumulate.com/reference](https://forumulate.com/reference)
- **Status:** [forumulate.com/status](https://forumulate.com/status)
- **Community:** [forumulate.com/community](https://forumulate.com/community)
- **Blog:** [forumulate.com/blog](https://forumulate.com/blog)
- **Security:** report vulnerabilities privately to [security@forumulate.com](mailto:security@forumulate.com). See our [security policy](https://github.com/forumulate/.github/blob/main/SECURITY.md).
