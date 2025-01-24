# 📜 **Topic Modeling ---ProjectMape**


---

## 🚀 **What This Repository is For**
This repository is designed to:
- 🔍 Analyze historical documents and extract **topics** and **themes**.
- 🤖 Use state-of-the-art **LLMs** for topic generation and refinement.
- 📉 Cluster and visualize textual data to uncover **hidden patterns**.
- 🗂️ Provide a high-level **categorization of themes** for meaningful insights.

The project aims to enable researchers, historians, and enthusiasts to better understand the administrative, social, and economic aspects of the Portuguese Empire through modern data analysis techniques.

---

## 📂 **Data Files**
Access the historical data used in this project here:  
**[🗂️ Data Files](https://drive.google.com/drive/folders/1iDmNsb1wcDv50SgCWitsvEwMqD1OxlxA?usp=drive_link)**

---

## 🧠 **Embedding Files**
Explore the document and topic embeddings generated for analysis here:  
**[📂 Embedding Files](https://drive.google.com/drive/folders/1jAk8lg47qJdbK7BeI_ICUZa7Y0ZAWo6w?usp=drive_link)**

---

## 📊 **Figure Files**
Check out the visualizations created during the project:  
**[📁 Figure Files](https://drive.google.com/drive/folders/11Y1DlElZEi-IC8P7Hhc0qm3hT5R9HMoo?usp=drive_link)**

---

## 🛠️ **Workflow Overview**
Here’s how the project works, step by step:

### 1️⃣ **Dataset Preparation**  
- 📝 The dataset consists of historical letters exchanged during PT-Empire
- 🧹 Preprocessing cleans and prepares the text for further analysis.

### 2️⃣ **Topic Generation**  
- ✏️ Topics are generated for each document using a **Primary LLM**, providing concise summaries of the content.

### 3️⃣ **Evaluation and Filtering**  
- 📉 **Cosine similarity** is computed to measure alignment between document embeddings and topics.  
- 🔍 Rows with low alignment (below a defined threshold) are flagged for refinement.

### 4️⃣ **Topic Refinement**  
- 🔄 Topics for low-alignment rows are regenerated using the **Primary LLM** and refined using a **Governing LLM** for contextual accuracy.

### 5️⃣ **Dimensionality Reduction**  
- 📉 Combined embeddings are reduced using **UMAP** to:  
  - Enable efficient clustering.  
  - Create 2D visualizations for interpretability.

### 6️⃣ **Clustering**  
- 🔗 Reduced embeddings are grouped into clusters using **KMeans**, representing documents with similar themes.

### 7️⃣ **Keyword Extraction**  
- 🧠 **YAKE** is used to extract top keywords for each cluster, identifying core themes.

### 8️⃣ **Cluster Topic Generation**  
- 🤖 The extracted keywords are summarized into a single **cluster topic** using an **LLM**.

### 9️⃣ **Broad Categorization**  
- 🗂️ Cluster topics are mapped to high-level categories (e.g., **Governance**, **Military**, **Trade**) using an LLM.

### 1️⃣0️⃣ **Final Dataset**  
- The enriched dataset includes:  
  - **Cluster Labels**: Groups of similar documents.  
  - **Cluster Topics**: Concise summaries for each cluster.  
  - **Broad Categories**: Thematic grouping for easier interpretation.

---

## 🎯 **Project Outcomes**
- 📂 A structured dataset with clusters, topics, and broad categories.  
- 📊 Visualizations for exploring patterns and relationships in the data.  
- 🤝 A framework for analyzing large, unstructured historical datasets.

---


