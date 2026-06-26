# 🤖 Artificial Intelligence Step 3: Deep Learning with Keras and TensorFlow

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.19.0-orange.svg)
![Keras](https://img.shields.io/badge/Keras-3.0+-red.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

**A comprehensive collection of Deep Learning implementations using Keras and TensorFlow**

</div>

---

## 📋 Table of Contents
- [Overview](#-overview)
- [Repository Structure](#-repository-structure)
- [Notebooks Overview](#-notebooks-overview)
  - [Advanced Model Architectures](#-advanced-model-architectures)
  - [Generative AI](#-generative-ai)
  - [Advanced Training Techniques](#-advanced-training-techniques)
  - [Core Deep Learning Concepts](#-core-deep-learning-concepts)
- [Installation](#-installation)
- [Usage](#-usage)
- [Topics Covered](#-topics-covered)
- [Prerequisites](#-prerequisites)
- [Contributing](#-contributing)
- [License](#-license)
- [Acknowledgments](#-acknowledgments)

---

## 🎯 Overview

This repository is a comprehensive collection of **Deep Learning** implementations and tutorials using **Keras** and **TensorFlow**. It serves as Step 3 in the Artificial Intelligence learning path, covering everything from fundamental concepts to state-of-the-art architectures including Transformers, GANs, and Diffusion Models.

### 📚 What's Inside

| Category | Notebooks |
|----------|-----------|
| **Advanced Model Architectures** | Transformers, Functional API, Custom Layers, Transpose CNN |
| **Generative AI** | GANs, Diffusion Models |
| **Advanced Training Techniques** | Transfer Learning, Hyperparameter Tuning, Data Augmentation |
| **Core Concepts** | Autoencoders, Q-Learning (Reinforcement Learning) |

---

## 📁 Repository Structure

```
Artificial-Intelligence-Step-3-Deep-Learning-with-Keras-and-Tensorflow/
│
├── Advance_Data_Augmentation_with_keras.ipynb
├── Advance_Transformer.ipynb
├── Building_Autoconcider.ipynb
├── Classify_waste_product_using_Transfer_Learning.ipynb
├── Creating_custom_layers_and_models_in_Keras.ipynb
├── Develop_GAN.ipynb
├── HyperParameter_Tuning_with_Keras.ipynb
├── Implement_Diffusion_Model.ipynb
├── Implementing_Keras_Functional_API.ipynb
├── Implementing_Transformers_for_Text_Generation.ipynb
├── Q_Learning_in_Keras(Reinforcement_Learning).ipynb
├── Transfer_Learning_with_Keras.ipynb
├── Transpose_CNN.ipynb
├── README.md
└── LICENSE
```

---

## 📓 Notebooks Overview

### 🔬 Advanced Model Architectures

#### 1. **Advanced Transformer** (`Advance_Transformer.ipynb`)
Implementation of Transformer architecture from scratch, covering:
- Self-attention mechanisms
- Multi-head attention
- Positional encoding
- Encoder-Decoder architecture
- Applications in NLP tasks

#### 2. **Implementing Transformers for Text Generation** (`Implementing_Transformers_for_Text_Generation.ipynb`)
Hands-on implementation of Transformers for text generation tasks:
- GPT-like architecture
- Text generation pipeline
- Tokenization strategies
- Training on text datasets

#### 3. **Implementing Keras Functional API** (`Implementing_Keras_Functional_API.ipynb`)
Deep dive into Keras Functional API:
- Building complex model architectures
- Multi-input/multi-output models
- Shared layers
- ResNet-like architectures
- Model composition and reuse

#### 4. **Transpose CNN** (`Transpose_CNN.ipynb`)
Understanding and implementing Transposed Convolutions:
- Upsampling techniques
- Semantic segmentation
- Decoder architectures
- Pixel-level predictions

#### 5. **Creating Custom Layers and Models in Keras** (`Creating_custom_layers_and_models_in_Keras.ipynb`)
Learn to extend Keras with custom components:
- Custom Layer creation
- Custom Model architectures
- Custom training loops
- Loss functions and metrics

---

### 🎨 Generative AI

#### 6. **Develop GAN** (`Develop_GAN.ipynb`)
Complete implementation of Generative Adversarial Networks:
- Generator and Discriminator architecture
- Training GANs
- DCGAN
- Image generation
- Training stability techniques

#### 7. **Implement Diffusion Model** (`Implement_Diffusion_Model.ipynb`)
Implementation of Diffusion Models:
- Forward diffusion process
- Reverse diffusion (denoising)
- U-Net architecture
- Training diffusion models
- Image generation from noise

---

### ⚡ Advanced Training Techniques

#### 8. **Transfer Learning with Keras** (`Transfer_Learning_with_Keras.ipynb`)
Comprehensive guide to Transfer Learning:
- Pre-trained models (VGG16, ResNet, etc.)
- Feature extraction
- Fine-tuning
- Domain adaptation
- Model freezing/unfreezing strategies

#### 9. **Classify Waste Product using Transfer Learning** (`Classify_waste_product_using_Transfer_Learnin...`)
Real-world application of Transfer Learning:
- VGG16 implementation
- Binary classification (Organic/Recyclable)
- Data augmentation
- Fine-tuning strategies
- ~81% accuracy achieved

#### 10. **Advance Data Augmentation with Keras** (`Advance_Data_Augmentation_with_keras.ipynb`)
Advanced augmentation techniques:
- ImageDataGenerator
- Custom augmentation pipelines
- Random transformations
- Augmentation strategies for limited data
- Mixup and CutMix techniques

#### 11. **HyperParameter Tuning with Keras** (`HyperParameter_Tuning_with_Keras.ipynb`)
Systematic hyperparameter optimization:
- Grid Search
- Random Search
- Bayesian Optimization
- Hyperband
- Cross-validation strategies

---

### 🏗️ Core Deep Learning Concepts

#### 12. **Building Autoencoder** (`Building_Autoconcider.ipynb`)
Complete implementation of Autoencoders:
- Encoder-Decoder architecture
- Dimensionality reduction
- Image reconstruction
- Denoising autoencoders
- Anomaly detection

#### 13. **Q-Learning in Keras (Reinforcement Learning)** (`Q_Learning_in_Keras(Reinforcement_Learning).ipynb`)
Reinforcement Learning implementation:
- Q-Learning algorithm
- Deep Q-Networks (DQN)
- Experience replay
- Environment interaction
- Policy learning

---

## 🚀 Installation

### Prerequisites
- Python 3.8+
- Jupyter Notebook
- TensorFlow 2.x
- CUDA-capable GPU (recommended for training)

### Setup

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/Artificial-Intelligence-Step-3-Deep-Learning-with-Keras-and-Tensorflow.git
cd Artificial-Intelligence-Step-3-Deep-Learning-with-Keras-and-Tensorflow
```

2. **Create virtual environment**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

### Requirements
```
tensorflow>=2.19.0
numpy>=1.24.0
matplotlib>=3.7.0
scikit-learn>=1.3.0
pandas>=2.0.0
jupyter>=1.0.0
```

---

## 📖 Usage

### Run Jupyter Notebook
```bash
jupyter notebook
```

### Run Specific Notebook
```bash
jupyter notebook "Notebook_Name.ipynb"
```

### Example: Run Transfer Learning Notebook
```bash
jupyter notebook Transfer_Learning_with_Keras.ipynb
```

---

## 🧠 Topics Covered

### ✅ Advanced Model Architectures
- Transformers (NLP & Vision)
- Transpose CNNs
- Custom Keras Layers
- Functional API Models

### ✅ Generative AI
- GANs (Generative Adversarial Networks)
- Diffusion Models
- Autoencoders

### ✅ Advanced Training
- Transfer Learning
- Hyperparameter Tuning
- Data Augmentation
- Custom Training Loops

### ✅ Reinforcement Learning
- Q-Learning
- Deep Q-Networks (DQN)

### ✅ Computer Vision
- Image Classification
- Transfer Learning
- Semantic Segmentation
- Image Generation

---

## 📊 Learning Path

This repository is **Step 3** in the Artificial Intelligence learning path:

| Step | Topic |
|------|-------|
| **Step 1** | Foundations of AI & Machine Learning |
| **Step 2** | Machine Learning with Scikit-Learn |
| **Step 3** | Deep Learning with Keras & TensorFlow |
| **Step 4** | Advanced AI & Deployment |

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/amazing-feature`)
3. **Commit your changes** (`git commit -m 'Add amazing feature'`)
4. **Push to the branch** (`git push origin feature/amazing-feature`)
5. **Open a Pull Request**

### Contribution Guidelines
- Maintain code quality and documentation
- Add comments for complex sections
- Include examples and visualizations
- Follow PEP 8 style guide

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- **TensorFlow** and **Keras** teams for the excellent frameworks
- **Google Research** for Transformer architecture
- **OpenAI** for diffusion models
- **DeepMind** for reinforcement learning advancements
- Open-source community for continuous innovation
- All researchers and practitioners advancing the field of AI

---

## 📚 References

### Core Papers
- [Attention Is All You Need](https://arxiv.org/abs/1706.03762) - Transformer
- [Generative Adversarial Networks](https://arxiv.org/abs/1406.2661) - GANs
- [Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239) - Diffusion Models
- [Deep Residual Learning](https://arxiv.org/abs/1512.03385) - ResNet

### Additional Resources
- [Keras Documentation](https://keras.io/)
- [TensorFlow Documentation](https://www.tensorflow.org/)
- [Hugging Face Transformers](https://huggingface.co/docs/transformers/index)

---

## ⭐ Show Your Support

If this repository helped you in your Deep Learning journey, please give it a ⭐ on GitHub and share it with others!

---

<div align="center">

**🤖 Keep Learning, Keep Building!**

</div>
