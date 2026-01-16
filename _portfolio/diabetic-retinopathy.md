---
title: "Diabetic Retinopathy Detection using Vision Transformers"
excerpt: "Deep learning system for automated diabetic retinopathy screening achieving 94% accuracy using Vision Transformers, deployed on AWS Lambda<br/><br/>![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)"
collection: portfolio
---

## Project Overview

This project implements a state-of-the-art **Vision Transformer (ViT)** model for automated diabetic retinopathy detection from retinal fundus images. The system achieves **94% accuracy** in classifying disease severity levels, providing a crucial tool for early detection and prevention of diabetes-related vision loss.

## Key Achievements

- **High Accuracy**: 94% classification accuracy on diabetic retinopathy severity levels
- **Modern Architecture**: Leverages Vision Transformers for superior feature learning from retinal images
- **Production Deployment**: Fully containerized and deployed on AWS Lambda for scalable predictions
- **Fast Inference**: Optimized for real-time screening in clinical settings

## Technical Stack

### Deep Learning Framework
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
- Vision Transformer (ViT) architecture
- Custom preprocessing pipeline for retinal images
- Transfer learning from pre-trained medical imaging models

### API & Deployment
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
- RESTful API for image upload and prediction
- Asynchronous request handling
- Input validation and error handling

### Containerization
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
- Multi-stage Docker builds for optimized image size
- Reproducible development and production environments
- Easy deployment across different platforms

### Cloud Infrastructure
![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)
- Serverless deployment for cost-effective scaling
- API Gateway integration for HTTPS endpoints
- S3 integration for model artifact storage

## Model Architecture

The Vision Transformer processes retinal images by:
1. Dividing images into fixed-size patches
2. Linearly embedding each patch
3. Adding positional embeddings
4. Processing through transformer encoder layers
5. Classification head for severity prediction

## Clinical Impact

This system assists ophthalmologists by:
- Providing rapid screening results
- Prioritizing high-risk patients
- Reducing diagnostic workload
- Enabling early intervention for vision preservation
