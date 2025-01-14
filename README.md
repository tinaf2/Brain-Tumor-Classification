# Brain-Tumor-Classification-with-ML
This repository contains a Brain Tumor Classification project that leverages deep learning to categorize MRI scans into four classes: Glioma, Meningioma, Pituitary, or No Tumor. The workflow includes:

<u>Data Processing</u>: Automated collection and labeling of MRI images from a Kaggle dataset, augmented with brightness shifts and normalization.

Transfer Learning: Fine-tuning a pretrained Xception model (ImageNet weights) for fast and accurate classification.

Custom CNN: A smaller, custom architecture built from scratch to compare performance, memory usage, and flexibility.

Model Evaluation: Thorough metrics (accuracy, precision, recall) alongside confusion matrices and classification reports.

Interpretability: Generation of saliency maps to visualize where the model “looks” in the MRI image, plus optional LLM-based explanations to clarify the model’s decision-making.

Deployment: A Streamlit web app that allows users to upload scans, select a model, and receive interactive predictions and saliency overlays—all accessible via ngrok for quick demonstrations.

This end-to-end solution highlights best practices in data ingestion, model training, explainability, and rapid prototyping of medical AI tools.
