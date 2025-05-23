# 🕵️‍♂️ Image Tampering Detection using ELA and CNN

Detect manipulated or tampered images using **Error Level Analysis (ELA)** and a **Convolutional Neural Network (CNN)** classifier.

## 📌 Overview

With the rise of digital media, image forgeries have become increasingly sophisticated and widespread. This project aims to:
- Detect image tampering (copy-move, splicing, resampling)
- Use **Error Level Analysis (ELA)** to highlight discrepancies
- Train a **CNN model** on ELA-processed images for classification

---
## 🧠 Methodology

1. **ELA Preprocessing**  
   - Converts an image to JPEG at 95% quality
   - Computes the difference between the original and recompressed image
   - Enhances error levels to reveal tampered regions

2. **CNN Classification**  
   - Binary classification: `Tampered` vs. `Authentic`
   - Trained on ELA-generated images
   - Capable of identifying subtle manipulation artifacts

---
