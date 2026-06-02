# Market Basket Analysis with Python — Target

## Project Overview
Customer Purchasing Behavior and Product Recommendation Report
built for Target e-commerce platform using Python.

## Objective
- Discover frequently purchased product category combinations
- Segment customers based on buying behavior
- Provide actionable recommendations for cross-selling and promotions

## Dataset
- 800 rows × 23 columns
- Features: Demographics, Purchase Frequency, Browsing Habits,
  Satisfaction Levels, Review Engagement

## Techniques Used
| Technique | Purpose |
|-----------|---------|
| Apriori Algorithm | Market Basket Analysis |
| Association Rules | Cross-sell discovery |
| K-Means Clustering | Customer segmentation |
| Hierarchical Clustering | Comparison model |
| PCA | Cluster visualization |

## Key Results
- Top Rule: Groceries → Clothing & Fashion
  (Confidence: 65.2%, Lift: 1.23)
- Customer Segments:
  - Frequent Buyers: 112 (14%)
  - Occasional Shoppers: 196 (24.5%)
  - At-Risk Customers: 492 (61.5%)
- Mean Satisfaction Score: 2.94 / 5

## Business Recommendations
1. Cross-sell Clothing on Grocery product pages
2. Display shipping fees upfront to reduce cart abandonment
3. Target 196 occasional shoppers with personalized promotions
4. Improve recommendation engine for higher satisfaction

## Libraries Used
```
pandas | numpy | matplotlib | seaborn
scikit-learn | mlxtend | scipy
```

## Project Structure
```
├── Market_Basket_Analysis_with_Python_-_Target.ipynb
├── Target.csv
├── README.md
└── requirements.txt
```

##  Author
**Nihal Mahto**
