# replicability_of_brain_associations

## 1_prepare_ukbb_data
### The program is used to select the imaging and variable data from UK Biobank and calculate the correlations between brain measures and a variable using booststrapping method.

## 2_estimate_global_replicability
### According to the bootstrapped correlation results, we calculate the global replicability (Intraclass correlation coefficient (ICC) and Jaccard index).

## 3_estimate_regional_replicability
### According to the bootstrapped correlation results, we calculate the regional replicability and find the minimally required sample sizes for replicable brain associations

## 4_improve_replicability_by_sample_selection
### We performed a pre-selection based on six representative variables, using quartiles to select two groups with the lowest and highest 25% scores. 
### Then, we used two-sample t-tests to compare the neuroimaging measures between the two groups, and estimated the regional replicability for each brain measure at different sampling sizes. 
### To further refine our pre-selection, we conducted a more extensive analysis, selecting two groups based on the smallest and largest scores at 10%, 20%, 30%, and 40%.

## 5_feature_selection_random_forest
### This program is used to calculate the feature selection results using random forest regression.

## 6_multivariate_regression_analysis
### This program is used to conduct the partial least squares (PLS) regression using boot strapping methods.

## 7_plot_global_replicability
### This program is used to visualize the global replicability.

## 8_plot_regional_replicability
### This program is used to visualize the regional replicability.

## 9_plot_feature_selection
### This program is used to visualize the replicability of feature selection.

## 10_plot_statistical_comparsions
### This program is used to visualize the statistical results.
