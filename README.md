# Awesome-Legal-Research-AI

## Top Legal Research AI Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on AI-Assisted Case Law Research, Citation Analysis, Legal Q&A, Memo Drafting & Generative Legal Work*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Legal Research AI**. These tools help lawyers and legal teams research case law and statutes, generate answers with citations, draft memos, analyze documents, and accelerate traditional legal research workflows using generative AI grounded in legal content.



**Examples** include Harvey AI, Lexis+ AI, Westlaw Precision AI, vLex Vincent, Casetext CoCounsel, Paxton AI, Spellbook, Leya AI, Darrow, and LawGeex (the category leaders).



**Open-source emphasis**: Enterprise legal research AI is dominated by commercial platforms tied to proprietary databases (Westlaw, Lexis, etc.). Strong open building blocks exist around **CourtListener**, **Eyecite**, **Juriscraper**, jurisdiction-specific RAG systems (e.g., GitLaw), and MCP servers that connect AI assistants to public case law. This section lists the most practical open resources and is realistic about the gap.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Harvey AI](https://www.harvey.ai/)**  

  Enterprise legal AI platform used by large law firms and legal departments for research, drafting, and document analysis on firm and matter data.



- **[Lexis+ AI](https://www.lexisnexis.com/)**  

  Generative AI research and drafting capabilities built on the LexisNexis content ecosystem, with citation tools (Shepard’s) and answer-to-source workflows.



- **[Westlaw Precision AI / CoCounsel](https://legal.thomsonreuters.com/)**  

  Thomson Reuters AI research and assistant capabilities (including CoCounsel, formerly Casetext) integrated with Westlaw content and KeyCite.



- **[vLex Vincent](https://vlex.com/)**  

  AI research assistant from vLex with multi-jurisdiction coverage and citation tools, positioned as an independent alternative to the major U.S. databases.



- **[Casetext CoCounsel](https://casetext.com/)**  

  AI legal assistant (now part of Thomson Reuters) known for research, document review, and deposition preparation workflows.



- **[Paxton AI](https://www.paxton.ai/)**  

  Legal AI platform focused on research, drafting, and workflow support for attorneys.



- **[Spellbook](https://www.spellbook.legal/)**  

  AI contract drafting and review tool that operates inside Microsoft Word and supports legal document workflows.



- **[Leya AI](https://www.leya.law/)**  

  European-oriented legal AI platform supporting research, drafting, and document analysis.



- **[Darrow](https://www.darrow.ai/)**  

  Legal AI focused on identifying potential litigation and claim opportunities from data and public sources.



- **[LawGeex](https://www.lawgeex.com/)**  

  AI contract review and legal automation platform that evaluates contracts against playbooks and policies.



## Open-Source GitHub Projects

- **[CourtListener & Free Law Project tools](https://github.com/freelawproject)**  

  Open legal data platform providing millions of U.S. court opinions, APIs, and related tools that form the foundation for many open legal research systems.



- **[Eyecite](https://github.com/freelawproject/eyecite)**  

  Fast, robust open-source legal citation extractor used to parse and normalize citations from text.



- **[Juriscraper](https://github.com/freelawproject/juriscraper)**  

  Open-source scrapers for court opinions, oral arguments, and related content across many U.S. jurisdictions.



- **[LegalMCP and US legal MCP servers](https://github.com/)**  

  Open MCP (Model Context Protocol) servers that connect AI assistants to case law search, citations, and related legal data sources.



- **[GitLaw and jurisdiction-specific RAG systems](https://github.com/mikelninh/gitlaw)**  

  Source-grounded legal research systems (e.g., over German federal law) that emphasize retrieval, citations, and reviewable next steps.



- **[UK legal MCP and open jurisdiction servers](https://github.com/)**  

  Open MCP servers providing access to UK case law, legislation, Hansard, and citation tools for AI assistants.



- **[Open legal research assistant prototypes](https://github.com/)**  

  Community projects building RAG-based case law search, citation validation, and memo drafting on top of public corpora.



- **[Caselaw Access Project and open corpora](https://github.com/)**  

  Large open collections of U.S. court decisions and related APIs usable for training or retrieval.



- **[Citation validation and anti-hallucination open tools](https://github.com/)**  

  Libraries and pipelines that check generated citations against source corpora to reduce fabricated authorities.



- **[Awesome LegalTech and curated open lists](https://github.com/chen-friedman/awesome-legaltech)**  

  Curated collections of open-source legal AI tools, datasets, benchmarks, and learning resources.



### Additional Strong Open-Source Options

- Building on **CourtListener + Eyecite + Juriscraper** for a public-domain U.S. case law research stack.

- Using MCP servers to give local or hosted LLMs direct, checkable access to primary legal sources.

- Running jurisdiction-specific RAG systems (GitLaw-style) for transparent, source-grounded answers.

- Accepting that deep, citator-backed research on proprietary databases, enterprise security, and polished BigLaw workflows still favor commercial platforms (Harvey, Lexis+ AI, Westlaw/CoCounsel, vLex Vincent, etc.).

- Focusing open-source efforts on public-domain law, citation integrity, and tools accessible to solo practitioners, legal aid, and researchers.



**Frameworks for building custom systems**: Index public case law (CourtListener or equivalent) → extract citations with Eyecite → build a RAG pipeline with local or hosted LLMs → validate every citation against the corpus → present answers with paragraph-level sources. Suitable for research, education, legal aid, and privacy-sensitive environments. Most practicing lawyers at scale continue to rely on commercial legal research AI tied to established databases.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Legal research AI can hallucinate citations and misstate the law. All outputs require verification by a qualified attorney. Open-source systems built on public data do not replace professional research platforms or legal advice. This list is not legal advice.



---

**Made for lawyers, legal technologists, and researchers who want transparent, source-grounded legal AI.**

Let's keep legal research rigorous, citable, and as open as practical.
