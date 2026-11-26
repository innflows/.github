# Innflows — Generative & Answer Engine Optimization (GEO / AEO)

**[Innflows](https://www.innflows.com)** builds engineering-grade **Generative Engine Optimization (GEO)** and **Answer Engine Optimization (AEO)** infrastructure—helping brands, B2B SaaS teams, and e-commerce merchants measure, diagnose, and improve how they are retrieved and cited across **ChatGPT Search, Google Gemini, Google AI Overviews, Google AI Mode, Grok, DeepSeek, and Qwen**.

---

## Open-Source Repositories & Benchmarks

| Repository | Category | Highlights |
| :--- | :--- | :--- |
| **[`innflows/awesome-geo-aeo`](https://github.com/innflows/awesome-geo-aeo)** | Handbook, Crawler Specs & CSV Datasets (`CC0-1.0`) | Bilingual (`EN` / `中文`) GEO & AEO engineering guide, 18-bot search-vs-training crawler matrix, copy-paste `robots.txt` / `llms.txt` / `Schema.org` JSON-LD templates, and open CSV benchmarks (`36,000+` native fan-out queries & `100` B2B SaaS domains). |
| **[`innflows/website-ai-readiness-audit`](https://github.com/innflows/website-ai-readiness-audit)** | CLI & Official MCP Server (`MIT`) | Zero-dependency Node.js & Python audit (`npx @innflows/ai-readiness-audit <url>`) + stdio MCP server (`io.github.innflows/ai-readiness-audit`) testing 14 AI crawlers, `/llms.txt` soft-404s, SSR HTML extractability, and `Schema.org` entity graphs. |

### Quick Audit in Your Terminal

```bash
npx @innflows/ai-readiness-audit https://yourdomain.com
```

---

## Empirical Research (`Innflows Research`)

- **[How ChatGPT and Gemini Actually Search the Web: Analyzing 36,000+ Native Fan-Out Queries](https://www.innflows.com/blog/seo/how-chatgpt-and-gemini-search-the-web-36k-query-study)** — Query fan-out budgets (`3.68` vs. `2.32`), `44.5%` vs. `0.0%` `site:` domain verification asymmetry, and the Brand Prior Gate.
- **[State of B2B SaaS AI Search Readiness: Auditing 100 Public Websites](https://www.innflows.com/blog/seo/state-of-b2b-saas-ai-search-readiness-100-website-study)** — `/llms.txt` adoption (`72%`), silent CDN/WAF `HTTP 403/429` blocks (`7%`), and the `76.3%` `SoftwareApplication` JSON-LD gap.

---

## Official Links

- **Website**: [https://www.innflows.com](https://www.innflows.com) · **Platform**: [https://geo.innflows.com](https://geo.innflows.com)
- **Research & Engineering Blog**: [https://www.innflows.com/blog](https://www.innflows.com/blog)
- **npm Package**: [`@innflows/ai-readiness-audit`](https://www.npmjs.com/package/@innflows/ai-readiness-audit)
- **Official MCP Registry**: [`io.github.innflows/ai-readiness-audit`](https://registry.modelcontextprotocol.io/v0/servers/io.github.innflows%2Fai-readiness-audit/versions/latest)
- **Shopify App Store**: [Innflows Website AI Audit](https://apps.shopify.com/website-audit)
