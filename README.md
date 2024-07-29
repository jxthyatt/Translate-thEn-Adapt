# Translate-thEn-Adapt (TEA)
Official repository for the submitted paper “Federated Hallucination Translation and Source-free Regularization Adaptation in Decentralized Domain Adaptation for Foggy Scene Understanding”. Previous version of Code is [here](https://github.com/jxthyatt/DDA-CoSoAdapt). Final Code will be released after acceptance.

## Replicate Demo and Results
### GTA5 to Foggy Cityscapes
We provide quantitative results and checkpoint files in demo “from GTA5 to Foggy Cityscapes” (here model is tested on Foggy Cityscapes dataset). Please view more details in TABLE I.

| Method                       | DDA            | Pub’Year            | mIoU            | Gain                  | Checkpoint file                                                          |
|------------------------------|----------------|---------------------|-----------------|-----------------------|--------------------------------------------------------------------------|
| Source only                  | -              | -                   | 31.4            | -                     | [Link](https://pan.baidu.com/s/1oSwHCyXoibNPgvUDZhXHjA) (Code: ppdu)     |
| CycleGAN                     | A              | ICCV’17             | 39.3            | 7.9                   | [Link](https://pan.baidu.com/s/1ZVP4hEG7eAjMlGW-sm30Zw) (Code: f63p)     |
| UNIT                         | A              | NeurIPS’17          | 25.7            | -5.7                  | [Link](https://pan.baidu.com/s/1WXROAUMtjSjUTUla3-Z8Wg) (Code: vsfp)     |
| MUNIT                        | A              | ECCV’18             | 21.9            | -9.5                  | [Link](https://pan.baidu.com/s/1Bu6Z7fqPGzMnJmc9I6_z_Q) (Code: pkvf)     |
| DRIT++                       | A              | IJCV’20             | 40.4            | 9.0                   | -                                                                        |
| CUT                          | A              | ECCV’20             | 39.4            | 8.0                   | [Link](https://pan.baidu.com/s/1wrNf4h8BpbUbRGTDDrqLqg) (Code: hpfg)     |
| NEGCUT                       | A              | ICCV’21             | 36.0            | 4.6                   | [Link](https://pan.baidu.com/s/1Sm6f3-gBHTK92PIWWL5rEQ) (Code: cgkp)     |
| LADD                         | A              | WACV’23             | 35.3            | -6.0                  | -                                                                        |
| DisCoGAN (ours)              | A              | TMM’24              | 43.0            | 11.6                  | [Link](https://pan.baidu.com/s/1A7gP80mf9oAq8N_b6YxT2A) (Code: dtm3)     |
| SFDA-Seg                     | B              | ICCV’21             | 44.5            | 13.1                  | [Link](https://pan.baidu.com/s/1jBJRnpIAy0CrXSyf3Fe4PA) (Code: bv4s)     |
| HCL                          | B              | NeurIPS’21          | 37.8            | 6.4                   | [Link](https://pan.baidu.com/s/1Gqczq98cUFqCp92nYPs9tw) (Code: rxv3)     |
| LDBE                         | B              | MM’21               | 48.2            | 16.8                  | -                                                                        |
| ProDA                        | B              | CVPR’21             | 49.2            | 17.8                  | [Link](https://pan.baidu.com/s/1e2UJqMONeqDWZTkIQsRuEw) (Code: gsrt)     |
| SFOCDA                       | B              | TCSVT’22            | 38.7            | 7.3                   | [Link](https://pan.baidu.com/s/1Uq-UDZUkUFlhquvoJi978Q) (Code: wfye)     |
| ProCA                        | B              | ECCV’22             | 44.8            | 13.4                  | [Link](https://pan.baidu.com/s/1jX9-SRLl0G9GpKsoHWtYAg) (Code: dh4b)     |
| RIPU                         | B              | CVPR’22             | 66.8            | 35.4                  | [Link](https://pan.baidu.com/s/1POl7UtLrBplN-OUoV17bmw) (Code: niu9)     |
| SimT                         | B              | TPAMI’23            | 54.6            | 23.2                  | [Link](https://pan.baidu.com/s/1hcw9mOR0FVW5uVcr3hGnUQ) (Code: kq8w)     |
| DisCoGAN+ProRA (ours)        | B              | TMM’24              | 55.3            | 23.9                  | [Link](https://pan.baidu.com/s/15B2o1f46rkMcWl_1zWkPNw) (Code: hp3h)     |


