# Analysis of Fuel Consumption Ratings and Carbon Dioxide Emissions for Light-Duty Vehicles in Canada

This project focused on analyzing a dataset containing model-specific fuel consumption ratings and estimated carbon dioxide emissions for new light-duty vehicles sold in Canada. The goal was to gain insights into the fuel efficiency and environmental impact of these vehicles and provide a basis for comparing different models across various model years.

The analysis began with an exploratory data analysis (EDA), which involved loading the dataset and conducting various visualizations and statistical summaries. The EDA included examining the distribution of the target variable (carbon dioxide emissions), exploring the distributions of numerical features (such as engine size and fuel consumption measures), and analyzing the relationships between variables through correlation analysis.

Additionally, the dataset provided adjusted fuel consumption ratings for vehicles from 1995 to 2014, reflecting 5-cycle testing. While these adjusted values were approximations derived from the original ratings rather than actual vehicle testing, they still served as valuable indicators for comparative analysis.

Furthermore, a Support Vector Regression (SVR) model was built to predict carbon dioxide emissions based on relevant features. The dataset was split into training and testing sets, and the SVR model was trained on the training data. Predictions were made on the test set, and the model's performance was evaluated using mean squared error and R2 score.

Overall, this project provided insights into the fuel efficiency and environmental impact of light-duty vehicles in Canada. By analyzing the dataset and building an SVR model, it aimed to contribute to the understanding of vehicle emissions and assist in making informed decisions regarding fuel consumption and environmental sustainability in the automotive industry.
