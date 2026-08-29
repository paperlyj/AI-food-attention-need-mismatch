# Scopus search strategy

Raw Scopus metadata are not redistributed in this repository because of database licensing restrictions.

The manuscript search strategy was designed to capture records combining AI-related terms with food-system-related terms.

## AI-related term groups

Examples of AI-related terms used in the search and screening workflow include:

- artificial intelligence
- machine learning
- deep learning
- neural network
- computer vision
- natural language processing
- data mining
- robotics
- automation

## Food-system-related term groups

Examples of food-system-related terms used in the search and screening workflow include:

- food
- agriculture
- food production
- food security
- nutrition
- food safety
- food quality
- food processing
- food supply chain
- sustainability
- food waste
- alternative protein

## Expected export files

To reproduce the analysis, export Scopus records as CSV files and name them as follows:

- `01_scopus_ai_food_metadata_raw_part01_2010_2015.csv`
- `01_scopus_ai_food_metadata_raw_part02_2016_2021.csv`
- `01_scopus_ai_food_metadata_raw_part03_2022_2023.csv`
- `01_scopus_ai_food_metadata_raw_part04_2024.csv`
- `01_scopus_ai_food_metadata_raw_part05_2025.csv`

The notebook expects the standard Scopus export fields including title, abstract, author keywords, index keywords, publication year, source title, cited-by count, DOI, affiliations, authors with affiliations, document type, publication stage, language, and EID.

Before final publication, paste the exact Scopus Boolean query, export date, and Scopus filtering options here.
