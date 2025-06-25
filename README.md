# AI vs Human Image Classifier 🤖🧑

This project explores the distinction between real human faces and AI-generated images using a convolutional neural network trained on Kaggle datasets.

## 🔍 Motivation
As part of my interest in ethical AI, this project aims to highlight the challenges in detecting hyper-realistic synthetic media created by tools like Stable Diffusion. With growing concerns over misinformation and deepfakes, building detection models is a crucial step in responsible AI development.

## 📁 Data Sources
- **Real Faces**: [Shahzaib's High Quality Dataset](https://www.kaggle.com/datasets/shahzaibshazoo/detect-ai-generated-faces-high-quality-dataset)
- **AI-Generated Faces**: [Stable Diffusion Images](https://www.kaggle.com/datasets/gpch2159/ai-vs-human-syn-imgs-v2-partial)

The dataset was carefully balanced to maintain a 1.5:1 ratio of AI to real images for fair evaluation.

## 🛠️ Features
- Custom PyTorch `Dataset` and DataLoader
- Pretrained `xception` model via `timm`
- Training, validation, and classification metrics (accuracy, confusion matrix, F1 score)
- Single-image prediction support

## 🚀 How to Run
```bash
# Clone the repo
[git clone https://github.com/yourusername/ai-vs-human-classifier.git](https://github.com/CindyWanyika/AI-image-Classifier.git)
cd AI-image-Classifier

# Install dependencies
pip install -r requirements.txt

# Run notebook or scripts to train and evaluate
