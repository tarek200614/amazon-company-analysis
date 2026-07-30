<div align="center">

# 📦 Amazon.com, Inc. — A Strategic Business Analysis

### E-commerce, Cloud Infrastructure, and Artificial Intelligence at Global Scale

[![License: MIT](https://img.shields.io/badge/License-MIT-131A22.svg?style=flat-square)](./LICENSE)
[![Status](https://img.shields.io/badge/Status-Complete-FF9900.svg?style=flat-square)](#)
[![Slides](https://img.shields.io/badge/Slides-30-232F3E.svg?style=flat-square)](#-presentation-overview)
[![Data Year](https://img.shields.io/badge/Data-FY2025%20%2F%20Q1%202026-146EB4.svg?style=flat-square)](#-references)

*A university-level strategic business analysis covering Amazon's retail, cloud (AWS), advertising, AI, logistics, and sustainability strategy — with verified FY2025 financials and 2026 market data.*

</div>

---

## 📖 Project Overview

This repository is a portfolio-ready business research project analyzing **Amazon.com, Inc.** as a strategic case study. It expands a compact research draft into a full **30-slide strategic business analysis** covering the company's three reporting segments (North America, International, AWS), its emerging "third pillar" advertising business, its agentic-AI shopping strategy, its logistics and fulfillment network, and its sustainability performance — closing with an original SWOT analysis, risk assessment, and set of strategic recommendations.

The presentation itself is the primary source of truth for this repository. Every supporting file here — the README, bibliography, and original diagrams — was built by analyzing the deck slide-by-slide (text, charts, and speaker notes) and cross-verifying every statistic against primary sources such as SEC filings, Amazon's own disclosures, and Synergy Research Group's cloud-market tracking.

> **Note:** This project is coursework-style business analysis produced for educational and portfolio purposes. It is not affiliated with, endorsed by, or produced on behalf of Amazon.com, Inc.

---

## 🎯 Objectives

- Deliver a comprehensive, evidence-based strategic profile of Amazon across retail, cloud, advertising, and AI.
- Quantify **where Amazon makes its money vs. where it makes its profit** — the central tension between segment revenue share and operating-income contribution.
- Evaluate Amazon's **2025–2026 AI pivot**: the Alexa for Shopping / Rufus unification, custom AI silicon (Trainium/Inferentia), and Amazon Bedrock.
- Assess **operational and reputational trade-offs**, including a ~30,000-role corporate restructuring and a 16% jump in 2025 carbon emissions tied to AI data-center growth.
- Benchmark Amazon against its principal competitors across five distinct competitive arenas (retail, cloud, advertising, AI assistants, logistics).
- Produce original strategic synthesis — a SWOT analysis, a risk matrix, and five analyst recommendations — grounded entirely in the cited evidence base.
- Package the work as a clean, recruiter-ready GitHub repository demonstrating research rigor, business-analysis structure, and technical documentation skills.

---

## 🧩 Key Topics Covered

| Category | Topics |
|---|---|
| **Corporate Profile** | Founding, leadership, milestones (1994–2026), market position |
| **Business Model** | Three-segment structure (North America / International / AWS), 1P vs. 3P retail |
| **Financial Performance** | FY2022–FY2025 net sales & net income trend, Q4 2025 highlights, segment economics |
| **Cloud Infrastructure** | AWS revenue, service portfolio, global cloud market share, growth-rate gap vs. Azure/Google Cloud |
| **Artificial Intelligence** | Trainium/Inferentia silicon, Amazon Bedrock, Alexa for Shopping (May 2026 launch) |
| **Advertising** | The "third pillar" business, DSP, AI-referral traffic trends |
| **Logistics & Operations** | Fulfillment network footprint, robotics automation, Prime Air, EV delivery fleet |
| **Customer Experience** | Prime membership, Alexa+ auto-enrollment, AI shopping personalization |
| **Human Capital** | Workforce size and structure, 2025–2026 restructuring, revenue per employee |
| **Sustainability** | The Climate Pledge, renewable-energy matching, 2025 emissions increase |
| **Competitive Landscape** | Segment-by-segment competitor benchmarking |
| **Strategic Synthesis** | SWOT analysis, risks & regulatory environment, growth opportunities, recommendations |

---

## 🛠️ Technologies & Tools Used

**Research & Analysis**
- Primary-source verification via SEC EDGAR (10-K, 8-K filings)
- Cross-referenced market data (Synergy Research Group, Statista)
- APA 7th-edition academic citation standards

**Presentation Production**
- Microsoft PowerPoint (`.pptx`) — 30-slide deck with native charts and iconography
- PDF export for universal, layout-preserving distribution

**Documentation & Repository**
- Markdown (GitHub-flavored) for all written documentation
- Python (`reportlab`, `matplotlib`) for the APA bibliography PDF and the original data visualization
- Hand-authored SVG for original diagrams and icon set
- Git / GitHub for version control and portfolio hosting

---

## 🖥️ Presentation Overview

**`presentation/Amazon_Research_Presentation.pdf`** — a high-fidelity, 30-slide PDF export of the original PowerPoint deck, preserving all layouts, native charts, icons, and typography.

The deck is organized into four narrative arcs:

1. **Foundations (Slides 1–9)** — Executive summary, corporate profile, history, business model, and multi-year financial performance.
2. **Core Businesses (Slides 10–19)** — Retail segments, the third-party marketplace, AWS, cloud market share, AI strategy, advertising, logistics, fulfillment automation, Prime, and workforce.
3. **Sustainability & Competitive Position (Slides 20–25)** — Climate Pledge commitments, emissions performance, competitive landscape, SWOT, risks, and the regulatory environment.
4. **Strategic Outlook (Slides 26–30)** — Future growth opportunities, analyst recommendations, conclusion, sources, and closing.

Every slide's speaker notes carry its underlying source attribution; the full citation list is consolidated in [`references/sources.md`](./references/sources.md).

---

## 🎓 Learning Outcomes

Working through this project builds and demonstrates:

- **Financial statement literacy** — reading segment reporting, operating income bridges, and quality-of-earnings adjustments (e.g., non-operating equity gains inflating headline net income growth).
- **Market-structure analysis** — interpreting cloud market-share data from multiple secondary sources that disagree slightly, and presenting it responsibly as a range rather than a false-precision figure.
- **Strategic frameworks in practice** — building a SWOT analysis and risk matrix that is *actually* traceable to the preceding evidence rather than generic template language.
- **Research integrity** — distinguishing primary disclosures (SEC filings, company statements) from secondary aggregation, and flagging where a widely cited statistic could not be verified against Amazon's own filings.
- **Technical documentation & portfolio packaging** — structuring a multi-asset research project (slides, PDF, bibliography, diagrams, icons) as a clean, navigable, recruiter-ready GitHub repository.

---

## 📁 Repository Structure

```text
amazon-company-analysis/
│
├── README.md                              # You are here
├── LICENSE                                 # MIT license (original written/visual work)
│
├── presentation/
│   └── Amazon_Research_Presentation.pdf    # Full 30-slide deck, PDF export
│
├── assets/
│   ├── images/                             # Original diagrams (not in the deck)
│   │   ├── amazon-growth-flywheel.svg
│   │   └── revenue-vs-profit-contribution.png
│   ├── icons/                              # Original SVG icon set for documentation
│   │   ├── aws-cloud.svg
│   │   ├── ecommerce.svg
│   │   ├── ai-strategy.svg
│   │   ├── sustainability.svg
│   │   ├── analysis.svg
│   │   └── references.svg
│   └── screenshots/                        # High-res PNG exports of key slides
│       ├── 01-cover.png
│       ├── 02-amazon-overview.png
│       ├── 03-business-model.png
│       ├── 04-revenue-streams.png
│       ├── 05-aws-cloud-infrastructure.png
│       ├── 06-supply-chain-logistics.png
│       ├── 07-fulfillment-innovation.png
│       ├── 08-sustainability-strategy.png
│       ├── 09-swot-analysis.png
│       ├── 10-financial-performance.png
│       ├── 11-future-outlook.png
│       └── 12-conclusion.png
│
└── references/
    ├── bibliography.pdf                    # APA 7th-edition bibliography
    └── sources.md                          # Categorized source list with verification notes
```

---

## 🖼️ Preview

<table>
<tr>
<td width="50%"><img src="./assets/screenshots/01-cover.png" alt="Cover slide" width="100%"></td>
<td width="50%"><img src="./assets/screenshots/02-amazon-overview.png" alt="Amazon corporate overview slide" width="100%"></td>
</tr>
<tr>
<td width="50%"><img src="./assets/screenshots/05-aws-cloud-infrastructure.png" alt="AWS cloud infrastructure slide" width="100%"></td>
<td width="50%"><img src="./assets/screenshots/09-swot-analysis.png" alt="SWOT analysis slide" width="100%"></td>
</tr>
<tr>
<td width="50%"><img src="./assets/screenshots/10-financial-performance.png" alt="Financial performance slide" width="100%"></td>
<td width="50%"><img src="./assets/screenshots/12-conclusion.png" alt="Conclusion slide" width="100%"></td>
</tr>
</table>

**Original diagram — Revenue Share vs. Profit Contribution (FY2025):**

<img src="./assets/images/revenue-vs-profit-contribution.png" alt="Revenue vs profit contribution by segment" width="70%">

**Original diagram — Amazon's Growth Flywheel:**

<img src="./assets/images/amazon-growth-flywheel.svg" alt="Amazon growth flywheel diagram" width="70%">

*See the full 30-slide deck in [`presentation/Amazon_Research_Presentation.pdf`](./presentation/Amazon_Research_Presentation.pdf) and every slide screenshot in [`assets/screenshots/`](./assets/screenshots/).*

---

## 👤 Author

**MEGHARI Abderrahmane Tarek**
Bachelor Informatique student (AI & Data Science specialization) — ECE Paris
Based in the Île-de-France region, France

Interested in web development, data science, and cybersecurity — and open to internship opportunities in these areas. Feel free to connect for feedback, collaboration, or opportunities.

---

## 📚 References

This project's every statistic is traceable to a verified source. The full bibliography, grouped by category (official Amazon sources, SEC filings, annual reports, AWS documentation, academic papers, books, industry reports, statistics, and news), is available in two formats:

- 📄 [`references/sources.md`](./references/sources.md) — categorized Markdown source list with verification notes
- 📑 [`references/bibliography.pdf`](./references/bibliography.pdf) — formatted APA 7th-edition bibliography

---

<div align="center">

*This is an independently produced academic/portfolio analysis. Amazon, AWS, and related marks are trademarks of Amazon.com, Inc. This project is not affiliated with or endorsed by Amazon.*

**⭐ If you found this project useful for learning business analysis or portfolio structuring, consider starring the repo.**

</div>

