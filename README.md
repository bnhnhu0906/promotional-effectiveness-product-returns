***Promotional Effectiveness & Product Return Behaviour in Online Fashion Retail***

Master's Thesis — MSc Marketing Analytics and Data Science, University of Groningen (2026)

Tools: Python (Pandas, Scikit-learn, Statsmodels, Matplotlib, Seaborn)


**Overview**

This study investigates how two promotional instruments — item-level discount depth and order-level coupon usage — affect product return probability in online fashion retail, and whether fashion level and customer store-shopping frequency moderate these relationships.

Dataset: 7,979 item-level transactions from a European online fashion retailer


**Key Findings**

Discount type outweighs discount depth in driving return risk: manufacturer-benchmarked pricing showed a return rate 9 percentage points lower than retailer-initiated discounts
Customer purchase frequency is the strongest predictor of return behaviour, outperforming all promotional variables across both machine learning models
Predictive models: Random Forest (AUC 0.787) and XGBoost (AUC 0.772) under 5-fold cross-validation

**Methods**

StageApproachConfirmatoryLogistic regression across 5 model specifications with clustered standard errorsPredictiveRandom Forest and XGBoost with 5-fold cross-validationFeature importancePermutation-based ranking to identify dominant return predictors


**Managerial Implications**

Retailers can differentiate promotional instruments based on return risk rather than treating all discounts as equally risky
CRM-based customer segmentation (by purchase frequency) is a more actionable lever for reducing return costs than promotional design alone


**Note on Data**

The dataset is proprietary and not included in this repository. The notebook documents the full analytical pipeline including data cleaning, feature engineering, model building, and robustness checks.
