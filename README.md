# Translate-thEn-Adapt (TEA)
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
| RIPU                         | B              | CVPR’22             | 66.8            | 35.4                  | [Link](https://pan.baidu.com/s/1POl7UtLrBplN-OUoV17bmw) (Code: niu9)     |
| SimT                         | B              | TPAMI’23            | 54.6            | 23.2                  | [Link](https://pan.baidu.com/s/1hcw9mOR0FVW5uVcr3hGnUQ) (Code: kq8w)     |
| DisCoGAN+ProRA (ours)        | B              | TMM’24              | 55.3            | 23.9                  | [Link](https://pan.baidu.com/s/15B2o1f46rkMcWl_1zWkPNw) (Code: hp3h)     |


:hotsprings: **Note:** A and B refer to federated domain adaptation and source-free domain adaptation in the field of DDA. RIPU will stand aside from the peer comparison since it acts as active domain adaptation to use a few target labels.


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
| HCL                          | B              | NeurIPS’21          | 36.9            | 9.7                   | [Link](https://pan.baidu.com/s/1FP6A6Hk3IxFBhcgNVrNUfA) (Code: neci)     |
| LDBE                         | B              | MM’21               | 36.1            | 8.9                   | [Link](https://pan.baidu.com/s/1PrZ0PPoMFy_4JTalV3_cUg) (Code: 5e62)     |
| ProDA                        | B              | CVPR’21             | 44.1            | 16.9                  | [Link](https://pan.baidu.com/s/1sA0UltvMwOXLTgXMsxiRrw) (Code: 4xxj)     |
| SFOCDA                       | B              | TCSVT’22            | 35.5            | 8.3                   | [Link](https://pan.baidu.com/s/15a_Ew5pdVin-VhNDMh-Gww) (Code: 4t7a)     |
| ProCA                        | B              | ECCV’22             | 35.7            | 8.5                   | [Link](https://pan.baidu.com/s/1vtYfofLBfWT6FpRozzSgNg) (Code: tjaj)     |
| RIPU                         | B              | CVPR’22             | 67.1            | 39.9                  | [Link](https://pan.baidu.com/s/1nUqCxo-RgNmDY3ls3_hKBg) (Code: w274)     |
| SimT                         | B              | TPAMI’23            | 40.6            | 13.4                  | [Link](https://pan.baidu.com/s/1xGZLqVaf-vc_WkEGZMDL0w) (Code: 59n5)     |
| DisCoGAN+ProRA (ours)        | B              | TMM’24              | 51.8            | 24.6                  | [Link](https://pan.baidu.com/s/1wRYMnvXb-IwxELRgUZzr_A) (Code: 4i2u)     |


:hotsprings: **Note:** A and B refer to federated domain adaptation and source-free domain adaptation in the field of DDA. RIPU will stand aside from the peer comparison since it acts as active domain adaptation to use a few target labels.


:airplane::airplane: We visualize examples of foggy scene understanding in demo “from [SYNTHIA](https://synthia-dataset.net/) to [Foggy Cityscapes](https://www.cityscapes-dataset.com/)” ( :star: here model is tested on Foggy Cityscapes dataset). Compared to federated or source-free DDA baseline, our TEA (DisCoGAN+ProRA) obtains 51.82% in mIoU to reach state-of-the-art performance for SFSU.
<p align="center">
<img src="assets/Fig10.pdf" width="700px"/></p>


### GTA5 to Foggy Driving ( :herb::herb: TABLE III)
:rocket::rocket: We provide quantitative results and checkpoint files in demo “from [GTA5](https://download.visinf.tu-darmstadt.de/data/from_games/) to [Foggy Driving](https://people.ee.ethz.ch/~csakarid/SFSU_synthetic/)” ( :star: here model is tested on unseen datasets such as Foggy Driving and Foggy Zurich). Please view more details in TABLE III.


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
| DISE                      | &#10007;   | CVPR’19             | 39.28         | 33.07         | 18.27         | [Link](https://pan.baidu.com/s/1dNBUF-uVDMuWRsAnm0J3uw) (Code: 2sup)     |
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
:rocket::rocket: We provide quantitative results and checkpoint files in demo “from [GTA5](https://download.visinf.tu-darmstadt.de/data/from_games/) to [Foggy Zurich](https://people.ee.ethz.ch/~csakarid/Model_adaptation_SFSU_dense/)” ( :star: here model is tested on Foggy Zurich dataset). Please view more details in TABLE V.


| Method                    | Src/Mid/Tgt       | V :arrow_right: R    | C :arrow_right: F    | mIoU          | gain          | Checkpoint file                                                          |
|---------------------------|-------------------|----------------------|----------------------|---------------|---------------|--------------------------------------------------------------------------|
| Source only               | -                 |                      |                      | 20.4          | -             | [Link](https://pan.baidu.com/s/1qp3rz1ojH_f5iUAInSm_7w) (Code: dhrp)     |
| DisCoGAN (ours)           | GTA/CZ/FZ         | &#10003;             |                      | 35.1          | 14.7          | [Link](https://pan.baidu.com/s/1onYBbSPQiefX_HUSX030gw) (Code: frtn)     |
| ProRA (ours)              | GTA/CZ/FZ         |                      | &#10003;             | 42.3          | 21.9          | [Link](https://pan.baidu.com/s/1lV-MMkMssR6NdBaMrEjAnA) (Code: vrwg)     |
| DisCoGAN+ProRA (ours)     | GTA/CZ/FZ         | &#10003;             | &#10003;             | 46.2          | 25.8          | [Link](https://pan.baidu.com/s/1A4kNRNk7EsXc33O10U2sJg) (Code: cma7)     |


:hotsprings: **Note:** Src/Mid/Tgt refer to source domain, middle domain and target domain. V :arrow_right: R and C :arrow_right: F refer to virtual-to-real and clear-to-foggy. Datasets include Clear Zurich (CZ), Foggy Zurich (FZ), GTA5 (GTA) and SYNTHIA (SYN).


:airplane::airplane: We visualize examples of foggy scene understanding in demo “from [GTA5](https://download.visinf.tu-darmstadt.de/data/from_games/) to [Foggy Zurich](https://people.ee.ethz.ch/~csakarid/Model_adaptation_SFSU_dense/)” ( :star: here model is tested on Foggy Zurich dataset). DisCoGAN and ProRA refer to only 1st module and only 2nd module. Ultimately, DisCoGAN+ProRA gains a clear margin of 25.85% in mIoU to act as best relative value.
<p align="center">
<img src="assets/Fig13.pdf" width="700px"/></p>


### SYNTHIA to Foggy Zurich ( :herb::herb: TABLE V)
:rocket::rocket: We provide quantitative results and checkpoint files in demo “from [SYNTHIA](https://synthia-dataset.net/) to [Foggy Zurich](https://people.ee.ethz.ch/~csakarid/Model_adaptation_SFSU_dense/)” ( :star: here model is tested on Foggy Zurich dataset). Please view more details in TABLE V.


| Method                    | Src/Mid/Tgt       | V :arrow_right: R    | C :arrow_right: F    | mIoU          | gain          | Checkpoint file                                                          |
|---------------------------|-------------------|----------------------|----------------------|---------------|---------------|--------------------------------------------------------------------------|
| Source only               | -                 |                      |                      | 12.4          | -             | [Link](https://pan.baidu.com/s/1YVa8uBLQHuGgj0UOXdbnCQ) (Code: 8gaa)     |
| DisCoGAN (ours)           | SYN/CZ/FZ         | &#10003;             |                      | 26.2          | 13.8          | [Link](https://pan.baidu.com/s/1iNuRGERGooVkAnTh6SFTXQ) (Code: wtcy)     |
| ProRA (ours)              | SYN/CZ/FZ         |                      | &#10003;             | 31.8          | 19.4          | [Link](https://pan.baidu.com/s/15I5yG4O2Y_dlXlwJFMsFkQ) (Code: 8v2a)     |
| DisCoGAN+ProRA (ours)     | SYN/CZ/FZ         | &#10003;             | &#10003;             | 36.4          | 24.0          | [Link](https://pan.baidu.com/s/1ewUtxuUtJG172on8upFZNg) (Code: rhiq)     |


:hotsprings: **Note:** Src/Mid/Tgt refer to source domain, middle domain and target domain. V :arrow_right: R and C :arrow_right: F refer to virtual-to-real and clear-to-foggy. Datasets include Clear Zurich (CZ), Foggy Zurich (FZ), GTA5 (GTA) and SYNTHIA (SYN).


:airplane::airplane: We visualize examples of foggy scene understanding in demo “from [SYNTHIA](https://synthia-dataset.net/) to [Foggy Zurich](https://people.ee.ethz.ch/~csakarid/Model_adaptation_SFSU_dense/)” ( :star: here model is tested on Foggy Zurich dataset). DisCoGAN and ProRA refer to only 1st module and only 2nd module. Ultimately, DisCoGAN+ProRA gains a clear margin of 24.03% in mIoU to act as best relative value.
<p align="center">
<img src="assets/Fig14.pdf" width="700px"/></p>



