# Pivot-Tables-U.S-Voters
# 🗳️ Pivot Tables – U.S. Voter Data Analysis (Excel)

This project showcases how **PivotTables in Microsoft Excel** can be used to explore and analyze U.S. voter demographics and turnout rates. It includes a step-by-step breakdown of key questions related to voter participation, along with visual evidence and calculated insights.

## 📁 Repository Contents

- `U.S-Voter-Data.xlsx`: Raw dataset used for Pivot Table analysis.
- `images/`: Folder containing screenshots of Pivot Table results.
  - `Q1.png` to `Q5.png`: Corresponding visuals for each analysis question.

## 🔧 Tools & Techniques

- **Microsoft Excel** (PivotTables & Calculated Fields)
- Basic Excel operations: Filtering, Sorting, Percentage of Parent/Column Total
- Custom Calculated Fields for metrics like Voter Population % and Turnout %

---

## 📊 Analysis Questions & Insights

### 1. How many states had a Voter Population % below 55%? Which states?

📌 **Method**:
- Created a **Calculated Field**:  
  `Voter Population % = Confirmed Voters / Citizen Population`
- Added `State` to Rows and `Voter Population %` to Values.

📷 **Result**:  
**5 States** had voter population % below 55%:
- **Texas**
- **Arkansas**
- **Oklahoma**
- **Hawaii**
- **West Virginia**

![Q1](images/Q1.png)

---

### 2. How many confirmed voters in California were over 65 in 2012? What % of California & national total?

📌 **Steps**:
- Added `State` and `Age` to Rows; `Confirmed Voters` to Values.
- Filtered for **California** and age **65+**.

📊 **Results**:
- Confirmed Voters over 65 in CA: **2,902,000**
- % of CA's total confirmed voters: **21.56%**
- % of total U.S. confirmed voters: **2.18%**

![Q2](images/Q2.png)

---

### 3. What % of citizen population do 45–64 year olds represent? And what % of confirmed voters?

📌 **Setup**:
- `Age` in Rows, `Citizen Population` and `Confirmed Voters` in Values.
- Set both to display as **% of Column Total**.

📊 **Results**:
- **45–64 year olds** represent:
  - **35.63%** of total **Citizen Population**
  - **39.12%** of total **Confirmed Voters**

![Q3](images/Q3.png)

---

### 4. Which state had the highest voter turnout rate? What about among 18–24 year olds?

📌 **Calculated Field**:
- `Voter Turnout = Confirmed Voters / Registered Voters`

📊 **Results**:
- 🏆 Highest Overall Turnout: **Colorado** – **94.69%**
  ![Q4.1](images/Q4.1.png)
- 🧑‍🎓 Highest (18–24 age group): **Wisconsin** – **93.18%**
  ![Q4.2](images/Q4.2.png)

---

### 5. As a politician, which states would you target to boost turnout among 18–24 year olds?

📌 **Strategy**:
- Used filters to rank states by **lowest turnout rate** for **18–24** year olds.

📊 **Target States**:
- **West Virginia**
- **Arkansas**
- **Texas**
- (See image for full list)

These states represent key opportunities to **engage younger voters** and close the turnout gap.

![Q5](images/Q5.png)

---

## 💡 Key Insights

- Voter turnout varies significantly **by state** and **age group**, especially among young voters.
- Some states consistently appear with **low participation rates**, offering clear targets for civic engagement campaigns.
- Excel's PivotTable functionality is a powerful tool to explore **multi-dimensional demographic data** with minimal coding.

---

## 👤 Contact

For questions, feedback, or collaboration opportunities:

- **📧 Email**: maxnguyenhoangminh@gmail.com  
- **🔗 LinkedIn**: [Max Nguyen Hoang Minh](https://www.linkedin.com/in/max-nguyen-hoang-minh)

---



