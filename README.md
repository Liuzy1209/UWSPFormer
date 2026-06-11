# UWSPFormer

Official repository for **UWSPFormer: Clarity-Guided Transformer for Underwater Hyperspectral Pansharpening under Spatially Non-Homogeneous Degradation**.

UWSPFormer is a clarity-guided Transformer framework for underwater hyperspectral pansharpening. It aims to reconstruct high-resolution hyperspectral images from low-resolution hyperspectral observations and high-resolution panchromatic (PAN) images under spatially non-homogeneous underwater degradation.

> Code, pretrained models, and detailed running instructions will be released progressively.



## Repository Structure

The repository will be organized as follows:

```text
UWSPFormer/
├── README.md
├── requirements.txt
├── train.py
├── test.py
├── configs/
│   ├── cave.yaml
│   └── chikusei.yaml
├── data/
│   ├── README.md
│   ├── CAVE/
│   └── Chikusei/
├── models/
│   ├── uwspformer.py
│   ├── bdig.py
│   ├── spesa.py
│   └── bffn.py
├── utils/
│   ├── degradation.py
│   ├── metrics.py
│   └── visualization.py
├── checkpoints/
└── results/
```



## License

The license will be released together with the source code.

## Contact

For questions about this work, please contact:

**Qingsheng Xue**
Ocean University of China
Email: [xueqingsheng@ouc.edu.cn](mailto:xueqingsheng@ouc.edu.cn)
