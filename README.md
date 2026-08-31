# SAR-OPT-Dataset
This repository is used by me to store the SAR-OPT datasets I use, including the specific divisions and download links, as well as the baseline test indicators I provide myself (SSIM/PSNR/RMSE/LIPIS/SAM/FID/KID). Each method was trained and tested on three independent random seeds: 42, 43, and 44, with average metrics and standard deviations calculated.

# Comparison on the WHU-900-198 dataset

| Method | SSIM(%)↑ | PSNR(dB)↑ | FID↓ | KID(×100)↓ | LPIPS(%)↓ | RMSE(×100)↓ | SAM(×100)↓ |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **WHU-900-198** | | | | | | | |
| CycleGAN (17 *ICCV*) | 40.78 ± 1.66 | 19.85 ± 0.71 | 156.70 ± 10.80 | 6.29 ± 1.48 | 49.32 ± 1.03 | 10.75 ± 0.83 | 7.63 ± 0.47 |
| Pix2pix (17 *ICPR*) | 42.23 ± 1.62 | 21.14 ± 0.25 | 191.63 ± 11.05 | 8.30 ± 0.48 | 49.13 ± 1.90 | 9.65 ± 0.31 | 7.44 ± 0.35 |
| Pix2pixHD (18 *CVPR*) | 37.99 ± 0.29 | 22.34 ± 0.06 | 173.02 ± 1.40 | 9.02 ± 0.21 | 40.93 ± 0.27 | 8.09 ± 0.05 | 5.46 ± 0.08 |
| CUT (20 *ECCV*) | 33.45 ± 0.08 | 18.83 ± 0.08 | 144.04 ± 2.67 | 4.30 ± 0.11 | 50.45 ± 0.43 | 11.94 ± 0.19 | 8.89 ± 0.40 |
| NICE-GAN (20 *CVPR*) | 35.98 ± 2.14 | 19.24 ± 1.00 | 164.22 ± 2.42 | 6.59 ± 0.60 | 49.29 ± 3.40 | 11.49 ± 1.36 | 8.17 ± 1.81 |
| UGATIT (20 *ICLR*) | 38.75 ± 0.23 | 20.43 ± 0.35 | 141.72 ± 3.53 | 4.53 ± 0.54 | 47.33 ± 0.35 | 10.27 ± 0.46 | 7.05 ± 0.20 |
| F-LSeSim (21 *CVPR*) | 39.06 ± 3.28 | 19.54 ± 0.46 | 163.69 ± 27.98 | 7.02 ± 4.39 | 50.14 ± 1.71 | 11.47 ± 0.19 | 8.85 ± 1.50 |
| ASGIT (21 *CVPR*) | 38.61 ± 1.04 | 19.48 ± 0.88 | 216.27 ± 20.01 | 14.66 ± 2.91 | 51.16 ± 4.92 | 10.98 ± 1.15 | 7.47 ± 0.79 |
| WFLM-GAN (22 *TGRS*) | 42.46 ± 0.69 | 23.11 ± 0.04 | 225.95 ± 11.31 | 15.46 ± 1.67 | 40.35 ± 0.24 | 7.42 ± 0.01 | 4.69 ± 0.05 |
| ParallelGAN (22 *TGRS*) | 36.17 ± 2.91 | 20.92 ± 0.82 | 220.55 ± 8.31 | 14.44 ± 1.70 | 46.24 ± 2.15 | 10.06 ± 1.40 | 6.28 ± 0.81 |
| StegoGAN (24 *CVPR*) | 39.59 ± 2.30 | 19.58 ± 0.32 | 152.39 ± 18.22 | 5.64 ± 2.20 | 48.72 ± 0.38 | 11.08 ± 0.36 | 8.31 ± 0.90 |
| PatchGCL (24 *AAAI*) | 33.90 ± 3.86 | 19.11 ± 1.69 | 175.66 ± 44.78 | 9.31 ± 6.36 | 50.31 ± 3.16 | 11.63 ± 2.04 | 9.28 ± 1.95 |
| UNSB (24 *ICLR*) | 33.97 ± 1.82 | 19.10 ± 0.44 | 153.68 ± 25.42 | 5.89 ± 2.96 | 51.61 ± 3.21 | 11.64 ± 0.55 | 8.96 ± 0.11 |

## dataset url
Link: https://pan.baidu.com/s/1X97kPnHnK9n5DfoMM_dneg?pwd=qfcm 
Password: qfcm 
