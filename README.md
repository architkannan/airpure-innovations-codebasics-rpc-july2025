# Pollution, People & Product: Journey to Design the Perfect Air Purifier for India

***A Power BI project to guide product development, prioritize high-risk cities, and optimize air purifier features based on air quality, health, and consumer demand insights.***

This project was my submission for the [**Codebasics Resume Project Challenge**](https://codebasics.io/challenges/codebasics-resume-project-challenge/20) for July 2025.


[**Live Dashboard**](https://app.powerbi.com/view?r=eyJrIjoiZGQxNzRlNDItMDc5Yi00NjY2LTlmZDItNGEwYTk4YmM2ZGE0IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)


[**Project Presentation Video on Linkedin**](https://www.linkedin.com/posts/architkannan_codebasics-resumeprojectchallenge-dataanalytics-activity-7360347125068582913-0fx6?utm_source=share&utm_medium=member_desktop&rcm=ACoAAAu24ssBa8xnl0qDKhvhVsegfe25y8b0D2o)



---

### ❗The Problem
- India faces severe air pollution, with 14 cities ranking among the world’s top 20 most polluted urban centers.
- ***AirPure Innovations***, an early-stage air purifier startup, needed answers on:
  - Pollutants to target
  - Essential product features
  - Priority cities and market size
  - How R&D should align with local pollution patterns
- Decision-making was hindered by fragmented AQI, health, population, and vehicle datasets.

---

## 💡 How to Explore this Project

Scroll through this README to explore insights, dashboard structure, and metrics.  


If you’d prefer to skip ahead and see a snapshot of the dashboard directly, jump down to the **Solution** section below. 

---

## 📝 Overview
This project analyzes three core dimensions to guide product-market fit:
1.	**Severity Mapping**– Cities with persistent or worsening AQI levels.
2.	**Health Impact Correlation** – The health burden of pollution and its effect on consumer well-being.
3.	**Demand Triggers** – How pollution spikes influence consumer behavior and purifier demand.


**Goal:** Design a ***self-explanatory dashboard*** for management and the product strategy team.


**Deliverables:**

•	**Market Prioritization Dashboard** with:

    o	City risk scores (AQI × population density × income)
    
    o	Health cost impact projections
  
•	**Product Requirements Document** outlining:

    o	Must-have features
    
    o	Competitor feature gap matrix
    
    o	Tiered pricing models for target segments

---

## 🔢 Data Sources

The primary actual datasets for this project were sourced from [**Dataful**](https://dataful.in/).

1. **Air Quality Index (AQI)**: Day-wise, state-wise AQI for major Indian cities (2022–2025).  
2. **Health Data**: Disease cases & deaths by state/district (2022–2025).  
3. **Vehicle Registration Data**: State-wise vehicle counts by class/fuel type (2022–2025).  
4. **Population Projections**: State & gender-wise urban population (2011–2036).  
5. **External Research & Trends**: Google Trends search interest (air purifier purchase, child asthma-related terms), competitor analysis, and secondary research basis research papers.

---

## ✅ Solution: Dashboard & Analytics
I developed a **Power BI dashboard** to provide actionable insights for AirPure Innovations:

**Tools & Techniques**
- **Power BI**
- **Excel**
- **DAX**

### Dashboard

🚀 [**Live Dashboard**](https://app.powerbi.com/view?r=eyJrIjoiZGQxNzRlNDItMDc5Yi00NjY2LTlmZDItNGEwYTk4YmM2ZGE0IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)


![AirPure Innovations Dashboard](https://github.com/architkannan/airpure-innovations-codebasics-rpc-july2025/blob/main/AirPureInnovations.gif)



**Dashboard Structure & Insights:**

| Visual | Purpose and Key Insight |
|--------|----------------------|
| **Bar chart – Top 5 & Bottom 5 cities** | Identified most and least polluted cities. Byrnihat had 9X higher average AQI than Tirunelveli (Dec 2024 – May 2025). |
| **Column chart – Monthly AQI trends** | Nov–Jan consistently exceeded mean AQI in top 10 states by area (Apr 2022–Apr 2025). |
| **Pie chart – Bengaluru vs Delhi** | Bengaluru recorded 24X more 'Satisfactory' air quality days than Delhi (Mar–May 2025). |
| **Weekday vs Weekend AQI column chart** | Negligible difference across metros — pollution is consistent daily. |
| **Pollutant Concentration Matrix** | PM2.5 & PM10 identified as top pollutants nationally. |
| **Population vs AQI combo chart** | Northern cities show high AQI regardless of population size. |
| **Health Correlation Tables** | AQI spikes correlate with child asthma searches (r=0.94) and air purifier purchase keywords (also r=0.94). |
| **Competitor Perception Map** | Recommended opportunity zone based on competition positioning. |
| **City Risk & Health Cost Matrix** | Heatmap highlighted high-risk Tier 1 metros and emerging hotspots. |

---

## 🌟 Impact: Product & Market Insights

### **Priority Cities & Pollution Focus**
- Tier 1 metros as high risk, high priority

- Pollutants prioritized: PM2.5, PM10, VOCs (volatile organic compounds), coarse dust  


### **Product Solution Overview**


[**Complete Product Requirements Document**](https://docs.google.com/document/d/15WxBphoL1G_wUxiuHMRIaPkupubzAvDrbpLoNITbiPs/edit?tab=t.0)




- **Metro-smart, portable purifier** for India’s mid-priced segment
  
- **Optimized filtration**: HEPA H13, pre-filter for coarse dust, activated carbon for VOCs
  
- **Uninterrupted operation**: Rechargeable battery for 4–8 hours
  
- **Hassle-free maintenance**: Tool-free, quick-swap cartridges with local replacements
  
- **Portability & intuitive controls**: Lightweight, easy to move, real-time AQI feedback




### **Core value proposition**  
*"Cleaner air for every metro home — portable, reliable, and designed for India’s toughest city pollution challenges."*



### **Must-Have Features & Purpose**
| Feature | Purpose / Insight |
|--------|-----------------|
| True HEPA H13 Filtration | Captures 99.97% of fine particles (PM2.5, PM10, allergens, dust). |
| Pre-filter for Coarse Dust | Handles urban debris from construction, traffic, and seasonal storms. |
| Activated Carbon Filter | Removes VOCs and odors, critical for indoor pollution mitigation. |
| Real-time PM2.5 & VOC Sensors | Live air quality feedback; data-driven feature based on AQI trends. |
| Rechargeable Battery | Ensures operation during frequent urban power cuts. |
| Portability | Lightweight, compact, and easy to relocate. |
| Auto Mode | Sensor-based fan speed adjusts to pollution levels. |
| Quiet Operation (<45 dB) | Suitable for bedrooms and living spaces. |
| Tool-Free Filter Replacement | Minimizes downtime and ensures consistent purification. |
| Intuitive User Interface | Simplifies air quality monitoring for all household members. |

### **R&D and Market Insights**
- Feature gap analysis identified opportunities for mid-tier MVP.  
  
- City risk scoring informed targeted market entry and prioritization.
  
- Dashboard provided quantitative justification for MVP design, feature selection, and customer segmentation.  

---

## 📌 Deliverables

- **Market Prioritization Dashboard**: Heatmap, city risk scores, health cost impact projections.
  
- **Product Requirements Document**: Must-have features, tiered pricing recommendations, MVP specifications.
  
- **Insights Repository**: Health correlations, pollutant prioritization, regional analysis, competitor gaps.  

---


## Acknowledgements
[Codebasics](https://codebasics.io/)

[Dataful](https://dataful.in/)



---

## Conclusion

This project demonstrates the ability to:

1. Extract actionable insights from complex, multi-source datasets.  
2. Apply advanced Excel and Power BI techniques for decision-focused analytics.  
3. Directly inform product design, market prioritization, and strategic R&D decisions.  

### **Contact**
If you’d like to discuss this project or collaborate, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/architkannan/) or [email](mailto:architkannan@zohomail.in).


