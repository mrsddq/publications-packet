# Medical Segmentation One-Pager

## Problem

Segment anatomical or lesion regions from medical images using a reproducible U-Net baseline.

## Method

2D U-Net with encoder-decoder skip connections, Dice/BCE-style training objective, and planned de-identified overlay reporting.

## Evidence Needed

- public dataset run such as CHAOS, KiTS, or Medical Segmentation Decathlon
- Dice and IoU table
- overlay examples
- failure-case discussion

## Limitation

Current implementation is 2D and does not capture full volumetric context.
