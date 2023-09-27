![Awareness-Banner](https://github.com/Datafyde/World_Hepatitis/assets/135570337/1d0b64f7-a3e4-44ad-9fdb-3459c422ec2b)

Interact with the final dashboard here:
[World Hepatitis Dashboard](http://bit.ly/viral-hepatitis-dashboard)

# Project Objectives
At the forefront of the battle against viral hepatitis and to raise awareness in commemoration of World Hepatitis Day, Datafied presents a snapshot of Viral Hepatitis showcasing both the triumphs and areas demanding intensified focus. 

# Dataset information
The data used for this project was sourced from The Polaris Observatory, an initiative of the non-profit CDA Foundation, that provides epidemiological data, modeling tools, training, and decision analytics to support eliminating Hepatitis B and C globally by 2030. The observatory offers the most up-to-date estimates for the hepatitis C virus (HCV), and hepatitis B virus (HBV) disease burden and economic impact, as well as strategies for eliminating each virus, and financing options. 

Data Source: [Polaris](https://cdafound.org/polaris/)


## Project Questions
We defined specific questions that the dashboard should answer. Example questions include:
- What is the total population?
- What is the number of prevalent cases?
- What percentage of the total population has been treated?
- What is the population to death ratio?
- How many countries were represented in this analysis?
- What is the progress made to eliminate viral hepatitis as against WHO's standard?

## Define the metrics and Key Performance Indicators (KPIs) that will help answer the business questions. 
Example metrics include:
- Death Rate
- Birth Dose Coverage
- HBIG Coverage
- Percentage of Population Treated
- Prevalence rate

## Preprocess the dataset
The dataset was cleaned by removing duplicates, correcting any inconsistencies, and ensuring the data was in a suitable format for analysis and visualization.

## Data modeling and relationships.
Dimensions with which to break down the analysis were identified. Hence, new tables for specified dimensions were created. These included:
- Indicators Table
- Countries Table
- Indicator Summary Table
- Summary Table
- Additional features were created to give more robustness to our analysis

The data model was designed using the Star Schema where the different dimensions were connected to the Facts table in a one-to-many relationship.

![Screenshot 2023-09-08 130549](https://github.com/Datafyde/World_Hepatitis/assets/135570337/5e41cf0a-f461-44ad-9de2-cd2379b9073f)

## Create visualizations and charts:
Appropriate chart types (e.g., bar charts, line charts, doughnut charts) were used to represent the metrics and insights. Interactive features such as filters were used for detailed information.

![Screenshot 2023-09-08 130314](https://github.com/Datafyde/World_Hepatitis/assets/135570337/53eb6268-1011-4c43-9d4e-0cab7dbe6250)

## Insights
- Countries continue to lag in terms of reaching relative or absolute Impact and Programmatic Targets by 2030 across all variables.
- More progress has been seen in tackling Hepatitis C. However, 3-dose vaccination coverage (Hepatitis B) has seen the most progress.
- A marked increase in successful interventions was noted, demonstrating the efficacy of targeted strategies and medical innovations.
- There is a substantial rise in 3-dose vaccination coverage, underscoring the tangible impact of healthcare initiatives.

## Recommendation
- Countries should ramp up health-care programs to meet the aim by 2030.
-Resources should be properly and strategically allocated to bridge the remaining gaps and expedite progress.

## Deployment and Documentation
Once the dashboard was finalized, it was deployed to Power BI service. The project process and deliverables are documented here on GitHub.

## Project Limitation and Future Works.
The dataset does not capture the dynamic progression of hepatitis over time. this underscores the need for a comprehensive approach that not only assesses the current situation but also tracks the evolving trends. Future work will involve incorporating a time dimension to gain a more nuanced understanding of the trajectory of Hepatitis B and C, enabling government and health organizations to make an informed decision that drives us closer to our goal of eradication.

Interact with the final dashboard here:
[World Hepatitis Dashboard](http://bit.ly/viral-hepatitis-dashboard)
