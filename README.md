# 🔍 Speed Analysis of Searching Algorithms  

This Jupyter Notebook compares the execution time of 10 different search algorithms to analyze their efficiency.  

## 📌 Algorithms Tested  
- **Linear Search**  
- **Binary Search**  
- **Jump Search**  
- **Interpolation Search**  
- **Exponential Search**  
- **Fibonacci Search**  
- **Ternary Search**  
- **Hashing-based Search**  
- **Depth-First Search (DFS)**  
- **Breadth-First Search (BFS)**  

## 📊 Project Overview  
This project generates a dataset of **100 random numbers**, implements multiple search algorithms, measures their execution time, and visualizes the results using **matplotlib**.  

### 🚀 Key Findings  
- **Exponential Search** was the fastest.  
- **Hashing-based Search** was the slowest due to hash table overhead.  
- **Binary, Jump, and Interpolation searches** performed efficiently for sorted data.  

### 🛠 Installation & Usage  
To run this project on your local machine:  
```bash
# Clone the repository  
git clone https://github.com/Danncode10/Speed-Analysis-of-Searching-Algorithms.git  
cd Speed-Analysis-of-Searching-Algorithms  

# Install dependencies  
pip install pandas matplotlib numpy  

# Run the Jupyter Notebook  
jupyter notebook search_algorithm_benchmark.ipynb  
