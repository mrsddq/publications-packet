# U-Net: Convolutional Networks for Biomedical Image Segmentation

**Authors**: Ronneberger, Fischer, Brox
**Year**: 2015
**Link**: https://arxiv.org/abs/1505.04597
**Implementation**: https://github.com/mrsddq/medical-segmentation

## Problem Statement
Biomedical segmentation often has limited annotated data and requires precise localization.

## Key Contribution
- Encoder-decoder architecture with skip connections.
- Heavy augmentation for small biomedical datasets.
- Pixel-wise segmentation from sparse labels.

## What I Implemented / Adapted
The repository implements the U-Net baseline in `models/unet.py` and uses it as the reference model before Attention U-Net.

## Critical Assessment
The 2D formulation is practical and fast, but it ignores 3D context in volumetric scans.
