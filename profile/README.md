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
The full map, with a quickstart per stack, is the [SDKs and integrations guide](https://forumulate.com/guides/sdks-and-integrations).

### Put Forumulate on any website

Comments, a docs search box, a changelog bell and content feeds, as plain HTML tags:

```html
<script type="module" src="https://cdn.jsdelivr.net/npm/@forumulate/embed@1"></script>
<forumulate-comments org="<org-id>" space="<space-id>"></forumulate-comments>
```

| Your stack | Package |
| --- | --- |
| Any site, no build step | [embed](https://github.com/forumulate/embed) · `@forumulate/embed` |
| React · Preact · Next.js · Remix | [react](https://github.com/forumulate/react) · [preact](https://github.com/forumulate/preact) · [next](https://github.com/forumulate/next) · [remix](https://github.com/forumulate/remix) |
| Vue · Nuxt | [vue](https://github.com/forumulate/vue) · [nuxt](https://github.com/forumulate/nuxt) |
| Svelte/SvelteKit · Solid · Qwik · Angular | [svelte](https://github.com/forumulate/svelte) · [solid](https://github.com/forumulate/solid) · [qwik](https://github.com/forumulate/qwik) · [angular](https://github.com/forumulate/angular) |
| Astro · Gatsby · Docusaurus · Eleventy | [astro](https://github.com/forumulate/astro) · [gatsby](https://github.com/forumulate/gatsby) · [docusaurus](https://github.com/forumulate/docusaurus) · [eleventy](https://github.com/forumulate/eleventy) |
| Django · Flask · Rails · Laravel | [django](https://github.com/forumulate/django) · [flask](https://github.com/forumulate/flask) · [rails](https://github.com/forumulate/rails) · [laravel](https://github.com/forumulate/laravel) |
| WordPress · Drupal · Ghost | [wordpress](https://github.com/forumulate/wordpress) · [drupal](https://github.com/forumulate/drupal) · [ghost](https://github.com/forumulate/ghost) |
| Hugo · Jekyll · Go templates | [hugo](https://github.com/forumulate/hugo) · [jekyll](https://github.com/forumulate/jekyll) · [forumulate-go-web](https://github.com/forumulate/forumulate-go-web) |

Every JavaScript package installs from npm (`npm i @forumulate/<name>`).

### Manage Forumulate from code

| Repository | What it is | Install |
| --- | --- | --- |
| [forumulate-js](https://github.com/forumulate/forumulate-js) | TypeScript/JavaScript SDK | `npm i @forumulate/sdk` |
| [forumulate-python](https://github.com/forumulate/forumulate-python) | Python SDK | `pip install git+https://github.com/forumulate/forumulate-python` |
| [forumulate-go](https://github.com/forumulate/forumulate-go) | Go SDK | `go get github.com/forumulate/forumulate-go` |
| [cli](https://github.com/forumulate/cli) | Forumulate from your terminal | `npm i -g @forumulate/cli` |
| [mcp](https://github.com/forumulate/mcp) | MCP server for Claude, Cursor and other agents | `npx -y @forumulate/mcp` |
| [extension-sdk](https://github.com/forumulate/extension-sdk) | Build extensions: signed requests, declarative UI | see the repo |
| [templates](https://github.com/forumulate/templates) | Official docs, forum, blog and changelog templates | see the repo |

[![npm @forumulate/embed](https://img.shields.io/npm/v/@forumulate/embed?label=%40forumulate%2Fembed)](https://www.npmjs.com/package/@forumulate/embed)
[![npm @forumulate/sdk](https://img.shields.io/npm/v/@forumulate/sdk?label=%40forumulate%2Fsdk)](https://www.npmjs.com/package/@forumulate/sdk)

## Links

- **Guides:** [forumulate.com/guides](https://forumulate.com/guides). Start with the [developer quickstart](https://forumulate.com/guides/developer-quickstart).
- **API reference:** [forumulate.com/reference](https://forumulate.com/reference)
- **Status:** [forumulate.com/status](https://forumulate.com/status)
- **Community:** [forumulate.com/community](https://forumulate.com/community)
- **Blog:** [forumulate.com/blog](https://forumulate.com/blog)
- **Security:** report vulnerabilities privately to [security@forumulate.com](mailto:security@forumulate.com). See our [security policy](https://github.com/forumulate/.github/blob/main/SECURITY.md).
