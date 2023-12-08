# COSMETICS ANALYZER and RECOMMENDER

### tl;dr- This project employs advanced data science techniques, including content-based recommendation systems, t-SNE dimensionality reduction, and Bokeh visualizations, to predict optimal cosmetics based on individual skin types and ingredients.

## Abstract

Many people in the recent day and age suffer from the dilemma of which cosmetic product to use for their skin. The cosmetic products they choose are mostly based on their skin type, allergies, etc. This project delves into the domain of cosmetic product optimization, employing advanced data science methodologies to predict ideal ingredients for individualized skincare regimens. Leveraging a content-based recommendation system, this initiative aims to enhance the precision of cosmetics selection by scrutinizing 1472 products from the Sephora dataset.

## Methodology

The content-based recommendation system relies on intricate word embedding techniques to process ingredient lists. The subsequent utilization of t-SNE, a machine learning dimensionality reduction algorithm, in conjunction with the Bokeh library for interactive visualization, facilitates an in-depth exploration of ingredient similarity landscapes.

## Exploratory Data Analysis (EDA)

A preliminary Exploratory Data Analysis (EDA) precedes machine learning endeavors, unraveling nuanced insights. Comprehensive analyses of product ratings and multifaceted features empower users with the ability to discern and select products aligned with their distinct preferences.

## Skin Typology Examination

The classification of skin types into dry, normal, oily, combination, and sensitive undergoes a rigorous analysis. Each typology is characterized by unique attributes and necessitates specific product formulations. For instance, combination skin presents a duality of oily and dry regions. The EDA scrutinizes intricate facets such as price distributions, ratings, and categorical preferences germane to specific skin types.

## Tokenization of Ingredients

To facilitate granular ingredient-level comparisons, a meticulous tokenization process is instituted. This involves the creation of a binary bag-of-words representation, discerning the presence or absence of ingredients in cosmetic formulations. Initialization of a document-term matrix (DTM) forms the bedrock for subsequent in-depth analyses.

## Bokeh Visualization

The visualization framework is fortified with the deployment of the Bokeh library, orchestrating the reduction of DTM dimensions using t-SNE. T-distributed Stochastic Neighbor Embedding, a sophisticated nonlinear dimensionality reduction methodology, is harnessed to map high-dimensional data onto a two-dimensional space. This transformative approach elucidates intricate ingredient similarities among cosmetic products.

## Conclusion

This project provides a sophisticated toolkit comprising detailed analyses and intricate visualizations, arming consumers with the requisite insights to navigate the complex terrain of cosmetic products tailored to their individualized skincare needs.

## Future Scope

I plan to make an ETL Pipeline to fetch product data from Nykaa and extract the ingredient data of the products. Furthermore, I plan to make a microservice of this model which could be pinged to analyze if a given product would be suitable for a particular user's skin persona.
