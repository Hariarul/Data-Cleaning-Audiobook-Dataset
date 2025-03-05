## Introduction
#### Overview of the Dataset

This dataset contains audiobook details, including attributes like the book's name, author, narrator, duration, release date, language, user ratings (stars), and price. The dataset is intended for analysis and machine learning applications, such as recommendation systems or price prediction models.

#### Purpose of Data Cleaning

Raw datasets often contain inconsistencies, missing values, and formatting errors that can affect analysis and model performance. This dataset requires data cleaning and preprocessing to ensure accuracy, consistency, and usability.

## Identified Issues

The dataset contains several inconsistencies that need to be addressed:

#### Incorrect Data Types

Dates and prices are stored as strings (objects) instead of datetime and float, respectively.
Stars (ratings) are numerical but stored as objects due to formatting issues.

#### String Contamination

The author and narrator columns include extra text such as "Written by" or "Narrated by", instead of just the names.

#### Mixed Format in Time Column

The time column includes both numbers and words (e.g., "10 hours 30 minutes" instead of a standard numeric format).
