## 🏀 NBA Spread & Total Prediction (2024–25 Season)

---

### 🎯 Goal  
To build a predictive model capable of forecasting **spreads** (winning margin) and **totals** (combined score) for ~150 NBA games during the 2024–25 season.

---

### 💡 Hypothesis  
Accurate prediction of spreads and totals is achievable using cumulative performance metrics and models trained exclusively on **past data**, simulating real-world betting scenarios.

---

### 📊 Data  
- NBA game results and team/player statistics from the 2024–25 season  
- Player-level performance (including shooting percentages and minutes played)  
- Historical data formatted to only include information available prior to each game  

---

### ⚙️ Methods  
- Models tested: `XGBoost`, `Lasso Regression`, and `Linear Models`
- Created new input features such as:
  - `AvgTSMins`: Team’s **average true shooting percentage**, weighted by each player’s **minutes played** in the previous game  
- Used **cumulative means** for variables like shooting %, rebounds, etc. to reflect rolling form 

---

### 💸 Outcome  
- All models performed **reasonably well**, with decent predictive strength  
- A friend's betting trials based on my predictions yielded a profit of **over $50** on spreads and totals
- The custom AvgTSMins variable was the strongest predictor of any one input vairable

&nbsp;

<img src="Model%20Success/Bet%20Slip.jpg" width="30%"> 

&nbsp;

<img src="Model%20Success/Raptors%20vs%20Magic%20Prediction.png" width="30%">

&nbsp;

<img src="Model%20Success/Raptors%20vs%20Magic%20Score.png" width="30%">
---

