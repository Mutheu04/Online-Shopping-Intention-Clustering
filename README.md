# Online Shoppers Purchasing Intention – Customer Behaviour Clustering

## Overview
This project applies unsupervised machine learning techniques to identify patterns in online shopping behaviour. Using the Online Shoppers Purchasing Intention dataset from the UCI Machine Learning Repository, clustering algorithms are used to group website visitors based on their browsing activity during a session.

The goal is to discover meaningful customer segments that exhibit different browsing behaviours and purchasing tendencies.

## Dataset
Source: UCI Machine Learning Repository  
Records: 12,330 browsing sessions  
Features: 18 behavioural variables

Each record represents a single user session on an e-commerce website and includes information such as:

- Number of administrative, informational, and product-related pages visited
- Time spent on different page categories
- Bounce rate and exit rate
- Traffic source
- Visitor type (returning or new)
- Month of visit

Target variable:
Revenue (True/False indicating whether a purchase occurred).  
Although clustering is unsupervised and does not use this label during training, it is used afterwards to analyse differences between clusters.

## Objective
The objective of this project is to apply clustering techniques to identify distinct groups of online shoppers based on their browsing behaviour. By analysing session patterns such as time spent on pages, interaction levels, and traffic characteristics, the analysis aims to reveal behavioural segments that differ in their likelihood of making a purchase.

## Methodology

### Data Exploration
- Dataset structure inspection
- Feature distribution analysis
- Identification of behavioural patterns in user sessions

### Data Preprocessing
- Handling categorical variables through encoding
- Feature scaling to normalise numerical attributes
- Preparing data for clustering algorithms

### Clustering Techniques
Unsupervised learning methods are applied to group similar browsing sessions.

Models explored include:
- K-Means Clustering
- Agglomerative Hierarchical Clustering

### Cluster Analysis
Clusters are analysed to understand behavioural differences between groups of shoppers. The Revenue variable is used to interpret how purchase behaviour differs across clusters.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Ethical Considerations
- The dataset contains no personally identifiable information.
- All records represent anonymised session-level behaviour.
- The analysis focuses on aggregated behavioural patterns rather than individual user profiling.

## Conclusion
The analysis demonstrates that clustering techniques can uncover meaningful behavioural segments among online shoppers. These insights can help businesses better understand customer engagement patterns and tailor marketing strategies to different visitor groups.
