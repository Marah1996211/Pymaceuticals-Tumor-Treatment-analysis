##Project Overview
This project revolves around the analysis of a pharmaceutical study conducted by Pymaceuticals, Inc., focusing on the efficacy of various drug treatments for squamous cell carcinoma (SCC) in mice. You, as a senior data analyst, were tasked with preparing and analyzing the study data to provide valuable insights for a technical report. Specifically, the study aimed to evaluate the performance of the drug Capomulin against several other treatment regimens over the course of 45 days.

You worked with data from an experiment involving 249 mice, tracking tumor development and evaluating various treatment options. The project’s primary goal was to clean, analyze, and visualize the data, ultimately drawing conclusions regarding the efficacy of these treatments.

Key Tasks Completed
1. Data Preparation
Merging DataFrames: You successfully merged two provided DataFrames (mouse_metadata and study_results) into a single DataFrame for more streamlined analysis.
Data Cleaning: The analysis revealed that some mice had duplicate timepoints, which needed to be removed. You identified these duplicates, extracted the data associated with the problematic mice, and removed them from the dataset to ensure data integrity.
Unique Mice Count: After cleaning, you displayed the number of unique mice IDs and confirmed the dataset was free from duplicates.
2. Summary Statistics
Drug Regimen Analysis: You created a summary statistics table that broke down key metrics (mean, median, variance, standard deviation, SEM) for the tumor volumes across different drug regimens. This allowed for an easy comparison of how each treatment performed.
Generated Summary Table: The summary statistics table was organized by drug regimen, offering clear insights into the treatment effectiveness based on tumor volume measurements.
3. Visualizations
Bar Charts: You generated two bar charts that displayed the total number of mouse timepoints for each drug regimen across the study. The first chart was created using the Pandas .plot() method, while the second chart was built with Matplotlib’s pyplot methods, ensuring a good comparison of both methods.
Pie Charts: You created two pie charts that visualized the gender distribution (male vs. female mice) in the study, using both Pandas and Matplotlib approaches to generate identical results.
4. Quartiles, Outliers, and Box Plots
Final Tumor Volume Analysis: You isolated the final tumor volumes from the four key treatments: Capomulin, Ramicane, Infubinol, and Ceftamin. Using these, you calculated the quartiles and interquartile ranges (IQRs) and determined potential outliers for each treatment group.
Box Plot Creation: You created a box plot that showed the distribution of tumor volumes for each treatment regimen. Outliers were highlighted with distinct colors and styles to provide a clearer understanding of the treatment effectiveness and variability.
5. Line Plot and Scatter Plot
Line Plot for Capomulin: You selected a single mouse treated with Capomulin and generated a line plot to visualize the change in tumor volume over time for that mouse. This plot helped track the progression of the tumor and the drug’s effect over the study duration.
Scatter Plot for Capomulin: You also generated a scatter plot showing the relationship between mouse weight and average tumor volume for the entire Capomulin treatment group. This plot helped explore any correlation between these two variables.
6. Correlation and Regression
Correlation Coefficient: You calculated the Pearson correlation coefficient between mouse weight and average tumor volume for the Capomulin treatment group. This helped quantify the strength of the relationship between these variables.
Linear Regression: You performed linear regression analysis on the same data, generating a regression line and plotting it over the scatter plot to visually represent the relationship between weight and tumor volume. This model allowed for predictions and deeper insights into the data.
Tools and Techniques Used
Pandas: For data manipulation, merging datasets, and summary statistics generation.
Matplotlib (pyplot): For creating bar charts, pie charts, box plots, line plots, and scatter plots.
NumPy: For statistical calculations like variance, standard deviation, and quartiles.
SciPy: For performing correlation and regression analysis.
Jupyter Notebook: For running the analysis, generating visualizations, and compiling the final report.
Results and Insights
Efficacy of Capomulin: The data analysis provided a clear picture of how Capomulin performed relative to other treatments, with Capomulin showing promising results, particularly in terms of tumor volume reduction.
Outlier Identification: Several outliers were identified in the tumor volume data, especially for treatments like Infubinol and Ramicane, which could point to anomalies or inefficacies in the respective treatments.
Statistical Analysis: The correlation between mouse weight and tumor volume for Capomulin was explored, and the linear regression model provided further insight into this relationship, which may inform future studies and treatment strategies.
Conclusion
Through this comprehensive analysis, you provided the executive team with a clear, detailed breakdown of the study’s results. The visualizations helped communicate the key findings effectively, and the statistical analyses supported evidence-based decision-making for the future development of Pymaceuticals' anti-cancer treatments.







