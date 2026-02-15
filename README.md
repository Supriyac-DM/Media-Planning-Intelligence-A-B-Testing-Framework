# 📊 Media Planning Intelligence: The "Price of Certainty" Framework

### **Eliminate Underpowered Tests. Engineer Statistical Wins.**

Most A/B tests fail because they are "underpowered" meaning the budget was too small to ever prove a win. This framework moves beyond basic calculators to provide a **Financial Engineering** approach to media testing. It calculates the literal cost and time required to achieve statistical significance before you spend a single dollar.


## 🚀 Key Modules

### **1. The Dynamic "16-Rule" Generator**

Instead of using "magic numbers," this model derives the safety constant () from the Standard Normal Distribution.

* **Confidence ():** Protection against False Positives (Type I Error).
* **Power ():** Protection against False Negatives (Type II Error).
* **Derivation:** Uses `NORM.S.INV` logic to map Z-Scores, ensuring the model scales for high-stakes medical ads (99% confidence) or fast creative tests (80% confidence).

### **2. The Reverse MDE (Reality Check)**

This is a budget-first intelligence tool. It analyzes your **Available Testing Budget** to reveal the "Truth" of your detection ability.

* **The Insight:** If your budget is $5k but your "Possible MDE" is 88%, the model warns you that you are "blind" to small wins.
* **Strategic Shift:** It pushes you to stop testing minor tweaks and start testing radical, high-impact changes.

### **3. Predictive Budget & Timeline Forecaster**

Input your **Target Lift** (e.g., 15%) and the model outputs:

* **Required Clicks:** Total traffic needed per variant.
* **Budget Required:** Total investment based on historical CPC.
* **Days to Significance:** Duration based on historical traffic velocity.

### **1. The Dynamic "16-Rule" Generator**

Instead of using "magic numbers," this model derives the safety constant ($K$) from the Standard Normal Distribution.

* **Confidence ($1-\alpha$):** Protection against False Positives (Type I Error).
* **Power ($1-\beta$):** Protection against False Negatives (Type II Error).
* **Derivation:** Uses `NORM.S.INV` logic to map Z-Scores, ensuring the model scales for high-stakes ads (99% confidence) or fast creative tests (80% confidence).

---

## 🛠️ The Core Methodology

The framework utilizes the standard sample size formula for a two-proportion z-test to ensure statistical power:

$$n = \frac{K \cdot p(1-p)}{(p \cdot \text{MDE})^2}$$

**Where:**
* **$K$**: The calculated statistical constant (Standard 95%/80% is **15.7**).
* **$p$**: Your historical Baseline Conversion Rate.
* **$\text{MDE}$**: Your Minimum Detectable Effect (Relative).

To solve for the **Reverse MDE** (What your budget can afford), we use:

$$\text{Possible MDE} = \frac{\sqrt{\frac{K \cdot p(1-p)}{n}}}{p}$$

## 📈 Strategic Decision Engine

The model includes an automated **Consultant Logic** cell:

* **Result > 20% MDE:** 🚩 *“STOP: Test Big Swings.”* (Your budget is too small for subtle changes).
* **Result < 20% MDE:** ✅ *“GO: Safe for Incremental Tweaks.”*

## 👨‍💻 About

This framework was developed to bridge the gap between **Media Buying** and **Data Science**. It ensures that every test run is mathematically viable and every dollar spent is an investment in certainty.

