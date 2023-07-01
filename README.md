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
| 2023 | CASCADE | WACV | Medical Image Segmentation via Cascaded Attention Decoding <br><sup><sub>*Md Mostafijur Rahman, Radu Marculescu*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/WACV2023/papers/Rahman_Medical_Image_Segmentation_via_Cascaded_Attention_Decoding_WACV_2023_paper.pdf)/[Code](https://github.com/SLDGroup/CASCADE)/Seg-Maps
| 2023 | TransNetR | MIDL | TransNetR: Transformer-based Residual Network for Polyp Segmentation with Multi-Center Out-of-Distribution Testing <br><sup><sub>*Debesh Jha, Nikhil Kumar Tomar, Vanshali Sharma, Ulas Bagci*</sub></sup> | [Paper](https://arxiv.org/pdf/2303.07428.pdf)/[Code](https://github.com/DebeshJha/TransNetR)/Seg-Maps
| 2023 | ESFPNet | Medical Imaging 2023: Biomedical Applications in Molecular, Structural, and Functional Imaging | ESFPNet: efficient deep learning architecture for real-time lesion segmentation in autofluorescence bronchoscopic video <br><sup><sub>*Qi Chang, Danish Ahmad, Jennifer Toth, Rebecca Bascom, William E. Higgins*</sub></sup> | [Paper](https://arxiv.org/pdf/2207.07759v3.pdf)/[Code](https://github.com/dumyCq/ESFPNet)/Seg-Maps
| 2023 | FCB-SwinV2 Transformer | Arxiv | FCB-SwinV2 Transformer for Polyp Segmentation <br><sup><sub>*Kerr Fitzgerald, Bogdan Matuszewski*</sub></sup> | [Paper](https://arxiv.org/ftp/arxiv/papers/2302/2302.01027.pdf)/Code/Seg-Maps
| 2023 | Polyp-SAM | Arxiv | Polyp-SAM: Transfer SAM for Polyp Segmentation <br><sup><sub>*Yuheng Li, Mingzhe Hu, Xiaofeng Yang*</sub></sup> | [Paper](https://arxiv.org/ftp/arxiv/papers/2305/2305.00293.pdf)/[Code](https://github.com/ricklisz/Polyp-SAM)/Seg-Maps	
| 2023 | LAPFormer | Arxiv | LAPFormer: A Light and Accurate Polyp Segmentation Transformer <br><sup><sub>*Mai Nguyen, Tung Thanh Bui, Quan Van Nguyen, Thanh Tung Nguyen, Toan Van Pham *</sub></sup> | [Paper](https://arxiv.org/pdf/2210.04393.pdf)/Code/Seg-Maps
| 2023 | Fu-TransHNet | Arxiv | Cooperation Learning Enhanced Colonic Polyp Segmentation Based on TransformerCNN Fusion <br><sup><sub>*Yuanyuan Wang, Zhaohong Deng,Qiongdan Lou, Shudong Hu, Kup-sze Choi, Shitong Wang*</sub></sup> | [Paper](https://arxiv.org/ftp/arxiv/papers/2301/2301.06892.pdf)/Code/Seg-Maps
| 2023 | PEFNet | MMM | PEFNet: Positional Embedding Feature for Polyp Segmentation <br><sup><sub>*Trong-Hieu Nguyen-Mau, Quoc-Huy Trinh, Nhat-Tan Bui, Phuoc-Thao Vo Thi, Minh-Van Nguyen, Xuan-Nam Cao, Minh-Triet Tran, Hai-Dang Nguyen*</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-27818-1_20)/[Code](https://github.com/huyquoctrinh/PEFNet)/Seg-Maps
| 2023 | APCNet | TIM | Attention-Guided Pyramid Context Network for Polyp Segmentation in Colonoscopy Images <br><sup><sub>*Guanghui Yue,Siying Li, Runmin Cong, Tianwei Zhou, Baiying Lei, Tianfu Wang*</sub></sup> | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10058111)/Code/Seg-Maps	
| 2023 | unnamed | Neurocomputingg | Accurate polyp segmentation through enhancing feature fusion and boosting boundary performanc <br><sup><sub>*Yanzhou Su, Jian Cheng, Chuqiao Zhong, Chengzhi Jiang, Jin Ye, Junjun He*</sub></sup> | [Paper](https://reader.elsevier.com/reader/sd/pii/S0925231223003569?token=F7DD07A4BF4F480A1648EDD7327A1017DB7A5EACFBC742BF6B5B818415DF03C6E728C206A00EE7DACB3A262AFFD64853&originRegion=us-east-1&originCreation=20230518081533)/Code/Seg-Maps	
| 2023 | FeDNet | BSPC | FeDNet: Feature Decoupled Network for polyp segmentation from endoscopy images <br><sup><sub>*Yanzhou Su, Jian Cheng, Chuqiao Zhong, Yijie Zhang, Jin Ye, Junjun He, Jun Liu*</sub></sup> | [Paper](https://reader.elsevier.com/reader/sd/pii/S1746809423001325?token=25CD9CF39B28CC9B719AF67D3062E10EC3506DF3729CD04CAEF1A1151460230718E494A23CF73D0B6D471A5B91C74A4A&originRegion=us-east-1&originCreation=20230518075548)/[Code](https://github.com/suyanzhou626/FeDNet-BSPC)/Seg-Maps
| 2023 | HarDNet-CPS | BSPC | HarDNet-CPS: Colorectal polyp segmentation based on Harmonic Densely United Network <br><sup><sub>*Tong Yu, Qingxiang Wu*</sub></sup> | [Paper](https://reader.elsevier.com/reader/sd/pii/S1746809423003865?token=6CFD7F61390B2E906B13547EC3481F8E23AAEC9B9A42F4DFB5D64EC4E1726C92368749A92842F1A46E66DEC8D391A5F0&originRegion=us-east-1&originCreation=20230518085852)/Code/Seg-Maps
| 2023 | RA-DENet | CompBioMed | RA-DENet: Reverse Attention and Distractions Elimination Network for polyp segmentation <br><sup><sub>*Kaiqi Wang, Li Liu, Xiaodong Fu, Lijun Liu, Wei Peng*</sub></sup> | [Paper](https://reader.elsevier.com/reader/sd/pii/S0010482523001695?token=FA58C819DA9C8F813C619868240E3E427BF2589832FFA0EB5A358959C9CC0B8081EE8BC5A16ED471FAC905FBF7C1E268&originRegion=us-east-1&originCreation=20230518075548)/Code/Seg-Maps
| 2023 | PPNet | CompBioMed | PPNet: Pyramid pooling based network for polyp segmentation <br><sup><sub>*Keli Hu, Wenping Chen, YuanZe Sun, Xiaozhao Hu, Qianwei Zhou, Zirui Zheng*</sub></sup> | [Paper](https://reader.elsevier.com/reader/sd/pii/S0010482523004936?token=2D12EE7774D5E3F4331D1B1B6F5DEC31BF6172F0A25C486A3DEFDC59270960EACB0CB5E49736971C8E3912C64BC2101A&originRegion=us-east-1&originCreation=20230518084005)/Code/Seg-Maps
| 2023 | EMTS-Net | JBHI | An Efficient Multi-Task Synergetic Network for Polyp Segmentation and Classification <br><sup><sub>*Miao Wang, Xingwei An, Zhengcun Pei, Ning Li, Li Zhang, Gang Liu and Dong Ming*</sub></sup> | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10120931)/Code/Seg-Maps
| 2023 | unnamed | ICASSP | Semantic Memory Guided Image Representation for Polyp Segmentation <br><sup><sub>*Zijin Yin, Runpu Wei, Kongming Liang , Yiyang Lin, Wei Liu, Zhanyu Ma, Min Min, Jun Guo*</sub></sup> | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10094302)/Code/Seg-Maps
| 2023 | DilatedSegNet | MMM | DilatedSegNet: A Deep Dilated Segmentation Network for Polyp Segmentation <br><sup><sub>*Nikhil Kumar Tomar, Debesh Jha, Ulas Bagci*</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-27077-2_26)/[Code](https://github.com/nikhilroxtomar/DilatedSegNet)/Seg-Maps

	
####  2.2.2. YEAR 2022

| **Year** | **Model** | **Publication** | **Title**                                 |  **Links**                                                    |
| :------: | :------: |:------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
| 2022 | BSCA-Net | PR | BSCA-Net: Bit Slicing Context Attention Network for Polyp Segmentation <br><sup><sub>*Yi Lin, Jichun Wu, Guobao Xiao, Junwen Guo, Geng Chen, Jiayi Ma*</sub></sup> | [Paper](https://guobaoxiao.github.io/papers/PR_2022_BSCA.pdf)/Code/Seg-Maps	
| 2022 | TRFRNet(UDA) | MICCAI | Task-Relevant Feature Replenishment for Cross-Centre Polyp Segmentation <br><sup><sub>*Yutian Shen, Ye Lu, Xiao Jia, Fan Bai, Max Q.-H. Meng*</sub></sup> | [Paper](https://link.springer.com/10.1007/978-3-031-16440-8_57)/[Code](https://github.com/CathyS1996/TRFRNet)/Seg-Maps	
| 2022 | TGANet| MICCAI | TGANet: Text-guided attention for improved polyp segmentation <br><sup><sub>*Nikhil Kumar Tomar, Debesh Jha, Ulas Bagci, Sharib Ali*</sub></sup> | [Paper](https://arxiv.org/pdf/2205.04280v1.pdf)/[Code](https://github.com/nikhilroxtomar/tganet)/Seg-Maps
| 2022 | LDNet | MICCAI | Lesion-Aware Dynamic Kernel for Polyp Segmentation <br><sup><sub>*Ruifei Zhang, Peiwen Lai, Xiang Wan, De-Jun Fan, Feng Gao, Xiao-Jian Wu, Guanbin Li*</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-16437-8_10)/[Code](https://github.com/ReaFly/LDNet)/Seg-Maps
| 2022 | SSFormer | MICCAI | Stepwise Feature Fusion: Local Guides Global <br><sup><sub>*Jinfeng Wang, Qiming Huang, Feilong Tang, Jia Meng, Jionglong Su, Sifan Song*</sub></sup> | [Paper](https://doi.org/10.1007/978-3-031-16437-8_11)/[Code](https://github.com/Qiming-Huang/ssformer)/Seg-Maps
| 2022 | BoxPolyp | MICCAI | BoxPolyp: Boost Generalized Polyp Segmentation Using Extra Coarse Bounding Box Annotations <br><sup><sub>*Jun Wei, Yiwen Hu, Guanbin Li, Shuguang Cui, S. Kevin Zhou, Zhen Li*</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-16437-8_7)/Code/Seg-Maps
| 2022 | PPFormer | MICCAI | Using Guided Self-Attention with Local Information for Polyp Segmentation <br><sup><sub>*Linghan Cai, Meijing Wu, Lijiang Chen, Wenpei Bai, Min Yang, Shuchang Lyu, Qi Zhao *</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-16440-8_60)/Code/Seg-Maps
| 2022 | SSTAN(Semi-Supervised) | MICCAI | Semi-supervised Spatial Temporal Attention Network for Video Polyp Segmentation <br><sup><sub>*Xinkai Zhao1, Zhenhua Wu, Shuangyi Tan, De-Jun Fan, Zhen Li, Xiang Wan, Guanbin Li*</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-16440-8_44)/[Code](https://github.com/ShinkaiZ/SSTAN)/Seg-Maps
| 2022 | MSRF-Net | JBHI | MSRF-Net: A Multi-Scale Residual Fusion Network for Biomedical Image Segmentation <br><sup><sub>*Abhishek Srivastava, Debesh Jha, Sukalpa Chanda, Umapada Pal, Håvard D. Johansen, Dag Johansen, Michael A. Riegler, Sharib Ali, Pål Halvorsen*</sub></sup> | [Paper](https://arxiv.org/pdf/2105.07451v2.pdf)/[Code](https://github.com/NoviceMAn-prog/MSRF-Net)/Seg-Maps
| 2022 | BCNet | JBHI | Boundary Constraint Network With Cross Layer Feature Integration for Polyp Segmentation <br><sup><sub>*Guanghui Yue, Wanwan Han, Bin Jiang, Tianwei Zhou, Runmin Cong, Tianfu Wang*</sub></sup> | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9772424)/Code/Seg-Maps
| 2022 | DCRNet | ISBI | Duplex contextual relation network for polyp segmentation <br><sup><sub>*Zijin Yin, Kongming Liang, Zhanyu Ma, Jun Guo*</sub></sup> | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9761402)/[Code](https://github.com/PRIS-CV/DCRNet)/Seg-Maps
| 2022 | FCBFormer | MIUA | FCN-Transformer Feature Fusion for Polyp Segmentation <br><sup><sub>*Edward Sanderson, Bogdan J. Matuszewski*</sub></sup> | [Paper](https://arxiv.org/pdf/2208.08352v1.pdf)/[Code](https://github.com/ESandML/FCBFormer)/Seg-Maps
| 2022 | ColonFormer | Access | ColonFormer: An Efficient Transformer based Method for Colon Polyp Segmentation <br><sup><sub>*Nguyen Thanh Duc, Nguyen Thi Oanh, Nguyen Thi Thuy, Tran Minh Triet, Dinh Viet Sang*</sub></sup> | [Paper](https://arxiv.org/pdf/2205.08473v3.pdf)/[Code](https://github.com/ducnt9907/ColonFormer)/Seg-Maps
| 2022 | BDG-Net | Medical Imaging 2022: Image Processing | BDG-Net: Boundary Distribution Guided Network for Accurate Polyp Segmentation <br><sup><sub>*Zihuan Qiu, Zhichuan Wang, Miaomiao Zhang, Ziyong Xu, Jie Fan, Linfeng Xu*</sub></sup> | [Paper](https://arxiv.org/pdf/2201.00767v2.pdf)/[Code](https://github.com/zihuanqiu/BDG-Net)/Seg-Maps
| 2022 | HarDNet-DFUS | Arxiv | HarDNet-DFUS: An Enhanced Harmonically-Connected Network for Diabetic Foot Ulcer Image Segmentation and Colonoscopy Polyp Segmentation <br><sup><sub>*Ting-Yu Liao, Ching-Hui Yang, Yu-Wen Lo, Kuan-Ying Lai, Po-Huai Shen, Youn-Long Lin*</sub></sup> | [Paper](https://arxiv.org/pdf/2209.07313v1.pdf)/[Code](https://github.com/yuwenlo/hardnet-dfus)/Seg-Maps
| 2022 | DuAT | Arxiv | DuAT: Dual-Aggregation Transformer Network for Medical Image Segmentation <br><sup><sub>*Feilong Tang, Qiming Huang, Jinfeng Wang, Xianxu Hou, Jionglong Su, Jingxin Liu*</sub></sup> | [Paper](https://arxiv.org/pdf/2212.11677v1.pdf)/[Code](https://github.com/Barrett-python/DuAT)/Seg-Maps
| 2022 | SEP | Arxiv | Spatially Exclusive Pasting: A General Data Augmentation for the Polyp Segmentation <br><sup><sub>*Lei Zhou*</sub></sup> | [Paper](https://arxiv.org/pdf/2211.08284v3.pdf)/Code/Seg-Maps
| 2022 | TC-Net | BIBM | Temporal Correlation Network for Video Polyp Segmentation <br><sup><sub>*Ziheng Xu, Dehui Qiu, Senlin Lin, Xinyue Zhang, Sheng Shi, Shengtao Zhu, Fa Zhang, Xiaohua Wan*</sub></sup> | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9995646)/Code/Seg-Maps
| 2022 | TransMixer | BIBM | TransMixer: A Hybrid Transformer and CNN Architecture for Polyp Segmentation <br><sup><sub>*Yanglin Huang, Donghui Tan, Yuan Zhang, Xuanya Li, Kai Hu*</sub></sup> | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9995247)/Code/Seg-Maps
| 2022 | ICBNet | BIBM | ICBNet: Iterative Context-Boundary Feedback Network for Polyp Segmentation <br><sup><sub>*Yefan Xiao, Zhihao Chen, Liang Wan, Lequan Yu, Lei Zhu*</sub></sup> | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9995022)/Code/Seg-Maps
| 2022 | CLD-Net | BIBM | CLD-Net: Complement Local Detail For Medical Small-Object Segmentation <br><sup><sub>*Rui Chen, Xiangfeng Wang, Bo Jin, Jiaqi Tu, Fengping Zhu, Yuxin Li*</sub></sup> | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9995217)/Code/Seg-Maps
| 2022 | TASNet | BIBM | Single-Modality Endoscopic Polyp Segmentation via Random Color Reversal Synthesis and Two-Branched Learning <br><sup><sub>*Mingzhu Chen, Xiaotong Li, Jilan Xu, Runtian Yuan, Yuejie Zhang, Rui Feng, Tao Zhang, Shang Gao*</sub></sup> | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9995402)/Code/Seg-Maps
| 2022 | unnamed | PRCV | Boundary-Aware Polyp Segmentation Network <br><sup><sub>*Lu Lu, Xitong Zhou, Shuhan Chen, Zuyu Chen, Jinhao Yu, Haonan Tang, Xuelong Hu*</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-18916-6_6)/Code/Seg-Maps
| 2022 | FuzzyNet | NeurIPS  Workshop | FuzzyNet: A Fuzzy Attention Module for Polyp Segmentation <br><sup><sub>*Krushi Patel, Fenjun Li, Guanghui Wang*</sub></sup> | [Paper](https://openreview.net/pdf?id=bDa_0vVujZ)/[Code](https://github.com/krushi1992/FuzzyNet)/Seg-Maps
| 2022 | SwinPA-Net | TNNLS | SwinPA-Net: Swin Transformer-Based Multiscale Feature Pyramid Aggregation Network for Medical Image Segmentation <br><sup><sub>*Hao Du, Jiazheng Wang, Min Liu, Yaonan Wang, Erik Meijering*</sub></sup> | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9895210)/Code/Seg-Maps
| 2022 | HSNet | CompBioMed | HSNet: A hybrid semantic network for polyp segmentation <br><sup><sub>*Wenchao Zhang, Chong Fu, Yu Zheng, Fangyuan Zhang, Yanli Zhao, Chiu-Wing Sham*</sub></sup> | [Paper](https://reader.elsevier.com/reader/sd/pii/S0010482522008812?token=EE7BA1875E01966A91E578639EFD828DDF0DC70EB31040C21B84577ACCE553691F6A00C24E0031488E2F0D28C583ECE0&originRegion=us-east-1&originCreation=20230518091751)/[Code](https://github.com/baiboat/HSNet)/Seg-Maps
| 2022 | MSRAformer | CompBioMed | MSRAformer: Multiscale spatial reverse attention network for polyp segmentation <br><sup><sub>*Cong Wu, Cheng Long, Shijun Li, Junjie Yang, Fagang Jiang, Ran Zhou*</sub></sup> | [Paper](https://reader.elsevier.com/reader/sd/pii/S0010482522009829?token=A592C64A25DCBB2D9EF047355807B6E491D19B8D4788C1F7EE939FD430DF3933A14CA70EA670E52F24B87E33D3FDACDA&originRegion=us-east-1&originCreation=20230518090647)/[Code](https://github.com/ChengLong1222/MSRAformer-main)/Seg-Maps

	


####  2.2.3. YEAR 2021

| **Year** | **Model** | **Publication** | **Title**                                 |  **Links**                                                    |
| :------: | :------: |:------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
| 2021 | MSNet | MICCAI | Automatic Polyp Segmentation via Multi-scale Subtraction Network <br><sup><sub>*Xiaoqi Zhao, Lihe Zhang, Huchuan Lu*</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-87193-2_12)/[Code](https://github.com/Xiaoqi-Zhao-DLUT/MSNet-M2SNet)/Seg-Maps	
| 2021 | CCBANet | MICCAI | CCBANet: Cascading Context and Balancing Attention for Polyp Segmentation <br><sup><sub>*Tan-Cong Nguyen, Tien-Phat Nguyen, Gia-Han Diep, Anh-Huy Tran-Dinh, Tam V. Nguyen, Minh-Triet Tran*</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-87193-2_60)/[Code](https://github.com/ntcongvn/CCBANet)/Seg-Maps	
| 2021 | HRENet | MICCAI | HRENet: A Hard Region Enhancement Network for Polyp Segmentation <br><sup><sub>*Yutian Shen, Xiao Jia, Max Q.-H. Meng</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-87193-2_53)/[Code](https://github.com/CathySH/HRENet)/Seg-Maps	
| 2021 | PNS-Net | MICCAI | Progressively Normalized Self-Attention Network for Video Polyp Segmentation <br><sup><sub>*Ge-Peng Ji, Yu-Cheng Chou, Deng-Ping Fan, Geng Chen, Huazhu Fu, Debesh Jha, Ling Shao</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-87193-2_14)/[Code](http://dpfan.net/pnsnet/)/Seg-Maps
| 2021 | LOD-Net | MICCAI | Learnable Oriented-Derivative Network for Polyp Segmentation <br><sup><sub>*Mengjun Cheng, Zishang Kong, Guoli Song, Yonghong Tian, Yongsheng Liang, Jie Chen*</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-87193-2_68)/[Code](https://github.com/midsdsy/LOD-Net)/Seg-Maps	
| 2021 | STFT | MICCAI | Multi-frame Collaboration for Effective Endoscopic Video Polyp Detection via Spatial-Temporal Feature Transformation <br><sup><sub>*Lingyun Wu, Zhiqiang Hu, Yuanfeng Ji, Ping Luo, Shaoting Zhang*</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-87240-3_29)/[Code](https://github.com/lingyunwu14/STFT)/Seg-Maps	
| 2021 | SANet | MICCAI | Shallow Attention Network for Polyp Segmentation <br><sup><sub>*Jun Wei, Yiwen Hu, Ruimao Zhang, Zhen Li, S. Kevin Zhou, Shuguang Cui*</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-87193-2_66)/[Code](https://github.com/weijun88/sanet)/Seg-Maps
| 2021 | TransFuse | MICCAI | TransFuse: Fusing Transformers and CNNs for Medical Image Segmentation <br><sup><sub>*Yundong Zhang, Huiye Liu, Qiang Hu*</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-87193-2_2)/[Code](https://github.com/Rayicer/TransFuse)/Seg-Maps	
| 2021 | MPA-DA(UDA) | JBHI | Mutual-Prototype Adaptation for Cross-Domain Polyp Segmentation <br><sup><sub>*Chen Yang, Xiaoqing Guo, Meilu Zhu, Bulat Ibragimov, Yixuan Yuan*</sub></sup> | [Paper](https://ieeexplore.ieee.org/document/9423517/)/[Code](https://github.com/CityU-AIM-Group/MPA-DA)/Seg-Maps
| 2021 | ResUNet++ + TTA + CRF | JBHI | A Comprehensive Study on Colorectal Polyp Segmentation with ResUNet++, Conditional Random Field and Test-Time Augmentation <br><sup><sub>*Debesh Jha, Pia H. Smedsrud, Dag Johansen, Thomas de Lange, Havard D. Johansen, Pal Halvorsen, and Michael A. Riegler*</sub></sup> | [Paper](https://arxiv.org/pdf/2107.12435v1.pdf)/[Code](https://github.com/DebeshJha/ResUNet-with-CRF-and-TTA)/Seg-Maps
| 2021 | C2FNet | IJCAI | Context-aware Cross-level Fusion Network for Camouflaged Object Detection <br><sup><sub>*Yujia Sun, Geng Chen, Tao Zhou, Yi Zhang, Nian Liu*</sub></sup> | [Paper](https://www.ijcai.org/proceedings/2021/0142.pdf)/[Code](https://github.com/thograce/C2FNet)/Seg-Maps
| 2021 | UACANet | ACM MM | UACANet: Uncertainty Augmented Context Attention for Polyp Segmentation <br><sup><sub>*Taehun Kim, Hyemin Lee, Daijin Kim*</sub></sup> | [Paper](https://arxiv.org/abs/2107.02368)/[Code](https://github.com/plemeri/UACANet)/Seg-Maps
| 2021 | Polyp-PVT | CAAI AIR | Polyp-PVT: Polyp Segmentation with Pyramid Vision Transformers <br><sup><sub>*Bo Dong, Wenhai Wang, Deng-Ping Fan, Jinpeng Li, Huazhu Fu, Ling Shao*</sub></sup> | [Paper](https://arxiv.org/abs/2108.06932)/[Code](https://github.com/DengPingFan/Polyp-PVT)/Seg-Maps
| 2021 | A-DenseUNet | Sensors | A-DenseUNet: Adaptive Densely Connected UNet for Polyp Segmentation in Colonoscopy Images with Atrous Convolution <br><sup><sub>*Safarov SIrojbek*</sub></sup> | [Paper](https://www.mdpi.com/1424-8220/21/4/1441)/Code/Seg-Maps
| 2021 | FANet | TNNLS | FANet: A Feedback Attention Network for Improved Biomedical Image Segmentation <br><sup><sub>*Nikhil Kumar Tomar, Debesh Jha, Michael A. Riegler, Håvard D. Johansen, Dag Johansen, Jens Rittscher, Pål Halvorsen, Sharib Ali*</sub></sup> | [Paper](https://arxiv.org/pdf/2103.17235v3.pdf)/[Code](https://github.com/nikhilroxtomar/fanet)/Seg-Maps
| 2021 | EU-Net | CRV | Enhanced U-Net: A Feature Enhancement Network for Polyp Segmentation <br><sup><sub>*Krushi Patel, Andres M. Bur, Guanghui Wang*</sub></sup> | [Paper](https://arxiv.org/pdf/2105.00999.pdf)/[Code](https://github.com/rucv/Enhanced-U-Net)/Seg-Maps
| 2021 | HarDNet-MSEG | Arxiv | HarDNet-MSEG: A Simple Encoder-Decoder Polyp Segmentation Neural Network that Achieves over 0.9 Mean Dice and 86 FPS <br><sup><sub>*Chien-Hsiang Huang, Hung-Yu Wu, Youn-Long Lin*</sub></sup> | [Paper](https://arxiv.org/abs/2101.07172)/[Code](https://github.com/james128333/HarDNet-MSEG)/Seg-Maps
| 2021 | CaraNet | Arxiv | CaraNet: Context Axial Reverse Attention Network for Segmentation of Small Medical Objects <br><sup><sub>*Ange Lou, Shuyue Guan, Hanseok Ko, Murray Loew*</sub></sup> | [Paper](https://arxiv.org/ftp/arxiv/papers/2108/2108.07368.pdf)/[Code](https://github.com/AngeLouCN/CaraNet)/Seg-Maps
| 2021 | GMSRF-Net | Arxiv | GMSRF-Net: An improved generalizability with global multi-scale residual fusion network for polyp segmentation <br><sup><sub>*Abhishek Srivastava, Sukalpa Chanda, Debesh Jha, Umapada Pal, Sharib Ali*</sub></sup> | [Paper](https://arxiv.org/pdf/2111.10614v1.pdf)/[Code](https://github.com/NoviceMAn-prog/GMSRFNet)/Seg-Maps
	
####  2.2.4. Before YEAR 2021 

| **Year** | **Model** | **Publication** | **Title**                                 |  **Links**                                                    |
| :------: | :------: |:------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
| 2020 | PraNet | MICCAI | PraNet: Parallel Reverse Attention Network for Polyp Segmentation <br><sup><sub>*Deng-Ping Fan, Ge-Peng Ji, Tao Zhou, Geng Chen, Huazhu Fu, Jianbing Shen, Ling Shao*</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-59725-2_26)/[Code](https://github.com/DengPingFan/PraNet)/Seg-Maps
| 2020 | ACSNet | MICCAI | Adaptive Context Selection for Polyp Segmentation <br><sup><sub>*Ruifei Zhang, Guanbin Li, Zhen Li, Shuguang Cui, Dahong Qian, Yizhou Yu*</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-59725-2_25)/[Code](https://github.com/ReaFly/ACSNet)/Seg-Maps
| 2020 | PolypSeg | MICCAI | PolypSeg: An Efficient Context-Aware Network for Polyp Segmentation from Colonoscopy Videos <br><sup><sub>*Jiafu Zhong, Wei Wang, Huisi Wu, Zhenkun Wen, Jing Qin*</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-59725-2_28)/Code/Seg-Maps
| 2020 | ThresholdNet | TMI | Learn to Threshold: ThresholdNet With Confidence-Guided Manifold Mixup for Polyp Segmentation <br><sup><sub>*Xiaoqing Guo, Chen Yang, Yajie Liu, Yixuan Yuan*</sub></sup> | [Paper](https://ieeexplore.ieee.org/document/9305717)/[Code](https://github.com/Guo-Xiaoqing/ThresholdNet)/Seg-Maps
| 2019 | ResUNet++ | ISM | ResUNet++: An Advanced Architecture for Medical Image Segmentation <br><sup><sub>*Debesh Jha, Pia H. Smedsrud, Michael A. Riegler, Dag Johansen, Thomas de Lange, Pal Halvorsen, Havard D. Johansen*</sub></sup> | [Paper](https://arxiv.org/pdf/1911.07067.pdf)/[Code](https://github.com/DebeshJha/ResUNetPlusPlus)/Seg-Maps
| 2019 | SFA | MICCAI | Selective Feature Aggregation Network with Area-Boundary Constraints for Polyp Segmentation <br><sup><sub>*Yuqi Fang, Cheng Chen, Yixuan Yuan, Kai-yu Tong*</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-32239-7_34)/[Code](https://github.com/Yuqi-cuhk/Polyp-Seg)/Seg-Maps


###  2.3. Video Polyp Segmentation

| **Year** | **Model** | **Publication** | **Title**                                 |  **Links**                                                    |
| :------: | :------: |:------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |	
| 2023 | ESFPNet | Medical Imaging 2023: Biomedical Applications in Molecular, Structural, and Functional Imaging | ESFPNet: efficient deep learning architecture for real-time lesion segmentation in autofluorescence bronchoscopic video <br><sup><sub>*Qi Chang, Danish Ahmad, Jennifer Toth, Rebecca Bascom, William E. Higgins*</sub></sup> | [Paper](https://arxiv.org/pdf/2207.07759v3.pdf)/[Code](https://github.com/dumyCq/ESFPNet)/Seg-Maps
| 2020 | PraNet | MICCAI | PraNet: Parallel Reverse Attention Network for Polyp Segmentation <br><sup><sub>*Deng-Ping Fan, Ge-Peng Ji, Tao Zhou, Geng Chen, Huazhu Fu, Jianbing Shen, Ling Shao*</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-59725-2_26)/[Code](https://github.com/DengPingFan/PraNet)


