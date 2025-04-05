# 💸 Desktop Expense Tracker

A clean and functional **desktop application** to help you **track your income and expenses** with ease. Built using **PyQt5**, the app features a modern interface with detailed financial analysis using charts and graphs.

---

## 🚀 Features

- ✅ Add, View, and Delete Income and Expense Entries  
- 📅 Track Date, Category, Amount, and Description  
- 📊 Pie Charts for Income & Expense Distribution  
- 📈 Line Chart showing Income vs Expense Trends  
- 🌗 Dark Themed UI for a sleek modern look  
- 🔙 Navigation-friendly with Back-to-Main functionality  

---

## 🖼️ Screenshots

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/67dfe9e7-c458-47fc-842d-33abb64c0dac" width="400"/></td>
    <td><img src="https://github.com/user-attachments/assets/00550b00-8bf1-44f7-8994-7cab2848cf58" width="400"/></td>
  </tr>
  <tr>
    <td align="center">Dashboard Page</td>
    <td align="center">Analysis Page</td>
  </tr>
</table>

---

## 🧠 Application Structure

### 1. `MainWindow`

- Displays total income, total expense, and current balance.
- Includes:
  - **Table view** for transactions
  - **Buttons**: Add Income, Add Expense, View Analysis

### 2. `AddIncomePage` / `AddExpensePage`

- Forms to input:
  - Amount
  - Category
  - Date
  - Description
- Submits and updates main dashboard.

### 3. `AnalysisPage`

- Uses **PyQt5.QtChart** for visualizations:
  - Income Pie Chart
  - Expense Pie Chart
  - Line Chart for trends
- Styled **Back to Main** button for easy navigation.

```python
back_button.setStyleSheet("""
    QPushButton {
        background-color: black;
        color: white;
        border: none;
        padding: 10px;
        margin: 5px;
    }
    QPushButton:hover {
        background-color: #333333;
    }
""")
