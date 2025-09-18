#  Restaurant Tips Analysis (EDA Project)

This project explores the **Seaborn Tips dataset**, which records restaurant bills and tips.  
The goal is to understand tipping behavior and the factors that influence how much people tip.  

---

##  Objectives
The analysis answers questions such as:
- Do men or women tip more?  
- Do smokers tip differently than non-smokers?  
- Are tips higher during lunch or dinner?  
- Does the size of the total bill affect the size of the tip?  
- Do larger groups leave bigger tips (percentage-wise)?  

---

##  Dataset
- **Name**: Tips Dataset  
- **Source**: Built into the Seaborn library  
- **Size**: 244 rows × 7 columns  
- **Features**:  
  - `total_bill` → Total bill in USD  
  - `tip` → Tip amount in USD  
  - `sex` → Gender of the customer  
  - `smoker` → Smoker or non-smoker  
  - `day` → Day of the week  
  - `time` → Meal time (Lunch/Dinner)  
  - `size` → Group size  

---

##  Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

##  Project Workflow
1. Data loading and overview  
2. Feature engineering (created **tip percentage**)  
3. Exploratory Data Analysis (EDA):  
   - Distribution plots (bill, tip, tip %)  
   - Categorical comparisons (day, time, gender, smoker)  
   - Scatterplots & trendlines  
   - Grouped summaries  
   - Correlation heatmap  
4. Insights and business takeaways  

---

##  Key Insights
- **Average tip % overall**: ~16% of total bill  
- **Best tipping days**: Friday (16.99%) and Sunday (16.69%)  
- **Lunch vs Dinner**: Lunch tips (16.41%) are slightly higher than dinner (15.95%)  
- **Smokers vs Non-smokers**: Smokers tip slightly more (16.32%) than non-smokers (15.93%)  
- **Group size effect**: Solo diners tip the highest % (21.7%), larger groups tip less %  

---

##  Repository Structure
restaurant-tips-eda/
│── README.md
│── tips_analysis.ipynb # Jupyter Notebook
│── tips_with_tip_percent.csv # Cleaned dataset
│── avg_tip_percent_by_day.png # Sample visualization


---

##  Notebook
 [View Notebook](./tips_analysis.ipynb)  

---

#  Appendix  

## Appendix A: GitHub Repository Link  

The complete Jupyter Notebook (`.ipynb` file) for this project has been uploaded to GitHub.  
It can be accessed at the following link:  

🔗 [https://github.com/bibekshrestha1124-glitch/restaurant-tips-eda](https://github.com/bibekshrestha1124-glitch/restaurant-tips-eda)  


