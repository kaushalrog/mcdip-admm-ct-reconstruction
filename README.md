# MCDIP-ADMM: Low-Dose CT Reconstruction

This repository contains an experimental implementation of an **unsupervised CT image reconstruction framework** based on **ADMM combined with Deep Image Prior (DIP)**.  
The project explores a **Multi-Code DIP (MCDIP) ensemble approach** to reduce overfitting and improve reconstruction quality in low-dose CT imaging.

## Project Overview
- CT reconstruction is modeled as an inverse problem: `y = Ax + n`
- Low-dose CT introduces severe noise and artifacts
- Deep Image Prior (DIP) helps without pre-training but suffers from overfitting
- This project mitigates overfitting using **MCDIP + ADMM**

## Key Contributions
- Integration of **ADMM framework** with **Multi-Code Deep Image Priors**
- Ensemble averaging of multiple DIP networks for stability
- Adaptive stopping strategy to reduce noise fitting
- Fully **unsupervised approach** (no training dataset required)

## Experimental Setup
- Synthetic CT data using Shepp-Logan phantom
- Radon transform for projection simulation
- Gaussian noise to simulate low-dose conditions
- Evaluation using PSNR and SSIM

## Files in This Repository
