=========================================================================
PROJECT: BALANCE ZERO - ANALYTICAL DECISION ENGINE
Problem Statement 3 | Track 1
Team/Author: bheemreddypoojitha224 / Bheemreddy Poojitha
Faculty Mentor: Dr. Y. Krishna Bhargavi
=========================================================================

1. OVERVIEW

---

BalanceZero is a physics-informed computational engine designed to
optimize Mass Balance (MB) calculations for forced degradation studies.

It utilizes Monte Carlo simulation (n=10,000) to stress-test standard
formulas against assay noise and volatility. The system implements the
"Adaptive Mass Balance Score (AMBS)" logic gate to automatically select
the most scientifically accurate formula for any given degradation profile.

2. KEY FEATURES

---

[+] AUTOMATIC VERIFICATION
Self-checks against the NEST Novartis Problem Statement values (11.3%
Deficiency) before running to ensure accuracy.

[+] SYNTHETIC DATA GENERATION
Creates 10,000 realistic clinical scenarios (varying purity, stress,
and volatility) to validate the logic.

[+] COMPREHENSIVE REPORTING
The project includes a full suite of deliverables: - Interactive UI Dashboard - Recommendation Matrix - Comparative Analysis Report - Scientific Figures (Scatter plots, Heatmaps, Sensitivity Curves)

3. FOLDER CONTENTS

---

> 01_Code_Base/
> |-- BalanceZero_Engine.py (The master logic script)
> |-- requirements.txt (List of required Python libraries)
> |-- README.txt (This file)

> 02_Reports/
> |-- Whitepaper_bheemreddypoojitha224_PS3.pdf (Detailed Scientific Report)
> |-- Presentation_bheemreddypoojitha224_PS3_Round2.pdf (Summary Deck)
> |-- Recommendation_matrix.pdf (Strategic Decision Matrix)
> |-- analysis_report.pdf (Detailed Comparative Analysis)

> 03_Results/
> |-- Simulation_Dataset.csv (Evidence data of 10,000 runs)
> |-- Validation_Log.txt (Verification proof)
> |-- BalanceZero_Dashboard.html (UI Output)
> |-- Figures/ (Scientific plots folder)

4. HOW TO RUN THE CODE

Prerequisites:
Python 3.8 or higher
Libraries listed in requirements.txt

---

STEP 1: Install Dependencies
Open a terminal/command prompt in the "01_Code_Base" folder and run:
pip install -r requirements.txt

STEP 2: Execute the Engine
Run the python script:
python BalanceZero_Engine.py

STEP 3: View Results
The code will verify the 11.3% deficiency match and populate the
"03_Results" folder with the datasets, HTML reports, and figures.

5. VERIFICATION LOGIC

---

The engine includes a hard-coded Integrity Check module. Upon launch, it
inputs the specific values from the Problem Statement:

- Initial API: 98.0%
- Stressed API: 82.5%

It then confirms the calculated Deficiency (AMBD) is 11.3%. This ensures
mathematical alignment with the challenge prompt.
