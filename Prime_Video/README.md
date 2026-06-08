<div align="center">

<img src="https://upload.wikimedia.org/wikipedia/commons/f/f1/Prime_Video.png" width="280"/>

# 🎬 PRIME VIDEO ANALYSIS DASHBOARD

### 🌌 OTT Streaming Analytics Dashboard Built with Power BI

<img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=700&size=28&duration=2500&pause=1000&color=00A8E1&center=true&vCenter=true&width=900&lines=Interactive+Power+BI+Dashboard;Amazon+Prime+Video+Analytics;Cinematic+OTT+Style+UI;Streaming+Insights+%26+Visualizations;Data+Analytics+Portfolio+Project"/>

<p align="center">

<img src="https://img.shields.io/badge/POWER%20BI-DASHBOARD-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
<img src="https://img.shields.io/badge/DATA%20ANALYTICS-PROJECT-00A8E1?style=for-the-badge"/>
<img src="https://img.shields.io/badge/STATUS-COMPLETED-success?style=for-the-badge"/>
<img src="https://img.shields.io/badge/UI%2FUX-PREMIUM-blueviolet?style=for-the-badge"/>

</p>

---

## 🌟 PROJECT OVERVIEW

This project is a **premium OTT platform-inspired analytics dashboard** created using **Power BI**.  
The dashboard provides deep insights into **Amazon Prime Video’s Movies & TV Shows dataset** through advanced visual storytelling, interactive filters, KPI cards, and cinematic UI design.

Designed with a **Netflix / Prime Video inspired interface**, this dashboard transforms raw entertainment data into meaningful business insights.

---

# 🔥 LIVE DASHBOARD PREVIEW

<p align="center">
<img width="1112" height="625" alt="Screenshot 2026-05-26 182229" src="https://github.com/user-attachments/assets/c5ce00fe-572a-4c66-9c43-76659f50923e" />

</p>

---

# 🎯 KEY HIGHLIGHTS

✨ Dark Cinematic Theme  
✨ Interactive Sidebar Navigation  
✨ Advanced KPI Cards  
✨ Dynamic Filters & Slicers  
✨ Genre & Ratings Analysis  
✨ Country-Wise Content Distribution  
✨ OTT Platform Inspired Design  
✨ Premium UI/UX Experience  

---

# 🎨 DASHBOARD FEATURES

<table>
<tr>
<td width="50%">

## 📌 KPI Metrics

- 🎬 Total Movies
- 📺 Total TV Shows
- ⭐ Average Ratings
- 🌍 Total Countries
- 🎭 Total Genres

</td>

<td width="50%">

## 📊 Visual Analytics

- 🌎 World Content Map
- 📈 Content Growth Trend
- 🍩 Content Type Distribution
- 🎭 Genre Analysis
- 🎬 Director Insights
- 🔥 Trending Shows Section

</td>
</tr>
</table>

---

# 🖼️ DASHBOARD SECTIONS

| Section | Description |
|----------|-------------|
| 🎬 KPI Cards | Key streaming platform metrics |
| 🌎 World Map | Country-wise content distribution |
| 📈 Trend Analysis | Content growth over years |
| 🍩 Donut Chart | Movies vs TV Shows |
| 🎭 Genres Chart | Top categories analysis |
| 🔥 Trending Shows | OTT poster showcase |
| 🎛️ Filter Panel | Dynamic user interaction |

---

# 🛠️ TOOLS & TECHNOLOGIES

<p align="center">

<img src="https://skillicons.dev/icons?i=python"/>
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
<img src="https://img.shields.io/badge/DAX-Advanced-blue?style=for-the-badge"/>
<img src="https://img.shields.io/badge/PowerQuery-Transform-orange?style=for-the-badge"/>

</p>

---

# 📂 DATASET DETAILS

The dataset contains:

✅ Movies & TV Shows  
✅ Ratings Information  
✅ Genre Categories  
✅ Country Distribution  
✅ Directors & Cast  
✅ Release Year Trends  

---

# ⚡ DAX MEASURES USED

## 🎬 Total Movies

```DAX
Total Movies = 
CALCULATE(
    COUNTROWS(amazon_prime_titles),
    amazon_prime_titles[type] = "Movie"
)
