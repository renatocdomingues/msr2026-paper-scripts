# Replication Package

This repository contains the scripts used in the study:

> **"Bug-Fixing in the Age of AI: Human vs. Agentic Pull Requests"**  
> Submitted to MSR 2026.

---

## 📁 Repository Structure

This repository contains the notebooks used in the data collection and analysis pipeline of the project.

🔹 Data Collection & Processing Notebooks

Step 1 - Get dataset.ipynb
Collects and prepares the initial dataset used in the study.

Step 2 - Get reviewers.ipynb
Extracts and processes reviewer information associated with the PRs.

Step 3 - Get Closure.ipynb
Gathers closure-related information.

Step 4 - Get comments.ipynb
Retrieves and processes comments associated with the PRs.

🔹 Research Question Notebooks

RQ1 - Statistics.ipynb
Performs statistical analysis related to Research Question 1.

RQ2 - Analysis PRs.ipynb
Get pull requests that were selected for manual analysis in Research Question 2. 

Each notebook is designed to be executed sequentially where applicable. Intermediate and final outputs are stored in the corresponding output directories.