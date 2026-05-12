# 🎬 Netflix Content Strategy Dashboard — Data Analysis & Interactive Visualization

[![Live Demo](https://img.shields.io/badge/Live%20Demo-View%20Dashboard-red?style=for-the-badge&logo=vercel)](https://netflix-data-analysis-git-main-teethi-sharma-s-projects.vercel.app)
[![React](https://img.shields.io/badge/React-18-blue?style=for-the-badge&logo=react)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org)
[![Vite](https://img.shields.io/badge/Vite-Latest-purple?style=for-the-badge&logo=vite)](https://vitejs.dev)

---

## 📋 Executive Summary

This project presents an end-to-end data analysis of Netflix's global content library, delivered through a fully interactive, browser-based dashboard. The analysis explores over 8,000+ titles across movies and TV shows to uncover content trends, geographic distribution, genre patterns, and growth trajectories over time. The dashboard enables stakeholders to dynamically filter, explore, and draw insights from Netflix's catalogue — providing a data-driven foundation for content acquisition and strategic decision-making.

**🔗 Live Dashboard:** [netflix-data-analysis-git-main-teethi-sharma-s-projects.vercel.app](https://netflix-data-analysis-git-main-teethi-sharma-s-projects.vercel.app)

---

## 🧩 Business Problem

Netflix operates in an intensely competitive streaming landscape, with rivals such as Disney+, Amazon Prime, and HBO Max aggressively expanding their content libraries. To retain subscribers and attract new ones, Netflix must make informed decisions about:

- **What type of content** (Movies vs. TV Shows) resonates most with its global audience
- **Which countries and regions** are underserved or over-indexed in terms of content production
- **What genres and ratings** dominate the library and whether they align with audience demand
- **How content volume has grown** year-over-year and whether the pace is sustainable

Without clear visibility into these patterns, content and business teams risk making expensive acquisition decisions based on intuition rather than evidence. This project addresses that gap by transforming raw catalogue data into actionable visual intelligence.

---

## 🔬 Methodology

The analysis followed a structured, end-to-end data pipeline:

**1. Data Collection**
- Dataset sourced from the publicly available Netflix Titles dataset (Kaggle), containing metadata for 8,000+ movies and TV shows including title, type, country, date added, release year, rating, duration, and genre.

**2. Data Cleaning & Preprocessing**
- Handled missing values across key fields (country, rating, duration)
- Parsed and standardised date formats for time-series analysis
- Split multi-valued fields (e.g., listed genres, cast) for accurate categorical breakdowns
- Filtered and normalised country names for geographic visualisation

**3. Exploratory Data Analysis (EDA)**
- Analysed content distribution by type (Movie vs. TV Show)
- Mapped content volume by country of production
- Identified top genres and content ratings (G, PG, TV-MA, etc.)
- Tracked year-over-year content additions to Netflix's catalogue
- Examined duration trends across movies and TV series

**4. Dashboard Development**
- Built a fully interactive single-page application (SPA) using React and TypeScript
- Implemented dynamic filtering by content type, country, rating, and year
- Integrated multiple chart types (bar, pie, line, treemap) for multi-dimensional storytelling
- Deployed to Vercel via GitHub CI/CD for public access

---

## 🛠️ Skills & Tools

| Category | Technologies Used |
|---|---|
| **Frontend Framework** | React 18, TypeScript |
| **Build Tool** | Vite |
| **Data Visualisation** | Recharts, D3.js |
| **Styling** | CSS3, Tailwind CSS |
| **Data Processing** | JavaScript (array methods, data transformation) |
| **Version Control** | Git, GitHub |
| **Deployment** | Vercel (CI/CD via GitHub) |
| **Development Environment** | StackBlitz |
| **Data Source** | Netflix Titles Dataset (Kaggle) |
| **Analytical Skills** | EDA, trend analysis, geographic analysis, data cleaning |

---

## 📊 Results & Recommendations

### Key Findings

- **Movies dominate the catalogue**, making up approximately 70% of all Netflix content, while TV Shows account for the remaining 30% — suggesting an opportunity to invest more heavily in serialised content, which drives higher long-term engagement.

- **The United States is the largest content producer** on the platform by a significant margin, followed by India, United Kingdom, and Canada. However, several high-growth markets (e.g., South Korea, Nigeria, Brazil) remain relatively underrepresented relative to their subscriber bases.

- **Drama, Comedy, and Documentary** are the three most prevalent genres across the catalogue, with International Movies and TV Shows growing rapidly — reflecting Netflix's strategic push into non-English content.

- **Content additions peaked between 2018 and 2020**, with a noticeable slowdown post-2021 — likely reflecting pandemic-era production disruptions and a shift toward quality over volume in acquisition strategy.

- **TV-MA and TV-14 ratings dominate**, indicating the library skews toward mature audiences. Family-friendly and children's content represents a smaller share, which may be a gap to address for household plan growth.

### Strategic Recommendations

1. **Increase investment in TV Show originals** — serialised content creates stickier viewing habits and reduces churn, particularly among younger demographics.

2. **Expand regional content production in high-growth markets** — particularly South Korea, Nigeria, and Latin America, where local-language originals (e.g., Squid Game, Money Heist) have demonstrated global breakout potential.

3. **Diversify content ratings toward family audiences** — adding more G and PG-rated content could improve household plan value and appeal to family subscribers.

4. **Re-accelerate content volume post-2021** — the slowdown in additions represents a risk as competitors have maintained aggressive library growth; a targeted content pipeline strategy is recommended.

5. **Leverage genre data for personalisation** — the dominance of a few genres presents an opportunity to invest in underrepresented niches (e.g., true crime, anime, docuseries) that attract highly engaged niche communities.

---

## 🚀 Next Steps

- **Incorporate ratings and viewer engagement data** — merging catalogue metadata with audience ratings (e.g., IMDb scores, Rotten Tomatoes) would allow analysis of quality vs. quantity trade-offs across content types and regions.

- **Sentiment analysis on descriptions** — applying NLP to title descriptions and reviews could reveal emerging content themes and audience preferences not captured in structured metadata alone.

- **Churn & retention modelling** — linking content characteristics (genre, type, duration) to subscriber retention metrics would enable predictive modelling for smarter acquisition decisions.

- **Competitor benchmarking** — expanding the dataset to include Disney+, Amazon Prime, and HBO Max catalogues would allow side-by-side comparison of content strategy and library gaps.

- **Real-time data pipeline** — replacing the static dataset with a live data feed via the Netflix API (or third-party sources) would keep the dashboard continuously updated, enabling ongoing monitoring rather than a point-in-time snapshot.

- **Advanced filtering & user personalisation** — adding user-defined watchlists, preference profiles, and recommendation logic to the dashboard would evolve it from an analytical tool into a content discovery platform.

---

## 📁 Project Structure

```
netflix-data-analysis/
├── public/              # Static assets
├── src/
│   ├── App.tsx          # Main dashboard component
│   └── ...              # Supporting components & utilities
├── index.html
├── package.json
├── vite.config.ts
└── tsconfig.app.json
```

---

## 🏃 Run Locally

```bash
# Clone the repository
git clone https://github.com/teethisharma/netflix-data-analysis.git

# Navigate into the project
cd netflix-data-analysis

# Install dependencies
npm install

# Start the development server
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

---

## 👩‍💻 Author

**Teethi Sharma**
- GitHub: [@teethisharma](https://github.com/teethisharma)

---

*Built with ⚡ StackBlitz | Deployed on Vercel*
