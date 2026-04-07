# Fruit Nutritional Analysis

## Overview
A data analysis project that pulls nutritional data from the Fruityvice API 
and calculates key dietary ratios to help individuals make more informed 
fruit choices for a balanced diet.

## Research Question
Which fruits and fruit families have the most balanced calorie-to-sugar and 
calorie-to-carbohydrate ratios?

## Data Source
Fruityvice API — nutritional data including calories, sugar, carbohydrates, 
fat, and protein per 100g for a variety of fruits

## Tech Stack
- Python
- Pandas
- Matplotlib
- Requests
- Google Colab / Jupyter Notebook

## Analysis Approach
1. Sent HTTP GET request to Fruityvice API using the Python requests library
2. Parsed nested JSON data using json_normalize()
3. Cleaned DataFrame by dropping irrelevant columns
4. Calculated two key ratios:
   - Cal-to-Sugar Ratio = Calories per 100g / Sugar per 100g
   - Cal-to-Carb Ratio = Calories per 100g / Carbohydrates per 100g
5. Visualized results using bar charts by fruit and fruit family

## Key Findings
- Avocados, horned melon, and hazelnuts had the highest calorie-to-sugar ratios
- Betulaceae and Lauraceae fruit families had the highest calorie-to-sugar ratios
- Tomatoes, avocados, and hazelnuts had the highest calorie-to-carbohydrate ratios
- Strawberries, bananas, and grapes offer more balanced calorie-to-sugar ratios
- Lychee, guava, and persimmon are good options for balanced calorie-to-carb ratios

## Limitations
- Analysis relies solely on Fruityvice API data which may not be fully 
  comprehensive or current
- Lesser-known fruits may be omitted introducing potential bias
- Human error during preprocessing could affect results

## Note
This was a collaborative academic project.
