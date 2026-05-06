# PatchRecDeepFakeDetection

Official code repository for:

**Patch-Based Reconstruction and Multimodal Residual Learning for Generalized Deepfake Detection**

## Abstract

Deepfake detectors often achieve near-perfect accuracy in-domain but fail under dataset or forgery shifts, especially when only a few manipulated samples are available for training. We propose a two-stage framework for generalized and data-efficient deepfake detection based on reconstruction residuals. In Stage I, we learn a real-face prior with PM-VAE, a masked patch reconstructor that augments a Masked Autoencoder with a lightweight variational bottleneck to regularize the patch latent space and reduce memorization. In Stage II, the generator is frozen and used to produce forensic evidence from partially observed inputs via block-wise masking on the patch grid; the resulting inpainted reconstructions yield residual cues that are stable and localized. We then train a multi-branch Transformer to fuse (i) RGB context, (ii) spatial residuals, and (iii) wavelet-domain residuals that explicitly capture high-frequency inconsistencies missed by spatial errors alone. Extensive experiments on FaceForensics++ dataset under cross-forgery protocols, on external benchmarks (Celeb-DF, DFD, DFDC) for cross-dataset evaluation, and on synthetic generation (StyleGAN family and Stable Diffusion) show improved robustness over reconstruction baselines, with consistent gains in low-data regimes down to a handful of fake frames per video.

## Figure 1

Figure 1 will be added soon.

## TODO

Code will be uploaded soon.
