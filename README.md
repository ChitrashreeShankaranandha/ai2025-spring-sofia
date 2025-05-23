# Vision Transformer (ViT) Interpretability with Captum

Fine-tuned a Vision Transformer (ViT) on CIFAR-10 and explored model interpretability using Captum's Integrated Gradients.

---

## 📊 Project Overview
- **Model**: Vision Transformer (`vit_base_patch16_224`) from timm
- **Dataset**: CIFAR-10 (10 classes, 60K images)
- **Loss**: CrossEntropyLoss
- **Optimizer**: Adam
- **Tools**: PyTorch, Captum, timm, TensorBoard
- **Visualizations**: Integrated Gradients Attribution Overlays

---

## 🧠 Interpretability Experiments
1. **Integrated Gradients**:
   - Visualize per-pixel influence on predictions
   - Overlay heatmaps on CIFAR-10 images

2. **Perturbation Test**:
   - Blur parts of images to observe prediction changes

3. **Local Samples**:
   - Attribution visualizations on local images

---

## 📂 Files
- `ViT_CiFAR_Captum.ipynb` — Main notebook
- `images/` — Attribution overlays and visual examples
- `checkpoints/` — Saved ViT model weights (optional)

---

## 🚀 Run Locally after cloning the repo
```bash

# Install dependencies
pip install torch torchvision timm captum matplotlib

# Run notebook
jupyter notebook ViT_CiFAR_Captum.ipynb
```

---

## 📹 Demo Video
Watch a walkthrough of this project:
https://youtu.be/_20NqslWbRM

---


