# Replicability-ukbb
Replicability of brain-phenotype associations

# 1_select_variables_from_ukbb.ipynb
We select the imaging data and variables from uk biobank (size=N).
The variables included: age, body mass index, fluid intelligence, numeric memory, neuroticism, alcohol consumption, birth month

# 2_calculate_correlations_by_sampling.ipynb
we randomly select two indepdent subsamples (size=n)from the full sample. n ranges from 100 to N/2. The Spearman's rank correlations were condcuted in two subsamples.

# 3_estimate_global_replicability.ipynb
According the results of correlations, we estimated the global replicability: the Jaccard index and intraclass correlation coefficients (ICC)

# 4_estimate_regional_replicability.ipynb
According the results of correlations, we estimated the regional replicability for single brain-phenotype association

# 5_plot_Jaccard_index_and_ICC.ipynb
plot the improvemnts of global replicability with increasing sampling size

# 6_plot_regional_replicability.ipynb
plot the improvemnts of regional replicability with increasing sampling size

# 7_calculate_ttest_median_split_by_sampling.ipynb
We used the median value to half split the full sample and then conducted the two-sample t-test while sampling

# 8_calculate_ttest_Q1_Q4_by_sampling.ipynb
We selected the first and fourth quarters and and then conducted the two-sample t-test while sampling

# 9_estimate_and_plot_regional_replicability_ttest.ipynb
We estimate the regional replicability of two-sample t-test and plot the improvemnts of regional replicability with increasing sampling size

# 10_feature_selection_replicability.ipynb
We conducted the multivariate random forest feature selection while sampling, and estimated the Jaccard index

