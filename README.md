# GanForge
**Indian Institute of Technology Kanpur (IITK) | ACA**

Welcome to **GanForge**, a comprehensive repository documenting my journey through the **IIT Kanpur ACA Summer Project** on Machine Learning, Deep Learning, and Generative AI. 

This repository serves as a structured log of coursework, coding assignments, and hands-on projects designed to build foundational and advanced skills in artificial intelligence. Throughout this program, the focus transitions from basic data manipulation and mathematical modeling to implementing robust deep learning architectures (like CNNs) using PyTorch, and exploring the mechanics of Generative Adversarial Networks (GANs).

**Key Learning Objectives Covered:**
- **Foundational ML:** Data preprocessing, statistical modeling, and basic machine learning algorithms.
- **Deep Learning Architectures:** Building and training neural networks from scratch using PyTorch.
- **Computer Vision:** Image processing, feature extraction, and implementing CNNs for real-world tasks like face mask detection.
- **Generative AI Concepts:** Understanding the underlying theory and application of modern generative models.

## Repository Structure

This repository is organized progressively by weekly assignments, culminating in a comprehensive Mid-Evaluation project.

- **`Week_1/`**: Initial assignments covering foundational data science and machine learning tasks.
- **`Week_2/`**: Advanced scripting and analysis tasks.
- **`Week_3/`**: Implementation of algorithms including Forward Substitution (FSI) and other mathematical modeling scripts.
- **`Mid_Evaluation/Face_Mask_Detection/`**: The core highlight of this repository. A Convolutional Neural Network (CNN) built from scratch using PyTorch for Face Mask Detection.
- **`EndEval/`**: The final group evaluation focusing on Generative AI, featuring CycleGAN (Monet-to-Photo) and Neural Style Transfer (Picasso-styled Mona Lisa).

---

## Highlight: Face Mask Detection (Mid-Evaluation)

**Description:**
A Deep Learning Computer Vision project designed to detect whether individuals in an image are wearing face masks. The model is built entirely in **PyTorch** and leverages a custom Convolutional Neural Network (CNN) architecture.

**Key Achievements:**
- **Accuracy**: Achieved a **95.21% Test Accuracy** on the holdout evaluation set.
- **Dataset**: Trained on the Kaggle Face Mask Detection dataset (PASCAL VOC XML annotations).
- **Tech Stack**: Python, PyTorch, Torchvision, OpenCV, Matplotlib.

**Files Included:**
- `Mideval_240628.ipynb`: The complete source code, training loops, and evaluation metrics.
- `Explanation of code.pdf`: Detailed documentation and architectural breakdown of the CNN.

---

## 🎨 Highlight: Generative AI & Style Transfer (End-Evaluation)

**Description:**
The culminating group project focusing on advanced Generative AI architectures. It implements CycleGAN for image-to-image translation (converting photos to Monet-style paintings) and leverages a pre-trained VGG19 model for Neural Style Transfer.

**Key Features:**
- **CycleGAN**: Bidirectional image translation trained on the `monet2photo` dataset.
- **Neural Style Transfer**: A custom PyTorch implementation applying the artistic style of Pablo Picasso's *The Weeping Woman* to Leonardo da Vinci's *Mona Lisa*.
- **Tech Stack**: Python, PyTorch, Torchvision, PIL, Matplotlib.

**Files Included:**
- `EndEval_code.ipynb`: The main notebook containing both the CycleGAN and Neural Style Transfer implementations.
- `EndEval_Project1_doc.pdf`: Detailed project documentation.
- `requirements.txt`: Environment dependencies.

---

## Getting Started

To explore the projects or run the code locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/CODER-7777/GanForge.git
   cd GanForge
   ```
2. Install the required dependencies (ensure you have PyTorch installed):
   ```bash
   pip install torch torchvision opencv-python matplotlib scikit-learn
   ```
3. Open the Jupyter Notebooks using your preferred environment (Jupyter Lab, VS Code, Kaggle, etc.).

---
*Created by Mansoju Vivekananda (Roll No: 240628)*