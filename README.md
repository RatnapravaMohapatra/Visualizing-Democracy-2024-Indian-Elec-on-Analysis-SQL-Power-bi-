# Visualizing Democracy: 2024 Indian General Election Analysis

A comprehensive project to analyze and visualize the **2024 Indian General Elections** using **SQL** and **Power BI**. This project showcases advanced data modeling, query optimization, and dashboard creation to derive actionable insights into voter behavior, party performance, and state-wise election outcomes.

---

##  Project Overview

- **Objective:** Transform raw election data into meaningful visualizations and insights.
- **Technologies Used:** 
  - **SQL** (for data querying and transformations)
  - **Power BI** (for interactive dashboards and data modeling)
- **Scope:** National-level analysis, state-level breakdown, and constituency-level insights.
- **Dashboards Included:**
  1. Overview Analysis
  2. State Demographics
  3. Political Landscape by State
  4. Constituency Analysis

---

##  Data Model

- **Key Tables:**
  - `constituencywise_results`
  - `partywise_results`
  - `statewise_results`
  - `constituencywise_details`
  - `states`
- **Primary Keys:**
  - `Constituency_ID`
  - `Parliament_Constituency`
  - `Party_ID`
  - `State_ID`


## SQL Queries

### Key Analysis Performed
- Total number of seats and seats won by each alliance (NDA, I.N.D.I.A., OTHER)
- State-wise and constituency-wise seat distribution
- Alliance majority analysis per state
- Winning candidate details and vote margins
- Distribution of **EVM votes vs Postal votes**
- Top 10 candidates with highest EVM votes
- Winner vs runner-up analysis for each constituency


## 📈 Power BI Dashboards

### Dashboards Developed
- **Overview Analysis**
  - Total seats won by alliances
  - Seat share percentage
  - Party performance summary

- **State Demographic Analysis**
  - State-wise total seats and majority analysis
  - Interactive map with drill-down features

- **Political Landscape by State**
  - Party alliance comparison by state
  - Majority indicator (NDA vs I.N.D.I.A.)

- **Constituency Analysis**
  - Winning candidates, vote share, and margins
  - Runner-up analysis and constituency-level breakdown

## 🛠 Setup Instructions

### 1. Database Setup
- Import the election dataset into your SQL environment.
- Execute the provided queries in order to:
  - Create necessary relationships
  - Add alliance classifications
  - Generate derived insights

### 2. Power BI Setup
- Open the `.pbix` file in Power BI Desktop.
- Ensure your data source paths are correctly mapped.
- Refresh the data model to reflect updated SQL outputs.

---

##  Election Details
- **Voting Dates:** 19 April – 1 June 2024  
- **Result Date:** 4 June 2024  
- **Total Seats Analyzed:** 543  

---

##  Features
- Interactive electoral maps
- Alliance-based filtering and drill-down
- Margin of victory visualization
- Comparative analysis (NDA vs I.N.D.I.A. vs OTHER)

---

## 👨‍💻 Developed By
**Ratnaprava Mohapatra**  

