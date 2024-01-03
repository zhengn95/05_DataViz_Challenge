# 05_DataViz_Challenge
Challenge 5 for UC Berkeley Data Analytics Bootcamp. In this assignment, we use Python, Pandas, and Matplotlib to visualize and analyze data

### Scenario: 
Pymaceuticals, Inc. is a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

This analysis uses complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

In this analysis, I was tasked with generating all of the tables and figures needed for the technical report of the clinical study and a summary of the study results.

### Mean Tumor Volume and Standard Deviation
According to the Summary Statistics, the mean Tumor Volume and median Tumor Volume at all time points for the Capomulin-treated mice (mean = 40.7 mm3, median = 41.6 mm3) were the smallest compared to all other drug regimens except for Ramicane-treated mice (mean = 40.2 mm3, median = 40.7 mm3). Likewise, the Ramicane-treated mice had the lowest variability in tumor volume (var = 23.5 mm3, standard deviation = 4.8 mm3) followed by the Capomulin-treated mice (var = 24.9 mm3, standard deviation = 5.0 mm3). 

### Bar Chart: Drug Regimen versus Number of Observed Mice/Timepoint 
The drug regimen with the highest number of observed mice per timepoint was Capomulin followed closely by Ramicane.

### Pie Plot: Sex of Mice
There were more male mice (958 mice, 51%) versus female mice (922 mice, 49%) in the study.

### Box Plot: Final Tumor Volume versus Four Drug Regimens
According to our boxplot analysis of the tumor volume at the last time point for mice treated by Capomulin, Ramicane, Infobinol, and Ceftamin, mice treated with Capomulin & Ramicane had a much lower tumor volume at the final timepoint when compared with Ramicane & Infobinol. It should be noted that a mouse treated with Infobinol had a much lower tumor volume at the final timepoint compared to other mice treated on the same drug creating an outlier.

### Line Plot: Capomulin Treated Mouse (ID l509), Tumor Volume versus Timepoint
When observing the tumor volume of a Capomulin-treated mouse at each timepoint in days, the tumor volume increased from day 0 to 20 and reach a peak at day 20.  The tumor volume would mostly decrease from day 20 and onward reaching it's lowest tumor volume between day 30 and 35.

### Scatter Plot: Mouse Weight versus the Average Observed Tumor Volume
According to the scatterplot generated for Capomulin-treated mice, there is a strong correlation between mouse weight and average tumor volume (r-squared = 0.71). The higher the mouse weight, the larger the average tumor volume.
