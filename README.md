# matplotlib-challenge
Part 0: Dependencies and reading in the data.
Part 1: Merged the study files and displayed to confirm.
Part 2: Confirmed had 249 unique mice and determined there were 5 duplicate ID-Timepoint entries (all for Moiuse ID g989) and dropped them. Now working with 1888 rows in the clean_df down 5 rows from 1893 in the merged_df.
Part 3: Determined Tumor Volume summary statistics (mean, median, standard deviation, variance and SEM) for each drug regimen using groupby and summary statistical methods. Displayed in data frame.
Part 4: Generated bar (measurements oer drug regimen) and pie charts (gender distribution) using pandas and matplotlib.
Part 5: Determined the final Tumor Volume for each mouse for Capomulin, ramicane, Infubinol, and Ceftamin. Presented the results in pyplot generated boxplots with styled outliers.
Part 6: Generated a line plot (Tumor Volume vs Timepoint) for a randomly selected mouse on Capomulin as well as a scatter plot (average Tumor Volume vs Mouse Weight) for mice on Capomulin.
Part 7: Determined the correlation coefficient (0.950524396185527). This is a strong positive correlation. Also generated the regression plot and styled the line red (together with the displayed equation).
