# The-Impact-of-Digital-Transformation-on-Business-Model-Alignment-in-Service-Firms

Lawrence Ankomah Sei · September 2025  


## Project Description
---
This repository contains the full of the study examining how  **digital transformation (DT)** influences **business model alignment (BMA)** in service firms. Using survey data from 235 industry professionals across consulting, finance, education, hospitality, and healthcare, the study evaluates:
- The direct effect of DT on BMA
- The moderating role of financial health (FH)
- The mediating effect of customer demand for digital services (CD)
The project combines regression analysis, moderation, mediation, structural equation modeling (SEM), and thematic analysis of open-ended responses.to provide a holistic assessment of how digitalization shapes strategic alignment in service organizations.



## Research Questions & Hypotheses
--- 
| RQ | Question | Hypothesis | Result |
|----|------------------------------------------|------------|-----------|
| RQ1 | What is the impact of digital transformation on service business model alignment? | H1: DT → BMA (+) | **Supported** (β = 0.82, p < 0.001, R² = 0.74) |
| RQ2 | Does financial health moderate the DT–BMA relationship? | H2: FH moderates DT → BMA | Mixed / partially supported (significant only in full model, β = -0.19, p = 0.02) |
| RQ3 | Does customer demand mediate the DT–BMA relationship? | H3: DT → CD → BMA | **Supported** (indirect effect = 0.113, 13.7% of total, p = 0.001) |

## Dataset
--- 
- **Source**:  survey (2025)  
- **Sample**: N = 235 respondents from service industries  
- **Variables**:  
  - 29 Likert-scale items (1–5) measuring four latent constructs  
  - Demographic variables (gender, age, education, position, firm type)  
  - Three open-ended questions (benefits, challenges, recommendations)  
- **No personally identifiable or confidential data** is included.

## Methods
--- 

**Scale Reliability & Validity**

- Cronbach’s α > 0.89
- Composite Reliability (CR) > 0.89
- Average Variance Extracted (AVE) > 0.55
- EFA using polychoric correlations and minres extraction

**Statistical Modeling**

- Simple and multiple regression
- Moderated regression (DT × FH interaction)
- Mediation analysis (Baron–Kenny + bootstrapped paths)
- Integrated OLS model with interactions (R² = 0.78)
- Structural Equation Modeling (SEM) using lavaan with MLR estimator

**Robustness Checks**

- Bootstrapping (1,000 samples)
- HC3 heteroskedasticity-consistent SEs
- Influence diagnostics (Cook’s D, leverage)
  
**Qualitative Analysis**

- Thematic coding of open-ended responses
- Identification of benefits, challenges, and recommendations
- Integrated interpretation with quantitative findings

All analyses were conducted in R using an R Markdown workflow.


## Key Findings
--- 
- Digital transformation is a **very strong predictor** of business model alignment (73.6% explained variance in simple model).  
- Financial health has a **significant direct effect** on BMA but only weakly (and negatively) moderates the DT–BMA link in the full model.  
- Customer demand **partially mediates** the DT–BMA relationship (13.7% of total effect).  
- Industry differences: Consulting and Healthcare firms lead in both DT and BMA; Hospitality lags.  
- Qualitative themes: top benefits = improved customer experience & efficiency; top challenges = high costs & resistance to change; top recommendation = staff training.


