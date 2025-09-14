# 🎬 Data-Driven Movie Studio Strategy  
**Phase 2 Project – Group 3**  

---

## 📌 Overview  
This project explores data from the movie industry to guide the launch of a **profitable new movie studio**.  
Our task was to conduct **exploratory data analysis (EDA)** on real-world movie datasets in order to identify which types of films are most successful at the box office and how production budgets influence outcomes.  

The ultimate goal is to provide **actionable, business-focused recommendations** that will help decision-makers understand what films to produce, how much to spend, and what strategies maximize returns on investment.  

We analyzed over **900 films released between 2010 and 2019**, integrating multiple datasets to uncover clear insights about profitability, risk management, and audience behavior.  

---

## 👥 Team Members  
This was a group project completed by **Group 3** as part of our Data Science Phase 2 deliverable:  
- Fatuma Tari
- Brian Kahiu
- Clariss Wangari *(Scrum Master)*  
- Lydia Onkundi

The team collaborated using GitHub for version control and branch management. Each member contributed to the analysis, documentation, and presentation.  

---

## 🎯 Business Understanding  

### The Problem  
Our company wants to enter the competitive movie industry but does not yet know which types of films are most likely to succeed. Entering the wrong genre or overspending on blockbuster budgets could result in financial losses.  

The challenge is therefore:  
**Which types of films will maximize box office success while balancing risk and reward?**  

### Key Business Questions  
To answer this challenge, we focused on three central questions:  
1. **Genres** – Which film genres deliver the highest Return on Investment (ROI)?  
2. **Budgets** – What budget ranges are most cost-effective for a new studio?  
3. **Ratings** – Do critical or audience ratings strongly influence financial success?  

---

## 📊 Data Understanding & Analysis  

### Data Sources  
The datasets were collected from multiple industry-standard sources, including:  
- **Box Office Mojo** – worldwide gross revenues  
- **IMDB** – ratings, metadata, and film attributes (stored in a SQLite database)  
- **The Numbers** – production budget and revenue information  
- **Rotten Tomatoes** and **TheMovieDB** – supplemental information for validation and enrichment  

The **sample includes 934 films from 2010–2019** with complete data on budgets, revenues, and ratings.  

### Metrics & Methods  
- ROI = Worldwide Gross ÷ Production Budget  
- Correlation analysis (budget vs. revenue)  
- Comparative analysis across genres  
- Linear Regression (Budget vs. Revenue) → R² ≈ *0.65*, showing that ~65% of revenue variance is explained by production budget  
- Data visualizations to support recommendations  

---

## 🔑 Findings & Recommendations  

### 1️⃣ Focus on High-ROI Genres  
- Horror films consistently outperform other genres, with an **average ROI of 14.3x**.  
- Mystery and Thriller genres also show above-average performance compared to the market.  
- These genres typically require **lower production budgets**, yet they achieve strong commercial success.  

➡️ **Recommendation**: Prioritize horror, thriller, and mystery films as the foundation of the new studio’s portfolio.  

| Genre   | Avg ROI | Avg Budget | Success Rate |
|---------|---------|------------|--------------|
| Horror  | 14.3x   | $15M       | 68%          |
| Average | 3.7x    | $60M       | 45%          |

---

### 2️⃣ Adopt a Tiered Budget Strategy  
- Strong correlation exists between budget and revenue, but **returns diminish after $100M**.  
- The **sweet spot for ROI lies in the $20M–$60M range**, where financial risk is lower but potential revenue remains strong.  

➡️ **Recommendation**: Use a phased budget approach, scaling up only after early successes.  

| Tier | Budget Range | Strategy |
|------|--------------|----------|
| 1️⃣ Foundation | $10M–$30M | Launch profitable horror/thrillers |
| 2️⃣ Growth     | $30M–$60M | Expand into mystery/action, franchises |
| 3️⃣ Expansion  | $60M–$100M | Compete with major studios |

---

### 3️⃣ Balance Quality vs. Commerce  
- Ratings and ROI show a **weak correlation (-0.06)**, indicating that critical acclaim does not guarantee financial success.  
- However, ratings have a **moderate positive effect on revenue (+0.28)**, showing some value in marketing appeal.  

➡️ **Recommendation**: Focus primarily on **audience demand and commercial viability**, while ensuring sufficient quality to attract consistent viewership.  

---

## 📈 Visualizations  

1. ROI by Genre – Horror dominates profitability  
   <img width="1190" height="790" alt="image" src="https://github.com/user-attachments/assets/ddd2bb7f-2413-43e9-943e-85beadff4114" />

2. Budget vs. Revenue – Clear sweet spot at mid-range budgets  
 <img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/f01e4f3e-dc0a-4048-aa7f-ae939a93cfe4" />

3. Ratings vs. ROI – Weak correlation between ratings & ROI  
   <img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/4ee26038-106f-444b-8f73-543cbb2f00a8" />
  

---


## 🛠️ Deliverables  
This project produced three main deliverables:  

-  **Presentation (PDF)**
  A non-technical presentation for business stakeholders, highlighting findings and recommendations.

-  **Presentation video(PDF)**
  A non-technical presentation video for business stakeholders, highlighting findings and recommendations.
  https://drive.google.com/file/d/1ZR9RMNVtSU-6E-G-AeEupIVSbDPn5N5K/view?usp=sharing

-  **Jupyter Notebook**  
  A technical notebook combining Python code, analysis, and Markdown explanations.
  https://github.com/KareeClariss/dsc-phase-2-project-G3/blob/Brian/student.ipynb

-  **GitHub Repository**  
  A collaborative version-controlled environment documenting our full workflow.  

---

## ✅ Conclusion  
Based on our exploratory analysis, we recommend the following strategic path for launching the new studio:  
- Begin with **low- to mid-budget horror/thriller films**, where ROI is highest and financial risk is minimized.  
- Maintain strict **budget control within the $20M–$60M range** to capture strong returns without competing with blockbusters.  
- Focus on **audience preferences and commercial viability** over critic reviews, ensuring a balance of profitability and sustainable growth.  

With this approach, the studio can expect a **3–8x ROI within 18–24 months**, with potential for greater success through sequels, franchises, and diversification.  

---

## 📂 Repository Structure  

| File / Folder | Description |
|---------------|-------------|
| `student.ipynb` | Final Jupyter Notebook containing full exploratory analysis |
| `Data-Driven Movie Studio Strategy.pdf` | Final stakeholder presentation (slides) |
| `zippedData/` | Source datasets used in analysis (CSV, TSV, SQLite) |
| `README.md` | Project documentation (this file) |
| `.gitignore` | Git ignore file for excluding unnecessary/large files |

---
