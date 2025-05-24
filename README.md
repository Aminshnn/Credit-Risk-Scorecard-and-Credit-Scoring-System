# Credit-Risk-Scorecard-and-Credit-Scoring-System

This project focused on developing a credit risk scorecard and credit scoring system using Lending Club data, with the goal of predicting loan defaults in a way that is accurate, interpretable, and aligned with banking industry standards.

To ensure practical application, I engineered the dataset by removing post-approval variables and transforming key features using **Weight of Evidence (WoE)** to preserve the monotonic relationship with default risk. Features were selected using a mix of model-based importance scores and domain knowledge. I handled class imbalance through resampling and trained a logistic regression model to estimate default probabilities.

These predicted probabilities were then converted into **credit scores**, assigning each borrower a score that reflects their likelihood of default in a standardized way. This makes it easier for credit teams to segment risk, automate approval decisions, and align lending strategy with portfolio objectives. I also transformed the model output into a structured scorecard, where each borrower’s score is broken down into points based on specific features (e.g., loan purpose, income level, credit history). This format is widely used in banks and credit bureaus because it provides **transparency**, **consistency**, and **explainability**—key requirements for both internal risk oversight and external regulations.

By presenting risk in this interpretable format, the scorecard helps ensure **fair lending practices** (e.g., under **ECOA**) and supports compliance with **Basel III** expectations around model governance and capital adequacy. It also enables practical integration into **loan underwriting systems, credit decision engines**, and **risk-based pricing frameworks**, all of which are critical in today’s **data-driven lending environments**.

The final output included:

- A full scorecard showing variable-level contributions to the score

- Individual credit scores for both training and test borrowers

- Visualizations of credit score distributions and variable impacts using WoE

- ROC and precision-recall curves to evaluate model performance and generalization

This project demonstrates how **machine learning and traditional credit scoring techniques** can work together to build a scalable, interpretable, and regulator-ready credit risk system. The approach reflects the practical needs of credit bureaus, banks, and lending institutions where accuracy, transparency, and compliance are critical to responsible lending.

