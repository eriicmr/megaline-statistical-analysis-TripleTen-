# 📞 Megaline Plan Revenue Analysis – Sprint 4 Project  

This project analyzes customer behavior for **Megaline**, a telecom company offering two prepaid plans: **Surf** and **Ultimate**.  
The goal is to determine which plan generates more revenue and provide recommendations for the marketing team.  

Using customer usage data (calls, messages, internet traffic), I performed:  
- Data cleaning & preprocessing  
- Revenue calculation for each user  
- Customer behavior analysis with descriptive statistics and visualizations  
- **Statistical hypothesis testing** to compare plan revenues and regional differences  

---

## 📌 Project Overview  

The analysis followed five main steps:  

1. **Data Preparation**  
   - Loaded 5 datasets (`users`, `calls`, `messages`, `internet`, `plans`)  
   - Converted column types, fixed errors, handled missing values and duplicates  

2. **Feature Engineering**  
   - Aggregated monthly usage per user: calls, minutes, messages, data  
   - Calculated **monthly revenue per user** by combining base fees + extra usage  

3. **Exploratory Data Analysis**  
   - Compared customer behavior across plans  
   - Calculated averages, variance, and standard deviation  
   - Visualized distributions with histograms  

4. **Hypothesis Testing**  
   - **H1**: Revenue differs between Ultimate and Surf plan users  
   - **H2**: Revenue differs between NY-NJ customers and other regions  
   - Applied statistical tests (two-sample t-tests) to evaluate hypotheses  

5. **Conclusions**  
   - Summarized findings on which plan is more profitable  
   - Provided insights for Megaline’s marketing strategy  

---

## 🛠️ Tools & Technologies  
- Python 3.x  
- Jupyter Notebook  
- Libraries:  
  - `pandas` (data manipulation)  
  - `numpy` (numerical operations)  
  - `matplotlib`, `seaborn` (visualizations)  
  - `scipy.stats` (hypothesis testing)  

---

## 📂 Dataset  

Files used:  
- `megaline_users.csv` — user demographics & plan  
- `megaline_calls.csv` — call details  
- `megaline_messages.csv` — SMS details  
- `megaline_internet.csv` — internet sessions  
- `megaline_plans.csv` — plan details  

---

## 🎯 Key Learning Outcomes  
- Practiced **data cleaning and preparation** with multiple datasets  
- Calculated **revenue metrics** using custom business rules  
- Applied **descriptive statistics** (mean, variance, std deviation)  
- Strengthened skills in **statistical hypothesis testing** (formulating null/alt hypotheses, applying t-tests, interpreting results)  
- Learned to **translate technical results into business insights**  

---

## 🚀 How to Use  
1. Clone this repository:  
   ```bash
   git clone https://github.com/eriicmr/megaline-statistical-analysis.git
