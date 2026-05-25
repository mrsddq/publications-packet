# Benchmarking Neural Network Robustness to Common Corruptions

**Authors**: Hendrycks and Dietterich
**Year**: 2019
**Link**: https://arxiv.org/abs/1903.12261
**Implementation**: https://github.com/mrsddq/vit-robustness-xai

## Key Contribution
ImageNet-C evaluates common corruptions across corruption type and severity using corruption error and mCE.

## What I Implemented / Adapted
`scripts/generate_corruptions.py` creates local corruption sets and `scripts/compute_mce.py` computes mCE from evaluation CSVs.
