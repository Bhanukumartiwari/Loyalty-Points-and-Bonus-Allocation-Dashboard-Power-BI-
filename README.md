# Loyalty-Points-and-Bonus-Allocation-Dashboard-Power-BI-# 🎮 Loyalty Points and ₹50,000 Bonus Distribution Dashboard (Power BI)

## 👤 Developed By:
**Bhanu Kumar Tiwari**  
📍 Badarpur, Delhi – 110044  
📞 +91 7982434496  
✉️ tiwaribhanu09@gmail.com  
🔗 GitHub: [github.com/Bhanukumartiwari](https://github.com/Bhanukumartiwari)

---

## 📌 Project Title:
**Loyalty Points & ₹50,000 Bonus Allocation System for an Online Gaming Platform**

---

## 📝 Overview

This Power BI dashboard was developed for a real-money online gaming company to track player engagement, calculate loyalty points based on in-game activity, and fairly distribute a ₹50,000 monthly bonus among the top 50 most loyal users.

The system divides each day into two slots and ranks players based on custom logic using DAX formulas.

---

## 🎯 Business Goals

- Track daily and monthly user engagement
- Reward top 50 loyal players every month
- Visualize slot-wise activity (S1 = 12AM–12PM, S2 = 12PM–12AM)
- Enable transparent and fair bonus distribution

---

## 📊 Key Features

- ✅ Slot-wise loyalty point table (S1 & S2)
- ✅ Month-wise leaderboard by loyalty points & games played
- ✅ ₹50,000 bonus distribution logic by player rank
- ✅ Tiered bonus breakdown
- ✅ KPIs: Avg Deposit Amount, Avg Games Played
- ✅ Interactive filters: Date, Slot

---

## 🧠 DAX Logic

### 🎯 Loyalty Points Calculation:

```DAX
Loyalty Points = 
    0.01 * [Deposit_Amount] + 
    0.005 * [Withdrawal_Amount] +
    0.001 * MAX([#Deposits] - [#Withdrawals], 0) + 
    0.2 * [Games_Played]
# 🎮 Loyalty Points and ₹50,000 Bonus Distribution Dashboard (Power BI)

## 👤 Developed By:
**Bhanu Kumar Tiwari**  
📍 Badarpur, Delhi – 110044  
📞 +91 7982434496  
✉️ tiwaribhanu09@gmail.com  
🔗 GitHub: [github.com/Bhanukumartiwari](https://github.com/Bhanukumartiwari)

---

## 📌 Project Title:
**Loyalty Points & ₹50,000 Bonus Allocation System for an Online Gaming Platform**

---

## 📝 Overview

This Power BI dashboard was developed for a real-money online gaming company to track player engagement, calculate loyalty points based on in-game activity, and fairly distribute a ₹50,000 monthly bonus among the top 50 most loyal users.

The system divides each day into two slots and ranks players based on custom logic using DAX formulas.

---

## 🎯 Business Goals

- Track daily and monthly user engagement
- Reward top 50 loyal players every month
- Visualize slot-wise activity (S1 = 12AM–12PM, S2 = 12PM–12AM)
- Enable transparent and fair bonus distribution

---

## 📊 Key Features

- ✅ Slot-wise loyalty point table (S1 & S2)
- ✅ Month-wise leaderboard by loyalty points & games played
- ✅ ₹50,000 bonus distribution logic by player rank
- ✅ Tiered bonus breakdown
- ✅ KPIs: Avg Deposit Amount, Avg Games Played
- ✅ Interactive filters: Date, Slot

---

## 🧠 DAX Logic

### 🎯 Loyalty Points Calculation:

```DAX
Loyalty Points = 
    0.01 * [Deposit_Amount] + 
    0.005 * [Withdrawal_Amount] +
    0.001 * MAX([#Deposits] - [#Withdrawals], 0) + 
    0.2 * [Games_Played]
```

---

## 💰 Bonus Distribution: ₹50,000 Pool

| Rank Range | Players | Bonus per Player | Total |
|------------|---------|------------------|-------|
| Rank 1     | 1       | ₹5,000           | ₹5,000 |
| Ranks 2–5  | 4       | ₹3,000           | ₹12,000 |
| Ranks 6–10 | 5       | ₹2,000           | ₹10,000 |
| Ranks 11–25| 15      | ₹1,000           | ₹15,000 |
| Ranks 26–50| 25      | ₹320             | ₹8,000 |
| **Total**  | **50**  | --               | **₹50,000** |

---

## 🧰 Tools & Tech Stack

- Power BI Desktop
- Power Query
- DAX
- Excel/CSV Data Source

---

## 📸 Dashboard Snapshots

>https://github.com/Bhanukumartiwari/Loyalty-Points-and-Bonus-Allocation-Dashboard-Power-BI-/blob/main/Copy%20of%20Analytics%20Position%20Case%20Study.xlsx _Screenshots from the Power BI dashboard included in `/screenshots/` folder_:

(https://github.com/Bhanukumartiwari/Loyalty-Points-and-Bonus-Allocation-Dashboard-Power-BI-/blob/main/Screenshot%202025-07-08%20213020.png)
- `monthly_leaderboard.png`
- `bonus_distribution.png`
- `avg_deposit_kpis.png`

---

## 📁 Project Structure

```
📦 loyalty-points-powerbi/
 ┣ 📁 screenshots/
 ┃ ┣─ slotwise_loyalty_points.png
 ┃ ┣─ monthly_leaderboard.png
 ┃ ┣─ bonus_distribution.png
 ┃ ┗─ avg_deposit_kpis.png
 ┣ 📁 data/
 ┃ ┗─ player_transactions_october.csv
 ┣ 📜 Loyalty_Points.pbix
 ┣ 📜 README.md
 ┗ 📜 project_details.md
```

---

## 🚀 Outcome

- Increased user engagement through loyalty incentives
- Transparent reward logic for players
- Flexible, slot-based daily tracking system
- Improved insights for future marketing campaigns

---

## 💡 Future Improvements

- Include **win/loss ratio** or **average session time**
- Add fraud prevention logic
- Introduce tiered user segments (Gold/Silver/Bronze)
- Use Power Automate for auto-reporting emails

---

## 📬 Contact

For any queries, feel free to reach out:

**Bhanu Kumar Tiwari**  
📧 tiwaribhanu09@gmail.com  
📱 +91 7982434496  
🔗 [GitHub Profile](https://github.com/Bhanukumartiwari)

---

⭐ _If you liked this project, don’t forget to star the repo!_

