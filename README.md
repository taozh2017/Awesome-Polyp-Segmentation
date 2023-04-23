# Awesome-Polyp-Segmentation

Will collect polyp segmentastion models.

<p align="center">
    <img src="polyp.png"/> <br />
</p>

# <p align=center>`Awesome List for Polyp Segmentation`

![Badge](https://img.shields.io/badge/-As%20awesome%20as%20you%20think!-red)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)


This awesome list is under construction. If you have anything to recommend or any suggestions, please feel free to contact us via e-mail (taozhou.ai@gmail) or directly push a PR. 

< **Last updated: 23/04/2023** >


##  1. Content


- [`Awesome List for Polyp Segmentation`](#awesome-list-for-polyp-segmentation)
	- [1. Content](#1-content)
	- [2. Paper List](#2-paper-list)
		- [2.1. Datasets \& Benchmarks](#21-datasets--benchmarks)
			- [2.1.1. Image-level Polyp](#211-video-level-polyp)
			- [2.1.2. Video-level Polyp](#212-image-level-polyp)
		- [2.2. Polyp Segmentation](#22-polyp--segmentation) 
			- [2.2.1. YEAR 2023](#221-year-2023)
			- [2.2.2. YEAR 2022](#222-year-2022)
			- [2.2.3. YEAR 2021](#223-year-2021)
			- [2.2.4. Before YEAR 2020](#224-before-year-2020)
		- [2.3. Video Polyp Segmentation](#23-video-polyp-segmentation)
		

##  2. Paper List

###  2.1. Datasets & Benchmarks

####  2.1.1. Image-level polyp segmentation

| **Dataset Name** | **Year** | **Publication** | **Links** |
| :------: | :------: | :-------: | :---------|
[CVCClinicDB](https://xueliancheng.github.io/SLT-Net-project/) | 2015 | CMIG | [Paper](https://www.sciencedirect.com/science/article/pii/S0895611115000567) |
[CVC-ColonDB](https://xueliancheng.github.io/SLT-Net-project/) | 2015 | CMIG | [Paper](https://www.sciencedirect.com/science/article/pii/S0895611115000567) |
[Kvasir](https://xueliancheng.github.io/SLT-Net-project/) | 2015 | CMIG | [Paper](https://www.sciencedirect.com/science/article/pii/S0895611115000567) |


####  2.1.2. Video-level polyp segmentation

| **Dataset Name** | **Year** | **Publication** | **Links** |
| :------: | :------: | :-------: | :---------|
[CVCClinicDB](https://xueliancheng.github.io/SLT-Net-project/) | 2015 | CMIG | [Paper](https://www.sciencedirect.com/science/article/pii/S0895611115000567) |


###  2.2. Polyp Segmentation


####  2.2.1. YEAR 2023

| **Year** | **Model** | **Publication** | **Title**                                 |  **Links**                                                    |
| :------: | :------: |:------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
| 2023 | CFA-Net | PR | Cross-level Feature Aggregation Network for Polyp Segmentation <br><sup><sub>*Tao Zhou, Yi Zhou, Kelei He, Chen Gong, Jian Yang, Huazhu Fu, Dinggang Shen*</sub></sup> | [Paper](https://www.sciencedirect.com/science/article/pii/S0031320323002558)/[Code](https://github.com/taozh2017/CFANet)/[Seg-Maps](https://github.com/taozh2017/CFANet)
	

####  2.2.2. YEAR 2022

| **Year** | **Model** | **Publication** | **Title**                                 |  **Links**                                                    |
| :------: | :------: |:------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
| 2022 | BSCA-Net | PR | BSCA-Net: Bit Slicing Context Attention Network for Polyp Segmentation <br><sup><sub>*Yi Lin, Jichun Wu, Guobao Xiao, Junwen Guo, Geng Chen, Jiayi Ma*</sub></sup> | [Paper](https://guobaoxiao.github.io/papers/PR_2022_BSCA.pdf)/Code/Seg-Maps	
| 2022 | TRFRNet(UDA) | MICCAI | Task-Relevant Feature Replenishment for Cross-Centre Polyp Segmentation <br><sup><sub>*Yutian Shen, Ye Lu, Xiao Jia, Fan Bai, Max Q.-H. Meng*</sub></sup> | [Paper](https://link.springer.com/10.1007/978-3-031-16440-8_57)/[Code](https://github.com/CathyS1996/TRFRNet)/Seg-Maps	
| 2022 | MSRF-Net | JBHI | MSRF-Net: A Multi-Scale Residual Fusion Network for Biomedical Image Segmentation <br><sup><sub>*Abhishek Srivastava, Debesh Jha, Sukalpa Chanda, Umapada Pal, Håvard D. Johansen, Dag Johansen, Michael A. Riegler, Sharib Ali, Pål Halvorsen*</sub></sup> | [Paper](https://arxiv.org/pdf/2105.07451v2.pdf)/[Code](https://github.com/NoviceMAn-prog/MSRF-Net)/Seg-Maps

####  2.2.3. YEAR 2021

| **Year** | **Model** | **Publication** | **Title**                                 |  **Links**                                                    |
| :------: | :------: |:------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
| 2021 | MSNet | MICCAI | Automatic Polyp Segmentation via Multi-scale Subtraction Network <br><sup><sub>*Xiaoqi Zhao, Lihe Zhang, Huchuan Lu*</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-87193-2_12)/[Code](https://github.com/Xiaoqi-Zhao-DLUT/MSNet-M2SNet)/Seg-Maps	
| 2021 | MPA-DA(UDA) | JBHI | Mutual-Prototype Adaptation for Cross-Domain Polyp Segmentation <br><sup><sub>*Chen Yang, Xiaoqing Guo, Meilu Zhu, Bulat Ibragimov, Yixuan Yuan*</sub></sup> | [Paper](https://ieeexplore.ieee.org/document/9423517/)/[Code](https://github.com/CityU-AIM-Group/MPA-DA)/Seg-Maps
| 2021 | C2FNet | IJCAI | Context-aware Cross-level Fusion Network for Camouflaged Object Detection <br><sup><sub>*Yujia Sun, Geng Chen, Tao Zhou, Yi Zhang, Nian Liu*</sub></sup> | [Paper](https://www.ijcai.org/proceedings/2021/0142.pdf)/[Code](https://github.com/thograce/C2FNet)/Seg-Maps
| 2021 | UACANet | ACM MM | UACANet: Uncertainty Augmented Context Attention for Polyp Segmentation <br><sup><sub>*Taehun Kim, Hyemin Lee, Daijin Kim*</sub></sup> | [Paper](https://arxiv.org/abs/2107.02368)/[Code](https://github.com/plemeri/UACANet)/Seg-Maps
| 2021 | HarDNet-MSEG | Arxiv | HarDNet-MSEG: A Simple Encoder-Decoder Polyp Segmentation Neural Network that Achieves over 0.9 Mean Dice and 86 FPS <br><sup><sub>*Chien-Hsiang Huang, Hung-Yu Wu, Youn-Long Lin*</sub></sup> | [Paper](https://arxiv.org/abs/2101.07172)/[Code](https://github.com/james128333/HarDNet-MSEG)/Seg-Maps
| 2021 | TransFuse | Arxiv | TransFuse: Fusing Transformers and CNNs for Medical Image Segmentation <br><sup><sub>*Yundong Zhang, Huiye Liu, Qiang Hu*</sub></sup> | [Paper](https://arxiv.org/pdf/2102.08005v2.pdf)/[Code](https://github.com/Rayicer/TransFuse)/Seg-Maps
| 2021 | CaraNet | Arxiv | CaraNet: Context Axial Reverse Attention Network for Segmentation of Small Medical Objects <br><sup><sub>*Ange Lou, Shuyue Guan, Hanseok Ko, Murray Loew*</sub></sup> | [Paper](https://arxiv.org/ftp/arxiv/papers/2108/2108.07368.pdf)/[Code](https://github.com/AngeLouCN/CaraNet)/Seg-Maps
| 2021 | Polyp-PVT | CAAI AIR | Polyp-PVT: Polyp Segmentation with Pyramid Vision Transformers <br><sup><sub>*Bo Dong, Wenhai Wang, Deng-Ping Fan, Jinpeng Li, Huazhu Fu, Ling Shao*</sub></sup> | [Paper](https://arxiv.org/abs/2108.06932)/[Code](https://github.com/DengPingFan/Polyp-PVT)/Seg-Maps
| 2021 | ResUNet++ + TTA + CRF | JBHI | A Comprehensive Study on Colorectal Polyp Segmentation with ResUNet++, Conditional Random Field and Test-Time Augmentation <br><sup><sub>*Debesh Jha, Pia H. Smedsrud, Dag Johansen, Thomas de Lange, Havard D. Johansen, Pal Halvorsen, and Michael A. Riegler*</sub></sup> | [Paper](https://arxiv.org/pdf/2107.12435v1.pdf)/[Code](https://github.com/DebeshJha/ResUNet-with-CRF-and-TTA)/Seg-Maps
| 2021 | GMSRF-Net | Arxiv | GMSRF-Net: An improved generalizability with global multi-scale residual fusion network for polyp segmentation <br><sup><sub>*Abhishek Srivastava, Sukalpa Chanda, Debesh Jha, Umapada Pal, Sharib Ali*</sub></sup> | [Paper](https://arxiv.org/pdf/2111.10614v1.pdf)/[Code](https://github.com/NoviceMAn-prog/GMSRFNet)/Seg-Maps
| 2021 | A-DenseUNet | Sensors | A-DenseUNet: Adaptive Densely Connected UNet for Polyp Segmentation in Colonoscopy Images with Atrous Convolution <br><sup><sub>*Safarov SIrojbek*</sub></sup> | [Paper](https://www.mdpi.com/1424-8220/21/4/1441)/Code/Seg-Maps
| 2021 | FANet | TNNLS | FANet: A Feedback Attention Network for Improved Biomedical Image Segmentation <br><sup><sub>*Nikhil Kumar Tomar, Debesh Jha, Michael A. Riegler, Håvard D. Johansen, Dag Johansen, Jens Rittscher, Pål Halvorsen, Sharib Ali*</sub></sup> | [Paper](https://arxiv.org/pdf/2103.17235v3.pdf)/[Code](https://github.com/nikhilroxtomar/fanet)/Seg-Maps
| 2021 | SANet | MICCAI | Shallow Attention Network for Polyp Segmentation <br><sup><sub>*Jun Wei, Yiwen Hu, Ruimao Zhang, Zhen Li, S. Kevin Zhou, Shuguang Cui*</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-87193-2_66)/[Code](https://github.com/weijun88/sanet)/Seg-Maps
| 2021 | EU-Net | CRV | Enhanced U-Net: A Feature Enhancement Network for Polyp Segmentation <br><sup><sub>*Krushi Patel, Andres M. Bur, Guanghui Wang*</sub></sup> | [Paper](https://arxiv.org/pdf/2105.00999.pdf)/[Code](https://github.com/rucv/Enhanced-U-Net)/Seg-Maps
| 2021 | DCRNet | ISBI | Duplex contextual relation network for polyp segmentation <br><sup><sub>*Zijin Yin, Kongming Liang, Zhanyu Ma, Jun Guo*</sub></sup> | [Paper](https://arxiv.org/pdf/2103.06725.pdf)/[Code](https://github.com/zijinY/DCRNet)/Seg-Maps
	
####  2.2.4. Before YEAR 2021 

| **Year** | **Model** | **Publication** | **Title**                                 |  **Links**                                                    |
| :------: | :------: |:------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
| 2020 | PraNet | MICCAI | PraNet: Parallel Reverse Attention Network for Polyp Segmentation <br><sup><sub>*Deng-Ping Fan, Ge-Peng Ji, Tao Zhou, Geng Chen, Huazhu Fu, Jianbing Shen, Ling Shao*</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-59725-2_26)/[Code](https://github.com/DengPingFan/PraNet)/Seg-Maps
| 2019 | SFA | MICCAI | Selective Feature Aggregation Network with Area-Boundary Constraints for Polyp Segmentation <br><sup><sub>*Yuqi Fang, Cheng Chen, Yixuan Yuan, Kai-yu Tong*</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-32239-7_34)/[Code](https://github.com/Yuqi-cuhk/Polyp-Seg)/Seg-Maps
| 2020 | ACSNet | MICCAI | Adaptive Context Selection for Polyp Segmentation <br><sup><sub>*Ruifei Zhang, Guanbin Li, Zhen Li, Shuguang Cui, Dahong Qian, Yizhou Yu*</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-59725-2_25)/[Code](https://github.com/ReaFly/ACSNet)/Seg-Maps
| 2019 | ResUNet++ | ISM | ResUNet++: An Advanced Architecture for Medical Image Segmentation <br><sup><sub>*Debesh Jha, Pia H. Smedsrud, Michael A. Riegler, Dag Johansen, Thomas de Lange, Pal Halvorsen, Havard D. Johansen*</sub></sup> | [Paper](https://arxiv.org/pdf/1911.07067.pdf)/[Code](https://github.com/DebeshJha/ResUNetPlusPlus)/Seg-Maps



###  2.3. Video Polyp Segmentation

| **Year** | **Model** | **Publication** | **Title**                                 |  **Links**                                                    |
| :------: | :------: |:------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
| 2022 | PraNet | MICCAI | PraNet: Parallel Reverse Attention Network for Polyp Segmentation <br><sup><sub>*Deng-Ping Fan, Ge-Peng Ji, Tao Zhou, Geng Chen, Huazhu Fu*, Jianbing Shen*, Ling Shao*</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-59725-2_26)/[Code](https://github.com/DengPingFan/PraNet)	


