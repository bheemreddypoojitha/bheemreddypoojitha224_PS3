# ⚖️ BALANCE ZERO - Analytical Decision Engine
**Problem Statement 3 | Track 1: Literature-Based Formula Optimization**

> **Team:** bheemreddypoojitha224 / Bheemreddy Poojitha  
> **Faculty Mentor:** Dr. Y. Krishna Bhargavi

---

## 📖 1. Overview
**BalanceZero** is a physics-informed computational engine designed to optimize **Mass Balance (MB)** calculations for forced degradation studies.

It utilizes **Monte Carlo simulation (n=10,000)** to stress-test standard formulas against assay noise and volatility. The system implements the **"Adaptive Mass Balance Score (AMBS)"** logic gate to automatically select the most scientifically accurate formula for any given degradation profile.

---

## 🚀 2. Key Features

### ✅ Automatic Verification
Self-checks against the **NEST Novartis Problem Statement values (11.3% Deficiency)** before running to ensure mathematical accuracy.

### 🧪 Synthetic Data Generation
Creates **10,000 realistic clinical scenarios** (varying purity, stress, and volatility) to validate the logic against edge cases.

### 📊 Comprehensive Reporting
The project generates a full suite of deliverables:
* **Interactive UI Dashboard** (HTML)
* **Recommendation Matrix** (Strategic Decision Framework)
* **Comparative Analysis Report**
* **Scientific Figures** (Scatter plots, Heatmaps, Sensitivity Curves)

---

## 📂 3. Folder Contents

```text
📦 bheemreddypoojitha224_Novartis_PS3
 ┣ 📂 01_Code_Base
 ┃ ┣ 📜 BalanceZero_Engine.py       # The master logic script
 ┃ ┣ 📜 requirements.txt            # List of dependencies
 ┃ ┗ 📜 README.md                   # This file
 ┃
 ┣ 📂 02_Reports
 ┃ ┣ 📄 Whitepaper_...pdf           # Detailed Scientific Report
 ┃ ┣ 📄 Presentation_...pdf         # Summary Deck (Round 2)
 ┃ ┣ 📄 Recommendation_matrix.pdf   # Strategic Decision Matrix
 ┃ ┗ 📄 analysis_report.pdf         # Comparative Analysis
 ┃
 ┗ 📂 03_Results
   ┣ 📂 Figures                     # Scientific plots (Scatter, Heatmap, Neon Curve)
   ┣ 📄 BalanceZero_Dashboard.html  # Interactive Dark Mode UI
   ┣ 📄 Simulation_Dataset.csv      # Evidence data (10,000 runs)
   ┗ 📄 Validation_Log.txt          # Verification proof (11.3% match)

```

---

## ⚙️ 4. How to Run the Code

### **Prerequisites**

* Python 3.8 or higher
* Libraries listed in `requirements.txt`

### **Step 1: Install Dependencies**

Open your terminal in the `01_Code_Base` folder and run:

```bash
pip install -r requirements.txt

```

### **Step 2: Execute the Engine**

Run the python script to start the simulation:

```bash
python BalanceZero_Engine.py

```

### **Step 3: View Results**

The engine will verify the math and populate the `03_Results` folder. Open **`BalanceZero_Dashboard.html`** in your browser to view the interactive results.

---

## 🔍 5. Verification Logic

The engine includes a **hard-coded Integrity Check module**. Upon launch, it inputs the specific hypothetical values from the Novartis Problem Statement:

* **Initial API:** `98.0%`
* **Stressed API:** `82.5%`

It validates that the **Calculated Deficiency (AMBD)** matches exactly **11.3%**. This ensures the computational model aligns perfectly with the challenge prompt before running the larger simulation.

```

```

