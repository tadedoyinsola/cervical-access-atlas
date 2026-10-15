# U.S. Cervical Cancer Prevention Access Atlas

**Where do women face the steepest barriers to cervical cancer prevention, county by county, and where should outreach go first?**

**Open the atlas:** https://tadedoyinsola.github.io/cervical-access-atlas/

An interactive geospatial atlas covering all 3,109 counties of the contiguous United States. It combines public data on health insurance, OB/GYN supply, geographic isolation and cervical cancer screening into a single picture of who is being left behind. It is built for:

- state and county health departments,
- funders and policymakers,
- community and advocacy groups,
- researchers who want to check or reuse the work.

Developed by Tolulope A. Oladeji and Diego F. Cuadros, Digital Epidemiology Laboratory, University of Cincinnati.

---

## Contents

1. [The problem, in plain words](#1-the-problem-in-plain-words)
2. [What the atlas shows](#2-what-the-atlas-shows)
3. [Key findings](#3-key-findings)
4. [How to use it: guides by role](#4-how-to-use-it-guides-by-role)
5. [How to read the scores](#5-how-to-read-the-scores)
6. [Methods (for reviewers)](#6-methods-for-reviewers)
7. [Validation: does the score mean anything?](#7-validation-does-the-score-mean-anything)
8. [Limitations and appropriate use](#8-limitations-and-appropriate-use)
9. [Data sources](#9-data-sources)
10. [Data dictionary (downloadable files)](#10-data-dictionary-downloadable-files)
11. [Running, updating and reusing the site](#11-running-updating-and-reusing-the-site)
12. [Citation, credits and contact](#12-citation-credits-and-contact)
13. [Glossary](#13-glossary)

---

## 1. The problem, in plain words

Cervical cancer is one of the most preventable cancers. Almost all cases are caused by long-lasting infection with high-risk human papillomavirus (HPV). Two proven tools stop it:

- **The HPV vaccine** prevents the infections that cause most cervical cancers.
- **Regular screening** (Pap and HPV tests) finds abnormal cells years before they turn into cancer, while they can still be treated.

Even so, about **13,100 women** in the United States are diagnosed with cervical cancer each year and about **4,200 die** from it (NCI State Cancer Profiles). Most of these cases happen in women who were never screened or were not screened recently.

**The tools exist. The problem is whether they can reach a woman where she lives.** If the nearest gynecologist is an hour's drive away, if she has no health insurance, or if her county has few health services, prevention never arrives.

The United States has a national target (Healthy People 2030) that **84.3%** of women aged 21–65 be up to date on cervical cancer screening. In this atlas, **92% of counties (2,873 of 3,109) fall short of that target.**

This atlas measures the *structural* barriers behind that shortfall, so decision-makers can see where they pile up and act there first.

---

## 2. What the atlas shows

The site is a single page with seven sections.

| Section | What it does | Who it's most useful for |
|---|---|---|
| **Headline** | Five key numbers and a one-sentence finding | Everyone |
| **01 Why it matters** | Background on cervical cancer and prevention | Community groups, the public |
| **02 Explore the map** | A county map with five layers, search, state zoom and hover details | Everyone |
| **03 Your county** | A plain-language profile of one county compared with its state and the U.S., plus a share link and a printable one-page brief | County health departments, advocates |
| **04 Priority counties** | A ranked table you can sort and filter, with CSV download | State health departments |
| **05 Targeting tool** | Compares three ways of choosing counties for outreach at different budgets | Funders, policymakers, program planners |
| **06–07 Use the atlas, Methods & data** | Role guides, methods, validation, limitations, data downloads, citation and links to free screening resources | Reviewers, researchers |

### The five map layers

| Layer | What it means | How it's coloured |
|---|---|---|
| **Barrier to prevention care** | How hard it is, structurally, for women in the county to reach prevention (the access index) | Five levels, Low → Severe, each a fifth of all counties |
| **Screening shortfall** | How many percentage points the county's screening rate falls below the 84.3% goal | Meets goal → Far below (6+ points) |
| **Combined priority** | An equal blend of the barrier and the screening shortfall | Lower → Highest |
| **Double-burden counties** | Counties in the worst fifth of the country for *both* barrier and screening shortfall | Highlighted in dark red |
| **No local OB/GYN** | Counties with no OB/GYN physician in patient care | Highlighted in red |

Colours use a yellow-to-red scale throughout: darker red always means *worse*.

---

## 3. Key findings

All figures cover the contiguous U.S. (3,109 counties). Alaska and Hawaii are not included.

- **92% of counties are below the national screening goal.** The median county has 81% of women up to date, about 3 points short of 84.3%.
- **1,424 counties (46%) have no practicing OB/GYN.** About 10 million women live in them.
- **304 counties carry a "double burden"**: they are in the worst fifth of the country for both low screening and high access barriers. About **4.6 million women** live in them.
- **Double-burden counties are concentrated in the South, above all in Texas.** 188 of the 304 are in Texas, followed by Oklahoma (29), Georgia (15) and Florida (15). The highest-priority counties nationally are along the Texas–Mexico border and in West Texas, for example Presidio, Zapata, Hudspeth and Starr counties.
- **A typical double-burden county looks like this**, compared with other counties:

  | Measure | Double-burden counties | Other counties |
  |---|---|---|
  | Women screened | 77% | 81% |
  | Uninsured (under 65) | 18% | 9% |
  | OB/GYNs per 10,000 women | 0 (three in four have none) | 0.8 |

- **These barriers line up with real cancer outcomes.** Double-burden counties have about **70% higher** cervical cancer incidence (14.4 vs 8.3 per 100,000) and higher mortality (4.0 vs 2.4 per 100,000). See [Validation](#7-validation-does-the-score-mean-anything).
- **The access index is not the same as general social vulnerability.** It agrees only weakly with the CDC Social Vulnerability Index (Spearman ρ ≈ 0.30). It picks out places SVI misses, especially the rural Great Plains and Mountain West, where isolation and missing specialists matter more than poverty.
- **How you choose counties changes who you reach.** With a budget covering 20% of counties:
  - targeting only the most deprived counties reaches 17% of under-screened women;
  - targeting where the most women are reaches 83%, but mostly in well-served places;
  - a **balanced** strategy reaches **62%** of under-screened women and keeps the effort in access-poor counties.

---

## 4. How to use it: guides by role

### State health departments
1. Go to **04 Priority counties** and choose your state in the filter.
2. Tick **Double-burden only** and/or **No local OB/GYN** to narrow the list.
3. Click any column heading to sort, for example by "Uninsured" or "Below goal".
4. Click **Download this list (CSV)** for your annual plan, a CDC cooperative agreement work plan, or mobile-unit routing.

*Example question it answers:* "Which 20 counties in my state should our breast and cervical cancer program prioritize next year?"

### County and local health departments
1. In **02 Explore the map**, type your county name in the search box.
2. Scroll to **03 Your county**. You'll see:
   - your barrier level and how you compare with the state and the U.S.;
   - a plain-language "What this means" summary.
3. Use **Print county brief** for a one-page handout for your board or commissioners.
4. Use **Compare with another county** to benchmark against a neighbour or peer county.

*Example question it answers:* "Why is our screening rate low, and is it insurance, specialists or distance?"

### Funders and policymakers
1. Go to **05 Targeting tool**.
2. Choose a strategy: **Equity first**, **Balanced** (recommended) or **Reach the most women**.
3. Move the budget slider (5–50% of counties). The tool reports:
   - women below the screening goal reached;
   - share of the national total;
   - double-burden counties covered;
   - the typical barrier level of the counties chosen.
4. Click **Show these counties on the map** to see them, or download the list for a proposal.

*Example question it answers:* "If we can fund outreach in 300 counties, which choice reaches the most women without abandoning the hardest-to-serve places?"

### Community and advocacy groups
1. Find your county and click **Copy share link**. The link opens the atlas directly on your county's profile (it ends in `#c=` followed by the county's 5-digit FIPS code).
2. Use the plain-language findings in flyers, testimony or grant applications.
3. Point women to the free resources in the **Cervical cancer can be prevented** box: HPV vaccination, free or low-cost screening through CDC's National Breast and Cervical Cancer Early Detection Program, and HRSA health centers.

### Researchers and reviewers
- Read sections [6](#6-methods-for-reviewers)–[8](#8-limitations-and-appropriate-use) below.
- Download `counties.geojson` or the CSV from the site (**07 Methods & data → Download the data**).

---

## 5. How to read the scores

- **Scores are relative, not absolute.** A barrier score of 80 means the county has higher barriers than about 80% of U.S. counties. It does *not* mean an 80% chance of anything.
- **The five levels are fifths of the country.** "Severe" means the worst 20% of counties nationally.
- **Scores describe places, not people.** A "Severe" county still has many women who are well served, and a "Low" county still has women who face barriers.
- **The scores are not a measure of cancer risk for any individual** and are not medical advice.
- **Cancer rates are shown for context only.** Many small counties have no published rate because there are too few cases to report reliably. That is shown as "Not published", not zero.

---

## 6. Methods (for reviewers)

### 6.1 Unit and scope
- **Unit:** 3,109 counties and county-equivalents of the contiguous U.S., using Census TIGER/Line 2023 boundaries.
- **Excluded:** Alaska and Hawaii.

### 6.2 Structural access index (the "barrier to prevention care")
Three structural domains, chosen in advance:

| Domain | Indicator(s) | Direction | Source |
|---|---|---|---|
| Insurance barrier | % of people under 65 without health insurance | higher = worse | Census SAHIE, 2023 |
| Provider scarcity | OB/GYN physicians in patient care per 10,000 women | fewer = worse | HRSA Area Health Resources Files, 2024–2025 |
| Geographic isolation | (a) population density; (b) great-circle distance from the county centroid to the nearest population center of 250,000 or more | lower density / farther = worse | Census TIGER/Line 2023; CDC/ATSDR SVI 2022 population and area |

How the index is put together:

1. Each indicator is converted to a z-score and oriented so that a higher value means worse access.
2. Indicators are averaged within each domain.
3. The three domains are averaged with **equal, pre-specified weights**.
4. The result is converted to a **0–100 percentile rank** (higher = worse access).

**Design rules**, fixed before any outcome data were examined:

- Cancer incidence and mortality are **never** inputs, so validation is not circular.
- **Race is not an input.**
- Weights are **not tuned** to any outcome.
- The CDC Social Vulnerability Index is used only as a **benchmark** to compare against, never as an input.

### 6.3 Screening shortfall
- County cervical cancer screening prevalence (women aged 21–65) comes from **CDC PLACES**. These are model-based small-area estimates built from BRFSS 2020 survey data.
- **Shortfall** = max(0, 84.3 − screening %), in percentage points. The target is the Healthy People 2030 objective C‑09.

### 6.4 Combined priority and double burden
- **Combined priority** = (percentile rank of the screening shortfall + access index) / 2, on a 0–100 scale. U.S. priority rank 1 is the highest-priority county.
- **Double-burden** = a county in the worst 20% nationally on **both** the screening shortfall and the access index.

### 6.5 Targeting tool
- **Women below the screening goal** (the "addressable gap") in each county = women × 0.60 × max(0, 0.843 − screening proportion).
  - The 0.60 is an approximate share of women of screening age (21–65).
  - Comparisons between strategies do not depend on this constant.
- **Budget** = the share of the 3,109 counties targeted, taken from the top of each strategy's ranking.
- **Strategies:**
  - **Equity first**: ranks counties by combined priority.
  - **Reach the most women**: ranks counties by the addressable gap.
  - **Balanced**: ranks counties by 0.65 × (percentile of the addressable gap) + 0.35 × (access index). The 0.65 weight was chosen from the efficiency–equity frontier analysis. It keeps most of the reach of the volume-based approach while targeting counties with a median barrier in the "High" band.
- These are **planning estimates of reach**, not predictions of cancers prevented.

### 6.6 How the atlas numbers relate to the published paper
The atlas covers the **contiguous U.S.** The companion paper (Paper 1) reports **national** figures that also include Alaska (30 boroughs/census areas) and Hawaii (5 counties). All inputs, data years and methods are identical, and every county's scores are the same in both. Only the set of counties counted differs.

| Figure | Paper (50 states + DC) | Atlas (contiguous U.S.) | Difference |
|---|---:|---:|---|
| Counties | 3,144 | 3,109 | 35 counties in Alaska and Hawaii |
| Counties with no OB/GYN | 1,446 | 1,424 | 22 in Alaska and Hawaii |
| Double-burden counties | 322 | 304 | 18 in Alaska and Hawaii |
| Women in double-burden counties | ≈ 4.8 million | ≈ 4.6 million | ≈ 187,000 women in Alaska and Hawaii |

Double-burden status and percentiles were computed nationally (3,144 counties) and then mapped for the contiguous states. They were **not** recomputed on the contiguous subset, so a county's score is the same in the paper and the atlas.

### 6.7 Software
- Analysis pipeline: Python (pandas, geopandas), with numbered, version-controlled scripts.
- Website: static HTML, JavaScript and Leaflet 1.9.4. No server, no tracking and no API keys; all calculations run in the reader's browser.

---

## 7. Validation: does the score mean anything?

The validation plan was **pre-registered** (analysis plan locked 13 October 2026) before cancer outcome data were opened. The outcomes are NCI State Cancer Profiles age-adjusted rates:

- incidence, 2019–2023;
- late-stage incidence;
- mortality, 2020–2024.

**Results:**

| Test | Result |
|---|---|
| Correlation of the access index with cervical cancer **incidence** (757 counties with published rates) | Spearman ρ = **0.58** (SVI: 0.48) |
| Correlation with cervical cancer **mortality** (281 counties) | ρ = **0.49** (SVI: 0.46) |
| Predictive value **added beyond SVI + OB/GYN density** for mortality, in states held out of the model | ΔR² = **+0.085** |
| Predictive value added for incidence, held-out states | ΔR² = +0.024 |
| Double-burden vs other counties, incidence | **14.4 vs 8.3** per 100,000 (p < 0.001) |
| Double-burden vs other counties, mortality | **4.0 vs 2.4** per 100,000 (p < 0.001) |

**Plain-language reading:** counties the atlas flags as having high barriers do have more cervical cancer and more deaths. The index explains part of that pattern that standard vulnerability measures miss.

These are **ecological associations**: they describe counties, not individuals, and do not prove that the barriers cause cancer. The test for late-stage incidence in held-out states was not positive, and we report that openly.

Full validation reports are in the project repository (`06_Documentation/outcome_validation.md`).

---

## 8. Limitations and appropriate use

**Appropriate uses:**

- prioritising counties for outreach;
- comparing places;
- supporting grant applications and plans;
- starting conversations with communities.

**Not appropriate for:**

- judging an individual woman's risk;
- evaluating the performance of a specific clinic or health department;
- making causal claims.

**Known limitations:**

- **Screening rates are model-based estimates** from CDC PLACES (2020 BRFSS survey data). This is the only source that covers every county, and it is the last release of the measure: CDC dropped it after the 2022 BRFSS question change, so no newer county series exists. Small-county estimates are statistically smoothed and may differ from local registry or claims data, and 2020 was a pandemic year when screening dipped. These limits affect only the screening shortfall, priority and double-burden layers. The access index contains no screening data, and its validation against NCI cancer registry outcomes is independent of PLACES.
- **HPV vaccination is not in the score.** No national county-level HPV vaccination data exist: CDC's National Immunization Survey–Teen reports states and selected local areas, and state immunization registries differ in coverage and access. This is also a matter of design. The index measures structural barriers to care (insurance, specialists, distance), not uptake behaviours such as vaccination or screening. And because the vaccine was introduced in 2006 for adolescents and young adults, most women developing cervical cancer today were past vaccine age, so screening is the main prevention lever for current burden. Vaccination will matter more as vaccinated cohorts reach screening age.
- **Travel time is approximated** by density and distance to a large population center, not by road travel time to the nearest OB/GYN. Road-network travel time is the planned next enhancement.
- **OB/GYN counts measure physicians, not services.** They do not capture family physicians, nurse practitioners, health centers or mobile units that also provide screening.
- **Cancer rates are suppressed** for many small counties, and Kansas, Minnesota and Virginia do not publish county rates.
- **Connecticut's planning regions** (which replaced its counties in Census 2023 geography) have no county screening estimates. They have an access score but no screening, priority or double-burden status.
- **Data years differ by source** (2020–2025). The atlas is a recent snapshot, not a real-time monitor.
- **Alaska and Hawaii are not mapped.**

---

## 9. Data sources

All data are free and public. No data use agreements were required.

| Data | Provider | Years | Used for |
|---|---|---|---|
| Small Area Health Insurance Estimates (SAHIE) | U.S. Census Bureau | 2023 | Insurance barrier |
| Area Health Resources Files (AHRF) | Health Resources & Services Administration (HRSA) | 2024–2025 | OB/GYN supply |
| TIGER/Line county boundaries | U.S. Census Bureau | 2023 | Geography, isolation, map |
| PLACES: Local Data for Better Health | Centers for Disease Control and Prevention (CDC) | 2020 survey data | Cervical screening |
| Social Vulnerability Index (SVI) | CDC / ATSDR | 2022 | Population and area; benchmark only |
| State Cancer Profiles | National Cancer Institute (NCI) | Incidence 2019–2023; mortality 2020–2024 | Validation and context only |
| Healthy People 2030 objective C‑09 | U.S. Dept. of Health & Human Services | — | 84.3% screening target |

---

## 10. Data dictionary (downloadable files)

**`counties.geojson`** has one feature per county (polygon boundary, simplified for web display) with the following properties. **The CSV download** on the site contains the same values, without boundaries.

| Field | Meaning | Units |
|---|---|---|
| `fips` | 5-digit county FIPS code | text |
| `name`, `st`, `sn` | County name, state abbreviation, state name | text |
| `access` | Structural access index (barrier to prevention care) | 0–100 percentile, higher = worse |
| `gap` | Screening shortfall below 84.3% | percentage points |
| `priority` | Combined priority score | 0–100, higher = higher priority |
| `prank` | U.S. priority rank | 1 = highest priority |
| `db` | Double-burden county | true / false |
| `screen` | Women aged 21–65 up to date on cervical screening | % |
| `obgyn` | OB/GYN physicians in patient care per 10,000 women | rate |
| `obn` | Number of OB/GYN physicians in patient care | count |
| `unins` | People under 65 without health insurance | % |
| `svi` | CDC Social Vulnerability Index (benchmark only) | 0–100 percentile |
| `inc`, `mort` | Cervical cancer incidence and mortality, age-adjusted (context only; blank = suppressed) | per 100,000 women |
| `pop`, `women` | Total population, female population | people |
| `addr` | Estimated women below the screening goal | people |

The file also contains a `meta` block with national and state summaries. **`states.geojson`** contains the state outlines drawn on the map.

---

## 11. Running, updating and reusing the site

**Files in this repository:**

| File | Purpose |
|---|---|
| `index.html` | The entire website (layout, map, tools and text) |
| `counties.geojson` | County boundaries and all scores |
| `states.geojson` | State outlines |
| `README.md` | This document |

**Preview on your own computer.** Browsers block data loading when you double-click an HTML file, so start a small local server in this folder:

```bat
python -m http.server 8000
```
Then open http://localhost:8000.

**Publish an update.** Upload the changed files to the repository root (Add file → Upload files → Commit). GitHub Pages republishes within a minute or two. Press Ctrl+F5 to see the new version.

**Customise.** Colours, class breaks, layer names and strategies are set in the `RAMP`, `LAYERS` and `STRATS` objects near the top of the script in `index.html`. The data can be re-generated from the analysis pipeline.

**Privacy.** The site uses no cookies, analytics or tracking. Fonts load from Google Fonts, the map library from unpkg, and photos from Unsplash.

---

## 12. Citation, credits and contact

**Please cite as:**

> Oladeji, T. A., & Cuadros, D. F. (2026). *U.S. Cervical Cancer Prevention Access Atlas* [interactive tool]. Digital Epidemiology Laboratory, University of Cincinnati. https://tadedoyinsola.github.io/cervical-access-atlas/

**Authors:** Tolulope A. Oladeji (PhD candidate, Geography & GIS) and Diego F. Cuadros (Digital Epidemiology Laboratory), University of Cincinnati.

**Related work:** [Nigeria Maternal Vulnerability Atlas](https://tadedoyinsola.github.io/nigeria-mvi-atlas/).

**Photo credits** (via Unsplash, Unsplash License):
- NASA (Earth at night);
- Bioscience Image Library by Fayette Reynolds (epithelium micrograph);
- CDC (vaccination);
- Jake Blucker (rural road).

**Questions, corrections or partnership requests:** please open an issue in this repository: https://github.com/tadedoyinsola/cervical-access-atlas/issues

**Disclaimer:** This is an independent academic project. It is not an official product of the CDC, HRSA, NCI or any health department, and it is not medical advice. Women looking for care can start at:

- [CDC: HPV vaccination](https://www.cdc.gov/hpv/vaccines/index.html)
- [CDC: Find a free or low-cost screening program](https://www.cdc.gov/breast-cervical-cancer-screening/about/screenings.html)
- [HRSA: Find a health center](https://findahealthcenter.hrsa.gov/)

---

## 13. Glossary

| Term | Meaning |
|---|---|
| **Access index / barrier to prevention care** | A 0–100 score of structural barriers (insurance, OB/GYN supply, isolation). Higher = harder to reach care. |
| **Screening shortfall (gap)** | How far a county's screening rate is below the national goal of 84.3%. |
| **Double-burden county** | In the worst 20% of counties for both the barrier and the screening shortfall. |
| **Percentile** | The share of counties with a lower value. A score of 90 is higher than 90% of counties. |
| **FIPS code** | A standard 5-digit number that identifies each U.S. county. |
| **HPV** | Human papillomavirus, the virus that causes almost all cervical cancers. |
| **Pap / HPV test** | Screening tests that find abnormal cervical cells or HPV infection before cancer develops. |
| **OB/GYN** | Obstetrician-gynecologist, the specialist who most often provides cervical screening follow-up and treatment. |
| **SVI** | CDC/ATSDR Social Vulnerability Index, a widely used measure of community vulnerability. |
| **Age-adjusted rate** | A cancer rate adjusted so that places with older or younger populations can be compared fairly. |
| **Ecological association** | A pattern observed across places, which may not hold for every individual. |
| **Pre-registration** | Writing down the analysis plan before seeing the outcome data, so results can't be tuned after the fact. |
