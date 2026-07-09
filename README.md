# 💊 Pharma-Tech: Computational Pharmacy Simulators

Welcome to my repository exploring the intersection of pharmacy and data science! As a pharmacy graduate learning to code, I've built these Python tools using **NumPy** to solve real-world pharmaceutical and computational challenges.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sanchita207-tech/Numpycodes/blob/main/numpycodes.ipynb)

---

## 🚀 Projects Included

### 1️⃣ Pharmacokinetic (PK) Drug Delivery Simulator
This script models drug behavior inside a biological system over a 24-hour timeline (sampling data points every 6 minutes).
* **Key Features:** * Simulates first-order drug elimination from the bloodstream using exponential decay.
  * Tracks drug accumulation in target tissue matrices over time.
  * Automatically calculates and extracts the drug's exact elimination half-life ($t_{1/2}$).

### 2️⃣ Pharmaceutical Inventory & Loss Calculator
A business-intelligence tool designed for batch formulation and supply chain quality control.
* **Key Features:**
  * Models chemical degradation rates of a batch formulation over a 30-day period.
  * Automated "Expiry Index" logic triggers a warning the exact day product potency drops below the critical 80% industry threshold.
  * Dynamically calculates total financial loss based on unsold inventory past the expiration day.

---

## 🛠️ Tech Stack & Concepts Used
* **Language:** Python 🐍
* **Libraries:** NumPy (Vectorized arrays, exponential decay modeling, dynamic indexing via `np.where()`)
* **Domains:** Biopharmaceutics, Pharmacokinetics, Pharmaceutical Management & Quality Assurance.

Feel free to click the **Open in Colab** badge above to run the code interactively!
