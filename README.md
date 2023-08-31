# Unsupervised Music Data Clustering
 Comprehensive code for the clustering approaches applied to the GTZAN data

In the realm of music distribution and categorization, challenges arise from the subjective nature of music genres and the need for standardized indexing on a global scale.
This thesis delves into the domain of Music Information Retrieval (MIR) to address these complexities, focusing on data-driven approaches to enhance music categorization.
A prevalent method of indexing songs is through genre classification, which can vary significantly based on cultural and geographical factors, as well as human-tagged genre
labels. Recognizing the necessity for a uniform and reproducible indexing system in the global music distribution industry, this thesis embarks on exploring diverse data-driven
models to cluster songs into coherent groups.

The primary objective is to compare these clustering models with human-tagged genre labels. The study investigates techniques for re-expressing music data in a reduced-dimensional space, subsequently selecting models that yield clusters aligned with human-defined genres. By doing so, the thesis aims to capture both categorization methods that
mirror human perception as well as those that provide standardized clusters.
The outcomes of this research illuminate the capacity of clustering techniques to emulate human-tagged genres and, conversely, to generate standardized categorizations. The
exploration highlights the impact of dimensionally reduced data on cluster formation,
offering insights into the variances within each reduced space and their influence on clustering outcomes.


The code for this thesis is divided into the following sections:

1. Data - contains the entire GTZAN data set, and the song files of each track
2. Exploratory Data Analysis - overview of the numerical variables in this data set, along with its distribution across different genres.
3. Exploratory Clustering - applying non-parametric clustering approaches on the GTZAN data like - Hierarchical, and K-means clustering
4. Model-based clustering - applying mixture modelling on a reduced dimension subset of the data
5. Mixture Factor Analysis - applying two main approaches of the IMIFA model - MFA and MIFA on the scaled GTZAN data set. It also contains the results of comparing models across all methods
