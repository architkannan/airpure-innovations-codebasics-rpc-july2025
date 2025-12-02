# Pollution, People & Product: Designing the Ideal Air Purifier for India  
***A Power BI project to guide product development, prioritize high-risk cities, and map demand drivers using air quality, health, and population data.***

This project was created as part of the [**Codebasics Resume Project Challenge**](https://codebasics.io/challenges/codebasics-resume-project-challenge/20) (July 2025).

[**Live Dashboard**](https://app.powerbi.com/view?r=eyJrIjoiZGQxNzRlNDItMDc5Yi00NjY2LTlmZDItNGEwYTk4YmM2ZGE0IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

[**Project Presentation Video**](https://www.linkedin.com/posts/architkannan_codebasics-resumeprojectchallenge-dataanalytics-activity-7360347125068582913-0fx6?utm_source=share&utm_medium=member_desktop&rcm=ACoAAAu24ssBa8xnl0qDKhvhVsegfe25y8b0D2o)

---

## ❗ The Problem

India faces one of the world’s worst air pollution crises.  
With **14 of the top 20 most polluted cities globally**, the challenge is both widespread and structurally complex.

**AirPure Innovations**, an early-stage startup, needed clarity on:

- Which pollutants to prioritize  
- What product features matter most  
- Which cities present the strongest market opportunity  
- How pollution patterns align with consumer health and demand  

Decision-making was slowed by **fragmentated AQI, health, population, and vehicle datasets** — each giving only part of the picture.

---

## 📝 Overview

This project analyzes three core dimensions to guide product-market fit and product development:

1. **Severity Mapping** – Cities with persistent or worsening AQI levels  
2. **Health Impact Correlation** – Disease burden and pollution-linked health risk  
3. **Demand Triggers** – How AQI spikes influence consumer interest and purifier search behaviour  

**Goal:**  
Build a **self-explanatory dashboard** that enables management and the product strategy team to quickly understand city risk, feature priorities, and market opportunities.

**Deliverables:**

- **Market Prioritization Dashboard** including  
  - City risk scores (AQI × population density × income)  
  - Health cost impact projections  

- **Product Requirements Document** covering  
  - Must-have features  
  - Competitor feature gap matrix  
  - Tiered pricing models for target customer segments  

---

## 🔢 Data Sources

Primary datasets came from **Dataful**, supported by external trend research.

1. **Air Quality Index (AQI)** – Daily, state-wise AQI for Indian cities (2022–2025)  
2. **Health Data** – Disease cases & deaths by state/district (2022–2025)  
3. **Vehicle Registration** – Vehicle counts by class/fuel type (2022–2025)  
4. **Population Projections** – Urban population forecasts (2011–2036)  
5. **External Trends & Research** –  
   Google Trends (air purifier / child asthma queries), competitor analysis, and secondary research from published studies  

---

## 🚀 Solution: Dashboard & Analytics

A Power BI dashboard was developed to bring all datasets together into a single decision-ready view.

### Tools & Techniques
- Power BI  
- Excel  
- DAX  

### Dashboard

🚀 [**Live Dashboard**](https://app.powerbi.com/view?r=eyJrIjoiZGQxNzRlNDItMDc5Yi00NjY2LTlmZDItNGEwYTk4YmM2ZGE0IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

![AirPure Innovations Dashboard](https://github.com/architkannan/airpure-innovations-codebasics-rpc-july2025/blob/main/AirPureInnovations.gif)

---

## 📊 Dashboard Structure & Insights

| Dashboard Component | Key Insight |
|---------------------|-------------|
| **Top 5 & Bottom 5 Cities (Bar Chart)** | Byrnihat average AQI was ~9× higher than Tirunelveli (Dec 2024–May 2025). |
| **Monthly AQI Trends (Column Chart)** | Nov–Jan consistently above mean AQI across top 10 states (Apr 2022–Apr 2025). |
| **Bengaluru vs Delhi (Pie Chart)** | Bengaluru had 24× more ‘Satisfactory’ days than Delhi (Mar–May 2025). |
| **Weekday vs Weekend AQI** | No meaningful difference — pollution is constant daily. |
| **Pollutant Concentration Matrix** | PM2.5 and PM10 are the most severe pollutants nationally. |
| **Population vs AQI** | Northern cities show high AQI regardless of population size. |
| **Health Correlation Tables** | AQI strongly correlates with search interest for child asthma and air purifiers (r = 0.94). |
| **Competitor Perception Map** | Helps position product features against market players. |
| **City Risk & Health Cost Matrix** | Highlights high-risk metros and emerging pollution hotspots. |

---

## 🌟 Impact: Product & Market Insights

### **Priority Cities & Pollution Focus**
- Tier-1 metros emerge as the highest-risk, highest-priority markets  
- Key pollutants to target: **PM2.5, PM10, VOCs, coarse dust**

---

## 🛠 Product Solution Overview

[**Complete Product Requirements Document**](https://docs.google.com/document/d/15WxBphoL1G_wUxiuHMRIaPkupubzAvDrbpLoNITbiPs/edit?tab=t.0)

Core recommendations included:

- **Metro-smart, portable purifier** built for mid-priced Indian households  
- **Optimized multi-stage filtration** (HEPA H13 + pre-filter + activated carbon)  
- **Rechargeable battery backup** to handle power cuts  
- **Tool-free, quick-swap filters** for low maintenance  
- **Lightweight design with real-time AQI feedback**

---

## ⭐ Core Value Proposition

**“Cleaner air for every metro home. Portable, reliable, and designed for India’s toughest city pollution challenges.”**

---

## 🔧 Must-Have Features & Purpose

| Feature | Purpose |
|--------|---------|
| True HEPA H13 | Captures 99.97% of PM2.5, PM10, dust, allergens |
| Pre-filter | Handles coarse dust and construction debris |
| Activated Carbon Filter | Removes VOCs and indoor odors |
| Real-time PM2.5 & VOC Sensors | Data-driven control based on AQI patterns |
| Rechargeable Battery | Ensures operation during power cuts |
| Portability | Easy mobility across rooms |
| Auto Mode | Sensor-based adaptive fan speed |
| Quiet Operation (<45 dB) | Suitable for bedrooms |
| Tool-Free Filter Replacement | Reduces downtime |
| Intuitive UX | Simplifies monitoring for all users |

---

## 📘 R&D and Market Insights

- Feature gap analysis revealed opportunities within the mid-tier purifier segment  
- City risk scoring informed phased market entry  
- Dashboard consolidated quantitative justification for MVP design, pricing, and segmentation  

---

## 📌 Deliverables

- **Market Prioritization Dashboard**  
- **Product Requirements Document**  
- **Insights Repository** (health correlations, pollutant priorities, city analysis, competitor gaps)

---

## 🙏 Acknowledgements

- [**Codebasics**](https://codebasics.io/)  
- [**Dataful**](https://dataful.in/)

---

## ✔️ Conclusion

This project demonstrates the ability to:

1. Extract insights from complex, multi-source datasets  
2. Apply Excel and Power BI for decision-driven analytics  
3. Support product design, market prioritization, and R&D strategy  

---

### Contact  
🔗 **LinkedIn:** https://www.linkedin.com/in/architkannan/  
📧 **Email:** architkannan@zohomail.in  
