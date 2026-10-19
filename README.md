<div align="center">

# Awesome AI Commerce [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

### A curated list of AI agents, automation & tooling for e-commerce and small businesses 🛍️🤖

*From conversational commerce to agent frameworks, Shopify AI to autonomous support — the best tools, libraries, and resources for building AI into how businesses sell, support, and source.*

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: CC0](https://img.shields.io/badge/License-CC0-lightgrey.svg)](LICENSE)

</div>

> **Why this list?** AI is reshaping how small and medium businesses sell, support, and source — but the tooling is scattered across app stores, GitHub, and blog posts. This list pulls the best of it into one place, with a bias toward things builders can actually use. Contributions welcome!
>
> ⭐ **Star this repo** to bookmark it and help other builders find it.
>
> 🛠️ = open source · 💰 = commercial/SaaS · 🧩 = framework/library

## Contents

- [AI Agent Frameworks](#ai-agent-frameworks)
- [Agent Payment Infrastructure](#agent-payment-infrastructure)
- [Conversational Commerce](#conversational-commerce)
- [Customer Support Automation](#customer-support-automation)
- [Voice AI](#voice-ai)
- [Shopify & Storefront AI](#shopify--storefront-ai)
- [Open-Source Commerce Platforms](#open-source-commerce-platforms)
- [Product Media & Imagery](#product-media--imagery)
- [Content & Marketing](#content--marketing)
- [Sales & Lead Generation](#sales--lead-generation)
- [Returns & Post-Purchase](#returns--post-purchase)
- [Analytics & Personalization](#analytics--personalization)
- [Sourcing & Supply Chain](#sourcing--supply-chain)
- [Inventory & Demand Forecasting](#inventory--demand-forecasting)
- [Learning Resources](#learning-resources)
- [Contributing](#contributing)

## AI Agent Frameworks

*Building blocks for autonomous and multi-agent commerce workflows.*

- 🧩🛠️ [CrewAI](https://github.com/crewAIInc/crewAI) — Role-based multi-agent framework in Python; a fast path to a crew of collaborating agents.
- 🧩🛠️ [Dify](https://github.com/langgenius/dify) — Open-source LLM app platform with a visual builder for agents and workflows; self-hostable.
- 🧩🛠️ [Flowise](https://github.com/FlowiseAI/Flowise) — Drag-and-drop UI to build LLM apps and agents visually.
- 🧩🛠️ [LangGraph](https://github.com/langchain-ai/langgraph) — Stateful, graph-based orchestration for multi-step and multi-agent workflows.
- 🧩🛠️ [LlamaIndex](https://github.com/run-llama/llama_index) — Data framework for building agents over your own private documents and product data.
- 🧩🛠️ [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) — Microsoft's consolidated successor to AutoGen and Semantic Kernel, for .NET and Python teams.
- 🧩🛠️ [n8n](https://github.com/n8n-io/n8n) — Workflow automation with native AI/LLM nodes; wire agents into hundreds of business apps.
- 🧩🛠️ [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) — Lightweight framework for single- and multi-agent apps.
- 🛠️ [Specialist Swarm](https://github.com/Manish567Kumar/specialist-swarm) — A coordinator agent that fans an RFP out to specialist sub-agents and returns a finished branded proposal.

## Agent Payment Infrastructure

*Payment runtimes used by AI agents, with explicit owner approval boundaries.*

- 🛠️ [Agent Payment Node](https://github.com/nuanu-ai/agent-payment-node) — Local macOS CLI and stdio MCP payments with foreground owner approval for signing.

## Conversational Commerce

*Chat and messaging automation that sells and supports.*

- 🛠️ [BizBot](https://github.com/Manish567Kumar/bizbot) — Open-source WhatsApp automation for SMBs: auto-reply, bot flows, and a shared inbox.
- 🛠️ [Chatwoot](https://github.com/chatwoot/chatwoot) — Open-source customer engagement suite with an omnichannel inbox and AI add-ons.
- 💰 [Manychat](https://manychat.com/) — Popular no-code chat marketing for Instagram, WhatsApp, and Messenger.
- 🛠️ [Typebot](https://github.com/baptisteArno/typebot.io) — Open-source conversational form and chatbot builder you can embed or run on WhatsApp.

## Customer Support Automation

*Agentic tools that resolve tickets end-to-end — orders, returns, WISMO — across chat, email, and messaging.*

- 🛠️ [Basjoo](https://github.com/haoyiyin/basjoo) — Open-source AI support platform with a RAG knowledge base and an embeddable chat widget.
- 💰 [Gorgias](https://www.gorgias.com/) — Ecommerce-native helpdesk with AI automation and deep Shopify order actions.
- 💰 [Intercom (Fin)](https://www.intercom.com/fin) — AI agent that resolves support conversations across channels.
- 💰 [Re:amaze](https://www.reamaze.com/) — Helpdesk and chat with AI replies, aimed at SMB stores.
- 💰 [Tidio](https://www.tidio.com/) — Chat and AI support widget popular with small stores.

## Voice AI

*Give an agent a phone number — for support lines, order status, or outbound calls.*

- 🛠️ [BentoVoiceAgent](https://github.com/bentoml/BentoVoiceAgent) — Phone-calling voice agent built fully on open-source models.
- 🧩🛠️ [Bolna](https://github.com/bolna-ai/bolna) — End-to-end open-source framework for production voice agents (ASR + LLM + TTS).
- 🛠️ [Patter](https://github.com/PatterAI/Patter) — MIT-licensed voice-AI SDK; give an agent a phone number in a few lines.
- 🧩🛠️ [Vocode](https://github.com/vocodedev/vocode-core) — Open-source library for building real-time voice LLM agents over phone and web.

## Shopify & Storefront AI

*AI built into the storefront and product catalog.*

- 💰 [Describely](https://describely.ai/) — Bulk AI product descriptions, titles, and metadata for large catalogs.
- 💰 [Octane AI](https://www.octaneai.com/) — Quizzes and AI-driven personalization for Shopify stores.
- 🛠️ [Shopify Liquid Cookbook](https://github.com/Manish567Kumar/shopify-liquid-cookbook) — Copy-paste Liquid theme customizations, no apps required.
- 💰 [Shopify Magic / Sidekick](https://www.shopify.com/magic) — Shopify's built-in AI for product descriptions and store assistance.

## Open-Source Commerce Platforms

*Own your stack — headless and composable engines you can build AI directly into.*

- 🛠️ [Medusa](https://github.com/medusajs/medusa) — Flexible open-source commerce platform (Node.js) with a customization framework for agents and developers.
- 🛠️ [Saleor](https://github.com/saleor/saleor) — High-performance, GraphQL-native, headless commerce API (Python/Django).
- 🛠️ [Svelte Commerce](https://github.com/itswadesh/svelte-commerce) — Open-source headless storefront for Medusa, Shopify, Saleor, Vendure, and WooCommerce.
- 🛠️ [Vendure](https://github.com/vendurehq/vendure) — Headless commerce framework built with TypeScript, NestJS, and GraphQL.

## Product Media & Imagery

*Turn raw product shots into clean, on-brand catalog images at scale.*

- 💰 [Kive](https://kive.ai/) — Re-renders products into consistent studio scenes across a whole catalog.
- 💰 [Photoroom](https://www.photoroom.com/) — AI background removal and product-scene generation, strong at batch processing.
- 🛠️ [rembg](https://github.com/danielgatis/rembg) — Popular open-source tool and library to remove image backgrounds; scriptable for bulk catalogs.
- 💰 [remove.bg](https://www.remove.bg/) — Fast, accurate single-image background removal with an API.

## Content & Marketing

*AI copy, creative, and campaign tooling for commerce.*

- 💰 [Brevo](https://www.brevo.com/) — Budget-friendly email and SMS automation for small businesses.
- 💰 [Copy.ai](https://www.copy.ai/) — AI copywriter for product descriptions, ads, and marketing content.
- 💰 [Jasper](https://www.jasper.ai/) — AI content platform for marketing teams and brand-consistent copy.
- 💰 [Klaviyo](https://www.klaviyo.com/) — Ecommerce marketing with best-in-class predictive and AI data.
- 🛠️ [Mautic](https://github.com/mautic/mautic) — Open-source marketing automation (email, campaigns, segmentation); self-hosted.
- 💰 [Omnisend](https://www.omnisend.com/) — Email and SMS marketing built for ecommerce, with AI assist.

## Sales & Lead Generation

*Agents that find, qualify, and reach out to buyers.*

- 💰 [Instantly](https://instantly.ai/) — Cold-outreach platform with AI-assisted sending and deliverability tooling.
- 🛠️ [OpenOutreach](https://github.com/eracle/OpenOutreach) — Self-hosted open-source AI lead finder that qualifies prospects and exports a CSV.
- 🛠️ [SalesGPT](https://github.com/filip-michalsky/SalesGPT) — Context-aware AI sales agent that engages leads across voice, email, SMS, and WhatsApp.

## Returns & Post-Purchase

*Automate the return lifecycle — eligibility, exchanges, fraud holds, and resale.*

- 💰 [AfterShip](https://www.aftership.com/) — Multi-carrier shipment tracking and returns automation.
- 💰 [Loop Returns](https://www.loopreturns.com/) — Shopify-first, exchange-led returns automation.
- 💰 [Narvar](https://corp.narvar.com/) — Enterprise post-purchase experience: tracking, returns, and communications.
- 💰 [Optoro](https://www.optoro.com/) — Returns processing and resale/liquidation to recover margin.
- 💰 [ReturnGO](https://returngo.ai/) — AI-native returns and exchanges platform with policy automation.

## Analytics & Personalization

*Understand behavior and tailor the storefront to each shopper.*

- 🛠️ [Gorse](https://github.com/gorse-io/gorse) — Open-source recommendation engine (Go) for personalized product suggestions.
- 💰 [Nosto](https://www.nosto.com/) — Commerce personalization and product recommendations.
- 🛠️ [PostHog](https://github.com/PostHog/posthog) — Open-source, self-hostable product analytics, session recording, and A/B testing.
- 💰 [Rebuy](https://www.rebuyengine.com/) — AI-powered upsell, cross-sell, and personalization for Shopify.

## Sourcing & Supply Chain

*AI for supplier discovery, RFQ automation, and trade — a fast-growing frontier.*

- 💰 [Fairmarkit](https://www.fairmarkit.com/) — AI-powered sourcing that automates RFQs and supplier discovery for tail spend.
- 💰 [Keelvar](https://www.keelvar.com/) — Sourcing optimization and autonomous sourcing bots for procurement.
- 💰 [Pactum](https://pactum.com/) — Autonomous AI negotiation with suppliers at scale.
- 🛠️ [Specialist Swarm](https://github.com/Manish567Kumar/specialist-swarm) — Multi-agent RFP/proposal automation (coordinator + specialists).
- 💰 [Zapro](https://zapro.ai/) — AI-driven vendor discovery and onboarding in one hub.

## Inventory & Demand Forecasting

*Predict demand, automate reorders, and cut stockouts and overstock.*

- 🛠️ [Inventory Management](https://github.com/Manish567Kumar/inventory-management) — Factory inventory management system.
- 💰 [Inventory Planner](https://www.inventory-planner.com/) — Demand forecasting and purchase-order automation for ecommerce.
- 💰 [Monocle](https://apps.shopify.com/forecast) — ML-based reorder suggestions and PO automation for Shopify.
- 💰 [Prediko](https://www.prediko.io/) — AI forecasting and Shopify-native replenishment workflows.

## Learning Resources

- 📚 [Anthropic — Managed Agents (multi-agent)](https://platform.claude.com/docs/en/managed-agents/multi-agent) — Docs for building coordinator/specialist agent systems.
- 📚 [LangChain — AI agent frameworks guide](https://www.langchain.com/resources/ai-agent-frameworks) — Overview of the current framework landscape.
- 📚 [Shopify — AI content creation](https://www.shopify.com/blog/ai-content-creation) — Practical guide to AI tooling for stores.
- 📚 [sindresorhus/awesome](https://github.com/sindresorhus/awesome) — The master index of awesome lists across every topic.

## Contributing

Contributions make this list great! Please read [CONTRIBUTING.md](CONTRIBUTING.md), then open a PR.

**Quick rules:**
- One tool per line: `[Name](link) — one-line description.`
- Mark it 🛠️ open source · 💰 commercial · 🧩 framework where it helps.
- Keep it genuinely useful and commerce/AI relevant.
- Alphabetical within a section where possible.
- No broken links, no pure self-promo spam.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](LICENSE)

To the extent possible under law, contributors have waived all copyright and related rights to this work.
