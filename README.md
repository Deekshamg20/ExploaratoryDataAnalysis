📊 Exploratory Data Analysis on Social Media Usage

This project focuses on performing Exploratory Data Analysis (EDA) on survey data about social media usage. With the growing influence of platforms such as Instagram, WhatsApp, Facebook, Twitter, and TikTok, understanding how people use these platforms is crucial for businesses, researchers, and policymakers. 
Social media has become an integral part of modern communication, marketing, and even political engagement, making it essential to analyze patterns of usage across different demographics.

The dataset used in this project is primary data collected through surveys from 78 individuals, including friends, family, and classmates. The respondents range in age from 18 to 63 years, with most being students and working professionals. Key survey details include demographics, device preferences, platform choices, time spent, and perceived impacts of social media. Smartphones emerged as the dominant device, while Instagram and WhatsApp were found to be the most popular platforms.

The analysis begins with data inspection and cleaning, including identifying missing values and understanding column data types. It then progresses to univariate analysis, which examines gender and occupation distributions, number of platforms used, average time spent, and perceived impacts (positive, negative, or mixed). Bivariate analysis further explores relationships such as age versus time spent, platform preferences by gender, and the impact of social media on mental health across groups. Multivariate analysis uses correlation heatmaps and pairplots to identify interrelationships among variables.

Additionally, the project employs advanced analysis techniques, such as K-means clustering, to segment users into distinct groups based on their usage behavior. The elbow method is applied to determine the optimal number of clusters, ensuring meaningful groupings of engagement patterns.

The insights derived from this project reveal meaningful trends in user behavior, highlight demographic differences in platform usage, and provide a foundation for deeper behavioral or predictive analysis. These findings can help marketers design targeted campaigns, developers enhance user experience, and researchers assess the social and psychological impact of social media.

📌 Project Overview

This project performs an Exploratory Data Analysis (EDA) on survey data collected from 78 participants to understand patterns of social media usage. The analysis focuses on demographics, platform preferences, time spent, and mental health impact.

The goal is to uncover insights that can help marketers, developers, and researchers understand user behavior and design better strategies.

📂 Dataset

Source: Primary dataset collected through surveys (friends, family, and classmates).

Size: 78 responses

Features include:

Demographics (Age, Gender, Occupation, Education Level, Location)

Devices used for accessing social media

Time spent daily on social media

Number of platforms used

Most-used platform (Instagram, WhatsApp, Facebook, etc.)

Perceived impact (positive, negative, mixed)

Mental health impact

🛠️ Code Description

The code in this repository is implemented in Python (Jupyter Notebook) and includes the following steps:

1. Data Inspection & Cleaning

Load dataset (.csv)

Check shape, column names, missing values

2. Univariate Analysis

Gender distribution

Occupation distribution

Platforms used & time spent

Perceived impact types

3. Bivariate Analysis

Age vs. time spent

Occupation vs. time spent

Platform usage by gender

Mental health impact by age

4. Multivariate Analysis

Correlation heatmap

Pairplots for numerical features

5. Advanced Analysis

K-means clustering to group users by usage patterns

Elbow method to find optimal number of clusters

📈 Results & Insights

Smartphones are the primary device for accessing social media.

Instagram & WhatsApp are the most popular platforms.

Time spent varies significantly by age and occupation.

Clustering reveals distinct user groups based on engagement levels.

Social media has mixed impacts on mental health.
