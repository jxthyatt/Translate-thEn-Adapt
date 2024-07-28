# Translate-thEn-Adapt (TEA)
Official repository for the submitted paper “Federated Hallucination Translation and Source-free Regularization Adaptation in Decentralized Domain Adaptation for Foggy Scene Understanding”. Previous version of Code is [here](https://github.com/jxthyatt/DDA-CoSoAdapt). Final Code will be released after acceptance.

## Replicate Demo and Results
### GTA5 to Foggy Cityscapes
We provide quantitative results and pretrained weights in demo “GTA5 to Foggy Cityscapes” (here model is tested on Foggy Cityscapes dataset). Please find more details in TABLE I.

| Method                       | DDA            | Pub’Year            | mIoU            | Gain                  | Checkpoint file                                                          |
|------------------------------|----------------|---------------------|-----------------|-----------------------|--------------------------------------------------------------------------|
| Source only                  | -              | -                   | 31.4            | 0.0                   | -                                                                    |
| CycleGAN                     | A              | ICCV’17             | 39.3            | 7.9                   | -                                                                    |
| UNIT                         | A              | NeurIPS’17          | 25.7            | -5.7                  | -                                                                    |
| MUNIT                        | A              | ECCV’18             | 21.9            | -9.5                  | -                                                                    |
| DRIT++                       | A              | IJCV’20             | 40.4            | 9.0                   | -                                                                    |
| CUT                          | A              | ECCV’20             | 39.4            | 8.0                   | -                                                                    |
| NEGCUT                       | A              | ICCV’21             | 36.0            | 4.6                   | -                                                                    |
| LADD                         | A              | WACV’23             | 35.3            | -6.0                  | -                                                                    |
| TEA$^\dagger$ (ours)         | A              | TMM’24              | 43.0            | 11.6                  | -                                                                    |
| SFDA-Seg                     | B              | ICCV’21             | 44.5            | 13.1                  | -                                                                    |
| HCL                          | B              | NeurIPS’21          | 37.8            | 6.4                   | -                                                                    |
| LDBE                         | B              | ACMMM’21            | 48.2            | 16.8                  | -                                                                    |
| ProDA                        | B              | CVPR’21             | 49.2            | 17.8                  | -                                                                    |
| SFOCDA                       | B              | TCSVT’22            | 38.7            | 7.3                   | -                                                                    |
| ProCA                        | B              | ECCV’22             | 44.8            | 13.4                  | -                                                                    |
| RIPU$^\ast$                  | B              | CVPR’22             | 66.8            | 35.4                  | -                                                                    |
| SimT                         | B              | TPAMI’23            | 54.6            | 23.2                  | -                                                                                |
| TEA$^\ddagger$ (ours)        | B              | TMM’24              | 55.3            | 23.9                  | [Link](https://pan.baidu.com/s/1F5UihtsKg4H_j9OaDc17cg) (Code: abqn)    |
