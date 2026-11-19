# Awesome-AI-Search-Engine-Semantic-Code-Search

## Top AI Search Engine & Semantic Code Search Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on AI Answer & Deep-Research Engines, Semantic Codebase Indexing, AST/LSP Symbol Search, Agentic Web Search APIs & Self-Hosted Metasearch*  

**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Search Engine & Semantic Code Search**. These tools power citation-backed conversational web search, multi-repository semantic code indexing, AST/LSP symbol navigation for coding agents, and self-hosted private search engines.

**Examples** include Cursor, Perplexity AI, Glean, Sourcegraph Cody, Exa, You.com, Augment Code, Greptile, Tavily, Kapa.ai, and h100envy/gem-search.

**Open-source emphasis**: This section features active projects for self-hosted Perplexity-style AI search engines (`Perplexica`, `SurfSense`, `Morphic`, `Khoj`, `Open Deep Research`), web scraping and search infrastructure (`Firecrawl`, `Crawl4AI`, `SearXNG`), semantic code search & AST/LSP indexers (`Serena`, `CocoIndex`, `Tabby`, `Bloop`, `Code-Index-MCP`, `Zoekt`), and vector/hybrid search backends (`Qdrant`, `Meilisearch`) — ideal for AI engineers, codebase architects, and researchers building grounded search pipelines.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

---

## Sector Overview & Market Dynamics

The global market for AI-driven search, enterprise discovery, and semantic code intelligence is estimated at approximately **$6.5B to $9.2B in 2026**, projected to exceed **$32B by 2032** at a 30%+ CAGR. Market dynamics reflect **moderate fragmentation with emergent "winner-takes-most" consolidation** across core sub-layers: general conversational search and developer IDE context engines exhibit aggressive tier-one concentration around category anchors (e.g., Cursor in AI code editing, Perplexity in conversational search), whereas enterprise knowledge federation, agentic search APIs, and self-hosted local RAG remain highly diverse and competitive.

---

## SaaS/Hosted Platforms

