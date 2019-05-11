# A Deep-Learning-Based Approach For Fast And Robust Steel Surface Defects Classification

By  Guizhong Fu, Peize Sun, Wenbin Zhu, Jiangxin Yang, Yanlong Cao, Michael Ying Yang and Yanpeng Cao.

The paper will be available at  |[`[Optics and Lasers in Engineering]`](https://www.journals.elsevier.com/optics-and-lasers-in-engineering/)

### Introduction
In this paper, we present a compact yet effective convolutional neural network (CNN) model, which emphasizes the training of low-level features and incorporates multiple receptive fields, to achieve fast and accurate steel surface defect classification.Our proposed method adopts the pre-trained SqueezeNet as the backbone architecture.We also construct a diversity-enhanced testing dataset of steel surface defects to evaluate the robustness of classification models. The dataset contains severe camera noise, non-uniform illumination, and motion blur.

### Enhanced Dataset
The enhanced dataset is build on NEU dataset:
A noise robust method based on completed local binary patterns for hot-rolled steel strip surface defects
neural networks |  |[`[Download]`](http://faculty.neu.edu.cn/me/songkc/Vision-based_SIS_Steel.html)


<img src="Dataset/Data.png" width="100%" height="100%">


The enhanced dataset can be download at:

Google Drive: https://drive.google.com/file/d/16HjqGvnr_OUfTF0HSN1XyNg9XPr4Edfw/view?usp=sharing

Baidu Cloud: https://pan.baidu.com/s/18OowNbcJmBIi92fTWKI2wg  Password：fcmh 

### Implementations
This code is based on Caffe. Thanks to the contributors of Caffe.
Caffe: https://github.com/BVLC/caffe

Our Model also uses the pretrain model SqueezeNet-1.0
SqueezeNet: https://github.com/DeepScale/SqueezeNet

### Experimental Results

|   Method   | Running time | Model size | Accuracy on NEU dataset | Accuracy on enhanced dataset |
|:------------:|:-------------------:|:-------------------:|:----------:|:------------:| 
|     ETE    |         5.3ms        |          1.9MB          |      95.8%     |    80.3%   |
|    DECAF+MLR   |         10.3ms       |          244MB          |      99.7%     |    91.3%   |
|    SDC-SN-ELF+MRF    |     8.0ms    |     3.1MB    |      100%     |    97.5%   |

**[ETE]** An end-to-end steel strip surface defects recognition system based on convolutional
neural networks |  |[`[pdf]`](https://onlinelibrary.wiley.com/doi/pdf/10.1002/srin.201600068)

**[DECAF+MLR]** A generic deep-learning-based approach for automated surface inspection |  |[`[pdf]`](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7864335)


### Contact
If you have any questions, feel free to contact:
- Guizhong Fu (fuguizhongchina@163.com)
- Yanpeng Cao (caoyp@zju.edu.cn)


### License
Copyright(c) Guizhong Fu and Yanpeng Cao
All rights reserved.
