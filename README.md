# **Deep Neural Networks: Activation Functions & Depth Analysis**  

## 📌 Overview  
This project explores how different activation functions and network depths affect Deep Neural Networks (DNNs). Using the **MNIST dataset**, it compares **Sigmoid, Tanh, ReLU, Leaky ReLU, and Parametric ReLU** to show how ReLU solves the vanishing gradient problem. It also tests different network depths to see their impact on performance.  

## 🚀 Key Features  
- Train a simple **DNN on MNIST**.  
- Compare **Sigmoid, Tanh, and ReLU** activation functions.  
- Analyze **ReLU variants** (Leaky ReLU, Parametric ReLU).  
- Test different **network depths** and visualize their effect.  

## 🛠 Technologies Used  
- **Python (PyTorch, NumPy, Matplotlib)**  
- **Jupyter Notebook**  
- **Torchvision** for dataset handling  

## 🔧 How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/TigistW/DNN-Activation-Analysis 
   cd DNN-Activation-Analysis 
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt  
   ```
3. Run the Jupyter notebook:  
   ```bash
   jupyter notebook ActivationFunctions.ipynb  
   ```

## 📊 Key Findings  
- **ReLU prevents vanishing gradients** and trains more effectively.  
- **Leaky ReLU & Parametric ReLU** improve performance slightly over ReLU.  
- **Deeper networks** improve accuracy but can lead to diminishing returns.  

## 🤝 Contributions  
Suggestions and improvements are welcome! 🚀  
