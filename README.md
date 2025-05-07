# Balloon Detection with DETR

Detecting party balloons in images and video using Facebook AI Research’s **DEtection TRansformer (DETR)** architecture.

| Section | Quick Link |
|---------|-----------|
| [Overview](#overview) | [Project Structure](#project-structure) |
| [Setup](#setup) | [Training](#training) |
| [Evaluation & Metrics](#evaluation--metrics) | [Inference Demo](#inference-demo) |
| [Results](#results) | [Acknowledgements](#acknowledgements) |

---

## Overview
This repository contains everything needed to train, evaluate, and demo a DETR model that locates **balloons** in images:

* **Single‑class object detection** (class = `balloon`)
* Small, custom dataset annotated in COCO format
* Reproducible training pipeline in a single Jupyter notebook (`CV.ipynb`)
* Side‑by‑side performance comparison **with** and **without** data augmentation

---

## Project Structure
