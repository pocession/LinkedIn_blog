## Workflow for the data analyst
Since Nov 2021, I have been a data analyst in Immunology/Aging/Bioinformatics for almost 1.5 yr. It's about time to have some reflections. Here is a modified workflow. In general, I would like to adopt industry-style workflow more in my daily analysis work.

I'll use a time-series analysis data as an example.

- Sit down and discuss: I would first gain an understanding of the context and specific goals of the project. For example, are people trying to look for patterns or trends from data? Then I must use smoothing techniques for the curve. Or are people trying to classify the curves into different groups, then I don’t transform the curves but use clustering techniques. Overall, this step is necessary and is aiming to gather information on what the growing curves represent and what type of insight people are seeking.

- Exploratory data analysis (EDA): This would involve visualizing the curves and summarizing their distributions, identifying any outliers or anomalies, and exploring relationships between variables if there are any. And at this step, I would also share the data and preliminary outcome with people and have some discussion to make sure we are on the same page.

- Real analysis: based on the results of the EDA, I would then determine the most appropriate statistical or machine learning techniques to use in order to answer the questions of interest. For example, if our goal is to identify patterns or trends in the curves, I may use different time-series analysis techniques such as ARIMA or exponential smoothing and identify the association between trends and variables. If people are trying to classify the curves, I have to use different clustering ways such as K-means or or hierarchical clustering.

- Visualization and interpretation: Powerpoint slides are necessary. Creating an interactive platform (R Shinny or Tableau) for people to play with data is a plus. To avoid biases, I’ll present the result and insight, without too much input from you. This process would also involve visualizing the results in an appropriate format (such as plots or heatmaps) and presenting a summary of the key findings, along with any limitations of the analysis and areas for future work.
