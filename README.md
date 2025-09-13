# 🎬 Data-Driven Movie Studio Strategy  
**Phase 2 Project – Group 3**  

---

## 📌 Overview  
This project explores movie industry data to guide the launch of a **profitable new movie studio**.  
Using exploratory data analysis (EDA), we provide **data-driven insights** into which film genres and budget strategies maximize ROI (Return on Investment).  

Our recommendations help the company decide **what films to create** and **how to allocate budgets effectively**.  

---

## 👥 Team Members  
- Fatuma  
- Brian  
- Clariss *(Scrum Master)*  
- Lydia  

---

## 🎯 Business Understanding  

### The Problem  
Our company wants to enter the movie industry but lacks domain expertise.  
The challenge: **Which types of films will maximize success at the box office?**  

### Key Business Questions  
1. Which genres deliver the highest ROI?  
2. What budget ranges balance risk and reward?  
3. Do critical ratings strongly influence financial performance?  

---

## 📊 Data Understanding & Analysis  

### Data Sources  
- **Box Office Mojo** – worldwide gross  
- **IMDB** – ratings, metadata (SQLite database)  
- **The Numbers** – budget, revenue data  
- **Rotten Tomatoes** & **TheMovieDB** – supplemental details  

**Sample**: 934 films (2010–2019) with complete budget and revenue data.  

### Metrics & Methods  
- **ROI** = Worldwide Gross ÷ Production Budget  
- Correlation analysis (budget vs. revenue)  
- Comparative analysis across genres  
- Visualizations to support recommendations  

---

## 🔑 Findings & Recommendations  

### 1️⃣ Focus on High-ROI Genres  
- Horror films yield **14.3x ROI** on average.  
- Mystery & Thriller genres also outperform the market.  

➡️ **Action**: Prioritize horror/thriller films for studio launch.  

| Genre   | Avg ROI | Avg Budget | Success Rate |
|---------|---------|------------|--------------|
| Horror  | 14.3x   | $15M       | 68%          |
| Average | 3.7x    | $60M       | 45%          |

---

### 2️⃣ Adopt a Tiered Budget Strategy  
- ROI peaks in the **$20M–$60M budget range**.  
- Avoid competing with $100M+ blockbusters initially.  

➡️ **Action**: Start with mid-range budgets to balance risk and reward.  

| Tier | Budget Range | Strategy |
|------|--------------|----------|
| 1️⃣ Foundation | $10M–$30M | Launch profitable horror/thrillers |
| 2️⃣ Growth     | $30M–$60M | Expand into mystery/action, franchises |
| 3️⃣ Expansion  | $60M–$100M | Compete with major studios |

---

### 3️⃣ Balance Quality vs. Commerce  
- Ratings show weak ROI correlation (**-0.06**).  
- Audience demand matters more than critical acclaim.  

➡️ **Action**: Target audience appeal and proven formulas.  

---

## 📈 Visualizations (to include)  
1. ROI by Genre – Horror dominates profitability  
2. Budget vs. Revenue – Clear sweet spot at mid-range budgets  
3. Ratings vs. ROI – Weak correlation between ratings & ROI  

*(Add visualizations here once saved as images and linked in Markdown)*  

---

## 🛠️ Deliverables  
- 📑 **[Presentation (PDF)](./Data-Driven%20Movie%20Studio%20Strategy%20(1).pdf)** – Business stakeholder presentation  
- 📓 **[Jupyter Notebook](./student%20(1).ipynb)** – Full exploratory data analysis  

---

## ✅ Conclusion  
- Launch with **low- to mid-budget horror/thriller films**  
- Maintain strict **budget control ($20M–$60M)**  
- Focus on **audience demand and proven genres** over critic scores  
- Expect **3–8x ROI** within the first 24 months  

---

## 📂 Repository Structure  
├── student.ipynb # Final Jupyter Notebook
├── Data-Driven Movie Studio Strategy.pdf # Final presentation
├── zippedData/ # Source datasets
├── README.md # Project documentation
└── .gitignore

Copy code
