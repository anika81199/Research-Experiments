
# List of Experiments

| S.No.| Experiment Name |
| -------- | -------- |
| 0| Creating test dataset (from BSDS300) such that it contains 10 classes with 50 images each with different noises, blurs added to it|
| 1| Training an autoencoder model to reconstruct the original image |
| 2| Visualizing the impact of Various Noises and Blurs on Images using t-SNE Plot of Encoded test Vectors |
| 3| Training an u-net model for better reconstructions and t-SNE |
| 4|  Visualizing the impact of combined distortions : Gaussian blur and Gaussian noise on t-SNE plot|
| 5|  Calculating PSNRs on BSDS300 and Unsplash Dataset for u-net model |
| 6|  Analyzing the trade-off between reducing bottleneck size and the PSNR of reconstruction |
| 7| Analyzing the impact of adding 1x1 Conv layer on Image Reconstruction Quality |
| 8|  Analyzing the reconstructions after introducing random black boxes in the image for models 32x32x8, 32x32x1, 16x16x8, 16x16x1, 8x8x8, 8x8x1 |
| 9|   Analyzing the reconstructions after introducing gaussian noise of different variances in the image for models 32x32x8, 32x32x1, 16x16x8, 16x16x1, 8x8x8, 8x8x1 |
| 10| Analyzing reconstruction after doing PCA (U-Net model) | Not done |
| 11|  Analyzing reconstruction after doing PCA (Autoencoder model) | 