# MA-HW2-Survival-Analysis
# Homework 3: Survival Analysis

This project focuses on building and comparing Accelerated Failure Time (AFT) models using various distributions to understand factors affecting customer churn and to calculate Customer Lifetime Value (CLV) for different segments.

## Dataset

The dataset used in this project contains the following fields:

- `ID`: Subscriber ID
- `region`: Region code
- `tenure`: Lifetime of the subscription
- `age`: Subscriber's age
- `marital`: Subscriber's marital status
- `address`: Number of years living at the current address
- `income`: Subscriber's annual income in thousands
- `ed`: Education level
- `retire`: Retirement status (Yes/No)
- `gender`: Gender of the subscriber
- `voice`: Voice service subscription (Yes/No)
- `internet`: Internet service subscription (Yes/No)
- `forward`: Call forwarding service activation (Yes/No)
- `custcat`: Customer category
- `churn`: Churn status (Yes/No)

## Parametric Models

### Objectives

- Build AFT models using all available distributions. For implementation details:
  - Python users can visit [Python Lifelines Documentation](https://lifelines.readthedocs.io/en/latest/lifelines.fitters.html)
  - R users can refer to the slides provided.
- Compare the models to determine the most effective one for decision-making.
- Visualize survival curves for all models in a single plot.
- Retain significant features in the final model.

## Customer Lifetime Value (CLV)

- Calculate the CLV per customer based on the final model.
- Use the logic provided in the slides to segment the CLV.
- Explore CLV differences across various customer segments.

## Report

### Guidelines

- Write a brief report (1-2 paragraphs) outlining your findings.
- Interpret the coefficients of your final model.
- Identify and describe the most valuable customer segments.
- Based on the assumption that the data represents the population:
  - Estimate the annual retention budget considering CLV and survival probabilities.
  - Identify the number of at-risk subscribers within a year.
- Provide additional suggestions for retention strategies.

## Submission Rules

Ensure your GitHub repository contains:

- `Code`: All code files used in the analysis.
- `Markdown/Notebook`: A detailed report including the analysis and code.
- `requirements.txt`: A file listing all Python packages required to run the code.
- `README.md`: This file with a project overview and setup instructions.

**Note:** Direct manual uploads are not allowed.

## Contributing

Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
