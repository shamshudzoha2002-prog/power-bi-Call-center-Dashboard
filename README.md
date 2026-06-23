📞 Call Center Dashboard — Power BI

A Power BI dashboard providing comprehensive insights into call center operations, including call volumes, agent performance, sentiment analysis, and SLA compliance

 
![Dashboard Preview](https://img.shields.io/badge/Tool-Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Data Period](https://img.shields.io/badge/Data%20Period-October%202020-blue?style=flat)
 

## 📊 Dashboard Overview

The report contains **two pages**:

### 🏠 Home — Summary Dashboard
A visual overview of all key call center metrics.

### 🗂️ Grid — Detailed Call Log
A tabular drill-down view of individual call records.

---

## 🔢 Key Metrics (KPIs)

| Metric | Value |
|--------|-------|
| Total Calls | 32.94K |
| Total Call Duration (within 60 min) | 824.22K |
| Total Call Duration (within 24h) | 13.74K |
| Avg Call Duration | 25.02 |
| Response Time % (Within SLA) | 75.26% |

---

## 📈 Visuals Included

- **Total Calls by Day** — Bar chart showing call distribution across days of the week (peak on Friday & Saturday)
- **Total Calls by State** — US choropleth map showing call volume by state
- **Total Calls by Reason** — Breakdown by call reason: Billing Questions, Payments, Service Outages
- **Total Calls by Channel** — Donut chart across Call-Center (32.3%), Web (25.06%), Email (22.68%), Chatbot (19.96%)
- **Total Calls by Sentiment** — Distribution of Negative, Neutral, Very Negative, Positive, Very Positive sentiments
- **Total Calls by Call Centre** — Bar chart by city: Los Angeles (13.7K), Baltimore (11.0K), Chicago (5.4K), Denver (2.8K)

---

## 🗃️ Grid View — Data Columns

| Column | Description |
|--------|-------------|
| ID | Unique call identifier |
| Customer Name | Name of the customer |
| Channel | Contact channel (Call-Center, Chatbot, Email, Web) |
| State | US state of the customer |
| Reason | Reason for call (Billing, Payments, Service Outage) |
| Response Time | SLA status (Within SLA / Below SLA / Above SLA) |
| City | Customer's city |
| Total Call Duration | Duration of the call in seconds/minutes |

---

## 🔍 Filters Available

- **Date Range** — Filter by start and end date
- **City** — Filter by customer city
- **Channel** — Filter by contact channel

---

## 🛠️ Tech Stack

- **Tool:** Microsoft Power BI Desktop
- **File:** `project_call_center.pbix`
- **Data Period:** October 2020 (01-10-2020 to 31-10-2020)

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/call-center-dashboard.git
   cd call-center-dashboard
   ```

2. **Open the report**
   - Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
   - Open `project_call_center.pbix`

3. **Explore the dashboard**
   - Use the **Home** page for a summary view
   - Switch to the **Grid** page for detailed call-level data
   - Apply filters (Date, City, Channel) from the left panel

---

## 📁 File Structure

```
call-center-dashboard/
│
├── project_call_center.pbix   # Main Power BI report file
└── README.md                  # Project documentation
```

---

## 📌 Insights at a Glance

- **Billing Questions** dominate call reasons (~23.46K calls)
- **Negative sentiment** is the most common (11.1K calls), suggesting room for service improvement
- **Friday and Saturday** see the highest call volumes (5.5K–5.6K)
- **Los Angeles** is the busiest call centre location (13.7K calls)
- **Call-Center channel** handles the largest share (32.3%) of contacts

---
Dashboard look like - 

<img width="1291" height="731" alt="Dashboard HOME" src="https://github.com/user-attachments/assets/b88730ea-be32-4734-a22f-b5808a818f1b" />



## 📄 License

This project is for educational and portfolio purposes. Data used is sample/synthetic call center data.
