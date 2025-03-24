# 📊 beerhouse_data_linear_regression

This project analyzes the relationship between **crime rates** and various **social factors** such as **education, religious attendance**, and the **density of beer houses** in British counties during the **1850s**. The goal is to understand how these variables may have influenced criminal activity in that historical context using **linear regression and exploratory data analysis**.

---

## 📁 Dataset Source

The dataset comes from a historical study by **John Clay (1857)** and is publicly hosted by the **University of Florida**:

📎 **Data URL:**  
[http://users.stat.ufl.edu/~winner/data/beerhall.dat](http://users.stat.ufl.edu/~winner/data/beerhall.dat)

### Variables in the dataset:
- `Criminals`: Number of convicted criminals per 100,000 inhabitants  
- `BeerHouses`: Number of beer houses per 100,000 inhabitants  
- `School`: School attendance per 10,000 people  
- `Church`: Church attendance per 2,000 people  
- Plus region and county identifiers

---

## 🧠 Purpose

The aim of the project is to:

1. **Perform data cleaning and visualization**
2. **Explore relationships** between crime and each predictor
3. **Transform variables** when necessary (e.g., `log(BeerHouses)`)
4. **Build and compare regression models**
5. **Select the best model** using AIC/BIC and interpret the results
6. **Assess assumptions** of linear regression (normality, homoscedasticity, outliers)

---

## 📌 Key Findings

- **Beer house density** is positively and significantly associated with crime.
- **School attendance** shows a negative (but weaker) association with crime.
- **Church attendance** has no significant effect.
- The best model (based on AIC/BIC) uses `log(BeerHouses)` and `School` as predictors.

---

## 🔧 Tools Used

- **R** & RMarkdown for analysis and report generation  
- `ggplot2`, `GGally`, `broom`, `MASS` for visualization and modeling  
- Statistical techniques: Linear regression, residual analysis, AIC/BIC model selection, hypothesis testing

---

## 📚 Reference

- Clay, J. (1857). *On the Relation Between Crime, Popular Instruction, Attendance on Religious Worship, and Beer-House*.  
  Journal of the Statistical Society of London, Vol. 20, pp. 22–32.

---

## 💬 Contact

Feel free to open an issue or reach out if you have questions or feedback!

