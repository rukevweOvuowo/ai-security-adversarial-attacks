# Adversarial Attack Evaluation on Deep Learning Models

## Overview
This project focuses on evaluating the robustness of deep learning models against multiple adversarial attacks. The goal is to simulate real-world AI security threats by performing AI red teaming and analyzing how different attack strategies impact model performance.

The project implements and compares several gradient-based adversarial attacks on image classification models, identifying vulnerabilities and measuring their effectiveness.

---

## Objectives
- Assess the robustness of deep learning models under adversarial conditions  
- Compare the effectiveness of multiple attack strategies  
- Quantify model performance degradation  
- Identify the most impactful adversarial techniques  
- Support the development of more robust AI systems  

---

## Models Evaluated
- VGG  
- ResNet  
- GoogLeNet  

---

##  Adversarial Attacks Implemented
- TPGD (Targeted PGD)
- MIFGSM (Momentum Iterative FGSM)
- TIFGSM (Translation-Invariant FGSM)
- NIFGSM (Nesterov Iterative FGSM)
- Jitter Attack

---

## Methodology
1. Load trained deep learning model  
2. Iterate over the test dataset  
3. Generate adversarial samples for each attack  
4. Compare predictions (original vs adversarial)  
5. Track performance metrics (accuracy, loss, success rate)  
6. Compute and compare success rates across attacks  

---

## Key Metrics
- Attack Success Rate  
- Model Accuracy Drop  
- Comparative Attack Performance  

---

## 📈 Results
- Up to 90% attack success rate  
- Up to 35% drop in classification accuracy  
- Identification of most effective attack  


---

## 🛠️ Technologies Used
- Python  
- PyTorch  
- torchattacks  
- NumPy  

---

## 💡 Insights
- Deep learning models are vulnerable to adversarial perturbations  
- Small changes can significantly impact predictions  
- Some attack variants outperform others  
- Robustness evaluation is critical for secure AI  



