# CLIP

**Authors**: Radford et al.
**Year**: 2021
**Link**: https://arxiv.org/abs/2103.00020
**Implementation**: https://github.com/mrsddq/clip-image-captioning

## Key Contribution
CLIP learns aligned image-text representations from large-scale contrastive pretraining.

## What I Implemented / Adapted
The captioning repo freezes CLIP as the visual encoder and trains caption decoders on cached image embeddings.
