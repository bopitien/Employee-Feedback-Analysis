#  Employee Feedback Analysis – A Data-Driven Approach to Workplace Engagement

This project explores employee feedback at **BrightWave Solutions**, aiming to uncover patterns in satisfaction, engagement, and workplace sentiment using Python and basic analytics. The focus is on **descriptive insights**, not machine learning.

---

##  Project Objective

To help HR and leadership:
- Understand employee satisfaction drivers
- Identify pain points affecting engagement and retention
- Visualize feedback trends using rating metrics and comment data
- Generate actionable recommendations to improve workplace experience

---

##  Business Background

**BrightWave Solutions**, a mid-sized services company, noticed:
- Increasing staff turnover
- Average satisfaction scores with little clarity on causes
- Employee feedback forms were underutilized due to lack of structured analysis

This project provides a way to **turn that feedback into insight**.

---

##  Dataset Overview

The dataset includes both **quantitative ratings** and **free-text feedback**:
- `Overall_Ratings`, `Compensation_Benefit_Stars`, `Career_Opportunities_Stars`, etc.
- `Comment_Positives`, `Comment_Negatives`, `Advice_To_Mgmt`
- Employee attributes like `Employee_Tenure`, `Location`, and `Engagement_Participation`

---

##  Tools & Libraries

- **Language:** Python  
- **Libraries:** Pandas, Seaborn, Matplotlib, WordCloud  
- **Notebook:** Jupyter  
- **Techniques:** EDA, Word Frequency, Boxplots, Heatmaps, Temporal Trends

---

##  Key Insights

-  **Compensation** was the lowest-rated category (~1.75/5), across all locations and tenure levels  
-  **Culture & Career Opportunities** scored highest (~4.39/5), showing strong company values  
-  **Wellness Satisfaction** was much higher among employees who participated in engagement activities  
-  **Tenure** had little variation across locations or engagement status — suggesting other factors drive retention  
-  **Comment Themes:** 
  - Positives: work, good, great, people  
  - Negatives: time, manager, stress, long  
  - Advice: give, management, support, better

---

##  Visualizations Included

- Barplots and histograms for satisfaction ratings
- Heatmaps to explore relationships across tenure, engagement, and location
- Word clouds of employee comments
- Line plots showing temporal changes in sentiment over time

---

##  Recommendations

- **Review Compensation Strategy**  
- **Improve Career Growth Opportunities**  
- **Enhance Wellness & Remote Work Programs**  
- **Close the Feedback Loop** – let employees know their voices are heard

---

##  Outcome

The project provides HR with:
- Clear visual evidence of what’s working and what’s not
- A reusable Python notebook for future feedback analysis
- Better support for employee engagement strategy

---

##  Future Scope

- Add sentiment scoring using NLP or rule-based classification  
- Build dashboards with Power BI or Streamlit  
- Extend analysis to include churn prediction

---

##  Author

Built by **Brume Pascal** as part of a portfolio of real-world data analytics case studies.  
Powered by Python.

