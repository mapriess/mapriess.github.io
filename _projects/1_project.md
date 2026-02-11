---
layout: page
title: Automated Invoice Recognition
description: Improving Applicability of Deep Learning based Token Classification models.
# img: assets/img/Automated-Invoice-Recognition.jpg
importance: 3
category: work
---

This project focuses on improving the practical applicability of deep learning 
models for automated invoice recognition. Using **LayoutLM-based models** for token 
classification on German receipts, the project addresses a critical gap in model 
evaluation during training.

The core challenge tackled in this project is that conventional classification 
metrics like F1-Score are insufficient for evaluating whether machine learning 
models are truly ready for production deployment. To solve this problem, the 
project developed a **novel evaluation metric** called **Document Integrity 
Precision (DIP)**, specifically designed for visual document understanding and 
token classification tasks.

DIP provides a rigorous measure of how many documents in the test dataset require 
manual interventions, enabling AI researchers and software developers to 
**accurately assess the level of process automation achievable in business software**. 
Unlike conventional metrics that may show minimal changes despite significant model 
impairments, DIP reliably indicates when models would require substantial human 
intervention in deployment.

The project includes comprehensive experiments demonstrating that as the number of 
predicted entities increases, conventional metrics become less sensitive, leading to 
poor automation quality assessments. DIP, in contrast, provides a single 
interpretable value for entire entity sets, making it an essential metric for 
business-focused model training.

This research project highlights the importance of task-specific evaluation metrics 
in production environments and opens avenues for developing similar metrics for 
other training tasks beyond token classification.