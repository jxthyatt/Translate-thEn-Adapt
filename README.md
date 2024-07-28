# Translate-thEn-Adapt (TEA)
Official repository for the submitted paper “Federated Hallucination Translation and Source-free Regularization Adaptation in Decentralized Domain Adaptation for Foggy Scene Understanding”. Previous version of Code is [here](https://github.com/jxthyatt/DDA-CoSoAdapt). Final Code will be released after acceptance.

## Replicate Demo and Results
### GTA5 to Foggy Cityscapes
We provide quantitative results and pretrained weights in demo “GTA5 to Foggy Cityscapes” (here model is tested on Foggy Cityscapes dataset). Please find more details in TABLE I.

| Method                       | DDA            | Pub’Year            | mIoU            | mIoU Gain             | Weight file                                                          |
|------------------------------|----------------|---------------------|-----------------|-----------------------|----------------------------------------------------------------------|
| Source only                  | -              | -                   | 31.4            | 0.9276 ± 0.0087 | [Link](https://pan.baidu.com/s/175BXR675dQSyhFX14bk5zg) (Code: l4oh) |
| CycleGAN                     | A              | ICCV’17             | 39.3            | 0.9276 ± 0.0087 |[Link](https://pan.baidu.com/s/175BXR675dQSyhFX14bk5zg) (Code: l4oh) |
| UNIT                         | A              | NeurIPS’17          | 25.7            | 0.9327 ± 0.0104 | [Link](https://pan.baidu.com/s/175BXR675dQSyhFX14bk5zg) (Code: l4oh) |
| MUNIT                        | A              | ECCV’18             | 21.9            | 0.9237 ± 0.0089 | [Link](https://pan.baidu.com/s/175BXR675dQSyhFX14bk5zg) (Code: l4oh) |
| DRIT++                       | A              | IJCV’20             | 40.4            | 0.9295 ± 0.0049 | [Link](https://pan.baidu.com/s/175BXR675dQSyhFX14bk5zg) (Code: l4oh) |
| CUT                          | A              | ECCV’20             | 39.4            | 0.9279 ± 0.0077 | -                                                                    |
| NEGCUT                       | A              | ICCV’21             | 36.0            | 0.9279 ± 0.0077 | -                                                                    |
| LADD                         | A              | WACV’23             | 35.3            | 0.9279 ± 0.0077 | -                                                                    |
| TEA$^\dagger$ (ours)         | A              | TMM’24              | 43.0            | 0.9279 ± 0.0077 | -                                                                    |
| SFDA-Seg                     | B              | ICCV’21             | 44.5            | 0.9279 ± 0.0077 | -                                                                    |
| HCL                          | B              | NeurIPS’21          | 37.8            | 0.9279 ± 0.0077 | -                                                                    |
| LDBE                         | B              | ACMMM’21            | 48.2            | 0.9279 ± 0.0077 | -                                                                    |
| ProDA                        | B              | CVPR’21             | 49.2            | 0.9279 ± 0.0077 | -                                                                    |
| SFOCDA                       | B              | TCSVT’22            | 38.7            | 0.9279 ± 0.0077 | -                                                                    |
| ProCA                        | B              | ECCV’22             | 44.8            | 0.9279 ± 0.0077 | -                                                                    |
| RIPU$^\ast$                  | B              | CVPR’22             | 66.8            | 0.9279 ± 0.0077 | -                                                                    |
| SimT                         | B              | TPAMI’23            | 54.6            | 0.9279 ± 0.0077 | -                                                                    |
| TEA$^\ddagger$ (ours)        | B              | TMM’24              | 55.3            | 0.9279 ± 0.0077 | -                                                                    |
