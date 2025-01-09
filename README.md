
Cardiovascular diseases are among the leading causes of death worldwide. Identifying the key risk factors that contribute to these conditions can help us make informed decisions about prevention and treatment. In this project, we analyzed medical data to uncover patterns and relationships between lifestyle choices, medical conditions, and cardiovascular disease. This article presents the findings in a simple and accessible manner, ensuring that even non-technical readers can follow along.

The Data
The dataset used in this project contains medical examination results, including measurements like height, weight, blood pressure, and cholesterol levels, as well as lifestyle information such as smoking, alcohol consumption, and physical activity. Each record also indicates whether the individual has cardiovascular disease.

To gain meaningful insights, the data was cleaned and processed to add useful information and remove inconsistencies. For example, we calculated whether an individual is overweight based on their Body Mass Index (BMI). We also normalized certain medical variables like cholesterol and glucose levels so that “good” values are represented as 0 and “bad” values as 1.

Visualizing the Data
To make the data easier to interpret, we created two key visualizations: a categorical plot and a heatmap.

The Categorical Plot
This plot compares six key factors (“cholesterol,” “glucose,” “smoke,” “alco,” “active,” and “overweight”) for people with and without cardiovascular disease. The chart is divided into two sections: one for individuals without cardiovascular disease (“cardio=0”) and one for those with the condition (“cardio=1”). Each bar represents the total number of people with either “good” (value=0) or “bad” (value=1) levels for each factor.

Key Findings from the Categorical Plot:

Cholesterol and Glucose: High levels of these indicators are more common in individuals with cardiovascular disease.

Lifestyle Factors: Smoking and alcohol consumption are slightly more frequent among those with the condition, and physical inactivity is also noticeable.

Overweight: A significant number of people with cardiovascular disease are overweight.

The Heatmap
The heatmap visualizes the relationships between different variables in the dataset. It uses colors to show the strength of these relationships, with darker colors representing weaker correlations and lighter colors representing stronger ones.

Key Findings from the Heatmap:

Blood Pressure: Systolic (higher) and diastolic (lower) blood pressure are strongly correlated, as expected.

Height and Weight: Taller individuals tend to weigh more, which is also logical.

Cholesterol and Glucose: These variables show a moderate correlation with cardiovascular disease, highlighting their role as important risk factors.

Weak Relationships: Most other variables show little to no direct relationship with each other.

Conclusions and Recommendations
This analysis confirms some well-known risk factors for cardiovascular disease and offers new perspectives on their relationships. Key takeaways include:

Maintaining healthy cholesterol and glucose levels is crucial for reducing cardiovascular risk.

Lifestyle choices like staying physically active and avoiding smoking and alcohol can make a significant difference.

Addressing overweight and obesity should be a priority for cardiovascular health.

For further exploration, the insights from this analysis could be used to build predictive models for cardiovascular disease risk. Such models can assist healthcare professionals in identifying high-risk individuals early and taking preventive action.

Final Thoughts
By combining data visualization techniques with medical knowledge, this project demonstrates how data can guide us toward better health outcomes. Whether you’re a healthcare professional, a researcher, or simply someone interested in your own health, understanding these patterns can empower you to make smarter decisions about your well-being.
