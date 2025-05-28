# QLab2025

A collection of two research-oriented projects focused on Time Series analysis and Image Restoration.

## Overview

- **Time Series:**
  - **P1T1:** Multivariate Time Series Imputation using Transformer Encoder
  - **P1T2:** Time Series Forecasting using DLinear
  - **P1T3:** Multivariate Time Series Forecasting using Conditional Diffusion Model (DDPM)

- **Image Restoration:**
  - **P2T1:** Denoising using DNCNN Architecture
  - **P2T2:** Denoising using Unet Architecture

## Time Series

### Datasets

- **Exchange Dataset:** Used for P1T1 and P1T2. [Download](https://drive.google.com/file/d/1EBLfP2Dx2K7LsSZybX4JJes-wEcTJbz-/view?usp=drive_link)
- **Timeseries Train Dataset:** Used for P1T3. [Download](https://indianinstituteofscience-my.sharepoint.com/:x:/g/personal/mothishg_iisc_ac_in/EWznM8dvt8hMgMg_plv4sUIBuFItAeCg25xugbQpm-eiMQ?e=ZlFqop)
- **Timeseries Test Dataset:** Used for P1T3. [Download](https://indianinstituteofscience-my.sharepoint.com/:x:/g/personal/mothishg_iisc_ac_in/EVsoPcgyHXdHoSx4a_A_OxsBzxhAqGHQM4aZ7w0nmOU84Q?e=R7SXab)

### Tasks

Each task is associated with a specific filename within the project repository.

#### P1T1: Multivariate Time Series Imputation using Transformer Encoder

- **Filename:** P1T1
- **Objective:** Train a transformer encoder to impute missing values in multivariate time series data with mask ratios of 12.5%, 25%, 37.5%, and 50%.
- **Sequence Length:** 96
- **Evaluation Metrics:** MSE, MAE
- **Visualization:** Plot results for different mask ratios.
- **Resources:** Use any online resources for model development.

#### P1T2: Time Series Forecasting using DLinear

- **Filename:** P1T2
- **Objective:** Implement and train the DLinear model for time series forecasting.
- **Sequence Length:** 96
- **Prediction Length:** 14
- **Settings:** Univariate (last feature) and Multivariate
- **Evaluation Metrics:** MSE, MAE
- **Visualization:** Compare results for univariate and multivariate settings.
- **Reference:** [DLinear Paper](https://arxiv.org/abs/2205.13504)

#### P1T3: Multivariate Time Series Forecasting using Conditional Diffusion Model (DDPM)

- **Filename:** P1T3
- **Objective:** Develop a conditional diffusion model for multivariate time series forecasting.
- **Sequence Length:** 96
- **Prediction Length:** 14
- **Settings:** Univariate (last feature) and Multivariate
- **Evaluation Metrics:** MSE, MAE
- **Visualization:** Compare results for univariate and multivariate settings.

## Experiment Tracking

- **Weights & Biases (W&B) Dashboard:** Track and visualize experiments. [Dashboard URL](https://wandb.ai/hvpatel-me-nit-patna/QLabIntern2025_Imputation/table?nw=nwuserhvpatelme)


<p>
</p>


## Image Restoration

### Dataset

- **CBSD68 Dataset:** Used for both P2T1 and P2T2. Clone from [GitHub Repository](https://github.com/clausmichele/CBSD68-dataset.git)
  - Use `noisy35` and `original` folders as paired sets for training denoiser networks.

### Tasks

Each task is associated with a specific filename within the project repository.

#### P2T1: Denoising using DNCNN Architecture

- **Filename:** P2T1
- **Objective:** Train a denoiser network using the DNCNN architecture.
- **Evaluation Metrics:** PSNR, SSIM
- **Visualization:** Display denoised images and metrics.
- **Reference:** [DNCNN Paper](https://arxiv.org/abs/1608.03981)

#### P2T2: Denoising using Unet Architecture

- **Filename:** P2T2
- **Objective:** Train a denoiser network using the Unet architecture.
- **Evaluation Metrics:** PSNR, SSIM
- **Visualization:** Display denoised images and metrics.


## References

* Zhou, Y. et al., "DnCNN: Beyond a Gaussian Denoiser" (2017).
* Zeng, F. et al., "DLinear: Simplifying Time Series Forecasting with Linear Models" (2022).
* Ho, J. et al., "Denoising Diffusion Probabilistic Models" (2020).

---


