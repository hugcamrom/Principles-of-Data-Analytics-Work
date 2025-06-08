# Principles-of-Data-Analytics-Work

Lecture by Ian McLoughlin at [ATU](https://www.atu.ie/)

![penguins](https://allisonhorst.github.io/palmerpenguins/logo.png)

```bash
python script.py
```

---

## Palmer Penguins Data Analysis

---

## Overview

This project explores the **Palmer Archipelago penguin dataset** using Python. It applies data analysis principles taught in the "Principles of Data Analytics" module by Professor Ian McLoughlin at ATU. The analogy of "learning to drive" was used throughout the course to help students understand the progression from beginner to independent coder.

> _“We're hopping into the car and we're wrecking the clutch.”_  
> — Professor McLoughlin, t01v04, Jan 22, 2024 -

## Objectives

- Learn basic Python programming concepts.
- Understand how to load, inspect, and manipulate real-world data.
- Create visualisations (scatter plots, histograms, bar charts).
- Analyse and interpret data using correlation and regression.
- Apply Markdown and GitHub practices for project documentation.

## Features

- Data cleaning (handling NaNs).
- Data exploration using `.describe()` and `.dtypes`.
- Plotting scatter plots with regression lines.
- Creating bar charts grouped by category.
- Visualising distributions with histograms.
- Calculating Pearson’s correlation coefficient.

## Usage

1. Open the `penguins.ipynb` notebook in Jupyter or VS Code.
2. Run all cells to see the data cleaning, plotting, and analysis.
3. Modify or extend with your own visualisations or interpretations.

## Project Structure

```bash

📁 project-root
├── penguins.ipynb         # Jupyter Notebook with full data analysis
├── README.md              # This README file
└── .gitignore             # Standard ignore rules
```

## Installation

To run the notebook:

1. Install Python 3.x  
2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install the required libraries:
   ```bash
   pip install pandas matplotlib numpy
   ```

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Tools and Libraries

- **Python** – Main programming language used.
- **pandas** – For data manipulation and DataFrame operations.
- **matplotlib** – For plotting charts and graphs.
- **NumPy** – For numerical calculations and arrays.
- **Jupyter Notebook** – For combining code, visuals, and notes.

## Documentation and Insights

- Variables such as `bill_length_mm`, `bill_depth_mm`, `body_mass_g`, etc., were examined.
- The dataset was cleaned using `df.dropna()` to remove missing values.
- Scatter plots between bill length and depth were plotted.
- Regression lines were added using `np.polyfit`.
- Grouped bar charts by species and sex were generated.
- Histograms of `body_mass_g` and `flipper_length_mm` were created.
- Pearson’s correlation coefficient was calculated for:
  - `body_mass_g` vs. `flipper_length_mm`: **0.87**

## Sources and References

- Palmer Penguins dataset from Wikimedia via Seaborn
- [Seaborn Penguin Dataset on GitHub](https://github.com/mwaskom/seaborn-data)
- ATU course material by Prof. Ian McLoughlin
- Python.org
- [W3Schools](https://www.w3schools.com/python/)
- [Real Python](https://realpython.com/)
- Stack Overflow
- GitHub, Visual Studio Code, ANACONDA, Git, Markdown

## Licence

This project is for educational purposes only. Based on course materials from ATU. Penguin dataset license as per Wikimedia/Seaborn.

## Tags

`#Python` `#DataAnalytics` `#Visualisation` `#PalmerPenguins` `#Jupyter` `#pandas` `#matplotlib` `#ATU`

---

**Author:** Hugo Camacho Romero  
**Student at [ATU](https://www.atu.ie/)**  
**Course:** Principles of Data Analytics
  