# Enzo Mischler

**Final-year engineering student at IMT Mines Alès** — Computer Science & AI, International Business Engineering track.
I work where organisational analysis meets software: understanding how work is actually done, quantifying what it costs, and building the tool that removes the friction.

Currently looking for a **6-month final-year AI consulting internship in Switzerland**, starting March 2027.

---

### What I've built

**Management platform for a non-profit health and social care organisation** *(10 facilities · private repository — client production system)*

A four-month engagement, from field audit to production rollout: mapping how the work was actually done, agreeing priorities with executive management, building the tool, and handing it over to the teams.

- Finance, HR and operations consolidated into a single platform, shipped to production over 8 sprints
- 3 source systems automated, including a headless-browser extraction pipeline — 400,000 accounting entries consolidated
- Monthly budget reporting produced from a single 10-minute accounting import
- Site directors given continuous access to indicators they previously had to rebuild
- ~880 automated tests covering the platform
- *Estimated* ~240 hours of administrative work recovered per year across the five main sites
- **The client renewed the engagement under a 12-month maintenance contract**

The code is not public: it is a live system holding client data. Client name and references available on request.

---

### Machine learning

**Predictive modelling of Parkinson's "OFF" motor episodes** *(academic R&D project, ongoing — private)*

Detecting OFF motor episodes from accelerometric time series, in a single-patient ambulatory pilot.

- 5 tri-axial accelerometers at 50 Hz, 9 days of recording, 94.9 h of usable signal → 68,000 windows
- ~100 time- and frequency-domain descriptors, reduced to 10–15 by Gini importance
- 7 models benchmarked under GroupKFold (5 folds × 10 repeats)
- Best F1 on the OFF class **0.47** (XGBoost) against **0.31** for the null classifier, AUC-ROC 0.69 — Wilcoxon-significant

**Electricity price forecasting** *(engineering project, team of 3)* — time-series modelling applied to strategic energy procurement for French municipalities. Python, TensorFlow/Keras.

---

### Public projects

| Project | What it is | Stack |
|---|---|---|
| [**GymTracker**](https://github.com/Enzo123-Byte/GymTracker) | Training and nutrition tracking PWA — 22 JavaScript modules, auth, workout builder, macro tracking, analytics and social features | JavaScript (ES modules) · Supabase · PWA |
| [**scraping-bonheur-education**](https://github.com/Enzo123-Byte/scraping-bonheur-education) | Building a country-level dataset linking World Happiness Report scores to education indices — scraping, cleaning, consolidation | Python · BeautifulSoup · pandas |
| [**CalculatriceMVC**](https://github.com/Enzo123-Byte/CalculatriceMVC) | A calculator used to demonstrate a strict MVC architecture, with model, view and controller separated by interfaces | Java |

---

### Toolbox

**AI & ML** Python · pandas · NumPy · scikit-learn · TensorFlow/Keras · XGBoost · time-series modelling
**Data & backend** SQL/PostgreSQL · Django · Supabase
**Ops** Docker · Linux · Git
**Also** JavaScript · Java · R · C/C++

**Languages spoken** French (native) · English (TOEIC 930/990 — C1) · German (B1)

---

📫 [enzo.mischler@gmail.com](mailto:enzo.mischler@gmail.com) · [LinkedIn](https://linkedin.com/in/enzo-mischler)
