# Impact of Car Features on Price & Profitability

Analyzing what drives consumer demand and pricing in the automobile market — engine specs, brand, body style, and fuel efficiency — to support product development and pricing decisions for a car manufacturer.

![Excel](https://img.shields.io/badge/MS%20Excel-Regression%20%26%20Analysis-217346?logo=microsoftexcel&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-Dashboard-E97627?logo=tableau&logoColor=white)
![PowerPoint](https://img.shields.io/badge/PowerPoint-Reporting-B7472A?logo=microsoftpowerpoint&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## Table of Contents
- [Business Scenario](#business-scenario)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Analysis](#data-analysis)
- [Dashboard](#dashboard)
- [Key Findings](#key-findings)
- [Conclusion](#conclusion)

---

## Business Scenario

Working as a data analyst for a car manufacturer, the brief was to optimize product development decisions — maximizing profit while still meeting consumer demand. That means understanding which car features (engine power, cylinder count, fuel efficiency, body style, brand) actually drive price and popularity, using regression analysis, pivot tables, sensitivity analysis, and market segmentation to turn raw specs into pricing and product strategy the manufacturer can act on.

## Data Source

**Car_data.csv** — sourced from Kaggle, originally collected by Cooper Union (a private college in New York City). Cleaned and prepared before analysis.

## Tools

| Tool | Purpose | Link |
|---|---|---|
| MS Excel | Regression analysis, pivot tables, sensitivity analysis | [Open](https://docs.google.com/spreadsheets/d/1gimXIc1Kmgh5v7_gn3KW__4j9aMnRP9n/edit?usp=sharing&ouid=105843925605549140071&rtpof=true&sd=true) |
| Tableau | Task insight visualizations | [Open](https://public.tableau.com/views/P_7Insights/T_1?:language=en-GB&:display_count=n&:origin=viz_share_link) |
| Tableau | Interactive dashboard | [Open](https://public.tableau.com/views/P_7Dashboard/Dashboard1?:language=en-GB&:display_count=n&:origin=viz_share_link) |
| PowerPoint | Data report | [Open](https://docs.google.com/presentation/d/1f_uJNdlQcYlMm6nZmTjcdof2bfvSAI3p/edit?usp=sharing&ouid=105843925605549140071&rtpof=true&sd=true) |

---

## Data Analysis

### 1. Popularity vs. Market Category

![T_1-1](https://github.com/esmdsuhail/Impact-of-Car-Features-on-Price-and-Profitability/assets/142283402/f790d77c-3320-4a91-a8ac-9876d11d8649)

![T_1-2](https://github.com/esmdsuhail/Impact-of-Car-Features-on-Price-and-Profitability/assets/142283402/156bd0b6-6138-4d0c-9404-5a97dea49bbe)

**Insight:** car model and popularity move together — a strong model can drive category popularity and vice versa — but market category is ultimately what sets the ceiling for both.

### 2. Engine Power vs. Price

![image](https://github.com/esmdsuhail/Impact-of-Car-Features-on-Price-and-Profitability/assets/142283402/510e617d-0905-4e6d-ac9f-66c64e62056f)

**Insight:** engine horsepower and price move proportionally — as HP rises, so does price. Most buyers, though, concentrate in a specific band: **200–500 HP** and **$50K–$500K**, marking the core of the market rather than the extremes.

### 3. Strongest Price Drivers

![T_3](https://github.com/esmdsuhail/Impact-of-Car-Features-on-Price-and-Profitability/assets/142283402/6ba99216-d67b-4145-870f-a6c32c20dad4)

**Insight:** regression analysis identifies **engine cylinder count and engine HP** as the two strongest predictors of price, each showing a clear positive relationship confirmed by the fitted regression lines.

### 4. Average Price by Manufacturer

![T_4](https://github.com/esmdsuhail/Impact-of-Car-Features-on-Price-and-Profitability/assets/142283402/7cfba1fc-aa3a-420a-9043-40885be5f0cd)

**Insight:** manufacturers cluster into distinct price segments — luxury vs. cost-effective/mid-market — giving a clear basis for competitive benchmarking within the right tier rather than across the whole market.

### 5. Fuel Efficiency vs. Cylinder Count

![T_5](https://github.com/esmdsuhail/Impact-of-Car-Features-on-Price-and-Profitability/assets/142283402/5a2c02ad-5c04-4a44-8424-dbf76bca3ec9)

**Insight:** fuel efficiency declines as cylinder count increases — a direct performance-vs-efficiency trade-off manufacturers have to weigh in product design.

---

## Dashboard Insights

### 1. Price Distribution by Brand & Body Style

![D_1](https://github.com/esmdsuhail/Impact-of-Car-Features-on-Price-and-Profitability/assets/142283402/23b0c509-bfae-4b94-bca4-dfc088b23e47)

**Insight:** sedans, 4DR SUVs, and coupes command the highest prices across brands, making them the priority body styles for premium positioning.

### 2. Highest & Lowest Average MSRP by Body Style

![D_2](https://github.com/esmdsuhail/Impact-of-Car-Features-on-Price-and-Profitability/assets/142283402/ff7a5b48-d6b7-4fee-bbae-473b0b8a26cf)

**Insight:** Bugatti coupes sit at the top of average MSRP across all body styles, while Plymouth sits at the bottom — a wide brand-driven price spread even within the same body style.

### 3. Transmission Type vs. MSRP

![D_3](https://github.com/esmdsuhail/Impact-of-Car-Features-on-Price-and-Profitability/assets/142283402/5f5c3a09-695c-4177-92a0-378eaed6e310)

**Insight:** automated manual transmissions show the widest price range of any transmission type, suggesting they're used across both budget and premium vehicles rather than being tier-specific.

### 4. Fuel Efficiency by Body Style & Model Year

![D_4](https://github.com/esmdsuhail/Impact-of-Car-Features-on-Price-and-Profitability/assets/142283402/6f096431-026e-4804-8108-bea2b8c2bc5e)

**Insight:** MPG has trended upward over time across virtually all brands and body styles — a consistent industry-wide efficiency improvement rather than an isolated trend.

### 5. Horsepower, MPG & Price by Brand

![D_5](https://github.com/esmdsuhail/Impact-of-Car-Features-on-Price-and-Profitability/assets/142283402/a30cca3c-fad5-4223-bacc-ca8bdc22b783)

**Insight:** Bugatti leads on horsepower while Tesla leads on fuel efficiency (MPG) — a clean illustration of how brands differentiate along entirely different performance axes rather than competing on the same metric.

---

## Dashboard

![Dashboard](https://github.com/esmdsuhail/Impact-of-Car-Features-on-Price-and-Profitability/assets/142283402/a955e546-0e6f-42be-8f2a-67c90b385fc8)

---

## Key Findings

- **Engine HP and cylinder count are the strongest price drivers**, confirmed both by direct trend charts and regression analysis — the two metrics manufacturers should weight most heavily in pricing strategy
- **The core market sits in a defined band** (200–500 HP, $50K–$500K) — most buyers aren't at the extremes, which matters more for volume-focused product decisions than headline halo models
- **Performance and efficiency trade off directly**: more cylinders means more power but lower MPG, a design tension every manufacturer has to navigate
- **Brands differentiate on different axes entirely** — Bugatti wins on power, Tesla wins on efficiency — showing there's more than one viable positioning strategy in this market, not just "faster and more expensive"

## Conclusion

This project shows how regression analysis, segmentation, and interactive dashboards combine to turn a raw features-and-pricing dataset into decisions a manufacturer can actually use — which specs to prioritize in new models, which market segment and body style to target, and where brand positioning creates room to compete without going head-to-head on the same metric. The dashboard makes these insights explorable on demand, rather than static, for ongoing product and pricing strategy work.

---

### Skills Demonstrated
Regression analysis, pivot tables, sensitivity analysis, market segmentation, interactive dashboard design (Tableau), and translating feature-level analysis into pricing/product strategy recommendations.
