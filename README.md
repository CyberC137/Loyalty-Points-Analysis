
#  Loyalty Points Analysis – Analytics Case Study

This repository contains a full project for analyzing loyalty points as part of a business case study. It simulates transaction and gameplay data for a fictional gaming platform and demonstrates how to:

- Compute player loyalty points using deposits, withdrawals, and games played
- Analyze slot-based activity on specific dates
- Rank players based on activity
- Allocate bonus rewards fairly
- Critique and improve the loyalty scoring formula

---

##  Contents

- `loyalty_points_analysis.ipynb` – Jupyter Notebook with the full analytical workflow
- `deposits_october.csv` – Simulated deposit transactions for October 2023
- `withdrawals_october.csv` – Simulated withdrawal transactions
- `games_october.csv` – Simulated game activity logs

---

##  Loyalty Formula

```
Loyalty Points = 
    0.01 * Total Deposit Amount +
    0.005 * Total Withdrawal Amount +
    0.001 * max(#Deposits − #Withdrawals, 0) +
    0.2 * #Games Played
```

---

##  Objectives

1. Compute loyalty points for players in October
2. Analyze activity in four specific date/slots
3. Rank users by engagement
4. Design a fair bonus distribution for top 50 users
5. Critically evaluate and suggest improvements to the loyalty formula

---

##  How to Use

1. Clone this repository or download the files
2. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook loyalty_points_analysis.ipynb
   ```
3. Run the notebook cells sequentially
4. Review outputs, charts, and bonus calculations

---

##  Dependencies

- Python 3.7+
- pandas
- numpy
- matplotlib (optional, for visualizations)

Install with:

```bash
pip install pandas numpy matplotlib
```

---

##  Notes

- This project uses randomly generated (dummy) data for demonstration purposes.
- Suitable for portfolio use, analytics interviews, or SQL/pandas practice.

---

##  Disclaimer

This project is for demonstration and educational use only. Use responsibly and do not deploy without proper testing.

---


© 2025 by CyberC137
