**Data-Driven Movie Studio Strategy**

Phase 2 Project – Group 3
Team Members

Fatuma Tari

Brian Kahiu

Clariss Wangari (Scrum Master)

Lyndia Onkundi

**Overview**

This project explores movie industry data to help our company launch a profitable new movie studio. Using exploratory data analysis (EDA), we provide data-driven insights into which film genres and budget strategies maximize ROI (Return on Investment).

Our goal is to guide business stakeholders in making informed decisions on what types of films to produce and how to allocate budgets effectively.


**Business Understanding**
The Problem

Our company wants to enter the movie industry but lacks domain expertise. The challenge: Which films should we produce to maximize success at the box office?

Key Business Questions

Which genres deliver the highest ROI?

What budget ranges balance risk and reward?

Do critical ratings strongly influence financial performance?

**Data Understanding & Analysis**
Data Sources

Box Office Mojo – worldwide gross

IMDB – ratings, metadata (SQLite database)

The Numbers – budget, revenue data

Rotten Tomatoes & TheMovieDB – supplemental details

Sample: 934 films (2010–2019) with complete budget and revenue data.

Metrics & Methods

ROI = Worldwide Gross ÷ Production Budget

Correlation analysis (budget vs. revenue)

Comparative analysis across genres

Visualizations to support recommendations

**Findings & Recommendations**
1. Focus on High-ROI Genres

Horror films yield 14.3x ROI on average.

Mystery & Thriller genres also outperform the market.
➡️ Action: Prioritize horror/thriller films for studio launch.

2. Adopt a Tiered Budget Strategy

ROI peaks in the $20M–$60M budget range.

Avoid competing with $100M+ blockbusters initially.
➡️ Action: Start with mid-range budgets to balance risk and reward.

3. Balance Quality vs. Commerce

Ratings have weak ROI correlation (-0.06).

Audience demand matters more than critical acclaim.
➡️ Action: Target audience appeal and proven formulas.

**Visualizations**

ROI by Genre – Horror dominates profitability

Budget vs. Revenue – clear sweet spot at mid-range budgets

Ratings vs. ROI – weak correlation between critical score and financial return

**Deliverables**

Presentation (PDF)
 – Non-technical business stakeholder presentation

Jupyter Notebook
 – Full EDA and visualizations

**Conclusion**

Launch with low- to mid-budget horror/thriller films

Maintain strict budget control ($20M–$60M)

Focus on audience demand and proven genres over critical scores

Expect 3–8x ROI within the first 24 months

**Repository Structure**
├── student.ipynb                 # Final Jupyter Notebook  
├── Data-Driven Movie Studio Strategy.pdf   # Final presentation  
├── zippedData/                   # Source datasets  
├── README.md                     # Project documentation  
└── .gitignore  
