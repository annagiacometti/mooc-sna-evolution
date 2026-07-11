# Comparative Social Network Analysis (SNA) of MOOC-Ed Dynamics

This repository contains the replication code, data structures, and the final research paper evaluating the social dynamics and structural evolutions between two consecutive editions of the MOOC-Ed course *Digital Learning and Teaching* (**DLT1** and **DLT2**).

## 📌 Research Question
Given the evolution of the MOOC-Ed DLT course design between DLT1 and DLT2, to what extent do the participants' profile characteristics (**Professional Role**, **Experience**, and **Gender**) associate with their network dynamics (**Participation** and **Centrality**), and how does this association differ between the two editions?

## 📂 Project Structure
The repository is organized as follows:
* `/notebooks`: Contains the Google Colab Python notebook (`ENG_Giacometti_Analisi_SNA_MOOC.ipynb`) covering the entire computational pipeline:
  * Exploratory Data Analysis (EDA)
  * Network Construction and Centrality Metric Calculations
  * Ordinary Least Squares (OLS) Regressions
  * Statistical Visualizations
* `/paper`: Contains the complete research paper (`Giacometti_2026_SNA_MOOC.pdf`) detailing the theoretical background, methodology, structural findings, and socio-educational implications.

## 🛠️ Tech Stack & Libraries
The analysis was performed using **Python 3** and the following core data science libraries:
* **NetworkX** – Network creation, topology analysis, and centrality metrics.
* **Statsmodels** – OLS Regression modeling and statistical inference.
* **Pandas & NumPy** – Data ingestion, cleaning, and structural alignment.
* **Matplotlib & Seaborn** – Graph visualizations and regression plots.

## 🚀 How to Run the Analysis
1. Open the notebook located in the `/notebooks` folder.
2. Click on the **"Open in Colab"** badge (or upload the `.ipynb` directly to Google Colab).
3. Ensure the initial cells properly pull the four essential source datasets (Edgelists and Nodelists) hosted on Google Drive.
4. Run all cells sequentially (`Runtime > Run all`) to reproduce the statistical summaries, regressions, and plots.
