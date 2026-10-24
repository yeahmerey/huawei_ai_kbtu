# Lab 2 — AI Fuzzy Temperature Control

## Overview

This project demonstrates the application of **Fuzzy Logic** to a room temperature control system. The goal is to simulate an intelligent controller that uses fuzzy rules to make decisions based on room temperature.

Unlike traditional systems that use strict thresholds, fuzzy logic works with degrees of membership, allowing the system to make more flexible decisions.

## Objectives

- Understand the basic concepts of fuzzy logic.
- Define fuzzy sets and membership functions.
- Create fuzzy rules for temperature control.
- Simulate a fuzzy temperature controller.
- Analyze the simulation results.

## Technologies Used

- Python
- Jupyter Notebook
- Fuzzy Logic
- `requirements.txt` for Python dependencies

## Project Structure

```text
Lab2_AI_Fuzzy_Temperature/
├── .venv/                  # Virtual environment (not committed to Git)
├── results/                # Simulation results
├── .gitignore              # Git ignore rules
├── requirements.txt        # Python dependencies
├── room_control.ipynb      # Main Jupyter Notebook
└── README.md               # Project documentation
```

## Installation and Setup

### 1. Clone the repository

```bash
git clone <YOUR_REPOSITORY_URL>
cd Lab2_AI_Fuzzy_Temperature
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

### 3. Activate the virtual environment

**Windows PowerShell:**

```powershell
.\.venv\Scripts\Activate.ps1
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Start Jupyter Notebook

```bash
jupyter notebook
```

Open `room_control.ipynb` and run the notebook cells in order.

## How to Run

1. Open `room_control.ipynb`.
2. Select the Python kernel associated with `.venv`.
3. Execute the notebook cells from top to bottom.
4. Observe the fuzzy temperature control simulation.
5. Review the generated outputs and files in the `results/` directory, if applicable.

## Results

The notebook demonstrates the behavior of the fuzzy temperature control system using the selected input parameters and fuzzy rules.

Simulation outputs can be saved in the `results/` directory for further analysis.

## Conclusion

This laboratory project provides practical experience with fuzzy logic and its application to intelligent temperature control. It demonstrates how fuzzy rules can be used to model decision-making in a system with imprecise input values.

## Author

Kaliyev Merey — Artificial Intelligence, Laboratory Work 2.
