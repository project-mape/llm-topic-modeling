Please Read This 

## This Repo---Is For Topic Modeling 

Data Files :
https://drive.google.com/drive/folders/1iDmNsb1wcDv50SgCWitsvEwMqD1OxlxA?usp=drive_link


Embedding Files:

https://drive.google.com/drive/folders/1jAk8lg47qJdbK7BeI_ICUZa7Y0ZAWo6w?usp=drive_link

Figure Files:

https://drive.google.com/drive/folders/11Y1DlElZEi-IC8P7Hhc0qm3hT5R9HMoo?usp=drive_link


######################33

This project focuses on analyzing historical texts from the Portuguese Empire to uncover meaningful patterns, topics, and broad categories through advanced Natural Language Processing (NLP) and clustering techniques. The workflow leverages state-of-the-art language models (LLMs), dimensionality reduction, and clustering algorithms to organize and interpret complex datasets in a structured, meaningful way.

🛠️ Overview of Workflow
Dataset Preparation:

The dataset consists of historical letters with rich textual information.
Initial preprocessing involves cleaning and preparing the text for further analysis.
Topic Generation:

In the first stage, topics are generated for each document using a Primary LLM.
Topics are aligned with document content to provide concise summaries.
Evaluation and Filtering:

Cosine similarity is computed between document embeddings and their corresponding topics.
Rows with low alignment (below a defined threshold) are identified for further refinement.
Topic Refinement:

For low-alignment rows, topics are regenerated using the Primary LLM and then refined with a Governing LLM for stricter adherence to context.
Dimensionality Reduction:

Combined embeddings of document texts and their topics are reduced using UMAP for:
Efficient clustering in a high-dimensional space.
Visualization in 2D for better interpretability.
Clustering:

The reduced embeddings are grouped into clusters using KMeans.
Each cluster represents a collection of documents with similar content/themes.
Keyword Extraction:

For each cluster, top keywords are extracted using YAKE to identify key themes.
Cluster Topic Generation:

The extracted keywords are passed to an LLM to generate a single, meaningful topic for each cluster.
Broad Categorization:

Cluster topics are mapped to broad categories (e.g., Governance, Military, Trade) using an LLM.
This provides a high-level understanding of the dataset’s overall themes.
Final Dataset:

The dataset now includes:
Cluster Labels: Identifying the cluster each document belongs to.
Cluster Topics: Concise topics summarizing the cluster.
Broad Categories: High-level categories providing thematic grouping.
#################################################
