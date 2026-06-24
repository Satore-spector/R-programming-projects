# R-programming-projects

Welcome to my R Programming repository! This is a curated collection of basic to advanced R scripts, projects, and practices that I have picked up as a self-taught programmer through various online resources.

### 🤠 What Sets This Repo Apart
Unlike standard syntax-drilling repositories, my goal here is to bridge the gap between theory and practice. **Every section aims to utilize real-world datasets** to demonstrate how R is actually applied in data analytics, statistics, and machine learning.

---

## 🗒️ Repository Structure

The repository is organized logically by topic, advancing from fundamental data manipulation to complex statistical modeling.

### 1. Basic Data Reading and Transformation (Base R)
* **Reading, Cleaning, and Transforming Data:** Core data manipulation techniques using standard built-in R functions.
* **Generating Data:** Simulating datasets using Base R's random generation tools.

### 2. Basic Data Reading and Transformation (Tidyverse)
* **Reading, Cleaning, and Transforming Data:** Leveraging `dplyr`, `tidyr`, and `readr` for modern, readable data pipelines.
* **Generating Data (with Tidymodels):** Utilizing the `tidymodels` ecosystem for structured data generation and resampling prep.

### 3. Data Visualization
* **With Base R:** Creating quick and functional exploratory plots (`plot`, `hist`, `boxplot`).
* **With Tidyverse & Tidygraphs:** Crafting advanced, publication-ready graphics using `ggplot2` and exploring relational/network data via `tidygraph`.

### 4. Mathematical Operations with R
* **Base R:** Implementing linear algebra, calculus basics, and standard matrix operations.
* **Using Mosaic:** Utilizing the `mosaic` package to simplify mathematics and introductory calculus in R.

### 5. Statistical Practices with R
* **Cross-Sectional Data:** Analyzing data collected at a single point in time.
* **Time Series:** Modeling and forecasting chronological data.
* **Panel Data:** Analyzing multi-dimensional data involving measurements over time for the same individuals/entities.
* **Other:** Miscellaneous statistical tests and advanced hypothesis testing.

### 6. Machine Learning and Simulations with R
* Predictive modeling, regression techniques, classification algorithms, and stochastic simulations.

---

## 📊 Data Sources(WIP)

To maintain a focus on practical application, the projects in this repository utilize data from the following real-world sources:
* *[Source Name 1]* - [Link to Source] (e.g., Kaggle, World Bank, UCI Machine Learning Repository)
* *[Source Name 2]* - [Link to Source]

---

## 🛠️ Getting Started

### ❗ Prerequisites
To run these scripts, you will need to have **R** installed. I highly recommend using **VS Code** as your IDE. I might create a structured guide for the installation of the same in the future.

### ❕Dependencies
You can install the primary packages used across this repository by running the following command in your R console:

```R
install.packages(c("tidyverse", "tidymodels", "tidygraph", "mosaic"))
