# Deep Knowledge Tracing Lab (DKT-Lab)

Welcome to the **DKT-Lab** organization 👋  
We develop open-source research projects around **Deep Knowledge Tracing (DKT)** — modeling how students acquire and demonstrate knowledge over time.  

Our focus is on building **pipelines, embeddings, and experimental frameworks** to advance educational data mining and personalized learning.

---

## 🚀 Active Projects

### 🔹 [Pipeline-for-Generating-multiple-Pre-trained-Embeddings-in-Deep-Knowledge-Tracing-DKT](https://github.com/Maximus42-byte/Pipeline-for-Generating-multiple-Pre-trained-Embeddings-in-Deep-Knowledge-Tracing-DKT-)
**Project 2: DKT Initialization with Text Embeddings**

- Develop a **pipeline** to generate embeddings for DKT using combinations of:  
  1. **Embedding models**  
  2. **Knowledge Component (KC) embeddings**  
  3. **Student action embeddings**  
- Implement functions to support KC embedding and student action embedding methods.  
- Define flexible functions for selecting the order of operations in different combinations.  
- Run the pipeline for multiple embedding combinations and prepare them for **pykt**.  
- Evaluate with **pykt** models, reporting **ACC** and **AUC** for each embedding.  

---

### 🔹 [Knowledge-Component-Reordering-in-knowledge-tracing](https://github.com/Maximus42-byte/Knowledge-Component-Reordering-in-knowledge-tracing)
**Project 3: KC Reordering with Embedding Clustering**

- Generate embeddings for each question in **ASSIST2009/2012/2017** datasets.  
- Use **t-SNE** to cluster embeddings with variable cluster counts (from 5 up to ~2×N KCs + 5).  
- Relabel dataset CSV files for each clustering scenario.  
- Train **pykt’s DKT** on each relabeled dataset and report **ACC** and **AUC** results.  

---

## 👨‍💻 Maintainers
- **Mahdi Saieedi** [@Maximus42-byte](https://github.com/Maximus42-byte)  
- **Kia Karbasi** [@karbazhyev](https://github.com/karbazhyev)  

---

⭐ If you find our work useful, please **star the repositories** and follow our organization for updates.  
🤝 Contributions and collaborations are welcome!
