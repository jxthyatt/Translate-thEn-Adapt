# Translate-thEn-Adapt (TEA)
Official repository for the submitted paper “Federated Hallucination Translation and Source-free Regularization Adaptation in Decentralized Domain Adaptation for Foggy Scene Understanding”. Previous version of Code is [here](https://github.com/jxthyatt/DDA-CoSoAdapt). Final Code will be released after acceptance.

## Replicate Demo and Results
### GTA5 to Foggy Cityscapes
We provide quantitative results and pretrained weights in demo “GTA5 to Foggy Cityscapes” (here model is tested on Foggy Cityscapes dataset). Please find more details in TABLE I.

| Method                      | Hipp            | SC              | Striatum        | Tha             | Weight file                                                          |
|----------------------------------|-----------------|-----------------|-----------------|-----------------|----------------------------------------------------------------------|
| Source only                           | 0.9033 ± 0.0143 | 0.8765 ± 0.0215 | 0.9179 ± 0.0108 | 0.9276 ± 0.0087 | [Link](https://pan.baidu.com/s/175BXR675dQSyhFX14bk5zg) (Code: l4oh) |
| CycleGAN                           | 0.9078 ± 0.0139 | 0.8646 ± 0.0190 | 0.9142 ± 0.0143 | 0.9259 ± 0.0055 | [Link](https://pan.baidu.com/s/175BXR675dQSyhFX14bk5zg) (Code: l4oh) |
| UNIT                           | 0.9084 ± 0.0157 | 0.8741 ± 0.0271 | 0.9175 ± 0.0036 | 0.9327 ± 0.0104 | [Link](https://pan.baidu.com/s/175BXR675dQSyhFX14bk5zg) (Code: l4oh) |
| MUNIT                           | 0.9068 ± 0.0200 | 0.8710 ± 0.0404 | 0.9167 ± 0.0126 | 0.9237 ± 0.0089 | [Link](https://pan.baidu.com/s/175BXR675dQSyhFX14bk5zg) (Code: l4oh) |
| DRIT++                           | 0.9046 ± 0.0167 | 0.8712 ± 0.0260 | 0.9205 ± 0.0105 | 0.9295 ± 0.0049 | [Link](https://pan.baidu.com/s/175BXR675dQSyhFX14bk5zg) (Code: l4oh) |
| CUT             | 0.9062 ± 0.0146 | 0.8715 ± 0.0250 | 0.9174 ± 0.0100 | 0.9279 ± 0.0077 | -                                                                    |
| NEGCUT             | 0.9062 ± 0.0146 | 0.8715 ± 0.0250 | 0.9174 ± 0.0100 | 0.9279 ± 0.0077 | -                                                                    |
| LADD             | 0.9062 ± 0.0146 | 0.8715 ± 0.0250 | 0.9174 ± 0.0100 | 0.9279 ± 0.0077 | -                                                                    |
| TEA$\alpha $             | 0.9062 ± 0.0146 | 0.8715 ± 0.0250 | 0.9174 ± 0.0100 | 0.9279 ± 0.0077 | -                                                                    |
| CUT             | 0.9062 ± 0.0146 | 0.8715 ± 0.0250 | 0.9174 ± 0.0100 | 0.9279 ± 0.0077 | -                                                                    |
| CUT             | 0.9062 ± 0.0146 | 0.8715 ± 0.0250 | 0.9174 ± 0.0100 | 0.9279 ± 0.0077 | -                                                                    |
