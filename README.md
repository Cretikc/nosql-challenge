NoSQL Challenge
Project Overview
In this challenge, the food hygiene rating data for UK restaurants was analyzed to assist the editors and journalists of Eat Safe, Love, a food magazine. The goal was to identify key insights and trends to help them decide where to focus future articles and reviews.

Methodology
Part 1: Database Setup and Initial Analysis
Used MongoDB to store and analyze food hygiene ratings across the UK.
Employed PyMongo to interact with MongoDB and pprint to display documents in a readable format within Python.
Verified the database setup by listing available databases and collections and retrieving sample documents.
Part 2: Database Modifications and Data Cleaning
Added new restaurant ratings, including the newly opened Halal restaurant in Greenwich.
Filtered restaurants by location using latitude and longitude to refine results.
Converted string values to numerical types to facilitate accurate analysis.
Removed specific establishments based on location and confirmed their deletion before proceeding.
Part 3: Data Analysis and Insights
Conducted query analysis to identify top-scoring establishments based on:
Hygiene ratings
Structural compliance
Confidence in management
Extracted key insights to provide Eat Safe, Love magazine editors with data-driven recommendations for their next articles.

Conclusion
This project successfully leveraged NoSQL databases and data analysis techniques to assist food journalists in making informed editorial decisions. The structured approach ensured data integrity, accuracy, and relevance for future reporting.