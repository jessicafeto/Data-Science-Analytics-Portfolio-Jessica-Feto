# Applied Data Science Capstone

This Capstone is the 10th and final course in the IBM Data Science Professional Certificate specialization. It summarizes the materials learned throughout the specialization in the form of a project.

## Project Background

SpaceX has become the most successful company in the commercial space industry by making space travel more affordable. The company advertises Falcon 9 rocket launches on its website at a cost of 62 million dollars, while other providers charge upwards of 165 million dollars. Much of the cost savings is due to SpaceX's ability to reuse the rocket's first stage. By predicting whether the first stage will land successfully, we can estimate the cost of a launch. In this project, based on publicly available information and machine learning models, we will predict if SpaceX can reuse the first stage of its rockets.

## Questions to be Answered

- How do variables such as payload mass, launch site, number of flights, and orbit affect the success of the first stage landing?
- Does the rate of successful landings increase over the years?
- What is the best algorithm for binary classification in this case?

## Methodology

1. **Data Collection**:
   - Using SpaceX's REST API
   - Web scraping from Wikipedia

2. **Data Wrangling**:
   - Filtering the data
   - Handling missing values
   - Applying One-Hot Encoding to prepare the data for binary classification

3. **Exploratory Data Analysis (EDA)**:
   - Conducted EDA using visualization techniques and SQL queries

4. **Interactive Visual Analytics**:
   - Used Folium for mapping and Plotly Dash for interactive data analysis

5. **Predictive Analysis**:
   - Built, tuned, and evaluated classification models to identify the best performing model for predicting the success of the first stage landing.
