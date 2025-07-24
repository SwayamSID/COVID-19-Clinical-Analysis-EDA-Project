![MasterHead](https://s3-ap-south-1.amazonaws.com/ricedigitals3bucket/AUPortalContent/2020/04/04092430/covid19.jpg)

# COVID-19 Clinical Analysis using EDA
This project is a detailed analysis about the pandemic Covid-19 that had spread rapidly and how its impact was on the countries across the world.

---

## 🎯 Aim of the Project
This project not only helps to understand the global response to COVID-19 via clinical research but also equips aspiring data analysts and scientists with hands-on experience in real-world EDA, data wrangling, and visualization.

---

## 🖊️ Objectives
1. Understand the Nature of Clinical Trials:</br>
  Analyze key characteristics such as trial status, phase, study design, and funding sources to understand the scope and scale of COVID-19 research efforts.

3. Identify Global Patterns and Contributions:</br>
  Evaluate the geographic distribution of trials to determine which countries have been most active in clinical research.

4. Analyze Demographics and Target Groups:</br>
  Study variables like age groups, gender, and intervention types to uncover trends in how different populations are involved in trials.

5. Track Time-based Trends:</br>
  Examine how the number of clinical trials has evolved over time, especially during peaks of the pandemic.

6. Handle and Clean Real-World Data:</br>
  Apply data cleaning techniques (missing data imputation, column removal, data type conversion) on a messy real-world dataset.

7. Generate Visual Insights:</br>
  Create informative visualizations (bar charts, time series, maps) to aid in better understanding and presentation of clinical trial trends.

---

## 🔑 Key Processes
1. Importing required Python Libraries:</br>The libraries that are required for this project:</br>
      - numpy</br>
      - pandas</br>
      - seaborn</br>
      - matplotlib</br>
      - plotly</br>

2. Loading the Dataset:</br>The dataset is obtained from the ClinicalTrials.gov site and that has to be loaded in order to build the required frames.

3. Basic Exploration:</br>Process like making columns, indexing, and shaping is done.

4. Handling Missing Data:</br>Removing all the Null Values from the dataset.

5. Feature Engineering:</br>Extracting the Countries from the dataset.

6. Univariate Analysis:</br>Understanding the distribution, central tendency, and spread of a single feature in a dataset.

7. Bivariate Analysis:</br>Analysing two variables simultaneously to discover relationships, correlations, or patterns between them.

8. Time Series Analysis:</br>Analysing the peak time when the disease spread was the highest.

9. Top Countries by Trials:</br>Finding out the most affected countries and arranging them in descending order.

10. Saving the Dataset:</br>After all the above processes, saving the cleaned data for future use.

---

## 🛎️ Important Graphs Related to the project
1. Status by Clinical Trials</br>
</br>
<img width="1017" height="705" alt="StatusofClinicalTrials" src="https://github.com/user-attachments/assets/e63948bb-547e-4cfa-aea2-3ec1b5b99278" /></br>
</br>

2. Distribution Phases</br>
</br>
<img width="1017" height="652" alt="DistributionofPhases" src="https://github.com/user-attachments/assets/cbc06bd8-0641-4e51-878d-f26300f36deb" /></br>

</br>
3. Age Group Distribution</br>
</br>
<img width="1023" height="872" alt="AgeGroupDistribution" src="https://github.com/user-attachments/assets/ad016bdd-169f-4cf4-83fe-9084248cd873" /></br>

</br>
4. Status vs. Phases</br>
</br>
<img width="1017" height="705" alt="StatusvsPhases" src="https://github.com/user-attachments/assets/0f113c5b-fdc9-4dda-9308-892d63b97f9d" /></br>

</br>
5. Trials Started Over Time</br>
</br>
<img width="1009" height="550" alt="TrialsStartedOverTime" src="https://github.com/user-attachments/assets/a901e489-2747-45e3-bbf1-1ea7e8705a98" /></br>

</br>
6. Top 10 Countries by Trails</br>
</br>
<img width="1017" height="657" alt="Top10Countries" src="https://github.com/user-attachments/assets/67e5e416-0b49-4b4f-abd1-f9198f387f9c" /></br>

---

## 📩 Conlcusion
This project provided a comprehensive exploratory analysis of global COVID-19 clinical trials using real-world data from ClinicalTrials.gov. Through univariate and bivariate analysis, we identified that a significant number of trials were conducted in countries like the United States, France, and the United Kingdom. Most of the studies were either in the “Completed” or “Active, not recruiting” status, with a majority focusing on adult populations.</br>

The analysis of trial phases showed that Phase 2 and Phase 3 trials were the most common, indicating mid-to-late-stage research efforts. Missing data was carefully handled using appropriate imputation techniques, especially for categorical fields and enrollment numbers. Time-series analysis revealed an increase in the number of trials during the pandemic peaks, reflecting the urgency of global research efforts.</br>

Overall, the project not only highlighted geographical and temporal trends in COVID-19 clinical research but also offered hands-on experience in data cleaning, visualization, and pattern recognition. This analysis is useful for understanding how global health crises drive clinical research and can guide future healthcare planning and decision-making.

---

## ✍️ Key Learnings from this Project
Through this project, I gained practical experience in cleaning and preparing real-world healthcare data by handling missing values, dropping irrelevant columns, and applying appropriate imputation techniques such as median filling and categorical labeling. I developed a solid understanding of Exploratory Data Analysis (EDA), performing both univariate and bivariate analysis to extract meaningful insights using Pandas and Seaborn. The project enhanced my ability to visualize data effectively through bar plots, histograms, stacked bar charts, and time-series graphs, which helped uncover trends in trial phases, statuses, and demographic targeting.</br>

I also learned how to engineer new features, such as extracting country information from location data and transforming date fields for temporal analysis. Working with this dataset deepened my understanding of how large-scale clinical research is structured globally, especially during a public health crisis like the COVID-19 pandemic. The project also taught me to identify statistical patterns such as skewness and outliers in numeric data like trial enrollment figures. Additionally, it strengthened my ability to interpret geographic insights, recognizing the countries that led clinical trial efforts. Finally, I improved my project documentation and structuring skills, emphasizing the importance of clearly defined objectives, workflow clarity, and well-presented conclusions.
