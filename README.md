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
