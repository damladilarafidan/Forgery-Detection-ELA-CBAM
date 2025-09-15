# Forgery-Detection-ELA-CBAM
Official implementation of the paper "Forgery Detection in Digital Images using ELA and Attention-based CNN Architecture". Includes ELA preprocessing, CBAM-based CNN training, and evaluation on CASIA v1.0/v2.0 and CoMoFoD datasets.
# Forgery Detection in Digital Images using ELA and Attention-based CNN Architecture

This repository provides the official implementation of the paper:

**Forgery Detection in Digital Images using ELA and Attention-based CNN Architecture**  
*(Damla Dilara Fidan, Gül Tahaoglu, 2025)*

---

## 📖 Overview
This work proposes a forgery detection framework that combines **Error Level Analysis (ELA)** preprocessing with a **CNN enhanced by Convolutional Block Attention Module (CBAM)**.  
The method is evaluated on three benchmark datasets: **CASIA v1.0, CASIA v2.0, and CoMoFoD**.  
Our results demonstrate that incorporating ELA preprocessing and CBAM improves the detection of tampered images compared to baseline CNN and existing attention-based approaches.

---

## 📂 Contents
- `preprocessing/` → Scripts for applying **ELA** on datasets  
- `models/` → CNN + CBAM implementation  
- `train.py` → Training script with configurable parameters  
- `evaluate.py` → Evaluation on CASIA and CoMoFoD datasets  
- `results/` → Experimental results and logs  

---

## 📊 Datasets
The experiments were conducted on:
- **CASIA v1.0 and v2.0**  
- **CoMoFoD (JPEG subset)**  

> ⚠️ Due to licensing restrictions, datasets are **not included** in this repository. Please download them from the official sources.

---

## 🔗 Citation
If you use this code in your research, please cite:

```bibtex
@inproceedings{fidan2025forgery,
  title={Forgery Detection in Digital Images using ELA and Attention-based CNN Architecture},
  author={Fidan, Damla Dilara and Tahaoglu, Gül},
  year={2025},
  booktitle={Proceedings of IEEE ...}
}
