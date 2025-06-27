## 🚀 **Debutanizer Soft Sensor using GNN and ANN**

This project implements a **soft sensor model** for a **Debutanizer Column**, comparing **Graph Neural Networks (GNN)** and **Artificial Neural Networks (ANN)** for predicting process variables. The project highlights how integrating **process structure via GNN** improves prediction performance over conventional ANN approaches.

✅ Combines **Chemical Engineering process knowledge** with **cutting-edge AI techniques**

---

## 🎯 **Problem Statement**

Real-time measurement of critical quality variables inside industrial columns like the **Debutanizer** is expensive and often infeasible. **Soft sensors** leverage easily accessible process data such as:

- **Temperature**
- **Pressure**
- **Flow rates**

to estimate these hard-to-measure properties.

**This project develops:**

✅ A **GNN-based soft sensor** incorporating process relationships via graph construction  
✅ A standard **ANN-based soft sensor** serving as a baseline  
✅ A direct **performance comparison** between the two approaches  

---

## ⚙️ **Technical Overview**

### 📊 **Dataset**

*Industrial-style Debutanizer Column Dataset*

- **Features:** Temperature, Pressure, Flow rates, etc.  
- **Target:** Product composition or key quality variable  

---

### 🧠 **Models**

#### ✅ **1. Graph Neural Network (GNN)**

- Graph constructed using **k-Nearest Neighbors (kNN)** to capture process relationships  
- **2-layer Graph Convolutional Network (GCN)** with ReLU activation  
- Implemented using **PyTorch** and **PyTorch Geometric**  
- Models both **feature dependencies** and **underlying structure** of the process  

#### ⚡ **2. Artificial Neural Network (ANN)**

- Fully Connected **Feedforward Neural Network**  
- Baseline approach treating data points as independent  
- Implemented using **PyTorch/Sklearn**  
- Lacks structural awareness of the process  

---

## 💡 **Key Takeaways**

✅ GNN effectively captures complex process interactions beyond feature-only models  
✅ Improved prediction accuracy makes GNN-based soft sensors promising for industrial deployment  
✅ Demonstrates practical fusion of **domain knowledge** and **modern machine learning**  

