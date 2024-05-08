# Torch ViT

### Quickstart

Install with `pip install torch_vit` and load a pretrained ViT with:

```python
from torch_vit import ViT
model = ViT('B_16_imagenet1k', pretrained=True)
```

### Overview
This repository contains an PyTorch reimplementation of the [Visual Transformer](https://openreview.net/forum?id=YicbFdNTTy) architecture from [Google](https://github.com/google-research/vision_transformer), along with pre-trained models and and wrapper modules and examples. Some other variations will developed in next releases

The goal of this implementation is to be simple, highly extensible, and easy to integrate into your own projects.

* **At the moment, you can easily:**
  * Loading Pretrained ViT Models
  * Evaluate on ImageClassification or Custom data
  * Finetune ViT on Custom Dataset
