# Projects

This section documents my data science projects, research questions, and data stories I create throughout the semesters.

---

## College Football Recruiting and Team Performance

### Research Question
To what extent do higher-ranked recruiting classes predict more wins in college football?

This project analyzes the relationship between college football recruiting rankings and team wins using CollegeFootballData API data from the 2021–2025 seasons.

The analysis explores whether stronger recruiting classes are associated with more successful seasons by comparing recruiting class rankings with total wins for FBS teams.

### Key Findings
- Recruiting rank and wins had a correlation of approximately **-0.286**.
- Because lower rankings represent stronger recruiting classes, stronger recruiting is generally associated with more wins.
- Teams with Top 10 recruiting classes averaged about **10 wins**, while teams ranked 51+ averaged about **6 wins**.
- Recruiting matters, but it does not fully explain team success.

### Project Links
- [View the Project Repository](https://github.com/Natemellenberger/college-football-recruiting-analysis)
- [View the Jupyter Notebook](https://github.com/Natemellenberger/college-football-recruiting-analysis/blob/main/recruiting_analysis.ipynb)

---

## NHL Shot Outcome Prediction

### Research Question
Can the characteristics of an NHL shot predict whether the shot will result in a goal or be saved?

This project uses 2025–2026 NHL shot-level data from MoneyPuck to examine which shot characteristics are associated with scoring.

I trained Logistic Regression and Decision Tree classification models using features such as shot distance, shot angle, shot type, player position, rebound status, and rush status.

### Key Findings
- Goals made up about **10.3%** of the final modeling dataset.
- Shots taken closer to the net and from more central angles were more likely to result in goals.
- Rebound and rush shots had higher goal rates than standard shot attempts.
- The balanced Logistic Regression provided the best overall balance between precision, recall, and F1-score.
- Shot distance and shot angle were among the most influential predictors.

### Project Links
- [View the Full Project](nhl-shot-project.md)
- [View the Project Repository](https://github.com/Natemellenberger/nhl-shot-outcome-prediction)
- [View the Jupyter Notebook](https://github.com/Natemellenberger/nhl-shot-outcome-prediction/blob/main/nhl_shot_prediction.ipynb)