# 🎬 Data-Driven Movie Studio Strategy  
**Phase 2 Project – Group 3**  



## 📌 Overview  
This project explores data from the movie industry to guide the launch of a **profitable new movie studio**.  
Our task was to conduct **exploratory data analysis (EDA)** on real-world movie datasets in order to identify which types of films are most successful at the box office and how production budgets influence outcomes.  

The ultimate goal is to provide **actionable, business-focused recommendations** that will help decision-makers understand what films to produce, how much to spend, and what strategies maximize returns on investment.  

We analyzed over **900 films released between 2010 and 2019**, integrating multiple datasets to uncover clear insights about profitability, risk management, and audience behavior.  



## 👥 Team Members  
This was a group project completed by **Group 3** as part of our Data Science Phase 2 deliverable:  
- Fatuma Tari
- Brian Kahiu
- Clariss Wangari *(Scrum Master)*  
- Lyndia Onkundi

The team collaborated using GitHub for version control and branch management. Each member contributed to the analysis, documentation, and presentation.  



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

These questions form the backbone of our analysis and business recommendations.  



## 📊 Data Understanding & Analysis  

### Data Sources  
The datasets were collected from multiple industry-standard sources, including:  
- **Box Office Mojo** – worldwide gross revenues  
- **IMDB** – ratings, metadata, and film attributes (stored in a SQLite database)  
- **The Numbers** – production budget and revenue information  
- **Rotten Tomatoes** and **TheMovieDB** – supplemental information for validation and enrichment  

The **sample includes 934 films from 2010–2019** with complete data on budgets, revenues, and ratings.  

### Metrics & Methods  
To analyze the data, we used the following metrics and techniques:  
- **ROI Calculation** = (Worldwide Gross ÷ Production Budget)  
- **Correlation Analysis** – to examine relationships between budget and revenue, and between ratings and ROI  
- **Genre Comparisons** – to identify categories with the strongest performance  
- **Data Visualizations** – to communicate findings clearly to both technical and non-technical audiences  

Our methodology emphasized **clarity and interpretability** over complexity, ensuring that results could be directly translated into business recommendations.  



## 🔑 Findings & Recommendations  

### 1️⃣ Focus on High-ROI Genres  
- Horror films consistently outperform other genres, with an **average ROI of 14.3x**.  
- Mystery and Thriller genres also show above-average performance compared to the market.  
- These genres typically require **lower production budgets**, yet they achieve strong commercial success.  

 **Recommendation**: Prioritize horror, thriller, and mystery films as the foundation of the new studio’s portfolio.  

| Genre   | Avg ROI | Avg Budget | Success Rate |
|---------|---------|------------|--------------|
| Horror  | 14.3x   | $15M       | 68%          |
| Average | 3.7x    | $60M       | 45%          |

<img width="1190" height="790" alt="image" src="https://github.com/user-attachments/assets/94877f32-8a75-426d-9046-6049d83710e7" />
<img width="1184" height="790" alt="image" src="https://github.com/user-attachments/assets/02549a92-bf76-47f6-a3f6-518eb8cb611f" />


### 2️⃣ Adopt a Tiered Budget Strategy  
- Strong correlation exists between budget and revenue, but **returns diminish after $100M**.  
- The **sweet spot for ROI lies in the $20M–$60M range**, where financial risk is lower but potential revenue remains strong.  

 **Recommendation**: Use a phased budget approach, scaling up only after early successes.  

| Tier | Budget Range | Strategy |
|------|--------------|----------|
| 1️⃣ Foundation | $10M–$30M | Launch profitable horror/thrillers |
| 2️⃣ Growth     | $30M–$60M | Expand into mystery/action, franchises |
| 3️⃣ Expansion  | $60M–$100M | Compete with major studios |

This staged approach allows the studio to **mitigate risk**, establish credibility, and gradually expand into larger markets.

<img width="1184" height="790" alt="image" src="https://github.com/user-attachments/assets/6b57997a-a2f4-4f86-924c-197d8b54066b" />


<img width="1184" height="790" alt="image" src="https://github.com/user-attachments/assets/6f4e5a0d-df95-44d6-adff-0024a541d028" />


### 3️⃣ Balance Quality vs. Commerce  
- Ratings and ROI show a **weak correlation (-0.06)**, indicating that critical acclaim does not guarantee financial success.  
- However, ratings have a **moderate positive effect on revenue (+0.28)**, showing some value in marketing appeal.  

 **Recommendation**: Focus primarily on **audience demand and commercial viability**, while ensuring sufficient quality to attract consistent viewership.  



## 📈 Visualizations (to include)  
The analysis was supported by multiple visualizations. Three key plots are central to the findings:  

1. **ROI by Genre** – Horror dominates profitability  
2. **Budget vs. Revenue** – Clear sweet spot at mid-range budgets  
3. **Ratings vs. ROI** – Weak correlation between critic ratings and profitability  

*(Plots can be embedded here once exported as images from the Jupyter Notebook)*  



## 🛠️ Deliverables  
This project produced three main deliverables:  

- 📑 **[Presentation (PDF)](./Data-Driven%20Movie%20Studio%20Strategy%20(1).pdf)**  
  A non-technical presentation for business stakeholders, highlighting findings and recommendations.  

- 📓 **[Jupyter Notebook](./student%20(1).ipynb)**  
  A technical notebook combining Python code, analysis, and Markdown explanations.  

- 📂 **GitHub Repository**  
  A collaborative version-controlled environment documenting our full workflow.  



## ✅ Conclusion  
Based on our exploratory analysis, we recommend the following strategic path for launching the new studio:  
- Begin with **low- to mid-budget horror/thriller films**, where ROI is highest and financial risk is minimized.  
- Maintain strict **budget control within the $20M–$60M range** to capture strong returns without competing with blockbusters.  
- Focus on **audience preferences and commercial viability** over critic reviews, ensuring a balance of profitability and sustainable growth.  

With this approach, the studio can expect a **3–8x ROI within 18–24 months**, with potential for greater success through sequels, franchises, and diversification.  



## 📂 Repository Structure  
├── student.ipynb # Final Jupyter Notebook (full analysis)
├── Data-Driven Movie Studio Strategy.pdf # Final presentation (slides for stakeholders)
├── zippedData/ # Source datasets used in analysis
├── README.md # Project documentation (this file)
└── .gitignore # Git ignore file for unnecessary/large files
