# Drug Regimen Success in Mice

In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens.

This was based off of two sets of data in separate CSV files, which were manipulated in a Jupyter Notebook using Pandas and Matplotlib. The first dataset details each mouse's "Mouse ID", which drug regimen they were given, as well as the mouses age, sex and weight. The second included the actual study results, which displayed the volume of a mouse's tumor when measured at several different timepoints.

# Unique Mice tested on each Regimen

![image](https://user-images.githubusercontent.com/68552052/112407785-b6120b00-8ce4-11eb-9a2d-2267b3ef9b5b.png)

# Final Tumor Volumes of Mice across Regimens of Interest

![image](https://user-images.githubusercontent.com/68552052/112407897-da6de780-8ce4-11eb-8874-6332569f8d9c.png)

# Mouse Treated with Capomulin Over Time

![image](https://user-images.githubusercontent.com/68552052/112408068-1d2fbf80-8ce5-11eb-9140-46e0f995ec28.png)

# Tumor Volume vs. Mouse Weight

![image](https://user-images.githubusercontent.com/68552052/112408149-46505000-8ce5-11eb-9b60-f3e5a843d048.png)

# Observations:

1. Based on the correlation scatterplot there appears to be a relationship between mouse weight and tumor volume. It makes sense that a larger mouse would generally have a larger tumor, maybe a better analysis would normalize the mouse weight and tumor volume.

2. Ramicane and Capomolin are the most successful at reducing tumor volume based on the box plots. They are able to keep the volume in a lower range and do not have outliers.

3. I only measured tumor volume at the end timepoint so we may have missed out on some successful drugs that just happened to show growth in their later stages. These could have been tested on larger mice and so left out of the box plot analysis.
