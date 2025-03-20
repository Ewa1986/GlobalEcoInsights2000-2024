
# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# GlobalEcoInsights 

The goal of this project is to provide actionable insights into the effects of climate change by identifying trends and correlations within the dataset. These insights can support policy decisions, promote sustainable practices, and increase public awareness of climate-related issues.

## Overview 
This dataset contains temperature and climate-related data for various countries over multiple years. It includes information on temperature, CO2 emissions, sea level rise, rainfall, population, renewable energy usage, extreme weather events, and forest area.

## Dataset Content -

Filename: temperature.csv
Rows: 1000
Columns: 10

#### Column Descriptions

* Year (int) - The year of the recorded data.
* Country (string) - The name of the country.
* Avg_Temperature_degC (float) - The average annual temperature in degrees Celsius.
* CO2_Emissions_tons_per_capita (float) - CO2 emissions in tons per capita.
* Sea_Level_Rise_mm (float) - Sea level rise in millimeters.
* Rainfall_mm (int) - Total annual rainfall in millimeters.
* Population (int)- The population of the country.
* Renewable_Energy_pct (float) - Percentage of total energy consumption from renewable sources.
* Extreme_Weather_Events (int) - Number of recorded extreme weather events.
* Forest_Area_pct (float) - Percentage of land area covered by forests.

## Business Requirements -

* Identify trends and correlations between variables (e.g., temperature vs. CO2 emissions, sea level rise vs. extreme weather events).
* Perform time-series analysis to observe changes over time.
* Conduct geospatial analysis to compare data across different countries.
* Create interactive dashboards and visualizations to present insights.
* Develop a user-friendly interface for stakeholders to explore data and insights.
* Ensure accessibility and ease of use for non-technical users.


## Hypothesis and Validations -

### Hypothesis 1 : Average temperature has increased over the years
  ##### Validation - Perform a trend analysis using linear regression or time series analysis on the Avg_Temperature_degC column across different years. Visualise the trend using line charts to observe any significant increase over time.

### Hypothesis 2 : Countries with a higher percentage of renewable energy have lower CO2 emissions.
   ##### Validation - Conduct a correlation analysis between Renewable_Energy_pct and CO2_Emissions_tons_per_capita. A negative correlation would support the hypothesis. Additionally, scatter plots and regression models can further confirm the relationship.

### Hypothesis 3 : A decrease in forest area percentage leads to an increase in extreme weather events.
  ##### Validation - Perform a comparative analysis using Forest_Area_pct and Extreme_Weather_Events data. Use correlation analysis and visualize the results using scatter plots. A significant negative correlation would support this hypothesis.

### Hypothesis 4 : Higher population growth contributes to increased CO2 emissions and rising sea levels.
  ##### Validation - Analyse the relationship between Population, CO2_Emissions_tons_per_capita, and Sea_Level_Rise_mm using multiple regression analysis. Evaluate the strength of the relationships through coefficients and significance levels.

## Project Plan
#### Step 1: Data Collection
 * Collect temperature and climate-related data from reliable sources for educational studies like Kaggle source.
 * Ensure the data covers a diverse set of countries over multiple years for comprehensive analysis.

#### Step 2: Data Cleaning
 * Perform data cleaning to handle missing values, outliers, or inconsistent data.
 * Standardise data formats and convert units if necessary.
 * Store the cleaned data in a structured format using CSV or database systems for easy access.

#### Step 3: Data Analysis
 * Conduct exploratory data analysis (EDA) to identify trends, patterns, and correlations.
 * Apply statistical analysis, including linear regression, correlation analysis, and hypothesis testing.
 * Create visualisations using libraries like Matplotlib,Plotly or Seaborn to enhance interpretation.

#### Step 4: Interpretation and Insights
 * Evaluate the analysis results to confirm or refute the proposed hypotheses.
 * Identify actionable insights and trends in temperature changes, CO2 emissions, renewable energy impact, and forest area changes.

#### Step 5: Visualisation and Documentation
 * Document findings using visual reports, Tableau dashboards and presentations.
 * Provide recommendations based on the analysis to inform policy decisions and sustainable practices.

### Research Methodology
 * Trend Analysis: Used to identify long-term temperature changes over the years.
 * Correlation Analysis: Applied to measure the strength and direction of relationships between variables such as renewable energy usage and CO2 emissions.
 * Regression Models: Implemented to predict outcomes based on independent variables like population growth and CO2 emissions.
 * Comparative Analysis: Used to evaluate how forest area percentage influences extreme weather events.

## The rationale to map the business requirements to the Data Visualisations
* List your business requirements and a rationale to map them to the Data Visualisations

## Analysis techniques used
* List the data analysis methods used and explain limitations or alternative approaches.
* How did you structure the data analysis techniques. Justify your response.
* Did the data limit you, and did you use an alternative approach to meet these challenges?
* How did you use generative AI tools to help with ideation, design thinking and code optimisation?

## Ethical considerations
* Were there any data privacy, bias or fairness issues with the data?
* How did you overcome any legal or societal issues?

## Dashboard Design
* List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other item that your dashboard library supports.
* Later, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project you were confident you would use a given plot to display an insight but subsequently you used another plot type).
* How were data insights communicated to technical and non-technical audiences?
* Explain how the dashboard was designed to communicate complex data insights to different audiences. 

## Unfixed Bugs
* Please mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
* Did you recognise gaps in your knowledge, and how did you address them?
* If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 

## Deployment
### Heroku

* The App live link is: https://YOUR_APP_NAME.herokuapp.com/ 
* Set the runtime.txt Python version to a [Heroku-20](https://devcenter.heroku.com/articles/python-support#supported-runtimes) stack currently supported version.
* The project was deployed to Heroku using the following steps.

1. Log in to Heroku and create an App
2. From the Deploy tab, select GitHub as the deployment method.
3. Select your repository name and click Search. Once it is found, click Connect.
4. Select the branch you want to deploy, then click Deploy Branch.
5. The deployment process should happen smoothly if all deployment files are fully functional. Click now the button Open App on the top of the page to access your App.
6. If the slug size is too large then add large files not required for the app to the .slugignore file.


## Main Data Analysis Libraries
* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.


## Credits 

* In this section, you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 
* You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign-up page are from This Open-Source site
- The images used for the gallery page were taken from this other open-source site



## Acknowledgements
* Thank the people who provided support through this project.