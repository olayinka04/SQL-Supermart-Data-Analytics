# SQL-Supermart-Data-Analytics

> **This case study can be found in the [SQL Masterclass: SQL for Data Analytics](https://starttechacademy.com/resources-data-analytics-with-sql/) course made by [Start-Tech Academy].**

# Table of contents
- [🏩About](#about)
- [📋 Requirements](#-requirements)
  - [📜 Requirement #1: Top 2 Categories](#-requirement-1-top-2-categories)
  - [📜 Requirement #2: Category Film Recommendations](#-requirement-2-category-film-recommendations)
  - [📜 Requirements #3 & #4: Individual Customer Insights](#-requirements-3--4-individual-customer-insights)
  - [📜 Requirement #5: Favorite Actor Recommendation](#-requirement-5-favorite-actor-recommendation)
- [🔎 Data Exploration](#-data-exploration)
- [⚙️ Problem Approach](#️-problem-approach)
- [🔗 Join Implementation](#-join-implementation)
    - [Part 1](#part-1)
    - [Part 2](#part-2)
- [🛠 Problem Solving](#-problem-solving)
- [🎡 Final Output](#-final-output)

# 🏩About
The Supermart Store Co asked for our support in the investigation of the store sales growth, discount performance, customer retention, customer preference and product contributions. The team needed to generate the necessasary results required to recommend or advise the store to make a data driving decisions for the next year campaign.

# 📜 Requirements
The supermart management team shared with us database of the store, consisting of the product table, Customer table and the sales table they have generated over the years.
- Table 1
> ** The Customer table consisting of 9 columns, showing customers name, age, country, state, city etc
![customer](https://user-images.githubusercontent.com/78763866/141340618-09931416-6649-46fa-a1b5-b123e73d3855.PNG)
- Table 2
> ** The customer product table consisting of 4 columns showing product ID, Product category, product sub-category and product name
![product](https://user-images.githubusercontent.com/78763866/141340915-9de486b1-1fe7-4d65-8896-39d46e3f57d9.PNG)
- Table 3
> ** The customer Sale table consisting of 11 columns showing order line, order date, ship date, customer ID, product ID and sales etc.
The Customer table from the ERD were explored in the link below.
![sales](https://user-images.githubusercontent.com/78763866/141340942-f201a75d-60de-44ef-8aa5-55f2795abb82.PNG)

# 🔎 Data Exploration

The analytics team provided an entity-relationship diagram (ERD).

![ERD shema](https://user-images.githubusercontent.com/78763866/141362355-8b823d73-4d39-48bb-9c03-f530ab8b7a82.PNG)
