# Computer Vision Research Projects

A comprehensive collection of deep learning research implementations focusing on **skin lesion classification and cancer detection** using state-of-the-art computer vision models.

## 📋 Table of Contents

- [Overview](#overview)
- [Projects](#projects)
- [Installation](#installation)
- [Usage](#usage)
- [Datasets](#datasets)
- [Results](#results)
- [Technologies](#technologies)
- [Contributing](#contributing)

## 🎯 Overview

This repository contains cutting-edge research implementations in computer vision, specifically targeting the classification and detection of skin lesions. The projects leverage advanced deep learning architectures and hybrid approaches to achieve high accuracy in dermatological image analysis.

### Objectives

- Develop robust models for skin lesion classification
- Implement state-of-the-art architectures (ConvNets, Transformers, Multi-modal fusion)
- Improve model interpretability and generalization
- Compare different approaches for medical image analysis

## 🔬 Projects

### 1. **ConvNeXtV2 with Focal Self-Attention for Skin Cancer Detection**

**Notebook:** `skin lesions classification/convnextv2-focal-self-attention-for-skin-cancer.ipynb`

A modern vision model combining ConvNeXtV2 backbone with focal self-attention mechanisms for improved feature extraction and spatial awareness in skin lesion images.

**Key Features:**
- ConvNeXtV2 architecture for hierarchical feature learning
- Focal self-attention to concentrate on discriminative regions
- Optimized for multi-class skin lesion classification

---

### 2. **MetaFusionNet: Novel Multi-Modal Skin Cancer Detection**

**Notebook:** `skin lesions classification/metafusionnet-novel-multi-modal-skin-cancer-detec.ipynb`

An innovative multi-modal fusion network that combines multiple data streams and model predictions for enhanced cancer detection capabilities.

**Key Features:**
- Multi-modal data fusion architecture
- Ensemble learning approach
- Superior generalization across diverse datasets
- Meta-learning components for improved robustness

---

### 3. **PAD-UFS: CNN-Transformer with Consistency Regularization**

**Notebook:** `skin lesions classification/pad-ufs-cnn-transformer-consistency-regularizati.ipynb`

A hybrid CNN-Transformer architecture incorporating consistency regularization for semi-supervised learning on skin lesion classification.

**Key Features:**
- CNN-Transformer hybrid model
- Consistency regularization for semi-supervised learning
- Pseudo-labeling strategies
- Improved performance with limited labeled data

---

## ⚙️ Installation

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab
- GPU support (CUDA) recommended for faster training

### Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/msalmankhan03/computer-vision-research-projects.git
   cd computer-vision-research-projects
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

### Core Dependencies

- **PyTorch** - Deep learning framework
- **TensorFlow/Keras** - Model implementation (if used)
- **Scikit-learn** - Machine learning utilities
- **OpenCV** - Image processing
- **Pandas & NumPy** - Data manipulation
- **Matplotlib & Seaborn** - Visualization

## 🚀 Usage

### Running the Notebooks

1. **Launch Jupyter:**
   ```bash
   jupyter notebook
   ```

2. **Navigate to a project** and open the desired notebook:
   ```
   skin lesions classification/
   ├── convnextv2-focal-self-attention-for-skin-cancer.ipynb
   ├── metafusionnet-novel-multi-modal-skin-cancer-detec.ipynb
   └── pad-ufs-cnn-transformer-consistency-regularizati.ipynb
   ```

3. **Run cells sequentially** from top to bottom. Each notebook includes:
   - Data loading and preprocessing
   - Model architecture definition
   - Training procedure
   - Evaluation and results

### Example Workflow

```python
# Load preprocessed data
X_train, y_train, X_test, y_test = load_data()

# Initialize and train model
model = ConvNeXtV2_FocalAttention()
model.fit(X_train, y_train, epochs=50, batch_size=32)

# Evaluate performance
accuracy, precision, recall, f1 = model.evaluate(X_test, y_test)
print(f"Accuracy: {accuracy:.4f}")
```

## 📊 Datasets

The research utilizes publicly available dermatological datasets:

- **HAM10000** - 10,015 images of skin lesions across 7 disease categories
- **ISIC (International Skin Imaging Collaboration)** - Large-scale skin lesion dataset
- **Skin Cancer MNIST** - Preprocessed skin cancer dataset

**Note:** Datasets are not included in the repository. Download them from official sources and place in a `data/` directory.

## 📈 Results

### Performance Summary

| Model | Architecture | Accuracy | Precision | Recall | F1-Score |
|-------|-------------|----------|-----------|--------|----------|
| ConvNeXtV2 + Focal Attention | Modern Vision | - | - | - | - |
| MetaFusionNet | Multi-Modal Fusion | - | - | - | - |
| PAD-UFS | CNN-Transformer Hybrid | - | - | - | - |

*Note: Fill in with actual results from your notebooks*

## 🛠️ Technologies & Frameworks

- **Deep Learning:** PyTorch, TensorFlow, Keras
- **Computer Vision:** OpenCV, Torchvision, Pillow
- **Data Processing:** Pandas, NumPy, Scikit-learn
- **Visualization:** Matplotlib, Seaborn, Plotly
- **Model Architectures:** ConvNeXtV2, Vision Transformers, EfficientNet
- **Training Tools:** Weights & Biases, TensorBoard

## 📝 Citation

If you use this research in your work, please cite:

```bibtex
@repository{msalmankhan03_cv_research_2026,
  author = {M. Salman Khan},
  title = {Computer Vision Research Projects: Skin Lesion Classification},
  year = {2026},
  url = {https://github.com/msalmankhan03/computer-vision-research-projects}
}
```

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 📧 Contact & Support

For questions, suggestions, or collaboration inquiries:

- **GitHub:** [@msalmankhan03](https://github.com/msalmankhan03)
- **Email:** Open an issue on the repository

## 🔗 References

- [ConvNeXt: A ConvNet for the 2020s](https://arxiv.org/abs/2201.03545)
- [Vision Transformers](https://arxiv.org/abs/2010.11929)
- [ISIC Skin Lesion Dataset](https://www.isic-archive.com/)
- [Focal Loss for Dense Object Detection](https://arxiv.org/abs/1708.02002)

---

**Last Updated:** April 5, 2026  
**Status:** Active Development 🚀