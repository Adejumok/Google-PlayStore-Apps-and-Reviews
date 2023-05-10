# Google-PlayStore-Apps-and-Reviews
This project did a comprehensive analysis of the Android app market by comparing over ten thousand apps in Google Play across different categories. It gives insights to the data to devise strategies to drive growth and retention.

## Introduction

In this project, we analyze data using Python to gain insights and answer questions. They include:
- How do all these apps perform on an average?
- Does the size of an app affect its rating?
- Do users really care about system-heavy apps or do they prefer light-weighted apps?
- Does the price of an app affect its rating?
- Are paid apps installed as much as free apps?
- How do people feel about the Google Play Store product, brand, or service? This can be done using a technique called sentiment analysis.
We use Jupyter Notebook to write our code and present our findings.

## Data

The data used in this project is a CSV file containing data from Google Play Store applications and reviews. We import the data into our notebook and clean it as needed.

## Analysis

We start by exploring the data and understanding its structure. We then use various Python libraries such as Pandas, Numpy, and Matplotlib to analyze the data and visualize our findings. We perform various data analysis tasks such as:

- Data cleaning and preparation
- Data exploration
- Data visualization
- Data modeling and prediction

## Results

We present our findings in this section using various visualizations such as graphs, charts, and tables. We also provide insights and interpretations of the data and answer the questions we set out to explore in the introduction.

## Conclusion
- From our research, we found that the average volume of ratings across all app categories is 4.17.
- We find that the majority of top rated apps (rating over 4) range from 2 MB to 20 MB. 
- We also find that the vast majority of apps price themselves under $10.
- It turns out that paid apps have a relatively lower number of installs than free apps, though the difference is not as stark as would have been expected.
- By plotting sentiment polarity scores of user reviews for paid and free apps, we observe that free apps receive a lot of harsh comments, as indicated by the outliers on the negative y-axis. Reviews for paid apps appear never to be extremely negative. This may indicate something about app quality, i.e., paid apps being of higher quality than free apps on average. The median polarity score for paid apps is a little higher than free apps, thereby syncing with our previous observation.

## Dependencies

This project requires the following Python libraries:

- Pandas
- Numpy
- Matplotlib
- Seaborn

To install these libraries, run the following command:

```
!pip install pandas numpy matplotlib seaborn
```

## Usage

To use this project, clone the repository and run the Jupyter Notebook file in your local environment. Make sure to have the required dependencies installed.

## Credits

This project is a DataCamp Intermdiate Python Project
