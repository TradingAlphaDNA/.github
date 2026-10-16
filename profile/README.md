# TradingAlphaDNA

**Understand your trades. Evolve your trading.**

TradingAlphaDNA (TAD) is a local stock and options trading review and insight application. Product and engineering highlights:

- **Product & financial logic:** Designed stock and options review workflows covering strategy contributions, per-stock P&L, trading costs, and capital efficiency.
- **Data architecture & curation:** Designed extensible, layered data models with user review and traceable corrections to improve data quality and support additional brokers and analyses.
- **AI-native development:** Built and iterated the application, coordinating specialized AI agents for implementation, code review, testing, and release.

### Application architecture

| Layer | Implementation |
| --- | --- |
| Backend | Python services and deterministic financial rules, with Decimal arithmetic for monetary calculations |
| Data | Layered broker records, normalized trade data and derived analysis; traceable user curation and SQLite revision history |
| Frontend | HTML, CSS and plain JavaScript browser views, served by the local application |

AI agents support development and review. The application runs locally without a model or API key; deterministic rules produce its financial results.

**Public showcase:** Product pages, screenshots, PDFs and selected engineering explanations are available in [tad-showcase](https://github.com/TradingAlphaDNA/tad-showcase). The full application source remains private.

**Under active development · [Demo available on request](mailto:hhuang68@gmail.com) · Planned distribution: shareware**

Pricing and usage terms are not yet announced.

### Explore TAD

- [Product introduction and screenshots · 中英文网站](https://tradingalphadna.github.io/tad-showcase/)
- Product overview PDF: [English](https://tradingalphadna.github.io/tad-showcase/TADIntro.en.pdf) · [中文](https://tradingalphadna.github.io/tad-showcase/TADIntro.cn.pdf)
- [Engineering case study](https://github.com/TradingAlphaDNA/tad-showcase/blob/main/docs/engineering-case-study.md)
- [Latest showcase materials](https://github.com/TradingAlphaDNA/tad-showcase/releases/latest)

![TAD product overview using synthetic demonstration data](https://raw.githubusercontent.com/TradingAlphaDNA/tad-showcase/main/assets/screenshots/tad-product-overview.jpg)

*Actual product screen with wholly synthetic demonstration data. Known results and unresolved items remain distinct; these figures are not investment-performance claims.*
