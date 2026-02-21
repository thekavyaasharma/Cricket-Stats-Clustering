# 🏏 Cricket Stats using Clustering Algorithm

This repository contains a cricket statistics clustering project that applies unsupervised machine learning techniques to group players based on performance metrics.  
The analysis is performed using Python (in a Jupyter Notebook) and explores patterns in batters/bowlers performance from a cricket dataset (`Cricket.csv`).

---

## 📁 Project Structure

```
Cricket-Stats-Clustering/
├── Cricket-Players-Clustering.ipynb  # Main Jupyter Notebook with clustering analysis
├── Cricket.csv                       # Cricket dataset used for clustering
├── requirements.txt                  # Python dependencies
└── README.md                         # This file
```

---

## 🧠 Overview

The goal of this project is to:

- Load and preprocess cricket player statistics data
- Explore features such as runs, averages, strike rates, etc.
- Apply clustering algorithms (e.g., K-Means, Hierarchical)
- Visualize clusters to identify similar player performance groups

This can help categorize batters, bowlers, or all-rounders based on statistical similarity.

---

## 📊 Key Concepts Used

- **Data Preprocessing**  
  Cleaning and normalizing the data for clustering

- **Unsupervised Learning**  
  Using clustering techniques like:
  - K-Means
  - Hierarchical Clustering

- **Visualization**  
  Scatter plots, heatmaps, and cluster labels to interpret results

---

## 🚀 How to Run

1. **Clone the repository:**

```bash
git clone https://github.com/thekavyaasharma/Cricket-Stats-Clustering.git
cd Cricket-Stats-Clustering
```

2. **Install dependencies:**

```bash
pip install -r requirements.txt
```

3. **Launch the Jupyter Notebook:**

```bash
jupyter notebook Cricket-Players-Clustering.ipynb
```

4. **Follow the analysis steps in the notebook:**
   - Load `Cricket.csv`
   - Explore statistical distributions
   - Run and visualize clustering algorithms

---

## 📦 Dependencies

Listed in `requirements.txt`, typically including:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyter notebook

Install using:

```bash
pip install -r requirements.txt
```

---

## 📈 What You'll Learn

- How to perform clustering on real-world sports data
- How to visualize player clusters
- How to interpret clustering results
- How to analyze patterns in cricket performance statistics

---

## 📌 Future Improvements

Here are some ideas to expand this project:

- Add more features (e.g., match format, career span)
- Compare multiple clustering techniques
- Use feature selection or dimensionality reduction
- Deploy an interactive dashboard for cluster visualization

---

## 📄 License

This project is open-source and free to use for educational purposes.

---

## 🙏 Acknowledgements

Thanks to all open cricket data providers — your datasets make analysis like this possible!
