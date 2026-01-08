Autism Care — MRI-based Autism Detection using Deep Learning

Overview

Autism Care is a deep learning–based research project focused on detecting Autism Spectrum Disorder (ASD) using structural brain MRI data.
The project explores how modern deep learning architectures—particularly Vision Transformers (ViT) and CNN-based models (ResNet)—can be applied to neuroimaging data to assist in early autism detection.

The work emphasizes model architecture design, preprocessing for medical imaging, and experimental evaluation, with the goal of supporting data-driven clinical insights.

Problem Statement

Early diagnosis of Autism Spectrum Disorder is challenging due to:
	•	Subtle neuroanatomical differences
	•	High variability across individuals
	•	Dependence on behavioral assessments

This project formulates autism detection as a binary classification problem using brain MRI scans, aiming to identify structural patterns associated with ASD using deep learning.

Dataset
	•	Dataset: ABIDE (Autism Brain Imaging Data Exchange)
	•	Modality: Structural MRI (sMRI)
	•	Labels:
	•	ASD
	•	Neurotypical control

The dataset is publicly available for research purposes and requires appropriate approval for access.


Methodology

1️ Preprocessing
	•	Skull stripping and intensity normalization
	•	Noise reduction and spatial alignment
	•	Signal enhancement to improve Signal-to-Noise Ratio (SNR)
→ Achieved ~30% improvement in SNR


2️ Model Architecture
	•	Vision Transformers (ViT) for capturing global spatial dependencies
	•	ResNet-based CNNs for hierarchical feature extraction
	•	Hybrid experimentation to compare CNN vs Transformer representations


3️ Training & Evaluation
	•	Binary classification setup
	•	Loss optimization using standard deep learning techniques
	•	Evaluation metrics:
	•	Accuracy
	•	Precision
	•	Recall

Best observed performance:
	•	92% classification accuracy on validation data



Results & Insights
	•	Transformer-based models demonstrated strong capability in capturing global structural patterns in MRI data
	•	Proper preprocessing significantly impacted downstream model performance
	•	Results indicate the potential of deep learning–based approaches as decision-support tools, not diagnostic replacements


 Research Contribution
	•	Designed and evaluated a deep learning pipeline for autism detection using MRI
	•	Conducted architectural comparisons between CNNs and Transformers
	•	Extracted neuroimaging-driven insights relevant to ASD classification

Research paper based on this work is currently under peer review.

Tech Stack
	•	Programming Language: Python
	•	Frameworks: PyTorch
	•	Models: Vision Transformers (ViT), ResNet
	•	Data Handling: NumPy, Pandas
	•	Visualization: Matplotlib
	•	Dataset: ABIDE
