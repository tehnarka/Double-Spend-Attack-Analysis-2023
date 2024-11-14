# Double-Spend Attack Analysis 2023

**Description:**
This project investigates the characteristics and thresholds of double-spend attacks in blockchain systems. It includes calculations for attacker hash power thresholds, probabilities of attacker chain dominance, and the minimum confirmation blocks required to secure transactions against double-spend attacks. Visualizations and theoretical explanations support the analysis.

---

## Objectives

1. **Threshold Analysis:**
   - Calculate the minimum share of malicious miners (`pst`) required to guarantee a successful double-spend attack.
   
2. **Probability Dependencies:**
   - Analyze the probability of a malicious chain overtaking the honest chain as a function of the initial block difference (`n`).
   - Provide a table and graph showing this dependency.

3. **Confirmation Blocks Analysis:**
   - Determine the minimum number of confirmation blocks needed to ensure a double-spend attack probability of at most `10^(-3)`.
   - Analyze results for varying synchronization times (`DH`) and attacker hash rates (`pM = 0.15, 0.25, 0.4`).
   - Provide corresponding tables and graphs.

---

## Features

1. **Mathematical Modeling:**
   - Derive and implement formulas for the attack threshold and probabilities.

2. **Visualization:**
   - Graphs illustrating the relationships between block confirmations, synchronization times, and attack probabilities.

3. **Performance Analysis:**
   - Evaluate blockchain security under varying network conditions and attacker strengths.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Double-Spend-Attack-Analysis-2023.git
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Python scripts or Jupyter Notebook:
   ```bash
   python main.py
   ```

---

## Usage

1. Calculate attack thresholds:
   ```python
   calculate_threshold(alpha_H, alpha_M)
   ```
2. Analyze probability dependencies:
   ```python
   plot_probability_vs_n(alpha_H, alpha_M, DH)
   ```
3. Compute minimum confirmation blocks:
   ```python
   calculate_min_confirmations(alpha, DH, pM)
   ```

---

## Results

- **Threshold Analysis:** Identified the minimum malicious miner share (`pst`) for successful attacks.
- **Probability Analysis:** Quantified the likelihood of chain dominance based on initial block difference.
- **Confirmation Blocks:** Established the number of blocks needed for varying synchronization times and hash rates.

---

## Author

- **Name:** Olha Nemkovych and Ivan Marynin
- **Group:** FI-94
