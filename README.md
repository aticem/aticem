### Hi there 👋 I'm Atilay

- 🏗️ Civil engineer (MSc, UK) working in **solar farm construction** — and building the software I wish the site had.
- 🤖 Passionate about **data, machine learning, AI and maths**; these days mostly shipping full-stack apps with LLMs inside them.
- 📚 Lifelong learner.

**Reach me:** [LinkedIn](https://www.linkedin.com/in/acsamiloglu/) · [Medium](https://atilaycemsamiloglu.medium.com) · [Kaggle](https://www.kaggle.com/atilaysamiloglu)

> 🔒 **My repositories are private.** This page describes what each project does.
> Source code is available on request — just ask on LinkedIn.

---

## ☀️ Solar construction tools

Field and office tools for utility-scale solar / BESS sites, built around the site's own GIS (GeoJSON) layouts.

| Project | What it does | Stack |
|---|---|---|
| [**CEW — Construction Engineering Workflow**](https://github.com/aticem/cew-showcase) | The umbrella platform: construction progress tracking, QA/QC and an AI assistant that answers questions over project documents (RAG with OCR, evaluation harness for answer quality). | Next.js, TypeScript, Supabase, Python AI service, Vertex AI / Gemini, Docker |
| [**Solar Docs Control**](https://github.com/aticem/solar-docs-control-showcase) | Queryable document-control system for solar projects: ingests handover packs, checklists, test reports and contracts, then answers questions with **file + page (and clause) citations**, strictly per site. Exposed to Claude via an MCP server. | Python, SQLite, MCP |
| [**XREF Bind**](https://github.com/aticem/xref-bind-showcase) | Takes a zipped DWG drawing set, permanently binds every (nested) xref into the main drawing and explodes it — one clean, editable DWG with an unchanged look. | Python (ezdxf), ODA File Converter, Node |
| [**Progress-tracking MVPs**](https://github.com/aticem/solar-progress-tracking-showcase) | A family of map-based daily progress apps, one per work package: DC / LV / MV cable pulling, MV fibre trenching, trenching, mounting tables, PV modules, MC4 connectors, LV boxes & inverters, PV string testing, cable megger testing and a punch list. Click or lasso items on the site layout to mark them done; daily logs, progress stats, history and chart / Excel export. | React, Vite, Leaflet, Turf.js, Chart.js, ExcelJS |
| [**GeoJSON renderer**](https://github.com/aticem/solar-progress-tracking-showcase) | High-performance canvas renderer for large site layouts: 4000+ objects with CAD-style text that scales with zoom. | React, Leaflet (canvas) |

## 🧰 Personal apps

| Project | What it does | Stack |
|---|---|---|
| [**Lincoln House Hunting**](https://github.com/aticem/home-searching-showcase) | Aggregates for-sale listings from Rightmove, Zoopla and OnTheMarket, de-duplicates across portals, enriches with EPC and Land Registry data, and lets you ask natural-language questions over listings with **verified quotes**. | Next.js, TypeScript, SQLite, Apify, Gemini / Claude |
| [**Budget App**](https://github.com/aticem/budget-app-showcase) | Type spending in plain language ("coffee 3.20, groceries 45") — an LLM turns it into structured transactions. | Next.js 16, React 19, Tailwind v4, Gemini |
| [**Daily Speaking**](https://github.com/aticem/daily-speaking-showcase) | Flashcard app for daily language practice: add cards, study sessions, favourites. | Next.js, Neon Postgres, Vercel |

## 📊 Data science & machine learning

| Project | Summary |
|---|---|
| [**Salary prediction (end-to-end)**](https://github.com/aticem/salary-prediction-showcase) | Predicts software-engineer salaries by country from the Stack Overflow survey; scikit-learn model tuned with cross-validation and grid search, served as a **Streamlit** app. |
| [**Customer segmentation (end-to-end)**](https://github.com/aticem/customer-segmentation-showcase) | Segments ~9,000 credit-card holders on 18 behavioural variables, comparing five clustering algorithms, to target offers like savings plans and loans; deployed as an app. |
| [**Email spam classifier**](https://github.com/aticem/email-spam-classifier-showcase) | Deploys a pre-trained spam classifier as a Python web app hosted on Render. |
| [**Insurance claim cost forecasting**](https://github.com/aticem/insurance-claim-forecasting-showcase) | Predicts claim costs from first-notification data with LightGBM and Random Forest to support earlier pricing decisions. |
| [**Recommendation systems**](https://github.com/aticem/recommendation-systems-showcase) | User-based and item-based collaborative filtering, scenario analysis (recent voters only, single-genre) and **SVD matrix factorisation** on MovieLens. |
| [**Time series forecasting**](https://github.com/aticem/time-series-forecasting-showcase) | CO₂ emissions with Holt-Winters (single / double / triple exponential smoothing), ARIMA / SARIMA, and a demand-forecasting script. |
| **Feature engineering & NLP** | Data pre-processing / feature-engineering pipeline, and text mining & NLP study. |
| [**SQL & analytics portfolio**](https://github.com/aticem/sql-analytics-portfolio-showcase) | COVID-19 data exploration and cleaning in SQL, Nashville housing data cleaning, Tableau dashboards, a movie-industry analysis and a web scraper. |
| **PySpark notes** | Handy PySpark snippets and patterns. |

---

**Tools I use:** Python · pandas · scikit-learn · LightGBM · TypeScript · React · Next.js · SQL · SQLite / Postgres · Leaflet / GeoJSON · LLM APIs (Gemini, Claude) · MCP
