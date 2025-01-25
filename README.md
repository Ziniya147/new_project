Project Title: Quiz Performance Analyzer
Project Overview
The Quiz Performance Analyzer script ingests quiz performance data from current and historical quizzes and generates insights for improving user performance. The script:

Ingests data from two JSON endpoints.
Cleans and prepares the data for analysis.
Analyzes user performance based on accuracy and incorrect answers.
Generates recommendations for improvement based on weak areas.

Approach Description
Data Ingestion:
Fetch current and historical quiz data using the requests library from the provided JSON URLs.
Data Cleaning:
Clean columns such as accuracy and incorrect_answers to ensure numeric values.
Data Analysis:
Compute average accuracy and total incorrect answers per user.
Identify weak areas by analyzing questions with high incorrect answers.
Generate Recommendations:
Provide actionable insights based on average accuracy and weak areas.
Output:
The script prints insights and recommendations in the console.

Key Features
Dynamic analysis for multiple users.
Identification of weak areas and targeted improvement suggestions.
Easy-to-extend script for integrating more data sources or features.
