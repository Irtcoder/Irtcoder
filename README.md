# Netflix Content Strategy Analysis

## 📌 Project Overview

This project analyzes the Netflix titles dataset to uncover patterns in Netflix's content catalog and understand how content varies across **time, content type, country, and genre**.

Rather than focusing only on common exploratory analysis such as the number of movies and TV shows, this project introduces a **Release-to-Netflix Gap** metric to investigate the time difference between a title's release year and the year it was added to Netflix.

The analysis explores whether Netflix follows different content distribution patterns across countries, genres, and content types.

## 🎯 Objectives

- Analyze the overall composition of Netflix's content catalog.
- Compare Movies and TV Shows.
- Study content release trends over time.
- Analyze Netflix's content addition trends.
- Investigate the time gap between release and Netflix availability.
- Compare this gap across Movies and TV Shows.
- Identify country-level differences in content availability.
- Analyze genre-level differences in the release-to-Netflix gap.
- Explore country–genre combinations to identify distinctive content patterns.
- Investigate India's content patterns separately.

## ⭐ Key Feature: Release-to-Netflix Gap

A key feature engineered during the project is:

Release-to-Netflix Gap = Year Added to Netflix − Release Year

This metric helps investigate how quickly or slowly different types of content appeared on Netflix relative to their recorded release year.

The analysis also considers the **median gap** alongside the mean to reduce the influence of extreme values.

## 🔍 Key Analysis

The project investigates questions such as:

1. Does Netflix add Movies and TV Shows at different points relative to their release?
2. Which genres tend to have larger release-to-Netflix gaps?
3. How does the gap vary across countries?
4. Which country–genre combinations show unusually large gaps?
5. Are some content categories dominated by older titles?
6. How does India's content acquisition pattern differ across genres?
7. What can these patterns tell us about Netflix's content strategy?

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📊 Dataset

The dataset contains information about Netflix titles, including:

- Show ID
- Type
- Title
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Genre
- Description

## 🧹 Data Preparation

The project includes:

- Duplicate detection
- Missing-value analysis
- Datetime conversion
- Feature engineering
- Country normalization
- Genre normalization
- Exploding multi-value categorical columns
- Data-quality checks
- Handling of negative release-to-Netflix gaps

## 📈 Visualizations

The analysis includes:

- Movies vs TV Shows distribution
- Release-year trends
- Netflix content addition trends
- Genre distribution
- Release-to-Netflix gap analysis
- Country-level comparisons
- Genre-level comparisons
- Country × Genre heatmap

## 💡 Key Insight

One of the notable findings is that the release-to-Netflix gap differs substantially across content types and country–genre combinations.

For Indian content, for example, **Music & Musicals and Action & Adventure** show relatively high median release-to-Netflix gaps, while some TV categories show much smaller gaps.

This suggests that Netflix's catalog composition and timing of content availability can vary significantly depending on the type, country, and genre of content.

## 🚀 Future Improvements

- Build an interactive Power BI dashboard.
- Perform statistical testing of country and genre differences.
- Analyze director and cast networks.
- Investigate temporal changes in Netflix's international content strategy.
- Develop predictive models for content addition patterns.

## 👤 Author

**Irtefa Alam**

Data Analytics | Python | Mathematics | Data Science
