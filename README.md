
# QLab2025 Task

The two projects based on Timeseries and Image Restoration.

# Time Series: 

W&B Dashboard URL: https://wandb.ai/hvpatel-me-nit-patna/QLabIntern2025_Imputation/table?nw=nwuserhvpatelme

## Multivariate Time series Imputation using Transformer Encoder : 
#### (Filename: P1T1) 



1. Dataset: [exchange](https://drive.google.com/file/d/1EBLfP2Dx2K7LsSZybX4JJes-wEcTJbz-/view?usp=drive_link.) 

2. Use the above dataset and train the transformer encoder with random mask ratios {12.5%, 25%, 37.5%, 50%}, with sequence length set to 96. 

3. Use any online resources for model development. Calculate MSE and MAE for different mask ratios and visualize results. 

 

## Time series forecasting using DLinear : 
#### (Filename: P1T2)

1. Dataset: [exchange](https://drive.google.com/file/d/1EBLfP2Dx2K7LsSZybX4JJes-wEcTJbz-/view?usp=drive_link.) 

2. Train using the given dataset with a sequence length of 96 and a prediction length of 14. 

3. Calculate MSE and MAE for univariate (last feature) and multivariate settings and visualize results. 

4. Ref to this paper for model:  [DLinear](https://arxiv.org/abs/2205.13504) 

 

## Multivariate Time series forecasting using Conditional Diffusion Model (DDPM): 
#### (Filename: P1T3)

 1. Dataset Train: [timeseries_train.xlsx](https://indianinstituteofscience-my.sharepoint.com/:x:/g/personal/mothishg_iisc_ac_in/EWznM8dvt8hMgMg_plv4sUIBuFItAeCg25xugbQpm-eiMQ?e=ZlFqop)

 2. Dataset Test: [timeseries_test.xlsx](https://indianinstituteofscience-my.sharepoint.com/:x:/g/personal/mothishg_iisc_ac_in/EVsoPcgyHXdHoSx4a_A_OxsBzxhAqGHQM4aZ7w0nmOU84Q?e=R7SXab) 

 3. Train using the given dataset with a sequence length of 96 and a prediction length of 14. 

 4. Calculate MSE and MAE for univariate (last feature) and multivariate settings and visualize results. 

 

# Image Restoration: 

## Denoising using DNCNN architecture 
#### (Filename: P2T1)

1. Dataset: [CBSD68](https://github.com/clausmichele/CBSD68-dataset.git) 

2. Use noisy35, original folders as paired set to train a Denoiser network 

3. Model: [DNCNN](https://arxiv.org/abs/1608.03981) 

4. Calculate PSNR and SSIM and visualize the results. 

 
## Denoising using Unet architecture 
#### (Filename: P2T2)

1. Dataset: [CBSD68](https://github.com/clausmichele/CBSD68-dataset.git) 

2. Use noisy35, original folders as paired set to train a Denoiser network 

3. Calculate PSNR and SSIM and visualize the results. 

 

 

 

 
