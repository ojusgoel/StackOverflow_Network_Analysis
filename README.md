# StackOverflow Network Analysis

This project presents an analytical and visual exploration of Stack Overflow tag data, focusing on uncovering trends and relationships among technology-related topics discussed in 2016. The analysis uses graph theory and network science techniques to understand the structural patterns of tag co-occurrence. We leverage the `igraph` library to build, analyze, and visualize the tag network.

---

## 👥 Contributors

- Nishchay Rajput (12241180)  
- Ojus Goel (12241190)  
- Patel Janmay Gaurav (12241240)  
- Pravar Gupta (12241340)  

**Mentor:** Dr. Rishi Ranjan Singh

---

## 🔍 Key Results

- Constructed a network of **3,368 tags** connected by **39,619 edges**  
- Detected **11 communities** and ranked technologies using **eigenvector centrality** and **degree**

---

## 📌 Project Overview

We constructed co-occurrence tag networks from Stack Overflow questions using the `igraph` library. Tags that appeared together in the same question were connected via weighted edges, enabling us to analyze:

- **Tag popularity** (frequency)  
- **Centrality** metrics (e.g., Betweenness, Eigenvector)  
- **Community detection**  
- **Temporal shifts in technology trends (2008–2016)**

---

## 📂 Dataset

- **Source:** [Kaggle StackSample Dataset](https://www.kaggle.com/datasets/stackoverflow/stacksample)  
- **Key files used:**
  - `Tags.csv`  
  - `Questions.csv`

---

## 🔧 Tools & Libraries

- Python  
- Pandas  
- NumPy  
- iGraph  
- Matplotlib / Seaborn (for visualization)

---

## 📈 Key Findings

- **Nodes (unique tags):** 3,368  
- **Edges (co-occurrences):** 39,619  
- **Average degree:** 23.5  
- **Network density:** 0.0069  
- **Communities detected:** 11  

**Temporal Trends (2008–2016):**  
- 2008–2010: Dominance of Microsoft (.NET, C#)  
- 2011–2013: Rise of web technologies (HTML, CSS, JavaScript)  
- 2014–2016: Growth of open-source and mobile (Python, Android, Node.js)

---

## ⚙️ Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/ojusgoel/StackOverflow_Network_Analysis.git
   cd Stackoverflow-Network
