---
library_name: keras
datasets:
- competitions/aiornot
metrics:
- accuracy
---

## Model description

A model that detects AI generated iamge

## Intended uses & limitations

Intended for use cases whenever real images are needed and not AI generated ones. This model however cannot distinguish an AI generated movie whenever it has a close resemblance with a real image.

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:

| Hyperparameters | Value |
| :-- | :-- |
| name | Adam |
| weight_decay | None |
| clipnorm | None |
| global_clipnorm | None |
| clipvalue | None |
| use_ema | False |
| ema_momentum | 0.99 |
| ema_overwrite_frequency | None |
| jit_compile | True |
| is_legacy_optimizer | False |
| learning_rate | 0.0010000000474974513 |
| beta_1 | 0.9 |
| beta_2 | 0.999 |
| epsilon | 1e-07 |
| amsgrad | False |
| training_precision | float32 |


 ## Model Plot

<details>
<summary>View Model Plot</summary>

![Model Image](./model.png)

</details>