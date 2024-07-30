# Translate-thEn-Adapt (TEA)
Official repository for the submitted paper “Federated Hallucination Translation and Source-free Regularization Adaptation in Decentralized Domain Adaptation for Foggy Scene Understanding”. Previous version of Code is [here](https://github.com/jxthyatt/DDA-CoSoAdapt). Final Code will be released after acceptance.

## Replicate Demo and Results
### GTA5 to Foggy Cityscapes (TABLE I)
We provide quantitative results and checkpoint files in demo “from GTA5 to Foggy Cityscapes” (here model is tested on Foggy Cityscapes dataset). Please view more details in TABLE I.


| Method                       | DDA            | Pub’Year            | mIoU            | Gain                  | Checkpoint file                                                          |
|------------------------------|----------------|---------------------|-----------------|-----------------------|--------------------------------------------------------------------------|
| Source only                  | -              | -                   | 31.4            | -                     | [Link](https://pan.baidu.com/s/1oSwHCyXoibNPgvUDZhXHjA) (Code: ppdu)     |
| CycleGAN                     | A              | ICCV’17             | 39.3            | 7.9                   | [Link](https://pan.baidu.com/s/1ZVP4hEG7eAjMlGW-sm30Zw) (Code: f63p)     |
| UNIT                         | A              | NeurIPS’17          | 25.7            | -5.7                  | [Link](https://pan.baidu.com/s/1WXROAUMtjSjUTUla3-Z8Wg) (Code: vsfp)     |
| MUNIT                        | A              | ECCV’18             | 21.9            | -9.5                  | [Link](https://pan.baidu.com/s/1Bu6Z7fqPGzMnJmc9I6_z_Q) (Code: pkvf)     |
| DRIT++                       | A              | IJCV’20             | 40.4            | 9.0                   | [Link](https://pan.baidu.com/s/1SjgJmxEv3mvl9dX6ewYImg) (Code: sb24)     |
| CUT                          | A              | ECCV’20             | 39.4            | 8.0                   | [Link](https://pan.baidu.com/s/1wrNf4h8BpbUbRGTDDrqLqg) (Code: hpfg)     |
| NEGCUT                       | A              | ICCV’21             | 36.0            | 4.6                   | [Link](https://pan.baidu.com/s/1Sm6f3-gBHTK92PIWWL5rEQ) (Code: cgkp)     |
| LADD                         | A              | WACV’23             | 35.3            | -6.0                  | [Link](https://pan.baidu.com/s/15b-FM28T3hy96UwGZ0Gw4g) (Code: spfj)     |
| DisCoGAN (ours)              | A              | TMM’24              | 43.0            | 11.6                  | [Link](https://pan.baidu.com/s/1A7gP80mf9oAq8N_b6YxT2A) (Code: dtm3)     |
| SFDA-Seg                     | B              | ICCV’21             | 44.5            | 13.1                  | [Link](https://pan.baidu.com/s/1jBJRnpIAy0CrXSyf3Fe4PA) (Code: bv4s)     |
| HCL                          | B              | NeurIPS’21          | 37.8            | 6.4                   | [Link](https://pan.baidu.com/s/1Gqczq98cUFqCp92nYPs9tw) (Code: rxv3)     |
| LDBE                         | B              | MM’21               | 48.2            | 16.8                  | [Link](https://pan.baidu.com/s/1VRKlzCyiIe6KPc4TMfVk-w) (Code: v376)     |
| ProDA                        | B              | CVPR’21             | 49.2            | 17.8                  | [Link](https://pan.baidu.com/s/1e2UJqMONeqDWZTkIQsRuEw) (Code: gsrt)     |
| SFOCDA                       | B              | TCSVT’22            | 38.7            | 7.3                   | [Link](https://pan.baidu.com/s/1Uq-UDZUkUFlhquvoJi978Q) (Code: wfye)     |
| ProCA                        | B              | ECCV’22             | 44.8            | 13.4                  | [Link](https://pan.baidu.com/s/1jX9-SRLl0G9GpKsoHWtYAg) (Code: dh4b)     |
| RIPU                         | B              | CVPR’22             | 66.8            | 35.4                  | [Link](https://pan.baidu.com/s/1POl7UtLrBplN-OUoV17bmw) (Code: niu9)     |
| SimT                         | B              | TPAMI’23            | 54.6            | 23.2                  | [Link](https://pan.baidu.com/s/1hcw9mOR0FVW5uVcr3hGnUQ) (Code: kq8w)     |
| DisCoGAN+ProRA (ours)        | B              | TMM’24              | 55.3            | 23.9                  | [Link](https://pan.baidu.com/s/15B2o1f46rkMcWl_1zWkPNw) (Code: hp3h)     |

Note: A and B refer to federated domain adaptation and source-free domain adaptation in the field of DDA. RIPU will stand aside from the peer comparison since it acts as active domain adaptation to use a few target labels.


We visualize examples of foggy scene understanding in demo “from GTA5 to Foggy Cityscapes” (here model is tested on Foggy Cityscapes dataset). Compared to federated or source-free DDA baseline, our TEA (DisCoGAN+ProRA) obtains 55.26% in mIoU to reach state-of-the-art performance for SFSU.
<p align="center">
<img src="assets/Fig9.pdf" width="700px"/></p>

### SYNTHIA to Foggy Cityscapes (TABLE II)
We provide quantitative results and checkpoint files in demo “from SYNTHIA to Foggy Cityscapes” (here model is tested on Foggy Cityscapes dataset). Please view more details in TABLE II.


| Method                       | DDA            | Pub’Year            | mIoU            | Gain                  | Checkpoint file                                                          |
|------------------------------|----------------|---------------------|-----------------|-----------------------|--------------------------------------------------------------------------|
| Source only                  | -              | -                   | 27.2            | -                     | [Link](https://pan.baidu.com/s/17K2VJVJkjrY-KOUwDNOjoA) (Code: ses8)     |
| CycleGAN                     | A              | ICCV’17             | 38.8            | 11.6                  | [Link](https://pan.baidu.com/s/1TLcvC1kkKdAd80Tj5DIEfg) (Code: vtex)     |
| UNIT                         | A              | NeurIPS’17          | 31.6            | 4.4                   | [Link](https://pan.baidu.com/s/1Ro30WEFC0NIOc_ye0Y-kCw) (Code: 4dfn)     |
| MUNIT                        | A              | ECCV’18             | 19.2            | -8.0                  | [Link](https://pan.baidu.com/s/15jGyInrCvRFS5901HdWMEg) (Code: tkpt)     |
| DRIT++                       | A              | IJCV’20             | 37.5            | 10.3                  | [Link](https://pan.baidu.com/s/1TnqcrC7HNHLKdJ0nu2F36w) (Code: p334)     |
| CUT                          | A              | ECCV’20             | 35.9            | 8.7                   | [Link](https://pan.baidu.com/s/1GVtMJU1QbJeSls5gq54yGw) (Code: eth5)     |
| NEGCUT                       | A              | ICCV’21             | 31.2            | 4.0                   | [Link](https://pan.baidu.com/s/16fnnhYwl_ClEEzfJuScx-A) (Code: 9enn)     |
| LADD                         | A              | WACV’23             | 32.9            | 5.7                   | [Link](https://pan.baidu.com/s/1VDULhtLO4VLy7W0l1v-9rw) (Code: exc4)     |
| DisCoGAN (ours)              | A              | TMM’24              | 39.5            | 12.3                  | [Link](https://pan.baidu.com/s/10xerTzDBD2KlOriyjDux9g) (Code: hswv)     |
| SFDA-Seg                     | B              | ICCV’21             | 35.3            | 8.1                   | [Link](https://pan.baidu.com/s/1i_WcN8wlZRI8T0T1FMS8IA) (Code: yf92)     |
| HCL                          | B              | NeurIPS’21          | 36.9            | 9.7                   | [Link](https://pan.baidu.com/s/1FP6A6Hk3IxFBhcgNVrNUfA) (Code: neci)     |
| LDBE                         | B              | MM’21               | 36.1            | 8.9                   | [Link](https://pan.baidu.com/s/1PrZ0PPoMFy_4JTalV3_cUg) (Code: 5e62)     |
| ProDA                        | B              | CVPR’21             | 44.1            | 16.9                  | [Link](https://pan.baidu.com/s/1sA0UltvMwOXLTgXMsxiRrw) (Code: 4xxj)     |
| SFOCDA                       | B              | TCSVT’22            | 35.5            | 8.3                   | [Link](https://pan.baidu.com/s/15a_Ew5pdVin-VhNDMh-Gww) (Code: 4t7a)     |
| ProCA                        | B              | ECCV’22             | 35.7            | 8.5                   | [Link](https://pan.baidu.com/s/1vtYfofLBfWT6FpRozzSgNg) (Code: tjaj)     |
| RIPU                         | B              | CVPR’22             | 67.1            | 39.9                  | [Link](https://pan.baidu.com/s/1nUqCxo-RgNmDY3ls3_hKBg) (Code: w274)     |
| SimT                         | B              | TPAMI’23            | 40.6            | 13.4                  | [Link](https://pan.baidu.com/s/1xGZLqVaf-vc_WkEGZMDL0w) (Code: 59n5)     |
| DisCoGAN+ProRA (ours)        | B              | TMM’24              | 51.8            | 24.6                  | [Link](https://pan.baidu.com/s/1wRYMnvXb-IwxELRgUZzr_A) (Code: 4i2u)     |

Note: A and B refer to federated domain adaptation and source-free domain adaptation in the field of DDA. RIPU will stand aside from the peer comparison since it acts as active domain adaptation to use a few target labels.


We visualize examples of foggy scene understanding in demo “from SYNTHIA to Foggy Cityscapes” (here model is tested on Foggy Cityscapes dataset). Compared to federated or source-free DDA baseline, our TEA (DisCoGAN+ProRA) obtains 51.82% in mIoU to reach state-of-the-art performance for SFSU.
<p align="center">
<img src="assets/Fig10.pdf" width="700px"/></p>







