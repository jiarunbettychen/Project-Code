## Optimizing Portfolio Weights with Theory and Machine Learning

This repository contains the report, poster, and code related to the project **Optimizing Portfolio Weights with Theory and Machine Learning**. This project explores portfolio optimization through theoretical models and machine learning techniques, tailored for investors with varying risk tolerances.

### Contents
- **Report**: [Link to Report](./Report.pdf)
- **Poster**: [Link to Poster](./Poster.pdf)
- **Code**: All project code is provided in the `Jupyter Notebook` or the `HTML` folder which supports the portfolio optimization models discussed in the report.

### Overview
In this study, we examine two portfolio optimization approaches:
1. **Minimizing Portfolio Variance**: Focuses on reducing portfolio risk.
2. **Linear-Quadratic Preference**: Balances risk and return based on investor risk tolerance, as outlined in Merton’s Portfolio Problem.

Backtesting on real world data, including 21 technology stocks, demonstrates the performance of each method. We test scenarios with different transaction costs, rebalancing schedules, and short-selling constraints, aiming to provide practical insights for investors.

### Key Sections

1. **Introduction**: Background on portfolio optimization.
2. **Model Setup and Parameter Estimation**: Explains model assumptions and methods for estimating asset returns and covariance matrices.
3. **Optimization Techniques**
   - **Variance Minimization**: Focuses on low-risk allocations.
   - **Linear-Quadratic Preference**: Incorporates expected returns and investor risk aversion.
4. **Results**: Comparison of different strategies, analyzing scenarios with and without rebalancing and short selling.
5. **Conclusion**: Summarizes the findings and practical implications.

### Dependencies
Python (Key packages: `numpy`, `pandas`, `scipy`, `matplotlib`, `cvxpy`)

### Usage
To reproduce results or apply the models to new data:
**Clone the repository**:
   ```bash
   git clone https://github.com/jiarunbettychen/Project-Code.git
   cd Project-Code
   ```
Run the scripts for portfolio optimization and backtesting.

### Contact
For any questions, feel free to reach out via [Email](mailto:betty010413@gmail.com) or connect on [LinkedIn](https://www.linkedin.com/in/jiarunbettychen).
