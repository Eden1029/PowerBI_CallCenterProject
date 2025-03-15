# 📞 Call Center Trend Analysis - Power BI & Excel Dashboard  

## 📌 Overview  
This **Call Center Analysis Project** provides a **detailed performance evaluation** of call center operations, covering **call volume, resolution rates, agent efficiency, customer satisfaction, and issue categories**.  
The dataset was analyzed using **Power BI** for visualization and **Excel** for data preparation.  

---

## 📂 Dataset Details  
- **Data Source:** Internal Call Center Records  
- **Time Period:** **Jan 1, 2021 – Mar 31, 2021**  
- **Total Calls:** **5,000**  
- **Resolved Calls:** **3,646** (**72.92% Resolution Rate**)  
- **Key Columns:**
  - **Agent Performance:** Calls handled, resolution rate, speed of answer  
  - **Call Metrics:** Answered vs. unanswered, resolution success rate  
  - **Customer Issues:** Payment, Streaming, Technical Support, Contract, Admin  
  - **Satisfaction Scores:** Customer ratings based on resolution speed  

---

## 🧹 Data Cleaning Process  
### ✅ **Handling Missing Values**  
- Checked for missing values in **call resolution and agent performance columns**.  
- **No major missing values** found, ensuring clean dataset quality.  

### ✅ **Data Standardization**  
- Standardized **call status labels** (e.g., "Yes"/"No" → "Y"/"N") for consistency.  
- Consolidated **customer issue types** into **5 main categories**.  

### ✅ **Numeric Data Adjustments**  
- Analyzed **average call handling time** per agent for efficiency scoring.  
- **Rounded satisfaction scores** to **two decimal places** for clarity.  

---

## 📐 Data Modeling
Below is the star schema model used in this project:

![Data Model](https://github.com/Eden1029/PowerBI_CallCenterProject/blob/main/Call%20Center%20Trend%20Data%20Model.png)

---

## 🔍 Key Insights & Trends  

### 1️⃣ **Call Handling Performance**  
✅ **Total Calls:** **5,000**  
✅ **Total Answered Calls:** **4,054** (**81.08% Answer Rate**)  
✅ **Total Resolved Calls:** **3,646** (**72.92% of all calls**)  

🔹 **Observation:**  
- **81% of calls were answered**, indicating strong call center responsiveness.  
- **Resolution rate of 72.92%** suggests effective customer support but room for improvement.  
- **Agents handle ~1,667 calls per month**, meaning **high call load per agent**.  

---

### 2️⃣ **Agent Performance Analysis**  
✅ **Best Performing Agent:** **Jim**  
✅ **Worst Performing Agent:** **Stewart**  

| Agent    | Total Calls | Total Resolved | Resolution Rate (%) |  
|----------|------------|----------------|----------------------|  
| **Jim**  | **666**    | **485**        | **72.9%**            |  
| **Martha**| **638**    | **461**        | **72.2%**            |  
| **Dan**  | **633**    | **471**        | **74.4%**            |  
| **Diane** | **633**    | **452**        | **71.4%**            |  
| **Stewart**| **582**   | **424**        | **72.9%** (Lowest)   |  

🔹 **Observation:**  
- **Jim handled the highest call volume (666 calls)** while maintaining **strong resolution rates**.  
- **Stewart had the lowest performance**, struggling with call resolution.  
- **Agent performance varies slightly**, but most stay within a **71-74% resolution success rate**.  

---

### 3️⃣ **Customer Issue Breakdown**  
✅ **Most Common Issues:**  
| Issue Type        | Calls | % Share |  
|------------------|-------|---------|  
| **Streaming Issues** | **749** | **15%** |  
| **Technical Support** | **736** | **14.7%** |  
| **Payment Problems** | **729** | **14.6%** |  
| **Admin Support** | **723** | **14.5%** |  
| **Contract Issues** | **709** | **14.2%** |  

🔹 **Observation:**  
- **Streaming & Technical Support issues are the most common.**  
- **Payment-related issues account for 14.6%**, meaning financial transactions are a frequent challenge.  
- **Call center should allocate specialized agents** for high-impact areas like **Streaming & Technical Support**.  

---

### 4️⃣ **Call Resolution & Response Time Trends**  
✅ **Average Speed of Answer:** **67.52 seconds**  
✅ **Average Talk Duration Impact on Satisfaction Scores:**  
| Talk Duration (min) | Avg Satisfaction Score |  
|---------------------|----------------------|  
| **0 - 1 min**      | **3.4**              |  
| **1 - 3 min**      | **3.5**              |  
| **3 - 5 min**      | **3.7**              |  
| **5+ min**         | **4.0**              |  

🔹 **Observation:**  
- **Satisfaction score increases with call duration.**  
- **Longer, well-handled calls (5+ min) result in the highest satisfaction (4.0).**  
- **Reducing response time while improving quality** can balance **customer satisfaction and efficiency**.  

---

### 5️⃣ **Monthly Call Trends**  
| Month     | Total Calls | Answered (%) | Resolved (%) |  
|----------|------------|-------------|------------|  
| **Jan 2021** | **1,600** | **80.5%** | **72.1%** |  
| **Feb 2021** | **1,750** | **82.3%** | **74.3%** |  
| **Mar 2021** | **1,650** | **81.1%** | **72.4%** |  

🔹 **Observation:**  
- **Call volume remained steady across Q1 2021.**  
- **February had the best resolution rate (74.3%)**, showing possible **agent efficiency improvements**.  
- **No major seasonal spikes**, indicating **consistent customer service demand**.  

---

## 📊 Power BI Dashboard Features  
The **interactive Power BI dashboard** provides:  
✅ **Total Calls, Answer Rates, and Resolution Rates**  
✅ **Agent Performance Comparison**  
✅ **Customer Satisfaction Score Analysis**  
✅ **Issue Breakdown & Trends**  

📌 **Download the Power BI File:** [Call Center Trend Dashboard.pbix](https://github.com/Eden1029/PowerBI_CallCenterProject/blob/main/Call%20Center%20Trend%20Dashboard.pbix)  
📌 **View the Dashboard Report:** [Call Center Trend Dashboard.pdf](https://github.com/Eden1029/PowerBI_CallCenterProject/blob/main/Call%20Center%20Trend%20Dashboard.pdf)

---

## 🚀 Future Improvements  
🔹 **Agent Training** to improve **low-performing agent scores**.  
🔹 **Reduce Speed of Answer Time** from **67s to under 60s**.  
🔹 **Enhance Customer Resolution Strategy** for high-frequency issues like **Streaming & Technical Support**.  
🔹 **Introduce AI-powered chatbots** to **automate FAQs and repetitive queries**.  

---

## 🤝 Connect with Me  
📧 **Email:** eden.vietnguyen@gmail.com  
🔗 **LinkedIn:** [www.linkedin.com/in/eden-nguyen](https://www.linkedin.com/in/eden-nguyen)  
🌐 **Portfolio Website:** [eden-nguyen.vercel.app](https://eden-nguyen.vercel.app/)  


