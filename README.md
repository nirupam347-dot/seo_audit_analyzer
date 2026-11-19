# 🔍 SEO Site Auditor

An automated On-Page SEO & Content Audit Analyzer built in Python and Jupyter Notebook. It crawls any live webpage, inspects technical metadata and HTML structure, calculates keyword density, and generates visual SEO health reports.

## ✨ Features
- **Live Webpage Fetcher:** Measures HTTP status codes and server response latency using `requests`.
- **On-Page Technical Audit:** Evaluates `<title>` length, `<meta name="description">`, `H1–H3` heading hierarchy, image `alt` attribute coverage, and internal vs. external link ratios with `BeautifulSoup` and `pandas`.
- **Keyword Density Analyzer:** Strips script/style tags, filters stop-words, and ranks the top keywords by frequency and percentage share.
- **Visual SEO Dashboard:** Generates keyword frequency bar charts and an overall On-Page SEO Health Score (`0–100`) using `matplotlib` and `seaborn`.

## 🛠️ Tech Stack
- **Language:** Python 3
- **Environment:** Jupyter Notebook (Anaconda)
- **Libraries:** `requests`, `beautifulsoup4`, `pandas`, `matplotlib`, `seaborn`

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone [https://github.com/nirupam347-dot/seo_audit_analyzer.git](https://github.com/nirupam347-dot/seo_audit_analyzer.git)
   ```
2. Install dependencies:
   ```bash
   pip install requests beautifulsoup4 pandas matplotlib seaborn jupyter
   ```
3. Launch `seo_audit_analyzer.ipynb` in Jupyter Notebook, set `TARGET_URL` in Cell 1, and run all cells.
   
