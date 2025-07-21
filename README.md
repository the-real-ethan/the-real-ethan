# Data Science Portfolio

Welcome to my project portfolio! Below are a few data-driven projects I’ve worked on that apply machine learning and statistical analysis to real-world problems — from ecosystem health to basketball performance. Each project emphasizes thoughtful modeling, rigorous evaluation, and practical impact.

---

## Predicting Frog Presence Using Climate Data  
**Tags**: `machine-learning`, `classification`, `random-forest`, `climate-data`, `biodiversity`

### Overview
This project explores how machine learning can be used to predict frog presence in Southeastern Australia based on climate data from 2017–2019. Frogs are critical bioindicators of ecosystem health, and their presence or absence can reveal deeper patterns in biodiversity.

### Tools & Methods
- **Data Sources**: TerraClimate climate datasets + frog audio monitoring data
- **Features**: Temperature, precipitation, drought index, vapor pressure, runoff, etc.
- **Models Tested**: Logistic Regression, SVM, Convolutional Neural Network (CNN), and Random Forest
- **Best Model**: Random Forest — F1 Score: **0.8387**, Precision: 0.7469, Recall: 0.9563

### Key Learnings
- Implemented a pipeline with Min-Max scaling and model encapsulation for streamlined processing
- Balanced interpretability and performance with Random Forest
- Generated actionable insights for biodiversity monitoring and sustainable planning

🔗 [View Full Notebook](./Frog_Presence_Model.ipynb)

---

## Testing the 'Hot Hand' Theory in the NBA  
**Tags**: `nba-api`, `data-visualization`, `hypothesis-testing`, `sports-analytics`, `python`

### Goal
This project uses real NBA game data to test the "Hot Hand" hypothesis — the idea that players are more likely to score after a successful shot. Using Python and the NBA API, I analyzed shot patterns, calculated conditional probabilities, and used statistical testing to see whether this phenomenon actually exists.

### Methods
- Accessed real-time and historical shot data using the NBA Stats API
- Calculated hit/miss streaks to test scoring probabilities
- Applied statistical testing to compare random vs. streak-based performance

### Outcome
- Visualized whether nba players showed statistically significant evidence of streak-based scoring
- Discovered that as a whole, nba players did not exhibit hot-hand effects
- Emphasized the importance of sample size and random chance in interpreting sports data

🔗 [View Full Notebook](./Does_the_Hot-Hand_Exist.ipynb)

---

## Predicting NBA Game Outcomes with Injury-Adjusted Probabilities  
**Tags**: `logistic-regression`, `nba-api`, `injury-analysis`, `calibration`, `brier-score`, `sports-analytics`

### Overview
This project models the probability of an NBA team winning a game based on team ratings, rest days, and injury-related player absences. I focused on evaluating the impact of injuries using two distinct approaches and assessing model calibration.

### Methods
- Used the `nba_api` to generate a dataset of game-level features and player-level availability
- Engineered injury metrics using two approaches:
  - **25-Minute Rule**: Tracks minutes lost for players who recently averaged ≥25 minutes
  - **Usage × Minutes**: Tracks all minutes missed weighted by player usage rate
- Fit logistic regression models and evaluated with:
  - **Brier Score** for probabilistic accuracy
  - **Calibration Curves** for alignment between predicted probabilities and observed outcomes
  - Coefficient significance testing for interpretation

### Outcome
- The **25-Minute Rule model** outperformed the usage-weighted approach in both significance and interpretability
- Key findings:
  - Injury to high-minute players significantly lowers win probability
  - Possession and usage-weighted injury features were surprisingly insignificant
  - Home advantage and team ratings remain strong predictors
- Documented areas for future improvement: injury severity weighting, non-linear modeling, and adjustments for end-of-season anomalies

🔗 [View Full Notebook](./NBA_Game_Prediction.ipynb)
## 📌 More Info
Feel free to explore each project notebook. If you'd like to collaborate or have questions, reach out!

📫 **Contact**: [jem200008@utdallas.edu]


