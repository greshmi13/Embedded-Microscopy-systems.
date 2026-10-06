# Embedded Intelligent Microscopy System for Identification and Counting of Marine Organisms

## 📌 Project Overview

The **Embedded Intelligent Microscopy System for Identification and Counting of Microscopic Marine Organisms** is an AI based prototype designed to automate the detection, identification, and counting of microscopic marine organisms from microscopy images.

The system combines **YOLOv8 object detection, OpenCV image processing, Google Colab model training, Raspberry Pi 4 Model B deployment, and an interactive dashboard** for visualization and analysis.

Unlike approaches limited to a small fixed set of organisms, our system follows an **expandable, dataset driven approach**, where additional organism categories can be incorporated through annotated training data and model retraining.

---

## 🎯 Objectives

- Automate microscopic marine organism detection and identification.
- Automatically count organisms class wise and in total.
- Reduce dependence on manual microscopic observation and counting.
- Perform lightweight AI inference on Raspberry Pi 4 Model B.
- Provide confidence scores and bounding boxes for detected organisms.
- Generate annotated images and CSV reports.
- Compare organism abundance between different sample conditions.
- Provide an expandable framework for adding new organism categories.
- Provide a user friendly dashboard for monitoring and analysis.

---

## 🔬 System Workflow

```text
Microscopic Marine Organism Dataset
                ↓
             Annotation
                ↓
       Train / Validation / Test
                ↓
          Google Colab
                ↓
          YOLOv8n Training
                ↓
        Model Evaluation
                ↓
          Model Export
                ↓
       Raspberry Pi 4 Model B
                ↓
       OpenCV Preprocessing
                ↓
          YOLO Inference
                ↓
       Confidence Filtering
                ↓
            Counting
                ↓
          Backend API
                ↓
           Dashboard
          ↙          ↘
 Annotated Image     CSV Report
          \          /
           ↓        ↓
          Sample Comparison
                ↓
       Observations & Reporting
