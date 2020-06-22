## Introduction
This project tries to build a personal benchamrk for deep local features on roxford dataset(http://cmp.felk.cvut.cz/revisitop)

## Methods
method | feature |  mAP (best) | evalute code
:---:|:---:|:---:|:---:
Delf | ASMK+SP | 67.8% | ---
AffNet | hardnet | 71.67% | local match
LFNet | pure | --- | local match
D2-Net | pure | 73.03% | local match
R2D2 | pure | --- | local match
ASLFeat | pure | 78.34% | local match 

- **AffNet** used qe and base map is 68.7%
- **LFNet** got a low mAP on this dataset
- **D2Net** -10k points, just flann
- **ASLFeat** -8k points, used ratio test

## References:
* [revisitop](https://github.com/filipradenovic/revisitop.git)
* [DELF](https://github.com/tensorflow/models/blob/master/research/delf)
* [AffNet](https://github.com/ducha-aiki/affnet)
* [Hardnet](https://github.com/DagnyT/hardnet.git)
* [D2-Net](https://github.com/mihaidusmanu/d2-net)
* [LFNet](https://github.com/vcg-uvic/lf-net-release)
* [R2D2](https://github.com/naver/r2d2)
* [ASLFeat](https://github.com/lzx551402/ASLFeat)



