# 🏅 Nobel_Prize_Analysis

Hello! In this part of my Research Notebook, I am looking into a dataset of Nobel Prize laureates from 1901 to 2020. My analysis covers data cleaning and feature engineering and also uses visualisations to answer different questions regarding gender distribution, repeat winners, and prize categories.


## Information about the Dataset

File: nobel_prize_data.csv

Shape: 962 rows × 16 columns

Key columns:

- year, category, prize, motivation, prize_share

- laureate_type (Individual / Organisation)

- full_name, birth_date, birth_city, birth_country, birth_country_current

- sex, organization_name, organization_city, organization_country, ISO


## Usage

1. Place nobel_prize_data.csv in the same directory as the notebook.

2. Open in Jupyter or Google Colab.

3. Run all cells sequentially (Runtime → Run all in Colab).

Simple as that!


## Key Findings

Here are some of the findings I made during the analysis:

- Gender gap: Of 934 laureates with recorded sex, 876 are male (~93.8%) and 58 are female (~6.2%).

- First female laureates:
Marie Curie (Physics, 1903)
Bertha von Suttner (Peace, 1905)
Selma Lagerlöf (Literature, 1909)

- Repeat winners: 6 laureates were awarded the prize more than once:
Marie Curie (Physics 1903, Chemistry 1911)
Linus Carl Pauling (Chemistry 1954, Peace 1962)
John Bardeen (Physics 1956, 1972)
Frederick Sanger (Chemistry 1958, 1980)
International Committee of the Red Cross (Peace 1917, 1944, 1963)
UN High Commissioner for Refugees (Peace 1954, 1981)

- Categories: 6 unique prize categories.


## Credits

Inspired by Day 79 of the course "100 Days of Code: The Complete Python Pro Bootcamp".

The project idea, structure, and learning path came from the course. The code in this repository was written by me as I followed along, and I have added my own comments and questions along the way.


### 💬 P.S. No Nobel Prizes were harmed in the making of this notebook. Several were, however, counted, sorted, and mildly judged.
