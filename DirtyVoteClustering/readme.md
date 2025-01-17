# Dirty Vote Clustering  

> **Announcement**  
> The files uploaded in this repository are **summaries** of the project. Sensitive and private data belonging to the client have been excluded and remain their property. Only non-confidential insights, methods, and visualizations are shared here for educational and showcase purposes.  

## Introduction  
This project is inspired by the film **Dirty Vote**, a documentary released on February 11, 2024, which explores allegations of irregularities in the 2024 Indonesian Presidential Election. The film sparked significant public interest, leading to diverse opinions and discussions in the comment section of the video.  

The primary goal of this project is to **analyze public responses or opinions** by clustering the comments using machine learning techniques. By identifying patterns and topics in these discussions, the project aims to provide valuable insights into public sentiment and the dynamics of the discourse surrounding the film.  

## Project Overview  
The **Dirty Vote Clustering** project demonstrates the application of **unsupervised learning** and natural language processing (NLP) to analyze and categorize unstructured text data. The analysis includes:  
- Clustering public comments based on their content.  
- Identifying central themes and visualizing relationships between topics.  

## Key Features  
- **Data Filtering:** Ensured the dataset is cleaned and relevant through rigorous filtering methods, reducing noise for better analysis.  
- **Preprocessing:**  
  - Initial inspection and cleansing (lowercasing, removal of special characters, etc.).  
  - Stopword removal, slang word correction, and stemming to standardize text data.  
- **Clustering Algorithms:**  
  - **DBSCAN**: Identified clusters based on data density.  
  - **K-Means++**: Grouped data using centroid-based clustering for enhanced performance.  
- **Evaluation Metrics:**  
  - Davies-Bouldin Index (DBI) and Silhouette Score for model evaluation.  
- **Topic Modeling:**  
  - Used **Latent Dirichlet Allocation (LDA)** to identify topics in each cluster.  
- **Network Analysis:**  
  - Visualized connections between topics using Kamada-Kawai layouts for deeper insights into relationships within the data.  

## Results  
- **Cluster Analysis:**  
  - Cluster 0: Discussions on political topics and concerns about electoral fraud.  
  - Cluster 1: Conversations about the "Dirty Vote" documentary and its portrayal of political dynamics.  
  - Cluster 2: Sentiments of hope and prayer tied to political leadership and elections.  
- **Topic Modeling:**  
  - Revealed key themes, including democracy, media influence, and public sentiment.  
- **Network Visualization:**  
  - Highlighted central topics and their interrelations, such as "politics," "vote," and "democracy."  

## Tools & Technologies  
- **Programming Languages:** Python  
- **Libraries:** pandas, NumPy, scikit-learn, NLTK, Matplotlib, Seaborn  
- **Algorithms:** DBSCAN, K-Means++, LDA  
- **Visualization Tools:** NetworkX, Kamada-Kawai Layout  
