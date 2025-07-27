# 🏥 Medical Insurance Cost Estimator

This project explores how individual lifestyle and demographic factors impact estimated medical insurance costs. It's based on a Codecademy Python Syntax project and focuses on practicing fundamental Python concepts such as variables, arithmetic operations, and string formatting.

## 📌 Project Overview

As a medical professional or data analyst, understanding how factors like age, sex, BMI, smoking status, and number of children influence insurance costs can provide valuable insights. This Python-based model uses a linear formula to estimate yearly insurance costs and investigates how changes in each factor affect the output.

## 🧮 Formula Used

The insurance cost is estimated using the following linear formula:

insurance_cost = 250 * age
- 128 * sex
+ 370 * bmi
+ 425 * num_of_children
+ 24000 * smoker
- 12500

Where:
- `age`: age in years
- `sex`: 0 for female, 1 for male
- `bmi`: body mass index
- `num_of_children`: number of children
- `smoker`: 0 for non-smoker, 1 for smoker

> *Note: The dataset and formula used are simplified and hypothetical. Real-world insurance models are far more complex and account for a broader set of factors.*

## 🧑 Sample Case

Initial example:
- Age: 28  
- Sex: Female (0)  
- BMI: 26.2  
- Children: 3  
- Smoker: No (0)

Calculated insurance cost: **$5469.00**

## 🔍 Factor Analysis

The project then investigates how changes to individual factors affect the estimated insurance cost:

- **Age**: +4 years  
  → Change: +$1000.00

- **BMI**: +3.1  
  → Change: +$2294.00

- **Sex**: Female (0) → Male (1)  
  → Change: -$128.00

- **Extra Practice**:  
  - Add 5 more children  
  - Change smoker status to "Yes" (1)  
  → Change: +$30247.00

## 📁 Files

- `insurance_cost_estimator.ipynb`: Jupyter Notebook with all code and outputs.
- `README.md`: Project overview and usage guide.

## 🛠 Technologies Used

- Python 3.x
- Jupyter Notebook
- Basic arithmetic operations and variable manipulation

## 🧠 Learning Objectives

- Practice Python syntax: variables, operators, reassignment
- Use basic arithmetic to simulate real-world models
- Understand how individual variables contribute to a total outcome
- Print readable results using string concatenation and formatting

## 🚀 Getting Started

1. Open the `insurance_cost_estimator.ipynb` file in Jupyter Notebook or VS Code with Jupyter extension.
2. Run the cells one at a time to see how the insurance cost changes as each factor is adjusted.
3. Modify the variable values to run your own simulations.

## 📝 Future Extensions

- Replace hardcoded values with user input
- Add visualizations using Matplotlib or Seaborn
- Import real-world datasets for more advanced modeling
- Apply linear regression for predictive modeling

## © Disclaimer

This model is a learning exercise and should not be used for actual insurance estimates or medical advice.

---

Created as part of the [Codecademy Python Syntax course](https://www.codecademy.com/learn/learn-python
