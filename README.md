# loan_data_prosper

## Loan Data from Prosper

The dataset used here was provided as a part of the Udacity Nanodegree program. It contains almost 114,000 loans of 81 variables, and this report analyzes 13 of the 81 variables.

### Analysis

I began by exploring the individual distributions of the variables in the dataset. Then, I looked at relationships between the variables and further explored the strongest trends. The exploration culminated in an interest in creating a linear model to predict borrower rate based on three of the variables. The linear model was able to account for over 50% of the variance in borrower rate, which I feel is fairly good considering only 3 of the 81 variables from the full dataset were used in the model.

### Libraries Used
- knitr
- ggplot2
- scales
- gridExtra
- psych
- RColorBrewer
- memisc
