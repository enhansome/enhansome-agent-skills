<a href="https://github.com/VoltAgent/voltagent">
     <img width="1500" alt="claude-skills" src="https://github.com/user-attachments/assets/a890e563-e999-4b1f-8ce1-20399b0574f8" />
</a>

<br/>
<br/>

<div align="center">
    <strong>A collection of official Agent Skills from leading development teams and the community.
    <br />
    Hand-picked, not AI-slop generated.
    </strong>
    <br />
    <br />

</div>

<div align="center">

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![Skills Count](https://img.shields.io/badge/Skills-1497+-blue?style=flat-square)
![Last Update](https://img.shields.io/github/last-commit/VoltAgent/awesome-agent-skills?label=Last%20update\&style=flat-square)
[![Discord](https://img.shields.io/discord/1361559153780195478.svg?label=\&logo=discord\&logoColor=ffffff\&color=7389D8\&labelColor=6A7EC2)](https://s.voltagent.dev/discord)

</div>

</div>

# Awesome Agent Skills with stars

Unlike many bulk-generated skill repositories, this collection focuses on real-world Agent Skills created and used by actual engineering teams, not mass AI‑generated stuff.

Compatible with Claude Code, Codex, Antigravity, Gemini CLI, Cursor, GitHub Copilot, OpenCode, Windsurf, and more. See the table below for paths and documentation.

The most contributed Agent Skills repository, built and maintained together with the community.

## 💛 Sponsors

|                                                                                                                                                                                                                                                                                                                                                                                                                                            |                                                                                                                                                                                                                                                                                                                                                                                 |
| :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|                                                                         <a href="https://www.testmuai.com"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.voltagent.dev/awesome-repo/testmui/testmuai-white.png"><img alt="TestMu AI" src="https://cdn.voltagent.dev/awesome-repo/testmui/testmuai-black.png" width="425"></picture></a>                                                                        | [TestMu AI (formerly LambdaTest)](https://www.testmuai.com) is an AI-native testing cloud platform built for modern engineering teams. Covering everything from autonomous test creation and fast execution to testing AI agents, chatbots and voice assistants.                                                                                                                |
|                                                                <a href="https://modem.dev/go/awesome-agent-skills"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.voltagent.dev/awesome-repo/modemlabs/modemlabs-dark.svg"><img alt="Modem" src="https://cdn.voltagent.dev/awesome-repo/modemlabs/modemlab-light.svg" width="425"></picture></a>                                                                | [Modem](https://modem.dev/go/awesome-agent-skills) is an AI product teammate that takes scattered discussions and turns them into a company-specific context that surfaces insights, automates actions, and closes the loop with teammates and customers.                                                                                                                       |
| <a href="https://crawlbase.com/?utm_source=awesome-agent-skills&utm_medium=sponsorship&utm_campaign=voltagent_2026q3&utm_content=readme_listing"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.voltagent.dev/awesome-repo/crawlbase-new/crawlbase-logo-dark-mode.svg"><img alt="Crawlbase" src="https://cdn.voltagent.dev/awesome-repo/crawlbase-new/crawlbase-logo-light-mode.svg" width="425"></picture></a> | [Crawlbase](https://crawlbase.com/?utm_source=awesome-agent-skills\&utm_medium=sponsorship\&utm_campaign=voltagent_2026q3\&utm_content=readme_listing) is web data infrastructure trusted by 70,000+ developers. Its Crawling API, MCP server, and integrations give AI agents live access to any webpage — with JavaScript rendering, proxy rotation, and anti-bot protection. |
|                                                                                                                                        <a href="https://serpapi.com/awesome-agent-skills"><img alt="SerpApi" src="https://cdn.voltagent.dev/awesome-repo/serpapi/serpapi-logo.png" width="425"></a>                                                                                                                                        | [SerpApi](https://serpapi.com/awesome-agent-skills) is a Web Search API for your AI apps. Available in Markdown and JSON for any integration.                                                                                                                                                                                                                                   |

<br />

<a href="https://sponsors.voltagent.dev/#awesome-agent-skills"><img src="https://img.shields.io/badge/📩_Become_a_Sponsor-Contact_Us-blue?style=for-the-badge&logoColor=white" alt="Become a Sponsor" /></a>

## Table of Contents

### Official Skills by

|                                                          |                                                                 |                                                         |                                                                 |
| -------------------------------------------------------- | --------------------------------------------------------------- | ------------------------------------------------------- | --------------------------------------------------------------- |
| [Claude](#official-claude-skills)                        | [VoltAgent](#skills-by-voltagent)                               | [SerpApi](#skills-by-serpapi)                           | [Crawlbase](#skills-by-crawlbase)                               |
| [TestMu AI](#skills-by-testmu-ai)                        | [Modem Dev](#skills-by-modem-dev)                               | [Angular](#skills-by-angular)                           | [Composio](#skills-by-composio-team)                            |
| [Supabase](#skills-by-supabase-team)                     | [Google Gemini](#skills-by-google-gemini)                       | [Stripe](#skills-by-stripe-team)                        | [Courier](#skills-by-courier)                                   |
| [CallStack](#skills-by-callstack)                        | [Expo](#skills-by-expo-team)                                    | [Better Auth](#skills-by-better-auth-team)              | [Tinybird](#skills-by-tinybird-team)                            |
| [HashiCorp](#skills-by-hashicorp-team-for-terraform)     | [Sanity](#skills-by-sanity-team)                                | [Firecrawl](#skills-by-firecrawl-team)                  | [Neon](#skills-by-neon-team)                                    |
| [ClickHouse](#skill-by-clickhouse)                       | [Remotion](#skills-by-remotion)                                 | [Replicate](#skills-by-replicate)                       | [Typefully](#skills-by-typefully)                               |
| [Vercel](#skills-by-vercel-engineering-team)             | [Cloudflare](#skills-by-cloudflare-team)                        | [Netlify](#skills-by-netlify-team)                      | [Google Labs (Stitch)](#skills-by-google-labs-stitch)           |
| [Google Workspace CLI](#skills-by-google-workspace-cli)  | [Hugging Face](#skills-by-hugging-face-team)                    | [Trail of Bits](#security-skills-by-trail-of-bits-team) | [Sentry](#skills-by-sentry-team-for-their-dev-team)             |
| [Microsoft](#skills-by-microsoft)                        | [fal.ai](#skills-by-falai-team)                                 | [WordPress](#skills-by-wordpress-development-team)      | [OpenAI](#skills-by-openai)                                     |
| [Figma](#skills-by-figma)                                | [Corey Haines](#marketing-skills-by-corey-haines)               | [Binance](#skills-by-binance)                           | [Dean Peters](#product-manager-skills-by-dean-peters)           |
| [Paweł Huryn](#product-management-skills-by-pawel-huryn) | [MiniMax](#skills-by-minimax-team)                              | [DuckDB](#skills-by-duckdb)                             | [GSAP](#skills-by-gsap-greensock)                               |
| [Garry Tan (gstack)](#skills-by-garry-tan-gstack)        | [Notion](#skills-by-notion)                                     | [Resend](#skills-by-resend)                             | [Addy Osmani (Web Quality)](#skills-by-addy-osmani-web-quality) |
| [MongoDB](#skills-by-mongodb)                            | [Kim Barrett (Advertising)](#advertising-skills-by-kim-barrett) | [Apollo GraphQL](#skills-by-apollo-graphql)             | [Auth0](#skills-by-auth0)                                       |
| [Brave](#skills-by-brave)                                | [Browserbase](#skills-by-browserbase)                           | [CodeRabbit](#skills-by-coderabbit)                     | [Coinbase](#skills-by-coinbase)                                 |
| [Datadog Labs](#skills-by-datadog-labs)                  | [Firebase](#skills-by-firebase)                                 | [Flutter](#skills-by-flutter)                           | [Venice.ai](#skills-by-veniceai)                                |
| [Red Hat](#skills-by-redhat)                             | [Community](#community-skills)                                  | [Redis](#skills-by-redis)                               | [NVIDIA](#skills-by-nvidia)                                     |
| [Google Cloud](#skills-by-google-cloud)                  | [Quality Standards](#skill-quality-standards)                   |                                                         |                                                                 |

<br/>

You ship products with AI, but every launch still dies quietly because nobody posts about it. [EveryFeed](https://everyfeed.ai/) plugs your AI assistant into a social workspace that drafts, schedules, and publishes across 35+ channels — no agency, no marketing hire.

<a href="https://everyfeed.ai/">
<img src="https://cdn.voltagent.dev/awesome-repo/everyfeed-social.png" alt="everyfeed"  /><br/>
</a>

<br/>
<br/>

Stop building from a blank page. [LaunchKit](https://launchkit.getdesign.md/) gives your AI coding assistant a complete, working product to start from — websites, startups, and web apps that are clickable on day one.

<a href="https://launchkit.getdesign.md/">
<img src="https://cdn.voltagent.dev/awesome-repo/new-launchkit.png" alt="launchkit"  /><br/>
</a>

<br/>

<details open>
<summary><h3 style="display:inline">Official Claude Skills</h3></summary>

* **[anthropics/docx](https://officialskills.sh/anthropics/skills/docx)** - Create, edit, and analyze Word documents
* **[anthropics/doc-coauthoring](https://officialskills.sh/anthropics/skills/doc-coauthoring)** - Collaborative document editing and co-authoring
* **[anthropics/pptx](https://officialskills.sh/anthropics/skills/pptx)** - Create, edit, and analyze PowerPoint presentations
* **[anthropics/xlsx](https://officialskills.sh/anthropics/skills/xlsx)** - Create, edit, and analyze Excel spreadsheets
* **[anthropics/pdf](https://officialskills.sh/anthropics/skills/pdf)** - Extract text, create PDFs, and handle forms
* **[anthropics/algorithmic-art](https://officialskills.sh/anthropics/skills/algorithmic-art)** - Create generative art using p5.js with seeded randomness
* **[anthropics/canvas-design](https://officialskills.sh/anthropics/skills/canvas-design)** - Design visual art in PNG and PDF formats
* **[anthropics/frontend-design](https://officialskills.sh/anthropics/skills/frontend-design)** - Frontend design and UI/UX development tools
* **[anthropics/slack-gif-creator](https://officialskills.sh/anthropics/skills/slack-gif-creator)** - Create animated GIFs optimized for Slack size constraints
* **[anthropics/theme-factory](https://officialskills.sh/anthropics/skills/theme-factory)** - Style artifacts with professional themes or generate custom themes
* **[anthropics/web-artifacts-builder](https://officialskills.sh/anthropics/skills/web-artifacts-builder)** - Build complex claude.ai HTML artifacts with React and Tailwind
* **[anthropics/mcp-builder](https://officialskills.sh/anthropics/skills/mcp-builder)** - Create MCP servers to integrate external APIs and services
* **[anthropics/webapp-testing](https://officialskills.sh/anthropics/skills/webapp-testing)** - Test local web applications using Playwright
* **[anthropics/brand-guidelines](https://officialskills.sh/anthropics/skills/brand-guidelines)** - Apply Anthropic's brand colors and typography to artifacts
* **[anthropics/internal-comms](https://officialskills.sh/anthropics/skills/internal-comms)** - Write status reports, newsletters, and FAQs
* **[anthropics/skill-creator](https://officialskills.sh/anthropics/skills/skill-creator)** - Guide for creating skills that extend Claude's capabilities
* **[anthropics/template](https://officialskills.sh/anthropics/skills/template)** - Basic template for creating new skills

</details>

<details>
<summary><h3 style="display:inline">Skills by VoltAgent</h3></summary>

Official skills by VoltAgent for building AI agents with the VoltAgent TypeScript framework.

* **[voltagent/create-voltagent](https://officialskills.sh/voltagent/skills/create-voltagent)** - Project setup guide with CLI and manual steps
* **[voltagent/voltagent-best-practices](https://officialskills.sh/voltagent/skills/voltagent-best-practices)** - Architecture and usage patterns for agents, workflows, memory, and servers
* **[voltagent/voltagent-core-reference](https://officialskills.sh/voltagent/skills/voltagent-core-reference)** - Reference for the VoltAgent class options and lifecycle methods
* **[voltagent/voltagent-docs-bundle](https://officialskills.sh/voltagent/skills/voltagent-docs-bundle)** - Lookup embedded docs from @voltagent/core for version-matched documentation

</details>

<details>
<summary><h3 style="display:inline">Skills by SerpApi</h3></summary>

Official skills by the [SerpApi](https://serpapi.com/awesome-agent-skills) team — the Web Search API for AI apps. They give agents structured, machine-readable search data through 130+ engines, from Google web and Scholar to Maps, Flights, Hotels, and Shopping.

* **[serpapi/serpapi-web-search](https://officialskills.sh/serpapi/skills/serpapi-web-search)** - Structured search data via 130+ engines: pick the right engine, extract the right keys, recover from errors
* **[serpapi/agent-usability-test](https://officialskills.sh/serpapi/skills/agent-usability-test)** - Test whether agents can discover and use your tool — the subject under test is the interface, not the agent

More from SerpApi (not skills, but they pair with them):

* **[serpapi/serpapi-cli](https://github.com/serpapi/serpapi-cli) ⭐ 13 | 🐛 6 | 🌐 Go | 📅 2026-09-03** - SerpApi client for the command line, covering all 130+ engines
* **[serpapi/serpapi-search-tools-python](https://github.com/serpapi/serpapi-search-tools-python) ⭐ 11 | 🐛 2 | 🌐 Python | 📅 2026-09-18** - Real-time search tools for Python agents with native support for popular agent SDKs

</details>

<details>
<summary><h3 style="display:inline">Skills by Crawlbase</h3></summary>

Official skills by the [Crawlbase](https://crawlbase.com/?utm_source=awesome-agent-skills\&utm_medium=sponsorship\&utm_campaign=voltagent_2026q3\&utm_content=readme_listing) team that give AI agents live web access through the Crawlbase MCP server: crawl any URL as raw HTML, clean Markdown, or a screenshot, and manage results in Crawlbase Cloud Storage.

* **[crawlbase/crawl-html](https://officialskills.sh/crawlbase/skills/crawl-html)** - Crawl a URL and return its raw HTML with JS rendering, device emulation, and geo-targeting
* **[crawlbase/crawl-markdown](https://officialskills.sh/crawlbase/skills/crawl-markdown)** - Extract clean, LLM-ready Markdown from any URL, stripped of ads and boilerplate
* **[crawlbase/crawl-screenshot](https://officialskills.sh/crawlbase/skills/crawl-screenshot)** - Take full-page or viewport screenshots of any URL on desktop or mobile
* **[crawlbase/storage-get](https://officialskills.sh/crawlbase/skills/storage-get)** - Retrieve a stored page from Crawlbase Cloud Storage as JSON, HTML, or Markdown
* **[crawlbase/storage-list](https://officialskills.sh/crawlbase/skills/storage-list)** - List stored rids with scroll-based pagination, up to 1000 per call
* **[crawlbase/storage-bulk-get](https://officialskills.sh/crawlbase/skills/storage-bulk-get)** - Retrieve up to 100 stored pages in one call, with optional auto-delete
* **[crawlbase/storage-count](https://officialskills.sh/crawlbase/skills/storage-count)** - Count the documents held in Crawlbase Cloud Storage for a token
* **[crawlbase/storage-delete](https://officialskills.sh/crawlbase/skills/storage-delete)** - Delete a single stored page from Crawlbase Cloud Storage by rid
* **[crawlbase/storage-bulk-delete](https://officialskills.sh/crawlbase/skills/storage-bulk-delete)** - Delete up to 100 stored pages from Crawlbase Cloud Storage in one call

More from Crawlbase (not skills, but they pair with them):

* **[crawlbase/crawlbase-mcp](https://github.com/crawlbase/crawlbase-mcp) ⭐ 58 | 🐛 0 | 🌐 JavaScript | 📅 2026-04-23** - The MCP server behind these skills (npm `@crawlbase/mcp`) with JS rendering, proxy rotation, and anti-bot protection
* **[crawlbase/langchain-crawlbase](https://github.com/crawlbase/langchain-crawlbase) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-05-02** - LangChain document loader, tool, and retriever backed by the Crawling API
* **[crawlbase/n8n-nodes-crawlbase](https://github.com/crawlbase/n8n-nodes-crawlbase) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-13** - Native Crawlbase node for n8n with credentials and Crawling API options

</details>

<details>
<summary><h3 style="display:inline">Skills by TestMu AI</h3></summary>

Production-grade Agent Skills for every major test automation framework, maintained by the TestMu AI (formerly LambdaTest) team. They help AI coding assistants generate expert-level test automation code across web, mobile, API, BDD, and unit testing stacks.

* **[testmu-ai/api-skill](https://github.com/LambdaTest/agent-skills/tree/main/api-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Suite of API skills for designing, mocking, documenting, securing, and generating tests for REST/GraphQL/gRPC APIs
* **[testmu-ai/appium-skill](https://github.com/LambdaTest/agent-skills/tree/main/appium-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Appium mobile automation for Android and iOS in Java, Python, or JS
* **[testmu-ai/behat-skill](https://github.com/LambdaTest/agent-skills/tree/main/behat-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Behat BDD tests for PHP with Gherkin and Mink
* **[testmu-ai/behave-skill](https://github.com/LambdaTest/agent-skills/tree/main/behave-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Behave BDD tests for Python with Gherkin and step implementations
* **[testmu-ai/capybara-skill](https://github.com/LambdaTest/agent-skills/tree/main/capybara-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Capybara E2E tests in Ruby with RSpec integration
* **[testmu-ai/cicd-pipeline-skill](https://github.com/LambdaTest/agent-skills/tree/main/cicd-pipeline-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate CI/CD pipelines for tests on GitHub Actions, Jenkins, GitLab CI, and Azure DevOps
* **[testmu-ai/codeception-skill](https://github.com/LambdaTest/agent-skills/tree/main/codeception-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Codeception acceptance, functional, and unit tests in PHP
* **[testmu-ai/cucumber-skill](https://github.com/LambdaTest/agent-skills/tree/main/cucumber-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Cucumber BDD tests with Gherkin and step definitions in Java, JS, or Ruby
* **[testmu-ai/cypress-skill](https://github.com/LambdaTest/agent-skills/tree/main/cypress-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Cypress E2E and component tests in JavaScript or TypeScript
* **[testmu-ai/detox-skill](https://github.com/LambdaTest/agent-skills/tree/main/detox-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Detox gray-box E2E tests for React Native apps in JavaScript
* **[testmu-ai/espresso-skill](https://github.com/LambdaTest/agent-skills/tree/main/espresso-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Espresso UI tests for Android apps in Kotlin or Java
* **[testmu-ai/flutter-testing-skill](https://github.com/LambdaTest/agent-skills/tree/main/flutter-testing-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Flutter widget, integration, and golden tests in Dart
* **[testmu-ai/gauge-skill](https://github.com/LambdaTest/agent-skills/tree/main/gauge-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Gauge specs in Markdown with steps in Java, Python, JS, or Ruby
* **[testmu-ai/geb-skill](https://github.com/LambdaTest/agent-skills/tree/main/geb-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Geb browser automation in Groovy with Spock and page objects
* **[testmu-ai/hyperexecute-skill](https://github.com/LambdaTest/agent-skills/tree/main/hyperexecute-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Operate TestMu AI HyperExecute end-to-end: YAML, CLI runs, debugging, and CI wiring
* **[testmu-ai/jasmine-skill](https://github.com/LambdaTest/agent-skills/tree/main/jasmine-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Jasmine BDD tests in JavaScript with spies and async support
* **[testmu-ai/jest-skill](https://github.com/LambdaTest/agent-skills/tree/main/jest-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Jest unit and integration tests in JS/TS with mocking and snapshots
* **[testmu-ai/junit-5-skill](https://github.com/LambdaTest/agent-skills/tree/main/junit-5-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate JUnit 5 unit and integration tests in Java with Mockito
* **[testmu-ai/karma-skill](https://github.com/LambdaTest/agent-skills/tree/main/karma-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Karma test-runner configs for browser-based JS testing
* **[testmu-ai/laravel-dusk-skill](https://github.com/LambdaTest/agent-skills/tree/main/laravel-dusk-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Laravel Dusk Chrome-based browser tests in PHP
* **[testmu-ai/lettuce-skill](https://github.com/LambdaTest/agent-skills/tree/main/lettuce-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Lettuce BDD tests for Python (legacy; prefer Behave)
* **[testmu-ai/mocha-skill](https://github.com/LambdaTest/agent-skills/tree/main/mocha-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Mocha tests in JavaScript with Chai and Sinon
* **[testmu-ai/mstest-skill](https://github.com/LambdaTest/agent-skills/tree/main/mstest-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate MSTest tests in C# for .NET
* **[testmu-ai/nemojs-skill](https://github.com/LambdaTest/agent-skills/tree/main/nemojs-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Nemo.js Selenium-based tests for Node.js
* **[testmu-ai/nightwatchjs-skill](https://github.com/LambdaTest/agent-skills/tree/main/nightwatchjs-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate NightwatchJS E2E tests in JavaScript with Selenium WebDriver
* **[testmu-ai/nunit-skill](https://github.com/LambdaTest/agent-skills/tree/main/nunit-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate NUnit 3 tests in C# with the constraint model and Moq
* **[testmu-ai/phpunit-skill](https://github.com/LambdaTest/agent-skills/tree/main/phpunit-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate PHPUnit tests in PHP with data providers and mocking
* **[testmu-ai/playwright-skill](https://github.com/LambdaTest/agent-skills/tree/main/playwright-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Playwright E2E tests in TS, JS, Python, Java, or C#
* **[testmu-ai/protractor-skill](https://github.com/LambdaTest/agent-skills/tree/main/protractor-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Protractor E2E tests for Angular in JS/TS (deprecated; prefer Playwright/Cypress)
* **[testmu-ai/puppeteer-skill](https://github.com/LambdaTest/agent-skills/tree/main/puppeteer-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Puppeteer scripts for browser automation, scraping, and PDF generation
* **[testmu-ai/pytest-skill](https://github.com/LambdaTest/agent-skills/tree/main/pytest-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate pytest tests in Python with fixtures, parametrize, and mocking
* **[testmu-ai/reqnroll-skill](https://github.com/LambdaTest/agent-skills/tree/main/reqnroll-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Reqnroll BDD tests for web and mobile in C#
* **[testmu-ai/robot-framework-skill](https://github.com/LambdaTest/agent-skills/tree/main/robot-framework-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Robot Framework keyword-driven tests in Python
* **[testmu-ai/rspec-skill](https://github.com/LambdaTest/agent-skills/tree/main/rspec-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate RSpec tests in Ruby with matchers, hooks, and mocking
* **[testmu-ai/selenide-skill](https://github.com/LambdaTest/agent-skills/tree/main/selenide-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Selenide UI tests in Java with auto-waits and a fluent API
* **[testmu-ai/selenium-skill](https://github.com/LambdaTest/agent-skills/tree/main/selenium-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Selenium WebDriver tests in Java, Python, JS, C#, Ruby, or PHP
* **[testmu-ai/serenity-bdd-skill](https://github.com/LambdaTest/agent-skills/tree/main/serenity-bdd-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Serenity BDD tests in Java with the Screenplay pattern and reporting
* **[testmu-ai/smartui-skill](https://github.com/LambdaTest/agent-skills/tree/main/smartui-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate SmartUI visual regression configs for screenshot comparison
* **[testmu-ai/specflow-skill](https://github.com/LambdaTest/agent-skills/tree/main/specflow-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate SpecFlow BDD tests for C#/.NET with Gherkin and step bindings
* **[testmu-ai/test-framework-migration-skill](https://github.com/LambdaTest/agent-skills/tree/main/test-framework-migration-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Migrate tests between Selenium, Playwright, Puppeteer, and Cypress
* **[testmu-ai/testcafe-skill](https://github.com/LambdaTest/agent-skills/tree/main/testcafe-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate TestCafe automation tests in JavaScript or TypeScript
* **[testmu-ai/testng-skill](https://github.com/LambdaTest/agent-skills/tree/main/testng-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate TestNG tests in Java with data providers and parallel execution
* **[testmu-ai/testunit-skill](https://github.com/LambdaTest/agent-skills/tree/main/testunit-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Test::Unit xUnit-style tests in Ruby
* **[testmu-ai/unittest-skill](https://github.com/LambdaTest/agent-skills/tree/main/unittest-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Python unittest tests with TestCase and setUp/tearDown
* **[testmu-ai/vitest-skill](https://github.com/LambdaTest/agent-skills/tree/main/vitest-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate Vitest tests in JS/TS with a Jest-compatible API and ESM
* **[testmu-ai/webdriverio-skill](https://github.com/LambdaTest/agent-skills/tree/main/webdriverio-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate WebdriverIO (WDIO) automation tests in JavaScript or TypeScript
* **[testmu-ai/xcuitest-skill](https://github.com/LambdaTest/agent-skills/tree/main/xcuitest-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate XCUITest UI tests for iOS/iPadOS apps in Swift
* **[testmu-ai/xunit-skill](https://github.com/LambdaTest/agent-skills/tree/main/xunit-skill) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - Generate xUnit.net tests in C# with Fact/Theory and FluentAssertions

</details>

<details>
<summary><h3 style="display:inline">Skills by Modem Dev</h3></summary>

* **[modem-dev/skills](https://github.com/modem-dev/skills) ⭐ 54 | 🐛 1 | 📅 2026-08-19** - Agent skills from [Modem](https://modem.dev/go/awesome-agent-skills), starting with write-discoverable-code

</details>

<details>
<summary><h3 style="display:inline">Skills by Zero</h3></summary>

* **[zero/zero](https://github.com/officialzeroxyz/zero-plugins/blob/main/plugins/zero/skills/zero/SKILL.md) ⭐ 20 | 🐛 1 | 🌐 Shell | 📅 2026-09-08** - Discover and call external paid tools for Claude Code agents instead of stopping to ask the user to sign up or fetch an API key
* **[zero/zero-gemini](https://github.com/officialzeroxyz/zero-plugins/tree/main/plugins/zero-gemini) ⭐ 20 | 🐛 1 | 🌐 Shell | 📅 2026-09-08** - Same Zero tool-discovery and payment layer packaged as a Gemini CLI extension

</details>

<details>
<summary><h3 style="display:inline">Skills by Angular</h3></summary>

* **[angular/angular-developer](https://github.com/angular/skills) ⭐ 651 | 🐛 0 | 📅 2026-09-17** - Generate Angular code and architectural guidance for components, services, reactivity
* **[angular/angular-new-app](https://github.com/angular/skills) ⭐ 651 | 🐛 0 | 📅 2026-09-17** - Create new Angular apps using CLI with modern best practices

</details>

<details>
<summary><h3 style="display:inline">Skills by Composio Team</h3></summary>

* **[composiohq/composio](https://officialskills.sh/composiohq/skills/composio)** - Connect AI agents to 1000+ external apps with managed authentication

</details>

<details>
<summary><h3 style="display:inline">Skills by Supabase Team</h3></summary>

* **[supabase/postgres-best-practices](https://officialskills.sh/supabase/skills/postgres-best-practices)** - PostgreSQL best practices for Supabase

</details>

<details>
<summary><h3 style="display:inline">Skills by Google Gemini</h3></summary>

* **[google-gemini/gemini-api-dev](https://officialskills.sh/google-gemini/skills/gemini-api-dev)** - Best practices for developing Gemini-powered apps using the Gemini API
* **[google-gemini/vertex-ai-api-dev](https://officialskills.sh/google-gemini/skills/vertex-ai-api-dev)** - Developing Gemini-powered apps on Google Cloud Vertex AI using the Gen AI SDK
* **[google-gemini/gemini-live-api-dev](https://officialskills.sh/google-gemini/skills/gemini-live-api-dev)** - Building real-time bidirectional streaming apps with the Gemini Live API
* **[google-gemini/gemini-interactions-api](https://officialskills.sh/google-gemini/skills/gemini-interactions-api)** - Building apps with the Gemini Interactions API for text, chat, streaming, and image generation

</details>

<details>
<summary><h3 style="display:inline">Skills by Stripe Team</h3></summary>

* **[stripe/stripe-best-practices](https://officialskills.sh/stripe/skills/stripe-best-practices)** - Best practices for building Stripe integrations
* **[stripe/upgrade-stripe](https://officialskills.sh/stripe/skills/upgrade-stripe)** - Upgrade Stripe SDK and API versions

</details>

<details>
<summary><h3 style="display:inline">Skills by Courier</h3></summary>

* **[trycourier/courier-skills](https://github.com/trycourier/courier-skills) ⭐ 13 | 🐛 1 | 📅 2026-09-11** - Multi-channel notifications via email, SMS, push, and chat

</details>

<details>
<summary><h3 style="display:inline">Skills by CallStack</h3></summary>

* **[callstackincubator/react-native-best-practices](https://officialskills.sh/callstackincubator/skills/react-native-best-practices)** - Performance optimization for React Native apps from Callstack
* **[callstackincubator/github](https://officialskills.sh/callstackincubator/skills/github)** - GitHub workflow patterns for PRs, code review, branching
* **[callstackincubator/upgrading-react-native](https://officialskills.sh/callstackincubator/skills/upgrading-react-native)** - React Native upgrade workflow: templates, dependencies, and common pitfalls

</details>

<details>
<summary><h3 style="display:inline">Skills by Better Auth Team</h3></summary>

* **[better-auth/best-practices](https://officialskills.sh/better-auth/skills/best-practices)** - Best practices for Better Auth integration
* **[better-auth/explain-error](https://officialskills.sh/better-auth/skills/explain-error)** - Explain Better Auth error messages
* **[better-auth/providers](https://officialskills.sh/better-auth/skills/providers)** - Better Auth authentication providers
* **[better-auth/create-auth](https://officialskills.sh/better-auth/skills/create-auth)** - Create authentication setup with Better Auth
* **[better-auth/emailAndPassword](https://officialskills.sh/better-auth/skills/emailAndPassword)** - Email and password authentication with Better Auth
* **[better-auth/organization](https://officialskills.sh/better-auth/skills/organization)** - Organization management with Better Auth
* **[better-auth/twoFactor](https://officialskills.sh/better-auth/skills/twoFactor)** - Two-factor authentication with Better Auth

</details>

<details>
<summary><h3 style="display:inline">Skills by Tinybird Team</h3></summary>

* **[tinybirdco/tinybird-best-practices](https://officialskills.sh/tinybirdco/skills/tinybird-best-practices)** - Tinybird project guidelines for datasources, pipes, endpoints, and SQL
* **[tinybirdco/tinybird-cli-guidelines](https://officialskills.sh/tinybirdco/skills/tinybird-cli-guidelines)** - Tinybird CLI usage guidelines and commands
* **[tinybirdco/tinybird-python-sdk-guidelines](https://officialskills.sh/tinybirdco/skills/tinybird-python-sdk-guidelines)** - Tinybird Python SDK usage guidelines
* **[tinybirdco/tinybird-typescript-sdk-guidelines](https://officialskills.sh/tinybirdco/skills/tinybird-typescript-sdk-guidelines)** - Tinybird TypeScript SDK usage guidelines

</details>

<details>
<summary><h3 style="display:inline">Skills by HashiCorp Team for Terraform</h3></summary>

* **[hashicorp/azure-verified-modules](https://officialskills.sh/hashicorp/skills/azure-verified-modules)** - Azure Verified Modules (AVM) certification standards for Terraform modules
* **[hashicorp/new-terraform-provider](https://officialskills.sh/hashicorp/skills/new-terraform-provider)** - Scaffold a new Terraform provider project using the Plugin Framework
* **[hashicorp/provider-resources](https://officialskills.sh/hashicorp/skills/provider-resources)** - Implement Terraform Provider resources and data sources using the Plugin Framework
* **[hashicorp/provider-test-patterns](https://officialskills.sh/hashicorp/skills/provider-test-patterns)** - Acceptance test patterns for Terraform providers using terraform-plugin-testing
* **[hashicorp/provider-actions](https://officialskills.sh/hashicorp/skills/provider-actions)** - Implement Terraform Provider Actions using the Plugin Framework
* **[hashicorp/run-acceptance-tests](https://officialskills.sh/hashicorp/skills/run-acceptance-tests)** - Run acceptance tests for Terraform providers using Go's test runner
* **[hashicorp/refactor-module](https://officialskills.sh/hashicorp/skills/refactor-module)** - Transform monolithic Terraform configurations into reusable modules
* **[hashicorp/terraform-search-import](https://officialskills.sh/hashicorp/skills/terraform-search-import)** - Discover existing cloud resources and bulk import them into Terraform state
* **[hashicorp/terraform-style-guide](https://officialskills.sh/hashicorp/skills/terraform-style-guide)** - Generate Terraform HCL code following HashiCorp's official style conventions
* **[hashicorp/terraform-stacks](https://officialskills.sh/hashicorp/skills/terraform-stacks)** - Manage infrastructure across multiple environments, regions, and cloud accounts
* **[hashicorp/terraform-test](https://officialskills.sh/hashicorp/skills/terraform-test)** - Built-in testing framework for Terraform configurations with .tftest.hcl files

</details>

<details>
<summary><h3 style="display:inline">Skills by Sanity Team</h3></summary>

* **[sanity-io/sanity-best-practices](https://officialskills.sh/sanity-io/skills/sanity-best-practices)** - Best practices for Sanity Studio, GROQ queries, and content workflows
* **[sanity-io/content-modeling-best-practices](https://officialskills.sh/sanity-io/skills/content-modeling-best-practices)** - Guidelines for designing scalable content models in Sanity
* **[sanity-io/seo-aeo-best-practices](https://officialskills.sh/sanity-io/skills/seo-aeo-best-practices)** - SEO and answer engine optimization patterns for content sites
* **[sanity-io/content-experimentation-best-practices](https://officialskills.sh/sanity-io/skills/content-experimentation-best-practices)** - Content A/B testing and experimentation workflows

</details>

<details>
<summary><h3 style="display:inline">Skills by Firecrawl Team</h3></summary>

* **[firecrawl/firecrawl-build](https://officialskills.sh/firecrawl/skills/firecrawl-build)** - Integrate Firecrawl into application code for web search, scraping, extraction, and browser interaction
* **[firecrawl/firecrawl-build-interact](https://officialskills.sh/firecrawl/skills/firecrawl-build-interact)** - Multi-step Firecrawl browser flows: clicks, form fills, pagination, and auth-aware navigation
* **[firecrawl/firecrawl-build-onboarding](https://officialskills.sh/firecrawl/skills/firecrawl-build-onboarding)** - Set up Firecrawl credentials and SDK in a project for the first integration
* **[firecrawl/firecrawl-build-scrape](https://officialskills.sh/firecrawl/skills/firecrawl-build-scrape)** - Integrate Firecrawl `/scrape` for single-page extraction from product code
* **[firecrawl/firecrawl-build-search](https://officialskills.sh/firecrawl/skills/firecrawl-build-search)** - Integrate Firecrawl `/search` for query-first discovery with optional content hydration

</details>

<details>
<summary><h3 style="display:inline">Skills by Neon</h3></summary>

* **[neondatabase/neon-postgres](https://officialskills.sh/neondatabase/skills/neon-postgres)** - Best practices for Neon Serverless Postgres
* **[neondatabase/claimable-postgres](https://officialskills.sh/neondatabase/skills/claimable-postgres)** - Claimable Postgres database provisioning with Neon
* **[neondatabase/neon-postgres-egress-optimizer](https://officialskills.sh/neondatabase/skills/neon-postgres-egress-optimizer)** - Optimize Neon Postgres egress and data transfer

</details>

<details>
<summary><h3 style="display:inline">Skills by ClickHouse</h3></summary>

* **[clickhouse/clickhouse-best-practices](https://officialskills.sh/clickhouse/skills/clickhouse-best-practices)** - Best practices for working with ClickHouse
* **[clickhouse/chdb-datastore](https://officialskills.sh/clickhouse/skills/chdb-datastore)** - Drop-in pandas replacement with ClickHouse performance across 16+ data sources
* **[clickhouse/chdb-sql](https://officialskills.sh/clickhouse/skills/chdb-sql)** - In-process ClickHouse SQL engine for Python — query files, databases, and cloud storage without a server
* **[clickhouse/clickhouse-architecture-advisor](https://officialskills.sh/clickhouse/skills/clickhouse-architecture-advisor)** - Design ClickHouse architectures and translate best practices into workload-specific decisions
* **[clickhouse/clickhousectl-cloud-deploy](https://officialskills.sh/clickhouse/skills/clickhousectl-cloud-deploy)** - Deploy to ClickHouse Cloud and migrate from local setups with clickhousectl
* **[clickhouse/clickhousectl-local-dev](https://officialskills.sh/clickhouse/skills/clickhousectl-local-dev)** - Spin up a local ClickHouse development environment from zero with clickhousectl

</details>

<details>
<summary><h3 style="display:inline">Skills by Remotion</h3></summary>

* **[remotion-dev/remotion](https://officialskills.sh/remotion-dev/skills/remotion)** - Programmatic video creation with React

</details>

<details>
<summary><h3 style="display:inline">Skills by Replicate</h3></summary>

* **[replicate/replicate](https://officialskills.sh/replicate/skills/replicate)** - Discover, compare, and run AI models using Replicate's API

</details>

<details>
<summary><h3 style="display:inline">Skills by Typefully</h3></summary>

* **[typefully/typefully](https://officialskills.sh/typefully/skills/typefully)** - Create, schedule, and publish social media content across X, LinkedIn, Threads, Bluesky, and Mastodon

</details>

<details>
<summary><h3 style="display:inline">Skills by Venice.ai</h3></summary>

Official skills by Venice.ai for the Venice API.

* **[veniceai/venice-api-overview](https://github.com/veniceai/skills/tree/main/skills/venice-api-overview) ⭐ 141 | 🐛 11 | 🌐 Python | 📅 2026-09-14** - API basics, auth modes, pricing, and versioning
* **[veniceai/venice-auth](https://github.com/veniceai/skills/tree/main/skills/venice-auth) ⭐ 141 | 🐛 11 | 🌐 Python | 📅 2026-09-14** - API keys and wallet-based Venice authentication
* **[veniceai/venice-chat](https://github.com/veniceai/skills/tree/main/skills/venice-chat) ⭐ 141 | 🐛 11 | 🌐 Python | 📅 2026-09-14** - Chat completions, multimodal inputs, tools, and streaming
* **[veniceai/venice-responses](https://github.com/veniceai/skills/tree/main/skills/venice-responses) ⭐ 141 | 🐛 11 | 🌐 Python | 📅 2026-09-14** - OpenAI-compatible Responses API for Venice
* **[veniceai/venice-embeddings](https://github.com/veniceai/skills/tree/main/skills/venice-embeddings) ⭐ 141 | 🐛 11 | 🌐 Python | 📅 2026-09-14** - Embeddings models, dimensions, and encoding formats
* **[veniceai/venice-image-generate](https://github.com/veniceai/skills/tree/main/skills/venice-image-generate) ⭐ 141 | 🐛 11 | 🌐 Python | 📅 2026-09-14** - Image generation endpoints and available styles
* **[veniceai/venice-image-edit](https://github.com/veniceai/skills/tree/main/skills/venice-image-edit) ⭐ 141 | 🐛 11 | 🌐 Python | 📅 2026-09-14** - Image edits, upscaling, and background removal
* **[veniceai/venice-audio-speech](https://github.com/veniceai/skills/tree/main/skills/venice-audio-speech) ⭐ 141 | 🐛 11 | 🌐 Python | 📅 2026-09-14** - Text-to-speech models, voices, formats, and streaming
* **[veniceai/venice-audio-music](https://github.com/veniceai/skills/tree/main/skills/venice-audio-music) ⭐ 141 | 🐛 11 | 🌐 Python | 📅 2026-09-14** - Music generation queueing, retrieval, and completion endpoints
* **[veniceai/venice-audio-transcription](https://github.com/veniceai/skills/tree/main/skills/venice-audio-transcription) ⭐ 141 | 🐛 11 | 🌐 Python | 📅 2026-09-14** - Audio transcription models and speech-to-text options
* **[veniceai/venice-video](https://github.com/veniceai/skills/tree/main/skills/venice-video) ⭐ 141 | 🐛 11 | 🌐 Python | 📅 2026-09-14** - Video generation and transcription workflows
* **[veniceai/venice-models](https://github.com/veniceai/skills/tree/main/skills/venice-models) ⭐ 141 | 🐛 11 | 🌐 Python | 📅 2026-09-14** - Model catalog, traits, and compatibility mappings
* **[veniceai/venice-characters](https://github.com/veniceai/skills/tree/main/skills/venice-characters) ⭐ 141 | 🐛 11 | 🌐 Python | 📅 2026-09-14** - Character endpoints and `character_slug` usage
* **[veniceai/venice-api-keys](https://github.com/veniceai/skills/tree/main/skills/venice-api-keys) ⭐ 141 | 🐛 11 | 🌐 Python | 📅 2026-09-14** - API key CRUD, rate limits, and Web3 keys
* **[veniceai/venice-billing](https://github.com/veniceai/skills/tree/main/skills/venice-billing) ⭐ 141 | 🐛 11 | 🌐 Python | 📅 2026-09-14** - Balance, usage, and billing analytics endpoints
* **[veniceai/venice-x402](https://github.com/veniceai/skills/tree/main/skills/venice-x402) ⭐ 141 | 🐛 11 | 🌐 Python | 📅 2026-09-14** - Wallet credits and x402 payments on Base
* **[veniceai/venice-crypto-rpc](https://github.com/veniceai/skills/tree/main/skills/venice-crypto-rpc) ⭐ 141 | 🐛 11 | 🌐 Python | 📅 2026-09-14** - JSON-RPC proxying for supported crypto networks
* **[veniceai/venice-augment](https://github.com/veniceai/skills/tree/main/skills/venice-augment) ⭐ 141 | 🐛 11 | 🌐 Python | 📅 2026-09-14** - Search, scraping, and text parsing endpoints
* **[veniceai/venice-errors](https://github.com/veniceai/skills/tree/main/skills/venice-errors) ⭐ 141 | 🐛 11 | 🌐 Python | 📅 2026-09-14** - Error handling, retries, and API status codes

</details>

<details>
<summary><h3 style="display:inline">Skills by Vercel Engineering Team</h3></summary>

* **[vercel-labs/next-best-practices](https://officialskills.sh/vercel-labs/skills/next-best-practices)** - Next.js best practices and recommended patterns
* **[vercel-labs/next-cache-components](https://officialskills.sh/vercel-labs/skills/next-cache-components)** - Caching strategies and cache-aware components in Next.js
* **[vercel-labs/next-upgrade](https://officialskills.sh/vercel-labs/skills/next-upgrade)** - Upgrade Next.js projects to newer versions

</details>

<details>
<summary><h3 style="display:inline">Skills by Cloudflare Team</h3></summary>

* **[cloudflare/agents-sdk](https://officialskills.sh/cloudflare/skills/agents-sdk)** - Build stateful AI agents with scheduling, RPC, and MCP servers
* **[cloudflare/cloudflare](https://officialskills.sh/cloudflare/skills/cloudflare)** - Comprehensive Cloudflare platform skill covering Workers, Pages, storage, AI, networking, security, and IaC
* **[cloudflare/cloudflare-email-service](https://officialskills.sh/cloudflare/skills/cloudflare-email-service)** - Send transactional email and route inbound mail with Cloudflare Email Sending and Email Routing
* **[cloudflare/durable-objects](https://officialskills.sh/cloudflare/skills/durable-objects)** - Stateful coordination with RPC, SQLite, and WebSockets
* **[cloudflare/sandbox-sdk](https://officialskills.sh/cloudflare/skills/sandbox-sdk)** - Build sandboxed applications for secure, isolated code execution on Workers
* **[cloudflare/web-perf](https://officialskills.sh/cloudflare/skills/web-perf)** - Audit Core Web Vitals and render-blocking resources
* **[cloudflare/workers-best-practices](https://officialskills.sh/cloudflare/skills/workers-best-practices)** - Review and author Workers code against production best practices and wrangler.jsonc conventions
* **[cloudflare/wrangler](https://officialskills.sh/cloudflare/skills/wrangler)** - Deploy and manage Workers, KV, R2, D1, Vectorize, Queues, Workflows

</details>

<details>
<summary><h3 style="display:inline">Skills by Netlify Team</h3></summary>

* **[netlify/netlify-functions](https://officialskills.sh/netlify/skills/netlify-functions)** - Build serverless API endpoints and background tasks
* **[netlify/netlify-edge-functions](https://officialskills.sh/netlify/skills/netlify-edge-functions)** - Low-latency edge middleware and geolocation logic
* **[netlify/netlify-blobs](https://officialskills.sh/netlify/skills/netlify-blobs)** - Key-value object storage for files and data
* **[netlify/netlify-db](https://officialskills.sh/netlify/skills/netlify-db)** - Managed Postgres with deploy preview branching
* **[netlify/netlify-image-cdn](https://officialskills.sh/netlify/skills/netlify-image-cdn)** - Optimize and transform images via CDN
* **[netlify/netlify-forms](https://officialskills.sh/netlify/skills/netlify-forms)** - HTML form handling with spam filtering
* **[netlify/netlify-frameworks](https://officialskills.sh/netlify/skills/netlify-frameworks)** - Deploy web frameworks with SSR support
* **[netlify/netlify-caching](https://officialskills.sh/netlify/skills/netlify-caching)** - Configure CDN caching and cache purging
* **[netlify/netlify-config](https://officialskills.sh/netlify/skills/netlify-config)** - Reference for netlify.toml site configuration
* **[netlify/netlify-cli-and-deploy](https://officialskills.sh/netlify/skills/netlify-cli-and-deploy)** - CLI setup, local dev, and deployment workflows
* **[netlify/netlify-deploy](https://officialskills.sh/netlify/skills/netlify-deploy)** - Automated deployment workflow for Netlify sites
* **[netlify/netlify-ai-gateway](https://officialskills.sh/netlify/skills/netlify-ai-gateway)** - Access AI models via unified gateway endpoint

</details>

<details>
<summary><h3 style="display:inline">Skills by Google Labs (Stitch)</h3></summary>

Agent Skills for the Stitch MCP server, compatible with Claude Code, Gemini CLI, Cursor, and more.

* **[google-labs-code/design-md](https://officialskills.sh/google-labs-code/skills/design-md)** - Create and manage DESIGN.md files
* **[google-labs-code/enhance-prompt](https://officialskills.sh/google-labs-code/skills/enhance-prompt)** - Improve prompts with design specs and UI/UX vocabulary
* **[google-labs-code/react-components](https://officialskills.sh/google-labs-code/skills/react-components)** - Stitch to React components conversion
* **[google-labs-code/remotion](https://officialskills.sh/google-labs-code/skills/remotion)** - Generate walkthrough videos from Stitch app designs
* **[google-labs-code/shadcn-ui](https://officialskills.sh/google-labs-code/skills/shadcn-ui)** - Build UI components with shadcn/ui
* **[google-labs-code/stitch-loop](https://officialskills.sh/google-labs-code/skills/stitch-loop)** - Iterative design-to-code feedback loop

</details>

<details>
<summary><h3 style="display:inline">Skills by Google Workspace CLI</h3></summary>

Official Google Workspace CLI skills for managing Google Workspace services via the `gws` CLI tool.

* **[googleworkspace/gws-shared](https://officialskills.sh/googleworkspace/skills/gws-shared)** - Shared authentication, global flags, and output formatting
* **[googleworkspace/gws-drive](https://officialskills.sh/googleworkspace/skills/gws-drive)** - Manage Google Drive files, folders, and shared drives
* **[googleworkspace/gws-sheets](https://officialskills.sh/googleworkspace/skills/gws-sheets)** - Read and write Google Sheets spreadsheets
* **[googleworkspace/gws-gmail](https://officialskills.sh/googleworkspace/skills/gws-gmail)** - Send, read, and manage Gmail email
* **[googleworkspace/gws-calendar](https://officialskills.sh/googleworkspace/skills/gws-calendar)** - Manage Google Calendar calendars and events
* **[googleworkspace/gws-admin-reports](https://officialskills.sh/googleworkspace/skills/gws-admin-reports)** - Audit logs and usage reports for Workspace
* **[googleworkspace/gws-docs](https://officialskills.sh/googleworkspace/skills/gws-docs)** - Read and write Google Docs documents
* **[googleworkspace/gws-slides](https://officialskills.sh/googleworkspace/skills/gws-slides)** - Read and write Google Slides presentations
* **[googleworkspace/gws-tasks](https://officialskills.sh/googleworkspace/skills/gws-tasks)** - Manage Google Tasks task lists and tasks
* **[googleworkspace/gws-people](https://officialskills.sh/googleworkspace/skills/gws-people)** - Manage Google People contacts and profiles
* **[googleworkspace/gws-chat](https://officialskills.sh/googleworkspace/skills/gws-chat)** - Manage Google Chat spaces and messages
* **[googleworkspace/gws-classroom](https://officialskills.sh/googleworkspace/skills/gws-classroom)** - Manage Google Classroom classes, rosters, and coursework
* **[googleworkspace/gws-forms](https://officialskills.sh/googleworkspace/skills/gws-forms)** - Read and write Google Forms
* **[googleworkspace/gws-keep](https://officialskills.sh/googleworkspace/skills/gws-keep)** - Manage Google Keep notes
* **[googleworkspace/gws-events](https://officialskills.sh/googleworkspace/skills/gws-events)** - Subscribe to Google Workspace events
* **[googleworkspace/gws-modelarmor](https://officialskills.sh/googleworkspace/skills/gws-modelarmor)** - Filter user-generated content for safety
* **[googleworkspace/gws-workflow](https://officialskills.sh/googleworkspace/skills/gws-workflow)** - Cross-service Google Workspace productivity workflows

</details>

<details>
<summary><h3 style="display:inline">Skills by Expo Team</h3></summary>

Official AI agent skills from the Expo team for building, deploying, and debugging Expo apps.

* **[expo/building-native-ui](https://officialskills.sh/expo/skills/building-native-ui)** - Build apps with Expo Router, styling, components, navigation, and animations
* **[expo/expo-api-routes](https://officialskills.sh/expo/skills/expo-api-routes)** - Create API routes in Expo Router with EAS Hosting
* **[expo/expo-cicd-workflows](https://officialskills.sh/expo/skills/expo-cicd-workflows)** - CI/CD workflows for Expo projects
* **[expo/expo-deployment](https://officialskills.sh/expo/skills/expo-deployment)** - Deploy Expo apps to production
* **[expo/expo-dev-client](https://officialskills.sh/expo/skills/expo-dev-client)** - Build and distribute Expo dev clients locally or via TestFlight
* **[expo/expo-tailwind-setup](https://officialskills.sh/expo/skills/expo-tailwind-setup)** - Set up Tailwind CSS v4 in Expo with NativeWind v5
* **[expo/expo-ui-jetpack-compose](https://officialskills.sh/expo/skills/expo-ui-jetpack-compose)** - Jetpack Compose UI components for Expo
* **[expo/expo-ui-swift-ui](https://officialskills.sh/expo/skills/expo-ui-swift-ui)** - SwiftUI components for Expo
* **[expo/native-data-fetching](https://officialskills.sh/expo/skills/native-data-fetching)** - Network requests, API calls, caching, and offline support
* **[expo/upgrading-expo](https://officialskills.sh/expo/skills/upgrading-expo)** - Upgrade Expo SDK versions
* **[expo/use-dom](https://officialskills.sh/expo/skills/use-dom)** - Run web code in a webview on native using DOM components

</details>

<details>
<summary><h3 style="display:inline">Skills by Hugging Face Team</h3></summary>

Official AI agent skills from the Hugging Face team for ML workflows.

* **[huggingface/hf-cli](https://officialskills.sh/huggingface/skills/hf-cli)** - HF CLI tool for Hub operations
* **[huggingface/hugging-face-dataset-viewer](https://officialskills.sh/huggingface/skills/hugging-face-dataset-viewer)** - Browse and query HF datasets with the Dataset Viewer API
* **[huggingface/hugging-face-datasets](https://officialskills.sh/huggingface/skills/hugging-face-datasets)** - Create and manage datasets with configs and SQL querying
* **[huggingface/hugging-face-evaluation](https://officialskills.sh/huggingface/skills/hugging-face-evaluation)** - Model evaluation with vLLM/lighteval and eval tables
* **[huggingface/hugging-face-jobs](https://officialskills.sh/huggingface/skills/hugging-face-jobs)** - Run compute jobs and Python scripts on HF infrastructure
* **[huggingface/hugging-face-model-trainer](https://officialskills.sh/huggingface/skills/hugging-face-model-trainer)** - Train models with TRL: SFT, DPO, GRPO, GGUF conversion
* **[huggingface/hugging-face-paper-pages](https://officialskills.sh/huggingface/skills/hugging-face-paper-pages)** - Create and manage paper pages on HF Hub
* **[huggingface/hugging-face-paper-publisher](https://officialskills.sh/huggingface/skills/hugging-face-paper-publisher)** - Publish papers on HF Hub with model/dataset links
* **[huggingface/hugging-face-tool-builder](https://officialskills.sh/huggingface/skills/hugging-face-tool-builder)** - Build reusable scripts for HF API operations
* **[huggingface/hugging-face-trackio](https://officialskills.sh/huggingface/skills/hugging-face-trackio)** - Track ML experiments with real-time dashboards
* **[huggingface/hugging-face-vision-trainer](https://officialskills.sh/huggingface/skills/hugging-face-vision-trainer)** - Train vision models on HF infrastructure
* **[huggingface/huggingface-gradio](https://officialskills.sh/huggingface/skills/huggingface-gradio)** - Build Gradio apps and deploy to HF Spaces
* **[huggingface/transformers.js](https://officialskills.sh/huggingface/skills/transformers.js)** - Run ML models in the browser with Transformers.js

</details>

<details>
<summary><h3 style="display:inline">Security Skills by Trail of Bits Team</h3></summary>

* **[trailofbits/ask-questions-if-underspecified](https://officialskills.sh/trailofbits/skills/ask-questions-if-underspecified)** - Prompt for clarification on ambiguous requirements
* **[trailofbits/audit-context-building](https://officialskills.sh/trailofbits/skills/audit-context-building)** - Deep architectural context via ultra-granular code analysis
* **[trailofbits/building-secure-contracts](https://officialskills.sh/trailofbits/skills/building-secure-contracts)** - Smart contract security toolkit with vulnerability scanners for 6 blockchains
* **[trailofbits/burpsuite-project-parser](https://officialskills.sh/trailofbits/skills/burpsuite-project-parser)** - Search and extract data from Burp Suite project files
* **[trailofbits/claude-in-chrome-troubleshooting](https://officialskills.sh/trailofbits/skills/claude-in-chrome-troubleshooting)** - Diagnose and fix Claude in Chrome MCP extension connectivity issues
* **[trailofbits/constant-time-analysis](https://officialskills.sh/trailofbits/skills/constant-time-analysis)** - Detect compiler-induced timing side-channels in crypto code
* **[trailofbits/culture-index](https://officialskills.sh/trailofbits/skills/culture-index)** - Index and search culture documentation
* **[trailofbits/differential-review](https://officialskills.sh/trailofbits/skills/differential-review)** - Security-focused diff review with git history analysis
* **[trailofbits/dwarf-expert](https://officialskills.sh/trailofbits/skills/dwarf-expert)** - DWARF debugging format expertise
* **[trailofbits/entry-point-analyzer](https://officialskills.sh/trailofbits/skills/entry-point-analyzer)** - Identify state-changing entry points in smart contracts
* **[trailofbits/firebase-apk-scanner](https://officialskills.sh/trailofbits/skills/firebase-apk-scanner)** - Scan Android APKs for Firebase misconfigurations and security vulnerabilities
* **[trailofbits/insecure-defaults](https://officialskills.sh/trailofbits/skills/insecure-defaults)** - Detect insecure default configurations like hardcoded secrets, default credentials, and weak crypto
* **[trailofbits/modern-python](https://officialskills.sh/trailofbits/skills/modern-python)** - Modern Python tooling with uv, ruff, ty, and pytest best practices
* **[trailofbits/property-based-testing](https://officialskills.sh/trailofbits/skills/property-based-testing)** - Property-based testing for multiple languages and smart contracts
* **[trailofbits/semgrep-rule-creator](https://officialskills.sh/trailofbits/skills/semgrep-rule-creator)** - Create and refine Semgrep rules for vulnerability detection
* **[trailofbits/semgrep-rule-variant-creator](https://officialskills.sh/trailofbits/skills/semgrep-rule-variant-creator)** - Port existing Semgrep rules to new target languages with test-driven validation
* **[trailofbits/sharp-edges](https://officialskills.sh/trailofbits/skills/sharp-edges)** - Identify error-prone APIs and dangerous configurations
* **[trailofbits/spec-to-code-compliance](https://officialskills.sh/trailofbits/skills/spec-to-code-compliance)** - Specification-to-code compliance checker for blockchain audits
* **[trailofbits/static-analysis](https://officialskills.sh/trailofbits/skills/static-analysis)** - Static analysis toolkit with CodeQL, Semgrep, and SARIF
* **[trailofbits/testing-handbook-skills](https://officialskills.sh/trailofbits/skills/testing-handbook-skills)** - Testing Handbook skills: fuzzers, static analysis, sanitizers
* **[trailofbits/variant-analysis](https://officialskills.sh/trailofbits/skills/variant-analysis)** - Find similar vulnerabilities via pattern-based analysis

</details>

<details>
<summary><h3 style="display:inline">Skills by Sentry team for their dev team.</h3></summary>

* **[getsentry/sentry-sdk-setup](https://officialskills.sh/getsentry/skills/sentry-sdk-setup)** - Set up Sentry in any language or framework — detects platform and routes to the right SDK
* **[getsentry/sentry-workflow](https://officialskills.sh/getsentry/skills/sentry-workflow)** - End-to-end Sentry workflow: fix production issues and review code with Sentry context
* **[getsentry/sentry-fix-issues](https://officialskills.sh/getsentry/skills/sentry-fix-issues)** - Find and fix Sentry issues with stack trace, breadcrumb, and trace context via MCP
* **[getsentry/sentry-code-review](https://officialskills.sh/getsentry/skills/sentry-code-review)** - Review code changes using Sentry issue and trace context
* **[getsentry/sentry-pr-code-review](https://officialskills.sh/getsentry/skills/sentry-pr-code-review)** - Review PR comments from Seer Bug Prediction and Sentry feedback
* **[getsentry/sentry-create-alert](https://officialskills.sh/getsentry/skills/sentry-create-alert)** - Create Sentry alerts with email, Slack, PagerDuty, Discord, and more
* **[getsentry/sentry-feature-setup](https://officialskills.sh/getsentry/skills/sentry-feature-setup)** - Configure advanced Sentry features: AI monitoring, OTel pipelines, and alerts
* **[getsentry/sentry-otel-exporter-setup](https://officialskills.sh/getsentry/skills/sentry-otel-exporter-setup)** - Configure the OpenTelemetry Collector with Sentry Exporter
* **[getsentry/sentry-setup-ai-monitoring](https://officialskills.sh/getsentry/skills/sentry-setup-ai-monitoring)** - Instrument OpenAI, Anthropic, Vercel AI, LangChain, Google GenAI, and Pydantic AI
* **[getsentry/sentry-sdk-upgrade](https://officialskills.sh/getsentry/skills/sentry-sdk-upgrade)** - Upgrade the Sentry JavaScript SDK across major versions
* **[getsentry/sentry-sdk-skill-creator](https://officialskills.sh/getsentry/skills/sentry-sdk-skill-creator)** - Create a new Sentry SDK skill bundle for a platform
* **[getsentry/sentry-android-sdk](https://officialskills.sh/getsentry/skills/sentry-android-sdk)** - Full Sentry SDK setup for Android (Kotlin and Java)
* **[getsentry/sentry-browser-sdk](https://officialskills.sh/getsentry/skills/sentry-browser-sdk)** - Full Sentry SDK setup for browser JavaScript
* **[getsentry/sentry-cloudflare-sdk](https://officialskills.sh/getsentry/skills/sentry-cloudflare-sdk)** - Full Sentry SDK setup for Cloudflare Workers, Pages, Durable Objects, Queues, and Workflows
* **[getsentry/sentry-cocoa-sdk](https://officialskills.sh/getsentry/skills/sentry-cocoa-sdk)** - Full Sentry SDK setup for Apple platforms (iOS, macOS, tvOS, watchOS, visionOS)
* **[getsentry/sentry-dotnet-sdk](https://officialskills.sh/getsentry/skills/sentry-dotnet-sdk)** - Full Sentry SDK setup for .NET (ASP.NET Core, MAUI, WPF, WinForms, Blazor, Azure Functions)
* **[getsentry/sentry-elixir-sdk](https://officialskills.sh/getsentry/skills/sentry-elixir-sdk)** - Full Sentry SDK setup for Elixir, Phoenix, Plug, LiveView, Oban, and Quantum
* **[getsentry/sentry-flutter-sdk](https://officialskills.sh/getsentry/skills/sentry-flutter-sdk)** - Full Sentry SDK setup for Flutter and Dart across all platforms
* **[getsentry/sentry-go-sdk](https://officialskills.sh/getsentry/skills/sentry-go-sdk)** - Full Sentry SDK setup for Go (net/http, Gin, Echo, Fiber, FastHTTP, Iris, Negroni)
* **[getsentry/sentry-nestjs-sdk](https://officialskills.sh/getsentry/skills/sentry-nestjs-sdk)** - Full Sentry SDK setup for NestJS with Express or Fastify, GraphQL, microservices
* **[getsentry/sentry-nextjs-sdk](https://officialskills.sh/getsentry/skills/sentry-nextjs-sdk)** - Full Sentry SDK setup for Next.js 13+ (App Router and Pages Router)
* **[getsentry/sentry-node-sdk](https://officialskills.sh/getsentry/skills/sentry-node-sdk)** - Full Sentry SDK setup for Node.js, Bun, and Deno
* **[getsentry/sentry-php-sdk](https://officialskills.sh/getsentry/skills/sentry-php-sdk)** - Full Sentry SDK setup for PHP, Laravel, and Symfony
* **[getsentry/sentry-python-sdk](https://officialskills.sh/getsentry/skills/sentry-python-sdk)** - Full Sentry SDK setup for Python (Django, Flask, FastAPI, Celery, Starlette, AIOHTTP, Tornado)
* **[getsentry/sentry-react-native-sdk](https://officialskills.sh/getsentry/skills/sentry-react-native-sdk)** - Full Sentry SDK setup for React Native and Expo
* **[getsentry/sentry-react-sdk](https://officialskills.sh/getsentry/skills/sentry-react-sdk)** - Full Sentry SDK setup for React (React Router v5-v7, TanStack Router, Redux, Vite, webpack)
* **[getsentry/sentry-ruby-sdk](https://officialskills.sh/getsentry/skills/sentry-ruby-sdk)** - Full Sentry SDK setup for Ruby (Rails, Sinatra, Rack, Sidekiq, Resque)
* **[getsentry/sentry-svelte-sdk](https://officialskills.sh/getsentry/skills/sentry-svelte-sdk)** - Full Sentry SDK setup for Svelte and SvelteKit

</details>

<details>
<summary><h3 style="display:inline">Skills by Microsoft</h3></summary>

Domain-specific knowledge for Azure SDK and Microsoft AI Foundry development. 133 skills across 6 languages.

### Core Skills

* **[microsoft/cloud-solution-architect](https://officialskills.sh/microsoft/skills/cloud-solution-architect)** - Design well-architected Azure cloud systems
* **[microsoft/continual-learning](https://officialskills.sh/microsoft/skills/continual-learning)** - Continual learning patterns for Azure AI
* **[microsoft/copilot-sdk](https://officialskills.sh/microsoft/skills/copilot-sdk)** - Build applications powered by GitHub Copilot SDK
* **[microsoft/entra-agent-id](https://officialskills.sh/microsoft/skills/entra-agent-id)** - Microsoft Entra Agent ID OAuth2 identities via Graph API
* **[microsoft/frontend-design-review](https://officialskills.sh/microsoft/skills/frontend-design-review)** - Review and create distinctive frontend interfaces
* **[microsoft/github-issue-creator](https://officialskills.sh/microsoft/skills/github-issue-creator)** - Structured GitHub issue reports from notes
* **[microsoft/mcp-builder](https://officialskills.sh/microsoft/skills/mcp-builder)** - MCP server creation guide for LLM tool integration
* **[microsoft/podcast-generation](https://officialskills.sh/microsoft/skills/podcast-generation)** - AI podcast audio with Azure OpenAI Realtime API
* **[microsoft/skill-creator](https://officialskills.sh/microsoft/skills/skill-creator)** - Guide for creating effective skills for AI coding agents

### .NET Skills

* **[microsoft/azure-ai-document-intelligence-dotnet](https://officialskills.sh/microsoft/skills/azure-ai-document-intelligence-dotnet)** - Document text, table, and data extraction
* **[microsoft/azure-ai-openai-dotnet](https://officialskills.sh/microsoft/skills/azure-ai-openai-dotnet)** - GPT-4, embeddings, DALL-E, and Whisper client
* **[microsoft/azure-ai-projects-dotnet](https://officialskills.sh/microsoft/skills/azure-ai-projects-dotnet)** - AI Foundry project management SDK
* **[microsoft/azure-ai-voicelive-dotnet](https://officialskills.sh/microsoft/skills/azure-ai-voicelive-dotnet)** - Real-time bidirectional voice AI
* **[microsoft/azure-eventgrid-dotnet](https://officialskills.sh/microsoft/skills/azure-eventgrid-dotnet)** - Event Grid topic and domain publishing
* **[microsoft/azure-eventhub-dotnet](https://officialskills.sh/microsoft/skills/azure-eventhub-dotnet)** - High-throughput event streaming
* **[microsoft/azure-identity-dotnet](https://officialskills.sh/microsoft/skills/azure-identity-dotnet)** - Microsoft Entra ID authentication
* **[microsoft/azure-maps-search-dotnet](https://officialskills.sh/microsoft/skills/azure-maps-search-dotnet)** - Geocoding, routing, and weather services
* **[microsoft/azure-mgmt-apicenter-dotnet](https://officialskills.sh/microsoft/skills/azure-mgmt-apicenter-dotnet)** - API inventory and governance
* **[microsoft/azure-mgmt-apimanagement-dotnet](https://officialskills.sh/microsoft/skills/azure-mgmt-apimanagement-dotnet)** - API Management provisioning via ARM
* **[microsoft/azure-mgmt-applicationinsights-dotnet](https://officialskills.sh/microsoft/skills/azure-mgmt-applicationinsights-dotnet)** - Application Insights resource management
* **[microsoft/azure-mgmt-arizeaiobservabilityeval-dotnet](https://officialskills.sh/microsoft/skills/azure-mgmt-arizeaiobservabilityeval-dotnet)** - Arize AI observability management
* **[microsoft/azure-mgmt-botservice-dotnet](https://officialskills.sh/microsoft/skills/azure-mgmt-botservice-dotnet)** - Bot Service provisioning via ARM
* **[microsoft/azure-mgmt-fabric-dotnet](https://officialskills.sh/microsoft/skills/azure-mgmt-fabric-dotnet)** - Microsoft Fabric capacity management
* **[microsoft/azure-mgmt-mongodbatlas-dotnet](https://officialskills.sh/microsoft/skills/azure-mgmt-mongodbatlas-dotnet)** - MongoDB Atlas as ARM resources
* **[microsoft/azure-mgmt-weightsandbiases-dotnet](https://officialskills.sh/microsoft/skills/azure-mgmt-weightsandbiases-dotnet)** - Weights & Biases deployment management
* **[microsoft/azure-resource-manager-cosmosdb-dotnet](https://officialskills.sh/microsoft/skills/azure-resource-manager-cosmosdb-dotnet)** - Cosmos DB resource provisioning
* **[microsoft/azure-resource-manager-durabletask-dotnet](https://officialskills.sh/microsoft/skills/azure-resource-manager-durabletask-dotnet)** - Durable Task Scheduler management
* **[microsoft/azure-resource-manager-mysql-dotnet](https://officialskills.sh/microsoft/skills/azure-resource-manager-mysql-dotnet)** - MySQL Flexible Server management
* **[microsoft/azure-resource-manager-playwright-dotnet](https://officialskills.sh/microsoft/skills/azure-resource-manager-playwright-dotnet)** - Playwright Testing workspace management
* **[microsoft/azure-resource-manager-postgresql-dotnet](https://officialskills.sh/microsoft/skills/azure-resource-manager-postgresql-dotnet)** - PostgreSQL Flexible Server management
* **[microsoft/azure-resource-manager-redis-dotnet](https://officialskills.sh/microsoft/skills/azure-resource-manager-redis-dotnet)** - Azure Cache for Redis provisioning
* **[microsoft/azure-resource-manager-sql-dotnet](https://officialskills.sh/microsoft/skills/azure-resource-manager-sql-dotnet)** - Azure SQL resource management
* **[microsoft/azure-search-documents-dotnet](https://officialskills.sh/microsoft/skills/azure-search-documents-dotnet)** - Full-text, vector, and hybrid search
* **[microsoft/azure-security-keyvault-keys-dotnet](https://officialskills.sh/microsoft/skills/azure-security-keyvault-keys-dotnet)** - Cryptographic key management
* **[microsoft/azure-servicebus-dotnet](https://officialskills.sh/microsoft/skills/azure-servicebus-dotnet)** - Enterprise messaging with queues and topics
* **[microsoft/m365-agents-dotnet](https://officialskills.sh/microsoft/skills/m365-agents-dotnet)** - M365, Teams, and Copilot Studio agents
* **[microsoft/microsoft-azure-webjobs-extensions-authentication-events-dotnet](https://officialskills.sh/microsoft/skills/microsoft-azure-webjobs-extensions-authentication-events-dotnet)** - Entra ID custom auth events handler

### Java Skills

* **[microsoft/azure-ai-anomalydetector-java](https://officialskills.sh/microsoft/skills/azure-ai-anomalydetector-java)** - Anomaly detection applications
* **[microsoft/azure-ai-contentsafety-java](https://officialskills.sh/microsoft/skills/azure-ai-contentsafety-java)** - Content moderation and safety
* **[microsoft/azure-ai-formrecognizer-java](https://officialskills.sh/microsoft/skills/azure-ai-formrecognizer-java)** - Document analysis and form extraction
* **[microsoft/azure-ai-projects-java](https://officialskills.sh/microsoft/skills/azure-ai-projects-java)** - AI Foundry project management
* **[microsoft/azure-ai-vision-imageanalysis-java](https://officialskills.sh/microsoft/skills/azure-ai-vision-imageanalysis-java)** - Image captioning, OCR, and object detection
* **[microsoft/azure-ai-voicelive-java](https://officialskills.sh/microsoft/skills/azure-ai-voicelive-java)** - Real-time bidirectional voice AI
* **[microsoft/azure-appconfiguration-java](https://officialskills.sh/microsoft/skills/azure-appconfiguration-java)** - Centralized app configuration management
* **[microsoft/azure-communication-callautomation-java](https://officialskills.sh/microsoft/skills/azure-communication-callautomation-java)** - Call automation with IVR and AI
* **[microsoft/azure-communication-callingserver-java](https://officialskills.sh/microsoft/skills/azure-communication-callingserver-java)** - CallingServer legacy SDK
* **[microsoft/azure-communication-chat-java](https://officialskills.sh/microsoft/skills/azure-communication-chat-java)** - Real-time chat with threads and receipts
* **[microsoft/azure-communication-common-java](https://officialskills.sh/microsoft/skills/azure-communication-common-java)** - Communication Services common utilities
* **[microsoft/azure-communication-sms-java](https://officialskills.sh/microsoft/skills/azure-communication-sms-java)** - SMS sending and delivery reports
* **[microsoft/azure-compute-batch-java](https://officialskills.sh/microsoft/skills/azure-compute-batch-java)** - Large-scale parallel and HPC batch jobs
* **[microsoft/azure-cosmos-java](https://officialskills.sh/microsoft/skills/azure-cosmos-java)** - Cosmos DB NoSQL with global distribution
* **[microsoft/azure-data-tables-java](https://officialskills.sh/microsoft/skills/azure-data-tables-java)** - NoSQL key-value table storage
* **[microsoft/azure-eventgrid-java](https://officialskills.sh/microsoft/skills/azure-eventgrid-java)** - Event-driven pub/sub messaging
* **[microsoft/azure-eventhub-java](https://officialskills.sh/microsoft/skills/azure-eventhub-java)** - Real-time high-throughput streaming
* **[microsoft/azure-identity-java](https://officialskills.sh/microsoft/skills/azure-identity-java)** - Microsoft Entra ID authentication
* **[microsoft/azure-messaging-webpubsub-java](https://officialskills.sh/microsoft/skills/azure-messaging-webpubsub-java)** - Real-time WebSocket messaging
* **[microsoft/azure-monitor-ingestion-java](https://officialskills.sh/microsoft/skills/azure-monitor-ingestion-java)** - Custom log ingestion to Azure Monitor
* **[microsoft/azure-monitor-opentelemetry-exporter-java](https://officialskills.sh/microsoft/skills/azure-monitor-opentelemetry-exporter-java)** - OpenTelemetry export to Azure Monitor
* **[microsoft/azure-monitor-query-java](https://officialskills.sh/microsoft/skills/azure-monitor-query-java)** - Query Azure Monitor logs and metrics
* **[microsoft/azure-security-keyvault-keys-java](https://officialskills.sh/microsoft/skills/azure-security-keyvault-keys-java)** - Cryptographic key management
* **[microsoft/azure-security-keyvault-secrets-java](https://officialskills.sh/microsoft/skills/azure-security-keyvault-secrets-java)** - Secret management for passwords and keys
* **[microsoft/azure-storage-blob-java](https://officialskills.sh/microsoft/skills/azure-storage-blob-java)** - Blob storage for file management

### Python Skills

* **[microsoft/agent-framework-azure-ai-py](https://officialskills.sh/microsoft/skills/agent-framework-azure-ai-py)** - Agent Framework for Azure AI Foundry
* **[microsoft/agents-v2-py](https://officialskills.sh/microsoft/skills/agents-v2-py)** - Foundry Agents SDK — container-based agents with custom images
* **[microsoft/azure-ai-contentsafety-py](https://officialskills.sh/microsoft/skills/azure-ai-contentsafety-py)** - Harmful content detection
* **[microsoft/azure-ai-contentunderstanding-py](https://officialskills.sh/microsoft/skills/azure-ai-contentunderstanding-py)** - Multimodal content extraction
* **[microsoft/azure-ai-ml-py](https://officialskills.sh/microsoft/skills/azure-ai-ml-py)** - Azure ML workspace and job management
* **[microsoft/azure-ai-projects-py](https://officialskills.sh/microsoft/skills/azure-ai-projects-py)** - AI Foundry project client and agents
* **[microsoft/azure-ai-textanalytics-py](https://officialskills.sh/microsoft/skills/azure-ai-textanalytics-py)** - NLP: sentiment, entities, key phrases
* **[microsoft/azure-ai-transcription-py](https://officialskills.sh/microsoft/skills/azure-ai-transcription-py)** - Speech-to-text transcription
* **[microsoft/azure-ai-translation-document-py](https://officialskills.sh/microsoft/skills/azure-ai-translation-document-py)** - Batch document translation
* **[microsoft/azure-ai-translation-text-py](https://officialskills.sh/microsoft/skills/azure-ai-translation-text-py)** - Real-time text translation
* **[microsoft/azure-ai-vision-imageanalysis-py](https://officialskills.sh/microsoft/skills/azure-ai-vision-imageanalysis-py)** - Image captions, tags, OCR, objects
* **[microsoft/azure-ai-voicelive-py](https://officialskills.sh/microsoft/skills/azure-ai-voicelive-py)** - Real-time bidirectional voice AI
* **[microsoft/azure-appconfiguration-py](https://officialskills.sh/microsoft/skills/azure-appconfiguration-py)** - Feature flags and dynamic settings
* **[microsoft/azure-containerregistry-py](https://officialskills.sh/microsoft/skills/azure-containerregistry-py)** - Container image and registry management
* **[microsoft/azure-cosmos-db-py](https://officialskills.sh/microsoft/skills/azure-cosmos-db-py)** - Cosmos DB with Python/FastAPI patterns
* **[microsoft/azure-cosmos-py](https://officialskills.sh/microsoft/skills/azure-cosmos-py)** - Cosmos DB NoSQL client library
* **[microsoft/azure-data-tables-py](https://officialskills.sh/microsoft/skills/azure-data-tables-py)** - NoSQL key-value table storage
* **[microsoft/azure-eventgrid-py](https://officialskills.sh/microsoft/skills/azure-eventgrid-py)** - Event-driven pub/sub routing
* **[microsoft/azure-eventhub-py](https://officialskills.sh/microsoft/skills/azure-eventhub-py)** - High-throughput event streaming
* **[microsoft/azure-identity-py](https://officialskills.sh/microsoft/skills/azure-identity-py)** - Microsoft Entra ID authentication
* **[microsoft/azure-keyvault-py](https://officialskills.sh/microsoft/skills/azure-keyvault-py)** - Secrets, keys, and certificate management
* **[microsoft/azure-messaging-webpubsubservice-py](https://officialskills.sh/microsoft/skills/azure-messaging-webpubsubservice-py)** - Real-time WebSocket messaging
* **[microsoft/azure-mgmt-apicenter-py](https://officialskills.sh/microsoft/skills/azure-mgmt-apicenter-py)** - API inventory and governance
* **[microsoft/azure-mgmt-apimanagement-py](https://officialskills.sh/microsoft/skills/azure-mgmt-apimanagement-py)** - API Management service administration
* **[microsoft/azure-mgmt-botservice-py](https://officialskills.sh/microsoft/skills/azure-mgmt-botservice-py)** - Bot Service resource management
* **[microsoft/azure-mgmt-fabric-py](https://officialskills.sh/microsoft/skills/azure-mgmt-fabric-py)** - Microsoft Fabric capacity management
* **[microsoft/azure-monitor-ingestion-py](https://officialskills.sh/microsoft/skills/azure-monitor-ingestion-py)** - Custom log ingestion to Azure Monitor
* **[microsoft/azure-monitor-opentelemetry-exporter-py](https://officialskills.sh/microsoft/skills/azure-monitor-opentelemetry-exporter-py)** - OpenTelemetry export to Application Insights
* **[microsoft/azure-monitor-opentelemetry-py](https://officialskills.sh/microsoft/skills/azure-monitor-opentelemetry-py)** - One-line Application Insights setup
* **[microsoft/azure-monitor-query-py](https://officialskills.sh/microsoft/skills/azure-monitor-query-py)** - Query Azure Monitor logs and metrics
* **[microsoft/azure-search-documents-py](https://officialskills.sh/microsoft/skills/azure-search-documents-py)** - Full-text, vector, and hybrid search
* **[microsoft/azure-servicebus-py](https://officialskills.sh/microsoft/skills/azure-servicebus-py)** - Enterprise messaging with queues and topics
* **[microsoft/azure-speech-to-text-rest-py](https://officialskills.sh/microsoft/skills/azure-speech-to-text-rest-py)** - REST speech-to-text for short audio
* **[microsoft/azure-storage-blob-py](https://officialskills.sh/microsoft/skills/azure-storage-blob-py)** - Blob object storage client
* **[microsoft/azure-storage-file-datalake-py](https://officialskills.sh/microsoft/skills/azure-storage-file-datalake-py)** - Hierarchical data lake storage
* **[microsoft/azure-storage-file-share-py](https://officialskills.sh/microsoft/skills/azure-storage-file-share-py)** - SMB file share management
* **[microsoft/azure-storage-queue-py](https://officialskills.sh/microsoft/skills/azure-storage-queue-py)** - Simple message queuing
* **[microsoft/fastapi-router-py](https://officialskills.sh/microsoft/skills/fastapi-router-py)** - FastAPI routers with CRUD and auth
* **[microsoft/m365-agents-py](https://officialskills.sh/microsoft/skills/m365-agents-py)** - M365, Teams, and Copilot Studio agents
* **[microsoft/pydantic-models-py](https://officialskills.sh/microsoft/skills/pydantic-models-py)** - Pydantic models for API schemas

### Rust Skills

* **[microsoft/azure-cosmos-rust](https://officialskills.sh/microsoft/skills/azure-cosmos-rust)** - Cosmos DB NoSQL client
* **[microsoft/azure-eventhub-rust](https://officialskills.sh/microsoft/skills/azure-eventhub-rust)** - Event Hubs streaming client
* **[microsoft/azure-identity-rust](https://officialskills.sh/microsoft/skills/azure-identity-rust)** - Microsoft Entra ID authentication
* **[microsoft/azure-keyvault-certificates-rust](https://officialskills.sh/microsoft/skills/azure-keyvault-certificates-rust)** - Key Vault certificate management
* **[microsoft/azure-keyvault-keys-rust](https://officialskills.sh/microsoft/skills/azure-keyvault-keys-rust)** - Key Vault cryptographic key management
* **[microsoft/azure-keyvault-secrets-rust](https://officialskills.sh/microsoft/skills/azure-keyvault-secrets-rust)** - Key Vault secret storage
* **[microsoft/azure-storage-blob-rust](https://officialskills.sh/microsoft/skills/azure-storage-blob-rust)** - Blob object storage client

### TypeScript Skills

* **[microsoft/azure-ai-contentsafety-ts](https://officialskills.sh/microsoft/skills/azure-ai-contentsafety-ts)** - Content safety for text and images
* **[microsoft/azure-ai-document-intelligence-ts](https://officialskills.sh/microsoft/skills/azure-ai-document-intelligence-ts)** - Document text and table extraction
* **[microsoft/azure-ai-projects-ts](https://officialskills.sh/microsoft/skills/azure-ai-projects-ts)** - AI Foundry project client and agents
* **[microsoft/azure-ai-translation-ts](https://officialskills.sh/microsoft/skills/azure-ai-translation-ts)** - Text and document translation
* **[microsoft/azure-ai-voicelive-ts](https://officialskills.sh/microsoft/skills/azure-ai-voicelive-ts)** - Real-time bidirectional voice AI
* **[microsoft/azure-appconfiguration-ts](https://officialskills.sh/microsoft/skills/azure-appconfiguration-ts)** - App config, feature flags, dynamic refresh
* **[microsoft/azure-cosmos-ts](https://officialskills.sh/microsoft/skills/azure-cosmos-ts)** - Cosmos DB NoSQL CRUD and queries
* **[microsoft/azure-eventhub-ts](https://officialskills.sh/microsoft/skills/azure-eventhub-ts)** - High-throughput event streaming
* **[microsoft/azure-identity-ts](https://officialskills.sh/microsoft/skills/azure-identity-ts)** - Microsoft Entra ID authentication
* **[microsoft/azure-keyvault-keys-ts](https://officialskills.sh/microsoft/skills/azure-keyvault-keys-ts)** - Cryptographic key management
* **[microsoft/azure-keyvault-secrets-ts](https://officialskills.sh/microsoft/skills/azure-keyvault-secrets-ts)** - Secret storage and retrieval
* **[microsoft/azure-microsoft-playwright-testing-ts](https://officialskills.sh/microsoft/skills/azure-microsoft-playwright-testing-ts)** - Playwright tests at scale on Azure
* **[microsoft/azure-monitor-opentelemetry-ts](https://officialskills.sh/microsoft/skills/azure-monitor-opentelemetry-ts)** - Application Insights tracing and metrics
* **[microsoft/azure-postgres-ts](https://officialskills.sh/microsoft/skills/azure-postgres-ts)** - PostgreSQL Flexible Server connection
* **[microsoft/azure-search-documents-ts](https://officialskills.sh/microsoft/skills/azure-search-documents-ts)** - Vector/hybrid search with semantic ranking
* **[microsoft/azure-servicebus-ts](https://officialskills.sh/microsoft/skills/azure-servicebus-ts)** - Messaging with queues and topics
* **[microsoft/azure-storage-blob-ts](https://officialskills.sh/microsoft/skills/azure-storage-blob-ts)** - Blob upload, download, and management
* **[microsoft/azure-storage-file-share-ts](https://officialskills.sh/microsoft/skills/azure-storage-file-share-ts)** - SMB file share operations
* **[microsoft/azure-storage-queue-ts](https://officialskills.sh/microsoft/skills/azure-storage-queue-ts)** - Queue message operations
* **[microsoft/azure-web-pubsub-ts](https://officialskills.sh/microsoft/skills/azure-web-pubsub-ts)** - Real-time WebSocket pub/sub messaging
* **[microsoft/frontend-ui-dark-ts](https://officialskills.sh/microsoft/skills/frontend-ui-dark-ts)** - Dark-themed React with Tailwind and animations
* **[microsoft/m365-agents-ts](https://officialskills.sh/microsoft/skills/m365-agents-ts)** - M365, Teams, and Copilot Studio agents
* **[microsoft/react-flow-node-ts](https://officialskills.sh/microsoft/skills/react-flow-node-ts)** - React Flow node components with Zustand
* **[microsoft/zustand-store-ts](https://officialskills.sh/microsoft/skills/zustand-store-ts)** - Zustand stores with middleware patterns

</details>

<details>
<summary><h3 style="display:inline">Skills by fal.ai Team</h3></summary>

* **[fal-ai-community/fal-3d](https://officialskills.sh/fal-ai-community/skills/fal-3d)** - Generate 3D models from text or images
* **[fal-ai-community/fal-audio](https://officialskills.sh/fal-ai-community/skills/fal-audio)** - Text-to-speech and speech-to-text using fal.ai audio models
* **[fal-ai-community/fal-generate](https://officialskills.sh/fal-ai-community/skills/fal-generate)** - Generate images and videos using fal.ai AI models
* **[fal-ai-community/fal-image-edit](https://officialskills.sh/fal-ai-community/skills/fal-image-edit)** - AI-powered image editing with style transfer and object removal
* **[fal-ai-community/fal-kling-o3](https://officialskills.sh/fal-ai-community/skills/fal-kling-o3)** - Generate images and videos with Kling O3 — Kling's most powerful model family
* **[fal-ai-community/fal-lip-sync](https://officialskills.sh/fal-ai-community/skills/fal-lip-sync)** - Create talking head videos and lip sync audio to video
* **[fal-ai-community/fal-platform](https://officialskills.sh/fal-ai-community/skills/fal-platform)** - Platform APIs for model management, pricing, and usage tracking
* **[fal-ai-community/fal-realtime](https://officialskills.sh/fal-ai-community/skills/fal-realtime)** - Real-time and streaming AI image generation
* **[fal-ai-community/fal-restore](https://officialskills.sh/fal-ai-community/skills/fal-restore)** - Restore and fix image quality — deblur, denoise, fix faces, restore documents
* **[fal-ai-community/fal-train](https://officialskills.sh/fal-ai-community/skills/fal-train)** - Train custom AI models (LoRA) on fal.ai for personalized image generation
* **[fal-ai-community/fal-tryon](https://officialskills.sh/fal-ai-community/skills/fal-tryon)** - Virtual try-on — see how clothes look on a person
* **[fal-ai-community/fal-upscale](https://officialskills.sh/fal-ai-community/skills/fal-upscale)** - Upscale and enhance image and video resolution using AI
* **[fal-ai-community/fal-video-edit](https://officialskills.sh/fal-ai-community/skills/fal-video-edit)** - Edit existing videos using AI — remix style, upscale, remove background, add audio
* **[fal-ai-community/fal-vision](https://officialskills.sh/fal-ai-community/skills/fal-vision)** - Analyze images — segment objects, detect, OCR, describe, visual Q\&A
* **[fal-ai-community/fal-workflow](https://officialskills.sh/fal-ai-community/skills/fal-workflow)** - Generate workflow JSON files for chaining AI models

</details>

<details>
<summary><h3 style="display:inline">Skills by WordPress Development Team</h3></summary>

* **[WordPress/wordpress-router](https://officialskills.sh/WordPress/skills/wordpress-router)** - Classifies WordPress repos and routes to the right workflow
* **[WordPress/wp-project-triage](https://officialskills.sh/WordPress/skills/wp-project-triage)** - Detects project type, tooling, and versions automatically
* **[WordPress/wp-block-development](https://officialskills.sh/WordPress/skills/wp-block-development)** - Gutenberg blocks: block.json, attributes, rendering, deprecations
* **[WordPress/wp-block-themes](https://officialskills.sh/WordPress/skills/wp-block-themes)** - Block themes: theme.json, templates, patterns, style variations
* **[WordPress/wp-plugin-development](https://officialskills.sh/WordPress/skills/wp-plugin-development)** - Plugin architecture, hooks, settings API, security
* **[WordPress/wp-rest-api](https://officialskills.sh/WordPress/skills/wp-rest-api)** - REST API routes/endpoints, schema, auth, and response shaping
* **[WordPress/wp-interactivity-api](https://officialskills.sh/WordPress/skills/wp-interactivity-api)** - Frontend interactivity with data-wp-\* directives and stores
* **[WordPress/wp-abilities-api](https://officialskills.sh/WordPress/skills/wp-abilities-api)** - Capability-based permissions and REST API authentication
* **[WordPress/wp-wpcli-and-ops](https://officialskills.sh/WordPress/skills/wp-wpcli-and-ops)** - WP-CLI commands, automation, multisite, search-replace
* **[WordPress/wp-performance](https://officialskills.sh/WordPress/skills/wp-performance)** - Profiling, caching, database optimization, Server-Timing
* **[WordPress/wp-phpstan](https://officialskills.sh/WordPress/skills/wp-phpstan)** - PHPStan static analysis for WordPress projects
* **[WordPress/wp-playground](https://officialskills.sh/WordPress/skills/wp-playground)** - WordPress Playground for instant local environments
* **[WordPress/wpds](https://officialskills.sh/WordPress/skills/wpds)** - WordPress Design System

</details>

<details>
<summary><h3 style="display:inline">Skills by OpenAI</h3></summary>

Official curated skills from OpenAI's skills repository.

* **[openai/cloudflare-deploy](https://officialskills.sh/openai/skills/cloudflare-deploy)** - Deploy apps to Cloudflare using Workers, Pages, and platform services
* **[openai/develop-web-game](https://officialskills.sh/openai/skills/develop-web-game)** - Build and test web games iteratively using Playwright with time-stepping
* **[openai/doc](https://officialskills.sh/openai/skills/doc)** - Read, create, and edit .docx documents with formatting and layout fidelity
* **[openai/gh-address-comments](https://officialskills.sh/openai/skills/gh-address-comments)** - Address review and issue comments on open GitHub PRs via CLI
* **[openai/gh-fix-ci](https://officialskills.sh/openai/skills/gh-fix-ci)** - Debug and fix failing GitHub Actions PR checks using log inspection
* **[openai/imagegen](https://officialskills.sh/openai/skills/imagegen)** - Generate and edit images using OpenAI's Image API for projects
* **[openai/jupyter-notebook](https://officialskills.sh/openai/skills/jupyter-notebook)** - Create clean, reproducible Jupyter notebooks for experiments and tutorials
* **[openai/linear](https://officialskills.sh/openai/skills/linear)** - Manage issues, projects, and team workflows in Linear
* **[openai/netlify-deploy](https://officialskills.sh/openai/skills/netlify-deploy)** - Automate Netlify deployments with CLI auth, linking, and environment support
* **[openai/notion-knowledge-capture](https://officialskills.sh/openai/skills/notion-knowledge-capture)** - Convert conversations into structured, searchable Notion wiki entries
* **[openai/notion-meeting-intelligence](https://officialskills.sh/openai/skills/notion-meeting-intelligence)** - Prep meetings by pulling Notion context and tailoring agendas
* **[openai/notion-research-documentation](https://officialskills.sh/openai/skills/notion-research-documentation)** - Research Notion content and synthesize findings into structured briefs
* **[openai/notion-spec-to-implementation](https://officialskills.sh/openai/skills/notion-spec-to-implementation)** - Convert Notion specs into linked implementation plans and tasks
* **[openai/openai-docs](https://officialskills.sh/openai/skills/openai-docs)** - Provide authoritative guidance from OpenAI developer documentation
* **[openai/pdf](https://officialskills.sh/openai/skills/pdf)** - Read, create, and review PDFs with layout and visual formatting integrity
* **[openai/playwright](https://officialskills.sh/openai/skills/playwright)** - Automate real browser interactions for navigation, forms, and scraping
* **[openai/render-deploy](https://officialskills.sh/openai/skills/render-deploy)** - Deploy applications to Render's cloud platform using Git-backed services
* **[openai/screenshot](https://officialskills.sh/openai/skills/screenshot)** - Capture desktop, app windows, or pixel regions across OS platforms
* **[openai/security-best-practices](https://officialskills.sh/openai/skills/security-best-practices)** - Review code for language-specific security vulnerabilities
* **[openai/security-ownership-map](https://officialskills.sh/openai/skills/security-ownership-map)** - Map people-to-file ownership, compute bus factor, and identify risks
* **[openai/security-threat-model](https://officialskills.sh/openai/skills/security-threat-model)** - Generate repo-specific threat models identifying trust boundaries
* **[openai/sentry](https://officialskills.sh/openai/skills/sentry)** - Inspect Sentry issues, summarize production errors, and pull health data
* **[openai/sora](https://officialskills.sh/openai/skills/sora)** - Generate, remix, and manage short video clips via OpenAI's Sora API
* **[openai/speech](https://officialskills.sh/openai/skills/speech)** - Generate spoken audio from text using OpenAI's API with built-in voices
* **[openai/spreadsheet](https://officialskills.sh/openai/skills/spreadsheet)** - Create, edit, analyze, and visualize spreadsheets with formulas
* **[openai/transcribe](https://officialskills.sh/openai/skills/transcribe)** - Transcribe audio files to text with optional speaker diarization
* **[openai/vercel-deploy](https://officialskills.sh/openai/skills/vercel-deploy)** - Deploy applications and websites to Vercel with preview or production options
* **[openai/yeet](https://officialskills.sh/openai/skills/yeet)** - Stage, commit, push code, and open a GitHub pull request via CLI
* **[openai/aspnet-core](https://officialskills.sh/openai/skills/aspnet-core)** - Build, review, and architect ASP.NET Core apps (Blazor, MVC, Minimal APIs, etc.)
* **[openai/chatgpt-apps](https://officialskills.sh/openai/skills/chatgpt-apps)** - Build, scaffold, and troubleshoot ChatGPT Apps SDK apps with MCP server and widget UI
* **[openai/figma](https://officialskills.sh/openai/skills/figma)** - Use the Figma MCP server to fetch design context and translate nodes into production code
* **[openai/figma-code-connect-components](https://officialskills.sh/openai/skills/figma-code-connect-components)** - Connect Figma design components to code components using Code Connect
* **[openai/figma-create-design-system-rules](https://officialskills.sh/openai/skills/figma-create-design-system-rules)** - Rules for implementing Figma designs using the Figma MCP server
* **[openai/figma-create-new-file](https://officialskills.sh/openai/skills/figma-create-new-file)** - Create a new blank Figma file or FigJam file
* **[openai/figma-generate-design](https://officialskills.sh/openai/skills/figma-generate-design)** - Translate app pages and layouts into Figma using design system tokens
* **[openai/figma-generate-library](https://officialskills.sh/openai/skills/figma-generate-library)** - Build or update a professional-grade design system in Figma from a codebase
* **[openai/figma-implement-design](https://officialskills.sh/openai/skills/figma-implement-design)** - Translate Figma designs into production-ready code with 1:1 visual fidelity
* **[openai/figma-use](https://officialskills.sh/openai/skills/figma-use)** - Prerequisite skill for every use\_figma tool call — write/read actions in Figma context
* **[openai/frontend-skill](https://officialskills.sh/openai/skills/frontend-skill)** - Create visually strong landing pages, websites, and app UIs with restrained composition
* **[openai/playwright-interactive](https://officialskills.sh/openai/skills/playwright-interactive)** - Persistent browser and Electron interaction via js\_repl for iterative UI debugging
* **[openai/slides](https://officialskills.sh/openai/skills/slides)** - Create and edit .pptx presentation decks with PptxGenJS
* **[openai/winui-app](https://officialskills.sh/openai/skills/winui-app)** - Bootstrap and develop modern WinUI 3 desktop apps with C# and Windows App SDK

</details>

<details>
<summary><h3 style="display:inline">Skills by Figma</h3></summary>

Official skills from Figma's MCP server guide.

* **[figma/figma-code-connect-components](https://officialskills.sh/figma/skills/figma-code-connect-components)** - Connect Figma design components to code components using Code Connect
* **[figma/figma-create-design-system-rules](https://officialskills.sh/figma/skills/figma-create-design-system-rules)** - Generate project-specific design system rules for Figma-to-code workflows
* **[figma/figma-create-new-file](https://officialskills.sh/figma/skills/figma-create-new-file)** - Create a new blank Figma Design or FigJam file
* **[figma/figma-generate-design](https://officialskills.sh/figma/skills/figma-generate-design)** - Build or update screens in Figma from code or description using design system components
* **[figma/figma-generate-library](https://officialskills.sh/figma/skills/figma-generate-library)** - Build or update a design system library in Figma from a codebase
* **[figma/figma-implement-design](https://officialskills.sh/figma/skills/figma-implement-design)** - Translate Figma designs into production-ready application code with 1:1 fidelity
* **[figma/figma-use](https://officialskills.sh/figma/skills/figma-use)** - Run Figma Plugin API scripts for canvas writes, inspections, variables, and design-system work

</details>

<details>
<summary><h3 style="display:inline">Marketing Skills by Corey Haines</h3></summary>

Official marketing skills by [Corey Haines](https://github.com/coreyhaines31), covering the full SaaS marketing stack from SEO and copywriting to growth, CRO, and paid acquisition.

* **[coreyhaines31/ab-testing](https://github.com/coreyhaines31/marketingskills/tree/main/skills/ab-testing) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Plan and implement A/B tests or experiments for any digital experience
* **[coreyhaines31/ad-creative](https://github.com/coreyhaines31/marketingskills/tree/main/skills/ad-creative) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Generate and iterate ad creative including headlines, descriptions, and primary text
* **[coreyhaines31/ai-seo](https://github.com/coreyhaines31/marketingskills/tree/main/skills/ai-seo) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Optimize content to appear in AI-generated answers and LLM search results
* **[coreyhaines31/analytics](https://github.com/coreyhaines31/marketingskills/tree/main/skills/analytics) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Set up and audit analytics tracking and measurement pipelines
* **[coreyhaines31/churn-prevention](https://github.com/coreyhaines31/marketingskills/tree/main/skills/churn-prevention) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Build cancellation flows, save offers, and recover failed payments
* **[coreyhaines31/cold-email](https://github.com/coreyhaines31/marketingskills/tree/main/skills/cold-email) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Write B2B cold emails and follow-up sequences that convert
* **[coreyhaines31/competitors](https://github.com/coreyhaines31/marketingskills/tree/main/skills/competitors) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Build competitor comparison and alternative landing pages for SEO
* **[coreyhaines31/content-strategy](https://github.com/coreyhaines31/marketingskills/tree/main/skills/content-strategy) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Plan content strategy and decide what topics and formats to prioritize
* **[coreyhaines31/copy-editing](https://github.com/coreyhaines31/marketingskills/tree/main/skills/copy-editing) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Edit and improve existing marketing copy for clarity and impact
* **[coreyhaines31/copywriting](https://github.com/coreyhaines31/marketingskills/tree/main/skills/copywriting) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Write and rewrite marketing copy for landing pages, homepages, and ads
* **[coreyhaines31/emails](https://github.com/coreyhaines31/marketingskills/tree/main/skills/emails) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Build email sequences, drip campaigns, and lifecycle email flows
* **[coreyhaines31/free-tools](https://github.com/coreyhaines31/marketingskills/tree/main/skills/free-tools) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Plan and build free tools for lead generation and SEO value
* **[coreyhaines31/launch](https://github.com/coreyhaines31/marketingskills/tree/main/skills/launch) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Plan product launches, feature announcements, and go-to-market strategies
* **[coreyhaines31/marketing-ideas](https://github.com/coreyhaines31/marketingskills/tree/main/skills/marketing-ideas) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Generate marketing strategies and campaign ideas for SaaS products
* **[coreyhaines31/marketing-psychology](https://github.com/coreyhaines31/marketingskills/tree/main/skills/marketing-psychology) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Apply psychological principles and behavioral science to copy and design
* **[coreyhaines31/onboarding](https://github.com/coreyhaines31/marketingskills/tree/main/skills/onboarding) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Optimize post-signup onboarding and user activation to improve time-to-value
* **[coreyhaines31/cro](https://github.com/coreyhaines31/marketingskills/tree/main/skills/cro) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Improve conversion rates on any marketing page or form, including homepages, landing pages, and contact forms
* **[coreyhaines31/ads](https://github.com/coreyhaines31/marketingskills/tree/main/skills/ads) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Create and optimize paid campaigns on Google, Meta, LinkedIn, and more
* **[coreyhaines31/paywalls](https://github.com/coreyhaines31/marketingskills/tree/main/skills/paywalls) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Design and optimize upgrade screens, paywalls, and upsell modals
* **[coreyhaines31/popups](https://github.com/coreyhaines31/marketingskills/tree/main/skills/popups) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Create and optimize popups, modals, and slide-ins for conversions
* **[coreyhaines31/pricing](https://github.com/coreyhaines31/marketingskills/tree/main/skills/pricing) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Define pricing, packaging, and monetization strategy for SaaS products
* **[coreyhaines31/product-marketing](https://github.com/coreyhaines31/marketingskills/tree/main/skills/product-marketing) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Create and maintain a product marketing context document for consistent messaging
* **[coreyhaines31/programmatic-seo](https://github.com/coreyhaines31/marketingskills/tree/main/skills/programmatic-seo) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Build SEO-driven page templates for large-scale content generation
* **[coreyhaines31/referrals](https://github.com/coreyhaines31/marketingskills/tree/main/skills/referrals) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Design and optimize referral, affiliate, and word-of-mouth programs
* **[coreyhaines31/revops](https://github.com/coreyhaines31/marketingskills/tree/main/skills/revops) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Streamline revenue operations, lead lifecycle, and marketing-to-sales handoff
* **[coreyhaines31/sales-enablement](https://github.com/coreyhaines31/marketingskills/tree/main/skills/sales-enablement) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Create pitch decks, one-pagers, objection handling docs, and demo scripts
* **[coreyhaines31/schema](https://github.com/coreyhaines31/marketingskills/tree/main/skills/schema) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Add and optimize schema markup and structured data for better SEO
* **[coreyhaines31/seo-audit](https://github.com/coreyhaines31/marketingskills/tree/main/skills/seo-audit) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Audit and diagnose technical and on-page SEO issues on a site
* **[coreyhaines31/signup](https://github.com/coreyhaines31/marketingskills/tree/main/skills/signup) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Optimize signup, registration, and trial activation flows for higher conversion
* **[coreyhaines31/site-architecture](https://github.com/coreyhaines31/marketingskills/tree/main/skills/site-architecture) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Plan and restructure page hierarchy, navigation, and URL structure
* **[coreyhaines31/social](https://github.com/coreyhaines31/marketingskills/tree/main/skills/social) ⭐ 50,766 | 🐛 114 | 🌐 JavaScript | 📅 2026-09-05** - Create and schedule social media content for LinkedIn, Twitter/X, and Instagram

</details>

<details>
<summary><h3 style="display:inline">Advertising Skills by Kim Barrett</h3></summary>

Direct-response advertising skills by Kim Barrett, organized into foundations, copy-chief, operator-os, orchestrators, and QA — covering avatar work, offer design, Schwartz-style copywriting, creative testing, and full-funnel campaign orchestration.

* **[realkimbarrett/avatar-extraction](https://github.com/realkimbarrett/advertising-skills/tree/main/skills/foundations/avatar-extraction) ⭐ 752 | 🐛 2 | 📅 2026-03-26** - Define exactly who the buyer is, what they want, what they've tried, and what's driving their decisions
* **[realkimbarrett/offer-extraction](https://github.com/realkimbarrett/advertising-skills/tree/main/skills/foundations/offer-extraction) ⭐ 752 | 🐛 2 | 📅 2026-03-26** - Turn a product or service into a compelling, high-converting offer
* **[realkimbarrett/schwartz-awareness-mapper](https://github.com/realkimbarrett/advertising-skills/tree/main/skills/copy-chief/schwartz-awareness-mapper) ⭐ 752 | 🐛 2 | 📅 2026-03-26** - Determine audience awareness level and the correct messaging approach
* **[realkimbarrett/mechanism-builder](https://github.com/realkimbarrett/advertising-skills/tree/main/skills/copy-chief/mechanism-builder) ⭐ 752 | 🐛 2 | 📅 2026-03-26** - Explain why your solution works and others failed with a unique mechanism
* **[realkimbarrett/headline-matrix](https://github.com/realkimbarrett/advertising-skills/tree/main/skills/copy-chief/headline-matrix) ⭐ 752 | 🐛 2 | 📅 2026-03-26** - Generate high-performing headline variations across different angles
* **[realkimbarrett/objection-crusher](https://github.com/realkimbarrett/advertising-skills/tree/main/skills/copy-chief/objection-crusher) ⭐ 752 | 🐛 2 | 📅 2026-03-26** - Identify and neutralize buyer objections and hesitation
* **[realkimbarrett/ad-angle-multiplier](https://github.com/realkimbarrett/advertising-skills/tree/main/skills/operator-os/ad-angle-multiplier) ⭐ 752 | 🐛 2 | 📅 2026-03-26** - Expand a core idea into multiple distinct ad angles for creative testing
* **[realkimbarrett/scroll-stopping-creative](https://github.com/realkimbarrett/advertising-skills/tree/main/skills/operator-os/scroll-stopping-creative) ⭐ 752 | 🐛 2 | 📅 2026-03-26** - Create ad concepts that stop attention in the first 3 seconds
* **[realkimbarrett/conversion-path-builder](https://github.com/realkimbarrett/advertising-skills/tree/main/skills/operator-os/conversion-path-builder) ⭐ 752 | 🐛 2 | 📅 2026-03-26** - Design the optimal funnel from click to conversion and booked calls
* **[realkimbarrett/performance-diagnosis](https://github.com/realkimbarrett/advertising-skills/tree/main/skills/operator-os/performance-diagnosis) ⭐ 752 | 🐛 2 | 📅 2026-03-26** - Diagnose why campaigns are underperforming — low conversion, high CPL, bad ads
* **[realkimbarrett/full-funnel-campaign-orchestrator](https://github.com/realkimbarrett/advertising-skills/tree/main/skills/orchestrators/full-funnel-campaign-orchestrator) ⭐ 752 | 🐛 2 | 📅 2026-03-26** - Coordinate all skills to build a complete ads + funnel campaign end-to-end
* **[realkimbarrett/generic-language-killer](https://github.com/realkimbarrett/advertising-skills/tree/main/skills/qa/generic-language-killer) ⭐ 752 | 🐛 2 | 📅 2026-03-26** - Remove vague, corporate, or AI-sounding language and replace it with clear, specific, human wording

</details>

<details>
<summary><h3 style="display:inline">Skills by Binance</h3></summary>

Official Web3 and trading skills from the Binance team. Includes crypto market data, on-chain analytics, token security auditing, and spot trading via the Binance API.

* **[binance/crypto-market-rank](https://officialskills.sh/binance/skills/crypto-market-rank)** - Query crypto market rankings including trending tokens, smart money inflows, meme rankings, and top trader PnL leaderboards
* **[binance/meme-rush](https://officialskills.sh/binance/skills/meme-rush)** - Track real-time meme token lists from launchpads (Pump.fun, Four.meme) and AI-powered hot market topics ranked by net inflow
* **[binance/query-address-info](https://officialskills.sh/binance/skills/query-address-info)** - Retrieve all token holdings and portfolio positions for any wallet address on BSC, Base, or Solana
* **[binance/query-token-audit](https://officialskills.sh/binance/skills/query-token-audit)** - Audit token security to detect scams, honeypots, and malicious contracts across BSC, Base, Solana, and Ethereum
* **[binance/query-token-info](https://officialskills.sh/binance/skills/query-token-info)** - Search tokens and fetch metadata, real-time market data, and K-Line candlestick charts by keyword or contract address
* **[binance/trading-signal](https://officialskills.sh/binance/skills/trading-signal)** - Monitor on-chain Smart Money buy/sell signals with price, max gain, and exit rate data on Solana and BSC
* **[binance/spot](https://officialskills.sh/binance/skills/spot)** - Place and manage spot trading orders on Binance via API key authentication, supporting mainnet and testnet

</details>

<details>
<summary><h3 style="display:inline">Skills by Apollo GraphQL</h3></summary>

Official skills from the Apollo GraphQL team for building GraphQL clients, servers, federated supergraphs, and the Apollo Router.

* **[apollographql/apollo-client](https://officialskills.sh/apollographql/skills/apollo-client)** - Build React applications with Apollo Client 4
* **[apollographql/apollo-connectors](https://officialskills.sh/apollographql/skills/apollo-connectors)** - Integrate REST APIs into GraphQL supergraphs using Apollo Connectors
* **[apollographql/apollo-federation](https://officialskills.sh/apollographql/skills/apollo-federation)** - Write Apollo Federation 2 subgraph schemas and compose them into a supergraph
* **[apollographql/apollo-kotlin](https://officialskills.sh/apollographql/skills/apollo-kotlin)** - A GraphQL client for Android, JVM, and Kotlin Multiplatform projects
* **[apollographql/apollo-mcp-server](https://officialskills.sh/apollographql/skills/apollo-mcp-server)** - Connect AI agents to GraphQL APIs through the Model Context Protocol
* **[apollographql/apollo-router](https://officialskills.sh/apollographql/skills/apollo-router)** - Version-aware configuration generator for the Rust-based Apollo Router
* **[apollographql/apollo-router-plugin-creator](https://officialskills.sh/apollographql/skills/apollo-router-plugin-creator)** - Write native Rust plugins for Apollo Router
* **[apollographql/apollo-server](https://officialskills.sh/apollographql/skills/apollo-server)** - Build GraphQL servers using Apollo Server 5
* **[apollographql/graphql-operations](https://officialskills.sh/apollographql/skills/graphql-operations)** - Write GraphQL queries, mutations, and subscriptions following best practices
* **[apollographql/graphql-schema](https://officialskills.sh/apollographql/skills/graphql-schema)** - Reference guide for designing clean, evolvable GraphQL schemas
* **[apollographql/rover](https://officialskills.sh/apollographql/skills/rover)** - CLI tool for managing GraphQL schemas in Apollo GraphOS
* **[apollographql/rust-best-practices](https://officialskills.sh/apollographql/skills/rust-best-practices)** - Rust coding guidelines drawn from Apollo GraphQL's internal handbook
* **[apollographql/skill-creator](https://officialskills.sh/apollographql/skills/skill-creator)** - Create and structure Agent Skills focused on Apollo GraphQL

</details>

<details>
<summary><h3 style="display:inline">Skills by Auth0</h3></summary>

Official authentication and identity skills from the Auth0 team. Covers SDKs for popular frameworks plus workflows for MFA, migration, and quickstart detection.

* **[auth0/auth0-android](https://officialskills.sh/auth0/skills/auth0-android)** - Add authentication to native Android apps using the Auth0 SDK
* **[auth0/auth0-angular](https://officialskills.sh/auth0/skills/auth0-angular)** - Add authentication to Angular apps using @auth0/auth0-angular
* **[auth0/auth0-aspnetcore-api](https://officialskills.sh/auth0/skills/auth0-aspnetcore-api)** - Add JWT access token validation to ASP.NET Core APIs
* **[auth0/auth0-express](https://officialskills.sh/auth0/skills/auth0-express)** - Add session-based authentication to Express.js apps
* **[auth0/auth0-fastify](https://officialskills.sh/auth0/skills/auth0-fastify)** - Add session-based authentication to Fastify web apps
* **[auth0/auth0-fastify-api](https://officialskills.sh/auth0/skills/auth0-fastify-api)** - Secure Fastify API endpoints with JWT Bearer token validation
* **[auth0/auth0-mfa](https://officialskills.sh/auth0/skills/auth0-mfa)** - Add Multi-Factor Authentication to Auth0-powered apps
* **[auth0/auth0-migration](https://officialskills.sh/auth0/skills/auth0-migration)** - Migrate users and auth flows from other providers to Auth0
* **[auth0/auth0-nextjs](https://officialskills.sh/auth0/skills/auth0-nextjs)** - Add authentication to Next.js apps
* **[auth0/auth0-nuxt](https://officialskills.sh/auth0/skills/auth0-nuxt)** - Add Auth0 authentication to Nuxt 3/4 apps with encrypted cookie sessions
* **[auth0/auth0-quickstart](https://officialskills.sh/auth0/skills/auth0-quickstart)** - Detect your framework and scaffold Auth0 integration automatically
* **[auth0/auth0-react](https://officialskills.sh/auth0/skills/auth0-react)** - Add authentication to React SPAs using @auth0/auth0-react
* **[auth0/auth0-react-native](https://officialskills.sh/auth0/skills/auth0-react-native)** - Add authentication to React Native and Expo mobile apps
* **[auth0/auth0-vue](https://officialskills.sh/auth0/skills/auth0-vue)** - Add authentication to Vue.js apps

</details>

<details>
<summary><h3 style="display:inline">Skills by Brave</h3></summary>

Official skills from the Brave team for accessing Brave Search APIs including web, images, videos, news, and local point-of-interest data.

* **[brave/answers](https://officialskills.sh/brave/skills/answers)** - AI-generated answers grounded in live web search results
* **[brave/bx](https://officialskills.sh/brave/skills/bx)** - CLI tool for web search built for AI agents
* **[brave/images-search](https://officialskills.sh/brave/skills/images-search)** - Search for images using the Brave Search API
* **[brave/llm-context](https://officialskills.sh/brave/skills/llm-context)** - Return pre-extracted web content (text, tables, code) from Brave Search
* **[brave/local-descriptions](https://officialskills.sh/brave/skills/local-descriptions)** - Fetch AI-generated text descriptions for points of interest
* **[brave/local-pois](https://officialskills.sh/brave/skills/local-pois)** - Retrieve detailed local business and POI information
* **[brave/news-search](https://officialskills.sh/brave/skills/news-search)** - Search Brave's news index with article metadata
* **[brave/spellcheck](https://officialskills.sh/brave/skills/spellcheck)** - Check search queries for spelling errors and get corrections
* **[brave/suggest](https://officialskills.sh/brave/skills/suggest)** - Query autocomplete suggestions via the Brave Search API
* **[brave/videos-search](https://officialskills.sh/brave/skills/videos-search)** - Search for videos across the web via the Brave Search API
* **[brave/web-search](https://officialskills.sh/brave/skills/web-search)** - Search the web via Brave's Search API with ranked results

</details>

<details>
<summary><h3 style="display:inline">Skills by Browserbase</h3></summary>

Official browser automation skills from the Browserbase team. Covers headless browsing, cookie sync, serverless functions, and adversarial UI testing.

* **[browserbase/browser](https://officialskills.sh/browserbase/skills/browser)** - Automate web browser interactions through natural language CLI commands
* **[browserbase/browserbase-cli](https://officialskills.sh/browserbase/skills/browserbase-cli)** - CLI wrapper around the Browserbase platform
* **[browserbase/cookie-sync](https://officialskills.sh/browserbase/skills/cookie-sync)** - Export cookies from local Chrome into a Browserbase persistent context
* **[browserbase/fetch](https://officialskills.sh/browserbase/skills/fetch)** - Fetch HTML, JSON, headers, and status codes through the Browserbase API
* **[browserbase/functions](https://officialskills.sh/browserbase/skills/functions)** - Deploy browser automation scripts as serverless cloud functions
* **[browserbase/search](https://officialskills.sh/browserbase/skills/search)** - Search the web via the Browserbase API with structured results
* **[browserbase/ui-test](https://officialskills.sh/browserbase/skills/ui-test)** - Run adversarial UI tests by analyzing git diffs in a real browser

</details>

<details>
<summary><h3 style="display:inline">Skills by CodeRabbit</h3></summary>

Official AI code review skills from the CodeRabbit team.

* **[coderabbitai/autofix](https://officialskills.sh/coderabbitai/skills/autofix)** - Fetch unresolved CodeRabbit review comments from GitHub PRs and apply fixes
* **[coderabbitai/code-review](https://officialskills.sh/coderabbitai/skills/code-review)** - Run AI-powered code reviews through the CodeRabbit CLI

</details>

<details>
<summary><h3 style="display:inline">Skills by Coinbase</h3></summary>

Official wallet, payments, and trading skills from the Coinbase team. Covers USDC transfers, onchain queries, x402 paid APIs, and Base trading.

* **[coinbase/authenticate-wallet](https://officialskills.sh/coinbase/skills/authenticate-wallet)** - Handle sign-in for the Coinbase payments wallet via email OTP
* **[coinbase/fund](https://officialskills.sh/coinbase/skills/fund)** - Add USDC to a Coinbase-powered wallet through Coinbase Onramp
* **[coinbase/monetize-service](https://officialskills.sh/coinbase/skills/monetize-service)** - Scaffold an Express server that charges USDC per request using x402
* **[coinbase/pay-for-service](https://officialskills.sh/coinbase/skills/pay-for-service)** - Call paid API endpoints that use the x402 protocol with automatic USDC
* **[coinbase/query-onchain-data](https://officialskills.sh/coinbase/skills/query-onchain-data)** - Query decoded onchain data (events, tx, blocks) on Base
* **[coinbase/search-for-service](https://officialskills.sh/coinbase/skills/search-for-service)** - Search and browse the x402 bazaar marketplace
* **[coinbase/send-usdc](https://officialskills.sh/coinbase/skills/send-usdc)** - Send USDC to any Ethereum address or ENS name on Base
* **[coinbase/trade](https://officialskills.sh/coinbase/skills/trade)** - Swap and trade tokens on Base using the CDP Swap API
* **[coinbase/x402](https://officialskills.sh/coinbase/skills/x402)** - Discover and call paid API endpoints using the x402 payment protocol

</details>

<details>
<summary><h3 style="display:inline">Skills by Datadog Labs</h3></summary>

Observability skills from Datadog Labs for APM, logs, monitors, and LLM observability workflows powered by the pup CLI.

* **[datadog-labs/dd-apm](https://officialskills.sh/datadog-labs/skills/dd-apm)** - Query Datadog APM data directly from your editor
* **[datadog-labs/dd-docs](https://officialskills.sh/datadog-labs/skills/dd-docs)** - Look up Datadog documentation via the LLM-optimized docs index
* **[datadog-labs/dd-llmo-eval-bootstrap](https://officialskills.sh/datadog-labs/skills/dd-llmo-eval-bootstrap)** - Analyze production LLM traces and generate evaluators
* **[datadog-labs/dd-llmo-eval-trace-rca](https://officialskills.sh/datadog-labs/skills/dd-llmo-eval-trace-rca)** - Root-cause LLM app failures using eval traces
* **[datadog-labs/dd-llmo-experiment-analyzer](https://officialskills.sh/datadog-labs/skills/dd-llmo-experiment-analyzer)** - Analyze single or comparative LLM experiment results
* **[datadog-labs/dd-logs](https://officialskills.sh/datadog-labs/skills/dd-logs)** - Search, filter, and archive Datadog logs through pup CLI
* **[datadog-labs/dd-monitors](https://officialskills.sh/datadog-labs/skills/dd-monitors)** - Manage Datadog monitors through the pup CLI
* **[datadog-labs/dd-pup](https://officialskills.sh/datadog-labs/skills/dd-pup)** - Rust-based CLI (pup) for talking to the Datadog API

</details>

<details>
<summary><h3 style="display:inline">Skills by Firebase</h3></summary>

Official skills from the Firebase team for setup, auth, Firestore, hosting, Genkit AI SDKs, and security rule auditing.

* **[firebase/developing-genkit-dart](https://officialskills.sh/firebase/skills/developing-genkit-dart)** - Build AI apps with the Genkit Dart SDK
* **[firebase/developing-genkit-go](https://officialskills.sh/firebase/skills/developing-genkit-go)** - Build AI apps with the Genkit Go SDK
* **[firebase/developing-genkit-js](https://officialskills.sh/firebase/skills/developing-genkit-js)** - Build AI-powered apps with Firebase Genkit in Node.js
* **[firebase/firebase-ai-logic-basics](https://officialskills.sh/firebase/skills/firebase-ai-logic-basics)** - Call Gemini models from web and mobile apps via Firebase AI Logic
* **[firebase/firebase-app-hosting-basics](https://officialskills.sh/firebase/skills/firebase-app-hosting-basics)** - Deploy and manage full-stack web apps (Next.js, Angular, etc.)
* **[firebase/firebase-auth-basics](https://officialskills.sh/firebase/skills/firebase-auth-basics)** - Set up Firebase Authentication with sign-in providers
* **[firebase/firebase-basics](https://officialskills.sh/firebase/skills/firebase-basics)** - Handle Firebase CLI install, auth, and day-to-day workflow
* **[firebase/firebase-data-connect-basics](https://officialskills.sh/firebase/skills/firebase-data-connect-basics)** - Build Firebase Data Connect backends backed by Cloud SQL
* **[firebase/firebase-firestore-enterprise-native-mode](https://officialskills.sh/firebase/skills/firebase-firestore-enterprise-native-mode)** - Set up and use Firestore Enterprise Native Mode
* **[firebase/firebase-firestore-standard](https://officialskills.sh/firebase/skills/firebase-firestore-standard)** - Complete guide for Cloud Firestore Standard Edition
* **[firebase/firebase-hosting-basics](https://officialskills.sh/firebase/skills/firebase-hosting-basics)** - Deploy static sites, SPAs, and microservices to Firebase Hosting
* **[firebase/firebase-security-rules-auditor](https://officialskills.sh/firebase/skills/firebase-security-rules-auditor)** - Audit Firestore security rules and flag risky patterns

</details>

<details>
<summary><h3 style="display:inline">Skills by Flutter</h3></summary>

Official skills from the Flutter team covering layouts, state, navigation, native interop, platform setup, and testing for cross-platform Flutter apps.

* **[flutter/flutter-adding-home-screen-widgets](https://officialskills.sh/flutter/skills/flutter-adding-home-screen-widgets)** - Add home screen widgets to Flutter apps on Android and iOS
* **[flutter/flutter-animating-apps](https://officialskills.sh/flutter/skills/flutter-animating-apps)** - Implement animated effects, transitions, and motion
* **[flutter/flutter-architecting-apps](https://officialskills.sh/flutter/skills/flutter-architecting-apps)** - Structure a Flutter app using layered architecture
* **[flutter/flutter-building-forms](https://officialskills.sh/flutter/skills/flutter-building-forms)** - Build Flutter forms with validation and user input
* **[flutter/flutter-building-layouts](https://officialskills.sh/flutter/skills/flutter-building-layouts)** - Build and fix layouts using the constraint system (Row, Column, Stack)
* **[flutter/flutter-building-plugins](https://officialskills.sh/flutter/skills/flutter-building-plugins)** - Create Flutter plugins that bridge Dart with platform code
* **[flutter/flutter-caching-data](https://officialskills.sh/flutter/skills/flutter-caching-data)** - Implement offline-first caching strategies
* **[flutter/flutter-embedding-native-views](https://officialskills.sh/flutter/skills/flutter-embedding-native-views)** - Embed native Android, iOS, and macOS views in Flutter widgets
* **[flutter/flutter-handling-concurrency](https://officialskills.sh/flutter/skills/flutter-handling-concurrency)** - Run heavy work in background Dart isolates
* **[flutter/flutter-handling-http-and-json](https://officialskills.sh/flutter/skills/flutter-handling-http-and-json)** - Handle HTTP requests and JSON serialization
* **[flutter/flutter-implementing-navigation-and-routing](https://officialskills.sh/flutter/skills/flutter-implementing-navigation-and-routing)** - Handle routing, navigation, and deep linking
* **[flutter/flutter-improving-accessibility](https://officialskills.sh/flutter/skills/flutter-improving-accessibility)** - Configure Flutter for screen readers and assistive tech
* **[flutter/flutter-interoperating-with-native-apis](https://officialskills.sh/flutter/skills/flutter-interoperating-with-native-apis)** - Bridge Flutter with native platform APIs
* **[flutter/flutter-localizing-apps](https://officialskills.sh/flutter/skills/flutter-localizing-apps)** - Configure Flutter for multiple languages and regions
* **[flutter/flutter-managing-state](https://officialskills.sh/flutter/skills/flutter-managing-state)** - Manage local widget state and shared application state
* **[flutter/flutter-reducing-app-size](https://officialskills.sh/flutter/skills/flutter-reducing-app-size)** - Measure and optimize Flutter app bundle sizes
* **[flutter/flutter-setting-up-on-linux](https://officialskills.sh/flutter/skills/flutter-setting-up-on-linux)** - Set up a Linux machine for Flutter desktop development
* **[flutter/flutter-setting-up-on-macos](https://officialskills.sh/flutter/skills/flutter-setting-up-on-macos)** - Set up a macOS machine for Flutter development
* **[flutter/flutter-setting-up-on-windows](https://officialskills.sh/flutter/skills/flutter-setting-up-on-windows)** - Set up a Windows machine for Flutter development
* **[flutter/flutter-testing-apps](https://officialskills.sh/flutter/skills/flutter-testing-apps)** - Implement unit, widget, and integration tests
* **[flutter/flutter-theming-apps](https://officialskills.sh/flutter/skills/flutter-theming-apps)** - Customize Flutter app appearance through the theming system
* **[flutter/flutter-working-with-databases](https://officialskills.sh/flutter/skills/flutter-working-with-databases)** - Build a structured data layer using SQLite

</details>

<details>
<summary><h3 style="display:inline">Product Manager Skills by Dean Peters</h3></summary>

46 battle-tested product management skills by [Dean Peters](https://github.com/deanpeters). Frame problems, hunt opportunities, scaffold validation experiments, and kill bad bets fast — with frameworks from Teresa Torres, Geoffrey Moore, Amazon, MITRE, and more.

**Component Skills**

* **[deanpeters/acquisition-channel-advisor](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/acquisition-channel-advisor) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Evaluate channels using unit economics and recommend scale/test/kill decisions
* **[deanpeters/ai-shaped-readiness-advisor](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/ai-shaped-readiness-advisor) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Assess automation vs. redesign opportunities across five competencies
* **[deanpeters/altitude-horizon-framework](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/altitude-horizon-framework) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Navigate the PM→Director mindset shift covering scope, time horizons, and failure modes
* **[deanpeters/business-health-diagnostic](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/business-health-diagnostic) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Diagnose SaaS health, identify red flags, and prioritize recovery actions
* **[deanpeters/company-research](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/company-research) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Deep-dive competitor or company analysis
* **[deanpeters/customer-journey-map](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/customer-journey-map) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Map customer experience across touchpoints using the NNGroup framework
* **[deanpeters/eol-message](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/eol-message) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Communicate product or feature deprecation gracefully
* **[deanpeters/epic-hypothesis](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/epic-hypothesis) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Turn initiatives into testable hypotheses with measurable success metrics
* **[deanpeters/finance-metrics-quickref](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/finance-metrics-quickref) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Reference guide for 32+ SaaS finance metrics with formulas and benchmarks
* **[deanpeters/jobs-to-be-done](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/jobs-to-be-done) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Understand customer objectives using the JTBD framework
* **[deanpeters/pestel-analysis](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/pestel-analysis) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Analyze external factors across Political, Economic, Social, Tech, Environmental, and Legal dimensions
* **[deanpeters/pol-probe](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/pol-probe) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Define lightweight validation experiments to test hypotheses
* **[deanpeters/positioning-statement](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/positioning-statement) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Define target audience, problem solved, and differentiation using Geoffrey Moore's framework
* **[deanpeters/press-release](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/press-release) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Clarify product vision with a future press release using Amazon's Working Backwards method
* **[deanpeters/problem-statement](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/problem-statement) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Frame customer problems with evidence before jumping to solutions
* **[deanpeters/proto-persona](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/proto-persona) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Create hypothesis-driven personas before conducting full research
* **[deanpeters/recommendation-canvas](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/recommendation-canvas) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Document AI-powered product recommendations
* **[deanpeters/saas-economics-efficiency-metrics](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/saas-economics-efficiency-metrics) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Calculate unit economics and capital efficiency including CAC, LTV, payback, and Rule of 40
* **[deanpeters/saas-revenue-growth-metrics](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/saas-revenue-growth-metrics) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Track revenue, retention, and growth metrics including MRR/ARR, churn, NRR, and expansion
* **[deanpeters/storyboard](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/storyboard) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Visualize user journeys with 6-frame narrative storyboards
* **[deanpeters/user-story](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/user-story) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Write user stories with acceptance criteria using Mike Cohn and Gherkin formats
* **[deanpeters/user-story-mapping](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/user-story-mapping) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Organize stories by user workflow using Jeff Patton's story mapping approach
* **[deanpeters/user-story-splitting](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/user-story-splitting) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Break down large stories using 8 proven splitting patterns

**Interactive Skills**

* **[deanpeters/context-engineering-advisor](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/context-engineering-advisor) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Diagnose context stuffing vs. engineering and guide memory and retrieval design
* **[deanpeters/customer-journey-mapping-workshop](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/customer-journey-mapping-workshop) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Guide journey mapping sessions with pain point identification
* **[deanpeters/director-readiness-advisor](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/director-readiness-advisor) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Coach the PM→Director transition across four key situations
* **[deanpeters/discovery-interview-prep](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/discovery-interview-prep) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Plan customer interviews using Mom Test style based on research goals
* **[deanpeters/epic-breakdown-advisor](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/epic-breakdown-advisor) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Split epics into stories using Richard Lawrence's 9 splitting patterns
* **[deanpeters/feature-investment-advisor](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/feature-investment-advisor) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Evaluate features using ROI and strategic value scoring
* **[deanpeters/finance-based-pricing-advisor](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/finance-based-pricing-advisor) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Evaluate pricing changes using financial impact analysis
* **[deanpeters/lean-ux-canvas](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/lean-ux-canvas) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Set up hypothesis-driven planning using Jeff Gothelf's Lean UX Canvas v2
* **[deanpeters/opportunity-solution-tree](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/opportunity-solution-tree) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Generate opportunities and solutions and recommend proof-of-concept tests
* **[deanpeters/pol-probe-advisor](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/pol-probe-advisor) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Recommend prototype type: Feasibility, Task-Focused, Narrative, Synthetic, or Vibe
* **[deanpeters/positioning-workshop](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/positioning-workshop) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Guide positioning definition with adaptive discovery questions
* **[deanpeters/prioritization-advisor](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/prioritization-advisor) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Recommend the right prioritization framework (RICE, ICE, Kano, etc.) for your situation
* **[deanpeters/problem-framing-canvas](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/problem-framing-canvas) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Lead through MITRE Problem Framing: Look Inward, Outward, and Reframe
* **[deanpeters/tam-sam-som-calculator](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/tam-sam-som-calculator) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Project market size with real-world data and citations
* **[deanpeters/user-story-mapping-workshop](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/user-story-mapping-workshop) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Walk through creating story maps with backbone and release slices
* **[deanpeters/vp-cpo-readiness-advisor](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/vp-cpo-readiness-advisor) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Coach the Director→VP/CPO transition including a CEO interview framework
* **[deanpeters/workshop-facilitation](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/workshop-facilitation) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Add step-by-step facilitation with numbered recommendations to any workshop

**Workflow Skills**

* **[deanpeters/discovery-process](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/discovery-process) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Full discovery cycle: frame problem → research → synthesize → validate (3-4 weeks)
* **[deanpeters/executive-onboarding-playbook](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/executive-onboarding-playbook) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - 30-60-90 day diagnostic playbook for VP/CPO onboarding transitions
* **[deanpeters/prd-development](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/prd-development) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Structured PRD process: problem → personas → solution → metrics → stories (2-4 days)
* **[deanpeters/product-strategy-session](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/product-strategy-session) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Full strategy session: positioning → framing → exploration → roadmap (2-4 weeks)
* **[deanpeters/roadmap-planning](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/roadmap-planning) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Strategic roadmap process: inputs → epics → prioritize → sequence → communicate (1-2 weeks)
* **[deanpeters/skill-authoring-workflow](https://github.com/deanpeters/Product-Manager-Skills/tree/main/skills/skill-authoring-workflow) ⭐ 7,000 | 🐛 9 | 🌐 Shell | 📅 2026-09-01** - Meta workflow for authoring skills: choose path → validate → update docs → package

</details>

<details>
<summary><h3 style="display:inline">Product Management Skills by Pawel Huryn</h3></summary>

65 product management skills by [Paweł Huryn](https://github.com/phuryn), creator of The Product Compass newsletter. Covers the full PM lifecycle — from discovery and strategy to execution, analytics, and go-to-market — with frameworks from Teresa Torres, Geoffrey Moore, and more.

**Data Analytics**

* **[phuryn/ab-test-analysis](https://github.com/phuryn/pm-skills/tree/main/pm-data-analytics/skills/ab-test-analysis) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Analyze A/B test results with statistical significance and recommendations
* **[phuryn/cohort-analysis](https://github.com/phuryn/pm-skills/tree/main/pm-data-analytics/skills/cohort-analysis) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Cohort retention curves, feature adoption, and segment insights
* **[phuryn/sql-queries](https://github.com/phuryn/pm-skills/tree/main/pm-data-analytics/skills/sql-queries) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Generate SQL queries from natural language across major dialects

**Execution**

* **[phuryn/brainstorm-okrs](https://github.com/phuryn/pm-skills/tree/main/pm-execution/skills/brainstorm-okrs) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Brainstorm team OKRs aligned with company objectives
* **[phuryn/create-prd](https://github.com/phuryn/pm-skills/tree/main/pm-execution/skills/create-prd) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Create a PRD with 8-section template covering problem to release
* **[phuryn/dummy-dataset](https://github.com/phuryn/pm-skills/tree/main/pm-execution/skills/dummy-dataset) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Generate realistic dummy datasets in CSV, JSON, or SQL
* **[phuryn/job-stories](https://github.com/phuryn/pm-skills/tree/main/pm-execution/skills/job-stories) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Create job stories with acceptance criteria in JTBD format
* **[phuryn/outcome-roadmap](https://github.com/phuryn/pm-skills/tree/main/pm-execution/skills/outcome-roadmap) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Transform output roadmaps into outcome-focused strategic plans
* **[phuryn/pre-mortem](https://github.com/phuryn/pm-skills/tree/main/pm-execution/skills/pre-mortem) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Run pre-mortem risk analysis on PRDs and launch plans
* **[phuryn/prioritization-frameworks](https://github.com/phuryn/pm-skills/tree/main/pm-execution/skills/prioritization-frameworks) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Reference guide to 9 prioritization frameworks with templates
* **[phuryn/release-notes](https://github.com/phuryn/pm-skills/tree/main/pm-execution/skills/release-notes) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Generate user-facing release notes from tickets or changelogs
* **[phuryn/retro](https://github.com/phuryn/pm-skills/tree/main/pm-execution/skills/retro) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Facilitate structured sprint retrospectives with action items
* **[phuryn/sprint-plan](https://github.com/phuryn/pm-skills/tree/main/pm-execution/skills/sprint-plan) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Plan sprints with capacity, story selection, and risk mapping
* **[phuryn/stakeholder-map](https://github.com/phuryn/pm-skills/tree/main/pm-execution/skills/stakeholder-map) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Build stakeholder maps with power/interest grid and comms plan
* **[phuryn/summarize-meeting](https://github.com/phuryn/pm-skills/tree/main/pm-execution/skills/summarize-meeting) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Summarize meeting transcripts into structured notes and actions
* **[phuryn/test-scenarios](https://github.com/phuryn/pm-skills/tree/main/pm-execution/skills/test-scenarios) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Create comprehensive test scenarios from user stories
* **[phuryn/user-stories](https://github.com/phuryn/pm-skills/tree/main/pm-execution/skills/user-stories) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Create INVEST-compliant user stories with 3 C's structure
* **[phuryn/wwas](https://github.com/phuryn/pm-skills/tree/main/pm-execution/skills/wwas) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Create backlog items in Why-What-Acceptance format

**Go-to-Market**

* **[phuryn/beachhead-segment](https://github.com/phuryn/pm-skills/tree/main/pm-go-to-market/skills/beachhead-segment) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Identify the first beachhead market segment for product launch
* **[phuryn/competitive-battlecard](https://github.com/phuryn/pm-skills/tree/main/pm-go-to-market/skills/competitive-battlecard) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Create sales-ready battlecards against specific competitors
* **[phuryn/growth-loops](https://github.com/phuryn/pm-skills/tree/main/pm-go-to-market/skills/growth-loops) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Identify growth loops across 5 flywheel types for traction
* **[phuryn/gtm-motions](https://github.com/phuryn/pm-skills/tree/main/pm-go-to-market/skills/gtm-motions) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Identify best GTM motions across 7 types including PLG and ABM
* **[phuryn/gtm-strategy](https://github.com/phuryn/pm-skills/tree/main/pm-go-to-market/skills/gtm-strategy) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Create GTM strategy with channels, messaging, and launch timeline
* **[phuryn/ideal-customer-profile](https://github.com/phuryn/pm-skills/tree/main/pm-go-to-market/skills/ideal-customer-profile) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Identify ICP with demographics, behaviors, and JTBD

**Market Research**

* **[phuryn/competitor-analysis](https://github.com/phuryn/pm-skills/tree/main/pm-market-research/skills/competitor-analysis) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Analyze competitors with strengths, weaknesses, and differentiation
* **[phuryn/customer-journey-map](https://github.com/phuryn/pm-skills/tree/main/pm-market-research/skills/customer-journey-map) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Map customer journeys with touchpoints, emotions, and opportunities
* **[phuryn/market-segments](https://github.com/phuryn/pm-skills/tree/main/pm-market-research/skills/market-segments) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Identify 3-5 customer segments with JTBD and product fit
* **[phuryn/market-sizing](https://github.com/phuryn/pm-skills/tree/main/pm-market-research/skills/market-sizing) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Estimate TAM, SAM, SOM with top-down and bottom-up approaches
* **[phuryn/sentiment-analysis](https://github.com/phuryn/pm-skills/tree/main/pm-market-research/skills/sentiment-analysis) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Analyze user feedback with sentiment scores and JTBD insights
* **[phuryn/user-personas](https://github.com/phuryn/pm-skills/tree/main/pm-market-research/skills/user-personas) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Create 3 user personas with JTBD, pains, and gains
* **[phuryn/user-segmentation](https://github.com/phuryn/pm-skills/tree/main/pm-market-research/skills/user-segmentation) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Segment users by behavior, JTBD, and needs from feedback data

**Marketing & Growth**

* **[phuryn/marketing-ideas](https://github.com/phuryn/pm-skills/tree/main/pm-marketing-growth/skills/marketing-ideas) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Generate 5 creative, cost-effective marketing ideas with rationale
* **[phuryn/north-star-metric](https://github.com/phuryn/pm-skills/tree/main/pm-marketing-growth/skills/north-star-metric) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Define North Star Metric and input metrics constellation
* **[phuryn/positioning-ideas](https://github.com/phuryn/pm-skills/tree/main/pm-marketing-growth/skills/positioning-ideas) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Brainstorm positioning ideas differentiated from competitors
* **[phuryn/product-name](https://github.com/phuryn/pm-skills/tree/main/pm-marketing-growth/skills/product-name) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Brainstorm 5 memorable product names aligned to brand values
* **[phuryn/value-prop-statements](https://github.com/phuryn/pm-skills/tree/main/pm-marketing-growth/skills/value-prop-statements) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Generate value prop statements for marketing, sales, and onboarding

**Product Discovery**

* **[phuryn/analyze-feature-requests](https://github.com/phuryn/pm-skills/tree/main/pm-product-discovery/skills/analyze-feature-requests) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Prioritize feature requests by theme, impact, effort, and risk
* **[phuryn/brainstorm-experiments-existing](https://github.com/phuryn/pm-skills/tree/main/pm-product-discovery/skills/brainstorm-experiments-existing) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Design experiments to test assumptions for existing products
* **[phuryn/brainstorm-experiments-new](https://github.com/phuryn/pm-skills/tree/main/pm-product-discovery/skills/brainstorm-experiments-new) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Design lean pretotypes for new product validation
* **[phuryn/brainstorm-ideas-existing](https://github.com/phuryn/pm-skills/tree/main/pm-product-discovery/skills/brainstorm-ideas-existing) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Brainstorm product ideas from PM, Designer, Engineer perspectives
* **[phuryn/brainstorm-ideas-new](https://github.com/phuryn/pm-skills/tree/main/pm-product-discovery/skills/brainstorm-ideas-new) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Brainstorm feature ideas for new products in early discovery
* **[phuryn/identify-assumptions-existing](https://github.com/phuryn/pm-skills/tree/main/pm-product-discovery/skills/identify-assumptions-existing) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Identify risky assumptions across Value, Usability, Viability, Feasibility
* **[phuryn/identify-assumptions-new](https://github.com/phuryn/pm-skills/tree/main/pm-product-discovery/skills/identify-assumptions-new) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Identify risky assumptions for new products across 8 risk categories
* **[phuryn/interview-script](https://github.com/phuryn/pm-skills/tree/main/pm-product-discovery/skills/interview-script) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Create structured customer interview scripts with JTBD probing
* **[phuryn/metrics-dashboard](https://github.com/phuryn/pm-skills/tree/main/pm-product-discovery/skills/metrics-dashboard) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Define product metrics dashboard with sources and alert thresholds
* **[phuryn/opportunity-solution-tree](https://github.com/phuryn/pm-skills/tree/main/pm-product-discovery/skills/opportunity-solution-tree) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Build Opportunity Solution Trees based on Teresa Torres' method
* **[phuryn/prioritize-assumptions](https://github.com/phuryn/pm-skills/tree/main/pm-product-discovery/skills/prioritize-assumptions) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Prioritize assumptions with Impact × Risk matrix and experiments
* **[phuryn/prioritize-features](https://github.com/phuryn/pm-skills/tree/main/pm-product-discovery/skills/prioritize-features) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Prioritize backlog by impact, effort, risk, and strategic alignment
* **[phuryn/summarize-interview](https://github.com/phuryn/pm-skills/tree/main/pm-product-discovery/skills/summarize-interview) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Summarize interview transcripts with JTBD and action items

**Product Strategy**

* **[phuryn/ansoff-matrix](https://github.com/phuryn/pm-skills/tree/main/pm-product-strategy/skills/ansoff-matrix) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Ansoff Matrix analysis across 4 growth strategy quadrants
* **[phuryn/business-model](https://github.com/phuryn/pm-skills/tree/main/pm-product-strategy/skills/business-model) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Generate Business Model Canvas with all 9 building blocks
* **[phuryn/lean-canvas](https://github.com/phuryn/pm-skills/tree/main/pm-product-strategy/skills/lean-canvas) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Generate Lean Canvas with problem, solution, UVP, and metrics
* **[phuryn/monetization-strategy](https://github.com/phuryn/pm-skills/tree/main/pm-product-strategy/skills/monetization-strategy) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Brainstorm 3-5 monetization strategies with validation experiments
* **[phuryn/pestle-analysis](https://github.com/phuryn/pm-skills/tree/main/pm-product-strategy/skills/pestle-analysis) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - PESTLE analysis across Political, Economic, Social, Tech, Legal, Environmental
* **[phuryn/porters-five-forces](https://github.com/phuryn/pm-skills/tree/main/pm-product-strategy/skills/porters-five-forces) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Porter's Five Forces competitive analysis with strategic insights
* **[phuryn/pricing-strategy](https://github.com/phuryn/pm-skills/tree/main/pm-product-strategy/skills/pricing-strategy) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Design pricing strategies with competitive analysis and WTP estimation
* **[phuryn/product-strategy](https://github.com/phuryn/pm-skills/tree/main/pm-product-strategy/skills/product-strategy) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Create product strategy using 9-section Product Strategy Canvas
* **[phuryn/product-vision](https://github.com/phuryn/pm-skills/tree/main/pm-product-strategy/skills/product-vision) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Brainstorm inspiring, achievable product vision statements
* **[phuryn/startup-canvas](https://github.com/phuryn/pm-skills/tree/main/pm-product-strategy/skills/startup-canvas) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Generate Startup Canvas combining Product Strategy and Business Model
* **[phuryn/swot-analysis](https://github.com/phuryn/pm-skills/tree/main/pm-product-strategy/skills/swot-analysis) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - SWOT analysis with actionable recommendations per quadrant
* **[phuryn/value-proposition](https://github.com/phuryn/pm-skills/tree/main/pm-product-strategy/skills/value-proposition) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Design value propositions using 6-part JTBD template

**Toolkit**

* **[phuryn/draft-nda](https://github.com/phuryn/pm-skills/tree/main/pm-toolkit/skills/draft-nda) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Draft NDAs covering information types, jurisdiction, and clauses
* **[phuryn/grammar-check](https://github.com/phuryn/pm-skills/tree/main/pm-toolkit/skills/grammar-check) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Identify grammar and flow errors with targeted fix suggestions
* **[phuryn/privacy-policy](https://github.com/phuryn/pm-skills/tree/main/pm-toolkit/skills/privacy-policy) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - Draft privacy policies with GDPR compliance considerations
* **[phuryn/review-resume](https://github.com/phuryn/pm-skills/tree/main/pm-toolkit/skills/review-resume) ⭐ 26,424 | 🐛 41 | 📅 2026-09-14** - PM resume review against 10 best practices including XYZ+S formula

</details>

<details>
<summary><h3 style="display:inline">Skills by MiniMax Team</h3></summary>

11 development and document generation skills from the MiniMax AI team. Covers frontend, fullstack, mobile, shader development, document creation (PDF, DOCX, XLSX, PPTX), and the MiniMax AI CLI with MiniMax API integration.

* **[MiniMax-AI/cli](https://officialskills.sh/MiniMax-AI/skills/cli)** - Generate text, image, video, speech, and music via MiniMax AI
* **[MiniMax-AI/frontend-dev](https://officialskills.sh/MiniMax-AI/skills/frontend-dev)** - Full-stack frontend with cinematic animations, AI-generated media via MiniMax API, and generative art
* **[MiniMax-AI/fullstack-dev](https://officialskills.sh/MiniMax-AI/skills/fullstack-dev)** - Backend architecture with REST API design, auth flows, real-time features, and database integration
* **[MiniMax-AI/android-native-dev](https://officialskills.sh/MiniMax-AI/skills/android-native-dev)** - Android native development with Kotlin/Jetpack Compose, Material Design 3, and accessibility
* **[MiniMax-AI/ios-application-dev](https://officialskills.sh/MiniMax-AI/skills/ios-application-dev)** - iOS development with UIKit, SnapKit, and SwiftUI covering navigation, Dark Mode, and HIG compliance
* **[MiniMax-AI/shader-dev](https://officialskills.sh/MiniMax-AI/skills/shader-dev)** - GLSL shader techniques for ray marching, fluid simulation, particle systems, and procedural generation
* **[MiniMax-AI/gif-sticker-maker](https://officialskills.sh/MiniMax-AI/skills/gif-sticker-maker)** - Convert photos into animated GIF stickers in Funko Pop / Pop Mart style via MiniMax API
* **[MiniMax-AI/minimax-pdf](https://officialskills.sh/MiniMax-AI/skills/minimax-pdf)** - Generate, fill, and reformat PDFs with a token-based design system and 15 cover styles
* **[MiniMax-AI/pptx-generator](https://officialskills.sh/MiniMax-AI/skills/pptx-generator)** - Create and edit PowerPoint presentations from scratch with PptxGenJS
* **[MiniMax-AI/minimax-xlsx](https://officialskills.sh/MiniMax-AI/skills/minimax-xlsx)** - Create, read, analyze, and validate Excel/spreadsheet files with zero format loss
* **[MiniMax-AI/minimax-docx](https://officialskills.sh/MiniMax-AI/skills/minimax-docx)** - Professional DOCX document creation and editing using OpenXML SDK

</details>

<details>
<summary><h3 style="display:inline">Skills by DuckDB</h3></summary>

Official DuckDB skills for data querying, file reading, and documentation search directly from Claude Code.

* **[duckdb/attach-db](https://officialskills.sh/duckdb/skills/attach-db)** - Attach a DuckDB database file for interactive querying with automatic schema exploration
* **[duckdb/query](https://officialskills.sh/duckdb/skills/query)** - Run SQL queries against attached databases or ad-hoc against files using Friendly SQL dialect
* **[duckdb/read-file](https://officialskills.sh/duckdb/skills/read-file)** - Read any data file (CSV, JSON, Parquet, Avro, Excel, spatial) locally or from remote storage
* **[duckdb/duckdb-docs](https://officialskills.sh/duckdb/skills/duckdb-docs)** - Search DuckDB and DuckLake documentation using full-text search over HTTPS
* **[duckdb/read-memories](https://officialskills.sh/duckdb/skills/read-memories)** - Search past Claude Code session logs to recover context from previous conversations
* **[duckdb/install-duckdb](https://officialskills.sh/duckdb/skills/install-duckdb)** - Install or update DuckDB CLI and extensions with version management

</details>

<details>
<summary><h3 style="display:inline">Skills by GSAP (GreenSock)</h3></summary>

Official GSAP animation skills covering the full GreenSock ecosystem — core API, timelines, ScrollTrigger, plugins, utilities, React integration, performance optimization, and framework support.

* **[greensock/gsap-core](https://officialskills.sh/greensock/skills/gsap-core)** - Core API with gsap.to(), from(), fromTo(), easing, duration, stagger, and defaults
* **[greensock/gsap-timeline](https://officialskills.sh/greensock/skills/gsap-timeline)** - Timelines with sequencing, position parameter, labels, nesting, and playback control
* **[greensock/gsap-scrolltrigger](https://officialskills.sh/greensock/skills/gsap-scrolltrigger)** - ScrollTrigger for scroll-linked animations, pinning, scrub, and refresh handling
* **[greensock/gsap-plugins](https://officialskills.sh/greensock/skills/gsap-plugins)** - Plugins including ScrollToPlugin, Flip, Draggable, SplitText, SVG, and physics
* **[greensock/gsap-utils](https://officialskills.sh/greensock/skills/gsap-utils)** - Utility functions like clamp, mapRange, interpolate, snap, selector, and wrap
* **[greensock/gsap-react](https://officialskills.sh/greensock/skills/gsap-react)** - React integration with useGSAP hook, refs, gsap.context(), cleanup, and SSR
* **[greensock/gsap-performance](https://officialskills.sh/greensock/skills/gsap-performance)** - Performance tips for transforms, will-change, batching, and ScrollTrigger optimization
* **[greensock/gsap-frameworks](https://officialskills.sh/greensock/skills/gsap-frameworks)** - Vue, Svelte, and other frameworks with lifecycle, scoping, and cleanup patterns

</details>

<details>
<summary><h3 style="display:inline">Skills by Garry Tan (gstack)</h3></summary>

28 skills by [Garry Tan](https://github.com/garrytan) (Y Combinator CEO) that transform Claude Code into a virtual engineering team — structured workflows from ideation to production deployment. Ships 600K+ lines of production code in 60 days.

* **[garrytan/office-hours](https://officialskills.sh/garrytan/skills/office-hours)** - YC Office Hours: six forcing questions that reframe your product before you write code
* **[garrytan/plan-ceo-review](https://officialskills.sh/garrytan/skills/plan-ceo-review)** - CEO/Founder plan review with four modes: Expansion, Selective Expansion, Hold Scope, Reduction
* **[garrytan/plan-eng-review](https://officialskills.sh/garrytan/skills/plan-eng-review)** - Eng Manager review: lock in architecture, data flow, diagrams, edge cases, and tests
* **[garrytan/plan-design-review](https://officialskills.sh/garrytan/skills/plan-design-review)** - Senior Designer review: rates each design dimension 0-10, explains what a 10 looks like, AI Slop detection
* **[garrytan/design-consultation](https://officialskills.sh/garrytan/skills/design-consultation)** - Build a complete design system from scratch with creative risks and realistic product mockups
* **[garrytan/design-review](https://officialskills.sh/garrytan/skills/design-review)** - Designer Who Codes: visual audit then fixes with atomic commits and before/after screenshots
* **[garrytan/review](https://officialskills.sh/garrytan/skills/review)** - Staff Engineer code review: finds bugs that pass CI but blow up in production
* **[garrytan/investigate](https://officialskills.sh/garrytan/skills/investigate)** - Systematic root-cause debugging: no fixes without investigation, traces data flow, tests hypotheses
* **[garrytan/qa](https://officialskills.sh/garrytan/skills/qa)** - QA Lead: test your app, find bugs, fix them with atomic commits, auto-generate regression tests
* **[garrytan/qa-only](https://officialskills.sh/garrytan/skills/qa-only)** - QA Reporter: same methodology as /qa but report only, no code changes
* **[garrytan/cso](https://officialskills.sh/garrytan/skills/cso)** - Chief Security Officer: OWASP Top 10 + STRIDE threat model with zero false-positive exclusions
* **[garrytan/ship](https://officialskills.sh/garrytan/skills/ship)** - Release Engineer: sync main, run tests, audit coverage, push, open PR
* **[garrytan/land-and-deploy](https://officialskills.sh/garrytan/skills/land-and-deploy)** - Merge the PR, wait for CI and deploy, verify production health
* **[garrytan/canary](https://officialskills.sh/garrytan/skills/canary)** - SRE post-deploy monitoring: watches for console errors, performance regressions, and page failures
* **[garrytan/benchmark](https://officialskills.sh/garrytan/skills/benchmark)** - Performance Engineer: baseline page load times, Core Web Vitals, and resource sizes
* **[garrytan/document-release](https://officialskills.sh/garrytan/skills/document-release)** - Technical Writer: update all project docs to match what you just shipped
* **[garrytan/retro](https://officialskills.sh/garrytan/skills/retro)** - Eng Manager weekly retro with per-person breakdowns and shipping streaks
* **[garrytan/browse](https://officialskills.sh/garrytan/skills/browse)** - Real Chromium browser for QA: real clicks, real screenshots, \~100ms per command
* **[garrytan/setup-browser-cookies](https://officialskills.sh/garrytan/skills/setup-browser-cookies)** - Import cookies from your real browser into the headless session
* **[garrytan/autoplan](https://officialskills.sh/garrytan/skills/autoplan)** - One command, fully reviewed plan: runs CEO → design → eng review automatically
* **[garrytan/codex](https://officialskills.sh/garrytan/skills/codex)** - Second Opinion via OpenAI Codex CLI: review, adversarial challenge, and open consultation
* **[garrytan/careful](https://officialskills.sh/garrytan/skills/careful)** - Safety Guardrails: warns before destructive commands (rm -rf, DROP TABLE, force-push)
* **[garrytan/freeze](https://officialskills.sh/garrytan/skills/freeze)** - Edit Lock: restrict file edits to one directory while debugging
* **[garrytan/guard](https://officialskills.sh/garrytan/skills/guard)** - Full Safety: /careful + /freeze in one command for maximum safety
* **[garrytan/unfreeze](https://officialskills.sh/garrytan/skills/unfreeze)** - Unlock: remove the /freeze boundary
* **[garrytan/setup-deploy](https://officialskills.sh/garrytan/skills/setup-deploy)** - Deploy Configurator: one-time setup for /land-and-deploy
* **[garrytan/gstack-upgrade](https://officialskills.sh/garrytan/skills/gstack-upgrade)** - Self-Updater: upgrade gstack to latest version

</details>

<details>
<summary><h3 style="display:inline">Skills by Notion</h3></summary>

Official skills from Notion's repositories — workspace-aware skills for capturing knowledge, preparing meetings, researching, and turning specs into tasks.

**From [notion-cookbook](https://github.com/makenotion/notion-cookbook/tree/main/skills/claude) ⭐ 210 | 🐛 18 | 🌐 TypeScript | 📅 2026-09-17:**

* **[makenotion/knowledge-capture](https://officialskills.sh/makenotion/skills/knowledge-capture)** - Transform conversations into structured Notion documentation pages with proper organization and linking
* **[makenotion/meeting-intelligence](https://officialskills.sh/makenotion/skills/meeting-intelligence)** - Prepare meeting materials by gathering Notion context and creating pre-reads and agendas
* **[makenotion/research-documentation](https://officialskills.sh/makenotion/skills/research-documentation)** - Search Notion workspace, synthesize findings, and create comprehensive research reports
* **[makenotion/spec-to-implementation](https://officialskills.sh/makenotion/skills/spec-to-implementation)** - Turn product/tech specs into concrete Notion tasks with acceptance criteria and progress tracking

**From [claude-code-notion-plugin](https://github.com/makenotion/claude-code-notion-plugin/tree/main/skills/notion) ⭐ 482 | 🐛 20 | 📅 2026-01-22:**

* **[makenotion/knowledge-capture](https://officialskills.sh/makenotion/skills/knowledge-capture)** - Transform conversations into structured Notion documentation pages with proper organization and linking
* **[makenotion/meeting-intelligence](https://officialskills.sh/makenotion/skills/meeting-intelligence)** - Prepare meeting materials by gathering Notion context and creating pre-reads and agendas
* **[makenotion/research-documentation](https://officialskills.sh/makenotion/skills/research-documentation)** - Search Notion workspace, synthesize findings, and create comprehensive research reports
* **[makenotion/spec-to-implementation](https://officialskills.sh/makenotion/skills/spec-to-implementation)** - Turn product/tech specs into concrete Notion tasks with acceptance criteria and progress tracking

</details>

<details>
<summary><h3 style="display:inline">Skills by Resend</h3></summary>

Official Resend skills to send and receive emails, build email templates and power your agent with email expertise.

* **[resend/resend](https://github.com/resend/resend-skills/tree/main/skills/resend) ⭐ 177 | 🐛 5 | 🌐 JavaScript | 📅 2026-09-14** - Send and manage emails via the Resend API
* **[resend/react-email](https://github.com/resend/resend-skills/tree/main/skills/react-email) ⭐ 177 | 🐛 5 | 🌐 JavaScript | 📅 2026-09-14** - Build emails with React Email components
* **[resend/email-best-practices](https://github.com/resend/resend-skills/tree/main/skills/email-best-practices) ⭐ 177 | 🐛 5 | 🌐 JavaScript | 📅 2026-09-14** - Email deliverability and design best practices
* **[resend/agent-email-inbox](https://github.com/resend/resend-skills/tree/main/skills/agent-email-inbox) ⭐ 177 | 🐛 5 | 🌐 JavaScript | 📅 2026-09-14** - AI agent email inbox management
* **[resend/resend-cli](https://github.com/resend/resend-skills/tree/main/skills/resend-cli) ⭐ 177 | 🐛 5 | 🌐 JavaScript | 📅 2026-09-14** - Resend CLI commands and workflows

</details>

<details>
<summary><h3 style="display:inline">Skills by - Google Chrome team - Addy Osmani (Web Quality)</h3></summary>

Lighthouse-style web quality skills from Addy Osmani(Google Chrome team) covering performance, Core Web Vitals, accessibility, SEO, and modern best practices — the same pillars Google Lighthouse audits.

* **[addyosmani/web-quality-audit](https://officialskills.sh/addyosmani/skills/web-quality-audit)** - Comprehensive quality review across performance, accessibility, SEO, and best practices categories
* **[addyosmani/performance](https://officialskills.sh/addyosmani/skills/performance)** - Loading speed, runtime efficiency, and resource optimization
* **[addyosmani/core-web-vitals](https://officialskills.sh/addyosmani/skills/core-web-vitals)** - LCP, INP, and CLS-specific optimizations
* **[addyosmani/accessibility](https://officialskills.sh/addyosmani/skills/accessibility)** - WCAG compliance, screen reader support, and keyboard navigation
* **[addyosmani/seo](https://officialskills.sh/addyosmani/skills/seo)** - Search engine optimization, crawlability, and structured data
* **[addyosmani/best-practices](https://officialskills.sh/addyosmani/skills/best-practices)** - Security, modern web APIs, and code quality patterns

</details>

<details>
<summary><h3 style="display:inline">Skills by MongoDB</h3></summary>

Official MongoDB Agent Skills for agentic workflows — connection management, schema design, query optimization, natural language querying, and Atlas Stream Processing.

* **[mongodb/mongodb-mcp-setup](https://officialskills.sh/mongodb/skills/mongodb-mcp-setup)** - Set up the MongoDB MCP server with authentication and connection configuration
* **[mongodb/mongodb-connection](https://officialskills.sh/mongodb/skills/mongodb-connection)** - Optimize MongoDB client connection pools, timeouts, and serverless patterns
* **[mongodb/mongodb-schema-design](https://officialskills.sh/mongodb/skills/mongodb-schema-design)** - Design efficient document schemas with validation and indexing patterns
* **[mongodb/atlas-stream-processing](https://officialskills.sh/mongodb/skills/atlas-stream-processing)** - Build, operate, and debug Atlas Stream Processing pipelines with Kafka, S3, and Lambda integrations
* **[mongodb/mongodb-natural-language-querying](https://officialskills.sh/mongodb/skills/mongodb-natural-language-querying)** - Translate natural language into MongoDB queries and aggregation pipelines
* **[mongodb/mongodb-query-optimizer](https://officialskills.sh/mongodb/skills/mongodb-query-optimizer)** - Analyze and optimize query performance using Atlas Performance Advisor
* **[mongodb/mongodb-search-and-ai](https://officialskills.sh/mongodb/skills/mongodb-search-and-ai)** - Implement Atlas Search and AI-powered recommendations with vector search

</details>

<details>
<summary><h3 style="display:inline">Skills by Redis</h3></summary>

* **[redis/redis-core](https://github.com/redis/agent-skills/tree/main/skills/redis-core) ⭐ 151 | 🐛 12 | 🌐 TypeScript | 📅 2026-09-08** - Redis development best practices — data structures, query engine, vector search, caching, and performance optimization.

</details>

<details>
<summary><h3 style="display:inline">Skills by NVIDIA</h3></summary>

Official skills published by NVIDIA for its AI, accelerated computing, robotics, simulation, and developer platforms. NVIDIA updates and reorganizes this catalog frequently, so this list links to the maintained source instead of duplicating a snapshot.

* **[Browse NVIDIA's official Agent Skills catalog](https://github.com/NVIDIA/skills/tree/main/skills) ⭐ 3,337 | 🐛 12 | 🌐 Python | 📅 2026-09-17** - View the current collection directly in NVIDIA's repository.

</details>

<details>
<summary><h3 style="display:inline">Skills by Google Cloud</h3></summary>

Official Google Cloud skills covering Firebase, BigQuery, Cloud Run, GKE, AlloyDB, Cloud SQL, Gemini Enterprise Agent Platform, networking observability, and the Well-Architected Framework. 19 skills.

* **[google/cloud/agent-platform-skill-registry](https://github.com/google/skills/tree/main/skills/cloud/agent-platform-skill-registry) ⭐ 20,115 | 🐛 19 | 🌐 Python | 📅 2026-09-18** - Interact with the Gemini Enterprise Agent Platform Skill Registry to create and search for available skills.
* **[google/cloud/alloydb-basics](https://github.com/google/skills/tree/main/skills/cloud/alloydb-basics) ⭐ 20,115 | 🐛 19 | 🌐 Python | 📅 2026-09-18** - Manages clusters, instances, and backups for AlloyDB for PostgreSQL, and integrates with AlloyDB model context protocol (MCP) tools for automated database operations.
* **[google/cloud/bigquery-basics](https://github.com/google/skills/tree/main/skills/cloud/bigquery-basics) ⭐ 20,115 | 🐛 19 | 🌐 Python | 📅 2026-09-18** - Manages datasets, tables, and jobs in BigQuery, and integrates with BigQuery ML and Gemini for advanced data analytics and AI-driven insights.
* **[google/cloud/cloud-run-basics](https://github.com/google/skills/tree/main/skills/cloud/cloud-run-basics) ⭐ 20,115 | 🐛 19 | 🌐 Python | 📅 2026-09-18** - Manages Cloud Run services, jobs, and worker pools.
* **[google/cloud/cloud-sql-basics](https://github.com/google/skills/tree/main/skills/cloud/cloud-sql-basics) ⭐ 20,115 | 🐛 19 | 🌐 Python | 📅 2026-09-18** - This file generates or explains Cloud SQL resources.
* **[google/cloud/firebase-basics](https://github.com/google/skills/tree/main/skills/cloud/firebase-basics) ⭐ 20,115 | 🐛 19 | 🌐 Python | 📅 2026-09-18** - Use this skill whenever you are working on a project that uses Firebase products or services, especially for mobile or web apps.
* **[google/cloud/gemini-agents-api](https://github.com/google/skills/tree/main/skills/cloud/gemini-agents-api) ⭐ 20,115 | 🐛 19 | 🌐 Python | 📅 2026-09-18** - Manages custom Agent resources on Gemini Enterprise Agent Platform.
* **[google/cloud/gemini-api](https://github.com/google/skills/tree/main/skills/cloud/gemini-api) ⭐ 20,115 | 🐛 19 | 🌐 Python | 📅 2026-09-18** - Guides the usage of the Gemini API on Agent Platform with the Google Gen AI SDK.
* **[google/cloud/gemini-interactions-api](https://github.com/google/skills/tree/main/skills/cloud/gemini-interactions-api) ⭐ 20,115 | 🐛 19 | 🌐 Python | 📅 2026-09-18** - Guides the usage of Gemini Interactions API on Gemini Enterprise Agent Platform.
* **[google/cloud/gke-basics](https://github.com/google/skills/tree/main/skills/cloud/gke-basics) ⭐ 20,115 | 🐛 19 | 🌐 Python | 📅 2026-09-18** - Plan, create, and configure production-ready Google Kubernetes Engine (GKE) clusters using the golden path Autopilot configuration.
* **[google/cloud/google-cloud-networking-observability](https://github.com/google/skills/tree/main/skills/cloud/google-cloud-networking-observability) ⭐ 20,115 | 🐛 19 | 🌐 Python | 📅 2026-09-18** - Investigates Google Cloud networking issues by analyzing logs, metrics, and diagnostics.
* **[google/cloud/google-cloud-recipe-auth](https://github.com/google/skills/tree/main/skills/cloud/google-cloud-recipe-auth) ⭐ 20,115 | 🐛 19 | 🌐 Python | 📅 2026-09-18** - Provides expert guidance on authenticating and authorizing to Google Cloud services and APIs, covering human users, service identities, Application Default Credentials (ADC), and b...
* **[google/cloud/google-cloud-recipe-onboarding](https://github.com/google/skills/tree/main/skills/cloud/google-cloud-recipe-onboarding) ⭐ 20,115 | 🐛 19 | 🌐 Python | 📅 2026-09-18** - Guidance for a developer's first steps on Google Cloud, covering account creation, billing setup, project management, and deploying a first resource.
* **[google/cloud/google-cloud-waf-cost-optimization](https://github.com/google/skills/tree/main/skills/cloud/google-cloud-waf-cost-optimization) ⭐ 20,115 | 🐛 19 | 🌐 Python | 📅 2026-09-18** - Generates cost optimization guidance for Google Cloud workloads based on the Google Cloud Well-Architected Framework (WAF).
* **[google/cloud/google-cloud-waf-operational-excellence](https://github.com/google/skills/tree/main/skills/cloud/google-cloud-waf-operational-excellence) ⭐ 20,115 | 🐛 19 | 🌐 Python | 📅 2026-09-18** - Generates operations-focused guidance for Google Cloud workloads based on the design principles and recommendations in the Operational Excellence pillar of the Google Cloud Well-Ar...
* **[google/cloud/google-cloud-waf-performance-optimization](https://github.com/google/skills/tree/main/skills/cloud/google-cloud-waf-performance-optimization) ⭐ 20,115 | 🐛 19 | 🌐 Python | 📅 2026-09-18** - Generates performance-focused guidance for Google Cloud workloads based on the design principles and recommendations in the Performance Optimization pillar of the Google Cloud Well...
* **[google/cloud/google-cloud-waf-reliability](https://github.com/google/skills/tree/main/skills/cloud/google-cloud-waf-reliability) ⭐ 20,115 | 🐛 19 | 🌐 Python | 📅 2026-09-18** - Generates reliability-focused guidance for Google Cloud workloads based on the design principles and recommendations in the Google Cloud Well-Architected Framework.
* **[google/cloud/google-cloud-waf-security](https://github.com/google/skills/tree/main/skills/cloud/google-cloud-waf-security) ⭐ 20,115 | 🐛 19 | 🌐 Python | 📅 2026-09-18** - Generates security-focused guidance for Google Cloud workloads based on the design principles and recommendations in the Google Cloud Well-Architected Framework (WAF).
* **[google/cloud/google-cloud-waf-sustainability](https://github.com/google/skills/tree/main/skills/cloud/google-cloud-waf-sustainability) ⭐ 20,115 | 🐛 19 | 🌐 Python | 📅 2026-09-18** - Generates sustainability-focused guidance for Google Cloud workloads based on the design principles and recommendations in the Google Cloud Well-Architected Framework (WAF).

</details>

<details>
<summary><h3 style="display:inline">Skills by RedHat</h3></summary>

Extend the power of AI across your organization with a curated library of skills, agents, and MCP servers—all backed by your Red Hat subscription. Whether you’re an SRE optimizing workflows in Cursor or an architect building intelligent interfaces, leverage trusted building blocks to deploy and scale agentic automation with confidence.

* **[redhat/cve-skillpack](https://catalog.redhat.com/en/ai/skills/detail/agentic-skill-pack-for-red-hat-customers#agent-and-skills)** - Understand CVEs, check product lifecycle status, gather diagnostics, and file support cases at the right severity — essential Red Hat skills for everyday operations.

* **[redhat/sre-skillpack](https://catalog.redhat.com/en/ai/skills/detail/agentic-skill-pack-for-site-reliability-engineers)** - Discover, remediate, and verify CVEs across your RHEL fleet — orchestrating Red Hat Lightspeed and Ansible Automation Platform through a single workflow.

* **[redhat/openshift-skillpack](https://catalog.redhat.com/en/ai/skills/detail/agentic-skill-pack-for-red-hat-openshift)** - Provision, inventory, and report on OpenShift clusters — spanning Assisted Installer, OCM, ROSA, ARO, and kubeconfig fleets — through a single conversational workflow.

* **[redhat/openshift-virtualization](https://catalog.redhat.com/en/ai/skills/detail/agentic-skill-pack-for-red-hat-openshift-virtualization)** - Manage the full VM lifecycle on OpenShift Virtualization — create, clone, snapshot, restore, rebalance, and report — through a single conversational workflow.

</details>

<details>
<summary><h3 style="display:inline">Skills by Cypress</h3></summary>

Official skills published by Cypress to help create, maintain, understand, and fix your Cypress tests. 3 skills.

* **[cypress-io/cypress-author](https://github.com/cypress-io/ai-toolkit/tree/main/skills/cypress-author) ⭐ 42 | 🐛 2 | 🌐 TypeScript | 📅 2026-09-16** - Creates, updates, and fixes Cypress E2E and component tests.
* **[cypress-io/cypress-explain](https://github.com/cypress-io/ai-toolkit/tree/main/skills/cypress-explain) ⭐ 42 | 🐛 2 | 🌐 TypeScript | 📅 2026-09-16** - Explains Cypress E2E and component tests, and answers questions about Cypress use and behavior.
* **[cypress-io/cypress-docs](https://github.com/cypress-io/ai-toolkit/tree/main/skills/cypress-docs) ⭐ 42 | 🐛 2 | 🌐 TypeScript | 📅 2026-09-16** - Search and extract Cypress information from official documentation.

</details>

### Community Skills

<details>
<summary><h3 style="display:inline">Vector Databases</h3></summary>

* **[qdrant/skills](https://github.com/qdrant/skills) ⭐ 236 | 🐛 6 | 🌐 Python | 📅 2026-09-18** - Agent skills for Qdrant vector search, covering scaling, performance optimization, search quality, monitoring, deployment, model migration, version upgrades, and SDK usage across Python, TypeScript, Rust, Go, .NET, and Java

</details>

<details>
<summary><h3 style="display:inline">Marketing</h3></summary>

* **[blader/humanizer](https://github.com/blader/humanizer) ⭐ 49,761 | 🐛 21 | 🌐 Python | 📅 2026-09-06** - Remove signs of AI-generated writing from text, making it sound more natural and human
* **[AgriciDaniel/claude-seo](https://github.com/AgriciDaniel/claude-seo) ⭐ 17,133 | 🐛 20 | 🌐 Python | 📅 2026-09-11** - Universal SEO skill for comprehensive website analysis and optimization
* **[nowork-studio/notfair-plugin](https://github.com/nowork-studio/notfair-plugin) ⭐ 3,820 | 🐛 11 | 🌐 TypeScript | 📅 2026-09-17** - SEO, GEO, Google Ads, and Meta Ads skills with live data
* **[aaron-he-zhu/aaron-marketing-skills](https://github.com/aaron-he-zhu/aaron-marketing-skills) ⭐ 2,798 | 🐛 0 | 🌐 Python | 📅 2026-09-18** - 69 marketing skills across SEO/GEO, influencer, paid ads, and email on one shared contract, with 5 benchmark-driven auditor gates (CORE-EEAT, CITE, C³, ROAS, SEND) and keyless data connectors
* **[sergebulaev/linkedin-skills](https://github.com/sergebulaev/linkedin-skills) ⭐ 2,686 | 🐛 1 | 🌐 Python | 📅 2026-09-18** - LinkedIn marketing skills: viral hooks, comment drafting, algorithm audit, humanizer
* **[Nanako0129/sepia](https://github.com/Nanako0129/sepia) ⭐ 2,675 | 🐛 8 | 🌐 Python | 📅 2026-09-17** - De-AI writing skill fixing narrative structure before word choice
* **[ScrapeCreators/social-media-research-skills](https://github.com/ScrapeCreators/social-media-research-skills) ⭐ 2,494 | 🐛 3 | 🌐 Python | 📅 2026-08-26** - Research social outliers, comments, competitors, ads, and trends
* **[Eronred/aso-skills](https://github.com/Eronred/aso-skills) ⭐ 1,873 | 🐛 0 | 🌐 MDX | 📅 2026-08-22** - 30+ App Store Optimization skills for keyword research, metadata optimization, competitor analysis, creative optimization, and mobile growth strategies via Appeeky API
* **[gooseworks-ai/goose-skills](https://github.com/gooseworks-ai/goose-skills) ⭐ 1,215 | 🐛 59 | 🌐 Python | 📅 2026-09-01** - 125 growth and GTM skills: ads, content, lead gen, SEO
* **[wshuyi/x-article-publisher-skill](https://github.com/wshuyi/x-article-publisher-skill) ⭐ 867 | 🐛 6 | 🌐 Python | 📅 2026-01-25** - Publish articles to X/Twitter
* **[indranilbanerjee/digital-marketing-pro](https://github.com/indranilbanerjee/digital-marketing-pro) ⭐ 824 | 🐛 2 | 🌐 Python | 📅 2026-09-07** - 150-skill engagement methodology — 12-Part Strategy Flow, 25 specialist agents, EU AI Act Article 50 ready (C2PA signing), 6-platform AEO/GEO incl. Google AI Mode
* **[gitroomhq/postiz-agent](https://github.com/gitroomhq/postiz-agent) ⭐ 470 | 🐛 16 | 🌐 TypeScript | 📅 2026-09-16** - Schedule social media posts across 28+ platforms programmatically
* **[BrianRWagner/ai-marketing-claude-code-skills](https://github.com/BrianRWagner/ai-marketing-claude-code-skills) ⭐ 420 | 🐛 2 | 🌐 Shell | 📅 2026-03-19** - 17 marketing frameworks for cold outreach, homepage audit, social cards, and more
* **[ilyautov/humanizer-ru](https://github.com/ilyautov/humanizer-ru/tree/main/skills/humanizer-ru) ⭐ 364 | 🐛 3 | 🌐 Python | 📅 2026-09-17** - Removes 64 AI-writing markers from Russian text, with scanner
* **[CosmoBlk/email-marketing-bible](https://github.com/CosmoBlk/email-marketing-bible) ⭐ 300 | 🐛 1 | 📅 2026-09-08** - 55K-word email marketing guide as an AI skill
* **[AIDevGTM/gtm-cofounder](https://github.com/AIDevGTM/gtm-cofounder) ⭐ 287 | 🐛 3 | 📅 2026-09-16** - 18 go-to-market skills for solo technical founders: positioning, first users, launch, pricing, and founder-led sales; grounded in Adam Frankl and Jakub Czakon
* **[taisly/agent](https://github.com/taisly/agent) ⭐ 213 | 🐛 2 | 🌐 JavaScript | 📅 2026-07-06** - Codex plugin, Agent Skill, CLI, and MCP server for publishing approved short-form videos to TikTok, Instagram Reels, YouTube Shorts, X, and Facebook through Taisly
* **[smixs/creative-director-skill](https://github.com/smixs/creative-director-skill) ⭐ 207 | 🐛 0 | 🌐 Python | 📅 2026-08-08** - AI creative director with recursive self-assessment: 20+ methodologies (SIT, TRIZ, Bisociation, SCAMPER, Synectics), 3-axis evaluation calibrated against Cannes/D\&AD/HumanKind, 5-phase process from brief to presentation
* **[Xquik-dev/x-twitter-scraper](https://github.com/Xquik-dev/x-twitter-scraper) ⭐ 199 | 🐛 3 | 🌐 JavaScript | 📅 2026-09-04** - Tweet search, profile tweets, follower export, media, posting, replies, MCP
* **[sandbaseai/sandbase-skills/multi-source-search](https://github.com/sandbaseai/sandbase-skills/tree/main/research/multi-source-search) ⭐ 195 | 🐛 2 | 🌐 Python | 📅 2026-09-08** - Evidence-led multi-source research with offline validation
* **[Bomx/distribb-skill](https://github.com/Bomx/distribb-skill) ⭐ 194 | 🐛 5 | 🌐 Python | 📅 2026-08-21** - SEO articles, keyword research, CMS publishing, high-DR backlink exchange
* **[degausai/wonda](https://github.com/degausai/wonda) ⭐ 153 | 🐛 3 | 🌐 TypeScript | 📅 2026-09-15** - AI content creation: images, video, music, audio, editing, publishing
* **[MohamedAbdallah-14/unslop](https://github.com/MohamedAbdallah-14/unslop) ⭐ 140 | 🐛 3 | 🌐 Python | 📅 2026-09-14** - Removes named AI writing tells (tricolons, em-dash pileups, hedging stacks, sycophancy openers, stock vocab like "delve"/"crucial"). Split lint/rewrite modes for auditing your own text without auto-rewriting. Five intensity levels, MIT
* **[Vladimir-Human/humanizer-ru](https://github.com/Vladimir-Human/humanizer-ru) ⭐ 125 | 🐛 2 | 🌐 Python | 📅 2026-09-18** - Removes AI-writing markers from Russian text
* **[infrasity-labs/dev-gtm-claude-skills](https://github.com/infrasity-labs/dev-gtm-claude-skills) ⭐ 124 | 🐛 0 | 🌐 Python | 📅 2026-06-28**: GTM-focused skill collection for developer go-to-market workflows including launch planning, positioning, and outbound sequences.
* **[Xquik-dev/tweetclaw](https://github.com/Xquik-dev/tweetclaw) ⭐ 95 | 🐛 9 | 🌐 TypeScript | 📅 2026-09-11** - Post tweets, replies, DMs; search, monitor, run giveaways
* **[SHADOWPR0/beautiful\_prose](https://github.com/SHADOWPR0/beautiful_prose) ⭐ 55 | 🐛 0 | 📅 2025-12-30** - Hard-edged writing style contract for timeless, forceful English prose without AI tics
* **[SupercmoHQ/superCMO-skills](https://github.com/SupercmoHQ/superCMO-skills) ⭐ 42 | 🐛 7 | 🌐 Python | 📅 2026-08-28** - Open-source skills + local MCP server for marketing video & image production: UGC videos, ad videos, product photography, and image ads from a product photo and a brief; casts AI actors, picks the best image/video models, edits any-length clips with consistent actor and product, and researches competitor ads. BYO or managed keys, Apache-2.0
* **[axelfreeman/marketing-mindset](https://github.com/axelfreeman/marketing-mindset) ⭐ 31 | 🐛 1 | 🌐 HTML | 📅 2026-09-18** - Marketing OS for AI agents — think like a marketer first, get tactics as the output
* **[mailtrap/mailtrap-skills](https://github.com/mailtrap/mailtrap-skills) ⭐ 10 | 🐛 2 | 🌐 Python | 📅 2026-09-14** - Send emails via API/SMTP with sandbox testing
* **[YannisKiefer/dark-psychology-skills](https://github.com/YannisKiefer/dark-psychology-skills) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-08-25** - 13 sales and negotiation skills for agents distilled from 36 books (CIA psyop manuals, FBI behavioral research, propaganda science, persuasion classics); every tactic passes an honest-influence filter: it must still work when fully disclosed
* **[Citlyze/citlyze-skills](https://github.com/citlyze/citlyze-skills) ⭐ 0 | 🐛 0 | 📅 2026-08-12** - AI search visibility skills from the Citlyze team: window-over-window visibility reports, citation gap analysis, prompt audits, and action plans via the Citlyze MCP server, plus a standalone AEO page audit that grades any URL without an account

</details>

<details>
<summary><h3 style="display:inline">Productivity and Collaboration</h3></summary>

* **[obra/brainstorming](https://github.com/obra/superpowers/blob/main/skills/brainstorming/SKILL.md) ⭐ 288,313 | 🐛 376 | 🌐 Shell | 📅 2026-09-18** - Generate and explore ideas
* **[obra/writing-plans](https://github.com/obra/superpowers/blob/main/skills/writing-plans/SKILL.md) ⭐ 288,313 | 🐛 376 | 🌐 Shell | 📅 2026-09-18** - Create strategic documentation
* **[obra/executing-plans](https://github.com/obra/superpowers/blob/main/skills/executing-plans/SKILL.md) ⭐ 288,313 | 🐛 376 | 🌐 Shell | 📅 2026-09-18** - Implement and run strategic plans
* **[obra/dispatching-parallel-agents](https://github.com/obra/superpowers/blob/main/skills/dispatching-parallel-agents/SKILL.md) ⭐ 288,313 | 🐛 376 | 🌐 Shell | 📅 2026-09-18** - Coordinate multiple simultaneous agents
* **[obra/using-superpowers](https://github.com/obra/superpowers/blob/main/skills/using-superpowers/SKILL.md) ⭐ 288,313 | 🐛 376 | 🌐 Shell | 📅 2026-09-18** - Leverage core platform capabilities
* **[santifer/career-ops](https://github.com/santifer/career-ops) ⭐ 71,995 | 🐛 530 | 🌐 JavaScript | 📅 2026-09-18** - 14-skill collection for AI-powered job search: JD evaluation with A-F scoring, ATS-optimized PDF generation, portal scanners (Greenhouse/Ashby/Lever), interview prep with STAR+R, batch processing, and a Go dashboard TUI
* **[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) ⭐ 62,267 | 🐛 115 | 🌐 Python | 📅 2026-09-18** - Research any topic across Reddit, X, YouTube, HN, Polymarket, and the web, ranked by upvotes, likes, and real money instead of editors
* **[zarazhangrui/frontend-slides](https://github.com/zarazhangrui/frontend-slides) ⭐ 29,494 | 🐛 68 | 🌐 JavaScript | 📅 2026-06-23** - Generate animation-rich HTML presentations with visual style previews
* **[xberg-io/xberg](https://github.com/xberg-io/xberg/tree/main/plugin/skills/xberg) ⭐ 9,321 | 🐛 6 | 🌐 Rust | 📅 2026-09-18** - Extract text, tables, and metadata from 101+ document formats
* **[PleasePrompto/notebooklm-skill](https://github.com/PleasePrompto/notebooklm-skill) ⚠️ Archived** - Interact with NotebookLM for document-based conversations
* **[op7418/NanoBanana-PPT-Skills](https://github.com/op7418/NanoBanana-PPT-Skills) ⭐ 3,255 | 🐛 7 | 🌐 Python | 📅 2026-01-19** - AI-powered PPT generation with document analysis and styled images
* **[Paramchoudhary/ResumeSkills](https://github.com/Paramchoudhary/ResumeSkills) ⭐ 2,336 | 🐛 5 | 📅 2026-06-19** - 20 specialized skills for resume optimization, ATS analysis, interview prep, and career transitions
* **[op7418/Youtube-clipper-skill](https://github.com/op7418/Youtube-clipper-skill) ⭐ 2,209 | 🐛 11 | 🌐 Python | 📅 2026-01-22** - YouTube clip generation and editing with automated workflows
* **[deusyu/translate-book](https://github.com/deusyu/translate-book) ⭐ 1,902 | 🐛 32 | 🌐 Python | 📅 2026-09-07** - Translate books (PDF/DOCX/EPUB) via parallel sub-agents with resume
* **[ReScienceLab/opc-skills](https://github.com/ReScienceLab/opc-skills) ⭐ 1,817 | 🐛 11 | 🌐 Python | 📅 2026-09-17** - Agent skills for solopreneurs with SEO, geo, and LLM tools
* **[NeoLabHQ/write-concisely](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/docs/skills/write-concisely) ⭐ 1,710 | 🐛 9 | 🌐 TypeScript | 📅 2026-08-26** - Applies the famous *The Elements of Style* book principles to make documentation and writing clearer and more professional by eliminating wordiness and improving structure.
* **[tjboudreaux/cc-thinking-skills](https://github.com/tjboudreaux/cc-thinking-skills) ⭐ 1,319 | 🐛 4 | 🌐 JavaScript | 📅 2026-08-07** - 28 eval-informed mental models for decisions, debugging, systems, and strategy
* **[bevibing/tutor-skills](https://github.com/bevibing/tutor-skills) ⭐ 1,149 | 🐛 7 | 🌐 Shell | 📅 2026-02-28** - Transform docs or codebases into Obsidian StudyVaults with interactive quizzes
* **[JimmySadek/youtube-fetcher](https://github.com/JimmySadek/youtube-fetcher-to-markdown) ⭐ 478 | 🐛 0 | 🌐 Python | 📅 2026-09-05** - Create Obsidian-ready Markdown notes from YouTube videos
* **[obra/superpowers-lab](https://github.com/obra/superpowers-lab) ⭐ 429 | 🐛 1 | 🌐 Shell | 📅 2026-06-01** - Lab environment for Claude superpowers
* **[zapier/zapier-mcp](https://github.com/zapier/zapier-mcp) ⭐ 410 | 🐛 1 | 📅 2026-07-29** - Official plugin distribution for the hosted Zapier MCP server. Connects Claude to thousands of apps — send messages, pull data, trigger workflows.
* **[openaccountants/openaccountants](https://github.com/openaccountants/openaccountants) ⭐ 390 | 🐛 8 | 🌐 Python | 📅 2026-09-18** - 371 tax classification skills across 134 countries
* **[Charlie85270/Dorothy](https://github.com/Charlie85270/Dorothy) ⭐ 347 | 🐛 10 | 🌐 TypeScript | 📅 2026-07-07** - Orchestrate multiple AI CLI agents with automations and MCP servers
* **[Neeeophytee/finding-unknowns-skills](https://github.com/Neeeophytee/finding-unknowns-skills) ⭐ 335 | 🐛 0 | 🌐 Python | 📅 2026-09-16** - 8 meta-skills that make a coding agent surface your unknowns before they get expensive: blindspot pass, interview, reference hunt, implementation plan/notes, pitch packager, and a pre-merge change quiz. Works in Claude Code, Codex, and Cursor via the agentskills.io SKILL.md format
* **[EveryInc/charlie-cfo-skill](https://github.com/EveryInc/charlie-cfo-skill) ⭐ 312 | 🐛 0 | 📅 2026-01-29** - Bootstrapped CFO financial management inspired by Charlie Munger
* **[ognjengt/founder-skills](https://github.com/ognjengt/founder-skills) ⭐ 305 | 🐛 1 | 🌐 JavaScript | 📅 2026-05-18** - Claude skills for founders with packaged startup workflows
* **[Digidai/product-manager-skills](https://github.com/Digidai/product-manager-skills) ⭐ 164 | 🐛 0 | 🌐 Shell | 📅 2026-04-12** - Senior PM agent with 30+ frameworks and SaaS metrics
* **[gokapso/integrate-whatsapp](https://github.com/gokapso/agent-skills/tree/master/skills/integrate-whatsapp) ⭐ 157 | 🐛 6 | 🌐 JavaScript | 📅 2026-09-17** - Connect WhatsApp, set up webhooks, and send messages
* **[gokapso/automate-whatsapp](https://github.com/gokapso/agent-skills/tree/master/skills/automate-whatsapp) ⭐ 157 | 🐛 6 | 🌐 JavaScript | 📅 2026-09-17** - Build WhatsApp automations with workflows and agents
* **[gokapso/observe-whatsapp](https://github.com/gokapso/agent-skills/tree/master/skills/observe-whatsapp) ⭐ 157 | 🐛 6 | 🌐 JavaScript | 📅 2026-09-17** - Debug WhatsApp delivery issues and run health checks
* **[pattern-ai-labs/agentcall](https://github.com/pattern-ai-labs/agentcall) ⭐ 157 | 🐛 2 | 🌐 Python | 📅 2026-09-15** - Let your AI agents join Google Meet, Zoom, Teams calls and collaborate like a real team-mate.
* **[vaibhavarora14/job-application-agent](https://github.com/vaibhavarora14/job-application-agent) ⭐ 150 | 🐛 4 | 🌐 JavaScript | 📅 2026-09-17** - Privacy-first job discovery and tracking
* **[wrsmith108/linear-claude-skill](https://github.com/wrsmith108/linear-claude-skill) ⭐ 126 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-17** - Manage Linear issues, projects, and teams
* **[manavmishra/zero-slop](https://github.com/manavmishra/ZeroSlop/blob/main/SKILL.md) ⭐ 122 | 🐛 5 | 🌐 Python | 📅 2026-09-13** - Edits AI-sounding prose while preserving facts, voice, and formatting
* **[kgraph57/strategy-consulting-visualization](https://github.com/kgraph57/mckinsey-style-visualization-skill) ⭐ 111 | 🐛 4 | 🌐 Python | 📅 2026-09-09** - McKinsey-style charts and consulting slide decks
* **[Linked-API/linkedin](https://github.com/Linked-API/linkedin-skills/tree/main/linkedin) ⭐ 59 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-13** - Fetch LinkedIn profiles, search people and companies, send messages, manage connections, create posts, react, comment, and run custom LinkedIn workflows from Claude Code, Codex, Cursor, and Windsurf.
* **[hanfang/claude-memory-skill](https://github.com/hanfang/claude-memory-skill) ⭐ 56 | 🐛 0 | 🌐 Shell | 📅 2026-02-07** - Minimal, low-friction hierarchical memory system with background agents and filesystem-based persistence
* **[Sendmux/skills](https://github.com/Sendmux/skills) ⭐ 19 | 🐛 0 | 🌐 JavaScript | 📅 2026-09-18** - Sendmux email and mailbox workflows for agents
* **[cyperx84/claude-skills-mental-models](https://github.com/cyperx84/claude-skills-mental-models) ⭐ 19 | 🐛 4 | 📅 2026-09-10** - Drop your own mental models in as files; 21 included
* **[PSPDFKit-labs/nutrient-agent-skill](https://github.com/PSPDFKit-labs/nutrient-agent-skill) ⭐ 17 | 🐛 0 | 🌐 Python | 📅 2026-08-30** - Document processing with Nutrient DWS API: convert (PDF/DOCX/XLSX/PPTX/HTML/images), extract text/tables, OCR (20+ languages), redact PII (pattern + AI), watermark, digital signatures, form filling. [MCP server](https://www.npmjs.com/package/@nutrient-sdk/dws-mcp-server) also available.
* **[SeanZoR/claude-speed-reader](https://github.com/SeanZoR/claude-speed-reader) ⭐ 16 | 🐛 0 | 🌐 HTML | 📅 2026-01-15** - Speed read Claude's responses at 600+ WPM using RSVP with Spritz-style ORP highlighting
* **[notiondevs/Notion Skills for Claude](https://www.notion.so/notiondevs/Notion-Skills-for-Claude-28da4445d27180c7af1df7d8615723d0)** - Skills for working with Notion

</details>

<details>
<summary><h3 style="display:inline">Development and Testing</h3></summary>

* **[obra/test-driven-development](https://github.com/obra/superpowers/blob/main/skills/test-driven-development/SKILL.md) ⭐ 288,313 | 🐛 376 | 🌐 Shell | 📅 2026-09-18** - Write tests before implementing code

* **[obra/subagent-driven-development](https://github.com/obra/superpowers/blob/main/skills/subagent-driven-development/SKILL.md) ⭐ 288,313 | 🐛 376 | 🌐 Shell | 📅 2026-09-18** - Development using multiple sub-agents

* **[obra/systematic-debugging](https://github.com/obra/superpowers/blob/main/skills/systematic-debugging/SKILL.md) ⭐ 288,313 | 🐛 376 | 🌐 Shell | 📅 2026-09-18** - Methodical problem-solving in code

* **[obra/finishing-a-development-branch](https://github.com/obra/superpowers/blob/main/skills/finishing-a-development-branch/SKILL.md) ⭐ 288,313 | 🐛 376 | 🌐 Shell | 📅 2026-09-18** - Complete Git code branches

* **[obra/requesting-code-review](https://github.com/obra/superpowers/blob/main/skills/requesting-code-review/SKILL.md) ⭐ 288,313 | 🐛 376 | 🌐 Shell | 📅 2026-09-18** - Initiate code review processes

* **[obra/receiving-code-review](https://github.com/obra/superpowers/blob/main/skills/receiving-code-review/SKILL.md) ⭐ 288,313 | 🐛 376 | 🌐 Shell | 📅 2026-09-18** - Process and incorporate code feedback

* **[obra/using-git-worktrees](https://github.com/obra/superpowers/blob/main/skills/using-git-worktrees/SKILL.md) ⭐ 288,313 | 🐛 376 | 🌐 Shell | 📅 2026-09-18** - Manage multiple Git working trees

* **[obra/verification-before-completion](https://github.com/obra/superpowers/blob/main/skills/verification-before-completion/SKILL.md) ⭐ 288,313 | 🐛 376 | 🌐 Shell | 📅 2026-09-18** - Validate work before finalizing

* **[obra/writing-skills](https://github.com/obra/superpowers/blob/main/skills/writing-skills/SKILL.md) ⭐ 288,313 | 🐛 376 | 🌐 Shell | 📅 2026-09-18** - Develop and document capabilities

* **[mattpocock/skills](https://github.com/mattpocock/skills) ⭐ 264,906 | 🐛 502 | 🌐 Shell | 📅 2026-09-18** - 17 dev workflow skills: PRD writing, TDD, codebase architecture, git guardrails, issue triage, refactoring plans, and more

* **[nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) ⭐ 128,663 | 🐛 86 | 🌐 Python | 📅 2026-09-15** - UI/UX design patterns and best practices

* **[Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) ⭐ 88,114 | 🐛 69 | 🌐 JavaScript | 📅 2026-09-16** - High-agency frontend skill that gives AI good taste with tunable design variance, motion intensity, and visual density to stop generic UI slop

* **[Lum1104/understand-anything](https://github.com/Egonex-AI/Understand-Anything) ⭐ 83,217 | 🐛 304 | 🌐 TypeScript | 📅 2026-09-12** - Interactive codebase knowledge graphs via multi-agent LLM analysis

* **[tt-a1i/archify](https://github.com/tt-a1i/archify/tree/main/archify) ⭐ 66,355 | 🐛 131 | 🌐 JavaScript | 📅 2026-09-18** - Generate validated interactive architecture diagrams from codebases or system descriptions

* **[mukul975/Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills) ⭐ 32,941 | 🐛 48 | 🌐 Python | 📅 2026-08-31** - 753 cybersecurity skills across 38 domains: cloud security, pentesting, red teaming, DFIR, malware analysis, threat intel, and more (MITRE ATT\&CK mapped)

* **[Skill\_Seekers](https://github.com/yusufkaraaslan/Skill_Seekers) ⭐ 14,996 | 🐛 58 | 🌐 Python | 📅 2026-09-16** - Automatically convert documentation websites, GitHub repositories, and PDFs into Claude AI skills in minutes

* **[ibelick/ui-skills](https://github.com/ibelick/ui-skills) ⭐ 8,675 | 🐛 14 | 🌐 TypeScript | 📅 2026-09-18** - Opinionated, evolving constraints to guide agents when building interfaces

* **[browser-act/browser-act](https://github.com/browser-act/skills/tree/main/browser-act) ⭐ 5,953 | 🐛 8 | 🌐 Python | 📅 2026-08-24** - Automate authenticated browsers with extraction and human handoff

* **[AvdLee/swiftui-expert-skill](https://github.com/AvdLee/SwiftUI-Agent-Skill/tree/main/swiftui-expert-skill) ⭐ 3,570 | 🐛 4 | 🌐 Python | 📅 2026-09-14** - Modern SwiftUI best practices and iOS 26+ Liquid Glass adoption

* **[foryourhealth111-pixel/Vibe-Skills](https://github.com/foryourhealth111-pixel/Vibe-Skills) ⭐ 3,335 | 🐛 42 | 🌐 Python | 📅 2026-08-31** - A skills governed plug-and-play harness for staged, test-driven skill orchestration

* **[CloudAI-X/threejs-skills](https://github.com/CloudAI-X/threejs-skills) ⭐ 3,326 | 🐛 9 | 📅 2026-07-09** - Three.js skills for creating 3D elements and interactive experiences

* **[lackeyjb/playwright-skill](https://github.com/lackeyjb/playwright-skill) ⭐ 3,123 | 🐛 7 | 🌐 JavaScript | 📅 2026-08-14** - Browser automation with Playwright

* **[KhazP/vibe-coding-prompt-template](https://github.com/KhazP/vibe-coding-prompt-template) ⭐ 3,087 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-10** - Plan MVPs into PRD, tech design, and AGENTS.md

* **[Simon-He95/markstream-install](https://github.com/Simon-He95/markstream-vue/tree/main/.agents/skills/markstream-install) ⭐ 3,010 | 🐛 3 | 🌐 Vue | 📅 2026-09-13** - Install streaming Markdown renderers across five frontend frameworks

* **[antonbabenko/terraform-skill](https://github.com/antonbabenko/terraform-skill) ⭐ 2,353 | 🐛 3 | 📅 2026-07-03** - Terraform and OpenTofu patterns: testing, modules, state, CI/CD.

* **[mcollina/skills](https://github.com/mcollina/skills/tree/main/skills) ⭐ 1,922 | 🐛 10 | 🌐 TypeScript | 📅 2026-08-17** - 11 skills by Matteo Collina: Node.js, Fastify, TypeScript, OAuth, Git/GitHub, ESLint neostandard, documentation (Diataxis), Node.js core internals, skill optimizer, and more

* **[NeoLabHQ/review](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/review) ⭐ 1,710 | 🐛 9 | 🌐 TypeScript | 📅 2026-08-26** - Comprehensive PR code review using specialized agents: bug-hunter, security-auditor, code-quality-reviewer, contracts-reviewer, historical-context-reviewer, test-coverage-reviewer

* **[NeoLabHQ/reflexion](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/reflexion) ⭐ 1,710 | 🐛 9 | 🌐 TypeScript | 📅 2026-08-26** - Self-refinement loop that forces the LLM to reflect on previous output and correct itself.

* **[NeoLabHQ/sdd](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/sdd) ⭐ 1,710 | 🐛 9 | 🌐 TypeScript | 📅 2026-08-26** - Spec-driven development workflow that transforms prompts into production-ready implementations through structured planning, architecture design, and LLM-as-a-Judge based quality gates.

* **[NeoLabHQ/ddd](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/ddd) ⭐ 1,710 | 🐛 9 | 🌐 TypeScript | 📅 2026-08-26** - Domain-driven development skills that also include Clean Architecture, SOLID principles, and design patterns.

* **[NeoLabHQ/sadd](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/sadd) ⭐ 1,710 | 🐛 9 | 🌐 TypeScript | 📅 2026-08-26** - Dispatches independent subagents for individual tasks with code review checkpoints between iterations for rapid, controlled development.

* **[NeoLabHQ/kaizen](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/kaizen) ⭐ 1,710 | 🐛 9 | 🌐 TypeScript | 📅 2026-08-26** - Applies continuous improvement methodology with multiple analytical approaches, based on Japanese Kaizen philosophy and Lean methodology.

* **[truongduy2611/app-store-preflight-skills](https://github.com/truongduy2611/app-store-preflight-skills) ⭐ 1,369 | 🐛 0 | 📅 2026-05-29** - Scan iOS/macOS projects to catch common mistakes that lead to App Store rejection before submission

* **[conorluddy/ios-simulator-skill](https://github.com/conorluddy/ios-simulator-skill) ⭐ 1,255 | 🐛 20 | 🌐 Python | 📅 2026-09-13** - Control iOS Simulator

* **[GanyuanRan/Aegis](https://github.com/GanyuanRan/Aegis) ⭐ 1,209 | 🐛 1 | 🌐 Python | 📅 2026-09-16** - Evidence-driven method pack for AI coding agents

* **[rorkai/app-store-connect-cli-skills](https://github.com/rorkai/app-store-connect-cli-skills) ⭐ 1,031 | 🐛 0 | 🌐 Python | 📅 2026-09-14** - Automate App Store deployments and management using ASC CLI

* **[agiwhitelist/auteur](https://github.com/agiwhitelist/auteur) ⭐ 1,020 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-06** - Builds websites gated by an anti-slop linter and motion QA

* **[ZhangHanDong/makepad-skills](https://github.com/ZhangHanDong/makepad-skills) ⭐ 750 | 🐛 0 | 📅 2026-04-07** - Makepad UI development skills for Rust apps: setup, patterns, shaders, packaging, and troubleshooting.

* **[aeonfun/aeon](https://github.com/aeonfun/aeon) ⭐ 739 | 🐛 1 | 🌐 Shell | 📅 2026-09-17** - 70+ Claude Code skills + autonomous GitHub Actions agent framework

* **[plasma-ai/fractal](https://github.com/plasma-ai/fractal/tree/main/fractal/skills/fractal) ⭐ 729 | 🐛 5 | 🌐 Python | 📅 2026-09-17** - Bounded hierarchical agent loops in isolated git worktrees

* **[alinaqi/maggy](https://github.com/alinaqi/maggy) ⭐ 708 | 🐛 0 | 🌐 Python | 📅 2026-09-16** - Opinionated project initialization with security-first guardrails, spec-driven atomic todos, LLM testing patterns, and CLI tool orchestration (gh, vercel, supabase)

* **[superdesigndev/superdesign-skill](https://github.com/superdesigndev/superdesign-skill) ⭐ 573 | 🐛 6 | 🌐 JavaScript | 📅 2026-08-21** - Creates design systems from existing codebases and iterates UI drafts

* **[ehmo/platform-design-skills](https://github.com/ehmo/platform-design-skills) ⭐ 528 | 🐛 1 | 📅 2026-03-19** - 300+ design rules from Apple HIG, Material Design 3, and WCAG 2.2 for cross-platform apps

* **[NoizAI/skills](https://github.com/NoizAI/skills) ⭐ 524 | 🐛 5 | 🌐 Python | 📅 2026-05-07** - Human-like TTS workflows with local/cloud APIs and app delivery

* **[baskduf/codex-fable5](https://github.com/baskduf/FableCodex/tree/main/plugins/codex-fable5/skills/codex-fable5) ⭐ 440 | 🐛 9 | 🌐 Python | 📅 2026-07-26** - Evidence-based workflow gates for Codex

* **[sanjay3290/postgres](https://github.com/sanjay3290/ai-skills/tree/main/skills/postgres) ⭐ 423 | 🐛 4 | 🌐 Python | 📅 2026-09-10** - Execute safe read-only SQL queries against PostgreSQL databases

* **[sanjay3290/deep-research](https://github.com/sanjay3290/ai-skills/tree/main/skills/deep-research) ⭐ 423 | 🐛 4 | 🌐 Python | 📅 2026-09-10** - Autonomous multi-step research using Gemini Deep Research Agent

* **[LambdaTest/agent-skills](https://github.com/LambdaTest/agent-skills) ⭐ 369 | 🐛 4 | 🌐 Python | 📅 2026-09-11** - TestMu AI (Formerly LambdaTest) Skills is a curated collection of Agent Skills that teach AI coding assistants how to write production-grade test automation.

* **[testdino-hq/playwright-skill](https://github.com/testdino-hq/playwright-skill) ⭐ 366 | 🐛 1 | 📅 2026-09-06** - 70+ production-tested Playwright automation testing patterns: E2E, POM, CI/CD, migrations, CLI

* **[zxkane/aws-skills](https://github.com/zxkane/aws-skills) ⭐ 363 | 🐛 0 | 🌐 Python | 📅 2026-06-15** - AWS development with infrastructure automation and cloud architecture patterns

* **[zscole/model-hierarchy-skill](https://github.com/zscole/model-hierarchy-skill) ⭐ 346 | 🐛 3 | 🌐 Python | 📅 2026-02-16** - Cost-optimized model routing based on task complexity

* **[drogers0/github-image-upload](https://github.com/drogers0/gh-image/tree/main/skills/github-image-upload) ⭐ 269 | 🐛 4 | 🌐 Go | 📅 2026-09-09** - Attach screenshots, PDFs, logs, zips, and videos to GitHub PRs, issues, and comments, returning canonical user-attachments URLs. GitHub has no public attachment-upload API. Works with Claude Code, Codex, Cursor, and Gemini CLI

* **[squirrelscan/squirrelscan](https://github.com/squirrelscan/squirrelscan/tree/main/skills) ⭐ 268 | 🐛 50 | 🌐 TypeScript | 📅 2026-09-18** - Audits websites for SEO, performance, security, accessibility and returns fixes

* **[Continuum-AI-Corp/orca-replay](https://github.com/Continuum-AI-Corp/OrcaReplay/tree/main/skills/orca-replay) ⭐ 255 | 🐛 9 | 🌐 TypeScript | 📅 2026-09-18** - Answer questions about past agent runs from their recordings

* **[scarletkc/vexor](https://github.com/scarletkc/vexor) ⭐ 241 | 🐛 4 | 🌐 Python | 📅 2026-09-12** - Vector-powered CLI for semantic file search with a Claude/Codex skill

* **[scarletkc/agents](https://github.com/scarletkc/agents) ⭐ 218 | 🐛 0 | 🌐 Python | 📅 2026-09-14** - Reusable standards and workflow skills for AI coding agents

* **[jthack/ffuf-claude-skill](https://github.com/jthack/ffuf_claude_skill) ⭐ 211 | 🐛 1 | 🌐 Python | 📅 2025-10-16** - Web fuzzing with ffuf

* **[coderabbitai/skills](https://github.com/coderabbitai/skills) ⭐ 177 | 🐛 15 | 📅 2026-09-16** - Code review and PR autofix workflows for coding agents

* **[hqhq1025/skill-optimizer](https://github.com/hqhq1025/skill-optimizer) ⭐ 169 | 🐛 1 | 🌐 Python | 📅 2026-05-14** - Diagnose and optimize Agent Skills (SKILL.md) with real session data and research-backed static analysis. Works with Claude Code, Codex, and any Agent Skills-compatible agent

* **[csthink/dashmotion](https://github.com/csthink/dashmotion/tree/main/skills/dashmotion) ⭐ 167 | 🐛 0 | 🌐 HTML | 📅 2026-06-16** - Animated technical diagrams from plain English or Mermaid, self-contained HTML/SVG

* **[Kayforkind/reimagine-it](https://github.com/Kayforkind/reimagine-it) ⭐ 161 | 🐛 0 | 🌐 JavaScript | 📅 2026-09-13** - Redesign HTML pages using only their existing content

* **[JasonColapietro/suede-creator-skills](https://github.com/JasonColapietro/suede-creator-skills) ⭐ 136 | 🐛 3 | 🌐 JavaScript | 📅 2026-09-18** - Design, UI polish, code review grading, AI evals, SEO audits.

* **[reliefeai/browser-relay](https://github.com/reliefeai/browser-relay/tree/v1.4.1/skills/browser-relay) ⭐ 128 | 🐛 5 | 🌐 JavaScript | 📅 2026-09-17** - Control an existing logged-in Chrome without stealing focus

* **[woniu9524/open-web-bridge](https://github.com/woniu9524/open-web-bridge) ⭐ 120 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-23** - Drive your real, logged-in Chrome via CDP from Claude Code, Codex, or Gemini CLI: semantic snapshots, real mouse clicks, human handoff for captchas and logins, HAR capture and replay

* **[d1vai/d1v](https://github.com/d1vai/d1v-cli/blob/main/skills/d1v/SKILL.md) ⭐ 99 | 🐛 0 | 🌐 Rust | 📅 2026-09-04** - Deploy web projects with verified previews and confirmed production releases

* **[Kevin7Qi/codex-collab](https://github.com/Kevin7Qi/codex-collab) ⭐ 96 | 🐛 1 | 🌐 TypeScript | 📅 2026-09-14** - Collaborate with Codex from Claude Code

* **[omkamal/pypict-skill](https://github.com/omkamal/pypict-claude-skill/blob/main/SKILL.md) ⭐ 95 | 🐛 0 | 🌐 Python | 📅 2026-03-22** - Pairwise test generation

* **[uucz/moyu](https://github.com/uucz/moyu) ⭐ 77 | 🐛 1 | 🌐 Python | 📅 2026-07-30** - Anti-over-engineering skill with 5 variants and 10 platforms

* **[fvadicamo/dev-agent-skills](https://github.com/fvadicamo/dev-agent-skills) ⭐ 72 | 🐛 12 | 🌐 Shell | 📅 2026-09-11** - Git and GitHub workflow skills for commits, PRs, and code reviews

* **[muthuishere/hand-drawn-diagrams](https://github.com/muthuishere/hand-drawn-diagrams) ⭐ 71 | 🐛 1 | 🌐 Python | 📅 2026-09-09** - Generate hand-drawn Excalidraw diagrams from a prompt — animated SVG, hosted edit link, and PNG export. Works with Claude Code, Codex, Gemini CLI, and any agent supporting standard skill paths

* **[eduardo-sl/go-agent-skills](https://github.com/eduardo-sl/go-agent-skills) ⭐ 71 | 🐛 0 | 🌐 Shell | 📅 2026-08-18** - Curated Go skills for code review, concurrency, testing, and architecture

* **[wendylabsinc/claude-skills](https://github.com/wendylabsinc/claude-skills) ⭐ 62 | 🐛 1 | 🌐 Swift | 📅 2026-09-04** - Swift Server development guidance with linting tool for best practices

* **[dembrandt/dembrandt-skills](https://github.com/dembrandt/dembrandt-skills) ⭐ 55 | 🐛 4 | 🌐 JavaScript | 📅 2026-09-15** - UX and design system skills: hierarchy, typography, accessibility, interactions

* **[robzolkos/skill-rails-upgrade](https://github.com/robzolkos/skill-rails-upgrade) ⭐ 54 | 🐛 0 | 📅 2026-01-27** - Analyze Rails apps and provide upgrade assessments

* **[massimodeluisa/recursive-decomposition-skill](https://github.com/massimodeluisa/recursive-decomposition-skill) ⭐ 47 | 🐛 0 | 🌐 HTML | 📅 2026-09-11** - Handle long-context tasks (100+ files, 50k+ tokens) through recursive decomposition strategies based on RLM research

* **[Rootly-AI-Labs/rootly-incident-responder](https://github.com/rootlyhq/rootly-mcp-server/blob/main/examples/skills/rootly-incident-responder.md) ⭐ 45 | 🐛 1 | 🌐 Python | 📅 2026-09-16** - AI-powered incident response with ML similarity matching, solution suggestions, and on-call coordination. Requires [Rootly MCP Server](https://github.com/rootlyhq/rootly-mcp-server) ⭐ 45 | 🐛 1 | 🌐 Python | 📅 2026-09-16

* **[Ryan-yang125/motion-lexicon](https://github.com/Ryan-yang125/motion-lexicon/tree/main/skills/motion-lexicon) ⭐ 42 | 🐛 9 | 🌐 TypeScript | 📅 2026-09-17** - Build and review product motion with installable React components

* **[wrsmith108/varlock-claude-skill](https://github.com/wrsmith108/varlock-claude-skill) ⭐ 33 | 🐛 0 | 📅 2026-03-04** - Secure environment variable management ensuring secrets are never exposed in Claude sessions, terminals, logs, or git commits

* **[rameerez/claude-code-startup-skills](https://github.com/rameerez/claude-code-startup-skills) ⭐ 30 | 🐛 0 | 🌐 Python | 📅 2026-02-23** - Skills for building and running software startups, apps, and SaaS

* **[dannwaneri/spec-writer](https://github.com/dannwaneri/spec-writer) ⭐ 28 | 🐛 0 | 📅 2026-03-18** - Turns vague requests into spec, plan, and tasks

* **[metalbear-co/skills](https://github.com/metalbear-co/skills) ⭐ 27 | 🐛 2 | 🌐 Shell | 📅 2026-09-17** - Skills that let agents code and test against your Kubernetes cluster using mirrord

* **[VoDaiLocz/kilo-kit-mcp](https://github.com/VoDaiLocz/kilo-kit-mcp) ⭐ 26 | 🐛 0 | 🌐 Python | 📅 2026-09-13** - Comprehensive library of 177 curated skills paired with an MCP runtime enforcing protocol-level C4 workflow gates, hard-gated command execution with security guardrails, and 5 cognitive reasoning engines (Tree of Thoughts DAG, Adversarial Grilling, 5-Whys Root Cause Tracer, Context Compactor, Self-Evolution) for Claude Code, Cursor, Antigravity, and Codex

* **[rainmanjam/poka-yoke](https://github.com/rainmanjam/poka-yoke) ⭐ 22 | 🐛 0 | 🌐 Python | 📅 2026-09-01** - Make misuse unrepresentable: audit, design, and enforce mistake-proofing devices

* **[ethos-link/rails-conventions](https://github.com/ethos-link/rails-conventions) ⭐ 17 | 🐛 2 | 🌐 Ruby | 📅 2026-09-17** - Rails 8 conventions for consistent production code changes

* **[ramzesenok/iOS-Accessibility-Audit-Skill](https://github.com/ramzesenok/iOS-Accessibility-Audit-Skill) ⭐ 13 | 🐛 0 | 📅 2026-03-01** - Audit iOS App against Accessibility norms

* **[saleh-alhaddad/itqan-engineering](https://github.com/saleh-alhaddad/itqan-engineering) ⭐ 10 | 🐛 0 | 🌐 Shell | 📅 2026-09-15** - Full software-engineering lifecycle in 12 skills: a resumable orchestrator plus spec, plan, TDD build, verify, five-axis review, security, and release — with approval gates before code and evidence before "done"

* **[efremidze/swift-patterns-skill](https://github.com/efremidze/swift-patterns-skill/tree/main/swift-patterns) ⭐ 9 | 🐛 1 | 📅 2026-03-16** - Modern Swift/SwiftUI best practices

* **[kensaurus/cursor-kenji](https://github.com/kensaurus/cursor-kenji) ⭐ 9 | 🐛 0 | 🌐 JavaScript | 📅 2026-09-17** - Ready-made playbooks your coding agent auto-triggers

* **[Maksim-Burtsev/simple-man](https://github.com/Maksim-Burtsev/simple-man) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2026-09-01** - Strips praise, recaps and filler from agent answers while keeping every fact you act on: findings carry location and fix, refusals carry the safe procedure, tutorials stay long-form. Benchmarked on 1,793 preregistered live calls with raw records committed. Works with Claude Code, Codex, Gemini CLI, Cursor

* **[lindblomstefan/skills-library](https://github.com/lindblomstefan/skills-library) ⭐ 1 | 🐛 8 | 🌐 JavaScript | 📅 2026-09-06** - Guided discovery skill for Claude Code: runs an interview to recommend from a catalog of 100+ AI skills; records session feedback that validates candidates over time

* **[hedralab/eskill](https://github.com/hedralab/eskill) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-08-25** - Meta-skill to build top-tier Agent Skills: spec-compliant SKILL.md, eval loop, validator, market research, numbered-file pipeline

</details>

<details>
<summary><h3 style="display:inline">Context Engineering</h3></summary>

* **[thedotmack/claude-mem](https://github.com/thedotmack/claude-mem) ⭐ 94,161 | 🐛 212 | 🌐 TypeScript | 📅 2026-09-18** - Compresses and persists agent memory across sessions
* **[Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) ⭐ 82,970 | 🐛 148 | 🌐 Python | 📅 2026-09-15** - Multi-platform search CLI for 17 sites including Chinese platforms
* **[muratcankoylan/context-fundamentals](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/context-fundamentals) ⭐ 18,008 | 🐛 53 | 🌐 Python | 📅 2026-09-11** - Understand what context is, why it matters, and the anatomy of context in agent systems
* **[muratcankoylan/context-degradation](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/context-degradation) ⭐ 18,008 | 🐛 53 | 🌐 Python | 📅 2026-09-11** - Recognize patterns of context failure: lost-in-middle, poisoning, distraction, and clash
* **[muratcankoylan/context-compression](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/context-compression) ⭐ 18,008 | 🐛 53 | 🌐 Python | 📅 2026-09-11** - Design and evaluate compression strategies for long-running sessions
* **[muratcankoylan/context-optimization](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/context-optimization) ⭐ 18,008 | 🐛 53 | 🌐 Python | 📅 2026-09-11** - Apply compaction, masking, and caching strategies
* **[muratcankoylan/multi-agent-patterns](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/multi-agent-patterns) ⭐ 18,008 | 🐛 53 | 🌐 Python | 📅 2026-09-11** - Master orchestrator, peer-to-peer, and hierarchical multi-agent architectures
* **[muratcankoylan/memory-systems](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/memory-systems) ⭐ 18,008 | 🐛 53 | 🌐 Python | 📅 2026-09-11** - Design short-term, long-term, and graph-based memory architectures
* **[muratcankoylan/tool-design](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/tool-design) ⭐ 18,008 | 🐛 53 | 🌐 Python | 📅 2026-09-11** - Build tools that agents can use effectively, including architectural reduction patterns
* **[muratcankoylan/evaluation](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/evaluation) ⭐ 18,008 | 🐛 53 | 🌐 Python | 📅 2026-09-11** - Build evaluation frameworks for agent systems
* **[rebelytics/task-observer](https://github.com/rebelytics/one-skill-to-rule-them-all) ⭐ 2,738 | 🐛 69 | 🌐 Python | 📅 2026-09-11** - Meta-skill for continuous skill improvement & automatic skill creation.
* **[NeoLabHQ/prompt-engineering](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/customaize-agent/skills/prompt-engineering) ⭐ 1,710 | 🐛 9 | 🌐 TypeScript | 📅 2026-08-26** - Widely used prompt engineering techniques and patterns, including Anthropic best practices and agent persuasion principles.
* **[vshulcz/deja-history](https://github.com/vshulcz/deja-vu/tree/main/claude-plugin/skills/deja-history) ⭐ 830 | 🐛 28 | 🌐 Go | 📅 2026-09-18** - Searches your own past sessions across 20 coding agents
* **[ohad6k/emulo](https://github.com/ohad6k/emulo) ⭐ 290 | 🐛 22 | 🌐 Python | 📅 2026-08-24** - Mines AI coding logs into personal agent profiles
* **[oliver-zehentleitner/keep-the-why](https://github.com/oliver-zehentleitner/keep-the-why) ⭐ 159 | 🐛 1 | 🌐 Python | 📅 2026-09-18** - Preserves the reasoning behind a codebase — decisions, workarounds, rejected alternatives
* **[zilliztech/mfs](https://github.com/zilliztech/mfs) ⭐ 143 | 🐛 3 | 🌐 Python | 📅 2026-07-31** - `mfs-find` / `mfs-ingest` skills that search, grep and read across your code, docs, chat (Slack/Gmail/Jira), databases and object stores as one file-like, searchable namespace; self-hosted with local ONNX embeddings
* **[khendzel/skills-janitor](https://github.com/khendzel/skills-janitor) ⭐ 119 | 🐛 2 | 🌐 Shell | 📅 2026-08-11** - Token audit, usage tracking, and swipe-to-delete skill pruning.
* **[orziz/odai](https://github.com/orziz/odai/tree/main/skills/odai) ⭐ 113 | 🐛 0 | 🌐 JavaScript | 📅 2026-09-18** - Govern evidence, responsibility routing, safety boundaries, and verified delivery
* **[Tubo2333/obsidian-knowledge-brain](https://github.com/Tubo2333/obsidian-knowledge-brain) ⭐ 97 | 🐛 1 | 🌐 Python | 📅 2026-07-02** - Cross-session knowledge memory and rule evolution for AI coding agents
* **[sametbrr/llm-wiki-manager](https://github.com/sametbrr/llm-wiki-manager) ⭐ 71 | 🐛 0 | 🌐 Python | 📅 2026-06-11** - Persistent LLM-managed personal wiki — the model writes, cross-references, and maintains the knowledge base while you curate sources. Implements Karpathy's LLM Wiki pattern with 8 operating modes.
* **[k-kolomeitsev/data-structure-protocol](https://github.com/k-kolomeitsev/data-structure-protocol) ⭐ 67 | 🐛 0 | 🌐 Python | 📅 2026-08-10** - Graph-based long-term memory skill for AI (LLM) coding agents — faster context, fewer tokens, safer refactors
* **[thousandflowers/skillreaper](https://github.com/thousandflowers/skillreaper) ⭐ 56 | 🐛 10 | 🌐 Go | 📅 2026-08-30** - Prunes unused skills, MCP servers, and subagents from transcript evidence
* **[stjbrown/agent-knowledge](https://github.com/stjbrown/agent-knowledge) ⭐ 38 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-01** - Maintains portable, cited agent knowledge bases in plain Markdown
* **[awrshift/claude-memory-kit](https://github.com/awrshift/claude-memory-kit) ⭐ 34 | 🐛 0 | 🌐 Python | 📅 2026-09-02** - Persistent memory with hooks, wiki, and daily synthesis for multi-project workflows
* **[chrono-meta/context-doctor](https://github.com/chrono-meta/forge-harness/tree/main/plugins/fh-meta/skills/context-doctor) ⭐ 14 | 🐛 2 | 🌐 Shell | 📅 2026-09-18** - Generates .claudeignore and flags context bloat before it costs tokens
* **[amirkiarafiei/subagent-cli-skills](https://github.com/amirkiarafiei/subagent-cli-skills/tree/main/skills) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2026-09-15** - Delegate heavy work to 15 other agent CLIs as subagents
* **[dankofly/perfectify](https://github.com/dankofly/perfectify) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2026-08-25** - Self-improving control kernel (DAGx AGI Kernel): hard approval stops for irreversible actions, evidence-gated completion, and a self-learning playbook with drift governance. Behaviorally evaluated; works across Claude Code, Codex, Hermes, and OpenCode

</details>

<details>
<summary><h3 style="display:inline">Specialized Domains</h3></summary>

* **[K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) ⭐ 45,446 | 🐛 13 | 🌐 Python | 📅 2026-09-14** - Scientific research and analysis skills
* **[wanshuiyin/Auto-claude-code-research-in-sleep](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) ⭐ 16,308 | 🐛 71 | 🌐 Python | 📅 2026-09-17** - Autonomous ML research with cross-model review loops and GPU deployment
* **[Orchestra-Research/AI-Research-SKILLs](https://github.com/Orchestra-Research/AI-Research-SKILLs) ⭐ 12,813 | 🐛 21 | 🌐 TeX | 📅 2026-06-16** - AI research skills for model training, inference, and MLOps
* **[Tencent/aig-agent-redteam](https://github.com/Tencent/AI-Infra-Guard/tree/main/skills/aig-agent-redteam) ⭐ 6,439 | 🐛 33 | 🌐 Python | 📅 2026-09-18** - One-command Agent red-team security assessment skill
* **[HUANGCHIHHUNGLeo/claude-real-video](https://github.com/HUANGCHIHHUNGLeo/claude-real-video) ⭐ 2,159 | 🐛 0 | 🌐 Python | 📅 2026-09-11** - Scene-aware keyframes plus transcripts so any LLM watches videos
* **[BehiSecc/vibesec](https://github.com/BehiSecc/VibeSec-Skill) ⭐ 1,281 | 🐛 1 | 📅 2026-02-17** - Helps write secure code by preventing common vulnerabilities including IDOR, XSS, SQL injection, SSRF, and weak authentication, approaching code from a bug hunter's perspective
* **[aklofas/kicad-happy](https://github.com/aklofas/kicad-happy) ⭐ 1,252 | 🐛 2 | 🌐 Python | 📅 2026-09-13** - AI-powered KiCad electronics design review and analysis
* **[prompt-security/clawsec](https://github.com/prompt-security/clawsec) ⭐ 1,106 | 🐛 27 | 🌐 JavaScript | 📅 2026-09-18** - Security skill suite with drift detection, automated audits, and skill integrity verification
* **[komal-SkyNET/claude-skill-homeassistant](https://github.com/komal-SkyNET/claude-skill-homeassistant) ⭐ 961 | 🐛 1 | 📅 2026-07-04** - Supercharge and manage Home Assistant workflows
* **[huifer/WellAlly-health](https://github.com/huifer/WellAlly-health) ⭐ 952 | 🐛 7 | 🌐 Shell | 📅 2026-07-16** - A health assistant skill for medical information analysis, symptom tracking, and wellness guidance.
* **[Optim-Agent/optim-agent](https://github.com/Optim-Agent/optim-agent) ⭐ 939 | 🐛 1 | 🌐 Python | 📅 2026-08-14** - Agent-guided optimization for measurable system tuning.
* **[ZeroPointRepo/youtube-skills](https://github.com/ZeroPointRepo/youtube-skills) ⭐ 881 | 🐛 4 | 📅 2026-09-15** - Agent skills for YouTube: pull video transcripts and discover videos (search, channel and playlist listings) via TranscriptAPI.
* **[MartinDelophy/edit-timeline-studio](https://github.com/MartinDelophy/ai-video-editor/tree/main/skills/edit-timeline-studio) ⭐ 837 | 🐛 7 | 🌐 JavaScript | 📅 2026-09-17** - Create editable video timelines with captions, voiceovers, and verified exports.
* **[GarethManning/regenerative-project-design-orchestrator](https://github.com/GarethManning/education-agent-skills/tree/main/skills/original-frameworks/regenerative-project-design-orchestrator) ⭐ 777 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-28** - Orchestrates proportionate regenerative learning projects with safeguards and stewardship
* **[GarethManning/learning-target-authoring-guide](https://github.com/GarethManning/education-agent-skills/tree/main/skills/original-frameworks/learning-target-authoring-guide) ⭐ 777 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-28** - Authors observable competency learning targets across developmental bands
* **[GarethManning/assessment-validity-checker](https://github.com/GarethManning/education-agent-skills/tree/main/skills/curriculum-assessment/assessment-validity-checker) ⭐ 777 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-28** - Audits assessments for validity, reliability, and learning alignment
* **[GarethManning/progressive-hint-ladder](https://github.com/GarethManning/education-agent-skills/tree/main/skills/student-learning/progressive-hint-ladder) ⭐ 777 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-28** - Provides graduated hints while preserving learner thinking and agency
* **[GarethManning/competency-unpacker](https://github.com/GarethManning/education-agent-skills/tree/main/skills/curriculum-assessment/competency-unpacker) ⭐ 777 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-28** - Unpacks broad competencies into assessable sub-skills and success criteria
* **[lawve-ai/awesome-legal-skills](https://github.com/lawve-ai/awesome-legal-skills) ⭐ 692 | 🐛 7 | 🌐 Python | 📅 2026-09-04** - Curated agent skills for automating legal workflows
* **[meodai/skill.color-expert](https://github.com/meodai/skill.color-expert) ⭐ 579 | 🐛 0 | 📅 2026-09-16** - Color science expert skill with 286K words of reference material covering OKLCH/OKLAB, palette generation, accessibility/contrast, color naming, pigment mixing, and historical color theory
* **[bitwize-music-studio/claude-ai-music-skills](https://github.com/bitwize-music-studio/claude-ai-music-skills) ⭐ 496 | 🐛 5 | 🌐 Python | 📅 2026-09-16** - Full-lifecycle AI music album production
* **[Orkas-AI/video-router](https://github.com/Orkas-AI/Orkas-VideoStudio/tree/main/packages/skills/video-router) ⭐ 487 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-10** - Route video requests through deterministic agent production stages
* **[sanjay3290/imagen](https://github.com/sanjay3290/ai-skills/tree/main/skills/imagen) ⭐ 423 | 🐛 4 | 🌐 Python | 📅 2026-09-10** - Generate images using Google Gemini's API
* **[morluto/rea](https://github.com/morluto/rea/tree/main/skills/reverse-engineer-anything) ⭐ 412 | 🐛 41 | 🌐 TypeScript | 📅 2026-09-08** - Reverse-engineer binaries, applications, and runtimes with REA
* **[shouldnotappearcalm/a-share-skill](https://github.com/shouldnotappearcalm/a-share-skill) ⭐ 241 | 🐛 0 | 🌐 Python | 📅 2026-06-24** - China A-share (Shanghai/Shenzhen) skills: real-time quotes, K-line history, technical indicators, events, capital flows, sector heatmaps, and paper trading. Works with Claude Code, Cursor, Codex, and Qoder
* **[talkstream/ru-text](https://github.com/talkstream/ru-text) ⭐ 234 | 🐛 1 | 🌐 Shell | 📅 2026-08-28** - Russian text quality: \~1,040 rules for typography, info-style, editorial, UX writing, business correspondence. Cross-platform: Claude Code, Codex CLI, Gemini CLI, Cursor.
* **[Alisa0808/vibe-creating-skill](https://github.com/Alisa0808/vibe-creating-skill) ⭐ 144 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-17** - Rewrites a rough idea or shot script into text-to-video prompts
* **[raintree-technology/hig-doctor](https://github.com/raintree-technology/hig-doctor) ⭐ 129 | 🐛 3 | 🌐 TypeScript | 📅 2026-09-11** - Apple Human Interface Guidelines as 14 agent skills covering platforms, foundations, components, patterns, inputs, and technologies for iOS, macOS, visionOS, watchOS, and tvOS
* **[video-db/skills](https://github.com/video-db/skills) ⭐ 120 | 🐛 1 | 🌐 Python | 📅 2026-09-11** - Realtime and batch video workflows: capture screen/audio, ingest URLs/YouTube/RTSP, transcribe, index, search, generate subtitles, edit timelines, and stream HLS output
* **[vmware-skills/VMware-AIops](https://github.com/vmware-skills/VMware-AIops) ⭐ 73 | 🐛 1 | 🌐 Python | 📅 2026-09-16** - AI-powered VMware vCenter/ESXi monitoring and operations: inventory queries, health/alarms, VM lifecycle (create, delete, snapshot, clone, migrate), vSAN management, Aria Operations analytics, and scheduled log scanning. Supports Claude Code, Gemini CLI, Codex, Aider, Trae, Kimi, and MCP.
* **[materials-simulation-skills](https://github.com/HeshamFS/materials-simulation-skills) ⭐ 68 | 🐛 0 | 🌐 Python | 📅 2026-06-25** - Agent skills for computational materials science: numerical stability, time-stepping, linear solvers, mesh generation, simulation validation, parameter optimization, and post-processing
* **[Ericyoung-183/alpha-insights](https://github.com/Ericyoung-183/alpha-insights) ⭐ 62 | 🐛 1 | 🌐 Python | 📅 2026-06-29** - Harness-enforced business research for Claude Code and Codex
* **[takechanman1228/claude-ecom](https://github.com/takechanman1228/claude-ecom) ⭐ 49 | 🐛 0 | 🌐 Python | 📅 2026-06-11** - Ecommerce CSV to business review with KPI decomposition
* **[more-io/apple-bridges](https://github.com/more-io/claude-apple-bridges) ⭐ 46 | 🐛 0 | 🌐 Swift | 📅 2026-09-05** - Native macOS app access — manage Apple Reminders, Calendar, Contacts, Notes, Mail, and tmux sessions via Swift CLI bridges
* **[honeydew-ai/honeydew-ai-coding-agents-plugins](https://github.com/honeydew-ai/honeydew-ai-coding-agents-plugins) ⭐ 41 | 🐛 2 | 🌐 Shell | 📅 2026-08-30** - 11 skills for the Honeydew semantic layer over Snowflake, Databricks, and BigQuery: model exploration, entity/relation/attribute/metric/context/domain creation, validation, query, filtering, and workspace branching
* **[perso-ai/perso-dubbing](https://github.com/perso-ai/perso-dubbing-plugin) ⭐ 38 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-14** - Video translator: dubbing, lip-sync, subtitles, and short clips
* **[frmoretto/clarity-gate](https://github.com/frmoretto/clarity-gate) ⭐ 33 | 🐛 0 | 🌐 Python | 📅 2026-03-02** - Epistemic quality verification for RAG systems
* **[NotMyself/claude-win11-speckit-update-skill](https://github.com/NotMyself/claude-win11-speckit-update-skill) ⚠️ Archived** - Windows 11 system management
* **[helius-labs/helius-skills](https://github.com/helius-labs/core-ai/tree/main/helius-skills) ⭐ 27 | 🐛 3 | 🌐 TypeScript | 📅 2026-09-17** - Ship Solana apps end-to-end; transaction sending, asset queries, real-time streaming, token swaps, prediction markets, browser wallets, and deep research into protocol internals all powered by Helius APIs, DFlow trading, and Phantom wallet integrations
* **[swaylq/humanize-chinese](https://github.com/swaylq/humanize-chinese) ⭐ 17 | 🐛 2 | 🌐 Python | 📅 2026-08-29** - Detect and rewrite AI-generated Chinese text, fully offline, no LLM
* **[ilyautov/small-business-ru](https://github.com/ilyautov/small-business-ru/tree/main/small-business-ru/skills) ⭐ 17 | 🐛 0 | 🌐 Python | 📅 2026-09-14** - 34 skills for Russian small business: taxes, deadlines, counterparty checks
* **[hanhuark/mechanical-engineering-research-skill](https://github.com/hanhuark/mechanical-engineering-research-skill) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2026-09-11** - Thermal-fluid research writing, proposals, DOE, and presentation feedback
* **[SHADOWPR0/security-bluebook-builder](https://github.com/SHADOWPR0/security-bluebook-builder) ⭐ 7 | 🐛 0 | 📅 2025-12-24** - Build security Blue Books for sensitive apps
* **[zincio/universal-checkout](https://github.com/zincio/skills/tree/master/skills/universal-checkout) ⭐ 7 | 🐛 2 | 🌐 Python | 📅 2026-09-16** - Official Zinc API (zinc.com) checkout across 50+ US retailers
* **[transloadit/skills](https://github.com/transloadit/skills/tree/main/skills) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-01** - Transloadit skill collection (6)
* **[apitube/news-api-skills](https://github.com/apitube/news-api-skills) ⭐ 0 | 🐛 0 | 📅 2026-08-23** - Search worldwide news by keyword, entity, sentiment, source, date
* **[peas/genealogy-research](https://paulo.com.br/skills/genealogy-research/SKILL.md)** - Genealogy research agent with OCR, FamilySearch, YAML data, and human-in-the-loop

</details>

<details>
<summary><h3 style="display:inline">n8n Automation</h3></summary>

* **[czlonkowski/n8n-code-javascript](https://github.com/czlonkowski/n8n-skills/tree/main/skills/n8n-code-javascript) ⭐ 6,255 | 🐛 10 | 🌐 Shell | 📅 2026-09-16** - JavaScript in n8n Code nodes with data access patterns
* **[czlonkowski/n8n-code-python](https://github.com/czlonkowski/n8n-skills/tree/main/skills/n8n-code-python) ⭐ 6,255 | 🐛 10 | 🌐 Shell | 📅 2026-09-16** - Python coding in n8n Code nodes with limitations
* **[czlonkowski/n8n-expression-syntax](https://github.com/czlonkowski/n8n-skills/tree/main/skills/n8n-expression-syntax) ⭐ 6,255 | 🐛 10 | 🌐 Shell | 📅 2026-09-16** - n8n expression syntax with {{}} and $json/$node variables
* **[czlonkowski/n8n-mcp-tools-expert](https://github.com/czlonkowski/n8n-skills/tree/main/skills/n8n-mcp-tools-expert) ⭐ 6,255 | 🐛 10 | 🌐 Shell | 📅 2026-09-16** - MCP tools guide with tool selection and node formats
* **[czlonkowski/n8n-node-configuration](https://github.com/czlonkowski/n8n-skills/tree/main/skills/n8n-node-configuration) ⭐ 6,255 | 🐛 10 | 🌐 Shell | 📅 2026-09-16** - Node configuration with dependency rules and AI connections
* **[czlonkowski/n8n-validation-expert](https://github.com/czlonkowski/n8n-skills/tree/main/skills/n8n-validation-expert) ⭐ 6,255 | 🐛 10 | 🌐 Shell | 📅 2026-09-16** - Fix n8n validation errors with error catalog
* **[czlonkowski/n8n-workflow-patterns](https://github.com/czlonkowski/n8n-skills/tree/main/skills/n8n-workflow-patterns) ⭐ 6,255 | 🐛 10 | 🌐 Shell | 📅 2026-09-16** - Workflow patterns for webhook, HTTP, database, and AI tasks

</details>

## 🔒 Security Notice

Skills in this list are curated, not audited. They may be updated, modified, or replaced by their original maintainers at any time after being added here.

Before installing or using any Agent Skill, review potential security risks and validate the source yourself.

Recommended tools:

* [Synk Skill Security Scanner](https://github.com/snyk/agent-scan) ⭐ 3,060 | 🐛 14 | 🌐 Python | 📅 2026-09-18
* [Agent Trust Hub](https://ai.gendigital.com/agent-trust-hub)

Agent skills can include prompt injections, tool poisoning, hidden malware payloads, or unsafe data handling patterns. Always review the code and use skills at your own discretion.

## Skills Paths for Other AI Coding Assistants

| Tool           | Project Path        | Global Path                   | Official Docs                                                                           |
| -------------- | ------------------- | ----------------------------- | --------------------------------------------------------------------------------------- |
| Antigravity    | `.agents/skills/`   | `~/.gemini/config/skills/`    | [Antigravity Skills](https://antigravity.google/docs/skills)                            |
| Claude Code    | `.claude/skills/`   | `~/.claude/skills/`           | [Claude Code Skills](https://docs.anthropic.com/en/docs/claude-code/skills)             |
| Codex          | `.agents/skills/`   | `~/.agents/skills/`           | [Codex Skills](https://developers.openai.com/codex/skills)                              |
| Cursor         | `.cursor/skills/`   | `~/.cursor/skills/`           | [Cursor Skills](https://cursor.com/docs/context/skills)                                 |
| Gemini CLI     | `.gemini/skills/`   | `~/.gemini/skills/`           | [Gemini CLI Skills](https://geminicli.com/docs/cli/skills/)                             |
| GitHub Copilot | `.github/skills/`   | `~/.copilot/skills/`          | [Copilot Skills](https://docs.github.com/en/copilot/concepts/agents/about-agent-skills) |
| OpenCode       | `.opencode/skills/` | `~/.config/opencode/skills/`  | [OpenCode Skills](https://opencode.ai/docs/skills)                                      |
| Windsurf       | `.windsurf/skills/` | `~/.codeium/windsurf/skills/` | [Windsurf Cascade Skills](https://docs.windsurf.com/windsurf/cascade/skills)            |

## Skill Quality Standards

As the ecosystem grows, consistent quality helps agents discover and use skills reliably. The following references and criteria keep the bar high.

### Quality Criteria

| Area                       | Guideline                                                                                                                                                               |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Description**            | Write in third person. State *what* the skill does and *when* to use it. Use specific keywords agents can match on (e.g., "PostgreSQL migration" not "database stuff"). |
| **Progressive disclosure** | Keep top-level metadata under \~100 tokens. Skill body should stay below 500 lines. Load resources (large docs, schemas) on demand, not inline.                         |
| **No absolute paths**      | Never hard-code machine-specific paths like `/Users/alice/`. Use relative paths or well-known variables (`$HOME`, `$PROJECT_ROOT`).                                     |
| **Scoped tools**           | Request only the tools the skill actually needs. Avoid blanket `"tools": ["*"]`. Declare tool dependencies explicitly.                                                  |

## 🤝 Contributing

We welcome contributions! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

* Submit new skills via PR
* Improve existing definitions

**Note:** Please don't submit skills you created 3 hours ago. We're now focusing on community-adopted skills, especially those published by development teams and proven in real-world usage. Quality over quantity.

## Contributor ♥️ Thanks

![Contributors](https://contrib.rocks/image?repo=voltagent/awesome-agent-skills\&max=500\&columns=20\&anon=1)

## License

MIT License - see [LICENSE](LICENSE)

This is a curated list. Skills listed here are created and maintained by their respective authors and teams, not by us. We select community-adopted, proven skills and do not audit, endorse, or guarantee the security or correctness of listed projects. They are not security-audited and should be reviewed before production use.

If you find an issue with a listed skill or want your skill removed, please [open an issue](https://github.com/VoltAgent/awesome-agent-skills/issues) ⭐ 34,557 | 🐛 20 | 📅 2026-09-15 and we'll take care of it promptly.

[codex-badge]: https://img.shields.io/github/stars/VoltAgent/awesome-codex-subagents?style=classic&label=Codex%20Subagents&color=000000&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0yMi4yODIgOS44MjFhNS45ODUgNS45ODUgMCAwIDAtLjUxNi00LjkxIDYuMDQ2IDYuMDQ2IDAgMCAwLTYuNTEtMi45QTYuMDY1IDYuMDY1IDAgMCAwIDQuOTgxIDQuMThhNS45ODUgNS45ODUgMCAwIDAtMy45OTggMi45IDYuMDQ2IDYuMDQ2IDAgMCAwIC43NDMgNy4wOTcgNS45OCA1Ljk4IDAgMCAwIC41MSA0LjkxMSA2LjA1MSA2LjA1MSAwIDAgMCA2LjUxNSAyLjlBNS45ODUgNS45ODUgMCAwIDAgMTMuMjYgMjRhNi4wNTYgNi4wNTYgMCAwIDAgNS43NzItNC4yMDYgNS45OSA1Ljk5IDAgMCAwIDMuOTk3LTIuOSA2LjA1NiA2LjA1NiAwIDAgMC0uNzQ3LTcuMDczek0xMy4yNiAyMi40M2E0LjQ3NiA0LjQ3NiAwIDAgMS0yLjg3Ni0xLjA0bC4xNDEtLjA4MSA0Ljc3OS0yLjc1OGEuNzk1Ljc5NSAwIDAgMCAuMzkyLS42ODF2LTYuNzM3bDIuMDIgMS4xNjhhLjA3MS4wNzEgMCAwIDEgLjAzOC4wNTJ2NS41ODNhNC41MDQgNC41MDQgMCAwIDEtNC40OTQgNC40OTR6TTMuNiAxOC4zMDRhNC40NyA0LjQ3IDAgMCAxLS41MzUtMy4wMTRsLjE0Mi4wODUgNC43ODMgMi43NTlhLjc3MS43NzEgMCAwIDAgLjc4IDBsNS44NDMtMy4zNjl2Mi4zMzJhLjA4LjA4IDAgMCAxLS4wMzMuMDYyTDkuNzQgMTkuOTVhNC41IDQuNSAwIDAgMS02LjE0LTEuNjQ2ek0yLjM0IDcuODk2YTQuNDg1IDQuNDg1IDAgMCAxIDIuMzY2LTEuOTczVjExLjZhLjc2Ni43NjYgMCAwIDAgLjM4OC42NzZsNS44MTUgMy4zNTUtMi4wMiAxLjE2OGEuMDc2LjA3NiAwIDAgMS0uMDcxIDBsLTQuODMtMi43ODZBNC41MDQgNC41MDQgMCAwIDEgMi4zNCA3Ljg3MnptMTYuNTk3IDMuODU1bC01LjgzMy0zLjM4N0wxNS4xMTkgNy4yYS4wNzYuMDc2IDAgMCAxIC4wNzEgMGw0LjgzIDIuNzkxYTQuNDk0IDQuNDk0IDAgMCAxLS42NzYgOC4xMDV2LTUuNjc4YS43OS43OSAwIDAgMC0uNDA3LS42Njd6bTIuMDEtMy4wMjNsLS4xNDEtLjA4NS00Ljc3NC0yLjc4MmEuNzc2Ljc3NiAwIDAgMC0uNzg1IDBMOS40MDkgOS4yM1Y2Ljg5N2EuMDY2LjA2NiAwIDAgMSAuMDI4LS4wNjFsNC44My0yLjc4N2E0LjUgNC41IDAgMCAxIDYuNjggNC42NnptLTEyLjY0IDQuMTM1bC0yLjAyLTEuMTY0YS4wOC4wOCAwIDAgMS0uMDM4LS4wNTdWNi4wNzVhNC41IDQuNSAwIDAgMSA3LjM3NS0zLjQ1M2wtLjE0Mi4wOEw4LjcwNCA1LjQ2YS43OTUuNzk1IDAgMCAwLS4zOTMuNjgxem0xLjA5Ny0yLjM2NWwyLjYwMi0xLjUgMi42MDcgMS41djIuOTk5bC0yLjU5NyAxLjUtMi42MDctMS41eiIvPjwvc3ZnPg==

[codex-link]: https://github.com/VoltAgent/awesome-codex-subagents

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-18._
