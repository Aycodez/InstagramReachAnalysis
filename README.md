# Instagram Reach Analysis Project

![Instagram Reach Analysis]

## Overview

This project focuses on analyzing the factors influencing the reach of Instagram posts. By exploring various features and their relationships, we aim to gain insights into the dynamics of post reach on the platform. Additionally, a GradientBoostRegressor model is trained with the data to predict the reach of an Instagram post based on the identified features.

## Table of Contents

- [Objective](#objective)
- [Features](#features)
- [Data Collection](#data-collection)
- [Data Analysis](#data-analysis)
- [Modeling](#modeling)
- [Results](#results)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Objective

The primary goal of this project is to understand and analyze the factors that contribute to the reach of Instagram posts. By leveraging data analysis and machine learning techniques, we aim to build a predictive model that can estimate the potential reach of a post based on its features.

## Features

The following features are considered in the analysis:

- **Caption Length**: The length of the caption accompanying the post.
- **Hashtags**: The number of hashtags used in the post.

- **Impressions**: From Home,Explore and others.
- **Engagement Metrics**: Likes, comments, and shares received by the post.

## Data Collection

To conduct the analysis, a dataset containing relevant information about Instagram posts was collected. The dataset includes data on various features such as captions, hashtags, likes, and engagement metrics. The data was obtained through the Instagram API and anonymized for privacy.

## Data Analysis

Exploratory data analysis (EDA) was performed to uncover patterns, correlations, and trends within the dataset. Visualization techniques and libraries like matplotlib,pands and plotly were employed to illustrate the relationships between different features and the reach of the posts.

## Modeling

A GradientBoostRegressor model was chosen for its ability to capture complex relationships within the data. The model was trained using the labeled dataset, and hyperparameter tuning was performed to optimize its performance.

## Results

The trained model demonstrates promising results in predicting the reach of Instagram posts. Evaluation metrics such as Mean Squared Error (MSE) and R-squared were used to assess the model's accuracy.

## Usage

To use the project:

1. Clone the repository: `git clone https://github.com/Aycodez/InstagramReachAnalysis.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the analysis script: `python InstagramReachanalysis.ipynb`

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
