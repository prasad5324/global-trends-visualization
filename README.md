# 📊 Simulated Global Development Visualization (1900–2023)

An interactive data visualization project exploring **simulated global trends** in
**GDP per capita**, **life expectancy**, and **population** over 123 years.

This project uses **Python**, **Pandas**, and **Plotly Express** to highlight how socioeconomic indicators evolve over time.
The final output is an animated bubble chart inspired by Gapminder’s famous global development visualizations.

---

## 🚀 Project Overview

This project demonstrates an end-to-end data workflow:

### ✔ Data Cleaning

* Reshaping wide-format CSVs using `melt()`
* Converting GDP/Population notations (k, M, B → integers)
* Handling NaN values and duplicated entries
* Converting year columns to numeric formats

### ✔ Feature Engineering

* Mapping countries to ISO codes
* Converting ISO codes → continent names (using `pycountry-convert`)
* Preparing a unified dataframe (`gapminder_df`)

### ✔ Data Visualization

Created an animated scatter plot with:

* **x-axis:** GDP per capita (log scale)
* **y-axis:** Life expectancy
* **bubble size:** population
* **colors:** continents
* **animation:** year (1900–2023)

---

## 🛠️ Technologies Used

* **Python 3**
* **Pandas**
* **NumPy**
* **Plotly Express**
* **pycountry-convert**
* **Google Colab**

