# ecommerce-pricing-analytics - Discount Strategy Optimization

Machine Learning solution for discount strategy optimization with 97.3% AUC (NUS Business Analytics Collaborative Project)

## Project Overview
Collaborative machine learning project achieving 97.3% AUC to predict discount profitability and prevent revenue-eroding pricing strategies. Developed during NUS Business Analytics program using comprehensive supervised and unsupervised learning approaches.

## Business Problem
Retail companies frequently implement discount strategies without predictive frameworks, leading to profit margin erosion and brand devaluation. This project addresses the "discount trap" challenge by classifying discount strategies as profitable ("Safe") or loss-making ("Trap").

## Technical Approach
- **Supervised Learning**: kNN, Random Forest, Decision Tree classification models
- **Unsupervised Learning**: K-Means clustering and PCA dimensionality reduction
- **Data Processing**: LOF outlier detection, feature engineering, class imbalance handling
- **Platform**: Orange Data Mining for visual machine learning workflows

## Key Results
| Model | Accuracy | F1 Score | AUC | Best Use Case |
|-------|----------|----------|-----|---------------|
| kNN | 98.4% | 0.956 | 0.992 | Flagging risky discounts |
| Random Forest | 97.8% | 0.943 | 0.991 | General prediction accuracy |
| Decision Tree | 95.7% | 0.927 | 0.973 | Rule creation for approvals |

## Business Insights
- **Discount Threshold**: Discounts above 20-30% consistently reduce profit margins
- **Risk Pattern**: VIP + Furniture + >30% discount combination identified as high-risk
- **Segmentation**: Furniture + Corporate segments show higher loss-making potential
- **Interpretability**: Decision tree provides clear business rules for pricing teams

## Files
- `ecommerce-pricing-analytics-presentation.pdf` - Complete project presentation
- `superstore-dataset.csv` - Modified retail dataset (if available)
- `orange-workflows/` - Orange Data Mining workflow files (if available)

## Tech Stack
- Orange Data Mining - Visual machine learning platform
- Superstore Dataset - Retail transaction data
- Machine Learning: kNN, Random Forest, Decision Tree, K-Means, PCA
- Data Processing: Outlier detection, normalization, feature engineering

## Business Applications
- Predictive discount approval workflows
- Profit margin protection strategies
- Category-specific pricing guidelines
- Marketing team decision support systems

---
**Collaborative Project**: NUS Business Analytics Program | Team DataLore  
**Individual Contribution**: Supervised learning model evaluation and presentation
