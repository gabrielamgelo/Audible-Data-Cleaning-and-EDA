# Audible Data Cleaning and EDA
The focus of this project is primarily on data cleaning, and then performing Exploratory Data Analysis on an Audible dataset found on kaggle. The dataset used can be found [here](https://www.kaggle.com/datasets/snehangsude/audible-dataset?select=audible_uncleaned.csv)
___
# *Here you'll find a simplified overview and explanation of what was done, the full project is available in the Jupyter Notebook file*.

## Technologies Used:


    Language: Python
    Python Libraries:
    Pandas: Used for data cleaning, manipulation and analysis
    Matplotlib & Seaborn: Used for visualizations.
    Jupyter Notebook: Used or interactive data exploration.

The repository contains:

• audible_uncleaned.csv: The dataset used.

• notebook.ipynb: The jupyter notebook containing the analysis

# OVERVIEW:

## 1- Data Validation:

In this step, the data was loaded and explored to find incorrect, mispelled, duplicated, or missing values. Then the data was treated and cleaned accordingly using various functions from the Pandas library.

**Standardizing the Values in the 'author' Column**

![Captura de tela 2025-01-15 201715](https://github.com/user-attachments/assets/78fcbff1-b532-4966-8041-c8d978348a43)

**Standardizing the Values in the 'narrator' Column**

![Captura de tela 2025-01-15 202028](https://github.com/user-attachments/assets/62c3a4a2-a2df-429e-beed-8d548550c883)

**Standardizing the Values in the 'releasedate' Column**

![Captura de tela 2025-01-15 202120](https://github.com/user-attachments/assets/3736a6ca-2cee-4f2a-81f3-624e19491a7f)

**Standardizing the Values in the 'time' Column**

![Captura de tela 2025-01-15 202212](https://github.com/user-attachments/assets/6d4df78e-9a9f-4496-9a29-8194c3e44f5a)

**Creating 'nb_ratings' Columns**

![Captura de tela 2025-01-15 202321](https://github.com/user-attachments/assets/0e5547a5-eabd-4dfd-9313-f2d3d459c3d0)

**Standardizing the Values in the 'stars' Column**

![Captura de tela 2025-01-15 202410](https://github.com/user-attachments/assets/6440f39c-e904-49d2-9f07-b62df371bace)

![Captura de tela 2025-01-15 202603](https://github.com/user-attachments/assets/20242650-7c78-4018-a5da-1dcb352672da)

**Standardizing the Values in the 'price' Column**

![Captura de tela 2025-01-15 202523](https://github.com/user-attachments/assets/619a4dd4-3381-4340-8e33-fc86b880d658)

## 2- Exploratory Analysis:

**Top 10 Languages with the Most Books:**

Here we can see that the most common langua for books in this dataset is english, with over 61k books written in english. Portuguese (my native language), is in the 8th spot, with 526 books.

![Captura de tela 2025-01-15 202830](https://github.com/user-attachments/assets/d76f8dde-7f8e-4b57-b851-d1975bf1a2e3)

**Spread of releases by date**

In this graph we can see the huge spike of book releases on Aubible starting around 2020.

![Captura de tela 2025-01-15 203512](https://github.com/user-attachments/assets/94987611-2b19-4aa5-b09a-b7a19fd2ab47)

**Correlation Between Columns**

No significant correlations between variables are really noticeable. The highest ones are the correlation between author and price (0.21), and price and stars (0.18). 

![Captura de tela 2025-01-15 203632](https://github.com/user-attachments/assets/d3d3550a-19f7-40f9-94b0-33ac33ba1d21)

**Top 20 Books With the Most Ratings**

This graph shows the combination of the books with the highest number of ratings and their ratings in stars. As we can see, the title Atomic Habits has the most and best ratings between all other titles. And then there is Ikigai, which is the opposite, having the most and worst ratings of all titles.

![Captura de tela 2025-01-15 203714](https://github.com/user-attachments/assets/257d0c30-38ac-4e6a-af47-e598f7572719)

**Top 20 Most Rated Books With 5 Stars**

This one shows the books with the most number of 5 star ratings. Atomic Habits is by far the best rated book, followed by Sapiens and harry Potter.

![Captura de tela 2025-01-15 203752](https://github.com/user-attachments/assets/fba07671-2849-4d0e-aac2-a4cc968535cc)

**Top 10 Authors With the Most Titles**

Here we can see that 矢島雅弘,石橋遊 has the highest number of releases, with 874 books. Attention to Shakespeare in 5th place, having 201 releases, that is due to most of them being different translations and narrations of his books.

![Captura de tela 2025-01-15 203914](https://github.com/user-attachments/assets/22633fcd-1c51-4cd8-9a03-b8ec13d950cf)

**Top 10 Authors With the Most 5 Stars Ratings**

In this last graph we can see the authors with the most 5 stars ratings, and David Goggins, who is an ex-SEAL and is a motivational speaker/influencer, is in 1st place by a huge margin.

![Captura de tela 2025-01-15 203957](https://github.com/user-attachments/assets/f83fdcdc-60de-43e1-9624-2c097ad75e23)
