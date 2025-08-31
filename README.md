# NeuroChain  
*A learning journey from perceptrons to GPT-style transformers*  

## 📌 Overview  
Core2GPT is an **educational machine learning framework** that bridges classical algorithms and modern deep learning. It’s designed to help you implement, train, and understand models ranging from **perceptrons and regression** all the way to **transformer-based GPT models** — using real datasets like **MNIST** and a custom **language ID task**.  

This project provides a **hands-on path** to see how simple ideas in machine learning grow into the foundations of today’s large language models.  

## 🛠️ Features  
- **Classical Models**: Perceptron, Regression, Digit Classification  
- **Deep Learning with PyTorch**: Fully connected networks and training pipelines  
- **Transformers & GPT**: Character-level GPT (`chargpt.py`) and GPT-like transformer (`gpt_model.py`)  
- **Datasets**:  
  - `mnist.npz` → handwritten digit recognition  
  - `lang_id.npz` → language identification  
- **Testing Tools**: `autograder.py` for automated checks  

## 📂 Project Structure
```
│── backend.py # Utilities and data handling
│── models.py # Core ML models (Perceptron, Regression, etc.)
│── gpt_model.py # Transformer-based GPT model
│── chargpt.py # Character-level GPT implementation
│── autograder.py # Automated grading/testing
│── data/
│ ├── mnist.npz # Digit classification dataset
│ └── lang_id.npz # Language ID dataset
│── input.txt # Example input for GPT
```

## 🚀 Installation  
```
Clone the repository and install dependencies:  
```bash
git clone https://github.com/<your-username>/Core2GPT.git
cd Core2GPT
pip install torch numpy
```

## 🏃 Running tests
```
python autograder.py
```