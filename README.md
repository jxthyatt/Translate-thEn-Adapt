# Translate-thEn-Adapt ( :tea:TEA)
Official repository for the submitted paper “Federated Hallucination Translation and Source-free Regularization Adaptation in Decentralized Domain Adaptation for Foggy Scene Understanding”. Previous version of Code is [here](https://github.com/jxthyatt/DDA-CoSoAdapt). :rainbow: Final Code will be released after acceptance.

## Replicate Demo and Results
### GTA5 to Foggy Cityscapes ( :herb::herb: TABLE I)
:rocket::rocket: We provide quantitative results and checkpoint files in demo “from [GTA5](https://download.visinf.tu-darmstadt.de/data/from_games/) to [Foggy Cityscapes](https://www.cityscapes-dataset.com/)” ( :star: here model is tested on Foggy Cityscapes dataset). Please view more details in TABLE I.


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
| RIPU :asterisk:              | B              | CVPR’22             | 66.8            | 35.4                  | [Link](https://pan.baidu.com/s/1POl7UtLrBplN-OUoV17bmw) (Code: niu9)     |
| SimT                         | B              | TPAMI’23            | 54.6            | 23.2                  | [Link](https://pan.baidu.com/s/1hcw9mOR0FVW5uVcr3hGnUQ) (Code: kq8w)     |
| DisCoGAN+ProRA (ours)        | B              | TMM’24              | 55.3            | 23.9                  | [Link](https://pan.baidu.com/s/15B2o1f46rkMcWl_1zWkPNw) (Code: hp3h)     |


:hotsprings: **Note:** A and B refer to federated domain adaptation and source-free domain adaptation in the field of DDA. RIPU :asterisk: will stand aside from the peer comparison since it acts as active domain adaptation to use a few target labels.


:airplane::airplane: We visualize examples of foggy scene understanding in demo “from [GTA5](https://download.visinf.tu-darmstadt.de/data/from_games/) to [Foggy Cityscapes](https://www.cityscapes-dataset.com/)” ( :star: here model is tested on Foggy Cityscapes dataset). Compared to federated or source-free DDA baseline, our TEA (DisCoGAN+ProRA) obtains 55.26% in mIoU to reach state-of-the-art performance for SFSU.
<p align="center">
<img src="assets/Fig9.pdf" width="700px"/></p>


### SYNTHIA to Foggy Cityscapes ( :herb::herb: TABLE II)
:rocket::rocket: We provide quantitative results and checkpoint files in demo “from [SYNTHIA](https://synthia-dataset.net/) to [Foggy Cityscapes](https://www.cityscapes-dataset.com/)” ( :star: here model is tested on Foggy Cityscapes dataset). Please view more details in TABLE II.


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
| HCL                          | B              | NeurIPS’21          | 36.9            | 9.7                   | [Link](https://pan.baidu.com/s/1XBh_ELFpseHxJr0ODqD3xw) (Code: 3f8r)     |
| LDBE                         | B              | MM’21               | 36.1            | 8.9                   | [Link](https://pan.baidu.com/s/1PrZ0PPoMFy_4JTalV3_cUg) (Code: 5e62)     |
| ProDA                        | B              | CVPR’21             | 44.1            | 16.9                  | [Link](https://pan.baidu.com/s/1sA0UltvMwOXLTgXMsxiRrw) (Code: 4xxj)     |
| SFOCDA                       | B              | TCSVT’22            | 35.5            | 8.3                   | [Link](https://pan.baidu.com/s/15a_Ew5pdVin-VhNDMh-Gww) (Code: 4t7a)     |
| ProCA                        | B              | ECCV’22             | 35.7            | 8.5                   | [Link](https://pan.baidu.com/s/1vtYfofLBfWT6FpRozzSgNg) (Code: tjaj)     |
| RIPU :asterisk:              | B              | CVPR’22             | 67.1            | 39.9                  | [Link](https://pan.baidu.com/s/1nUqCxo-RgNmDY3ls3_hKBg) (Code: w274)     |
| SimT                         | B              | TPAMI’23            | 40.6            | 13.4                  | [Link](https://pan.baidu.com/s/1xGZLqVaf-vc_WkEGZMDL0w) (Code: 59n5)     |
| DisCoGAN+ProRA (ours)        | B              | TMM’24              | 51.8            | 24.6                  | [Link](https://pan.baidu.com/s/1wRYMnvXb-IwxELRgUZzr_A) (Code: 4i2u)     |


:hotsprings: **Note:** A and B refer to federated domain adaptation and source-free domain adaptation in the field of DDA. RIPU :asterisk: will stand aside from the peer comparison since it acts as active domain adaptation to use a few target labels.


:airplane::airplane: We visualize examples of foggy scene understanding in demo “from [SYNTHIA](https://synthia-dataset.net/) to [Foggy Cityscapes](https://www.cityscapes-dataset.com/)” ( :star: here model is tested on Foggy Cityscapes dataset). Compared to federated or source-free DDA baseline, our TEA (DisCoGAN+ProRA) obtains 51.82% in mIoU to reach state-of-the-art performance for SFSU.
<p align="center">
<img src="assets/Fig10.pdf" width="700px"/></p>


### GTA5 to Foggy Driving ( :herb::herb: TABLE III)
:rocket::rocket: We provide quantitative results and checkpoint files in demo “from [GTA5](https://download.visinf.tu-darmstadt.de/data/from_games/) to [Foggy Driving](https://people.ee.ethz.ch/~csakarid/SFSU_synthetic/)” ( :star: here model is tested on unseen datasets such as Foggy Driving and Foggy Zurich). Please view more details in TABLE III.


| Method                    | DDA        | Pub’Year            | FC            | FD            | FZ            | Checkpoint file                                                          |
|---------------------------|------------|---------------------|---------------|---------------|---------------|--------------------------------------------------------------------------|
| Source only               | -          | -                   | 31.39         | 33.24         | 23.33         | [Link](https://pan.baidu.com/s/1fEMzwyZtniHnEouLHuwiUA) (Code: 566j)     |
| ADVENT                    | &#10007;   | CVPR’19             | 36.89         | 33.48         | 21.71         | [Link](https://pan.baidu.com/s/14U8ecye-ngEzmXjmpCBs2g) (Code: 2xik)     |
| DISE                      | &#10007;   | CVPR’19             | 41.47         | 34.63         | 22.40         | [Link](https://pan.baidu.com/s/1HUPR8_O18mELWb40sfEMww) (Code: idai)     |
| CAG-UDA                   | &#10007;   | NeurIPS’19          | 45.44         | 35.60         | 37.04         | [Link](https://pan.baidu.com/s/1dNB8IfjrbPIfP3RdJL4FFA) (Code: 8cqq)     |
| MaxSquareLoss             | &#10007;   | ICCV’19             | 38.28         | 35.38         | 24.14         | [Link](https://pan.baidu.com/s/1t-OAsEVnWBJjTu46zvsKnQ) (Code: pviq)     |
| Classes Matter            | &#10007;   | ECCV’20             | 36.53         | 29.59         | 23.31         | [Link](https://pan.baidu.com/s/14ZhBL8HEqplEYbqOJ-iAxQ) (Code: bmcy)     |
| ASANet                    | &#10007;   | TIP’21              | 36.15         | 30.30         | 20.95         | [Link](https://pan.baidu.com/s/1sUoGUYvHgTIQrjqF7E738w) (Code: 29ay)     |
| RobustNet                 | &#10007;   | CVPR’21             | 38.38         | 32.90         | 25.84         | [Link](https://pan.baidu.com/s/1bwpohufMajJg32OAd1ad4w) (Code: 7kki)     |
| Seg-Uncertainty           | &#10007;   | IJCV’21             | 48.17         | 38.39         | 26.39         | [Link](https://pan.baidu.com/s/19Rk-eBtk-7KOWUx2Mp3AZw) (Code: df78)     |
| DisCoGAN (ours)           | &#10003;   | TMM’24              | 43.05         | 35.91         | 30.47         | [Link](https://pan.baidu.com/s/1BLAhZkDKzk0r2crS6BvDoQ) (Code: 4ng5)     |
| ProRA (ours)              | &#10003;   | TMM’24              | 49.71         | 37.65         | 32.28         | [Link](https://pan.baidu.com/s/1n2xCu49kXcVPmTgrlzptBg) (Code: iqgc)     |
| DisCoGAN+ProRA (ours)     | &#10003;   | TMM’24              | 55.26         | 42.24         | 35.51         | [Link](https://pan.baidu.com/s/1tI3rlI0969DwfNwFYZUFcQ) (Code: cswk)     |


:hotsprings: **Note:** &#10007; and &#10003; refer to conventional unsupervised domain adaptation (UDA) and privacy-preserving decentralized domain adaptation (DDA). Datasets include Foggy Cityscapes (FC), Foggy Driving (FD) and Foggy Zurich (FZ).


:airplane::airplane: We visualize examples of foggy scene understanding in demo “from [GTA5](https://download.visinf.tu-darmstadt.de/data/from_games/) to [Foggy Driving](https://people.ee.ethz.ch/~csakarid/SFSU_synthetic/)” ( :star: here model is tested on unseen Foggy Driving dataset). Compared to traditional UDA and DDA baselines, our TEA (DisCoGAN+ProRA) acquires 42.24% in mIoU to enable out-of-domain generalization for SFSU.
<p align="center">
<img src="assets/Fig11.pdf" width="700px"/></p>


### SYNTHIA to Foggy Driving ( :herb::herb: TABLE IV)
:rocket::rocket: We provide quantitative results and checkpoint files in demo “from [SYNTHIA](https://synthia-dataset.net/) to [Foggy Driving](https://people.ee.ethz.ch/~csakarid/SFSU_synthetic/)” ( :star: here model is tested on unseen datasets such as Foggy Driving and Foggy Zurich). Please view more details in TABLE IV.


| Method                    | DDA        | Pub’Year            | FC            | FD            | FZ            | Checkpoint file                                                          |
|---------------------------|------------|---------------------|---------------|---------------|---------------|--------------------------------------------------------------------------|
| Source only               | -          | -                   | 27.15         | 30.25         | 13.65         | [Link](https://pan.baidu.com/s/1R0pwqSI3aHoBlTVB9RwsUg) (Code: bq4c)     |
| ADVENT                    | &#10007;   | CVPR’19             | 32.91         | 31.98         | 15.69         | [Link](https://pan.baidu.com/s/1oJ2vBBHMuNTXN2l9cnfCfw) (Code: xp4g)     |
| DISE                      | &#10007;   | CVPR’19             | 39.28         | 33.07         | 18.27         | [Link](https://pan.baidu.com/s/1vcj22VDG0SaIjgqOTkCMlw) (Code: igyk)     |
| CAG-UDA                   | &#10007;   | NeurIPS’19          | 42.31         | 35.08         | 24.86         | [Link](https://pan.baidu.com/s/1joz8w9Msnm53xwJ6OWDlhQ) (Code: sfvz)     |
| MaxSquareLoss             | &#10007;   | ICCV’19             | 40.24         | 37.07         | 23.19         | [Link](https://pan.baidu.com/s/1gbsLo9FjRvN2LZtXXEntUw) (Code: p27s)     |
| Classes Matter            | &#10007;   | ECCV’20             | 44.61         | 41.26         | 25.39         | [Link](https://pan.baidu.com/s/1oPLhwlY9qvc-zmib0bdFAg) (Code: 5ji6)     |
| ASANet                    | &#10007;   | TIP’21              | 35.80         | 29.69         | 15.45         | [Link](https://pan.baidu.com/s/1YO3u0rj8h65pxar77q9TGQ) (Code: chcp)     |
| RobustNet                 | &#10007;   | CVPR’21             | 36.11         | 30.27         | 16.08         | [Link](https://pan.baidu.com/s/124mBiUn2zDPWyahWrvp5ew) (Code: vp6t)     |
| Seg-Uncertainty           | &#10007;   | IJCV’21             | 44.94         | 42.48         | 25.99         | [Link](https://pan.baidu.com/s/15uDP5zf1fANmKaK-WZ4mzg) (Code: 7w63)     |
| DisCoGAN (ours)           | &#10003;   | TMM’24              | 39.50         | 24.52         | 20.52         | [Link](https://pan.baidu.com/s/1mqZ1A1eGDK3bpwK8woPZUg) (Code: vvmj)     |
| ProRA (ours)              | &#10003;   | TMM’24              | 45.76         | 39.29         | 29.58         | [Link](https://pan.baidu.com/s/1OsKdMaGSphkLIob8FXaijw) (Code: 7gcf)     |
| DisCoGAN+ProRA (ours)     | &#10003;   | TMM’24              | 51.82         | 42.89         | 33.26         | [Link](https://pan.baidu.com/s/1H2JKVgltDbWJgadvl8cE-A) (Code: kkwf)     |


:hotsprings: **Note:** &#10007; and &#10003; refer to conventional unsupervised domain adaptation (UDA) and privacy-preserving decentralized domain adaptation (DDA). Datasets include Foggy Cityscapes (FC), Foggy Driving (FD) and Foggy Zurich (FZ).


:airplane::airplane: We visualize examples of foggy scene understanding in demo “from [SYNTHIA](https://synthia-dataset.net/) to [Foggy Driving](https://people.ee.ethz.ch/~csakarid/SFSU_synthetic/)” ( :star: here model is tested on unseen Foggy Driving dataset). Compared to traditional UDA and DDA baselines, our TEA (DisCoGAN+ProRA) acquires 42.89% in mIoU to enable out-of-domain generalization for SFSU.
<p align="center">
<img src="assets/Fig12.pdf" width="700px"/></p>


### GTA5 to Foggy Zurich ( :herb::herb: TABLE V)
:rocket::rocket: We provide quantitative results and checkpoint files in demo “from [GTA5](https://download.visinf.tu-darmstadt.de/data/from_games/) to [Foggy Zurich](https://people.ee.ethz.ch/~csakarid/Model_adaptation_SFSU_dense/)” ( :star: here model is tested on seen Foggy Zurich dataset). Please view more details in TABLE V.


| Method                    | Src/Mid/Tgt       | V :arrow_right: R    | C :arrow_right: F    | mIoU          | Gain          | Checkpoint file                                                          |
|---------------------------|-------------------|----------------------|----------------------|---------------|---------------|--------------------------------------------------------------------------|
| Source only               | -                 |                      |                      | 20.4          | -             | [Link](https://pan.baidu.com/s/1qp3rz1ojH_f5iUAInSm_7w) (Code: dhrp)     |
| DisCoGAN (ours)           | GTA/CZ/FZ         | &#10003;             |                      | 35.1          | 14.7          | [Link](https://pan.baidu.com/s/1onYBbSPQiefX_HUSX030gw) (Code: frtn)     |
| ProRA (ours)              | GTA/CZ/FZ         |                      | &#10003;             | 42.3          | 21.9          | [Link](https://pan.baidu.com/s/1lV-MMkMssR6NdBaMrEjAnA) (Code: vrwg)     |
| DisCoGAN+ProRA (ours)     | GTA/CZ/FZ         | &#10003;             | &#10003;             | 46.2          | 25.8          | [Link](https://pan.baidu.com/s/1A4kNRNk7EsXc33O10U2sJg) (Code: cma7)     |


:rocket::rocket: We also provide quantitative results and checkpoint files in demo “from [GTA5](https://download.visinf.tu-darmstadt.de/data/from_games/) to [Foggy Zurich](https://people.ee.ethz.ch/~csakarid/Model_adaptation_SFSU_dense/)” ( :star: here model is tested on unseen Foggy Driving dataset). They are not published in TABLE V.


| Method                    | Src/Mid/Tgt       | V :arrow_right: R    | C :arrow_right: F    | mIoU          | Gain          | Checkpoint file                                                          |
|---------------------------|-------------------|----------------------|----------------------|---------------|---------------|--------------------------------------------------------------------------|
| Source only               | -                 |                      |                      | 28.7          | -             | [Link](https://pan.baidu.com/s/1JY4JsvHwffUxBMqgjQDGfQ) (Code: nknr)     |
| DisCoGAN (ours)           | GTA/CZ/FD         | &#10003;             |                      | 30.4          | 1.7           | [Link](https://pan.baidu.com/s/1j_HxhNZqQwypOEx0JT4UHQ) (Code: u4bc)     |
| ProRA (ours)              | GTA/CZ/FD         |                      | &#10003;             | 35.2          | 6.5           | [Link](https://pan.baidu.com/s/1OApSmh6bycx6GVjiPRRV3A) (Code: tbnt)     |
| DisCoGAN+ProRA (ours)     | GTA/CZ/FD         | &#10003;             | &#10003;             | 37.7          | 9.0           | [Link](https://pan.baidu.com/s/14a2Gjc_JWmjo66-DR7gU6w) (Code: r98i)     |


:hotsprings: **Note:** Src/Mid/Tgt refer to source domain, middle domain and target domain. V :arrow_right: R and C :arrow_right: F refer to virtual-to-real and clear-to-foggy. Datasets include Clear Zurich (CZ), Foggy Zurich (FZ), Foggy Driving (FD), GTA5 (GTA) and SYNTHIA (SYN).


:airplane::airplane: We visualize examples of foggy scene understanding in demo “from [GTA5](https://download.visinf.tu-darmstadt.de/data/from_games/) to [Foggy Zurich](https://people.ee.ethz.ch/~csakarid/Model_adaptation_SFSU_dense/)” ( :star: here model is tested on Foggy Zurich dataset). DisCoGAN and ProRA refer to only 1st module and only 2nd module. Ultimately, DisCoGAN+ProRA gains a clear margin of 25.85% in mIoU to act as best relative value.
<p align="center">
<img src="assets/Fig13.pdf" width="700px"/></p>


### SYNTHIA to Foggy Zurich ( :herb::herb: TABLE V)
:rocket::rocket: We provide quantitative results and checkpoint files in demo “from [SYNTHIA](https://synthia-dataset.net/) to [Foggy Zurich](https://people.ee.ethz.ch/~csakarid/Model_adaptation_SFSU_dense/)” ( :star: here model is tested on seen Foggy Zurich dataset). Please view more details in TABLE V.


| Method                    | Src/Mid/Tgt       | V :arrow_right: R    | C :arrow_right: F    | mIoU          | Gain          | Checkpoint file                                                          |
|---------------------------|-------------------|----------------------|----------------------|---------------|---------------|--------------------------------------------------------------------------|
| Source only               | -                 |                      |                      | 12.4          | -             | [Link](https://pan.baidu.com/s/1YVa8uBLQHuGgj0UOXdbnCQ) (Code: 8gaa)     |
| DisCoGAN (ours)           | SYN/CZ/FZ         | &#10003;             |                      | 26.2          | 13.8          | [Link](https://pan.baidu.com/s/1iNuRGERGooVkAnTh6SFTXQ) (Code: wtcy)     |
| ProRA (ours)              | SYN/CZ/FZ         |                      | &#10003;             | 31.8          | 19.4          | [Link](https://pan.baidu.com/s/15I5yG4O2Y_dlXlwJFMsFkQ) (Code: 8v2a)     |
| DisCoGAN+ProRA (ours)     | SYN/CZ/FZ         | &#10003;             | &#10003;             | 36.4          | 24.0          | [Link](https://pan.baidu.com/s/1ewUtxuUtJG172on8upFZNg) (Code: rhiq)     |


:rocket::rocket: We also provide quantitative results and checkpoint files in demo “from [SYNTHIA](https://synthia-dataset.net/) to [Foggy Zurich](https://people.ee.ethz.ch/~csakarid/Model_adaptation_SFSU_dense/)” ( :star: here model is tested on unseen Foggy Driving dataset). They are not published in TABLE V.


| Method                    | Src/Mid/Tgt       | V :arrow_right: R    | C :arrow_right: F    | mIoU          | Gain          | Checkpoint file                                                          |
|---------------------------|-------------------|----------------------|----------------------|---------------|---------------|--------------------------------------------------------------------------|
| Source only               | -                 |                      |                      | 21.2          | -             | [Link](https://pan.baidu.com/s/1fPqNAfqQSAo8y2hJ5eNN8w) (Code: yebt)     |
| DisCoGAN (ours)           | SYN/CZ/FD         | &#10003;             |                      | 33.5          | 12.3          | [Link](https://pan.baidu.com/s/17ddO2dz7UC5gdS1GccvuWA) (Code: qquu)     |
| ProRA (ours)              | SYN/CZ/FD         |                      | &#10003;             | 36.8          | 15.6          | [Link](https://pan.baidu.com/s/1usiLuR1tRumYZ23OQ7EALQ) (Code: e7m9)     |
| DisCoGAN+ProRA (ours)     | SYN/CZ/FD         | &#10003;             | &#10003;             | 39.7          | 18.5          | [Link](https://pan.baidu.com/s/1HKQxRU644bgggHy51ozNTg) (Code: hxxg)     |


:hotsprings: **Note:** Src/Mid/Tgt refer to source domain, middle domain and target domain. V :arrow_right: R and C :arrow_right: F refer to virtual-to-real and clear-to-foggy. Datasets include Clear Zurich (CZ), Foggy Zurich (FZ), Foggy Driving (FD), GTA5 (GTA) and SYNTHIA (SYN).


:airplane::airplane: We visualize examples of foggy scene understanding in demo “from [SYNTHIA](https://synthia-dataset.net/) to [Foggy Zurich](https://people.ee.ethz.ch/~csakarid/Model_adaptation_SFSU_dense/)” ( :star: here model is tested on Foggy Zurich dataset). DisCoGAN and ProRA refer to only 1st module and only 2nd module. Ultimately, DisCoGAN+ProRA gains a clear margin of 24.03% in mIoU to act as best relative value.
<p align="center">
<img src="assets/Fig14.pdf" width="700px"/></p>


### Cityscapes to Foggy Cityscapes ( :herb::herb: TABLE VII)
:rocket::rocket: We provide quantitative results and checkpoint files in demo of image-to-image translation “from [Cityscapes](https://www.cityscapes-dataset.com/) to [Foggy Cityscapes](https://www.cityscapes-dataset.com/)” ( :star: here higher PSNR, SSIM, VIF and lower GMSD, LPIPS refer to better performance). Please view more details in TABLE VII.


| Method            | PSNR :arrow_up:      | SSIM :arrow_up:      | VIF :arrow_up:       | GMSD :arrow_down:      | LPIPS :arrow_down:     | Checkpoint file                                                          |
|-------------------|----------------------|----------------------|----------------------|------------------------|------------------------|--------------------------------------------------------------------------|
| CycleGAN          | 19.81                | 0.837                | 0.840                | 0.125                  | 0.126                  | [Link](https://pan.baidu.com/s/1KdhSOv0RdHHfJkeCyLp4Ww) (Code: m1wg)     |
| UNIT              | 15.91                | 0.541                | 0.797                | 0.185                  | 0.165                  | [Link](https://pan.baidu.com/s/11AZhEtt-icsT2wzrxQnXyw) (Code: q8rv)     |
| MUNIT             | 16.02                | 0.689                | 0.793                | 0.158                  | 0.222                  | [Link](https://pan.baidu.com/s/1j6Eb048KxChkEm-MCDRDkw) (Code: d74u)     |
| DRIT++            | 18.23                | 0.803                | 0.836                | 0.140                  | 0.159                  | [Link](https://pan.baidu.com/s/18hBLKJxd6z6ckLnbDp1fOg) (Code: sv2s)     |
| StarGANv2         | 19.72                | 0.791                | 0.841                | 0.125                  | 0.151                  | [Link](https://pan.baidu.com/s/14A9un-q2UHxH2U8CkFixKA) (Code: futn)     |
| CUT               | 20.20                | 0.819                | 0.852                | 0.129                  | 0.145                  | [Link](https://pan.baidu.com/s/1_bRAf-QJeahEP5WzDr5jBw) (Code: 5vhm)     |
| NEGCUT            | 20.00                | 0.789                | 0.844                | 0.139                  | 0.157                  | [Link](https://pan.baidu.com/s/1BLkjXBjlF11I9AumFNj1XA) (Code: 5q1n)     |
| DisCoGAN (ours)   | 21.49                | 0.839                | 0.844                | 0.105                  | 0.125                  | [Link](https://pan.baidu.com/s/16L8sWWynOZof6XCGaaRMxg) (Code: 6rkn)     |


:hotsprings: **Note:** Evaluation metrics include learned perceptual image patch similarity (LPIPS), visual information fidelity (VIF), peak signal noise rate (PSNR), structural similarity index measure (SSIM), and gradient magnitude similarity deviation (GMSD).


### Foggy Cityscapes to Cityscapes ( :herb::herb: TABLE VII)
:rocket::rocket: We provide quantitative results and checkpoint files in demo of image-to-image translation “from [Foggy Cityscapes](https://www.cityscapes-dataset.com/) to [Cityscapes](https://www.cityscapes-dataset.com/)” ( :star: here higher PSNR, SSIM, VIF and lower GMSD, LPIPS refer to better performance). Please view more details in TABLE VII.


| Method            | PSNR :arrow_up:      | SSIM :arrow_up:      | VIF :arrow_up:       | GMSD :arrow_down:      | LPIPS :arrow_down:     | Checkpoint file                                                          |
|-------------------|----------------------|----------------------|----------------------|------------------------|------------------------|--------------------------------------------------------------------------|
| CycleGAN          | 22.10                | 0.810                | 0.797                | 0.119                  | 0.125                  | [Link](https://pan.baidu.com/s/1KdhSOv0RdHHfJkeCyLp4Ww) (Code: m1wg)     |
| UNIT              | 18.89                | 0.487                | 0.797                | 0.201                  | 0.165                  | [Link](https://pan.baidu.com/s/11AZhEtt-icsT2wzrxQnXyw) (Code: q8rv)     |
| MUNIT             | 20.05                | 0.683                | 0.792                | 0.157                  | 0.184                  | [Link](https://pan.baidu.com/s/1j6Eb048KxChkEm-MCDRDkw) (Code: d74u)     |
| DRIT++            | 19.36                | 0.784                | 0.783                | 0.147                  | 0.132                  | [Link](https://pan.baidu.com/s/18hBLKJxd6z6ckLnbDp1fOg) (Code: sv2s)     |
| StarGANv2         | 20.53                | 0.727                | 0.783                | 0.133                  | 0.166                  | [Link](https://pan.baidu.com/s/14A9un-q2UHxH2U8CkFixKA) (Code: futn)     |
| CUT               | 21.90                | 0.788                | 0.795                | 0.120                  | 0.128                  | [Link](https://pan.baidu.com/s/1HM-51HAdQxC2j9ZS_ZtnCw) (Code: q2ty)     |
| NEGCUT            | 20.75                | 0.700                | 0.794                | 0.139                  | 0.156                  | [Link](https://pan.baidu.com/s/1_ji2dpt_jZOwrtwZNWpCrw) (Code: enu6)     |
| DisCoGAN (ours)   | 22.94                | 0.804                | 0.797                | 0.115                  | 0.121                  | [Link](https://pan.baidu.com/s/16L8sWWynOZof6XCGaaRMxg) (Code: 6rkn)     |


:hotsprings: **Note:** Evaluation metrics include learned perceptual image patch similarity (LPIPS), visual information fidelity (VIF), peak signal noise rate (PSNR), structural similarity index measure (SSIM), and gradient magnitude similarity deviation (GMSD).


:airplane::airplane: We further visualize examples of unpaired image translation in demo “from [GTA5](https://download.visinf.tu-darmstadt.de/data/from_games/) or [SYNTHIA](https://synthia-dataset.net/) to [Cityscapes](https://www.cityscapes-dataset.com/)” where DisCoGAN (ours) performs best to transfer style while preserving content, such as traffic light and road in left sub-graph as well as motorcycle and bike in right sub-graph.
<p align="center">
<img src="assets/Fig4.pdf" width="700px"/></p>


### Ablation Study on DisCoGAN ( :herb::herb: TABLE VII + TABLE X)
:rocket::rocket: We provide ablation results and checkpoint files on DisCoGAN in demo of image translation “from [Cityscapes](https://www.cityscapes-dataset.com/) to [Foggy Cityscapes](https://www.cityscapes-dataset.com/)” ( :star: here higher PSNR, SSIM, VIF and lower GMSD, LPIPS refer to better performance). Please view loss configurations (:one: - :eight:) in TABLE X.


| Method            | PSNR :arrow_up:      | SSIM :arrow_up:      | VIF :arrow_up:       | GMSD :arrow_down:      | LPIPS :arrow_down:     | Checkpoint file                                                          |
|-------------------|----------------------|----------------------|----------------------|------------------------|------------------------|--------------------------------------------------------------------------|
| DisCoGAN :one:    | 12.52                | 0.499                | 0.783                | 0.182                  | 0.213                  | [Link](https://pan.baidu.com/s/1jnX1HF69xvtigbm4XEg3jA) (Code: b5mb)     |
| DisCoGAN :two:    | 12.89                | 0.685                | 0.784                | 0.143                  | 0.186                  | [Link](https://pan.baidu.com/s/1duEoAkTePUdHjiyx3xpi_w) (Code: 9mx8)     |
| DisCoGAN :three:  | 20.52                | 0.828                | 0.803                | 0.110                  | 0.132                  | [Link](https://pan.baidu.com/s/1Dgsggdp0XjA7oB7GZMRnzg) (Code: x85u)     |
| DisCoGAN :four:   | 20.95                | 0.830                | 0.807                | 0.109                  | 0.131                  | [Link](https://pan.baidu.com/s/1p7ksDnud86JinW5OpomVyg) (Code: ziec)     |
| DisCoGAN :five:   | 21.37                | 0.834                | 0.816                | 0.108                  | 0.130                  | [Link](https://pan.baidu.com/s/1BFB8mXWZeU6gKxaf8RZsHA) (Code: sqcs)     |
| DisCoGAN :six:    | 21.16                | 0.832                | 0.820                | 0.108                  | 0.132                  | [Link](https://pan.baidu.com/s/1RYLlXqGXdqbfKhWFQYJ9PQ) (Code: tqvy)     |
| DisCoGAN :seven:  | 21.23                | 0.836                | 0.838                | 0.106                  | 0.129                  | [Link](https://pan.baidu.com/s/1eM3Tjbjr9T-5JK4yhL6J5g) (Code: asgc)     |
| DisCoGAN :eight:  | 21.49                | 0.839                | 0.844                | 0.105                  | 0.125                  | [Link](https://pan.baidu.com/s/1tvvoXuR239XV_gotTBhOCQ) (Code: xjs4)     |


:rocket::rocket: We also provide ablation results and checkpoint files on DisCoGAN in demo of image translation “from [Foggy Cityscapes](https://www.cityscapes-dataset.com/) to [Cityscapes](https://www.cityscapes-dataset.com/)” ( :star: here higher PSNR, SSIM, VIF and lower GMSD, LPIPS refer to better performance). Please view loss configurations (:one: - :eight:) in TABLE X.


| Method            | PSNR :arrow_up:      | SSIM :arrow_up:      | VIF :arrow_up:       | GMSD :arrow_down:      | LPIPS :arrow_down:     | Checkpoint file                                                          |
|-------------------|----------------------|----------------------|----------------------|------------------------|------------------------|--------------------------------------------------------------------------|
| DisCoGAN :one:    | 12.62                | 0.564                | 0.722                | 0.170                  | 0.215                  | [Link](https://pan.baidu.com/s/1jnX1HF69xvtigbm4XEg3jA) (Code: b5mb)     |
| DisCoGAN :two:    | 12.65                | 0.651                | 0.763                | 0.147                  | 0.139                  | [Link](https://pan.baidu.com/s/1duEoAkTePUdHjiyx3xpi_w) (Code: 9mx8)     |
| DisCoGAN :three:  | 19.38                | 0.781                | 0.781                | 0.126                  | 0.129                  | [Link](https://pan.baidu.com/s/1Dgsggdp0XjA7oB7GZMRnzg) (Code: x85u)     |
| DisCoGAN :four:   | 19.45                | 0.785                | 0.788                | 0.127                  | 0.129                  | [Link](https://pan.baidu.com/s/1p7ksDnud86JinW5OpomVyg) (Code: ziec)     |
| DisCoGAN :five:   | 21.92                | 0.791                | 0.788                | 0.121                  | 0.124                  | [Link](https://pan.baidu.com/s/1BFB8mXWZeU6gKxaf8RZsHA) (Code: sqcs)     |
| DisCoGAN :six:    | 22.48                | 0.789                | 0.786                | 0.119                  | 0.123                  | [Link](https://pan.baidu.com/s/1RYLlXqGXdqbfKhWFQYJ9PQ) (Code: tqvy)     |
| DisCoGAN :seven:  | 22.50                | 0.796                | 0.794                | 0.119                  | 0.122                  | [Link](https://pan.baidu.com/s/1eM3Tjbjr9T-5JK4yhL6J5g) (Code: asgc)     |
| DisCoGAN :eight:  | 22.94                | 0.804                | 0.797                | 0.115                  | 0.121                  | [Link](https://pan.baidu.com/s/1tvvoXuR239XV_gotTBhOCQ) (Code: xjs4)     |


:hotsprings: **Note:** Evaluation metrics include learned perceptual image patch similarity (LPIPS), visual information fidelity (VIF), peak signal noise rate (PSNR), structural similarity index measure (SSIM), and gradient magnitude similarity deviation (GMSD).


### Ablation Study on ProRA ( :herb::herb: TABLE VIII + TABLE IX)
:rocket::rocket: We provide ablation results and checkpoint files on ProRA in demo of domain adaptation “from [GTA5](https://download.visinf.tu-darmstadt.de/data/from_games/) to [Foggy Cityscapes](https://www.cityscapes-dataset.com/)” ( :star: here Gain refers to performance gain of overall 19-class mIoU). Please view loss configurations (:one: - :six:) in TABLE VIII.


| ProRA :one:    | ProRA :two:    | ProRA :three:  | ProRA :four:   | ProRA :five:   | ProRA :six:    | Gain           | Checkpoint file                                                            |
|----------------|----------------|----------------|----------------|----------------|----------------|----------------|----------------------------------------------------------------------------|
|                |                |                |                |                |                | 0.0            | [Link](https://pan.baidu.com/s/17CW_JoZsB0DAUG0q7ncTpA) (Code: aj26)       |
|                | &#10003;       |                |                |                |                | 9.2            | [Link](https://pan.baidu.com/s/1wZVLBT-nQB1mVh0wUxNURA) (Code: evev)       |
| &#10003;       | &#10003;       |                |                |                |                | 11.7           | [Link](https://pan.baidu.com/s/16pfI3vCwm9XqxaZO_Dx1-Q) (Code: 6deg)       |
| &#10003;       | &#10003;       | &#10003;       |                |                |                | 16.9           | [Link](https://pan.baidu.com/s/1rvOLaitnv77N9CE01us8JA) (Code: jj51)       |
| &#10003;       | &#10003;       |                | &#10003;       |                |                | 22.2           | [Link](https://pan.baidu.com/s/1blJIlIyEwptorBdflbwi3g) (Code: 2f5d)       |
| &#10003;       | &#10003;       | &#10003;       | &#10003;       |                |                | 22.4           | [Link](https://pan.baidu.com/s/1sbC4RobjTcOVxTGjHW46VQ) (Code: 75gs)       |
| &#10003;       | &#10003;       | &#10003;       | &#10003;       | &#10003;       |                | 22.9           | [Link](https://pan.baidu.com/s/1hk1lk5k9NP5VCAYnG-7FDg) (Code: igxx)       |
| &#10003;       | &#10003;       | &#10003;       | &#10003;       |                | &#10003;       | 23.1           | [Link](https://pan.baidu.com/s/1h5oHEprkc2IA-c3rm1K3QQ) (Code: yk9g)       |
| &#10003;       | &#10003;       | &#10003;       | &#10003;       | &#10003;       | &#10003;       | 23.9           | [Link](https://pan.baidu.com/s/1XzeaU-Z0EPC7A9_IGGlf7g) (Code: qam5)       |


:rocket::rocket: We provide ablation results and checkpoint files on ProRA in demo of domain adaptation “from [SYNTHIA](https://synthia-dataset.net/) to [Foggy Cityscapes](https://www.cityscapes-dataset.com/)” ( :star: here Gain refers to performance gain of overall 16-class mIoU). Please view loss configurations (:one: - :six:) in TABLE IX.


| ProRA :one:    | ProRA :two:    | ProRA :three:  | ProRA :four:   | ProRA :five:   | ProRA :six:    | Gain           | Checkpoint file                                                            |
|----------------|----------------|----------------|----------------|----------------|----------------|----------------|----------------------------------------------------------------------------|
|                |                |                |                |                |                | 0.0            | [Link](https://pan.baidu.com/s/15W-Vijn7XPtk-ohDV7vsPw) (Code: qhvg)       |
|                | &#10003;       |                |                |                |                | 10.3           | [Link](https://pan.baidu.com/s/1McLKDvxJN1f26FdcMW0CpQ) (Code: 5g4j)       |
| &#10003;       | &#10003;       |                |                |                |                | 12.3           | [Link](https://pan.baidu.com/s/1vV2qvI1y6ryIoxEug8kqdA) (Code: 5mus)       |
| &#10003;       | &#10003;       | &#10003;       |                |                |                | 15.3           | [Link](https://pan.baidu.com/s/1IoxvxwBVcvgPEs2grhqImg) (Code: xv7b)       |
| &#10003;       | &#10003;       |                | &#10003;       |                |                | 19.1           | [Link](https://pan.baidu.com/s/1QtmzcH6eUgJlNas4xDCKLA) (Code: z8vw)       |
| &#10003;       | &#10003;       | &#10003;       | &#10003;       |                |                | 21.9           | [Link](https://pan.baidu.com/s/1oVkRpPx69AMKoz-d1yYeqQ) (Code: uur8)       |
| &#10003;       | &#10003;       | &#10003;       | &#10003;       | &#10003;       |                | 24.2           | [Link](https://pan.baidu.com/s/1hhc8l0I7r_MjLh5N2esnKQ) (Code: sdai)       |
| &#10003;       | &#10003;       | &#10003;       | &#10003;       |                | &#10003;       | 23.9           | [Link](https://pan.baidu.com/s/1Xbas2oRZKDzEXufy42FlNw) (Code: z22y)       |
| &#10003;       | &#10003;       | &#10003;       | &#10003;       | &#10003;       | &#10003;       | 24.6           | [Link](https://pan.baidu.com/s/1uEwRojtFr3g2P0Eoft-dRA) (Code: 5ux5)       |



