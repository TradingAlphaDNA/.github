# TradingAlphaDNA

**See what your stock and options trades actually earned.**

> **Your broker data stays on your computer.** The current local TAD app imports, processes and saves your broker files and account data on your computer, not in a TAD cloud service. In-app Upload submits to that local app; anything you choose to share through feedback, email or another service is separate.

> **券商数据留在你的电脑上。** 当前本地版在本机导入、处理和保存，不上传 TAD 云端；自行分享反馈或邮件是另一动作。

Trading records can be spread across accounts, stocks and option legs. TAD connects them so investors can review how related trades contributed to gains and losses—and how much capital they used.

Built for investors who actively manage stocks and options, especially when broker screens and spreadsheets make it hard to see the combined result.

[Download the Mac preview](https://github.com/TradingAlphaDNA/tad-showcase/releases/tag/tad-test-v1.1.0-alpha.1) · [See the product · 中英文介绍](https://tradingalphadna.github.io/tad-showcase/) · [Request a demo](mailto:hhuang68@gmail.com)

### Try the Mac technical preview

**[Download 1.1.0-alpha.1 · Mac 公开测试](https://github.com/TradingAlphaDNA/tad-showcase/releases/tag/tad-test-v1.1.0-alpha.1)** · [English instructions](https://github.com/TradingAlphaDNA/tad-showcase/blob/main/docs/testing/README.en.md) · [中文步骤](https://github.com/TradingAlphaDNA/tad-showcase/blob/main/docs/testing/README.zh.md) · [Feedback](https://github.com/TradingAlphaDNA/tad-showcase/issues/new?template=technical-preview.yml)

**Ad-hoc signed; NOT notarized / 临时签名，尚未公证。** Planned: Apple Silicon M1 and later M-series, release macOS 15/26/27. Verified: development Mac on macOS 15.2 only; test-user installation and download results are pending. No Python/Git or private source access is needed. Start with the included synthetic data in a fresh environment; keep personal records out of public feedback. [Evaluation notice](https://github.com/TradingAlphaDNA/tad-showcase/blob/main/docs/testing/TESTING-NOTICE.md).

[Supported broker files](https://github.com/TradingAlphaDNA/tad-showcase/blob/main/docs/testing/broker-support.en.md) · [中文支持矩阵](https://github.com/TradingAlphaDNA/tad-showcase/blob/main/docs/testing/broker-support.zh.md). Moomoo, Chase / J.P. Morgan investment accounts and E*TRADE use specific USD CSV layouts; a broker name alone does not establish compatibility. Statement PDFs are archive-only in the ordinary upload flow.

### Project highlights

- **Product & financial logic:** Designed stock and options review workflows covering strategy contributions, per-stock P&L, trading costs, and capital efficiency.
- **Data architecture & curation:** Designed extensible, layered data models with user review and traceable corrections to improve data quality and support additional brokers and analyses.
- **AI-native development:** Built and iterated the application, coordinating specialized AI agents for implementation, code review, testing, and release.

The project turns a practical trading-review problem into a working local application, from broker-data import and trade reconstruction to investment analysis. [Read the engineering case study](https://github.com/TradingAlphaDNA/tad-showcase/blob/main/docs/engineering-case-study.md) for the design choices and validation behind it.

### Help improve TAD

Does TAD address a problem you face when trading options? If you’d like to help us improve it, email us at **[hhuang68@gmail.com](mailto:hhuang68@gmail.com)**. We’ll follow up to learn about your needs and discuss how we can help.

Please don’t include account details or trading records in your initial email.

### Explore TAD

- [Project overview](https://github.com/TradingAlphaDNA/tad-showcase)
- Product overview: [English PDF](https://tradingalphadna.github.io/tad-showcase/TADIntro.en.pdf) · [中文 PDF](https://tradingalphadna.github.io/tad-showcase/TADIntro.cn.pdf)
- [Earlier presentation archive](https://github.com/TradingAlphaDNA/tad-showcase/releases/tag/showcase-v1.0.2)

![TAD product overview using synthetic demonstration data](https://raw.githubusercontent.com/TradingAlphaDNA/tad-showcase/main/assets/screenshots/tad-alpha1-overview.en.jpg)

*Actual public test kit 1.1.0-alpha.1; wholly synthetic accounts, saved prices dated 2026-10-26. Known results and scope limits stay visible. No personal data or promised investment performance.*

**Under active development · Planned distribution: shareware.** Pricing and usage terms are not yet announced.

The public showcase contains presentations and selected engineering explanations. The full application source remains private. The public preview is available for local evaluation as described in its evaluation notice; the showcase does not provide an open-source license. TAD runs locally without a model or API key.
