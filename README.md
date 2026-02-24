# 🚀 LR-Optimization-Comparison: First vs Second-Order Methods for Linear Regression

[![Stars](https://img.shields.io/github/stars/YOURUSERNAME/LR-Optimization-Comparison)](https://github.com/YOURUSERNAME/LR-Optimization-Comparison)
[![Forks](https://img.shields.io/github/forks/YOURUSERNAME/LR-Optimization-Comparison)](https://github.com/YOURUSERNAME/LR-Optimization-Comparison)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Paper](https://img.shields.io/badge/Paper-Research-red)](https://your-paper-link)

**Theoretical & Computational Comparison: GD/AdaGrad vs Newton's Method**  
*By Aayush Kasurde (Thakur College of Engineering)*

<img src="outputs/convergence_comparison.gif" width="800" alt="Convergence GIF">  
*Watch AdaGrad spiral vs Newton's bold leaps!*

## 🌟 Key Highlights
- **One-step Newton** for quadratic loss 🎯
- **Adaptive AdaGrad** for sparse data stability
- **Visual 3D contours** + iteration tables matching Table I [file:1]
- Datasets: Diabetes, California Housing (UCI) 🏠

## 📊 Quick Results
| Method       | Iterations | Final MSE | Speed    |
|--------------|------------|-----------|----------|
| Normal Eq   | 1         | 0.000    | Analytical |
| AdaGrad     | 600-2500  | Low      | Gradual  | [file:1]
| Newton      | 3-10      | 0.000    | Rapid    | [file:1]

## 🚀 Get Started
```bash
git clone https://github.com/YOURUSERNAME/LR-Optimization-Comparison.git
cd LR-Optimization-Comparison
pip install -r requirements.txt
jupyter notebook notebooks/03_Experiments.ipynb
