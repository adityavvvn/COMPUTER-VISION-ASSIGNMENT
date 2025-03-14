# COMPUTER-VISION-ASSIGNMENT

# 🏭 Garbage Detection in Noisy Environments: A Robust Approach Using Noise Reduction and Segmentation
**A Robust Approach Using Noise Reduction & Segmentation**  

![Project Banner](https://github.com/adityavvvn/COMPUTER-VISION-ASSIGNMENT/blob/main/banner.jpg)  

## 🚀 Project Overview  
This project focuses on **detecting plastic waste in noisy underwater environments** using advanced **noise reduction** techniques and multiple **segmentation methods**. The goal is to **enhance image quality** and accurately identify plastic debris for **environmental conservation** and **marine ecosystem preservation**.  

🔗 **GitHub Repository:** [COMPUTER VISION ASSIGNMENT](https://github.com/adityavvvn/COMPUTER-VISION-ASSIGNMENT)  
📂 **Dataset:** [Underwater Plastic Pollution Detection](https://www.kaggle.com/datasets/arnavs19/underwater-plastic-pollution-detection)  

---

## 📊 Problem Statement  
**Why is underwater plastic detection challenging?**  
- 🌑 **Low lighting conditions** affect visibility and color contrast.  
- 🌊 **Motion blur & sensor noise** make segmentation complex.  
- 🔄 **Overlapping waste objects** complicate object detection.  
- ♻️ **Diverse waste materials** require precise classification.  

---

## 🛠️ Methodology  

### **1️⃣ Noise Reduction**
| **Filter Type**       | **Description** | **Pros** | **Cons** |
|------------------|--------------|---------|--------|
| **Gaussian Filter** | Smooths image, removes Gaussian noise | Fast & simple | Blurs edges |
| **Median Filter** | Removes salt-and-pepper noise | Preserves edges | Less effective for Gaussian noise |
| **Bilateral Filter** | Preserves edges while reducing noise | Maintains textures | Computationally expensive |
| **Anisotropic Diffusion** | Adaptive noise removal | Excellent edge preservation | Needs parameter tuning |

### **2️⃣ Segmentation Methods**  
We applied five different **segmentation techniques** to detect plastic waste:  

| **Method** | **Accuracy** | **Strengths** | **Weaknesses** |
|------------|------------|----------------------------|----------------------|
| **K-Means Clustering** | 89.3% | Fast, easy implementation | Sensitive to initialization |
| **Mean-Shift Segmentation** | 92.1% | Robust to noise, adaptive | Slow for large images |
| **Felzenszwalb Segmentation** | 95.6% | Preserves structure, efficient | Sensitive to parameters |
| **Watershed Segmentation** | 93.4% | Works well for high-contrast images | Requires preprocessing |
| **SLIC Superpixels** | 90.2% | Edge-preserving, computationally efficient | Needs parameter tuning |

---

## 📈 Evaluation Metrics  
We used **three key metrics** to assess segmentation accuracy:  
✔ **IoU (Intersection over Union)** – Measures how well predicted masks overlap with the ground truth.  
✔ **Dice Coefficient** – Similarity measure between the predicted and actual segmentation.  
✔ **Pixel Accuracy** – Percentage of correctly classified pixels in the image.  

**Results:**  

