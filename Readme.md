# Salesforce Pipeline Risk Detection & Early Warning System

## 📌 Overview
Sales teams manage thousands of opportunities in Salesforce, but pipeline visibility alone is not enough. Deals often stall unnoticed, revenue forecasts slip, and risks are discovered too late.

This project is a **proactive pipeline risk detection system** built using **Tableau Cloud**, designed to identify at-risk opportunities early, explain *why* they are risky, and guide sales managers toward immediate action.

---

## 🎯 Problem Statement
Salesforce provides pipeline tracking, but sales leaders face four key challenges:

- No early detection of stalled or aging deals
- Lack of prioritization for high-risk opportunities
- Static dashboards without explainability
- Disconnected insights from daily decision-making

---

## 💡 Solution
This Tableau Cloud solution continuously evaluates the sales pipeline to:

- Detect overdue and aging opportunities
- Quantify revenue exposure
- Explain risk drivers (deal age, stage stagnation)
- Provide an action-ready list of high-risk deals
- Update dynamically as data changes

---

## 🧠 Key Features

### 1️⃣ Pipeline Health KPIs
- Open Opportunities
- Overdue Opportunities
- Revenue at Risk
- Average Deal Age

### 2️⃣ Early Risk Detection
- Deals flagged using configurable overdue thresholds
- Severity classification (Low, Medium, High, Critical)

### 3️⃣ Explainable Analytics
- Risk drivers broken down by deal stage
- Tooltip-based risk explanations (no black-box AI)

### 4️⃣ Actionable Insights
- High Risk Deals Action List
- Drill-down from summary metrics to individual opportunities

### 5️⃣ Interactive & Adaptive
- Cross-filtering across charts
- Parameter-driven risk thresholds
- Real-time refresh-ready architecture

---

## 🛠 Tools & Technologies Used
- Tableau Cloud
- Tableau Calculated Fields
- Tableau Parameters
- Dashboard Actions (Filter & Highlight)
- Tableau Relationships (No physical joins)
- Explainable business logic (rule-based risk scoring)

---

## 📊 Dashboard Components
- Pipeline Risk Overview (KPIs)
- Pipeline Revenue at Risk by Severity
- Risk Drivers Breakdown by Deal Stage
- Sales Agent Efficiency Matrix
- High Risk Deals Action List

---

## 🎥 Demo & Interactive Dashboard

### 📈 Live Tableau Dashboard
View the interactive dashboard here:

👉 **[Salesforce Pipeline Risk Detection Dashboard](https://prod-in-a.online.tableau.com/t/joshidevanshi1012-3789950e71/views/SalesforcePipelineRiskDetectionDashbaord/SalesforcePipelineRiskDetection)**

### 🔗 Embed Code
To embed this dashboard in your own webpage, use:

```html
<script type='module' src='https://prod-in-a.online.tableau.com/javascripts/api/tableau.embedding.3.latest.min.js'></script>
<tableau-viz id='tableau-viz' src='https://prod-in-a.online.tableau.com/t/joshidevanshi1012-3789950e71/views/SalesforcePipelineRiskDetectionDashbaord/SalesforcePipelineRiskDetection' width='1536' height='690' toolbar='bottom' ></tableau-viz>
```

---

## 📈 Business Impact
- Enables proactive deal intervention
- Improves forecast accuracy
- Reduces revenue leakage
- Mirrors real-world Salesforce Revenue Operations use cases

---

## 🚀 Future Enhancements

If more time were available, the following enhancements could be added:

1. **Tableau Next Integration**
   - Semantic Models for standardized pipeline definitions
   - Deeper Salesforce CRM object integration

2. **Agentforce / Slack Integration**
   - Automated alerts for newly at-risk deals
   - Risk notifications embedded in sales workflows

3. **Predictive Risk Scoring**
   - ML-based deal aging prediction
   - Probability of close based on historical patterns

4. **Scenario Simulation**
   - What-if analysis for overdue thresholds
   - Revenue impact forecasting

5. **Executive Narrative Insights**
   - Auto-generated insights using Tableau Pulse
   - Natural-language explanations of risk trends

See `docs/future_improvements.md` for more details.

---

## 📁 Project Structure

```
salesforce-pipeline-risk-detection/
│
├── README.md
├── data/
│   └── sample_data_description.md
├── tableau/
│   └── dashboard_screenshots.png
├── video/
│   └── demo_video_link.txt
└── docs/
    └── future_improvements.md
```

---

## 📊 Data Description

This project uses a Salesforce-style sales pipeline dataset consisting of:

- Accounts
- Products
- Sales Pipeline Opportunities
- Sales Teams

The data includes:
- Opportunity stages
- Deal values
- Engagement dates
- Close dates
- Sales agent assignments

Null values were intentionally handled inside Tableau using calculated fields and data modeling best practices to simulate real-world CRM data conditions.

For more details, see `data/sample_data_description.md`.

---

## 👤 Author
**Devanshi Joshi**  
Tableau Hackathon 2025

---

## 📝 License
This project is created for the Tableau Hackathon 2025.

---

## 🙏 Acknowledgments
Special thanks to the Tableau Community and Salesforce ecosystem for inspiration and best practices in pipeline analytics.