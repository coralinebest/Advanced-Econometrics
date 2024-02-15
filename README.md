# Advanced Econometrics

## Overview:
This report explores the determinants of the world happiness score using parametric and nonparametric econometric models in R. The analysis includes standard linear regression, Generalized Additive Models (GAM), and parametric models inspired by the insights from GAM.

## Presentation of the Application:

### What is the study about?
The study focuses on the World Happiness Report (2019), a significant survey that outlines global happiness levels. The report incorporates metrics from various disciplines, including economics, psychology, and public policy, providing insights into the science of happiness.

### Description of the Data:
The dataset consists of happiness scores derived from the Gallup World Poll, measuring individual satisfaction. Additional variables include GDP per capita, healthy life expectancy, social support, freedom to make life choices, generosity, and corruption perception.


## Regression Model:

### Linear Regression:
The linear regression model explores the relationship between happiness scores and key variables (GDP per capita, social support, healthy life expectancy, freedom to make life choices). Results indicate significant positive effects, with GDP per capita showing a strong correlation.

## Nonparametric Approach:

### Generalized Additive Model (GAM):
The GAM model explores nonlinear effects of variables on happiness scores. Results suggest quasilinear relationships for social support and freedom to make life choices, while GDP per capita and healthy life expectancy exhibit more complex effects.

#### Modified GAM:
To enhance interpretability, a modified GAM introduces linear relations for freedom to make life choices and social support. While slightly reducing explanatory power, it improves interpretability.

### Parametric Models:
Two parametric models, a piecewise linear model and a polynomial model, are introduced based on GAM insights. These models provide improved fit compared to the linear model but are less flexible than GAM.

#### Conclusion:
The parametric models offer increased interpretability, easier inference, and lower variance of estimates compared to GAM. While providing a better fit than the linear model, they fall slightly short of the flexibility of the nonparametric GAM.
This report highlights the trade-offs between parametric and nonparametric models in understanding happiness determinants. The chosen models cater to different needs, emphasizing the importance of considering both interpretability and flexibility in econometric analyses.
