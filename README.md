# 🧠 Data Science Portfolio

Welcome to my project portfolio! Below are a few data-driven projects I’ve worked on that apply machine learning and statistical analysis to real-world problems — from ecosystem health to basketball performance. Each project emphasizes thoughtful modeling, rigorous evaluation, and practical impact.

---

## 🐸 Predicting Frog Presence Using Climate Data  
**Tags**: `machine-learning`, `classification`, `random-forest`, `climate-data`, `biodiversity`

### 🌍 Overview
This project explores how machine learning can be used to predict frog presence in Southeastern Australia based on climate data from 2015–2019. Frogs are critical bioindicators of ecosystem health, and their presence or absence can reveal deeper patterns in biodiversity.

### 🛠 Tools & Methods
- **Data Sources**: TerraClimate climate datasets + frog audio monitoring data
- **Features**: Temperature, precipitation, drought index, vapor pressure, runoff, etc.
- **Models Tested**: Logistic Regression, SVM, Convolutional Neural Network (CNN), and Random Forest
- **Best Model**: Random Forest — F1 Score: **0.8387**, Precision: 0.7469, Recall: 0.9563

### 📈 Key Learnings
- Used Recursive Feature Elimination (RFE) to reduce overfitting and improve model performance
- Balanced interpretability and performance with Random Forest
- Generated actionable insights for biodiversity monitoring and sustainable planning

🔗 [View Full Notebook](./frog_presence_prediction.ipynb)

---

## 🏀 Testing the 'Hot Hand' Theory in the NBA  
**Tags**: `nba-api`, `data-visualization`, `hypothesis-testing`, `sports-analytics`, `python`

### 🎯 Goal
This project uses real NBA game data to test the "Hot Hand" hypothesis — the idea that players are more likely to score after a successful shot. Using Python and the NBA API, I analyzed shot patterns, calculated conditional probabilities, and used statistical testing to see whether this phenomenon actually exists.

### 🧪 Methods
- Accessed real-time and historical shot data using the NBA Stats API
- Calculated hit/miss streaks to test scoring probabilities
- Applied statistical testing to compare random vs. streak-based performance

### 📊 Outcome
- Visualized whether nba players showed statistically significant evidence of streak-based scoring
- Discovered that as a whole, nba players did not exhibit hot-hand effects
- Emphasized the importance of sample size and random chance in interpreting sports data

🔗 [View Full Notebook](./Does_the_Hot-Hand_Exist.ipynb)
## 📌 More Info
Feel free to explore each project notebook. If you'd like to collaborate or have questions, reach out!

📫 **Contact**: [jem200008@utdallas.edu]


