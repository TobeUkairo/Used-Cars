# Executive Summary

**Objective**: To identify factors influencing used car prices, aiding the dealership in inventory and pricing decisions.

**Key Findings**: Premium brands significantly increase car values. Vehicle age and mileage inversely affect prices. Fuel type variations play a notable role in pricing.

**Recommendation**: Focus on acquiring high-value brands and adjust pricing strategies based on age, mileage, and fuel type.


## Data Overview

**Dataset Description**: The dataset includes data on 426,880 used cars, encompassing various makes, models, years, conditions, and other attributes.

**Source**: Compiled from a comprehensive online car marketplace.

**Scope**: Encompasses a diverse range of vehicles, offering a broad market perspective.


## Data Preparation

**Cleaning**: Removed outliers and non-positive prices.

**Transformation**: Applied Box-Cox transformation for normalization.

**Feature Engineering**: Introduced 'car_age' as a new feature.

**Model Selection**: Chose Linear Regression for its interpretability and relevance to the data.

**Hyperparameter Tuning**: Employed GridSearchCV for optimal parameter selection.

## Model Insights and Interpretation

**Model Performance**:

**R-squared**: 47.69%, indicating the model's moderate ability to predict price variations.

**MSE**: 14.6605, reflecting the average squared difference from actual prices.

## Influential Factors

Brands like Ferrari and Tesla boost prices.

Older cars and those with high mileage have lower prices.

Diesel fuel types positively influence prices, whereas electric/hybrid vehicles negatively impact prices.

## Recommendations for Inventory Management

**High-Value Brands**: Prioritize acquiring and selling brands that have a strong positive impact on prices.

**Pricing Strategy**: Consider a car's age and mileage in pricing. Older and high-mileage cars should be priced lower.

**Market Trend Adaptation**: Stay updated on fuel type trends and consumer preferences.

## Limitations and Future Work

**Limitations**:

The model explains only about 48% of the price variance.

Certain niche market segments might not be fully captured.

## Future Directions

Incorporating more granular data (specific models, detailed condition ratings). Exploring non-linear models for potentially better predictions.

## Conclusion

The analysis provides valuable information into price determinants in the used car market. The dealership can take advantage of these findings to optimize inventory acquisition and develop pricing strategies.
