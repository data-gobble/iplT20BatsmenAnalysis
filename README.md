# IPL Batsmen Performance Analysis (2008-2025) 🏏

## Description

This project performs an analysis of Indian Premier League (IPL) batsmen statistics from the 2008 to 2025 seasons. The goal is to uncover insights into player performance, identify top performers based on various metrics, relationship between key batting metrics and build a simple regression model to predict the total runs a player might score.

---

## Dataset

The dataset used in this analysis contains key statistical career metrics for every batsman who has played in the IPL between 2008 and 2025.

* **Source:** The data has been extracted from ESPN Statsguru: https://stats.espncricinfo.com/ci/engine/stats/index.html
* **Key Columns:** `Player`, `Runs`, `Average`, `Strike Rate`, `Balls Faced`, `Innings`, `4s`, `6s`, `Highest_Score`, etc.

---

## Analysis & Key Insights

This project explores the following questions and insights:

1.  **All-Time Run Scorers:** Who are the top 10 leading run-scorers in the history of the IPL?
2.  **Top Individual Scores:** Who are the top 10 batsmen with the highest individual scores in a single innings?
3.  **Elite Strike Rates:** Who are the most explosive scorers (highest strike rate) among players with at least 1000 career runs?
4.  **Top Averages:** Who are the most consistent run-scorers (highest average) among players with at least 1000 career runs?
5. **Boundary Dominance:** Which batsmen score the highest percentage of their runs from boundaries (4s and 6s)?
6.  **Strike Rate vs. Average:** Visualizing the relationship between scoring rate and consistency for all batsmen.
7. **Average vs Boundary Percentage:** Visualizing the relationship between consistency and boundary dominance for all batsmen.
8.  **Maximum Six-Hitters:** Who has hit the most sixes among players with 1000+ runs?
9.  **Correlation Analysis:** How do different batting stats like strike rate, average, and boundary-hitting correlate with each other? 
10.  **Predictive Modeling:** A linear regression model was built to predict a player's total career runs based on features like balls faced, innings played, and boundaries hit.

---

## Technologies & Libraries Used 💻

* **Python**
* **Pandas:** For data manipulation and analysis.
* **Matplotlib & Seaborn:** For data visualization and plotting.
* **Scikit-learn:** For building the linear regression model.
* **Jupyter Notebook:** As the development environment.

---

## Setup & Installation

To run this project on your local machine, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/data-gobble/iplT20BatsmenAnalysis.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd iplT20BatsmenAnalysis
    ```
3.  **Install the required libraries:**
    ```bash
    pip install -r requirements.txt
    ```


4.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```

---

## How to Use

Open the `iplbat.ipynb` notebook and run the cells sequentially to see the step-by-step data cleaning, analysis, visualization, and modeling process.

---
