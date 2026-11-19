# Awesome-AI-Search-Engine-Semantic-Code-Search

## Top AI Search Engine & Semantic Code Search Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on AI Answer & Deep-Research Engines, Semantic Codebase Indexing, AST/LSP Symbol Search, Agentic Web Search APIs & Self-Hosted Metasearch*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Search Engine & Semantic Code Search**. These tools power citation-backed conversational web search, multi-repository semantic code indexing, AST/LSP symbol navigation for coding agents, and self-hosted private search engines.



**Examples** include Perplexity AI, Sourcegraph Cody, Greptile, Glean, Cursor, Augment Code, Phind, You.com, Kapa.ai, Tavily, and h100envy/gem-search (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosted Perplexity-style AI search engines (`Perplexica`, `SurfSense`, `Morphic`, `Open Deep Research`), semantic code search & AST/LSP indexers (`CocoIndex`, `Code-Index-MCP`, `Serena`, `Blaze`, `Zoekt`), and privacy-first metasearch engines (`SearXNG`) — ideal for AI engineers, codebase architects, and researchers building grounded, sovereign search pipelines.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Perplexity AI](https://perplexity.ai)**  

  Flagship conversational AI search and answer engine combining real-time web indexing, multi-model reasoning, Deep Research reports, and inline source citations.



- **[Sourcegraph Cody & Code Search](https://sourcegraph.com)**  

  Enterprise code intelligence and semantic search platform indexing massive multi-repository codebases to power context-aware chat, symbol navigation, and batch refactoring.



- **[Greptile](https://greptile.com)**  

  AI codebase indexing and semantic code search API/bot enabling teams and agents to query entire repositories, understand cross-file dependencies, and automate PR reviews.



- **[Glean](https://glean.com)**  

  Enterprise AI workplace search and knowledge discovery platform connecting 100+ SaaS apps, code repositories, and docs with permissions-aware semantic retrieval.



- **[Cursor (Codebase Indexing)](https://cursor.com)**  

  AI-native code editor featuring automatic Merkle-tree-synced semantic vector indexing (`@Codebase`) for instant natural-language search across large repositories.



- **[Augment Code](https://augmentcode.com)**  

  Enterprise AI software engineering platform built around a real-time semantic context engine capable of indexing and reasoning across multi-million-line monorepos.



- **[Tavily](https://tavily.com)**  

  AI-native search engine API engineered specifically for LLM agents and RAG pipelines, returning clean, ranked, snippet-extracted web context optimized for minimal token overhead.



- **[Kapa.ai](https://kapa.ai)**  

  AI technical documentation and developer support search platform indexing docs, GitHub issues, Discord threads, and codebases into cited developer Q&A assistants.



- **[Phind & You.com](https://phind.com)**  

  Developer-focused AI search engines combining live web retrieval, multi-step code reasoning, and interactive technical answer synthesis.



- **[Exa (formerly Metaphor)](https://exa.ai)**  

  Neural search engine API built with custom embedding models to retrieve semantically relevant web pages, research papers, GitHub repos, and structured entities for AI agents.





## Open-Source GitHub Projects



- **[h100envy/gem-search](https://github.com)**  

  Open-source AI-powered search engine and grounded answer utility built for fast web retrieval, semantic synthesis, and streamlined search workflows.



- **[Perplexica (`ItzCrazyKns/Perplexica`)](https://github.com)**  

  Leading open-source (`MIT`) self-hosted AI search engine powered by SearXNG and local (`Ollama`) or cloud LLMs featuring Focus Modes, citation links, and image/video search.



- **[SearXNG (`searxng/searxng`)](https://github.com)**  

  Privacy-respecting open-source (`AGPL-3.0`) metasearch engine aggregating results from 70+ search services with clean JSON API output—widely used as the web-search backend for AI agents.



- **[Morphic (`miurla/morphic`)](https://github.com)**  

  Modern open-source (`MIT`) AI-powered search engine with a generative UI built on Next.js, supporting multi-provider LLMs, SearXNG/Tavily search, and chat history persistence.



- **[SurfSense (`MODSetter/SurfSense`)](https://github.com)**  

  Open-source (`Apache-2.0`) NotebookLM and Perplexity alternative connecting personal knowledge bases (Slack, Notion, GitHub, YouTube, PDFs) with hybrid semantic + keyword search.



- **[GPT-Researcher (`assafelovic/gpt-researcher`)](https://github.com)**  

  Autonomous open-source (`Apache-2.0`) deep-research agent conducting parallelized web and local document searches to compile comprehensive, source-cited research reports.



- **[STORM (`stanford-oval/storm`)](https://github.com)**  

  Open-source (`MIT`) knowledge-curation and synthesis engine from Stanford NLP that conducts multi-perspective search queries to generate grounded, cited long-form articles.



- **[CocoIndex (`cocoindex-io/cocoindex`)](https://github.com)**  

  Ultra-fast open-source (`Apache-2.0`) data and semantic code indexing framework written in Rust featuring incremental Tree-sitter code chunking and real-time vector sync.



- **[Serena (`oraios/serena`)](https://github.com)**  

  Open-source (`MIT`) semantic coding-agent toolkit and MCP server leveraging Language Server Protocol (`LSP`) symbol graphs to give AI agents IDE-grade `find_symbol` and `find_referencing_symbols` search.



- **[Code-Index-MCP (`johnhuang316/code-index-mcp`) & mcp-server-codebase-index](https://github.com)**  

  Open-source Model Context Protocol (MCP) servers providing AI coding assistants with persistent, semantic and AST-indexed codebase search across large repositories.



- **[Zoekt (`sourcegraph/zoekt`)](https://github.com)**  

  Open-source (`Apache-2.0`) fast trigram-based code search engine built by Sourcegraph engineers for sub-second regex, symbol, and multi-repository code search at scale.



- **[OpenGrok (`oracle/opengrok`)](https://github.com)**  

  Battle-tested open-source (`CDDL-1.0`) source code search and cross-reference engine supporting full-text, symbol, definition, and version-history indexing across massive repositories.



- **[Blaze / Cody Local / Continue Codebase Indexer (`continuedev/continue`)](https://github.com)**  

  Open-source (`Apache-2.0`) local semantic codebase indexing engine combining Tree-sitter AST chunking, LanceDB embeddings, and ripgrep lexical search inside VS Code and JetBrains.



- **[ripgrep (`BurntSushi/ripgrep`) & ast-grep (`ast-grep/ast-grep`)](https://github.com)**  

  Blazing-fast open-source (`MIT` / `Unlicense`) Rust CLI tools for regex text search (`rg`) and structural Abstract Syntax Tree (`AST`) pattern search (`sg`) used by virtually every coding agent.



- **[Tree-sitter (`tree-sitter/tree-sitter`)](https://github.com)**  

  Foundational open-source (`MIT`) incremental parsing library powering syntax-aware code chunking, repository maps, and symbol extraction across 100+ programming languages.



- **[Onyx (`onyx-dot-app/onyx`, formerly Danswer)](https://github.com)**  

  Flagship open-source (`MIT` / `EE`) enterprise AI search platform connecting 40+ workplace data sources (GitHub, Confluence, Slack, Google Drive) with hybrid semantic retrieval and inline citations.



### Additional Strong Open-Source Options



- **[Farfalle (`rashadphz/farfalle`)](https://github.com)** and **[LibreChat Web Search (`danny-avila/LibreChat`)](https://github.com)** for lightweight self-hosted Perplexity-style search UIs supporting Ollama, SearXNG, and reranking.

- **[Crawl4AI (`unclecode/crawl4ai`)](https://github.com)** and **[Firecrawl (`mendableai/firecrawl`)](https://github.com)** for open-source Tavily/Exa-style web scraping and clean Markdown extraction feeding agent search pipelines.

- **[CodeBERT / UniXcoder / Jina-Code-Embeddings (`jina-ai/jina-embeddings`)](https://github.com)** and **[BGE-M3 (`FlagOpen/FlagEmbedding`)](https://github.com)** for open-weight code and multilingual dense/sparse embedding models powering semantic search.

- **[Qdrant (`qdrant/qdrant`)](https://github.com)** and **[Meilisearch (`meilisearch/meilisearch`)](https://github.com)** for fast Rust-based vector and hybrid keyword-plus-semantic search backends.

- **[kit (`cased/kit`)](https://github.com)** for an open-source Python toolkit providing AST symbol extraction, dependency graphs, and semantic code search primitives for AI developer tools.



**Frameworks for building custom systems**: Combine **h100envy/gem-search** or **Perplexica + SearXNG** (AI web search) with **CocoIndex + Tree-sitter** (semantic code indexing), **Serena MCP + ast-grep + ripgrep** (LSP/AST/lexical code search), and **Qdrant + Ollama** (local vector storage & inference) for sovereign AI search and code-retrieval engines.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).
