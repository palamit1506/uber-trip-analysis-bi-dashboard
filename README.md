# 🚖 Uber Trip Analysis — Power BI Dashboard

An interactive **Power BI dashboard** designed to analyze Uber trip bookings, revenue, customer behavior, and ride patterns across cities and time windows.  
The dashboard transforms raw booking data into **business insights** to support decision-making for ride-sharing platforms.

---

## 📌 Objective
To analyze historical Uber ride data and extract key trends related to **demand, revenue, customer preferences, and trip patterns**, enabling business teams to:

- Understand ride booking behaviour
- Identify peak demand periods and high-performing areas
- Track vehicle category performance
- Improve pricing and marketing strategies

---

## 📂 Dataset
| Attribute | Details |
|----------|---------|
| Source | Public Uber ride dataset |
| Records | ~100K+ trips (city-wise) |
| Data Type | Trips, customer info, fare, trip distance, timestamps |

Core fields:
`Trip ID`, `City`, `Trip Date`, `Vehicle Type`, `Trip Distance`, `Payment Mode`, `Fare Amount`, `Driver ID`

---

## 🧼 Data Cleaning & Transformation
Performed inside **Power Query & SQL / ETL**:

- Removed null, duplicate & invalid entries
- Standardized date and time formats
- Extracted **Month, Weekday, and Hour-of-Day**
- Classified **Day vs Night trips**
- Created calculated metrics for **Average Fare**, **Total Bookings**, and **Revenue by Category**

---

## 📊 Dashboard Features

| Insight | Description |
|--------|-------------|
| 📌 Total Bookings | Count of all completed rides |
| 💰 Total Revenue | Total earning across all trips |
| 🚗 Vehicle Performance | Revenue comparison by car type |
| ⏰ Peak Travel Time | Hour/day/month demand patterns |
| 📍 Locations | Top pickup & drop-off zones |
| 💳 Customer Preference | Share of trips by payment mode |
| 📏 Trip Distance Analysis | Relationship between distance & fare |

---

## 🔍 Key Business Insights
- **SUV category generated the highest revenue despite lower booking volume**
- **Peak demand occurred during evening rush hours and weekends**
- **Online payment was the most preferred payment mode**
- **Central business districts contributed the most pickups and drop-offs**
- **Long-distance trips contributed the highest revenue per ride**

---

## 🧠 KPIs Used
| KPI | Meaning |
|-----|---------|
| Total Bookings | Count of completed trips |
| Total Revenue | Sum of trip fares |
| Avg Fare per Ride | Revenue / Bookings |
| Avg Trip Duration | Indicates customer behaviour |
| Avg Trip Distance | Long vs short ride distribution |

---

## 📁 Dashboard Pages
| Page | Focus |
|------|-------|
| Overview | KPIs & aggregated ride metrics |
| City-wise Analysis | Breakdowns by city & location |
| Customer Behaviour | Time/day preference, payment mode |
| Vehicle Insights | Category-wise revenue & demand |

---

## 🛠️ Tech Stack
| Category | Tools |
|----------|-------|
| BI Tool | **Power BI** |
| Data Modeling | Star Schema |
| Query | Power Query Editor |
| DAX Calculations | KPIs & business logic |
| ETL | Excel / SQL (as applicable) |

---

## 🚀 How to Use the Dashboard
1. Download the `.pbix` file from the repository
2. Open in **Power BI Desktop**
3. Refresh the data source if using live connections (optional)
4. Interact using slicers to filter **Date, City, Vehicle Type, and Payment Mode**

---
