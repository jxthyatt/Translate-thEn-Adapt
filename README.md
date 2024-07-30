# Translate-thEn-Adapt (TEA)
Official repository for the submitted paper “Federated Hallucination Translation and Source-free Regularization Adaptation in Decentralized Domain Adaptation for Foggy Scene Understanding”. Previous version of Code is [here](https://github.com/jxthyatt/DDA-CoSoAdapt). Final Code will be released after acceptance.

## Replicate Demo and Results
### GTA5 to Foggy Cityscapes ( :four_leaf_clover: TABLE I)
:rocket: We provide quantitative results and checkpoint files in demo “from [GTA5](https://download.visinf.tu-darmstadt.de/data/from_games/) to [Foggy Cityscapes](https://www.cityscapes-dataset.com/)” ( :warning: here model is tested on Foggy Cityscapes dataset). Please view more details in TABLE I.


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


:hotsprings: **Note:** A and B refer to federated domain adaptation and source-free domain adaptation in the field of DDA. RIPU will stand aside from the peer comparison since it acts as active domain adaptation to use a few target labels.


We visualize examples of foggy scene understanding in demo “from [GTA5](https://download.visinf.tu-darmstadt.de/data/from_games/) to [Foggy Cityscapes](https://www.cityscapes-dataset.com/)” ( :warning: here model is tested on Foggy Cityscapes dataset). Compared to federated or source-free DDA baseline, our TEA (DisCoGAN+ProRA) obtains 55.26% in mIoU to reach state-of-the-art performance for SFSU.
<p align="center">
<img src="assets/Fig9.pdf" width="700px"/></p>

### SYNTHIA to Foggy Cityscapes ( :four_leaf_clover: TABLE II)
:rocket: We provide quantitative results and checkpoint files in demo “from [SYNTHIA](https://synthia-dataset.net/) to [Foggy Cityscapes](https://www.cityscapes-dataset.com/)” (here model is tested on Foggy Cityscapes dataset). Please view more details in TABLE II.


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


:hotsprings: **Note:** A and B refer to federated domain adaptation and source-free domain adaptation in the field of DDA. RIPU will stand aside from the peer comparison since it acts as active domain adaptation to use a few target labels.


We visualize examples of foggy scene understanding in demo “from [SYNTHIA](https://synthia-dataset.net/) to [Foggy Cityscapes](https://www.cityscapes-dataset.com/)” (here model is tested on Foggy Cityscapes dataset). Compared to federated or source-free DDA baseline, our TEA (DisCoGAN+ProRA) obtains 51.82% in mIoU to reach state-of-the-art performance for SFSU.
<p align="center">
<img src="assets/Fig10.pdf" width="700px"/></p>

### GTA5 to Foggy Driving ( :four_leaf_clover: TABLE III)
:rocket: We provide quantitative results and checkpoint files in demo “from [GTA5](https://download.visinf.tu-darmstadt.de/data/from_games/) to [Foggy Driving](https://people.ee.ethz.ch/~csakarid/SFSU_synthetic/)” ( :warning: here model is tested on unseen Foggy Driving dataset). Please view more details in TABLE III.


| Method                    | DDA        | Pub’Year            | FC            | FD            | FZ            | Checkpoint file                                                          |
|---------------------------|------------|---------------------|---------------|---------------|---------------|--------------------------------------------------------------------------|
| Source only               | -          | -                   | 31.39         | 33.24         | 23.33         | [Link](https://pan.baidu.com/s/1fEMzwyZtniHnEouLHuwiUA) (Code: 566j)     |
| ADVENT                    | &#10007;   | CVPR’19             | 36.89         | 33.48         | 21.71         | [Link](https://pan.baidu.com/s/14U8ecye-ngEzmXjmpCBs2g) (Code: 2xik)     |
| DISE                      | &#10007;   | CVPR’19             | 41.47         | 34.63         | 22.40         | [Link](https://pan.baidu.com/s/1bbVd58voU39uasFX7SgiFQ) (Code: ixnw)     |
| CAG-UDA                   | &#10007;   | NeurIPS’19          | 45.44         | 35.60         | 37.04         | [Link](https://pan.baidu.com/s/1dNB8IfjrbPIfP3RdJL4FFA) (Code: 8cqq)     |
| MaxSquareLoss             | &#10007;   | ICCV’19             | 38.28         | 35.38         | 24.14         | [Link](https://pan.baidu.com/s/1t-OAsEVnWBJjTu46zvsKnQ) (Code: pviq)     |
| Classes Matter            | &#10007;   | ECCV’20             | 36.53         | 29.59         | 23.31         | [Link](https://pan.baidu.com/s/14ZhBL8HEqplEYbqOJ-iAxQ) (Code: bmcy)     |
| ASANet                    | &#10007;   | TIP’21              | 36.15         | 30.30         | 20.95         | [Link](https://pan.baidu.com/s/1sUoGUYvHgTIQrjqF7E738w) (Code: 29ay)     |
| RobustNet                 | &#10007;   | CVPR’21             | 38.38         | 32.90         | 25.84         | [Link](https://pan.baidu.com/s/1bwpohufMajJg32OAd1ad4w) (Code: 7kki)     |
| Seg-Uncertainty           | &#10007;   | IJCV’21             | 48.17         | 38.39         | 26.39         | [Link](https://pan.baidu.com/s/19Rk-eBtk-7KOWUx2Mp3AZw) (Code: df78)     |
| DisCoGAN (ours)           | &#10003;   | TMM’24              | 43.05         | 35.91         | 30.47         | [Link](https://pan.baidu.com/s/1BLAhZkDKzk0r2crS6BvDoQ) (Code: 4ng5)     |
| ProRA (ours)              | &#10003;   | TMM’24              | 49.71         | 37.65         | 32.28         | [Link](https://pan.baidu.com/s/1n2xCu49kXcVPmTgrlzptBg) (Code: iqgc)     |
| DisCoGAN+ProRA (ours)     | &#10003;   | TMM’24              | 55.26         | 42.24         | 35.51         | [Link](https://pan.baidu.com/s/1tI3rlI0969DwfNwFYZUFcQ) (Code: cswk)     |



