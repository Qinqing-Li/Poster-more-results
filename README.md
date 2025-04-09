# Read me

**Hi!** 👋 This repository contains some visual results for my poster *"Performance comparison of multi-modality MRI segmentation models"*. It compares two different image fusion methods — **DDcGAN** and **SwinFusion** — for the task of segmenting brain tumours from MRI scans.<br><br>


The `ddcgan_visualisations/` and `swin_fusion_visualisations/` folders each contain 500 PNG images (50 patients × 10 slices). Each sample shows:

- 🖼️ the fused image (T2-Flare image + T1CE image),

- 🎯 the ground truth segmentation,

- 🤖 the tumour segmentation predicted by the segmentation model.