| Platform | Company Scale (Valuation / Revenue) | Pricing (Starting Paid Tier) | Free Tier Limits / Free Trial | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Cursor](https://cursor.com)** | **$29.3B Valuation** (~$1B+ ARR) | **$20/user/month** (Pro plan) | **Permanent Free Tier (Hobby)**: 2-week Pro trial upon signup; perpetual free plan includes 2,000 completions/month, basic agent/codebase queries, and standard (slow-queue) frontier model requests during peak hours. | AI-native code editor featuring automatic Merkle-tree-synced semantic vector indexing (`@Codebase`) for instant natural-language search across large repositories. |
| **[Perplexity AI](https://perplexity.ai)** | **$20.0B Valuation** (~$200M–$450M ARR) | **$20/month** ($17/month billed annually for Pro) | **Permanent Free Tier**: Unlimited standard quick searches with citations; up to 3 Pro (multi-step reasoning) searches per day; 1 Deep Research report per month; file upload capped at rolling weekly limits (max 40 MB/file). | Flagship conversational AI search and answer engine combining real-time web indexing, multi-model reasoning, Deep Research reports, and inline source citations. |
| **[Glean](https://glean.com)** | **$7.2B Valuation** (~$300M ARR) | **$45/user/month** (Enterprise contracts typically start at ~$30,000+/year with 100-seat minimums) | **No Free Tier / No Self-Serve Free Trial**: Evaluation is available exclusively via scheduled sales demos and negotiated enterprise Proof-of-Concept (POC) engagements. | Enterprise AI workplace search and knowledge discovery platform connecting 100+ SaaS apps, code repositories, and docs with permissions-aware semantic retrieval. |
| **[Sourcegraph Cody](https://sourcegraph.com)** | **$2.6B Valuation** (~$32M–$50M ARR) | **$19/user/month** (Enterprise Cody starting tier; custom deployment contracts) | **No Permanent Free Tier**: Cody standalone free tiers were retired in mid-2025; access is provided via enterprise team trials (14 to 30 days) arranged through enterprise sales. | Enterprise code intelligence and semantic search platform indexing massive multi-repository codebases to power context-aware chat, symbol navigation, and batch refactoring. |
| **[Exa (formerly Metaphor)](https://exa.ai)** | **$2.2B Valuation** (~$100M ARR) | **$4 per 1,000 searches** (Lite) / **$7 per 1,000 searches** (Auto/Fast); Websets plans start at **$49/month** | **Permanent Free Tier**: **$10 in free API credits every month** (~2,500 Lite searches or ~1,400 Auto searches) with a one-time $10 onboarding bonus; rate-limited at 10 QPS; no credit card required. | Neural search engine API built with custom embedding models to retrieve semantically relevant web pages, research papers, GitHub repos, and structured entities for AI agents. |
| **[You.com](https://you.com)** | **$1.5B Valuation** | **$20/month** (Pro plan); API starts at **$5 per 1,000 queries** | **Permanent Free Tier**: Web app includes basic search queries; API provides **100 free search calls per day** without requiring a credit card. | AI search engine and search API infrastructure for agents combining live web retrieval, multi-model reasoning, and clean markdown extraction. |
| **[Augment Code](https://augmentcode.com)** | **$977M Valuation** (~$20M ARR) | **$20/month** (Standard plan; shared credit pool architecture) | **No Permanent Free Tier**: Offers a **14-day free trial** for evaluation; subsequent access requires a paid monthly workspace subscription or enterprise POC. | Enterprise AI software engineering platform built around a real-time semantic context engine capable of indexing and reasoning across multi-million-line monorepos. |
| **[Greptile](https://greptile.com)** | **$750M Valuation** (Series B) | **$1 per credit** (Pro plan; no per-seat fees, pooled across team) | **Permanent Free Tier (Starter)**: **50 free credits per month** for 1 developer across unlimited repositories; 14-day free trial for Pro team tier; free for open-source maintainers. | AI codebase indexing and semantic code search API/bot enabling teams and agents to query entire repositories, understand cross-file dependencies, and automate PR reviews. |
| **[Tavily](https://tavily.com)** | **$275M Acquisition** (by Nebius) | **$30/month** (Project plan, includes 4,000 credits; $0.008/credit overage) | **Permanent Free Tier (Researcher)**: **1,000 API credits per month** (1 search = 1 credit; extract = 1 credit per 5 URLs); capped at 100 requests per minute; no credit card required. | AI-native search engine API engineered specifically for LLM agents and RAG pipelines, returning clean, ranked, snippet-extracted web context optimized for minimal token overhead. |
| **[Kapa.ai](https://kapa.ai)** | **~$15M–$25M Est. Valuation** (~$1.2M ARR) | **$299/month** (Growth plan; custom quotes for high volume) | **14-Day Free Trial**: Full access for 14 days capped at 1 knowledge index, up to 5,000 crawled pages, 5,000 retrieval queries, and 1,000 generated answers; free program for open-source projects. | AI technical documentation and developer support search platform indexing docs, GitHub issues, Discord threads, and codebases into cited developer Q&A assistants. |

---

## Open-Source GitHub Projects

*Sorted by GitHub Star Count (descending)*

- **[Firecrawl (`mendableai/firecrawl`)](https://github.com/mendableai/firecrawl)** [![GitHub stars](https://img.shields.io/github/stars/mendableai/firecrawl?style=social&color=white)](https://github.com/mendableai/firecrawl/stargazers)  
  Turn entire websites into clean, LLM-ready markdown or structured data with crawl, scrape, map, and extract endpoints built specifically for AI search engines and agents.

- **[RAGFlow (`infiniflow/ragflow`)](https://github.com/infiniflow/ragflow)** [![GitHub stars](https://img.shields.io/github/stars/infiniflow/ragflow?style=social&color=white)](https://github.com/infiniflow/ragflow/stargazers)  
  Open-source RAG engine based on deep document understanding and multi-modal semantic search, synthesizing grounded answers with complete citations across complex enterprise corpora.

- **[Crawl4AI (`unclecode/crawl4ai`)](https://github.com/unclecode/crawl4ai)** [![GitHub stars](https://img.shields.io/github/stars/unclecode/crawl4ai?style=social&color=white)](https://github.com/unclecode/crawl4ai/stargazers)  
  Open-source, lightning-fast web crawler and scraper tailored for LLMs and AI pipelines, outputting structured Markdown, chunks, and citations with minimal latency.

- **[ripgrep (`BurntSushi/ripgrep`)](https://github.com/BurntSushi/ripgrep)** [![GitHub stars](https://img.shields.io/github/stars/BurntSushi/ripgrep?style=social&color=white)](https://github.com/BurntSushi/ripgrep/stargazers)  
  Blazingly fast line-oriented regex search tool respecting gitignore patterns, widely embedded in AI coding agents and local codebase indexers as the lexical retrieval backbone.

- **[Meilisearch (`meilisearch/meilisearch`)](https://github.com/meilisearch/meilisearch)** [![GitHub stars](https://img.shields.io/github/stars/meilisearch/meilisearch?style=social&color=white)](https://github.com/meilisearch/meilisearch/stargazers)  
  Lightning-fast, Rust-based open-source search engine providing typo-tolerant full-text search and hybrid semantic search vector capabilities via an intuitive RESTful API.

- **[LibreChat (`danny-avila/LibreChat`)](https://github.com/danny-avila/LibreChat)** [![GitHub stars](https://img.shields.io/github/stars/danny-avila/LibreChat?style=social&color=white)](https://github.com/danny-avila/LibreChat/stargazers)  
  Enhanced open-source AI platform featuring multi-model orchestration, integrated web search (SearXNG/Google/Bing/Tavily), file retrieval, and agents with source citations.

- **[SearXNG (`searxng/searxng`)](https://github.com/searxng/searxng)** [![GitHub stars](https://img.shields.io/github/stars/searxng/searxng?style=social&color=white)](https://github.com/searxng/searxng/stargazers)  
  Privacy-respecting open-source metasearch engine aggregating results from 70+ search services with JSON API output—widely deployed as the default self-hosted web-search backend for AI agents.

- **[Perplexica (`ItzCrazyKns/Perplexica`)](https://github.com/ItzCrazyKns/Perplexica)** [![GitHub stars](https://img.shields.io/github/stars/ItzCrazyKns/Perplexica?style=social&color=white)](https://github.com/ItzCrazyKns/Perplexica/stargazers)  
  Self-hosted AI search engine alternative to Perplexity AI powered by SearXNG and local (Ollama) or cloud LLMs, featuring specialized Focus Modes and cited references.

- **[Khoj (`khoj-ai/khoj`)](https://github.com/khoj-ai/khoj)** [![GitHub stars](https://img.shields.io/github/stars/khoj-ai/khoj?style=social&color=white)](https://github.com/khoj-ai/khoj/stargazers)  
  Open-source AI second brain and self-hosted search engine that indexes personal notes, documents, PDFs, GitHub code, and web content with citation-backed semantic retrieval.

- **[Continue (`continuedev/continue`)](https://github.com/continuedev/continue)** [![GitHub stars](https://img.shields.io/github/stars/continuedev/continue?style=social&color=white)](https://github.com/continuedev/continue/stargazers)  
  Leading open-source AI code assistant for VS Code and JetBrains featuring an embedded codebase indexer (`@codebase`) combining Tree-sitter AST chunking and LanceDB vector search.

- **[Qdrant (`qdrant/qdrant`)](https://github.com/qdrant/qdrant)** [![GitHub stars](https://img.shields.io/github/stars/qdrant/qdrant?style=social&color=white)](https://github.com/qdrant/qdrant/stargazers)  
  High-performance open-source vector search engine and database written in Rust with extended filtering and hybrid search support, ideal for production semantic search backends.

- **[Tabby (`tabbyML/tabby`)](https://github.com/tabbyML/tabby)** [![GitHub stars](https://img.shields.io/github/stars/tabbyML/tabby?style=social&color=white)](https://github.com/tabbyML/tabby/stargazers)  
  Self-hosted AI coding assistant with built-in repository context indexing, AST parsing, and code search engine powering privacy-first code completion and inline navigation.

- **[Onyx (`onyx-dot-app/onyx`, formerly Danswer)](https://github.com/onyx-dot-app/onyx)** [![GitHub stars](https://img.shields.io/github/stars/onyx-dot-app/onyx?style=social&color=white)](https://github.com/onyx-dot-app/onyx/stargazers)  
  Enterprise open-source AI workplace search platform connecting 40+ workplace data sources (GitHub, Confluence, Slack, Google Drive) with hybrid semantic retrieval and verified citations.

- **[STORM (`stanford-oval/storm`)](https://github.com/stanford-oval/storm)** [![GitHub stars](https://img.shields.io/github/stars/stanford-oval/storm?style=social&color=white)](https://github.com/stanford-oval/storm/stargazers)  
  Open-source knowledge curation and research engine from Stanford NLP that conducts multi-perspective search queries to generate grounded, cited long-form analytical articles.

- **[Serena (`oraios/serena`)](https://github.com/oraios/serena)** [![GitHub stars](https://img.shields.io/github/stars/oraios/serena?style=social&color=white)](https://github.com/oraios/serena/stargazers)  
  Semantic coding-agent toolkit and MCP server leveraging Language Server Protocol (LSP) symbol graphs to provide AI agents with precise `find_symbol` and `find_referencing_symbols` search.

- **[GPT-Researcher (`assafelovic/gpt-researcher`)](https://github.com/assafelovic/gpt-researcher)** [![GitHub stars](https://img.shields.io/github/stars/assafelovic/gpt-researcher?style=social&color=white)](https://github.com/assafelovic/gpt-researcher/stargazers)  
  Autonomous open-source deep-research agent conducting parallelized web and local document searches to compile detailed, citation-backed research reports.

- **[Tree-sitter (`tree-sitter/tree-sitter`)](https://github.com/tree-sitter/tree-sitter)** [![GitHub stars](https://img.shields.io/github/stars/tree-sitter/tree-sitter?style=social&color=white)](https://github.com/tree-sitter/tree-sitter/stargazers)  
  Foundational incremental parsing library powering syntax-aware code chunking, repository symbol maps, and structural AST extraction across 100+ programming languages.

- **[SurfSense (`MODSetter/SurfSense`)](https://github.com/MODSetter/SurfSense)** [![GitHub stars](https://img.shields.io/github/stars/MODSetter/SurfSense?style=social&color=white)](https://github.com/MODSetter/SurfSense/stargazers)  
  Open-source alternative to NotebookLM and Perplexity connecting personal knowledge bases (Slack, Notion, GitHub, YouTube, PDFs) with hybrid semantic + keyword search.

- **[ast-grep (`ast-grep/ast-grep`)](https://github.com/ast-grep/ast-grep)** [![GitHub stars](https://img.shields.io/github/stars/ast-grep/ast-grep?style=social&color=white)](https://github.com/ast-grep/ast-grep/stargazers)  
  Fast structural Abstract Syntax Tree (AST) code search and rewriting tool used by coding agents to query syntactic code patterns across large codebases.

- **[CocoIndex (`cocoindex-io/cocoindex`)](https://github.com/cocoindex-io/cocoindex)** [![GitHub stars](https://img.shields.io/github/stars/cocoindex-io/cocoindex?style=social&color=white)](https://github.com/cocoindex-io/cocoindex/stargazers)  
  High-speed data and semantic code indexing framework written in Rust featuring incremental Tree-sitter code chunking and real-time vector sync.

- **[Bloop (`BloopAI/bloop`)](https://github.com/BloopAI/bloop)** [![GitHub stars](https://img.shields.io/github/stars/BloopAI/bloop?style=social&color=white)](https://github.com/BloopAI/bloop/stargazers)  
  Fast code search engine using Tree-sitter, Rust, and semantic vector embeddings to search codebases using natural language and regex queries.

- **[Morphic (`miurla/morphic`)](https://github.com/miurla/morphic)** [![GitHub stars](https://img.shields.io/github/stars/miurla/morphic?style=social&color=white)](https://github.com/miurla/morphic/stargazers)  
  Open-source AI-powered search engine with a generative UI built on Next.js, supporting multi-provider LLMs, SearXNG/Tavily search, and chat history persistence.

- **[OpenGrok (`oracle/opengrok`)](https://github.com/oracle/opengrok)** [![GitHub stars](https://img.shields.io/github/stars/oracle/opengrok?style=social&color=white)](https://github.com/oracle/opengrok/stargazers)  
  Battle-tested source code search and cross-reference engine supporting full-text, symbol, definition, and version-history indexing across massive repositories.

- **[Farfalle (`rashadphz/farfalle`)](https://github.com/rashadphz/farfalle)** [![GitHub stars](https://img.shields.io/github/stars/rashadphz/farfalle?style=social&color=white)](https://github.com/rashadphz/farfalle/stargazers)  
  Lightweight self-hosted AI search engine UI supporting local and cloud LLMs (Ollama, OpenAI, Groq) with SearXNG and Tavily web retrieval.

- **[Zoekt (`sourcegraph/zoekt`)](https://github.com/sourcegraph/zoekt)** [![GitHub stars](https://img.shields.io/github/stars/sourcegraph/zoekt?style=social&color=white)](https://github.com/sourcegraph/zoekt/stargazers)  
  Fast trigram-based code search engine engineered by Sourcegraph for sub-second regex, symbol, and multi-repository code search at scale.

- **[Code-Index-MCP (`johnhuang316/code-index-mcp`)](https://github.com/johnhuang316/code-index-mcp)** [![GitHub stars](https://img.shields.io/github/stars/johnhuang316/code-index-mcp?style=social&color=white)](https://github.com/johnhuang316/code-index-mcp/stargazers)  
  Open-source Model Context Protocol (MCP) server providing AI coding assistants with persistent, semantic, and AST-indexed codebase search.

- **[h100envy/gem-search (`h100envy/gem-search`)](https://github.com/h100envy/gem-search)** [![GitHub stars](https://img.shields.io/github/stars/h100envy/gem-search?style=social&color=white)](https://github.com/h100envy/gem-search/stargazers)  
  Open-source AI-powered search engine and grounded answer utility built for fast web retrieval, semantic synthesis, and streamlined search workflows.

---

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow the table/badge formatting conventions).
3. Ensure all links are live, pricing and free tier specs are explicitly stated, and open-source star badges are linked to stargazers.
4. Open a Pull Request detailing your additions.

---

## Disclaimer

All product names, logos, brands, and registered trademarks belong to their respective owners. Mention in this repository does not imply endorsement or official affiliation.
