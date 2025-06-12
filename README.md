## **Medical Synthetic Referral Classification**


### **=> Objective**

Simulate a healthcare setting where real clinical data is unavailable due to privacy laws. Generate synthetic medical referral documents and build a classifier to categorize them by:
Urgency: routine vs urgent

### **=> Tasks Overview**
1) Generate Synthetic Referral Records
Programmatically create realistic PDF/image referral documents with varied patient cases and regional formats (e.g., Ontario vs. BC).

2) Add Metadata
Include structured fields: patient contact, referral date, DOB, healthcare ID, etc. Document assumptions (e.g., ID formats).

3) Define Classification Targets
Label each document by specialty and/or urgency level. Choose one clear classification task and explain your rationale.

4) Train a Classifier
Build an ML model (e.g., fine-tuned BERT or SVM) to classify referrals from unstructured text. Split into train/test and explain design choices, evaluation, and potential overfitting to synthetic patterns.

5) Reflect & Report
Document your process, challenges (e.g., class imbalance, realism), and potential real-world applications. Address risks of synthetic data and suggest next steps for production readiness.

### **=> Real-World Impact**

This mirrors real hospital workflows, where auto-triaging of referrals can accelerate patient care. Use this project to explore how AI + synthetic data can enable safe prototyping in sensitive domains.

Medical_Referral_Urgency_Classifier_with_UrgencyColumn.ipynb – This notebook uses a dataset with a dedicated Urgency column and performs classification from scratch using that label.

Medical_Referral_Urgency_Classifier_finetuning.ipynb – In this approach, there is no explicit Urgency column. Instead, urgency is inferred from the symptom descriptions using a fine-tuned DistilBERT model.


Note: Before running the notebooks, please ensure that the logo image is uploaded to the runtime environment or update the path accordingly. I have not included a logo in this repository, an appropriate image can be added
