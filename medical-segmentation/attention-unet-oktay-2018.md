# Attention U-Net

**Authors**: Oktay et al.
**Year**: 2018
**Link**: https://arxiv.org/abs/1804.03999
**Implementation**: https://github.com/mrsddq/medical-segmentation

## Key Contribution
Attention gates suppress irrelevant skip-connection activations before decoder fusion.

## What I Implemented / Adapted
`models/attention_unet.py` adds attention gates to the skip pathways and is configured by `configs/attention_unet.yaml`.

## Critical Assessment
Attention gates add parameters and compute, so the comparison must include a plain U-Net baseline.
