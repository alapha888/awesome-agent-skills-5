# Awesome Agent Skills [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of Agent Skills (SKILL.md) for Claude Code, Codex, Gemini CLI, Cursor and other AI coding agents.

Review any skill before you install it. Skills can run code and read files on your machine.

## Contents

- [Specification and Official Docs](#specification-and-official-docs)
- [Official Skill Collections](#official-skill-collections)
- [Community Skill Collections](#community-skill-collections)
- [Skills by Category](#skills-by-category)
- [Tools](#tools)
- [Guides](#guides)
<!-- toc-end -->

## Specification and Official Docs

- [Adding Skills Support to a Client](https://agentskills.io/client-implementation/adding-skills-support) - How an agent runtime discovers, loads, and activates skills.
- [Agent Skills Overview](https://agentskills.io) - Home of the open Agent Skills format, with an introduction and links to the spec.
- [Agent Skills Specification](https://agentskills.io/specification) - Defines the SKILL.md frontmatter fields, folder layout, and progressive disclosure model.
- [agentskills/agentskills](https://github.com/agentskills/agentskills) - Source repository for the specification, docs site, and reference library.
- [Client Showcase](https://agentskills.io/clients) - List of agent products that support the Agent Skills format.

### Tool Documentation

- [Amp](https://ampcode.com/news/agent-skills) - Announcement and usage notes for Agent Skills in Amp.
- [Augment CLI](https://docs.augmentcode.com/cli/skills) - Skill locations and loading rules for the Augment command-line agent.
- [Claude API](https://platform.claude.com/docs/en/build-with-claude/skills-guide) - Uploading and using skills through the Claude API and the code execution tool.
- [Claude Apps](https://support.claude.com/en/articles/12512180-use-skills-in-claude) - Enabling, uploading, and using skills in Claude on web, desktop, and mobile.
- [Claude Code](https://code.claude.com/docs/en/skills) - Creating, scoping, and invoking skills in Claude Code.
- [Claude Platform Overview](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/overview) - How skills work across Claude products, including the loading levels.
- [Cline](https://docs.cline.bot/customization/skills) - Skill folders and activation in the Cline editor extension.
- [Cursor](https://cursor.com/docs/skills) - Project and user skill locations and invocation in Cursor.
- [Factory Droid](https://docs.factory.ai/harness/skills) - Skill setup and discovery in Factory's Droid agents.
- [Gemini CLI](https://geminicli.com/docs/cli/skills/) - Skill discovery, activation, and management commands in Gemini CLI.
- [GitHub Copilot](https://docs.github.com/en/copilot/concepts/agents/about-agent-skills) - How Copilot coding agent, Copilot CLI, and VS Code use skills.
- [GitHub Copilot CLI](https://docs.github.com/en/copilot/how-tos/copilot-cli/customize-copilot/add-skills) - Adding repository and personal skills to Copilot CLI.
- [Google Antigravity](https://antigravity.google/docs/skills) - Skill support in the Antigravity agent IDE.
- [Goose](https://goose-docs.ai/docs/guides/context-engineering/using-skills/) - Using skills in the Goose agent.
- [Kiro](https://kiro.dev/docs/skills/) - Workspace and global skills in the Kiro IDE.
- [OpenAI Codex](https://learn.chatgpt.com/docs/build-skills) - Building, installing, and invoking skills in Codex CLI, IDE extension, and app.
- [OpenCode](https://opencode.ai/docs/skills/) - Skill locations, permissions, and the skill tool in OpenCode.
- [VS Code](https://code.visualstudio.com/docs/agent-customization/agent-skills) - Using Agent Skills with Copilot agent mode in VS Code.
- [Windsurf](https://docs.devin.ai/desktop/cascade/skills) - Cascade skills in the Windsurf editor.

## Official Skill Collections

- [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins) - Anthropic plugins with skills for data, design, engineering, sales, legal, finance, and support work.
- [anthropics/skills](https://github.com/anthropics/skills) - Anthropic's reference skills, including the document skills behind Claude's file creation.
- [callstackincubator/agent-skills](https://github.com/callstackincubator/agent-skills) - Callstack skills for React Native performance, upgrades, and library authoring.
- [ClickHouse/agent-skills](https://github.com/ClickHouse/agent-skills) - ClickHouse skills for schema review, query tuning, chDB, and client libraries.
- [cloudflare/skills](https://github.com/cloudflare/skills) - Cloudflare skills for Workers, Durable Objects, Wrangler, Agents SDK, and Zero Trust.
- [datadog-labs/agent-skills](https://github.com/datadog-labs/agent-skills) - Datadog skills for APM setup, monitors, logs, RUM, and cloud integrations.
- [dbt-labs/dbt-agent-skills](https://github.com/dbt-labs/dbt-agent-skills) - dbt Labs skills for modeling, testing, the semantic layer, and migrations.
- [elastic/agent-skills](https://github.com/elastic/agent-skills) - Elastic skills for Elasticsearch, Kibana, observability, and security workflows.
- [expo/skills](https://github.com/expo/skills) - Expo skills for Expo Router, EAS builds and updates, native UI, and SDK upgrades.
- [figma/mcp-server-guide](https://github.com/figma/mcp-server-guide) - Figma skills that pair with the Figma MCP server for design-to-code and file generation.
- [firebase/agent-skills](https://github.com/firebase/agent-skills) - Firebase skills for Auth, Firestore, Hosting, security rules, and AI Logic.
- [getsentry/skills](https://github.com/getsentry/skills) - Skills the Sentry team uses for commits, PRs, code review, and security review.
- [google-labs-code/stitch-skills](https://github.com/google-labs-code/stitch-skills) - Google Stitch skills for generating designs, design systems, and components.
- [googleworkspace/cli](https://github.com/googleworkspace/cli) - Google Workspace CLI with skills for Gmail, Drive, Calendar, Docs, Sheets, and Chat.
- [grafana/skills](https://github.com/grafana/skills) - Grafana skills for PromQL, dashboards, alerting, Grafana Cloud, and k6.
- [hashicorp/agent-skills](https://github.com/hashicorp/agent-skills) - HashiCorp skills for Terraform modules, providers, tests, and Packer images.
- [huggingface/skills](https://github.com/huggingface/skills) - Hugging Face skills for datasets, model training, Spaces, Gradio, and the Hub CLI.
- [langchain-ai/langchain-skills](https://github.com/langchain-ai/langchain-skills) - LangChain skills for LangChain, LangGraph, Deep Agents, and LangSmith evals.
- [microsoft/skills](https://github.com/microsoft/skills) - Microsoft skills for Azure SDKs across .NET, Python, Java, and TypeScript.
- [mongodb/agent-skills](https://github.com/mongodb/agent-skills) - MongoDB skills for schema design, query optimization, connections, and Atlas Search.
- [neondatabase/agent-skills](https://github.com/neondatabase/agent-skills) - Neon skills for serverless Postgres, branching, auth, and egress tuning.
- [NVIDIA/skills](https://github.com/NVIDIA/skills) - NVIDIA skills for CUDA libraries, cuOpt, DeepStream, BioNeMo, and other NVIDIA products.
- [openai/skills](https://github.com/openai/skills) - OpenAI's skill catalog for Codex, split into system and curated skills.
- [prisma/skills](https://github.com/prisma/skills) - Prisma skills for the Prisma CLI, Client API, Prisma Postgres, and v7 upgrades.
- [pulumi/agent-skills](https://github.com/pulumi/agent-skills) - Pulumi skills for authoring, debugging, and migrating infrastructure from other IaC tools.
- [remotion-dev/skills](https://github.com/remotion-dev/skills) - Remotion skills for building, captioning, and rendering videos in React.
- [semgrep/skills](https://github.com/semgrep/skills) - Semgrep skills for code security, LLM application security, and writing Semgrep rules.
- [stripe/ai](https://github.com/stripe/ai) - Stripe repository whose agent plugins include skills for integration practices and API upgrades.
- [supabase/agent-skills](https://github.com/supabase/agent-skills) - Supabase skills for the Supabase platform and Postgres best practices.
- [trailofbits/skills](https://github.com/trailofbits/skills) - Trail of Bits skills for security audits, static analysis, fuzzing, and smart contract review.
- [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) - Vercel skills for React performance, UI review, writing review, and deployment.

## Community Skill Collections

- [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) - Engineering workflow skills covering specs, planning, testing, review, and shipping.
- [Jeffallan/claude-skills](https://github.com/Jeffallan/claude-skills) - Skills for full-stack roles such as framework specialists, DevOps, and testing.
- [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) - Over 160 skills for scientific Python libraries and research databases in biology, chemistry, and medicine.
- [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills) - Skills for Obsidian Markdown, Bases, JSON Canvas, and the Obsidian CLI.
- [letta-ai/skills](https://github.com/letta-ai/skills) - Shared skill repository from Letta for Letta Code, Claude Code, Codex, and other agents.
- [muratcankoylan/Agent-Skills-for-Context-Engineering](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering) - Skills on context engineering, memory systems, multi-agent patterns, and evaluation.
- [obra/superpowers](https://github.com/obra/superpowers) - Development methodology skills for brainstorming, planning, TDD, debugging, and subagent workflows.
- [tech-leads-club/agent-skills](https://github.com/tech-leads-club/agent-skills) - Skill registry that validates and scans submitted skills before listing them.
- [wshobson/agents](https://github.com/wshobson/agents) - Plugin marketplace bundling skills, agents, and commands for several agent harnesses.

## Skills by Category

### AI and Agent Development

- [claude-api](https://github.com/anthropics/skills/tree/main/skills/claude-api) - Reference for building applications on the Claude API and Anthropic SDKs.
- [context-compression](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/context-compression) - Techniques for summarizing and compacting context in long-running agent sessions.
- [huggingface-llm-trainer](https://github.com/huggingface/skills/tree/main/skills/huggingface-llm-trainer) - Fine-tunes language and vision models with TRL or Unsloth on Hugging Face Jobs.
- [langgraph-fundamentals](https://github.com/langchain-ai/langchain-skills/tree/main/config/skills/langgraph-fundamentals) - Covers StateGraph, nodes, edges, streaming, and error handling in LangGraph.
- [mcp-builder](https://github.com/anthropics/skills/tree/main/skills/mcp-builder) - Guide for designing and building MCP servers in Python or TypeScript.
- [transformers-js](https://github.com/huggingface/skills/tree/main/skills/transformers-js) - Runs Hugging Face models in JavaScript and TypeScript with Transformers.js.

### Browser Automation and Testing

- [agent-browser](https://github.com/vercel-labs/agent-browser/tree/main/skills/agent-browser) - Drives the agent-browser CLI to navigate pages, fill forms, and take screenshots.
- [dev-browser](https://github.com/SawyerHood/dev-browser/tree/main/skills/dev-browser) - Browser automation with persistent named pages through the dev-browser CLI.
- [k6](https://github.com/grafana/skills/tree/main/skills/grafana-k6/k6) - Writes and reviews k6 load, stress, soak, and browser test scripts.
- [playwright-cli](https://github.com/microsoft/playwright-cli/tree/main/skills/playwright-cli) - Automates browser actions and Playwright tests through the Playwright CLI.
- [playwright-skill](https://github.com/lackeyjb/playwright-skill/tree/main/skills/playwright-skill) - Writes and runs Playwright scripts for screenshots, responsive checks, and login flows.
- [property-based-testing](https://github.com/trailofbits/skills/tree/main/plugins/property-based-testing/skills/property-based-testing) - Writes and reviews property-based tests with Hypothesis, fast-check, proptest, and others.
- [webapp-testing](https://github.com/anthropics/skills/tree/main/skills/webapp-testing) - Tests local web applications with Playwright, including screenshots and browser logs.

### Data and Databases

- [clickhouse-best-practices](https://github.com/ClickHouse/agent-skills/tree/main/skills/clickhouse-best-practices) - Rule set for reviewing ClickHouse schemas, queries, and configuration.
- [huggingface-datasets](https://github.com/huggingface/skills/tree/main/skills/huggingface-datasets) - Queries, filters, and downloads Hugging Face datasets through the Dataset Viewer API.
- [jupyter-notebook](https://github.com/openai/skills/tree/main/skills/.curated/jupyter-notebook) - Creates and edits Jupyter notebooks from bundled templates.
- [mongodb-schema-design](https://github.com/mongodb/agent-skills/tree/main/plugins/mongodb/skills/mongodb-schema-design) - MongoDB schema patterns and anti-patterns for modeling and migration from SQL.
- [neon-postgres](https://github.com/neondatabase/agent-skills/tree/main/skills/neon-postgres) - Connections, branching, migrations, and scaling for Postgres on Neon.
- [prisma-upgrade-v7](https://github.com/prisma/skills/tree/main/prisma-upgrade-v7) - Migration guide from Prisma ORM v6 to v7.
- [query](https://github.com/duckdb/duckdb-skills/tree/main/skills/query) - Runs SQL or natural language questions against DuckDB databases and files.
- [sql-queries](https://github.com/anthropics/knowledge-work-plugins/tree/main/data/skills/sql-queries) - Writes and optimizes SQL across Snowflake, BigQuery, Databricks, and PostgreSQL.
- [supabase-postgres-best-practices](https://github.com/supabase/agent-skills/tree/main/skills/supabase-postgres-best-practices) - Postgres schema, index, and security practices maintained by Supabase.
- [using-dbt-for-analytics-engineering](https://github.com/dbt-labs/dbt-agent-skills/tree/main/skills/dbt/skills/using-dbt-for-analytics-engineering) - Builds and tests dbt models and validates results with dbt show.

### Design and Frontend

- [composition-patterns](https://github.com/vercel-labs/agent-skills/tree/main/skills/composition-patterns) - React composition patterns for replacing boolean prop sprawl with reusable APIs.
- [design-md](https://github.com/google-labs-code/stitch-skills/tree/main/plugins/stitch-utilities/skills/design-md) - Extracts a design system from a Stitch project into a DESIGN.md file.
- [figma-design-to-code](https://github.com/figma/mcp-server-guide/tree/main/skills/figma-design-to-code) - Implements Figma designs as code using the Figma MCP server.
- [figma-implement-motion](https://github.com/figma/mcp-server-guide/tree/main/skills/figma-implement-motion) - Translates Figma motion and animation into application code.
- [frontend-design](https://github.com/anthropics/skills/tree/main/skills/frontend-design) - Guidance on aesthetic direction and typography when building or reshaping UI.
- [react-best-practices](https://github.com/vercel-labs/agent-skills/tree/main/skills/react-best-practices) - React and Next.js performance rules from Vercel Engineering.
- [theme-factory](https://github.com/anthropics/skills/tree/main/skills/theme-factory) - Applies preset or generated color and font themes to slides, docs, and pages.
- [web-design-guidelines](https://github.com/vercel-labs/agent-skills/tree/main/skills/web-design-guidelines) - Reviews UI code against Vercel's Web Interface Guidelines.

### Development Workflow

- [agents-md](https://github.com/getsentry/skills/tree/main/skills/agents-md) - Creates and maintains AGENTS.md and CLAUDE.md project instruction files.
- [commit](https://github.com/getsentry/skills/tree/main/skills/commit) - Writes conventional commit messages with issue references.
- [gh-address-comments](https://github.com/openai/skills/tree/main/skills/.curated/gh-address-comments) - Addresses review comments on the current branch's pull request with the gh CLI.
- [gh-fix-ci](https://github.com/openai/skills/tree/main/skills/.curated/gh-fix-ci) - Inspects failing GitHub Actions checks, plans a fix, and implements it.
- [pr-writer](https://github.com/getsentry/skills/tree/main/skills/pr-writer) - Writes and refreshes pull request titles and descriptions.
- [spec-driven-development](https://github.com/addyosmani/agent-skills/tree/main/skills/spec-driven-development) - Writes a specification before implementation starts.
- [systematic-debugging](https://github.com/obra/superpowers/tree/main/skills/systematic-debugging) - Root-cause debugging process to follow before proposing a fix.
- [temporal-developer](https://github.com/temporalio/skill-temporal-developer) - Builds and debugs Temporal workflows, activities, and workers across SDK languages.
- [test-driven-development](https://github.com/obra/superpowers/tree/main/skills/test-driven-development) - Red-green-refactor loop applied before writing implementation code.
- [using-git-worktrees](https://github.com/obra/superpowers/tree/main/skills/using-git-worktrees) - Sets up an isolated git worktree before feature work.
- [writing-plans](https://github.com/obra/superpowers/tree/main/skills/writing-plans) - Turns a spec into a step-by-step implementation plan.

### DevOps and Infrastructure

- [dd-monitors](https://github.com/datadog-labs/agent-skills/tree/main/dd-monitors) - Lists, searches, and creates Datadog monitors with alerting practices.
- [durable-objects](https://github.com/cloudflare/skills/tree/main/skills/durable-objects) - Builds and reviews Cloudflare Durable Objects code.
- [elasticsearch-esql](https://github.com/elastic/agent-skills/tree/main/skills/elasticsearch/elasticsearch-esql) - Writes and runs ES|QL queries against Elasticsearch.
- [netlify-deploy](https://github.com/openai/skills/tree/main/skills/.curated/netlify-deploy) - Deploys and links sites on Netlify with the Netlify CLI.
- [promql](https://github.com/grafana/skills/tree/main/skills/grafana-core/promql) - Writes and optimizes PromQL for Prometheus and Grafana Mimir.
- [pulumi-best-practices](https://github.com/pulumi/agent-skills/tree/main/pulumi/skills/pulumi-best-practices) - Practices for writing and reviewing Pulumi programs and components.
- [pulumi-terraform-to-pulumi](https://github.com/pulumi/agent-skills/tree/main/migration/skills/pulumi-terraform-to-pulumi) - Migrates Terraform or OpenTofu code and state to Pulumi.
- [render-deploy](https://github.com/openai/skills/tree/main/skills/.curated/render-deploy) - Generates render.yaml Blueprints and deploys applications to Render.
- [terraform-style-guide](https://github.com/hashicorp/agent-skills/tree/main/plugins/terraform/skills/terraform-style-guide) - Generates Terraform HCL following HashiCorp style conventions.
- [terraform-test](https://github.com/hashicorp/agent-skills/tree/main/plugins/terraform/skills/terraform-test) - Writes and runs Terraform tests in .tftest.hcl files.
- [web-perf](https://github.com/cloudflare/skills/tree/main/skills/web-perf) - Audits Core Web Vitals and Lighthouse performance scores.
- [wrangler](https://github.com/cloudflare/skills/tree/main/skills/wrangler) - Runs and troubleshoots Wrangler CLI commands for Cloudflare Workers.

### Documents and Office

- [doc-coauthoring](https://github.com/anthropics/skills/tree/main/skills/doc-coauthoring) - Structured workflow for co-writing specs, proposals, and decision docs.
- [docx](https://github.com/anthropics/skills/tree/main/skills/docx) - Creates, reads, and edits Word documents and templates.
- [gws-gmail-triage](https://github.com/googleworkspace/cli/tree/main/skills/gws-gmail-triage) - Summarizes unread Gmail messages through the Google Workspace CLI.
- [notion-knowledge-capture](https://github.com/openai/skills/tree/main/skills/.curated/notion-knowledge-capture) - Turns conversations and decisions into structured Notion pages.
- [obsidian-markdown](https://github.com/kepano/obsidian-skills/tree/main/skills/obsidian-markdown) - Writes Obsidian Flavored Markdown with wikilinks, embeds, callouts, and properties.
- [pdf](https://github.com/anthropics/skills/tree/main/skills/pdf) - Extracts, merges, splits, fills, and creates PDF files.
- [pptx](https://github.com/anthropics/skills/tree/main/skills/pptx) - Creates, reads, and edits PowerPoint decks and templates.
- [xlsx](https://github.com/anthropics/skills/tree/main/skills/xlsx) - Creates, reads, and edits spreadsheets, formulas, and CSV files.

### Media and Creative

- [algorithmic-art](https://github.com/anthropics/skills/tree/main/skills/algorithmic-art) - Creates generative art with p5.js and seeded randomness.
- [canvas-design](https://github.com/anthropics/skills/tree/main/skills/canvas-design) - Produces posters and static visual designs as PNG or PDF.
- [json-canvas](https://github.com/kepano/obsidian-skills/tree/main/skills/json-canvas) - Creates and edits JSON Canvas files for mind maps and flowcharts.
- [remotion-best-practices](https://github.com/remotion-dev/skills/tree/main/skills/remotion-best-practices) - Entry point that routes to Remotion skills for video creation in React.
- [slack-gif-creator](https://github.com/anthropics/skills/tree/main/skills/slack-gif-creator) - Creates animated GIFs sized and validated for Slack.
- [transcribe](https://github.com/openai/skills/tree/main/skills/.curated/transcribe) - Transcribes audio and video with optional speaker labels.

### Mobile

- [expo-router](https://github.com/expo/skills/tree/main/plugins/expo/skills/expo-router) - File-based routing, navigation, and native stacks in Expo Router.
- [expo-upgrade](https://github.com/expo/skills/tree/main/plugins/expo/skills/expo-upgrade) - Upgrades Expo SDK versions and resolves dependency issues.
- [react-native-best-practices](https://github.com/callstackincubator/agent-skills/tree/main/skills/react-native-best-practices) - React Native performance rules for FPS, startup time, bundle size, and memory.
- [upgrading-react-native](https://github.com/callstackincubator/agent-skills/tree/main/skills/upgrading-react-native) - Upgrades React Native apps using rn-diff-purge template diffs.

### Payments and Auth

- [better-auth-best-practices](https://github.com/better-auth/skills/tree/main/better-auth/best-practices) - Configures Better Auth servers, clients, adapters, sessions, and plugins.
- [stripe-best-practices](https://github.com/stripe/ai/tree/main/providers/claude/plugin/skills/stripe-best-practices) - Guides Stripe API selection, sandbox setup, and integration decisions.
- [upgrade-stripe](https://github.com/stripe/ai/tree/main/providers/claude/plugin/skills/upgrade-stripe) - Upgrades Stripe API versions and SDKs.

### Science

- [astropy](https://github.com/K-Dense-AI/scientific-agent-skills/tree/main/skills/astropy) - Astropy workflows for units, coordinates, FITS files, and cosmology.
- [biopython](https://github.com/K-Dense-AI/scientific-agent-skills/tree/main/skills/biopython) - Sequence handling, file parsing, phylogenetics, and NCBI access with Biopython.

### Security

- [codeql](https://github.com/trailofbits/skills/tree/main/plugins/static-analysis/skills/codeql) - Scans a codebase with CodeQL data flow and taint tracking.
- [differential-review](https://github.com/trailofbits/skills/tree/main/plugins/differential-review/skills/differential-review) - Security-focused review of code changes with blast radius analysis.
- [find-bugs](https://github.com/getsentry/skills/tree/main/skills/find-bugs) - Finds bugs and security issues in the current branch's changes.
- [firebase-security-rules-auditor](https://github.com/firebase/agent-skills/tree/main/skills/firebase-security-rules-auditor) - Audits Firestore and Cloud Storage security rules for privilege escalation and bypasses.
- [gha-security-review](https://github.com/getsentry/skills/tree/main/skills/gha-security-review) - Reviews GitHub Actions workflows for exploitable patterns.
- [llm-security](https://github.com/semgrep/skills/tree/main/skills/llm-security) - Security guidance for LLM applications based on the OWASP Top 10 for LLMs.
- [security-ownership-map](https://github.com/openai/skills/tree/main/skills/.curated/security-ownership-map) - Maps code ownership and bus factor for security-sensitive files from git history.
- [security-threat-model](https://github.com/openai/skills/tree/main/skills/.curated/security-threat-model) - Writes a repository-grounded threat model with trust boundaries and abuse paths.
- [semgrep](https://github.com/trailofbits/skills/tree/main/plugins/static-analysis/skills/semgrep) - Runs Semgrep rulesets over a codebase after an approved scan plan.
- [supply-chain-risk-auditor](https://github.com/trailofbits/skills/tree/main/plugins/supply-chain-risk-auditor/skills/supply-chain-risk-auditor) - Audits dependencies for advisories, abandoned upstreams, and publisher risk.

### Writing and Marketing

- [blog-writing-guide](https://github.com/getsentry/skills/tree/main/skills/blog-writing-guide) - Writes and reviews engineering blog posts to Sentry's standards.
- [copywriting](https://github.com/coreyhaines31/marketingskills/tree/main/skills/copywriting) - Writes and rewrites marketing copy for landing, pricing, and product pages.
- [defuddle](https://github.com/kepano/obsidian-skills/tree/main/skills/defuddle) - Extracts readable Markdown from web pages with the Defuddle CLI.
- [humanizer](https://github.com/blader/humanizer) - Removes common signs of AI-generated writing from text.
- [internal-comms](https://github.com/anthropics/skills/tree/main/skills/internal-comms) - Writes status reports, leadership updates, and newsletters in set formats.
- [seo-audit](https://github.com/coreyhaines31/marketingskills/tree/main/skills/seo-audit) - Audits a site for technical and on-page SEO issues.
- [writing-guidelines](https://github.com/vercel-labs/agent-skills/tree/main/skills/writing-guidelines) - Reviews docs and prose against Vercel's writing guidelines.

## Tools

### Authoring

- [Skill Template](https://github.com/anthropics/skills/tree/main/template) - Minimal SKILL.md template from Anthropic's skills repository.
- [skill-creator](https://github.com/anthropics/skills/tree/main/skills/skill-creator) - Anthropic skill for creating, editing, and evaluating skills.
- [skill-improver](https://github.com/trailofbits/skills/tree/main/plugins/code-improver/skills/skill-improver) - Runs a review-and-fix loop over a skill until review findings are resolved.
- [skill-writer](https://github.com/getsentry/skills/tree/main/skills/skill-writer) - Creates and iterates on skills following the Agent Skills specification.

### Installers and Loaders

- [gh skill](https://cli.github.com/manual/gh_skill) - GitHub CLI command group for searching, installing, and updating skills.
- [openskills](https://github.com/numman-ali/openskills) - npm CLI that installs skills and exposes them to agents without native skill support.
- [skill-installer](https://github.com/openai/skills/tree/main/skills/.system/skill-installer) - Codex system skill that installs skills from the curated list or a GitHub path.
- [skillport](https://github.com/gotalab/skillport) - Manages skills once and serves them to agents through a CLI or MCP.
- [skills](https://github.com/vercel-labs/skills) - The `npx skills` CLI for adding skills from GitHub repositories to many agents.
- [skillz](https://github.com/intellectronica/skillz) - MCP server that exposes SKILL.md skills to clients without native support.

### Validation and Security

- [agent-scan](https://github.com/snyk/agent-scan) - Scans agents, MCP servers, and skills for prompt injection and other risks.
- [skill-scanner](https://github.com/cisco-ai-defense/skill-scanner) - Static and behavioral scanner for security issues in agent skills.
- [skill-scanner (Sentry)](https://github.com/getsentry/skills/tree/main/skills/skill-scanner) - Skill that reviews other skills for injection and unsafe instructions.
- [skills-ref](https://github.com/agentskills/agentskills/tree/main/skills-ref) - Reference Python library and CLI that validates SKILL.md files against the spec.

### Directories and Registries

- [Claude Code Plugin Marketplaces](https://code.claude.com/docs/en/plugin-marketplaces) - How to publish and install skills through Claude Code plugin marketplaces.
- [claude-plugins.dev](https://claude-plugins.dev/skills) - Searchable index of skills and plugins found on GitHub.
- [skills.sh](https://skills.sh) - Directory and leaderboard of skills installable with `npx skills`.
- [SkillsMP](https://skillsmp.com) - Search engine for skills collected from public GitHub repositories.
- [Smithery Skills](https://smithery.ai/skills) - Skill listings on the Smithery registry.
- [Tessl Registry](https://tessl.io/registry) - Package registry for versioned agent skills.

## Guides

- [Agent Skills Best Practices (agentskills.io)](https://agentskills.io/skill-creation/best-practices) - Scoping, instruction writing, and structure advice from the spec site.
- [Agent Skills Quickstart](https://agentskills.io/skill-creation/quickstart) - Walkthrough for writing a first skill.
- [Claude Agent Skills: A First Principles Deep Dive](https://leehanchung.github.io/blogs/2025/10/26/claude-skills-deep-dive/) - Examination of how Claude selects and loads skills internally.
- [Claude Skills Are Awesome, Maybe a Bigger Deal Than MCP](https://simonwillison.net/2025/Oct/16/claude-skills/) - Simon Willison's analysis of the skills model and its token efficiency.
- [Equipping Agents for the Real World with Agent Skills](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills) - Anthropic engineering post on the design of skills and progressive disclosure.
- [Evaluating Skills](https://agentskills.io/skill-creation/evaluating-skills) - How to test whether a skill improves agent results.
- [GitHub Copilot Now Supports Agent Skills](https://github.blog/changelog/2025-12-18-github-copilot-now-supports-agent-skills/) - GitHub changelog entry on skill support across Copilot surfaces.
- [Introducing Agent Skills](https://claude.com/blog/skills) - Anthropic announcement of skills in Claude apps, Claude Code, and the API.
- [Optimizing Skill Descriptions](https://agentskills.io/skill-creation/optimizing-descriptions) - Writing descriptions so agents activate a skill at the right time.
- [Skill Authoring Best Practices (Claude)](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/best-practices) - Anthropic guidance on conciseness, structure, and testing across models.
- [The Complete Guide to Building Skills for Claude](https://resources.anthropic.com/hubfs/The-Complete-Guide-to-Building-Skill-for-Claude.pdf) - Anthropic PDF covering skill planning, writing, testing, and distribution.
- [Using Scripts in Skills](https://agentskills.io/skill-creation/using-scripts) - Bundling executable scripts with a skill and calling them from instructions.

## Contributing

Contributions are welcome. Open a pull request with a link to the source for any change.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

---

Maintained by [Ali Hesari](https://alihesari.com). Follow on [GitHub](https://github.com/alihesari) and [X](https://x.com/alihesari) for updates.
