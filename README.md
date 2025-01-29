
# 📌 Stock Stress-Testing Project

This project allows users to **stress-test** a selected stock using an **interactive Excel file**.

---

## 📌 Features
- 🧹 **Clean all sheets** → Clears all sheets in the Excel file.
- 🎲 **Stress Testing** → Runs a **Monte Carlo simulation** to predict possible asset values over time.
- ⚠️ **Crisis Scenario** → Simulates a financial crisis where stock prices drop by **40%**.
- 📊 **Risk Metrics** → Displays risk measures such as **VaR** and **Expected Shortfall (ES)**.

---

## 📌 Excel Interface
📌 **Select the stock** you want to analyze in **cell (1,1)**.

### 🔘 **Available Buttons:**
- **[🧹 Clean all sheets]**
- **[🎲 Stress Testing]**
- **[⚠️ Crisis Scenario]**
- **[📊 Risk Metrics]**

---

## 📌 Technical Details
### 1️⃣ **Clean all sheets**
➡️ Clears all content from all Excel sheets.

### 2️⃣ **Monte Carlo Simulation (Stress Testing)**
➡️ **Simulates possible future price paths** for the selected asset.  
➡️ Results are displayed in the **"Monte Carlo Simulations"** sheet.

### 3️⃣ **Crisis Scenario**
➡️ **Applies a -40% drop** to returns.  
➡️ Models a **sharp decline in asset prices** during a financial crisis.

### 4️⃣ **Risk Metrics**
➡️ Displays the following **risk measures**:
   - **📉 VaR (Value at Risk)** → Maximum potential loss at a given confidence level.
   - **📊 Expected Shortfall (CVaR)** → The **average loss beyond the VaR threshold**.

---

## 📌 How to Use This File?
1. **Open the Excel file**.
2. **Select a stock** in **cell (1,1)**.
3. **Click one of the buttons** to run the corresponding simulation.

📌 **Results will be displayed in different Excel sheets**.

---

## 📌 Example Results
### 📊 **Monte Carlo Simulation**
| Period | Simulation 1 | Simulation 2 | Simulation 3 |
|--------|-------------|-------------|-------------|
| 1      | 100.5       | 101.2       | 99.8        |
| 2      | 102.1       | 100.7       | 98.5        |
| ...    | ...         | ...         | ...         |

### ⚠️ **Crisis Scenario (-40%)**
| Period | Original Price | Crisis Price |
|--------|--------------|--------------|
| 1      | 100.5        | 60.3         |
| 2      | 102.1        | 61.3         |

### 📊 **Risk Metrics**
| 🔹 Metric          | 📉 Value |
|-------------------|----------|
| VaR (95%)        | -4.23%   |
| Expected Shortfall | -5.67%   |

---

