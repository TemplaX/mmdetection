# Scale-Aware Trident Networks for Object Detection

## Introduction

```
@InProceedings{li2019scale,
  title={Scale-Aware Trident Networks for Object Detection},
  author={Li, Yanghao and Chen, Yuntao and Wang, Naiyan and Zhang, Zhaoxiang},
  journal={The International Conference on Computer Vision (ICCV)},
  year={2019}
}
```

## Results and models

We reports the test results using only one branch for inference.

|    Backbone     |  Style  | mstrain | Lr schd | Mem (GB) | Inf time (fps) | box AP | Download |
| :-------------: | :-----: | :-----: | :-----: | :------: | :------------: | :----: | :------: |
|    R-50         |  caffe  |    N    |   1x    |          |                | 37.7   |  |
|    R-50         |  caffe  |    Y    |   1x    |          |                | 37.6   |  |
|    R-50         |  caffe  |    Y    |   3x    |          |                | 40.3   |  |
