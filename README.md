# Face Recognition Fine-Tuning

This project demonstrates fine-tuning of a **FaceNet-based face recognition model** using high-quality and low-quality image datasets.  
The goal is to evaluate baseline performance, fine-tune the model, and compare results before and after training.

---

## 📂 Dataset Description
- 8 individuals with images separated into:
  - **High_quality** → sharp, clear images (used for training/fine-tuning)
  - **Low_quality** → blurred, noisy images (used for evaluation/testing)

This split simulates real-world scenarios like CCTV vs professional photos.

---

## 🚀 Steps Implemented
1. **Baseline Evaluation**
   - Extract embeddings using pretrained FaceNet.
   - Evaluate with ROC curve, Precision-Recall curve, similarity distributions.

2. **Fine-Tuning**
   - Trained the model on high-quality images for 10 epochs.
   - Saved fine-tuned model checkpoint.

3. **Post-Fine-Tuning Evaluation**
   - Re-evaluated on test data.
   - Compared ROC, PR, and similarity scores with baseline.

---

## 📊 Results

### Baseline Performance
- ROC AUC: ~0.66
- Average Precision: ~0.66

### After Fine-Tuning
- Micro-average ROC AUC: ~0.85
- PR curve improved significantly for most classes.

---

## 🖼️ Sample Outputs
- Baseline ROC Curve  
- Precision-Recall Curve  
- Similarity Distribution  
- Fine-tuned ROC & PR curves  

---

