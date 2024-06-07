---
title: Projects
permalink: /projects/
---

<div style="margin-top: 20px;">
    <a href="/" style="display: inline-block; text-align: center; margin-right: 10px;">
        <img src="/assets/img/home.png" alt="Home" style="width: 100px; height: 100px;"><br>
        <span style="display: block; background-color: #007bff; color: white; padding: 10px; border-radius: 5px;">Home</span>
    </a>
    <a href="/about" style="display: inline-block; text-align: center; margin-right: 10px;">
        <img src="/assets/img/about_me.png" alt="About Me" style="width: 100px; height: 100px;"><br>
        <span style="display: block; background-color: #007bff; color: white; padding: 10px; border-radius: 5px;">About Me</span>
    </a>
    <a href="/resume" style="display: inline-block; text-align: center; margin-right: 10px;">
        <img src="/assets/img/resume.png" alt="Resume" style="width: 100px; height: 100px;"><br>
        <span style="display: block; background-color: #007bff; color: white; padding: 10px; border-radius: 5px;">Resume</span>
    </a>
    <a href="/projects" style="display: inline-block; text-align: center; margin-right: 10px;">
        <img src="/assets/img/projects.png" alt="Projects" style="width: 100px; height: 100px;"><br>
        <span style="display: block; background-color: #007bff; color: white; padding: 10px; border-radius: 5px;">Projects</span>
    </a>
    <a href="/contact" style="display: inline-block; text-align: center; margin-right: 10px;">
        <img src="/assets/img/contact.png" alt="Contact" style="width: 100px; height: 100px;"><br>
        <span style="display: block; background-color: #007bff; color: white; padding: 10px; border-radius: 5px;">Contact</span>
    </a>
</div>

<br>

# Projects

Here are some of the projects that I've completed and what I am currently working on:

![AGCO_Logo](/assets/img/agco_logo.png)

**Identifying Fraudulent Transactions in Travel and Expense Reports (AGCO Corporation)**:

**Date**: January 2024 to May 2024

**Software Used**: Python, Tableau, Excel

In collaboration with AGCO Corporation as part of my Consulting Practicum, I was tasked with identifying potential outliers in the company's travel and expense reports. During this project, I used Python to build and tune an Isolation Forest and a Principal Component Analysis model to automate anomaly detection, further enhancing each model's accuracy through continuous feedback and pattern analysis. After compiling a list of transactions that could be potential outliers, I piped the data into Tableau to create an interactive dashboard to present the main insights, allowing the audit team to quickly identify and investigate the suspicious reports. 


**Estimating Vaccination Rates for H1N1 and Seasonal Influenza**:

**Date**: November 2023 to December 2023

**Software Used**: Python

In this project, I used predictive modeling with the National 2009 H2N1 Flu Survey dataset to determine the individual vaccination likelihood for the 2009 H1N1 influenza virus and the seasonal influenza virus. Through careful data preprocessing that included accounting for missing values, ensuring all numeric variables were scaled properly, and encoding categorical variables in a binary representation, I verified that the data was prepared efficiently prior to constructing the machine learning models. The models that I constructed in this project were Logistic Regression, Random Forest Classification, XGBoost (Extreme Gradient Boosting), Decision Tree Classifier, Gaussian Naive Bayes, and LightGBM (Light Gradient Boosting Machine). By tuning each model's hyperparameters with Grid-Search Cross-Validation, I was able to effectively minimize computational resources and maximize ROC_AUC performance.

To learn more about this project, please visit the corresponding GitHub repository [here](https://github.com/hakhan2000/Predict-Flu-Vaccination).

**United States COVID-19 New Positive Changes in 2021**:

**Date**: September 2023 to October 2023

**Software Used**: Tableau

In this project, I utilized COVID-19 data to determine how the amount of new positive cases in the United States changed over time in 2021. Using Tableau, I created several visualizations that included a dynamic map, line chart, table chart, and bar chart that integrated seamlessly together to create an interactive user-friendly dashboard. In doing so, I was able to pinpoint California as the state with the highest amount of new positive COVID-19 cases in the United States for 2021 and then created different visualizations to dive deeper into the state and county level.

To learn more about this project, please visit the corresponding GitHub repository [here](https://github.com/hakhan2000/COVID-CA-2021-Dashboard).

Here is a screenshot of the dashboard at the county level for California below:

![CA County Dashboard](/assets/img/CA-County-Dashboard.png)

**Prototyping Cloud-Native Data Architecture**:

**Date**: September 2023 to October 2023

**Software Used**: AWS S3, AWS Glue, AWS Redshift, AWS Sagemaker

In this project, I became more familiar with using the cloud to perform data analysis. Specifically, I constructed a predictive machine learning model using AWS Sagemaker to assess the likelihood of bankruptcy for 10 companies that were being considered for a new portfolio. Moreover, I designed a cloud-native data architecture in AWS that has the capability to centralize data storage and streamline analytics. This architecture included the following steps: creating a landing zone for various data types and sources using AWS S3 and using AWS Redshift to create a data warehouse that consolidated balance sheets, income statements, and bankruptcy statuses for ease in access. Finally, I used AWS Glue to maintain efficient scalability and replicability through automation.

To learn more about this project, please visit the corresponding GitHub repository [here](https://github.com/hakhan2000/Design-Cloud-Data-Architecture).

My final presentation about this project can be found below:

<iframe width="560" height="315" src="https://www.youtube.com/embed/GnT2lOavsAY" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

**Unveiling SpaceX Falcon9 Launch Success**:

**Date**:  February 2023 to April 2023

**Software Used**: Python, SQL, Folium, Plotly

In this project, I performed web scraping with Python using the BeautifulSoup and Requests libraries to acquire Falcon 9 launch records from SpaceX. The main task was to identify and understand factors that influence these launches to assist competing startups in making a strategic bid against them. After that, I used Python and SQL to conduct exploratory data analysis and generate labeled data that could be used to create supervised models. Finally, I created an interactive dashboard with Plotly to allow for ease in launch record analysis, developed a proximity map with Folium for launch site analysis, and built/tuned several classification models to predict the success of the first stage landing.

To learn more about this project, please visit the corresponding GitHub repository [here](https://github.com/hakhan2000/SpaceX-Falcon9-Project/tree/main).

**Classifying NFL Offensive Play Types**:

**Date**: September 2021 to December 2021

**Software Used**: Python

In this project, my goal was to determine whether NFL Offensive Plays can be predicted and classified by use of machine learning models. If successful, the ideal model could be used to assist a defensive team in devising strategies that are meant to counter a team that is known to execute certain types of plays. Specifically, I used NFL data from the 2020 season and created two Python notebook files: the first notebook was used to perform data cleaning, which consisted of removing plays in a column with specific conditions, verifying that the column is not null, standardizing certain values through mapping, and saving the data as a CSV file. Moreover, the second notebook was used to perform feature selection, encode categorical variables, and the primary model training steps. These steps included splitting the data into training and test sets, training the model using the training data, evaluating the model using training and validation sets, and printing out the model's performance scores. Some models used in the analysis include Decision Tree, K-Nearest Neighbors, Random Forest, Bagging, Adaptive Boosting, and Stacking.

To learn more about this project, please visit the corresponding GitHub repository [here](https://github.com/hakhan2000/Predicting-NFL-Offensive-Plays).