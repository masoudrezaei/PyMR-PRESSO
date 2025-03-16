# PyMR-PRESSO
A Fast Python Implementation of MR-PRESSO
## 📌 Overview  
MR-PRESSO (**Mendelian Randomization Pleiotropy RESidual Sum and Outlier**) is a powerful method for detecting and correcting horizontal pleiotropy in **Mendelian Randomization (MR)** analyses. However, the original **R-based implementation** can be computationally inefficient, especially when applied to **large-scale GWAS datasets**.  

To address this challenge, we introduce **PyMR-PRESSO**, a **Python-based** implementation optimized for speed and scalability using **NumPy arrays**.  

---

## 🚀 Why PyMR-PRESSO?  

### ⚡ Challenge: Computational Inefficiency in R  
- The standard MR-PRESSO **R package** is **slow** on large datasets due to inefficient matrix operations.  
- Running outlier detection across many **genetic variants (SNPs)** can be prohibitively slow.  

### ✅ Solution: Python Optimization  
- **NumPy-powered** implementation for **faster matrix operations**.  
- **Vectorized computations** to reduce redundant loops and increase performance.  
- **Parallel processing** support for large-scale MR analyses.  

### 🐍 Why Python?  
- **NumPy & Pandas:** Efficient handling of large GWAS datasets.  
- **Optimized for parallel computing**, reducing runtime significantly.  
- **Better memory management** compared to R’s in-memory operations.  

### 📈 Impact  
- **Drastically improved execution time** compared to the R version.  
- **Scalability for large GWAS datasets** and high-dimensional MR analyses.  
- **More accessible** for researchers familiar with Python’s data science ecosystem.
### 📝 How to Use:

1. Open the **PyMR-PRESSO Jupyter Notebook** on Google Colab by clicking the link below:
   - [Open MR-PRESSO-Py Colab Notebook](<https://github.com/masoudrezaei/PyMR-PRESSO/blob/main/PyMR_PRESSO.ipynb>)

## 📄 Citation

If you use PyMR-PRESSO in your research, please cite the original MR-PRESSO paper:

Verbanck, M., Chen, C.-Y., Neale, B., & Do, R. (2018). Detection of widespread horizontal pleiotropy in causal relationships inferred from Mendelian randomization between complex traits and diseases. *Nature Genetics*, 50(5), 693–698. [https://doi.org/10.1038/s41588-018-0099-7](https://doi.org/10.1038/s41588-018-0099-7)
