# 📊 Task 2 – Campaign Performance Dashboard  

## 📌 Overview  
This project delivers an interactive **marketing campaign performance dashboard** built in **Power BI** using the provided `Facebook Ads Performance Dataset – Kaggle`.  

The dashboard provides:  
- **Campaign KPIs** (Impressions, Clicks, CTR, Conversions, Spend, ROI)  
- **Top-performing ads/posts** with detailed breakdowns  
- **ROI summary** across campaigns  
- **Audience insights** (Age, Gender, Device, Region)  
- **Interactive filters** for deep dives  
- **Actionable recommendations** based on data trends  

---

## ⚙️ Data Source  
- Dataset: `Facebook Ads Performance Dataset – Kaggle`  
- Key Fields:  
  - **Impressions**  
  - **Clicks**  
  - **Approved_Conversion**  
  - **Spend**  
  - **Campaign / Ad ID / Ad Name**  
  - **Age / Gender / Device / Region**  

---

## 🧮 Metrics & Calculated Fields  
The following calculated fields were created in Power BI:  

- **Conversion_Value** = `100` (configurable)  
- **Revenue** = `Approved_Conversion * Conversion_Value`  
- **CTR %** = `(Clicks / Impressions) * 100`  
- **CPC (Cost per Click)** = `Spend / Clicks`  
- **CPA (Cost per Acquisition)** = `Spend / Approved_Conversion`  
- **CPM (Cost per 1000 Impressions)** = `(Spend / Impressions) * 1000`  
- **CVR % (Conversion Rate)** = `(Approved_Conversion / Clicks) * 100`  
- **ROAS (Return on Ad Spend)** = `Revenue / Spend`  
- **ROI %** = `((Revenue – Spend) / Spend) * 100`  

---

## 📊 Dashboard Structure  

1. **KPI Header (Scorecards)**  
   - Impressions | Clicks | CTR % | Conversions | Spend | ROI %  

2. **Top-Performing Posts (Table)**  
   - By Ad ID / Campaign with metrics (Impressions, Clicks, CTR %, Conversions, CPC, CPA, ROI %).  

3. **ROI Summary (Visuals)**  
   - ROI % by Campaign (Bar Chart)  
   - Spend vs ROI % with Conversions bubble (Scatter Plot)  

4. **Audience & Distribution (Charts)**  
   - Spend by Campaign / Device (Pie/Donut Chart)  
   - CTR % by Age (Bar Chart)  
   - Conversions by Gender (Bar Chart)  

5. **Interactive Filters**  
   - Age | Gender | Campaign | Device / Region  

6. **Recommendations Panel**  
   - Text box summarizing key insights (e.g., reallocate budget, target specific age groups, pause low-ROI campaigns).  

---

## 🎮 How to Use the Dashboard  
- **Interact with Filters** (Age, Gender, Campaign, Device) to slice performance.  
- **Click column headers** in the table to re-sort posts dynamically.  
- **Hover on charts** to view tooltips with exact numbers.  
- Use the **Recommendations panel** to guide marketing strategy adjustments.  

---

## 📤 Deliverables  
- **Overview of campaign KPIs**  
- **Insights into top-performing posts**  
- **ROI summary**  
- **Interactive filters (by age, region, device, etc.)**  
- **Actionable recommendations**  

---

## ✅ Key Takeaways  
- Provides a **360° view of campaign effectiveness**.  
- Highlights **which campaigns/posts drive the most ROI**.  
- Enables **data-driven decision-making** with interactive filters.  
- Supplies **actionable recommendations** for optimization.  

---

## 📂 Folder Structure  

```text
FUTURE_DS_02/
├── 📁 1_Data/
│   ├── 📄 data.csv
│   └── 📄 TASK 2 DATA CLEANED.csv
├── 📊 2_PowerBI/
│   └── 📈 task 2.pbix
├── 🖼️ 3_Assets/
│   └── 📸 screenshots/
├── 📑 4_Report/
│   ├── 📝 Executive_Summary.docx
│   └── 🎤 Presentation.pptx
└── 📘 README.md
```

<p align="center"> ✨ Maintained by <a href="https://github.com/yashhavalannache">Yash Havalannache</a> ✨ </p> 