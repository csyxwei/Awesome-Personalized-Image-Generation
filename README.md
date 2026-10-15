# Personalization Image Generation with Generative Models

This repo is used for recording and tracking recent personalized image generation with different generative models. For more detailed information, please refer to our survey paper: [Personalized Image Generation with Deep Generative Models: A Decade Survey](https://arxiv.org/pdf/2502.13081).

![](assets/personalization_methods.png)

## Contents

![](assets/outline.png)

- [Personalization with Diffusion Models](#Personalization-with-Diffusion-Models)
    - [Subject-Driven Generation](#Subject-Driven-Generation)
    - [Face-Driven Generation](#Face-Driven-Generation)
    - [Character-Driven Generation](#Character-Driven-Generation)
    - [Style-Driven Generation](#Style-Driven-Generation)
    - [High-level Semantics Generation](#High-level-Semantics-Generation)
    - [Multiple Concepts Generation](#Multiple-Concepts-Generation)
    - [Text-driven Image Editing](#Text-driven-Image-Editing)
    - [Personalized Video Generation](#Personalized-Video-Generation)
    - [Personalized 3D Generation](#Personalized-3D-Generation)
- [Personalization with AR Models](#Personalization-with-AR-Models)
- [Personalization with GANs](#Personalization-with-GANs)
  - [GAN Inversion](#GAN-Inversion)
  - [Latent Editing](#Latent-Editing)
- [Related Benchmarks](#Related-Benchmarks)
- [Related Surveys](#Related-Surveys)

## Personalization with Diffusion Models

### Subject-Driven Generation

**PaCo-RL: Advancing Reinforcement Learning for Consistent Image Generation with Pairwise Reward Modeling**<br>
*Bowen Ping, Chengyou Jia, Minnan Luo, Changliang Xia, Xin Shen, Zhuohang Dang, Hangwei Qian*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2512.04784) / [Project](https://x-gengroup.github.io/HomePage_PaCo-RL/) / [Code](https://github.com/X-GenGroup/PaCo-RL)

**MINDiff: Mask-Integrated Negative Attention for Controlling Overfitting in Text-to-Image Personalization**<br>
*Seulgi Jeong, Jaeil Kim*<br>
ICCV 2025W.  / [PDF](http://arxiv.org/abs/2511.17888) / [Code](https://github.com/seuleepy/MINDiff)

**Infinite-Story: A Training-Free Consistent Text-to-Image Generation**<br>
*Jihun Park, Kyoungmin Lee, Jongmin Gim, Hyeonseo Jo, Minseok Oh, Wonhyeok Choi, Kyumin Hwang, Jaeyeul Kim, Minwoo Choi, Sunghoon Im*<br>
AAAI 2026.  / [PDF](http://arxiv.org/abs/2511.13002)

**EchoDistill: Bidirectional Concept Distillation for One-Step Diffusion Personalization**<br>
*Yixiong Yang, Tao Wu, Senmao Li, Shiqi Yang, Yaxing Wang, Joost Weijer, Kai Wang*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2510.20512) / [Project](https://liulisixin.github.io/EchoDistill-page/)

**From Competition to Synergy: Unlocking Reinforcement Learning for Subject-Driven Image Generation**<br>
*Ziwei Huang, Ying Shu, Hao Fang, Quanyu Long, Wenya Wang, Qiushi Guo, Tiezheng Ge, Leilei Gan*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2510.18263)

**UniFusion: Vision-Language Model as Unified Encoder in Image Generation**<br>
*Kevin Li, Manuel Brack, Sudeep Katakol, Hareesh Ravi, Ajinkya Kale*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2510.12789) / [Project](https://thekevinli.github.io/unifusion/)

**ReMix: Towards a Unified View of Consistent Character Generation and Editing**<br>
*Benjia Zhou, Bin Fu, Pei Cheng, Yanru Wang, Jiayuan Fan, Tao Chen*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2510.10156)

**IC-Custom: Diverse Image Customization via In-Context Learning**<br>
*Yaowei Li, Xiaoyu Li, Zhaoyang Zhang, Yuxuan Bian, Gan Liu, Xinyuan Li, Jiale Xu, Wenbo Hu, Yating Liu, Lingen Li, Jing Cai, Yuexian Zou, Yancheng He, Ying Shan*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2507.01926) / [Project](https://liyaowei-stu.github.io/project/IC_Custom/) / [Code](https://github.com/TencentARC/IC-Custom)

**TIDE: Achieving Balanced Subject-Driven Image Generation via Target-Instructed Diffusion Enhancement**<br>
*Jibai Lin, Bo Ma, Yating Yang, Xi Zhou, Rong Ma, Turghun Osman, Ahtamjan Ahmat, Rui Dong, Lei Wang*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2509.06499) / [Code](https://github.com/KomJay520/TIDE)

**Memory-Efficient Personalization of Text-to-Image Diffusion Models via Selective Optimization Strategies**<br>
*Seokeon Choi, Sunghyun Park, Hyoungwoo Park, Jeongho Kim, Sungrack Yun*<br>
ICCV 2025 LIMIT Workshop.  / [PDF](http://arxiv.org/abs/2507.10029)

**MM-R1: Unleashing the Power of Unified Multimodal Large Language Models for Personalized Image Generation**<br>
*Qian Liang, Yujia Wu, Kuncheng Li, Jiwei Wei, Shiyuan He, Jinyu Guo, Ning Xie*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2508.11433)

**Echo-4o: Harnessing the Power of GPT-4o Synthetic Images for Improved Image Generation**<br>
*Junyan Ye, Dongzhi Jiang, Zihao Wang, Leqi Zhu, Zhenghao Hu, Zilong Huang, Jun He, Zhiyuan Yan, Jinghua Yu, Hongsheng Li, Conghui He, Weijia Li*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2508.09987) / [Code](https://github.com/yejy53/Echo-4o) / [Dataset](https://huggingface.co/datasets/Yejy53/Echo-4o-Image)

**Lay2Story: Extending Diffusion Transformers for Layout-Togglable Story Generation**<br>
*Ao Ma, Jiasong Feng, Ke Cao, Jing Wang, Yun Wang, Quanwei Zhang, Zhanjie Zhang*<br>
ICCV 2025.  / [PDF](http://arxiv.org/abs/2508.08949)

**Steering Guidance for Personalized Text-to-Image Diffusion Models**<br>
*Sunghyun Park, Seokeon Choi, Hyoungwoo Park, Sungrack Yun*<br>
ICCV 2025.  / [PDF](http://arxiv.org/abs/2508.00319)

**HOComp: Interaction-Aware Human-Object Composition**<br>
*Dong Liang, Jinyuan Jia, Yuhao Liu, Rynson W. H. Lau*<br>
NeurIPS 2025.  / [PDF](http://arxiv.org/abs/2507.16813) / [Project](https://dliang293.github.io/HOComp-project/) / [Code](https://github.com/dliang293/HOComp)

**Improving Personalized Image Generation through Social Context Feedback**<br>
*Parul Gupta, Abhinav Dhall, Thanh-Toan Do*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2507.16095)

**FreeCus: Free Lunch Subject-driven Customization in Diffusion Transformers**<br>
*Yanbing Zhang, Zhe Wang, Qin Zhou, Mengping Yang*<br>
ICCV 2025.  / [PDF](http://arxiv.org/abs/2507.15249) / [Code](https://github.com/Monalissaa/FreeCus)

**T-LoRA: Single Image Diffusion Model Customization Without Overfitting**<br>
*Vera Soboleva, Aibek Alanov, Andrey Kuznetsov, Konstantin Sobolev*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2507.05964) / [Code](https://github.com/ControlGenAI/T-LoRA)

**APT: Adaptive Personalized Training for Diffusion Models with Limited Data**<br>
*JungWoo Chae, Jiyoon Kim, JaeWoong Choi, Kyungyul Kim, Sangheum Hwang*<br>
CVPR 2025.  / [PDF](http://arxiv.org/abs/2507.02687) / [Project](https://lgcnsai.github.io/apt/)

**Noise Consistency Regularization for Improved Subject-Driven Image Synthesis**<br>
*Yao Ni, Song Wen, Piotr Koniusz, Anoop Cherian*<br>
CVPR 2025W.  / [PDF](http://arxiv.org/abs/2506.06483)

**Parallel Rescaling: Rebalancing Consistency Guidance for Personalized Diffusion Models**<br>
*JungWoo Chae, Jiyoon Kim, Sangheum Hwang*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2506.00607)

**Dimension-Reduction Attack! Video Generative Models are Experts on Controllable Image Synthesis**<br>
*Hengyuan Cao, Yutong Feng, Biao Gong, Yijing Tian, Yunhong Lu, Chuang Liu, Bin Wang*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2505.23325) / [Project](https://dra-ctrl-2025.github.io/DRA-Ctrl/) / [Code](https://github.com/Kunbyte-AI/DRA-Ctrl)

**Identity-Preserving Text-to-Image Generation via Dual-Level Feature Decoupling and Expert-Guided Fusion**<br>
*Kewen Chen, Xiaobin Hu, Wenqi Ren*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2505.22360)

**AlignGen: Boosting Personalized Image Generation with Cross-Modality Prior Alignment**<br>
*Yiheng Lin, Shifang Zhao, Ting Liu, Xiaochao Qu, Luoqi Liu, Yao Zhao, Yunchao Wei*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2505.21911)

**DreamBoothDPO: Improving Personalized Generation using Direct Preference Optimization**<br>
*Shamil Ayupov, Maksim Nakhodnov, Anastasia Yaschenko, Andrey Kuznetsov, Aibek Alanov*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2505.20975) / [Code](https://github.com/ControlGenAI/DreamBoothDPO)

**Geometry-Editable and Appearance-Preserving Object Compositon**<br>
*Jianman Lin, Haojie Li, Chunmei Qing, Zhijing Yang, Liang Lin, Tianshui Chen*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2505.20914)

**Regularized Personalization of Text-to-Image Diffusion Models without Distributional Drift**<br>
*Gihoon Kim, Hyungjin Park, Taesup Kim*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2505.19519)

**In-Context Brush: Zero-shot Customized Subject Insertion with Context-Aware Latent Space Manipulation**<br>
*Yu Xu, Fan Tang, You Wu, Lin Gao, Oliver Deussen, Hongbin Yan, Jintao Li, Juan Cao, Tong-Yee Lee*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2505.20271)

**OmniGen2: Exploration to Advanced Multimodal Generation**<br>
*Chenyuan Wu, Pengfei Zheng, Ruiran Yan, Shitao Xiao, Xin Luo, Yueze Wang, Wanli Li, Xiyan Jiang, Yexin Liu, Junjie Zhou, Ze Liu, Ziyi Xia, Chaofan Li, Haoge Deng, Jiahao Wang, Kun Luo, Bo Zhang, Defu Lian, Xinlong Wang, Zhongyuan Wang, Tiejun Huang, Zheng Liu*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2506.18871) / [Project](https://vectorspacelab.github.io/OmniGen2) / [Code](https://github.com/VectorSpaceLab/OmniGen2)

**MMIG-Bench: Towards Comprehensive and Explainable Evaluation of Multi-Modal Image Generation Models**<br>
*Hang Hua, Ziyun Zeng, Yizhi Song, Yunlong Tang, Liu He, Daniel Aliaga, Wei Xiong, Jiebo Luo*<br>
Arxiv 2025. / [PDF](https://arxiv.org/pdf/2505.19415) / [Project](https://github.com/hanghuacs/MMIG-Bench) / [Code](https://github.com/hanghuacs/MMIG-Bench)

**Visually Guided Decoding: Gradient-Free Hard Prompt Inversion with Language Models**<br>
*Donghoon Kim, Minji Bae, Kyuhong Shim, Byonghyo Shim*<br>
ICLR 2025. / [PDF](https://arxiv.org/abs/2505.08622) 

**DRC: Enhancing Personalized Image Generation via Disentangled Representation Composition**<br>
*Yiyan Xu, Wuqiang Zheng, Wenjie Wang, Fengbin Zhu, Xinting Hu, Yang Zhang, Fuli Feng, Tat-Seng Chua*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2504.17349)

**FreeGraftor: Training-Free Cross-Image Feature Grafting for Subject-Driven Text-to-Image Generation**<br>
*Zebin Yao, Lei Ren, Huixing Jiang, Chen Wei, Xiaojie Wang, Ruifan Li, Fangxiang Feng*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2504.15958) / [Code](https://github.com/Nihukat/FreeGraftor) 

**Flux Already Knows - Activating Subject-Driven Image Generation without Training**<br>
*Hao Kang, Stathi Fotiadis, Liming Jiang, Qing Yan, Yumin Jia, Zichuan Liu, Min Jin Chong, Xin Lu*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2504.11478) / [Code](http://github.com/bytedance/LatentUnfold) 

**VisualCloze: A Universal Image Generation Framework via Visual In-Context Learning**<br>
*Zhong-Yu Li, Ruoyi Du, Juncheng Yan, Le Zhuo, Zhen Li, Peng Gao, Zhanyu Ma, Ming-Ming Cheng*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2504.07960) / [Project](https://visualcloze.github.io/) / [Code](https://github.com/lzyhha/VisualCloze)

**FlexIP: Dynamic Control of Preservation and Personality for Customized Image Generation**<br>
*Linyan Huang, Haonan Lin, Yanning Zhou, Kaiwen Xiao*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2504.07405) / [Project](https://flexip-tech.github.io/flexip/#/)

**Transfer between Modalities with MetaQueries**<br>
*Xichen Pan, Satya Narayan Shukla, Aashu Singh, Zhuokai Zhao, Shlok Kumar Mishra, Jialiang Wang, Zhiyang Xu, Jiuhai Chen, Kunpeng Li, Felix Juefei-Xu, Ji Hou, Saining Xie*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2504.06256) / [Project](https://xichenpan.com/metaquery/) 

**CREA: A Collaborative Multi-Agent Framework for Creative Content Generation with Diffusion Models**<br>
*Kavana Venkatesh, Connor Dunlop, Pinar Yanardag*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2504.05306) / [Project](https://crea-diffusion.github.io/) 

**Single Image Iterative Subject-driven Generation and Editing**<br>
*Yair Shpitzer, Gal Chechik, Idan Schwartz*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2503.16025) / [Project](https://siso-paper.github.io/) / [Code](https://github.com/yairshp/SISO)

**TF-TI2I: Training-Free Text-and-Image-to-Image Generation via Multi-Modal Implicit-Context Learning in Text-to-Image Models**<br>
*Teng-Fang Hsiao, Bo-Kai Ruan, Yi-Lun Wu, Tzu-Ling Lin, Hong-Han Shuai*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2503.15283) / [Project](https://bluedyee.github.io/TF-TI2I_page/) / [Code](https://github.com/BlueDyee/TF-TI2I)

**Personalize Anything for Free with Diffusion Transformer**<br>
*Haoran Feng, Zehuan Huang, Lin Li, Hairong Lv, Lu Sheng*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2503.12590) / [Project](https://fenghora.github.io/Personalize-Anything-Page/) / [Code](https://github.com/fenghora/personalize-anything)

**UniCombine: Unified Multi-Conditional Combination with Diffusion Transformer**<br>
*Haoxuan Wang, Jinlong Peng, Qingdong He, Hao Yang, Ying Jin, Jiafu Wu, Xiaobin Hu, Yanjie Pan, Zhenye Gan, Mingmin Chi, Bo Peng, Yabiao Wang*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2503.09277) / [Code](https://github.com/Xuan-World/UniCombine)

**RealGeneral: Unifying Visual Generation via Temporal In-Context Learning with Video Models**<br>
*Yijing Lin, Mengqi Huang, Shuhan Zhuang, Zhendong Mao*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2503.10406) / [Project](https://lyne1.github.io/realgeneral_web/)

**OminiControl2: Efficient Conditioning for Diffusion Transformers**<br>
*Zhenxiong Tan, Qiaochu Xue, Xingyi Yang, Songhua Liu, Xinchao Wang*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2503.08280) / [Code](https://github.com/Yuanshi9815/OminiControl)

**ConceptGuard: Continual Personalized Text-to-Image Generation with Forgetting and Confusion Mitigation**<br>
*Zirun Guo, Tao Jin*<br>
CVPR 2025. / [PDF](https://arxiv.org/abs/2503.10358)

**LatexBlend: Scaling Multi-concept Customized Generation with Latent Textual Blending**<br>
*Jian Jin, Zhenbo Yu, Yang Shen, Zhenyong Fu, Jian Yang*<br>
CVPR 2025. / [PDF](https://arxiv.org/abs/2503.06956) / [Project](https://jinjianrick.github.io/latexblend/)

**Towards More Accurate Personalized Image Generation: Addressing Overfitting and Evaluation Bias**<br>
*Mingxiao Li, Tingyu Qu, Tinne Tuytelaars, Marie-Francine Moens*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2503.06632) / [Code](https://github.com/Mingxiao-Li/Towards-More-Accurate-Personalized-Image-Generation)

**Conceptrol: Concept Control of Zero-shot Personalized Image Generation**<br>
*Qiyuan He, Angela Yao*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2503.06568) / [Project](https://qy-h00.github.io/Conceptrol/) / [Code](https://github.com/QY-H00/Conceptrol)

**ACCORD: Alleviating Concept Coupling through Dependence Regularization for Text-to-Image Diffusion Personalization**<br>
*Shizhan Liu, Hao Zheng, Hang Yu, Jianguo Li*<br>
Arxiv 2025. / [PDF](https://www.arxiv.org/abs/2503.01122)

**Generating Multi-Image Synthetic Data for Text-to-Image Customization**<br>
*Nupur Kumari, Xi Yin, Jun-Yan Zhu, Ishan Misra, Samaneh Azadi*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2502.01720) / [Project](https://www.cs.cmu.edu/~syncd-project/) / [Code](https://github.com/nupurkmr9/syncd)

**Beyond Fine-Tuning: A Systematic Study of Sampling Techniques in Personalized Image Generation**<br>
*Vera Soboleva, Maksim Nakhodnov, Aibek Alanov*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2502.05895) 

**Nested Attention: Semantic-aware Attention Values for Concept Personalization**<br>
*Patashnik, Or and Gal, Rinon and Ostashev, Daniil and Tulyakov, Sergey and Aberman, Kfir and Cohen-Or, Daniel.*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2501.01407)  / [Project](https://snap-research.github.io/NestedAttention/)

**AnyDressing: Customizable Multi-Garment Virtual Dressing via Latent Diffusion Models**<br>
*Li, Xinghui and Sun, Qichao and Zhang, Pengze and Ye, Fulong and Liao, Zhichao and Feng, Wanquan and Zhao, Songtao and He, Qian.*<br>
CVPR 2025.  / [PDF](https://arxiv.org/abs/2412.04146)  / [Project](https://crayon-shinchan.github.io/AnyDressing/)  / [Code](https://github.com/Crayon-Shinchan/AnyDressing)

**LoRACLR: Contrastive Adaptation for Customization of Diffusion Models**<br>
*Enis Simsar, Thomas Hofmann, Federico Tombari, Pinar Yanardag*<br>
CVPR 2025.  / [PDF](https://arxiv.org/abs/2412.09622)  / [Project](https://loraclr.github.io/)

**Customized Generation Reimagined: Fidelity and Editability Harmonized**<br>
*Jin, Jian and Shen, Yang and Fu, Zhenyong and Yang, Jian.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2412.04831v1)  / [Code](https://github.com/jinjianRick/DCI_ICO)

**P3S-Diffusion: A Selective Subject-driven Generation Framework via Point Supervision**<br>
*Hu, Junjie and Gao, Shuyong and Hong, Lingyi and Wang, Qishan and Zhao, Yuzhou and Wang, Yan and Zhang, Wenqiang.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2412.19533)

**Large-Scale Text-to-Image Model with Inpainting is a Zero-Shot Subject-Driven Image Generator**<br>
*Shin, Chaehun and Choi, Jooyoung and Kim, Heeseung and Yoon, Sungroh.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2411.15466)  / [Project](https://diptychprompting.github.io/)

**DreamCache: Finetuning-Free Lightweight Personalized Image Generation via Feature Caching**<br>
*Aiello, Emanuele and Michieli, Umberto and Valsesia, Diego and Ozay, Mete and Magli, Enrico.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2411.17786)  / [Project](https://emanuele97x.github.io/DreamCache/)  / [Code](https://github.com/Emanuele97x/DreamCache)

**Diffusion Self-Distillation for Zero-Shot Customized Image Generation**<br>
*Cai, Shengqu and Chan, Eric and Zhang, Yunzhi and Guibas, Leonidas and Wu, Jiajun and Wetzstein, Gordon.*<br>
CVPR 2025.  / [PDF](https://arxiv.org/abs/2411.18616)  / [Project](https://primecai.github.io/dsd/) / [Code](https://github.com/primecai/diffusion-self-distillation)

**DreamBlend: Advancing personalized fine-tuning of text-to-image diffusion models**<br>
*Ram, Shwetha and Neiman, Tal and Feng, Qianli and Stuart, Andrew and Tran, Son and Chilimbi, Trishul.*<br>
WACV 2025.  / [PDF](https://arxiv.org/abs/2411.19390v1)

**OminiControl: Minimal and Universal Control for Diffusion Transformer**<br>
*Tan, Zhenxiong and Liu, Songhua and Yang, Xingyi and Xue, Qiaochu and Wang, Xinchao.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2411.15098)  / [Code](https://github.com/Yuanshi9815/OminiControl)

**One Diffusion to Generate Them All**<br>
*Le, Duong H. and Pham, Tuan and Lee, Sangho and Clark, Christopher and Kembhavi, Aniruddha and Mandt, Stephan and Krishna, Ranjay and Lu, Jiasen.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2411.16318v1)  / [Project](https://lehduong.github.io/OneDiffusion-homepage/)  / [Code](https://github.com/lehduong/OneDiffusion)

**Qwen2VL-Flux: Unifying Image and Text Guidance for Controllable Image Generation**<br>
*Pengqi Lu*<br>
GitHub 2024.  / [PDF](https://github.com/erwold/qwen2vl-flux/blob/main/technical-report.pdf) / [Code](https://github.com/erwold/qwen2vl-flux)

**Cusconcept: Customized visual concept decomposition with diffusion models**<br>
*Xu, Zhi and Hao, Shaozhe and Han, Kai.*<br>
WACV 2025.  / [PDF](https://arxiv.org/abs/2410.00398)  / [Code](https://github.com/xzLcan/CusConcept)

**DisEnvisioner: Disentangled and Enriched Visual Prompt for Customized Image Generation**<br>
*He, Jing and Li, Haodong and Hu, Yongzhe and Shen, Guibao and Cai, Yingjie and Qiu, Weichao and Chen, Ying-Cong.*<br>
ICLR 2025.  / [PDF](https://arxiv.org/abs/2410.02067)  / [Project](https://disenvisioner.github.io/)  / [Code](https://github.com/EnVision-Research/DisEnvisioner)

**HybridBooth: Hybrid Prompt Inversion for Efficient Subject-Driven Generation**<br>
*Guan, Shanyan and Ge, Yanhao and Tai, Ying and Yang, Jian and Li, Wei and You, Mingyu.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2410.08192v1)  / [Project](https://sites.google.com/view/hybridbooth)

**Learning to Customize Text-to-Image Diffusion In Diverse Context**<br>
*Kim, Taewook and Chen, Wei and Qiu, Qiang.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2410.10058)

**ArtiFade: Learning to Generate High-quality Subject from Blemished Images**<br>
*Yang, Shuya and Hao, Shaozhe and Cao, Yukang and Wong, Kwan-Yee K.*<br>
CVPR 2025.  / [PDF](https://arxiv.org/abs/2409.03745) / [Project](https://wp2023.cs.hku.hk/fyp23045/)

**CustomContrast: A Multilevel Contrastive Perspective For Subject-Driven Text-to-Image Customization**<br>
*Chen, Nan and Huang, Mengqi and Chen, Zhuowei and Zheng, Yang and Zhang, Lei and Mao, Zhendong.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2409.05606)  / [Project](https://cn-makers.github.io/CustomContrast/)

**EZIGen: Enhancing zero-shot subject-driven image generation with precise subject encoding and decoupled guidance**<br>
*Duan, Zicheng and Ding, Yuxuan and Gou, Chenhui and Zhou, Ziqin and Smith, Ethan and Liu, Lingqiao.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2409.08091)  / [Project](https://zichengduan.github.io/pages/EZIGen/index.html)  / [Code](https://github.com/ZichengDuan/EZIGen)

**TextBoost: Towards One-Shot Personalization of Text-to-Image Models via Fine-tuning Text Encoder**<br>
*Park, NaHyeon and Kim, Kunhee and Shim, Hyunjung.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2409.08248)  / [Project](https://textboost.github.io/)  / [Code](https://github.com/nahyeonkaty/textboost)

**OmniGen: Unified image generation**<br>
*Xiao, Shitao and Wang, Yueze and Zhou, Junjie and Yuan, Huaying and Xing, Xingrun and Yan, Ruiran and Wang, Shuting and Huang, Tiejun and Liu, Zheng.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2409.11340)  / [Project](https://vectorspacelab.github.io/OmniGen/)  / [Code](https://github.com/VectorSpaceLab/OmniGen)

**Equilibrated Diffusion: Frequency-aware Textual Embedding for EquilibratedImage Customization**<br>
*Liyuan Ma, Xueji Fang, Guo-Jun Qi*<br>
ACM MM 2024 Oral. / [PDF](https://openreview.net/pdf?id=ERuypCHYvX) / [Project](https://maple-aigc.github.io/EqDiff/) / [Code](https://github.com/maple-research-lab/EqDiff)

**IPAdapter-Instruct: Resolving Ambiguity in Image-based Conditioning using Instruct Prompts**<br>
*Rowles, Ciara and Vainer, Shimon and De Nigris, Dante and Elizarov, Slava and Kutsy, Konstantin and Donné, Simon.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2408.03209)  / [Project](https://unity-research.github.io/IP-Adapter-Instruct.github.io/)  / [Code](https://github.com/unity-research/IP-Adapter-Instruct)

**BRAT: Bonus oRthogonAl Token for Architecture Agnostic Textual Inversion**<br>
*Baker, James.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2408.04785)  / [Code](https://github.com/jamesBaker361/tex_inv_plus)

**RealCustom++: Representing Images as Real-Word for Real-Time Customization**<br>
*Mao, Zhendong and Huang, Mengqi and Ding, Fei and Liu, Mingcong and He, Qian and Chang, Xiaojun and Zhang, Yongdong.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2408.09744)

**CoRe: Context-Regularized Text Embedding Learning for Text-to-Image Personalization**<br>
*Wu, Feize and Pang, Yun and Zhang, Junyi and Pang, Lianyu and Yin, Jian and Zhao, Baoquan and Li, Qing and Mao, Xudong.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2408.15914)

**Dreambench++: A human-aligned benchmark for personalized image generation**<br>
*Peng, Yuang and Cui, Yuxin and Tang, Haomiao and Qi, Zekun and Dong, Runpei and Bai, Jing and Han, Chunrui and Ge, Zheng and Zhang, Xiangyu and Xia, Shu-Tao.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2406.16855)  / [Project](https://dreambenchplus.github.io/)  / [Code](https://github.com/yuangpeng/dreambench_plus)

**JeDi: Joint-Image Diffusion Models for Finetuning-Free Personalized Text-to-Image Generation**<br>
*Zeng, Yu and Patel, Vishal M and Wang, Haochen and Huang, Xun and Wang, Ting-Chun and Liu, Ming-Yu and Balaji, Yogesh.*<br>
CVPR 2024.  / [PDF](https://openaccess.thecvf.com/content/CVPR2024/html/Zeng_JeDi_Joint-Image_Diffusion_Models_for_Finetuning-Free_Personalized_Text-to-Image_Generation_CVPR_2024_paper.html)

**Improving Subject-Driven Image Synthesis with Subject-Agnostic Guidance**<br>
*Chan, Kelvin CK and Zhao, Yang and Jia, Xuhui and Yang, Ming-Hsuan and Wang, Huisheng.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2405.01356)

**Non-confusing Generation of Customized Concepts in Diffusion Models**<br>
*Lin, Wang and Chen, Jingyuan and Shi, Jiaxin and Zhu, Yichen and Liang, Chen and Miao, Junzhong and Jin, Tao and Zhao, Zhou and Wu, Fei and Yan, Shuicheng and {others}.*<br>
ICML 2024.  / [PDF](https://arxiv.org/abs/2405.06914)  / [Project](https://clif-official.github.io/clif/)  / [Code](https://github.com/clif-official/clif_code)

**FreeTuner: Any Subject in Any Style with Training-free Diffusion**<br>
*Xu, Youcan and Wang, Zhen and Xiao, Jun and Liu, Wei and Chen, Long.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2405.14201)

**Personalized Residuals for Concept-Driven Text-to-Image Generation**<br>
*Ham, Cusuh and Fisher, Matthew and Hays, James and Kolkin, Nicholas and Liu, Yuchen and Zhang, Richard and Hinz, Tobias.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2405.12978v1)  / [Project](https://cusuh.github.io/personalized-residuals/)

**Moma: Multimodal llm adapter for fast personalized image generation**<br>
*Song, Kunpeng and Zhu, Yizhe and Liu, Bingchen and Yan, Qing and Elgammal, Ahmed and Yang, Xiao.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2404.05674v1)  / [Project](https://moma-adapter.github.io/)  / [Code](https://github.com/bytedance/MoMA)

**Moa: Mixture-of-attention for subject-context disentanglement in personalized image generation**<br>
*Wang, Kuan-Chieh and Ostashev, Daniil and Fang, Yuwei and Tulyakov, Sergey and Aberman, Kfir.*<br>
SIGGRAPH Asia 2024.  / [PDF](https://arxiv.org/abs/2404.11565v2)  / [Project](https://snap-research.github.io/mixture-of-attention/)

**FaceChain-SuDe: Building Derived Class to Inherit Category Attributes for One-shot Subject-Driven Generation**<br>
*Qiao, Pengchong and Shang, Lei and Liu, Chang and Sun, Baigui and Ji, Xiangyang and Chen, Jie.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2403.06775v1)  / [Project](https://facechain-fact.github.io)  / [Code](https://github.com/modelscope/facechain)

**Tuning-free image customization with image and text guidance**<br>
*Li, Pengzhi and Nie, Qiang and Chen, Ying and Jiang, Xi and Wu, Kai and Lin, Yuhuan and Liu, Yong and Peng, Jinlong and Wang, Chengjie and Zheng, Feng.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2403.12658v1)

**Harmonizing Visual and Textual Embeddings for Zero-Shot Text-to-Image Customization**<br>
*Song, Yeji and Kim, Jimyeong and Park, Wonhark and Shin, Wonsik and Rhee, Wonjong and Kwak, Nojun.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2403.14155)  / [Project](https://ldynx.github.io/harmony-zero-t2i/)  / [Code](https://github.com/ldynx/harmony-zero-t2i)

**Automated Black-box Prompt Engineering for Personalized Text-to-Image Generation**<br>
*He, Yutong and Robey, Alexander and Murata, Naoki and Jiang, Yiding and Williams, Joshua and Pappas, George J and Hassani, Hamed and Mitsufuji, Yuki and Salakhutdinov, Ruslan and Kolter, J Zico.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2403.19103)

**Locate, Assign, Refine: Taming Customized Image Inpainting with Text-Subject Guidance**<br>
*Pan, Yulin and Mao, Chaojie and Jiang, Zeyinzi and Han, Zhen and Zhang, Jingfeng.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2403.19534)  / [Project](https://ali-vilab.github.io/largen-page/)  / [Code](https://github.com/modelscope/scepter)

**RealCustom: Narrowing Real Text Word for Real-Time Open-Domain Text-to-Image Customization**<br>
*Huang, Mengqi and Mao, Zhendong and Liu, Mingcong and He, Qian and Zhang, Yongdong.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2403.00483v1)  / [Project](https://github.com/Corleone-Huang/RealCustomProject)  / [Code](https://corleone-huang.github.io/realcustom/)

**Dreammatcher: Appearance matching self-attention for semantically-consistent text-to-image personalization**<br>
*Nam, Jisu and Kim, Heesu and Lee, DongJae and Jin, Siyoon and Kim, Seungryong and Chang, Seunggyu.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2402.09812v2)  / [Project](https://cvlab-kaist.github.io/DreamMatcher/)  / [Code](https://github.com/cvlab-kaist/DreamMatcher)

**ComFusion: Personalized Subject Generation in Multiple Specific Scenes From Single Image**<br>
*Hong, Yan and Zhang, Jianfu.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2402.11849)

**Direct consistency optimization for compositional text-to-image personalization**<br>
*Lee, Kyungmin and Kwak, Sangkyung and Sohn, Kihyuk and Shin, Jinwoo.*<br>
NeurIPS 2024.  / [PDF](https://arxiv.org/abs/2402.12004)  / [Project](https://dco-t2i.github.io/)  / [Code](https://github.com/kyungmnlee/dco)

**Instruct-Imagen: Image generation with multi-modal instruction**<br>
*Hu, Hexiang and Chan, Kelvin CK and Su, Yu-Chuan and Chen, Wenhu and Li, Yandong and Sohn, Kihyuk and Zhao, Yang and Ben, Xue and Gong, Boqing and Cohen, William and Chang, Ming-Wei and Jia, Xuhui.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2401.01952)

**Memory-Efficient Personalization using Quantized Diffusion Model**<br>
*Ryu, Hyogon and Lim, Seohyun and Shim, Hyunjung.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2401.04339)  / [Code](https://github.com/ugonfor/TuneQDM)

**PALP: prompt aligned personalization of text-to-image models**<br>
*Arar, Moab and Voynov, Andrey and Hertz, Amir and Avrahami, Omri and Fruchter, Shlomi and Pritch, Yael and Cohen-Or, Daniel and Shamir, Ariel.*<br>
SIGGRAPH Asia 2024.  / [PDF](https://arxiv.org/abs/2401.06105v1)  / [Project](https://prompt-aligned.github.io/)

**UNIMO-G: Unified Image Generation through Multimodal Conditional Diffusion**<br>
*Li, Wei and Xu, Xue and Liu, Jiachen and Xiao, Xinyan.*<br>
ACL 2024.  / [PDF](https://arxiv.org/abs/2401.13388)  / [Project](https://unimo-ptm.github.io/)

**Bootpig: Bootstrapping zero-shot personalized image generation capabilities in pretrained diffusion models**<br>
*Purushwalkam, Senthil and Gokul, Akash and Joty, Shafiq and Naik, Nikhil.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2401.13974)

**Object-Driven One-Shot Fine-tuning of Text-to-Image Diffusion with Prototypical Embedding**<br>
*Lu, Jianxiang and Xie, Cong and Guo, Hui.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2401.15708)

**Pick-and-draw: Training-free semantic guidance for text-to-image personalization**<br>
*Lv, Henglei and Xiao, Jiayu and Li, Liang and Huang, Qingming.*<br>
ACM MM 2024.  / [PDF](https://arxiv.org/abs/2401.16762)

**Decoupled textual embeddings for customized image generation**<br>
*Cai, Yufei and Wei, Yuxiang and Ji, Zhilong and Bai, Jinfeng and Han, Hu and Zuo, Wangmeng.*<br>
AAAI 2024.  / [PDF](https://arxiv.org/abs/2312.11826v1)  / [Code](https://github.com/PrototypeNx/DETEX)

**Retrieving conditions from reference images for diffusion models**<br>
*Tang, Haoran and Zhou, Xin and Deng, Jieren and Pan, Zhihong and Tian, Hao and Chaudhari, Pratik.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2312.02521)

**Instructbooth: Instruction-following personalized text-to-image generation**<br>
*Chae, Daewon and Park, Nokyung and Kim, Jinkyu and Lee, Kimin.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2312.03011)  / [Project](https://sites.google.com/view/instructbooth)

**Orthogonal adaptation for modular customization of diffusion models**<br>
*Po, Ryan and Yang, Guandao and Aberman, Kfir and Wetzstein, Gordon.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2312.02432v3)  / [Project](https://ryanpo.com/ortha/)

**Customization assistant for text-to-image generation**<br>
*Zhou, Yufan and Zhang, Ruiyi and Gu, Jiuxiang and Sun, Tong.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2312.03045v2)

**Dreamtuner: Single image is enough for subject-driven generation**<br>
*Hua, Miao and Liu, Jiawei and Ding, Fei and Liu, Wei and Wu, Jie and He, Qian.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2312.13691)  / [Project](https://dreamtuner-diffusion.github.io/)

**Ssr-encoder: Encoding selective subject representation for subject-driven generation**<br>
*Zhang, Yuxuan and Song, Yiren and Liu, Jiaming and Wang, Rui and Yu, Jinpeng and Tang, Hao and Li, Huaxia and Tang, Xu and Hu, Yao and Pan, Han and {others}.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2312.16272)  / [Project](https://ssr-encoder.github.io/)  / [Code](https://github.com/Xiaojiu-z/SSR_Encoder)

**Towards accurate guided diffusion sampling through symplectic adjoint method**<br>
*Pan, Jiachun and Yan, Hanshu and Liew, Jun Hao and Feng, Jiashi and Tan, Vincent YF.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2312.12030)  / [Code](https://github.com/HanshuYAN/AdjointDPM)

**Catversion: Concatenating embeddings for diffusion-based text-to-image personalization**<br>
*Zhao, Ruoyu and Zhu, Mingrui and Dong, Shiyin and Wang, Nannan and Gao, Xinbo.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2311.14631)  / [Project](https://royzhao926.github.io/CatVersion-page)  / [Code](https://github.com/RoyZhao926/CatVersion)

**Parameter-efficient orthogonal finetuning via butterfly factorization**<br>
*Liu, Weiyang and Qiu, Zeju and Feng, Yao and Xiu, Yuliang and Xue, Yuxuan and Yu, Longhui and Feng, Haiwen and Liu, Zhen and Heo, Juyeon and Peng, Songyou and {others}.*<br>
ICLR 2024.  / [PDF](https://arxiv.org/abs/2311.06243)

**An image is worth multiple words: Multi-attribute inversion for constrained text-to-image synthesis**<br>
*Agarwal, Aishwarya and Karanam, Srikrishna and Shukla, Tripti and Srinivasan, Balaji Vasan.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2311.11919)

**Hifi tuner: High-fidelity subject-driven fine-tuning for diffusion models**<br>
*Wang, Zhonghao and Wei, Wei and Zhao, Yang and Xiao, Zhisheng and Hasegawa-Johnson, Mark and Shi, Humphrey and Hou, Tingbo.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2312.00079)

**Singleinsert: Inserting new concepts from a single image into text-to-image models for flexible editing**<br>
*Wu, Zijie and Yu, Chaohui and Zhu, Zhen and Wang, Fan and Bai, Xiang.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2310.08094)  / [Project](https://jarrentwu1031.github.io/SingleInsert-web)  / [Code](https://github.com/JarrentWu1031/SingleInsert)

**An image is worth multiple words: Learning object level concepts using multi-concept prompt learning**<br>
*Jin, Chen and Tanno, Ryutaro and Saseendran, Amrutha and Diethe, Tom and Teare, Philip.*<br>
ICML 2024.  / [PDF](https://arxiv.org/abs/2310.12274)  / [Project](https://astrazeneca.github.io/mcpl.github.io/)  / [Code](https://github.com/AstraZeneca/MCPL/tree/master)

**Customnet: Zero-shot object customization with variable-viewpoints in text-to-image diffusion models**<br>
*Yuan, Ziyang and Cao, Mingdeng and Wang, Xintao and Qi, Zhongang and Yuan, Chun and Shan, Ying.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2310.19784)  / [Project](https://jiangyzy.github.io/CustomNet/)

**Viewpoint textual inversion: Unleashing novel view synthesis with pretrained 2d diffusion models**<br>
*Burgess, James and Wang, Kuan-Chieh and Yeung, Serena.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2309.07986)  / [Project](https://jmhb0.github.io/view_neti/)  / [Code](https://github.com/jmhb0/view_neti)

**Ip-adapter: Text compatible image prompt adapter for text-to-image diffusion models**<br>
*Ye, Hu and Zhang, Jun and Liu, Sibo and Han, Xiao and Yang, Wei.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2308.06721)  / [Project](https://ip-adapter.github.io/)  / [Code](https://github.com/tencent-ailab/IP-Adapter)

**Anydoor: Zero-shot object-level image customization**<br>
*Chen, Xi and Huang, Lianghua and Liu, Yu and Shen, Yujun and Zhao, Deli and Zhao, Hengshuang.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2307.09481v2)  / [Project](https://ali-vilab.github.io/AnyDoor-Page/)  / [Code](https://github.com/ali-vilab/AnyDoor)

**Subject-diffusion: Open domain personalized text-to-image generation without test-time fine-tuning**<br>
*Ma, Jian and Liang, Junhao and Chen, Chen and Lu, Haonan.*<br>
SIGGRAPH 2024.  / [PDF](https://arxiv.org/abs/2307.11410)  / [Project](https://oppo-mente-lab.github.io/subject_diffusion/)  / [Code](https://github.com/OPPO-Mente-Lab/Subject-Diffusion)

**Domain-agnostic tuning-encoder for fast personalization of text-to-image models**<br>
*Arar, Moab and Gal, Rinon and Atzmon, Yuval and Chechik, Gal and Cohen-Or, Daniel and Shamir, Ariel and H. Bermano, Amit.*<br>
SIGGRAPH Asia 2023.  / [PDF](https://arxiv.org/abs/2307.06925v1)  / [Project](https://datencoder.github.io/)

**ViCo: Plug-and-play Visual Condition for Personalized Text-to-image Generation**<br>
*Hao, Shaozhe and Han, Kai and Zhao, Shihao and Wong, Kwan-Yee K.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2306.00971)  / [Code](https://github.com/haoosz/ViCo)

**Diffusion self-guidance for controllable image generation**<br>
*Epstein, Dave and Jabri, Allan and Poole, Ben and Efros, Alexei and Holynski, Aleksander.*<br>
NeurIPS 2023.  / [PDF](https://arxiv.org/abs/2306.00986)  / [Project](https://dave.ml/selfguidance/)

**Controlling text-to-image diffusion by orthogonal finetuning**<br>
*Qiu, Zeju and Liu, Weiyang and Feng, Haiwen and Xue, Yuxuan and Feng, Yao and Liu, Zhen and Zhang, Dan and Weller, Adrian and Schölkopf, Bernhard.*<br>
NeurIPS 2023.  / [PDF](https://arxiv.org/abs/2306.07280)  / [Project](https://oft.wyliu.com/)  / [Code](https://github.com/Zeju1997/oft)

**Enhancing detail preservation for customized text-to-image generation: A regularization-free approach**<br>
*Zhou, Yufan and Zhang, Ruiyi and Sun, Tong and Xu, Jinhui.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2305.13579)  / [Code](https://github.com/drboog/ProFusion)

**Disenbooth: Disentangled parameter-efficient tuning for subject-driven text-to-image generation**<br>
*Chen, Hong and Zhang, Yipeng and Wang, Xin and Duan, Xuguang and Zhou, Yuwei and Zhu, Wenwu.*<br>
ICLR 2024.  / [PDF](https://arxiv.org/abs/2305.03374)  / [Code](https://github.com/forchchch/DisenBooth)

**Break-a-scene: Extracting multiple concepts from a single image**<br>
*Avrahami, Omri and Aberman, Kfir and Fried, Ohad and Cohen-Or, Daniel and Lischinski, Dani.*<br>
SIGGRAPH Asia 2023.  / [PDF](https://arxiv.org/abs/2305.16311v2)  / [Project](https://omriavrahami.com/break-a-scene/)  / [Code](https://github.com/google/break-a-scene)

**Blip-diffusion: Pre-trained subject representation for controllable text-to-image generation and editing**<br>
*Li, Dongxu and Li, Junnan and Hoi, Steven.*<br>
NeurIPS 2023.  / [PDF](https://arxiv.org/abs/2305.14720)  / [Project](https://dxli94.github.io/BLIP-Diffusion-website/)  / [Code](https://github.com/salesforce/LAVIS/tree/main/projects/blip-diffusion)

**Key-locked rank one editing for text-to-image personalization**<br>
*Tewel, Yoad and Gal, Rinon and Chechik, Gal and Atzmon, Yuval.*<br>
SIGGRAPH 2023.  / [PDF](https://arxiv.org/abs/2305.01644v2)  / [Project](https://research.nvidia.com/labs/par/Perfusion/)

**A neural space-time representation for text-to-image personalization**<br>
*Alaluf, Yuval and Richardson, Elad and Metzer, Gal and Cohen-Or, Daniel.*<br>
ACM TOG 2023.  / [PDF](https://arxiv.org/abs/2305.15391v1)  / [Project](https://neuraltextualinversion.github.io/NeTI/)  / [Code](https://github.com/NeuralTextualInversion/NeTI)

**Concept decomposition for visual exploration and inspiration**<br>
*Vinker, Yael and Voynov, Andrey and Cohen-Or, Daniel and Shamir, Ariel.*<br>
ACM TOG 2023.  / [PDF](https://arxiv.org/abs/2305.18203v2)  / [Project](https://inspirationtree.github.io/inspirationtree/)  / [Code](https://github.com/google/inspiration_tree)

**Prospect: Prompt spectrum for attribute-aware personalization of diffusion models**<br>
*Zhang, Yuxin and Dong, Weiming and Tang, Fan and Huang, Nisha and Huang, Haibin and Ma, Chongyang and Lee, Tong-Yee and Deussen, Oliver and Xu, Changsheng.*<br>
ACM TOG 2023.  / [PDF](https://arxiv.org/abs/2305.16225v3)  / [Code](https://github.com/zyxElsa/ProSpect)

**The CLIP model is secretly an image-to-prompt converter**<br>
*Ding, Yuxuan and Tian, Chunna and Ding, Haoxuan and Liu, Lingqiao.*<br>
NeurIPS 2023.  / [PDF](https://arxiv.org/abs/2305.12716v2)

**Instantbooth: Personalized text-to-image generation without test-time finetuning**<br>
*Shi, Jing and Xiong, Wei and Lin, Zhe and Jung, Hyun Joon.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2304.03411v1)  / [Project](https://jshi31.github.io/InstantBooth)

**Subject-driven text-to-image generation via apprenticeship learning**<br>
*Chen, Wenhu and Hu, Hexiang and Li, Yandong and Ruiz, Nataniel and Jia, Xuhui and Chang, Ming-Wei and Cohen, William W.*<br>
NeurIPS 2023.  / [PDF](https://arxiv.org/abs/2304.00186)  / [Project](https://cloud.google.com/vertex-ai/docs/generative-ai/image/fine-tune-model)

**Taming encoder for zero fine-tuning image customization with text-to-image diffusion models**<br>
*Jia, Xuhui and Zhao, Yang and Chan, Kelvin CK and Li, Yandong and Zhang, Han and Gong, Boqing and Hou, Tingbo and Wang, Huisheng and Su, Yu-Chuan.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2304.02642)

**Gradient-free textual inversion**<br>
*Fei, Zhengcong and Fan, Mingyuan and Huang, Junshi.*<br>
ACM MM 2023.  / [PDF](https://arxiv.org/abs/2304.05818v1)

**p+: Extended textual conditioning in text-to-image generation**<br>
*Voynov, Andrey and Chu, Qinghao and Cohen-Or, Daniel and Aberman, Kfir.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2303.09522)  / [Project](https://prompt-plus.github.io)

**Cones: Concept neurons in diffusion models for customized generation**<br>
*Liu, Zhiheng and Feng, Ruili and Zhu, Kai and Zhang, Yifei and Zheng, Kecheng and Liu, Yu and Zhao, Deli and Zhou, Jingren and Cao, Yang.*<br>
ICML 2023.  / [PDF](https://arxiv.org/abs/2303.05125)

**Svdiff: Compact parameter space for diffusion fine-tuning**<br>
*Han, Ligong and Li, Yinxiao and Zhang, Han and Milanfar, Peyman and Metaxas, Dimitris and Yang, Feng.*<br>
ICCV 2023.  / [PDF](https://arxiv.org/abs/2303.11305)

**Highly personalized text embedding for image manipulation by stable diffusion**<br>
*Han, Inhwa and Yang, Serin and Kwon, Taesung and Ye, Jong Chul.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2303.08767)  / [Project](https://hiper0.github.io/)  / [Code](https://github.com/HiPer0/HiPer)

**Unified multi-modal latent diffusion for joint subject and text conditional image generation**<br>
*Ma, Yiyang and Yang, Huan and Wang, Wenjing and Fu, Jianlong and Liu, Jiaying.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2303.09319)

**Elite: Encoding visual concepts into textual embeddings for customized text-to-image generation**<br>
*Wei, Yuxiang and Zhang, Yabo and Ji, Zhilong and Bai, Jinfeng and Zhang, Lei and Zuo, Wangmeng.*<br>
ICCV 2023.  / [PDF](https://arxiv.org/abs/2302.13848v2)  / [Code](https://github.com/csyxwei/ELITE)

**Encoder-based domain tuning for fast personalization of text-to-image models**<br>
*Gal, Rinon and Arar, Moab and Atzmon, Yuval and Bermano, Amit H and Chechik, Gal and Cohen-Or, Daniel.*<br>
ACM TOG 2023.  / [PDF](https://arxiv.org/abs/2302.12228)  / [Project](https://tuning-encoder.github.io/)

**Multi-concept customization of text-to-image diffusion**<br>
*Kumari, Nupur and Zhang, Bingliang and Zhang, Richard and Shechtman, Eli and Zhu, Jun-Yan.*<br>
CVPR 2023.  / [PDF](https://arxiv.org/abs/2212.04488v2)  / [Project](https://www.cs.cmu.edu/~custom-diffusion)  / [Code](https://github.com/adobe-research/custom-diffusion)

**Dreamartist: Towards controllable one-shot text-to-image generation via positive-negative prompt-tuning**<br>
*Dong, Ziyi and Wei, Pengxu and Lin, Liang.*<br>
Arxiv 2022.  / [PDF](https://arxiv.org/abs/2211.11337)

**Personalizing text-to-image generation via aesthetic gradients**<br>
*Gallego, Victor.*<br>
Arxiv 2022.  / [PDF](https://arxiv.org/abs/2209.12330)  / [Code](https://github.com/vicgalle/stable-diffusion-aesthetic-gradients)

**Re-imagen: Retrieval-augmented text-to-image generator**<br>
*Chen, Wenhu and Hu, Hexiang and Saharia, Chitwan and Cohen, William W.*<br>
ICLR 2023.  / [PDF](https://arxiv.org/abs/2209.14491)

**An image is worth one word: Personalizing text-to-image generation using textual inversion**<br>
*Gal, Rinon and Alaluf, Yuval and Atzmon, Yuval and Patashnik, Or and Bermano, Amit H and Chechik, Gal and Cohen-Or, Daniel.*<br>
ICLR 2023.  / [PDF](https://arxiv.org/abs/2208.01618)  / [Project](https://textual-inversion.github.io/)  / [Code](https://github.com/rinongal/textual_inversion)

**Dreambooth: Fine tuning text-to-image diffusion models for subject-driven generation**<br>
*Ruiz, Nataniel and Li, Yuanzhen and Jampani, Varun and Pritch, Yael and Rubinstein, Michael and Aberman, Kfir.*<br>
CVPR 2023.  / [PDF](https://arxiv.org/abs/2208.12242v2)  / [Project](https://dreambooth.github.io)  / [Code](https://github.com/google/dreambooth)

**Lora: Low-rank adaptation of large language models**<br>
*Hu, Edward J and Shen, Yelong and Wallis, Phillip and Allen-Zhu, Zeyuan and Li, Yuanzhi and Wang, Shean and Wang, Lu and Chen, Weizhu.*<br>
ICLR 2022.  / [PDF](https://arxiv.org/abs/2106.09685)  / [Code](https://github.com/microsoft/LoRA)

### Face-Driven Generation

**Training for Identity, Inference for Controllability: A Unified Approach to Tuning-Free Face Personalization**<br>
*Lianyu Pang, Ji Zhou, Qiping Wang, Baoquan Zhao, Zhenguo Yang, Qing Li, Xudong Mao*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2512.03964) / [Code](https://github.com/lyuPang/UniID)

**Ar2Can: An Architect and an Artist Leveraging a Canvas for Multi-Human Generation**<br>
*Shubhankar Borse, Phuc Pham, Farzad Farhadzadeh, Seokeon Choi, Phong Ha Nguyen, Anh Tuan Tran, Sungrack Yun, Munawar Hayat, Fatih Porikli*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2511.22690)

**A Training-Free Approach for Multi-ID Customization via Attention Adjustment and Spatial Control**<br>
*Jiawei Lin, Guanlong Jiao, Jianjin Xu*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2511.20401)

**BeyondFacial: Identity-Preserving Personalized Generation Beyond Facial Close-ups**<br>
*Songsong Zhang, Chuanqi Tang, Hongguang Zhang, Guijian Tang, Minglong Li, Xueqiong Li, Shaowu Yang, Yuanxi Peng, Wenjing Yang, Jing Zhao*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2511.11989)

**Finetuning-Free Personalization of Text to Image Generation via Hypernetworks**<br>
*Sagar Shrestha, Gopal Sharma, Luowei Zhou, Suren Kumar*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2511.03156)

**PSTF-AttControl: Per-Subject-Tuning-Free Personalized Image Generation with Controllable Face Attributes**<br>
*Xiang liu, Zhaoxiang Liu, Huan Hu, Zipeng Wang, Ping Chen, Zezhou Chen, Kai Wang, Shiguo Lian*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2510.25084) / [Code](https://github.com/UnicomAI/PSTF-AttControl)

**FreeFuse: Multi-Subject LoRA Fusion via Auto Masking at Test Time**<br>
*Yaoli Liu, Yao-Xiang Ding, Kun Zhou*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2510.23515) / [Project](https://future-item.github.io/FreeFuse/)

**Identity-GRPO: Optimizing Multi-Human Identity-preserving Video Generation via Reinforcement Learning**<br>
*Xiangyu Meng, Zixian Zhang, Zhenghao Zhang, Junchao Liao, Long Qin, Weizhi Wang*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2510.14256) / [Project](https://ali-videoai.github.io/identity_page/) / [Code](https://github.com/alibaba/identity-grpo)

**WithAnyone: Towards Controllable and ID Consistent Image Generation**<br>
*Hengyuan Xu, Wei Cheng, Peng Xing, Yixiao Fang, Shuhan Wu, Rui Wang, Xianfang Zeng, Daxin Jiang, Gang Yu, Xingjun Ma, Yu-Gang Jiang*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2510.14975) / [Project](https://doby-xu.github.io/WithAnyone/) / [Code](https://github.com/Doby-Xu/WithAnyone)

**UMO: Scaling Multi-Identity Consistency for Image Customization via Matching Reward**<br>
*Yufeng Cheng, Wenxu Wu, Shaojin Wu, Mengqi Huang, Fei Ding, Qian He*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2509.06818) / [Project](https://bytedance.github.io/UMO/) / [Code](https://github.com/bytedance/UMO)

**EditIDv2: Editable ID Customization with Data-Lubricated ID Feature Integration for Text-to-Image Generation**<br>
*Guandong Li, Zhaobin Chu*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2509.05659)

**CraftGraffiti: Exploring Human Identity with Custom Graffiti Art via Facial-Preserving Diffusion Models**<br>
*Ayan Banerjee, Fernando Vilariño, Josep Lladós*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2508.20640) / [Code](https://github.com/ayanban011/CraftGraffiti)

**ID-EA: Identity-driven Text Enhancement and Adaptation with Textual Inversion for Personalized Text-to-Image Generation**<br>
*Hyun-Jun Jin, Young-Eun Kim, Seong-Whan Lee*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2507.11990)

**Imagine for Me: Creative Conceptual Blending of Real Images and Text via Blended Attention**<br>
*Wonwoong Cho, Yanxia Zhang, Yan-Ying Chen, David I. Inouye*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2506.24085) / [Project](https://imagineforme.github.io/) / [Code](https://github.com/WonwoongCho/IT-Blender)

**FastFace: Tuning Identity Preservation in Distilled Diffusion via Guidance and Attention**<br>
*Sergey Karpukhin, Vadim Titov, Andrey Kuznetsov, Aibek Alanov*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2505.21144) / [Code](https://github.com/ControlGenAI/FastFace)

**Identity-Preserving Text-to-Video Generation by Frequency Decomposition**<br>
*Shenghai Yuan, Jinfa Huang, Xianyi He, Yunyuan Ge, Yujun Shi, Liuhan Chen, Jiebo Luo, Li Yuan*<br>
CVPR 2025 (Highlight).  /  [PDF](https://arxiv.org/abs/2411.17440) / [Project](https://pku-yuangroup.github.io/ConsisID/) / [Code](https://github.com/PKU-YuanGroup/ConsisID)

**PIDiff: Image Customization for Personalized Identities with Diffusion Models**<br>
*Jinyu Gu, Haipeng Liu, Meng Wang, Yang Wang*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2505.05081)

**DreamID: High-Fidelity and Fast diffusion-based Face Swapping via Triplet ID Group Learning**<br>
*Fulong Ye, Miao Hua, Pengze Zhang, Xinghui Li, Qichao Sun, Songtao Zhao, Qian He, Xinglong Wu*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2504.14509) / [Project](https://superhero-7.github.io/DreamID/) / [Code](https://github.com/superhero-7/DreamID)

**Learning Joint ID-Textual Representation for ID-Preserving Image Synthesis**<br>
*Zichuan Liu, Liming Jiang, Qing Yan, Yumin Jia, Hao Kang, Xin Lu*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2504.14202) 

**ID-Booth: Identity-consistent Face Generation with Diffusion Models**<br>
*Darian Tomašević, Fadi Boutros, Chenhao Lin, Naser Damer, Vitomir Štruc, Peter Peer*<br>
FG 2025.  / [PDF](https://arxiv.org/abs/2504.07392) / [Code](https://github.com/dariant/ID-Booth)

**SPF-Portrait: Towards Pure Portrait Customization with Semantic Pollution-Free Fine-tuning**<br>
*Xiaole Xian, Zhichao Liao, Qingyu Li, Wenyu Qin, Pengfei Wan, Weicheng Xie, Long Zeng, Linlin Shen, Pingfa Feng*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2504.00396) / [Project](https://spf-portrait.github.io/SPF-Portrait/)

**Consistent Subject Generation via Contrastive Instantiated Concepts**<br>
*Lee Hsin-Ying, Kelvin C.K. Chan, Ming-Hsuan Yang*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2503.24387) / [Project](https://contrastive-concept-instantiation.github.io/) / [Code](https://github.com/contrastive-concept-instantiation/cocoins)

**Meta-LoRA: Meta-Learning LoRA Components for Domain-Aware ID Personalization**<br>
*Barış Batuhan Topal, Umut Özyurt, Zafer Doğan Budak, Ramazan Gokberk Cinbis*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2503.22352) 

**HyperLoRA: Parameter-Efficient Adaptive Generation for Portrait Synthesis**<br>
*Mengtian Li, Jinshu Chen, Wanquan Feng, Bingchuan Li, Fei Dai, Songtao Zhao, Qian He*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2503.16944)

**InfiniteYou: Flexible Photo Recrafting While Preserving Your Identity**<br>
*Liming Jiang, Qing Yan, Yumin Jia, Zichuan Liu, Hao Kang, Xin Lu*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2503.16418) / [Project](https://bytedance.github.io/InfiniteYou/) / [Code](https://github.com/bytedance/InfiniteYou)

**EditID: Training-Free Editable ID Customization for Text-to-Image Generation**<br>
*Guandong Li, Zhaobin Chu*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2503.12526) 

**FaceID-6M: A Large-Scale, Open-Source FaceID Customization Dataset**<br>
*Shuhe Wang, Xiaoya Li, Jiwei Li, Guoyin Wang, Xiaofei Sun, Bob Zhu, Han Qiu, Mo Yu, Shengjie Shen, Tianwei Zhang, Eduard Hovy*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2503.07091)  / [Code](https://github.com/ShuheSH/FaceID-6M)

**PersonaHOI: Effortlessly Improving Personalized Face with Human-Object Interaction Generation**<br>
*Hu, Xinting and Wang, Haoran and Lenssen, Jan Eric and Schiele, Bernt.*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2501.05823)  / [Code](https://github.com/JoyHuYY1412/PersonaHOI)

**IC-Portrait: In-Context Matching for View-Consistent Personalized Portrait**<br>
*Yang, Han and Simsar, Enis and Anagnostidis, Sotiris and Zang, Yanlong and Hofmann, Thomas and Liu, Ziwei.*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2501.17159)

**EmojiDiff: Advanced Facial Expression Control with High Identity Preservation in Portrait Generation**<br>
*Jiang, Liangwei and Li, Ruida and Zhang, Zhifeng and Fang, Shuo and Ma, Chenguang.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2412.01254)  / [Project](https://emojidiff.github.io/)

**Diff-PC: Identity-preserving and 3D-aware controllable diffusion for zero-shot portrait customization**<br>
*Xu, Yifang and Zhai, Benxiang and Zhang, Chenyu and Li, Ming and Li, Yang and Du, Sidan.*<br>
Information Fusion.  / [PDF](https://www.sciencedirect.com/science/article/pii/S156625352400647X)

**MagicNaming: Consistent Identity Generation by Finding a "Name Space" in T2I Diffusion Models**<br>
*Zhao, Jing and Zheng, Heliang and Wang, Chaoyue and Lan, Long and Hunag, Wanrong and Tang, Yuhua.*<br>
AAAI 2025.  / [PDF](https://arxiv.org/abs/2412.14902)  / [Project](https://magicfusion.github.io/MagicNaming/)  / [Code](https://github.com/MagicFusion/MagicNaming)

**PersonaMagic: Stage-Regulated High-Fidelity Face Customization with Tandem Equilibrium**<br>
*Li, Xinzhe and Zhan, Jiahui and He, Shengfeng and Xu, Yangyang and Dong, Junyu and Zhang, Huaidong and Du, Yong.*<br>
AAAI 2025.  / [PDF](https://arxiv.org/abs/2412.15674)  / [Code](https://github.com/xzhe-Vision/PersonaMagic)

**Omni-ID: Holistic Identity Representation Designed for Generative Tasks**<br>
*Qian, Guocheng and Wang, Kuan-Chieh and Patashnik, Or and Heravi, Negin and Ostashev, Daniil and Tulyakov, Sergey and Cohen-Or, Daniel and Aberman, Kfir.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2412.09694)  / [Project](https://snap-research.github.io/Omni-ID/)

**RealisID: Scale-Robust and Fine-Controllable Identity Customization via Local and Global Complementation**<br>
*Sun, Zhaoyang and Du, Fei and Chen, Weihua and Wang, Fan and Chen, Yaxiong and Rong, Yi and Xiong, Shengwu.*<br>
AAAI 2025.  / [PDF](https://arxiv.org/abs/2412.16832)

**Foundation Cures Personalization: Recovering Facial Personalized Models' Prompt Consistency**<br>
*Cai, Yiyang and Jiang, Zhengkai and Liu, Yulong and Jiang, Chunyang and Xue, Wei and Luo, Wenhan and Guo, Yike.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2411.15277)

**PersonaCraft: Personalized Full-Body Image Synthesis for Multiple Identities from Single References Using 3D-Model-Conditioned Diffusion**<br>
*Kim, Gwanghyun and Jeon, Suh Yoon and Lee, Seunggyu and Chun, Se Young.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2411.18068)  / [Project](https://gwang-kim.github.io/persona_craft/)  / [Code](https://github.com/gwang-kim/PersonaCraft)

**ID-Patch: Robust ID Association for Group Photo Personalization**<br>
*Zhang, Yimeng and Zhi, Tiancheng and Liu, Jing and Sang, Shen and Jiang, Liming and Yan, Qing and Liu, Sijia and Luo, Linjie.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2411.13632)  / [Project](https://byteaigc.github.io/ID-Patch/)

**FaceChain-FACT: Face Adapter with Decoupled Training for Identity-preserved Personalization**<br>
*Yu, Cheng and Xie, Haoyu and Shang, Lei and Liu, Yang and Dan, Jun and Bo, Liefeng and Sun, Baigui.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2410.12312)  / [Code](https://github.com/modelscope/facechain)

**Imagine yourself: Tuning-free personalized image generation**<br>
*He, Zecheng and Sun, Bo and Juefei-Xu, Felix and Ma, Haoyu and Ramchandani, Ankit and Cheung, Vincent and Shah, Siddharth and Kalia, Anmol and Subramanyam, Harihar and Zareian, Alireza and {others}.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2409.13346)

**Fusion is all you need: Face Fusion for Customized Identity-Preserving Image Synthesis**<br>
*Mohamed, Salaheldin and Han, Dong and Li, Yong.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2409.19111)

**ID-Booth: Identity-consistent image generation with diffusion models**<br>
*Tomašević, Darian and Boutros, Fadi and Damer, Naser and Struc, Vitomir and Peer, Peter.*<br>
OpenReview 2024.  / [PDF](https://openreview.net/forum?id=NWvsm2VxAM)

**UniPortrait: A Unified Framework for Identity-Preserving Single-and Multi-Human Image Personalization**<br>
*He, Junjie and Geng, Yifeng and Bo, Liefeng.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2408.05939)  / [Project](https://aigcdesigngroup.github.io/UniPortrait-Page/)  / [Code](https://github.com/junjiehe96/UniPortrait)

**Difflora: Generating personalized low-rank adaptation weights with diffusion**<br>
*Wu, Yujia and Shi, Yiming and Wei, Jiwei and Sun, Chengwei and Zhou, Yuyang and Yang, Yang and Shen, Heng Tao.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2408.06740)

**MagicFace: Training-free Universal-Style Human Image Customized Synthesis**<br>
*Wang, Yibin and Zhang, Weizhong and Jin, Cheng.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2408.07433)  / [Project](https://codegoat24.github.io/MagicFace/)  / [Code](https://github.com/CodeGoat24/MagicFace)

**MagicID: Flexible ID Fidelity Generation System**<br>
*Deng, Zhaoli and Liu, Wen and Wang, Fanyi and Zhang, Junkang and Chen, Fan and Zhang, Meng and Zhang, Wendong and Mi, Zhenpeng.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2408.09248)

**Precisecontrol: Enhancing text-to-image diffusion models with fine-grained attribute control**<br>
*Parihar, Rishubh and Sachidanand, VS and Mani, Sabariswaran and Karmali, Tejan and Venkatesh Babu, R.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2408.05083)  / [Project](https://rishubhpar.github.io/PreciseControl.home/)  / [Code](https://github.com/rishubhpar/PreciseControl)

**Cross Initialization for Face Personalization of Text-to-Image Models**<br>
*Pang, Lianyu and Yin, Jian and Xie, Haoran and Wang, Qiping and Li, Qing and Mao, Xudong.*<br>
CVPR 2024.  / [PDF](https://openaccess.thecvf.com/content/CVPR2024/html/Pang_Cross_Initialization_for_Face_Personalization_of_Text-to-Image_Models_CVPR_2024_paper.html)  / [Code](https://github.com/lyuPang/CrossInitialization)

**MasterWeaver: Taming Editability and Face Identity for Personalized Text-to-Image Generation**<br>
*Wei, Yuxiang and Ji, Zhilong and Bai, Jinfeng and Zhang, Hongzhi and Zhang, Lei and Zuo, Wangmeng.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2405.05806v3)  / [Project](https://masterweaver.github.io/)  / [Code](https://github.com/csyxwei/MasterWeaver)

**RectifID: Personalizing Rectified Flow with Anchored Classifier Guidance**<br>
*Sun, Zhicheng and Yang, Zhenhao and Jin, Yang and Chi, Haozhe and Xu, Kun and Chen, Liwei and Jiang, Hao and Song, Yang and Gai, Kun and Mu, Yadong.*<br>
NeurIPS 2024.  / [PDF](https://arxiv.org/abs/2405.14677)  / [Code](https://github.com/feifeiobama/RectifID)

**Pulid: Pure and lightning id customization via contrastive alignment**<br>
*Guo, Zinan and Wu, Yanze and Chen, Zhuowei and Chen, Lang and Zhang, Peng and He, Qian.*<br>
NeurIPS 2024.  / [PDF](https://arxiv.org/abs/2404.16022)  / [Code](https://github.com/ToTheBeginning/PuLID)

**Lcm-lookahead for encoder-based text-to-image personalization**<br>
*Gal, Rinon and Lichter, Or and Richardson, Elad and Patashnik, Or and Bermano, Amit H and Chechik, Gal and Cohen-Or, Daniel.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2404.03620)  / [Project](https://lcm-lookahead.github.io/)  / [Code](https://github.com/OrLichter/lcm-lookahead)

**ID-Aligner: Enhancing Identity-Preserving Text-to-Image Generation with Reward Feedback Learning**<br>
*Chen, Weifeng and Zhang, Jiacheng and Wu, Jie and Wu, Hefeng and Xiao, Xuefeng and Lin, Liang.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2404.15449)  / [Project](https://idaligner.github.io/)  / [Code](https://github.com/Weifeng-Chen/ID-Aligner)

**CharacterFactory: Sampling Consistent Characters with GANs for Diffusion Models**<br>
*Qinghe Wang, Baolu Li, Xiaomin Li, Bing Cao, Liqian Ma, Huchuan Lu, Xu Jia*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2404.15677)  / [Project](https://qinghew.github.io/CharacterFactory/)  / [Code](https://github.com/qinghew/CharacterFactory)

**Consistentid: Portrait generation with multimodal fine-grained identity preserving**<br>
*Huang, Jiehui and Dong, Xiao and Song, Wenhui and Li, Hanhui and Zhou, Jun and Cheng, Yuhao and Liao, Shutao and Chen, Long and Yan, Yiqiang and Liao, Shengcai and {others}.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2404.16771)  / [Project](https://ssugarwh.github.io/consistentid.github.io/)  / [Code](https://github.com/JackAILab/ConsistentID)

**Face2Diffusion for Fast and Editable Face Personalization**<br>
*Shiohara, Kaede and Yamasaki, Toshihiko.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2403.05094v1)  / [Project](https://mapooon.github.io/Face2DiffusionPage/)  / [Code](https://github.com/mapooon/Face2Diffusion)

**Infinite-ID: Identity-preserved Personalization via ID-semantics Decoupling Paradigm**<br>
*Wu, Yi and Li, Ziqiang and Zheng, Heliang and Wang, Chaoyue and Li, Bin.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2403.11781v1)  / [Project](https://infinite-id.github.io/)

**IDAdapter: Learning Mixed Features for Tuning-Free Personalization of Text-to-Image Models**<br>
*Cui, Siying and Guo, Jia and An, Xiang and Deng, Jiankang and Zhao, Yongle and Wei, Xinyu and Feng, Ziyong.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2403.13535v2)

**FlashFace: Human Image Personalization with High-fidelity Identity Preservation**<br>
*Zhang, Shilong and Huang, Lianghua and Chen, Xi and Zhang, Yifei and Wu, Zhi-Fan and Feng, Yutong and Wang, Wei and Shen, Yujun and Liu, Yu and Luo, Ping.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2403.17008)  / [Project](https://jshilong.github.io/flashface-page/)  / [Code](https://github.com/ali-vilab/FlashFace)

**Attention Calibration for Disentangled Text-to-Image Personalization**<br>
*Zhang, Yanbing and Yang, Mengping and Zhou, Qin and Wang, Zhe.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2403.18551v2)  / [Code](https://github.com/Monalissaa/DisenDiff)

**Caphuman: Capture your moments in parallel universes**<br>
*Liang, Chao and Ma, Fan and Zhu, Linchao and Deng, Yingying and Yang, Yi.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2402.00627v3)  / [Project](https://caphuman.github.io/)  / [Code](https://github.com/VamosC/CapHuman)

**Instantid: Zero-shot identity-preserving generation in seconds**<br>
*Wang, Qixun and Bai, Xu and Wang, Haofan and Qin, Zekui and Chen, Anthony and Li, Huaxia and Tang, Xu and Hu, Yao.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2401.07519)  / [Project](https://instantid.github.io/)  / [Code](https://github.com/instantX-research/InstantID)

**Towards a simultaneous and granular identity-expression control in personalized face generation**<br>
*Liu, Renshuai and Ma, Bowen and Zhang, Wei and Hu, Zhipeng and Fan, Changjie and Lv, Tangjie and Ding, Yu and Cheng, Xuan.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2401.01207v2)  / [Project](https://diffsfsr.github.io/)

**Stableidentity: Inserting anybody into anywhere at first sight**<br>
*Wang, Qinghe and Jia, Xu and Li, Xiaomin and Li, Taiqing and Ma, Liqian and Zhuge, Yunzhi and Lu, Huchuan.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2401.15975)  / [Project](https://qinghew.github.io/StableIdentity/)  / [Code](https://github.com/qinghew/StableIdentity)

**SeFi-IDE: Semantic-Fidelity Identity Embedding for Personalized Diffusion-Based Generation**<br>
*Li, Yang and Yang, Songlin and Wang, Wei and Dong, Jing.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2402.00631)  / [Project](https://com-vis.github.io/SeFi-IDE/)

**Photomaker: Customizing realistic human photos via stacked id embedding**<br>
*Li, Zhen and Cao, Mingdeng and Wang, Xintao and Qi, Zhongang and Cheng, Ming-Ming and Shan, Ying.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2312.04461v1)  / [Project](https://photo-maker.github.io)  / [Code](https://github.com/TencentARC/PhotoMaker)

**Portraitbooth: A versatile portrait model for fast identity-preserved personalization**<br>
*Peng, Xu and Zhu, Junwei and Jiang, Boyuan and Tai, Ying and Luo, Donghao and Zhang, Jiangning and Lin, Wei and Jin, Taisong and Wang, Chengjie and Ji, Rongrong.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2312.06354v1)  / [Project](https://portraitbooth.github.io/)

**Facestudio: Put your face everywhere in seconds**<br>
*Yan, Yuxuan and Zhang, Chi and Wang, Rui and Zhou, Yichao and Zhang, Gege and Cheng, Pei and Yu, Gang and Fu, Bin.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2312.02663)  / [Project](https://icoz69.github.io/facestudio/)  / [Code](https://github.com/TencentQQGYLab/FaceStudio)

**Portrait diffusion: Training-free face stylization with chain-of-painting**<br>
*Liu, Jin and Huang, Huaibo and Jin, Chao and He, Ran.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2312.02212)  / [Code](https://github.com/liujin112/PortraitDiffusion)

**When stylegan meets stable diffusion: a w+ adapter for personalized image generation**<br>
*Li, Xiaoming and Hou, Xinyu and Loy, Chen Change.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2311.17461)  / [Project](https://csxmli2016.github.io/projects/w-plus-adapter/)  / [Code](https://github.com/csxmli2016/w-plus-adapter)

**A data perspective on enhanced identity preservation for diffusion personalization**<br>
*He, Xingzhe and Cao, Zhiwen and Kolkin, Nicholas and Yu, Lantao and Wan, Kun and Rhodin, Helge and Kalarot, Ratheesh.*<br>
WACV 2025.  / [PDF](https://arxiv.org/abs/2311.04315)

**High-fidelity Person-centric Subject-to-Image Synthesis**<br>
*Wang, Yibin and Zhang, Weizhong and Zheng, Jianwei and Jin, Cheng.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2311.10329v5)  / [Code](https://github.com/CodeGoat24/Face-diffuser)

**Photoverse: Tuning-free image customization with text-to-image diffusion models**<br>
*Chen, Li and Zhao, Mengyi and Liu, Yiheng and Ding, Mingxu and Song, Yangyang and Wang, Shizun and Wang, Xu and Yang, Hao and Liu, Jing and Du, Kang and {others}.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2309.05793)  / [Project](https://photoverse2d.github.io/)

**Magicapture: High-resolution multi-concept portrait customization**<br>
*Hyung, Junha and Shin, Jaeyo and Choo, Jaegul.*<br>
AAAI 2024.  / [PDF](https://arxiv.org/abs/2309.06895v2)

**Hyperdreambooth: Hypernetworks for fast personalization of text-to-image models**<br>
*Ruiz, Nataniel and Li, Yuanzhen and Jampani, Varun and Wei, Wei and Hou, Tingbo and Pritch, Yael and Wadhwa, Neal and Rubinstein, Michael and Aberman, Kfir.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2307.06949v2)  / [Project](https://hyperdreambooth.github.io/)

**Dreamidentity: Improved editability for efficient face-identity preserved image generation**<br>
*Chen, Zhuowei and Fang, Shancheng and Liu, Wei and He, Qian and Huang, Mengqi and Zhang, Yongdong and Mao, Zhendong.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2307.00300)  / [Project](https://dreamidentity.github.io/)

**Inserting anybody in diffusion models via celeb basis**<br>
*Yuan, Ge and Cun, Xiaodong and Zhang, Yong and Li, Maomao and Qi, Chenyang and Wang, Xintao and Shan, Ying and Zheng, Huicheng.*<br>
NeurIPS 2023.  / [PDF](https://arxiv.org/abs/2306.00926)  / [Project](https://celeb-basis.github.io/)  / [Code](https://github.com/ygtxr1997/CelebBasis)

**Face0: Instantaneously conditioning a text-to-image model on a face**<br>
*Valevski, Dani and Wasserman, Danny and Matias, Yossi and Leviathan, Yaniv.*<br>
SIGGRAPH Asia 2023.  / [PDF](https://arxiv.org/abs/2306.06638)

**Diffusion in diffusion: Cyclic one-way diffusion for text-vision-conditioned generation**<br>
*Wang, Ruoyu and Yang, Yongqi and Qian, Zhihao and Zhu, Ye and Wu, Yu.*<br>
ICLR 2024.  / [PDF](https://arxiv.org/abs/2306.08247)  / [Project](https://wangruoyu02.github.io/cow.github.io/)  / [Code](https://github.com/wangruoyu02/COW)

**Fastcomposer: Tuning-free multi-subject image generation with localized attention**<br>
*Xiao, Guangxuan and Yin, Tianwei and Freeman, William T and Durand, Frédo and Han, Song.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2305.10431)  / [Project](https://hanlab.mit.edu/projects/fastcomposer)  / [Code](https://github.com/mit-han-lab/fastcomposer)

### Character-Driven Generation

**DreamingComics: A Story Visualization Pipeline via Subject and Layout Customized Generation using Video Models**<br>
*Patrick Kwon, Chen Chen*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2512.01686) / [Project](https://yj7082126.github.io/dreamingcomics/)

**From Wardrobe to Canvas: Wardrobe Polyptych LoRA for Part-level Controllable Human Image Generation**<br>
*Jeongho Kim, Sunghyun Park, Hyoungwoo Park, Sungrack Yun, Jaegul Choo, Seokeon Choi*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2507.10217)

**CharaConsist: Fine-Grained Consistent Character Generation**<br>
*Mengyu Wang, Henghui Ding, Jianing Peng, Yao Zhao, Yunpeng Chen, Yunchao Wei*<br>
ICCV 2025.  / [PDF](http://arxiv.org/abs/2507.11533) / [Project](https://murray-wang.github.io/CharaConsist/) / [Code](https://github.com/Murray-Wang/CharaConsist)

**Retrieval Augmented Comic Image Generation**<br>
*Yunhao Shui, Xuekuan Wang, Feng Qiu, Yuqiu Huang, Jinzhu Li, Haoyu Zheng, Jinru Han, Zhuo Zeng, Pengpeng Zhang, Jiarui Han, Keqiang Sun*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2506.12517)

**InstantCharacter: Personalize Any Characters with a Scalable Diffusion Transformer Framework**<br>
*Jiale Tao, Yanbing Zhang, Qixun Wang, Yiji Cheng, Haofan Wang, Xu Bai, Zhengguang Zhou, Ruihuang Li, Linqing Wang, Chunyu Wang, Qin Lin, Qinglin Lu*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2504.12395)  / [Project](https://instantcharacter.github.io/) / [Code](https://github.com/Tencent/InstantCharacter)

**Visual Persona: Foundation Model for Full-Body Human Customization**<br>
*Jisu Nam, Soowon Son, Zhan Xu, Jing Shi, Difan Liu, Feng Liu, Aashish Misraa, Seungryong Kim, Yang Zhou*<br>
CVPR 2025.  / [PDF](https://arxiv.org/abs/2503.15406)  / [Project](https://cvlab-kaist.github.io/Visual-Persona/) / [Code](https://github.com/cvlab-kaist/Visual-Persona)

**AnyStory: Towards Unified Single and Multiple Subject Personalization in Text-to-Image Generation**<br>
*He, Junjie and Tuo, Yuxiang and Chen, Binghui and Zhong, Chongyang and Geng, Yifeng and Bo, Liefeng.*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2501.09503)  / [Project](https://aigcdesigngroup.github.io/AnyStory/)

**SerialGen: Personalized Image Generation by First Standardization Then Personalization**<br>
*Xie, Cong and Zou, Han and Yu, Ruiqi and Zhang, Yan and Zhan, Zhenpeng.*<br>
CVPR 2025.  / [PDF](https://arxiv.org/abs/2412.01485)  / [Project](https://serialgen.github.io/)

**StoryWeaver: A Unified World Model for Knowledge-Enhanced Story Character Customization**<br>
*Zhang, Jinlu and Tang, Jiji and Zhang, Rongsheng and Lv, Tangjie and Sun, Xiaoshuai.*<br>
AAAI 2025.  / [PDF](https://arxiv.org/abs/2412.07375)  / [Code](https://github.com/Aria-Zhangjl/StoryWeaver)

**Content-style disentangled representation for controllable artistic image stylization and generation**<br>
*Zhuoqi, Ma and Yixuan, Zhang and Zejun, You and Long, Tian and Xiyang, Liu.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2412.14496)

**StoryMaker: Towards Holistic Consistent Characters in Text-to-image Generation**<br>
*Zhou, Zhengguang and Li, Jing and Li, Huaxia and Chen, Nemo and Tang, Xu.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2409.12576)  / [Code](https://github.com/RedAIGC/StoryMaker)

**Dreamstory: Open-domain story visualization by llm-guided multi-subject consistent diffusion**<br>
*He, Huiguo and Yang, Huan and Tuo, Zixi and Zhou, Yuan and Wang, Qiuyue and Zhang, Yuhang and Liu, Zeyu and Huang, Wenhao and Chao, Hongyang and Yin, Jian.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2407.12899)  / [Project](https://dream-xyz.github.io/dreamstory)

**Character-Adapter: Prompt-Guided Region Control for High-Fidelity Character Customization**<br>
*Ma, Yuhang and Xu, Wenting and Tang, Jiji and Jin, Qinfeng and Zhang, Rongsheng and Zhao, Zeng and Fan, Changjie and Hu, Zhipeng.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2406.16537)  / [Project](https://github.com/Character-Adapter/Character-Adapter)

**From Parts to Whole: A Unified Reference Framework for Controllable Human Image Generation**<br>
*Huang, Zehuan and Fan, Hongxing and Wang, Lipeng and Sheng, Lu.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2404.15267)  / [Project](https://huanngzh.github.io/Parts2Whole/)  / [Code](https://github.com/huanngzh/Parts2Whole)

**UniHuman: A Unified Model For Editing Human Images in the Wild**<br>
*Li, Nannan and Liu, Qing and Singh, Krishna Kumar and Wang, Yilin and Zhang, Jianming and Plummer, Bryan A and Lin, Zhe.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2312.14985)  / [Code](https://github.com/NannanLi999/UniHuman)

**Autostory: Generating diverse storytelling images with minimal human effort**<br>
*Wang, Wen and Zhao, Canyu and Chen, Hao and Chen, Zhekai and Zheng, Kecheng and Shen, Chunhua.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2311.11243)  / [Project](https://aim-uofa.github.io/AutoStory/)  / [Code](https://github.com/aim-uofa/AutoStory)

**Synthesizing coherent story with auto-regressive latent diffusion models**<br>
*Pan, Xichen and Qin, Pengda and Li, Yuhong and Xue, Hui and Chen, Wenhu.*<br>
WACV 2024.  / [PDF](https://arxiv.org/abs/2211.10950v1)  / [Code](https://github.com/xichenpan/ARLDM)

**The Chosen One: Consistent Characters in Text-to-Image Diffusion Models**<br>
*Avrahami, Omri and Hertz, Amir and Vinker, Yael and Arar, Moab and Fruchter, Shlomi and Fried, Ohad and Cohen-Or, Daniel and Lischinski, Dani.*<br>
SIGGRPAH 2024.  / [PDF](https://arxiv.org/abs/2311.10093)  / [Project](https://omriavrahami.com/the-chosen-one/)  / [Code](https://github.com/ZichengDuan/TheChosenOne)

### Style-Driven Generation

**A Style is Worth One Code: Unlocking Code-to-Style Image Generation with Discrete Style Space**<br>
*Huijie Liu, Shuhao Cui, Haoxiang Cao, Shuai Ma, Kai Wu, Guoliang Kang*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2511.10555) / [Code](https://github.com/Kwai-Kolors/CoTyle)

**SplitFlux: Learning to Decouple Content and Style from a Single Image**<br>
*Yitong Yang, Yinglin Wang, Changshuo Wang, Yongjun Zhang, Ziyang Chen, Shuting He*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2511.15258)

**NP-LoRA: Null Space Projection Unifies Subject and Style in LoRA Fusion**<br>
*Chuheng Chen, Xiaofei Zhou, Geyuan Zhang, Yong Huang*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2511.11051)

**OmniStyle2: Scalable and High Quality Artistic Style Transfer Data Generation via Destylization**<br>
*Ye Wang, Zili Yi, Yibo Zhang, Peng Zheng, Xuping Xie, Jiang Lin, Yilin Wang, Rui Ma*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2509.05970) / [Code](https://github.com/StyleX-Research/OmniStyle2)

**USO: Unified Style and Subject-Driven Generation via Disentangled and Reward Learning**<br>
*Shaojin Wu, Mengqi Huang, Yufeng Cheng, Wenxu Wu, Jiahe Tian, Yiming Luo, Fei Ding, Qian He*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2508.18966) / [Project](https://bytedance.github.io/USO/) / [Code](https://github.com/bytedance/USO)

**Leveraging Diffusion Models for Stylization using Multiple Style Images**<br>
*Dan Ruta, Abdelaziz Djelouah, Raphael Ortiz, Christopher Schroers*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2508.12784)

**SPG: Style-Prompting Guidance for Style-Specific Content Creation**<br>
*Qian Liang, Zichong Chen, Yang Zhou, Hui Huang*<br>
Pacific Graphics 2025.  / [PDF](http://arxiv.org/abs/2508.11476) / [Code](https://github.com/Rumbling281441/SPG)

**Subject or Style: Adaptive and Training-Free Mixture of LoRAs**<br>
*Jia-Chen Zhang, Yu-Jie Xiong*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2508.02165)

**A Training-Free Style-Personalization via Scale-wise Autoregressive Model**<br>
*Kyoungmin Lee, Jihun Park, Jongmin Gim, Wonhyeok Choi, Kyumin Hwang, Jaeyeul Kim, Sunghoon Im*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2507.04482)

**Only-Style: Stylistic Consistency in Image Generation without Content Leakage**<br>
*Tilemachos Aravanis, Panagiotis Filntisis, Petros Maragos, George Retsinas*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2506.09916) / [Project](https://tilemahosaravanis.github.io/Only-Style-PP/) / [Code](https://github.com/TilemahosAravanis/Only-Style)

**ConsiStyle: Style Diversity in Training-Free Consistent T2I Generation**<br>
*Yohai Mazuz, Janna Bruner, Lior Wolf*<br>
SIGGRPAH Asia 2025.  / [PDF](http://arxiv.org/abs/2505.20626) / [Project](https://jbruner23.github.io/consistyle/)

**Training-free Stylized Text-to-Image Generation with Fast Inference**<br>
*Xin Ma, Yaohui Wang, Xinyuan Chen, Tien-Tsin Wong, Cunjian Chen*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2505.19063)

**StyleAR: Customizing Multimodal Autoregressive Model for Style-Aligned Text-to-Image Generation**<br>
*Yi Wu, Lingting Zhu, Shengju Qian, Lei Liu, Wandi Qiao, Lequan Yu, Bin Li*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2505.19874) / [Project](https://stylear.github.io/) / [Code](https://github.com/wuyi2020/StyleAR)

**OmniConsistency: Learning Style-Agnostic Consistency from Paired Stylization Data**<br>
*Yiren Song, Cheng Liu, Mike Zheng Shou*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2505.18445) / [Code](https://github.com/showlab/OmniConsistency) / [Dataset](https://huggingface.co/datasets/showlab/OmniConsistency)

**CDST: Color Disentangled Style Transfer for Universal Style Reference Customization**<br>
*Shiwen Zhang, Zhuowei Chen, Lang Chen, Yanze Wu*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2506.13770)

**Style Customization of Text-to-Vector Generation with Image Diffusion Priors**<br>
*Peiying Zhang, Nanxuan Zhao, Jing Liao*<br>
SIGGRAPH 2025.  / [PDF](https://arxiv.org/abs/2505.10558)  / [Project](https://customsvg.github.io/) / [Code](https://github.com/intchous/custom-svg-style)

**AC-LoRA: Auto Component LoRA for Personalized Artistic Style Image Generation**<br>
*Zhipu Cui, Andong Tian, Zhi Ying, Jialiang Lu*<br>
ICCGV 2025.  / [PDF](https://arxiv.org/abs/2504.02231)  

**UnZipLoRA: Separating Content and Style from a Single Image**<br>
*Liu, Chang and Shah, Viraj and Cui, Aiyu and Lazebnik, Svetlana.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2412.04465)  / [Project](https://unziplora.github.io/)

**LoRA. rar: Learning to Merge LoRAs via Hypernetworks for Subject-Style Conditioned Image Generation**<br>
*Shenaj, Donald and Bohdal, Ondrej and Ozay, Mete and Zanuttigh, Pietro and Michieli, Umberto.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2412.05148)

**Style-Friendly SNR Sampler for Style-Driven Generation**<br>
*Choi, Jooyoung and Shin, Chaehun and Oh, Yeongtak and Kim, Heeseung and Yoon, Sungroh.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2411.14793)  / [Project](https://stylefriendly.github.io/)

**CSGO: Content-Style Composition in Text-to-Image Generation**<br>
*Xing, Peng and Wang, Haofan and Sun, Yanpeng and Wang, Qixun and Bai, Xu and Ai, Hao and Huang, Renyuan and Li, Zechao.*<br>
OpenReview 2024.  / [PDF](https://openreview.net/forum?id=E3PgLQzPob)

**FineStyle: Fine-grained Controllable Style Personalization for Text-to-image Models**<br>
*Zhang, Gong and Sohn, Kihyuk and Hahn, Meera and Shi, Humphrey and Essa, Irfan.*<br>
NeurIPS 2024.  / [PDF](https://openreview.net/forum?id=1SmXUGzrH8)  / [Code](https://github.com/SHI-Labs/FineStyle)

**Customizing text-to-image models with a single image pair**<br>
*Jones, Maxwell and Wang, Sheng-Yu and Kumari, Nupur and Bau, David and Zhu, Jun-Yan.*<br>
SIGGRAPH Asia 2024.  / [PDF](https://arxiv.org/abs/2405.01536v2)  / [Project](https://paircustomization.github.io/)  / [Code](https://github.com/PairCustomization/PairCustomization)

**RB-Modulation: Training-Free Personalization of Diffusion Models using Stochastic Optimal Control**<br>
*Rout, Litu and Chen, Yujia and Ruiz, Nataniel and Kumar, Abhishek and Caramanis, Constantine and Shakkottai, Sanjay and Chu, Wen-Sheng.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2405.17401) / [Code](https://github.com/google/RB-Modulation)

**InstantStyle: Free lunch towards style-preserving in text-to-image generation**<br>
*Wang, Haofan and Spinelli, Matteo and Wang, Qixun and Bai, Xu and Qin, Zekui and Chen, Anthony.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2404.02733)  / [Code](https://github.com/instantX-research/InstantStyle)

**Text-to-Image Synthesis for Any Artistic Styles: Advancements in Personalized Artistic Image Generation via Subdivision and Dual Binding**<br>
*Park, Junseo and Ko, Beomseok and Jang, Hyeryung.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2404.05256)

**Block-wise LoRA: Revisiting Fine-grained LoRA for Effective Personalization and Stylization in Text-to-Image Generation**<br>
*Li, Likun and Zeng, Haoqi and Yang, Changpeng and Jia, Haozhe and Xu, Di.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2403.07500)

**Break-for-make: Modular low-rank adaptations for composable content-style customization**<br>
*Xu, Yu and Tang, Fan and Cao, Juan and Zhang, Yuxin and Deussen, Oliver and Dong, Weiming and Li, Jintao and Lee, Tong-Yee.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2403.19456)

**U-VAP: User-specified Visual Appearance Personalization via Decoupled Self Augmentation**<br>
*Wu, You and Liu, Kean and Mi, Xiaoyue and Tang, Fan and Cao, Juan and Li, Jintao.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2403.20231v1)  / [Code](https://github.com/ICTMCG/U-VAP)

**Implicit style-content separation using b-lora**<br>
*Frenkel, Yarden and Vinker, Yael and Shamir, Ariel and Cohen-Or, Daniel.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2403.14572)  / [Project](https://b-lora.github.io/B-LoRA/)  / [Code](https://github.com/yardenfren1996/B-LoRA)

**ArtAdapter: Text-to-Image Style Transfer using Multi-Level Style Encoder and Explicit Adaptation**<br>
*Chen, Dar-Yen and Tennent, Hamish and Hsu, Ching-Wen.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2312.02109v2)  / [Project](https://cardinalblue.github.io/artadapter.github.io/)  / [Code](https://github.com/cardinalblue/ArtAdapter)

**Style aligned image generation via shared attention**<br>
*Hertz, Amir and Voynov, Andrey and Fruchter, Shlomi and Cohen-Or, Daniel.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2312.02133v2)  / [Project](https://style-aligned-gen.github.io/)  / [Code](https://github.com/google/style-aligned/)

**Ziplora: Any subject in any style by effectively merging loras**<br>
*Shah, Viraj and Ruiz, Nataniel and Cole, Forrester and Lu, Erika and Lazebnik, Svetlana and Li, Yuanzhen and Jampani, Varun.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2311.13600v1)  / [Project](https://ziplora.github.io/)

**StyleBoost: A Study of Personalizing Text-to-Image Generation in Any Style using DreamBooth**<br>
*Park, Junseo and Ko, Beomseok and Jang, Hyeryung.*<br>
ICTC 2023.  / [PDF](https://ieeexplore.ieee.org/abstract/document/10392676)

**StyleAdapter: A Unified Stylized Image Generation Model**<br>
*Wang, Zhouxia and Wang, Xintao and Xie, Liangbin and Qi, Zhongang and Shan, Ying and Wang, Wenping and Luo, Ping.*<br>
IJCV 2024.  / [PDF](https://arxiv.org/abs/2309.01770v2)

**Styledrop: Text-to-image generation in any style**<br>
*Sohn, Kihyuk and Ruiz, Nataniel and Lee, Kimin and Chin, Daniel Castro and Blok, Irina and Chang, Huiwen and Barber, Jarred and Jiang, Lu and Entis, Glenn and Li, Yuanzhen and Hao, Yuan and Essa, Irfan and Rubinstein, Michael and Krishnan, Dilip.*<br>
NeurIPS 2023.  / [PDF](https://arxiv.org/abs/2306.00983)  / [Project](https://styledrop.github.io/)

**Inversion-based style transfer with diffusion models**<br>
*Zhang, Yuxin and Huang, Nisha and Tang, Fan and Huang, Haibin and Ma, Chongyang and Dong, Weiming and Xu, Changsheng.*<br>
CVPR 2023.  / [PDF](https://arxiv.org/abs/2211.13203v3)  / [Code](https://github.com/zyxElsa/InST)

### High-level Semantics Generation

**PhyCustom: Towards Realistic Physical Customization in Text-to-Image Generation**<br>
*Fan Wu, Cheng Chen, Zhoujie Fu, Jiacheng Wei, Yi Xu, Deheng Ye, Guosheng Lin*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2512.02794) / [Code](https://github.com/wufan-cse/PhyCustom)

**Event-Customized Image Generation**<br>
*Wang, Zhen and Jiang, Yilei and Zheng, Dong and Xiao, Jun and Chen, Long.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2410.02483)

**ImPoster: Text and Frequency Guidance for Subject Driven Action Personalization using Diffusion Models**<br>
*Kothandaraman, Divya and Kulkarni, Kuldeep and Shekhar, Sumit and Srinivasan, Balaji Vasan and Manocha, Dinesh.*<br>
COLING 2025.  / [PDF](https://arxiv.org/abs/2409.15650)  / [Code](https://github.com/divyakraman/ImPosterDiffusion2024)

**Customizing Text-to-Image Generation with Inverted Interaction**<br>
*Mengmeng Ge, Xu Jia, Takashi Isobe, Xiaomin Li, Qinghe Wang, Jing Mu, Dong Zhou, liwang Amd, Huchuan Lu, Lu Tian, Ashish Sirasao, Emad Barsoum*<br>
ACM MM 2024. / [PDF](https://openreview.net/pdf?id=3Xx2MgYX67) 

**Lego: Learning to disentangle and invert concepts beyond object appearance in text-to-image diffusion models**<br>
*Motamed, Saman and Paudel, Danda Pani and Van Gool, Luc.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2311.13833)

**Learning disentangled identifiers for action-customized text-to-image generation**<br>
*Huang, Siteng and Gong, Biao and Feng, Yutong and Chen, Xi and Fu, Yuqian and Liu, Yu and Wang, Donglin.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2311.15841v5)  / [Project](https://adi-t2i.github.io/ADI/)

**ReVersion: Diffusion-based relation inversion from images**<br>
*Huang, Ziqi and Wu, Tianxing and Jiang, Yuming and Chan, Kelvin CK and Liu, Ziwei.*<br>
SIGGRAPH Asia 2024.  / [PDF](https://arxiv.org/abs/2303.13495)  / [Project](https://ziqihuangg.github.io/projects/reversion.html)  / [Code](https://github.com/ziqihuangg/ReVersion)

### Multiple Concepts Generation

**PSR: Scaling Multi-Subject Personalized Image Generation with Pairwise Subject-Consistency Rewards**<br>
*Shulei Wang, Longhui Wei, Xin He, Jianbo Ouyang, Hui Lu, Zhou Zhao, Qi Tian*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2512.01236) / [Code](https://github.com/wang-shulei/PSR)

**iMontage: Unified, Versatile, Highly Dynamic Many-to-many Image Generation**<br>
*Zhoujie Fu, Xianfang Zeng, Jinghong Lan, Xinyao Liao, Cheng Chen, Junyi Chen, Jiacheng Wei, Wei Cheng, Shiyu Liu, Yunuo Chen, Gang Yu, Guosheng Lin*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2511.20635) / [Project](https://kr1sjfu.github.io/iMontage-web/)

**Canvas-to-Image: Compositional Image Generation with Multimodal Controls**<br>
*Yusuf Dalva, Guocheng Gordon Qian, Maya Goldenberg, Tsai-Shien Chen, Kfir Aberman, Sergey Tulyakov, Pinar Yanardag, Kuan-Chieh Jackson Wang*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2511.21691) / [Project](https://snap-research.github.io/canvas-to-image/) 

**MIFO: Learning and Synthesizing Multi-Instance from One Image**<br>
*Kailun Su, Ziqi He, Xi Wang, Yang Zhou*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2511.00542)

**LayerComposer: Interactive Personalized T2I via Spatially-Aware Layered Canvas**<br>
*Guocheng Gordon Qian, Ruihang Zhang, Tsai-Shien Chen, Yusuf Dalva, Anujraaj Argo Goyal, Willi Menapace, Ivan Skorokhodov, Meng Dong, Arpit Sahni, Daniil Ostashev, Ju Hu, Sergey Tulyakov, Kuan-Chieh Jackson Wang*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2510.20820) / [Project](https://snap-research.github.io/canvascomposer/)

**Chimera: Compositional Image Generation using Part-based Concepting**<br>
*Shivam Singh, Yiming Chen, Agneet Chatterjee, Amit Raj, James Hays, Yezhou Yang, Chitta Baral*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2510.18083) / [Project](https://chimera-compositional-image-generation.vercel.app/) / [Code](https://github.com/shivamsingh-gpu/Chimera)

**ContextGen: Contextual Layout Anchoring for Identity-Consistent Multi-Instance Generation**<br>
*Ruihang Xu, Dewei Zhou, Fan Ma, Yi Yang*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2510.11000) / [Project](https://nenhang.github.io/ContextGen/) / [Code](https://github.com/nenhang/ContextGen)

**Mod-Adapter: Tuning-Free and Versatile Multi-concept Personalization via Modulation Adapter**<br>
*Weizhi Zhong, Huan Yang, Zheng Liu, Huiguo He, Zijian He, Xuesong Niu, Di Zhang, Guanbin Li*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2505.18612)

**PartComposer: Learning and Composing Part-Level Concepts from Single-Image Examples**<br>
*Junyu Liu, R. Kenny Jones, Daniel Ritchie*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2506.03004)

**MOSAIC: Multi-Subject Personalized Generation via Correspondence-Aware Alignment and Disentanglement**<br>
*Dong She, Siming Fu, Mushui Liu, Qiaoqiao Jin, Hualiang Wang, Mu Liu, Jidong Jiang*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2509.01977) / [Project](https://bytedance-fanqie-ai.github.io/MOSAIC/) / [Code](https://github.com/bytedance-fanqie-ai/MOSAIC)

**FocusDPO: Dynamic Preference Optimization for Multi-Subject Personalized Image Generation via Adaptive Focus**<br>
*Qiaoqiao Jin, Siming Fu, Dong She, Weinan Jia, Hualiang Wang, Mu Liu, Jidong Jiang*<br>
AAAI 2026.  / [PDF](http://arxiv.org/abs/2509.01181) / [Project](https://bytedance-fanqie-ai.github.io/FocusDPO/) / [Code](https://github.com/bytedance-fanqie-ai/FocusDPO)

**Interact-Custom: Customized Human Object Interaction Image Generation**<br>
*Zhu Xu, Zhaowen Wang, Yuxin Peng, Yang Liu*<br>
ACMMM 2025.  / [PDF](http://arxiv.org/abs/2508.19575) / [Code](https://github.com/XZPKU/Inter-custom)

**MUSE: Multi-Subject Unified Synthesis via Explicit Layout Semantic Expansion**<br>
*Fei Peng, Junqiang Wu, Yan Li, Tingting Gao, Di Zhang, Huiyuan Fu*<br>
ICCV 2025.  / [PDF](http://arxiv.org/abs/2508.14440) / [Code](https://github.com/pf0607/MUSE)

**TARA: Token-Aware LoRA for Composable Personalization in Diffusion Models**<br>
*Yuqi Peng, Lingtao Zheng, Yufeng Yang, Yi Huang, Mingfu Yan, Jianzhuang Liu, Shifeng Chen*<br>
AAAI 2026.  / [PDF](http://arxiv.org/abs/2508.08812) / [Code](https://github.com/YuqiPeng77/TARA)

**PositionIC: Unified Position and Identity Consistency for Image Customization**<br>
*Junjie Hu, Tianyang Han, Kai Ma, Jialin Gao, Hao Dou, Song Yang, Xianhua He, Jianhui Zhang, Junfeng Luo, Xiaoming Wei, Wenqiang Zhang*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2507.13861)

**LAMIC: Layout-Aware Multi-Image Composition via Scalability of Multimodal Diffusion Transformer**<br>
*Yuzhuo Chen, Zehua Ma, Jianhua Wang, Kai Kang, Shunyu Yao, Weiming Zhang*<br>
AAAI 2026.  / [PDF](http://arxiv.org/abs/2508.00477) / [Code](https://github.com/Suchenl/LAMIC)

**QR-LoRA: Efficient and Disentangled Fine-tuning via QR Decomposition for Customized Generation**<br>
*Jiahui Yang, Yongjia Ma, Donglin Di, Hao Li, Wei Chen, Yan Xie, Jianxun Cui, Xun Yang, Wangmeng Zuo*<br>
ICCV 2025.  / [PDF](http://arxiv.org/abs/2507.04599) / [Project](https://luna-ai-lab.github.io/QR-LoRA/) / [Code](https://github.com/luna-ai-lab/QR-LoRA)

**FreeLoRA: Enabling Training-Free LoRA Fusion for Autoregressive Multi-Subject Personalization**<br>
*Peng Zheng, Ye Wang, Rui Ma, Zuxuan Wu*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2507.01792)

**XVerse: Consistent Multi-Subject Control of Identity and Semantic Attributes via DiT Modulation**<br>
*Bowen Chen, Mengyi Zhao, Haomiao Sun, Li Chen, Xu Wang, Kang Du, Xinglong Wu*<br>
NeurIPS 2025.  / [PDF](http://arxiv.org/abs/2506.21416) / [Project](https://bytedance.github.io/XVerse/) / [Code](https://github.com/bytedance/XVerse)

**ShowFlow: From Robust Single Concept to Condition-Free Multi-Concept Generation**<br>
*Trong-Vu Hoang, Quang-Binh Nguyen, Thanh-Toan Do, Tam V. Nguyen, Minh-Triet Tran, Trung-Nghia Le*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2506.18493)

**LoRAShop: Training-Free Multi-Concept Image Generation and Editing with Rectified Flow Transformers**<br>
*Yusuf Dalva, Hidir Yesiltepe, Pinar Yanardag*<br>
NeurIPS 2025.  / [PDF](http://arxiv.org/abs/2505.23758) / [Project](https://lorashop.github.io/) / [Code](https://github.com/gemlab-vt/LoRAShop)

**Create Anything Anywhere: Layout-Controllable Personalized Diffusion Model for Multiple Subjects**<br>
*Wei Li, Hebei Li, Yansong Peng, Siying Wu, Yueyi Zhang, Xiaoyan Sun*<br>
ICME 2025.  / [PDF](http://arxiv.org/abs/2505.20909)

**MultLFG: Training-free Multi-LoRA composition using Frequency-domain Guidance**<br>
*Aniket Roy, Maitreya Suin, Ketul Shah, Rama Chellappa*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2505.20525)

**MUSAR: Exploring Multi-Subject Customization from Single-Subject Dataset via Attention Routing**<br>
*Zinan Guo, Pengze Zhang, Yanze Wu, Chong Mou, Songtao Zhao, Qian He*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2505.02823) / [Code](https://github.com/guozinan126/MUSAR) / [Dataset](https://huggingface.co/datasets/guozinan/MUSAR-Gen)

**DreamO: A Unified Framework for Image Customization**<br>
*Chong Mou, Yanze Wu, Wenxu Wu, Zinan Guo, Pengze Zhang, Yufeng Cheng, Yiming Luo, Fei Ding, Shiwen Zhang, Xinghui Li, Mengtian Li, Mingcong Liu, Yi Zhang, Shaojin Wu, Songtao Zhao, Jian Zhang, Qian He, Xinglong Wu*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2504.16915) / [Code](https://github.com/bytedance/DreamO)

**Storybooth: Training-free Multi-Subject Consistency for Improved Visual Storytelling**<br>
*Jaskirat Singh, Junshen Kevin Chen, Jonas Kohler, Michael Cohen*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2504.05800)

**FaR: Enhancing Multi-Concept Text-to-Image Diffusion via Concept Fusion and Localized Refinement**<br>
*Gia-Nghia Tran, Quang-Huy Che, Trong-Tai Dam Vu, Bich-Nga Pham, Vinh-Tiep Nguyen, Trung-Nghia Le, Minh-Triet Tran*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2504.03292) 

**Less-to-More Generalization: Unlocking More Controllability by In-Context Generation**<br>
*Shaojin Wu, Mengqi Huang, Wenxu Wu, Yufeng Cheng, Fei Ding, Qian He*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2504.02160) / [Project](https://bytedance.github.io/UNO/) / [Code](https://github.com/bytedance/UNO)

**ICE: Intrinsic Concept Extraction from a Single Image via Diffusion Models**<br>
*Fernando Julio Cendra, Kai Han*<br>
CVPR 2025.  / [PDF](https://arxiv.org/abs/2503.19902) / [Project](https://visual-ai.github.io/ice)

**DynASyn: Multi-Subject Personalization Enabling Dynamic Action Synthesis**<br>
*Yongjin Choi, Chanhun Park, Seung Jun Baek*<br>
AAAI 2025.  / [PDF](https://arxiv.org/abs/2503.17728) 

**Piece it Together: Part-Based Concepting with IP-Priors**<br>
*Elad Richardson, Kfir Goldberg, Yuval Alaluf, Daniel Cohen-Or*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2503.10365) / [Project](https://eladrich.github.io/PiT/) / [Code](https://github.com/eladrich/PiT)

**DynamicID: Zero-Shot Multi-ID Image Personalization with Flexible Facial Editability**<br>
*Xirui Hu, Jiahao Wang, Hao Chen, Weizhan Zhang, Benqi Wang, Yikun Li, Haishun Nan*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2503.06505) 

**K-LoRA: Unlocking Training-Free Fusion of Any Subject and Style LoRAs**<br>
*Ziheng Ouyang, Zhen Li, Qibin Hou*<br>
CVPR 2025.  / [PDF](https://arxiv.org/abs/2502.18461) / [Project](https://k-lora.github.io/K-LoRA.io/) / [Code](https://github.com/HVision-NKU/K-LoRA)

**FlipConcept: Tuning-Free Multi-Concept Personalization for Text-to-Image Generation**<br>
*Young Beom Woo, Sun Eung Kim*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2502.15203) 

**IP-Composer: Semantic Composition of Visual Concepts**<br>
*Sara Dorfman, Dana Cohen-Bar, Rinon Gal, Daniel Cohen-Or*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2502.13951) / [Project](https://ip-composer.github.io/IP-Composer/) / [Code](https://github.com/ip-composer)

**Multitwine: Multi-Object Compositing with Text and Layout Control**<br>
*Gemma Canet Tarrés, Zhe Lin, Zhifei Zhang, He Zhang, Andrew Gilbert, John Collomosse, Soo Ye Kim*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2502.05165)

**Cached Multi-Lora Composition for Multi-Concept Image Generation**<br>
*Xiandong Zou, Mingzhu Shen, Christos-Savvas Bouganis, Yiren Zhao*<br>
ICLR 2025.  / [PDF](https://www.arxiv.org/abs/2502.04923)

**Object-level Visual Prompts for Compositional Image Generation**<br>
*Parmar, Gaurav and Patashnik, Or and Wang, Kuan-Chieh and Ostashev, Daniil and Narasimhan, Srinivasa and Zhu, Jun-Yan and Cohen-Or, Daniel and Aberman, Kfir.*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2501.01424)  / [Project](https://snap-research.github.io/visual-composer/)

**TokenVerse: Versatile Multi-concept Personalization in Token Modulation Space**<br>
*Garibi, Daniel and Yadin, Shahar and Paiss, Roni and Tov, Omer and Zada, Shiran and Ephrat, Ariel and Michaeli, Tomer and Mosseri, Inbar and Dekel, Tali.*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2501.12224)  / [Project](https://token-verse.github.io/)

**Improving Multi-Subject Consistency in Open-Domain Image Generation with Isolation and Reposition Attention**<br>
*He, Huiguo and Wang, Qiuyue and Zhou, Yuan and Cai, Yuxuan and Chao, Hongyang and Yin, Jian and Yang, Huan.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2411.19261)

**PersonaCraft: Personalized Full-Body Image Synthesis for Multiple Identities from Single References Using 3D-Model-Conditioned Diffusion**<br>
*Kim, Gwanghyun and Jeon, Suh Yoon and Lee, Seunggyu and Chun, Se Young.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2411.18068)  / [Project](https://gwang-kim.github.io/persona_craft/)  / [Code](https://github.com/gwang-kim/PersonaCraft)

**MagicTailor: Component-Controllable Personalization in Text-to-Image Diffusion Models**<br>
*Zhou, Donghao and Huang, Jiancheng and Bai, Jinbin and Wang, Jiaze and Chen, Hao and Chen, Guangyong and Hu, Xiaowei and Heng, Pheng-Ann.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2410.13370)  / [Project](https://correr-zhou.github.io/MagicTailor/)  / [Code](https://github.com/correr-zhou/MagicTailor)

**How to Continually Adapt Text-to-Image Diffusion Models for Flexible Customization?**<br>
*Dong, Jiahua and Liang, Wenqi and Li, Hongliu and Zhang, Duzhen and Cao, Meng and Ding, Henghui and Khan, Salman and Khan, Fahad Shahbaz.*<br>
NeurIPS 2024.  / [PDF](https://arxiv.org/abs/2410.17594)  / [Code](https://github.com/JiahuaDong/CIFC)

**RelationBooth: Towards Relation-Aware Customized Object Generation**<br>
*Shi, Qingyu and Qi, Lu and Wu, Jianzong and Bai, Jinbin and Wang, Jingbo and Tong, Yunhai and Li, Xiangtai and Yang, Ming-Husang.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2410.23280)  / [Project](https://shi-qingyu.github.io/RelationBooth/)

**GroundingBooth: Grounding Text-to-Image Customization**<br>
*Xiong, Zhexiao and Xiong, Wei and Shi, Jing and Zhang, He and Song, Yizhi and Jacobs, Nathan.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2409.08520)  / [Project](https://groundingbooth.github.io/)

**MS-Diffusion: Multi-subject Zero-shot Image Personalization with Layout Guidance**<br>
*Wang, Xierui and Fu, Siming and Huang, Qihan and He, Wanggui and Jiang, Hao.*<br>
ICLR 2025.  / [PDF](https://openreview.net/forum?id=PJqP0wyQek)

**Concept Conductor: Orchestrating Multiple Personalized Concepts in Text-to-Image Synthesis**<br>
*Yao, Zebin and Feng, Fangxiang and Li, Ruifan and Wang, Xiaojie.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2408.03632)  / [Project](https://nihukat.github.io/Concept-Conductor/)  / [Code](https://github.com/Nihukat/Concept-Conductor)

**Training-free Subject-Enhanced Attention Guidance for Compositional Text-to-image Generation**<br>
*Liu, Shengyuan and Wang, Bo and Ma, Ye and Yang, Te and Cao, Xipeng and Chen, Quan and Li, Han and Dong, Di and Jiang, Peng.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2405.06948)

**Multi-Subject Personalization**<br>
*Jain, Arushi and Paliwal, Shubham and Sharma, Monika and Jamwal, Vikram and Vig, Lovekesh.*<br>
NeurIPS 2023.  / [PDF](https://arxiv.org/abs/2405.12742)

**FreeCustom: Tuning-Free Customized Image Generation for Multi-Concept Composition**<br>
*Ding, Ganggui and Zhao, Canyu and Wang, Wen and Yang, Zhen and Liu, Zide and Chen, Hao and Shen, Chunhua.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2405.13870v1)  / [Project](https://aim-uofa.github.io/FreeCustom/)  / [Code](https://github.com/aim-uofa/FreeCustom)

**Identity Decoupling for Multi-Subject Personalization of Text-to-Image Models**<br>
*Jang, Sangwon and Jo, Jaehyeong and Lee, Kimin and Hwang, Sung Ju.*<br>
NeurIPS 2024.  / [PDF](https://arxiv.org/abs/2404.04243)  / [Project](https://mudi-t2i.github.io/)  / [Code](https://github.com/agwmon/MuDI)

**Concept Weaver: Enabling Multi-Concept Fusion in Text-to-Image Models**<br>
*Kwon, Gihyun and Jenni, Simon and Li, Dingzeyu and Lee, Joon-Young and Ye, Jong Chul and Heilbron, Fabian Caba.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2404.03913v1)

**MC$^2$: Multi-concept Guidance for Customized Multi-concept Generation**<br>
*Jiang, Jiaxiu and Zhang, Yabo and Feng, Kailai and Wu, Xiaohe and Zuo, Wangmeng.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2404.05268)  / [Code](https://github.com/JIANGJiaXiu/MC-2)

**LoRA-Composer: Leveraging Low-Rank Adaptation for Multi-Concept Customization in Training-Free Diffusion Models**<br>
*Yang, Yang and Wang, Wen and Peng, Liang and Song, Chaotian and Chen, Yao and Li, Hengjia and Yang, Xiaolong and Lu, Qinglin and Cai, Deng and Wu, Boxi and {others}.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2403.11627)  / [Project](https://young98cn.github.io/lora_composer_page/)  / [Code](https://github.com/Young98CN/LoRA_Composer)

**Omg: Occlusion-friendly personalized multi-concept generation in diffusion models**<br>
*Kong, Zhe and Zhang, Yong and Yang, Tianyu and Wang, Tao and Zhang, Kaihao and Wu, Bizhu and Chen, Guanying and Liu, Wei and Luo, Wenhan.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2403.10983v2)  / [Project](https://kongzhecn.github.io/omg-project/)  / [Code](https://github.com/kongzhecn/OMG/)

**$\lambda$-ECLIPSE: Multi-Concept Personalized Text-to-Image Diffusion Models by Leveraging CLIP Latent Space**<br>
*Patel, Maitreya and Jung, Sangmin and Baral, Chitta and Yang, Yezhou.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2402.05195)  / [Project](https://eclipse-t2i.github.io/Lambda-ECLIPSE/)  / [Code](https://github.com/eclipse-t2i/lambda-eclipse-inference)

**Compositional inversion for stable diffusion models**<br>
*Zhang, Xulu and Wei, Xiao-Yong and Wu, Jinlin and Zhang, Tianyi and Zhang, Zhaoxiang and Lei, Zhen and Li, Qing.*<br>
AAAI 2024.  / [PDF](https://arxiv.org/abs/2312.08048v3)  / [Code](https://github.com/zhangxulu1996/Compositional-Inversion)

**Customizable image synthesis with multiple subjects**<br>
*Liu, Zhiheng and Zhang, Yifei and Shen, Yujun and Zheng, Kecheng and Zhu, Kai and Feng, Ruili and Liu, Yu and Zhao, Deli and Zhou, Jingren and Cao, Yang.*<br>
NeurIPS 2023.  / [PDF](https://arxiv.org/abs/2305.19327v1)  / [Project](https://cones-page.github.io/)  / [Code](https://github.com/ali-vilab/Cones-V2)

**Mix-of-show: Decentralized low-rank adaptation for multi-concept customization of diffusion models**<br>
*Gu, Yuchao and Wang, Xintao and Wu, Jay Zhangjie and Shi, Yujun and Chen, Yunpeng and Fan, Zihan and Xiao, Wuyou and Zhao, Rui and Chang, Shuning and Wu, Weijia and {others}.*<br>
NeurIPS 2023.  / [PDF](https://arxiv.org/abs/2305.18292)  / [Code](https://github.com/TencentARC/Mix-of-Show)

**Multi-concept customization of text-to-image diffusion**<br>
*Kumari, Nupur and Zhang, Bingliang and Zhang, Richard and Shechtman, Eli and Zhu, Jun-Yan.*<br>
CVPR 2023.  / [PDF](https://arxiv.org/abs/2212.04488v2)  / [Project](https://www.cs.cmu.edu/~custom-diffusion)  / [Code](https://github.com/adobe-research/custom-diffusion)

### Personalized Video Generation

**First Frame Is the Place to Go for Video Content Customization**<br>
*Jingxi Chen, Zongxia Li, Zhichao Liu, Guangyao Shi, Xiyang Wu, Fuxiao Liu, Cornelia Fermuller, Brandon Y. Feng, Yiannis Aloimonos*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2511.15700) / [Project](https://firstframego.github.io/) / [Code](https://github.com/zli12321/FFGO-Video-Customization)

**ID-Composer: Multi-Subject Video Synthesis with Hierarchical Identity Preservation**<br>
*Panwang Pan, Jingjing Zhao, Yuchen Lin, Chenguo Lin, Chenxin Li, Haopeng Li, Honglei Yan, Tingting Shen, Yadong Mu*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2511.00511)

**CoMo: Compositional Motion Customization for Text-to-Video Generation**<br>
*Youcan Xu, Zhen Wang, Jiaxin Shi, Kexin Li, Feifei Shao, Jun Xiao, Yi Yang, Jun Yu, Long Chen*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2510.23007) / [Project](https://como6.github.io/)

**BachVid: Training-Free Video Generation with Consistent Background and Character**<br>
*Han Yan, Xibin Song, Yifu Wang, Hongdong Li, Pan Ji, Chao Ma*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2510.21696) / [Project](https://wolfball.github.io/bachvid/) / [Code](https://github.com/wolfball/BachVid)

**Identity-Preserving Image-to-Video Generation via Reward-Guided Optimization**<br>
*Liao Shen, Wentao Jiang, Yiran Zhu, Jiahe Li, Tiezheng Ge, Zhiguo Cao, Bo Zheng*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2510.14255) / [Project](https://ipro-alimama.github.io/)

**OmniVCus: Feedforward Subject-driven Video Customization with Multimodal Control Conditions**<br>
*Yuanhao Cai, He Zhang, Xi Chen, Jinbo Xing, Yiwei Hu, Yuqian Zhou, Kai Zhang, Zhifei Zhang, Soo Ye Kim, Tianyu Wang, Yulun Zhang, Xiaokang Yang, Zhe Lin, Alan Yuille*<br>
NeurIPS 2025.  / [PDF](http://arxiv.org/abs/2506.23361) / [Code](https://github.com/caiyuanhao1998/Open-OmniVCus)

**MAGREF: Masked Guidance for Any-Reference Video Generation with Subject Disentanglement**<br>
*Yufan Deng, Yuanyang Yin, Xun Guo, Yizhi Wang, Jacob Zhiyuan Fang, Shenghai Yuan, Yiding Yang, Angtian Wang, Bo Liu, Haibin Huang, Chongyang Ma*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2505.23742) / [Project](https://magref-video.github.io/) / [Code](https://github.com/MAGREF-Video/MAGREF)

**HuMo: Human-Centric Video Generation via Collaborative Multi-Modal Conditioning**<br>
*Liyang Chen, Tianxiang Ma, Jiawei Liu, Bingchuan Li, Zhuowei Chen, Lijie Liu, Xu He, Gen Li, Qian He, Zhiyong Wu*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2509.08519) / [Project](https://phantom-video.github.io/HuMo/) / [Code](https://github.com/Phantom-video/HuMo)

**Identity-Preserving Text-to-Video Generation via Training-Free Prompt, Image, and Guidance Enhancement**<br>
*Jiayi Gao, Changcheng Hua, Qingchao Chen, Yuxin Peng, Yang Liu*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2509.01362) / [Code](https://github.com/Andyplus1/IPT2V)

**PersonaAnimator: Personalized Motion Transfer from Unconstrained Videos**<br>
*Ziyun Qian, Runyu Xiao, Shuyuan Tu, Wei Xue, Dingkang Yang, Mingcheng Li, Dongliang Kou, Minghao Han, Zizhi Chen, Lihua Zhang*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2508.19895)

**Stand-In: A Lightweight and Plug-and-Play Identity Control for Video Generation**<br>
*Bowen Xue, Qixin Yan, Wenjing Wang, Hao Liu, Chen Li*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2508.07901) / [Code](https://github.com/WeChatCV/Stand-In)

**LaVieID: Local Autoregressive Diffusion Transformers for Identity-Preserving Video Creation**<br>
*Wenhui Song, Hanhui Li, Jiehui Huang, Panwen Hu, Yuhao Cheng, Long Chen, Yiqiang Yan, Xiaodan Liang*<br>
ACMMM 2025.  / [PDF](http://arxiv.org/abs/2508.07603) / [Code](https://github.com/ssugarwh/LaVieID)

**Identity-Preserving Text-to-Video Generation Guided by Simple yet Effective Spatial-Temporal Decoupled Representations**<br>
*Yuji Wang, Moran Li, Xiaobin Hu, Ran Yi, Jiangning Zhang, Han Feng, Weijian Cao, Yabiao Wang, Chengjie Wang, Lizhuang Ma*<br>
ACMMM 2025.  / [PDF](http://arxiv.org/abs/2507.04705) / [Code](https://github.com/rain152/IPVG)

**Zero-Shot Dynamic Concept Personalization with Grid-Based LoRA**<br>
*Rameen Abdal, Or Patashnik, Ekaterina Deyneka, Hao Chen, Aliaksandr Siarohin, Sergey Tulyakov, Daniel Cohen-Or, Kfir Aberman*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2507.17963) / [Project](https://snap-research.github.io/zero-shot-dynamic-concepts/)

**Proteus-ID: ID-Consistent and Motion-Coherent Video Customization**<br>
*Guiyu Zhang, Chen Shi, Zijian Jiang, Xunzhi Xiang, Jingjing Qian, Shaoshuai Shi, Li Jiang*<br>
SIGGRAPH Asia 2025.  / [PDF](http://arxiv.org/abs/2506.23729) / [Project](https://grenoble-zhang.github.io/Proteus-ID/) / [Code](https://github.com/grenoble-zhang/Proteus-ID)

**Training-Free Motion Customization for Distilled Video Generators with Adaptive Test-Time Distillation**<br>
*Jintao Rong, Xin Xie, Xinyi Yu, Linlin Ou, Xinyu Zhang, Chunhua Shen, Dong Gong*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2506.19348) / [Project](https://euminds.github.io/motionecho/) 

**EchoShot: Multi-Shot Portrait Video Generation**<br>
*Jiahao Wang, Hualian Sheng, Sijia Cai, Weizhan Zhang, Caixia Yan, Yachuang Feng, Bing Deng, Jieping Ye*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2506.15838) / [Project](https://johnneywang.github.io/EchoShot-webpage/) / [Code](https://github.com/JoHnneyWang/EchoShot)

**PolyVivid: Vivid Multi-Subject Video Generation with Cross-Modal Interaction and Enhancement**<br>
*Teng Hu, Zhentao Yu, Zhengguang Zhou, Jiangning Zhang, Yuan Zhou, Qinglin Lu, Ran Yi*<br>
NeurIPS 2025.  / [PDF](http://arxiv.org/abs/2506.07848) / [Project](https://sjtuplayer.github.io/projects/PolyVivid/)

**OpenS2V-Nexus: A Detailed Benchmark and Million-Scale Dataset for Subject-to-Video Generation**<br>
*Shenghai Yuan, Xianyi He, Yufan Deng, Yang Ye, Jinfa Huang, Bin Lin, Jiebo Luo, Li Yuan*<br>
NeurIPS 2025 D&B.  /  [PDF](https://arxiv.org/abs/2505.20292) / [Project](https://pku-yuangroup.github.io/OpenS2V-Nexus/) / [Code](https://github.com/PKU-YuanGroup/OpenS2V-Nexus)

**Identity-Preserving Text-to-Video Generation by Frequency Decomposition**<br>
*Shenghai Yuan, Jinfa Huang, Xianyi He, Yunyuan Ge, Yujun Shi, Liuhan Chen, Jiebo Luo, Li Yuan*<br>
CVPR 2025 (Highlight).  /  [PDF](https://arxiv.org/abs/2411.17440) / [Project](https://pku-yuangroup.github.io/ConsisID/) / [Code](https://github.com/PKU-YuanGroup/ConsisID)

**BridgeIV: Bridging Customized Image and Video Generation through Test-Time Autoregressive Identity Propagation**<br>
*Panwen Hu, Jiehui Huang, Qiang Sun, Xiaodan Liang*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2505.06985)

**HunyuanCustom: A Multimodal-Driven Architecture for Customized Video Generation**<br>
*Teng Hu, Zhentao Yu, Zhengguang Zhou, Sen Liang, Yuan Zhou, Qin Lin, Qinglin Lu*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2505.04512) / [Project](https://hunyuancustom.github.io/) / [Code](https://github.com/Tencent-Hunyuan/HunyuanCustom) / [Demo](https://hunyuan.tencent.com/modelSquare/home/play?modelId=192)

**DualReal: Adaptive Joint Training for Lossless Identity-Motion Fusion in Video Customization**<br>
*Wenchuan Wang, Mengqi Huang, Yijing Tu, Zhendong Mao*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2505.02192) / [Project](https://wenc-k.github.io/dualreal-customization/)

**Subject-driven Video Generation via Disentangled Identity and Motion**<br>
*Daneul Kim, Jingxu Zhang, Wonjoon Jin, Sunghyun Cho, Qi Dai, Jaesik Park, Chong Luo*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2504.17816) / [Project](https://carpedkm.github.io/projects/disentangled_sub/index.html) / [Code](https://github.com/carpedkm/disentangled-subject-to-vid)

**JointTuner: Appearance-Motion Adaptive Joint Training for Customized Video Generation**<br>
*Fangda Chen, Shanshan Zhao, Chuanfu Xu, Long Lan*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2503.23951) / [Project](https://fdchen24.github.io/JointTuner-Website/) 

**Any2Caption:Interpreting Any Condition to Caption for Controllable Video Generation**<br>
*Shengqiong Wu, Weicai Ye, Jiahao Wang, Quande Liu, Xintao Wang, Pengfei Wan, Di Zhang, Kun Gai, Shuicheng Yan, Hao Fei, Tat-Seng Chua*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2503.24379) / [Project](https://sqwu.top/Any2Cap/) / [Code](https://github.com/ChocoWu/Any2Caption)

**VideoMage: Multi-Subject and Motion Customization of Text-to-Video Diffusion Models**<br>
*Chi-Pin Huang, Yen-Siang Wu, Hung-Kai Chung, Kai-Po Chang, Fu-En Yang, Yu-Chiang Frank Wang*<br>
CVPR 2025. / [PDF](https://arxiv.org/abs/2503.21781) / [Project](https://jasper0314-huang.github.io/videomage-customization/)

**FullDiT: Multi-Task Video Generative Foundation Model with Full Attention**<br>
*Xuan Ju, Weicai Ye, Quande Liu, Qiulin Wang, Xintao Wang, Pengfei Wan, Di Zhang, Kun Gai, Qiang Xu*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2503.19907) / [Project](https://fulldit.github.io/)

**Concat-ID: Towards Universal Identity-Preserving Video Synthesis**<br>
*Yong Zhong, Zhuoyi Yang, Jiayan Teng, Xiaotao Gu, Chongxuan Li*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2503.14151) / [Project](https://ml-gsai.github.io/Concat-ID-demo/) / [Code](https://github.com/ML-GSAI/Concat-ID)

**MagicID: Hybrid Preference Optimization for ID-Consistent and Dynamic-Preserved Video Customization**<br>
*Hengjia Li, Lifan Jiang, Xi Xiao, Tianyang Wang, Hongwei Yi, Boxi Wu, Deng Cai*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2503.12689) / [Project](https://echopluto.github.io/MagicID-project/) / [Code](https://github.com/EchoPluto/MagicID)

**DreamInsert: Zero-Shot Image-to-Video Object Insertion from A Single Image**<br>
*Qi Zhao, Zhan Ma, Pan Zhou*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2503.10342) 

**DreamRelation: Relation-Centric Video Customization**<br>
*Yujie Wei, Shiwei Zhang, Hangjie Yuan, Biao Gong, Longxiang Tang, Xiang Wang, Haonan Qiu, Hengjia Li, Shuai Tan, Yingya Zhang, Hongming Shan*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2503.07602) / [Project](https://dreamrelation.github.io/) 

**FantasyID: Face Knowledge Enhanced ID-Preserving Video Generation**<br>
*Yunpeng Zhang, Qiang Wang, Fan Jiang, Yaqi Fan, Mu Xu, Yonggang Qi*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2502.13995) / [Project](https://fantasy-amap.github.io/fantasy-id/) / [Code](https://github.com/Fantasy-AMAP/fantasy-id)

**Dynamic Concepts Personalization from Single Videos**<br>
*Rameen Abdal, Or Patashnik, Ivan Skorokhodov, Willi Menapace, Aliaksandr Siarohin, Sergey Tulyakov, Daniel Cohen-Or, Kfir Aberman*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2502.14844) / [Project](https://snap-research.github.io/dynamic_concepts/)

**Phantom: Subject-consistent video generation via cross-modal alignment**<br>
*Lijie Liu, Tianxiang Ma, Bingchuan Li, Zhuowei Chen, Jiawei Liu, Qian He, Xinglong Wu*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2502.11079) / [Project](https://phantom-video.github.io/Phantom/) / [Code](https://github.com/Phantom-video/Phantom)

**CustomVideoX: 3D Reference Attention Driven Dynamic Adaptation for Zero-Shot Customized Video Diffusion Transformers**<br>
*D. She, Mushui Liu, Jingxuan Pang, Jin Wang, Zhen Yang, Wanggui He, Guanghao Zhang, Yi Wang, Qihan Huang, Haobin Tang, Yunlong Yu, Siming Fu*<br>
Arxiv 2025. / [PDF](https://www.arxiv.org/abs/2502.06527) / [Project](https://xiaobul.github.io/CustomVideoX/) / [Code](https://github.com/XiaoBuL/CustomVideoX-)

**Movie Weaver: Tuning-Free Multi-Concept Video Personalization with Anchored Prompts**<br>
*Feng Liang, Haoyu Ma, Zecheng He, Tingbo Hou, Ji Hou, Kunpeng Li, Xiaoliang Dai, Felix Juefei-Xu, Samaneh Azadi, Animesh Sinha, Peizhao Zhang, Peter Vajda, Diana Marculescu*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2502.07802) / [Project](https://jeff-liangf.github.io/projects/movieweaver/)

**DIVE: Taming DINO for Subject-Driven Video Editing**<br>
*Yi Huang, Wei Xiong, He Zhang, Chaoqi Chen, Jianzhuang Liu, Mingfu Yan, Shifeng Chen*<br>
Arxiv 2024. / [PDF](https://arxiv.org/abs/2412.03347) / [Project](https://dino-video-editing.github.io/)

**VideoMaker: Zero-shot Customized Video Generation with the Inherent Force of Video Diffusion Models**<br>
*Tao Wu, Yong Zhang, Xiaodong Cun, Zhongang Qi, Junfu Pu, Huanzhang Dou, Guangcong Zheng, Ying Shan, Xi Li*<br>
Arxiv 2024. / [PDF](https://arxiv.org/abs/2412.19645) / [Project](https://wutao-cs.github.io/VideoMaker/) / [Code](https://github.com/WuTao-CS/VideoMaker)

**MoTrans: Customized Motion Transfer with Text-driven Video Diffusion Models**<br>
*Xiaomin Li, Xu Jia, Qinghe Wang, Haiwen Diao, Mengmeng Ge, Pengxiang Li, You He, Huchuan Lu*<br>
Arxiv 2024. / [PDF](https://arxiv.org/abs/2412.01343) / [Code](https://github.com/XiaominLi1997/MoTrans)

**PersonalVideo: High ID-Fidelity Video Customization without Dynamic and Semantic Degradation**<br>
*Hengjia Li, Haonan Qiu, Shiwei Zhang, Xiang Wang, Yujie Wei, Zekun Li, Yingya Zhang, Boxi Wu, Deng Cai*<br>
Arxiv 2024. / [PDF](https://arxiv.org/abs/2411.17048) / [Project](https://personalvideo.github.io/) / [Code](https://github.com/EchoPluto/PersonalVideo)

**DreamRunner: Fine-Grained Storytelling Video Generation with Retrieval-Augmented Motion Adaptation**<br>
*Zun Wang, Jialu Li, Han Lin, Jaehong Yoon, Mohit Bansal*<br>
Arxiv 2024. / [PDF](https://arxiv.org/abs/2411.16657) / [Project](https://zunwang1.github.io/DreamRunner) / [Code](https://github.com/wz0919/DreamRunner)

**DreamVideo-2: Zero-Shot Subject-Driven Video Customization with Precise Motion Control**<br>
*Yujie Wei, Shiwei Zhang, Hangjie Yuan, Xiang Wang, Haonan Qiu, Rui Zhao, Yutong Feng, Feng Liu, Zhizhong Huang, Jiaxin Ye, Yingya Zhang, Hongming Shan*<br>
Arxiv 2024. / [PDF](https://arxiv.org/abs/2410.13830) / [Project](https://dreamvideo2.github.io/)

**CustomCrafter: Customized Video Generation with Preserving Motion and Concept Composition Abilities**<br>
*Tao Wu, Yong Zhang, Xintao Wang, Xianpan Zhou, Guangcong Zheng, Zhongang Qi, Ying Shan, Xi Li*<br>
AAAI 2025. / [PDF](https://arxiv.org/abs/2408.13239) / [Project](https://customcrafter.github.io/) / [Code](https://github.com/WuTao-CS/CustomCrafter)

**Text Prompting for Multi-Concept Video Customization by Autoregressive Generation**<br>
*Divya Kothandaraman, Kihyuk Sohn, Ruben Villegas, Paul Voigtlaender, Dinesh Manocha, Mohammad Babaeizadeh*<br>
CVPR 2024 AI4CC Workshop. / [PDF](https://arxiv.org/abs/2405.13951) 

**DisenStudio: Customized Multi-subject Text-to-Video Generation with Disentangled Spatial Control**<br>
*Hong Chen, Xin Wang, Yipeng Zhang, Yuwei Zhou, Zeyang Zhang, Siao Tang, Wenwu Zhu*<br>
Arxiv 2024. / [PDF](https://arxiv.org/abs/2405.12796) / [Project](https://forchchch.github.io/disenstudio.github.io/)

**Magic-Me: Identity-Specific Video Customized Diffusion**<br>
*Ze Ma, Daquan Zhou, Chun-Hsiao Yeh, Xue-She Wang, Xiuyu Li, Huanrui Yang, Zhen Dong, Kurt Keutzer, Jiashi Feng*<br>
Arxiv 2024. / [PDF](https://arxiv.org/abs/2402.09368) / [Project](https://magic-me-webpage.github.io/) / [Code](https://github.com/Zhen-Dong/Magic-Me)

**CustomVideo: Customizing Text-to-Video Generation with Multiple Subjects**<br>
*Zhao Wang, Aoxue Li, Lingting Zhu, Yong Guo, Qi Dou, Zhenguo Li*<br>
Arxiv 2024. / [PDF](https://arxiv.org/abs/2401.09962) / [Project](https://kyfafyd.wang/projects/customvideo/)

**VideoBooth: Diffusion-based Video Generation with Image Prompts**<br>
*Yuming Jiang, Tianxing Wu, Shuai Yang, Chenyang Si, Dahua Lin, Yu Qiao, Chen Change Loy, Ziwei Liu*<br>
CVPR 2024. / [PDF](https://arxiv.org/abs/2312.00777) / [Project](https://vchitect.github.io/VideoBooth-project/) / [Code](https://github.com/Vchitect/VideoBooth)

**Pia: Your personalized image animator via plug-and-play modules in text-to-image models**<br>
*Zhang, Yiming and Xing, Zhening and Zeng, Yanhong and Fang, Youqing and Chen, Kai.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2312.13964v3)  / [Project](https://pi-animator.github.io/)  / [Code](https://github.com/open-mmlab/PIA)

### Personalized 3D Generation

**MVCustom: Multi-View Customized Diffusion via Geometric Latent Rendering and Completion**<br>
*Minjung Shin, Hyunin Cho, Sooyeon Go, Jin-Hwa Kim, Youngjung Uh*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2510.13702) / [Project](https://minjung-s.github.io/mvcustom) / [Code](https://github.com/minjung-s/MVCustom)

**Personalize Your Gaussian: Consistent 3D Scene Personalization from a Single Image**<br>
*Yuxuan Wang, Xuanyu Yi, Qingshan Xu, Yuan Zhou, Long Chen, Hanwang Zhang*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2505.14537) / [Code]([https://github.com/NVlabs/dream-in-4d](https://github.com/Yuxuan-W/CP-GS))

**A Unified Approach for Text- and Image-guided 4D Scene Generation**<br>
*Yufeng Zheng, Xueting Li, Koki Nagano, Sifei Liu, Karsten Kreis, Otmar Hilliges, Shalini De Mello*<br>
CVPR 2024. / [PDF](https://arxiv.org/abs/2311.16854) / [Project](https://research.nvidia.com/labs/nxp/dream-in-4d/) / [Code](https://github.com/NVlabs/dream-in-4d)

**Animate124: Animating One Image to 4D Dynamic Scene**<br>
*Yuyang Zhao, Zhiwen Yan, Enze Xie, Lanqing Hong, Zhenguo Li, Gim Hee Lee*<br>
Arxiv 2023. / [PDF](https://arxiv.org/abs/2311.14603) / [Project](https://animate124.github.io/) / [Code](https://github.com/HeliosZhao/Animate124)

**Chasing Consistency in Text-to-3D Generation from a Single Image**<br>
*Yichen Ouyang, Wenhao Chai, Jiayi Ye, Dapeng Tao, Yibing Zhan, Gaoang Wang*<br>
Arxiv 2023. / [PDF](https://arxiv.org/abs/2309.03599)

**DreamBooth3D: Subject-Driven Text-to-3D Generation**<br>
*Amit Raj, Srinivas Kaza, Ben Poole, Michael Niemeyer, Nataniel Ruiz, Ben Mildenhall, Shiran Zada, Kfir Aberman, Michael Rubinstein, Jonathan Barron, Yuanzhen Li, Varun Jampani*<br>
ICCV 2023. / [PDF](https://arxiv.org/abs/2303.13508) / [Project](https://dreambooth3d.github.io/) 

### Text-driven Image Editing

**UniEdit-Flow: Unleashing Inversion and Editing in the Era of Flow Models**<br>
*Guanlong Jiao, Biqing Huang, Kuan-Chieh Wang, Renjie Liao*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2504.13109) / [Project](https://uniedit-flow.github.io/) 

**FreeFlux: Understanding and Exploiting Layer-Specific Roles in RoPE-Based MMDiT for Versatile Image Editing**<br>
*Tianyi Wei, Yifan Zhou, Dongdong Chen, Xingang Pan*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2503.16153) / [Project](https://wtybest.github.io/projects/FreeFlux/) / [Code](https://github.com/wtybest/FreeFlux)

**BlobCtrl: A Unified and Flexible Framework for Element-level Image Generation and Editing**<br>
*Yaowei Li, Lingen Li, Zhaoyang Zhang, Xiaoyu Li, Guangzhi Wang, Hongxiang Li, Xiaodong Cun, Ying Shan, Yuexian Zou*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2503.13434) / [Project](https://liyaowei-stu.github.io/project/BlobCtrl/) / [Code](https://github.com/TencentARC/BlobCtrl)

**Edit Transfer: Learning Image Editing via Vision In-Context Relations**<br>
*Lan Chen, Qi Mao, Yuchao Gu, Mike Zheng Shou*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2503.13327) / [Project](https://cuc-mipg.github.io/EditTransfer.github.io/) / [Code](https://github.com/CUC-MIPG/Edit-Transfer)

**Distilling Diversity and Control in Diffusion Models**<br>
*Rohit Gandikota, David Bau*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2503.10637) / [Project](https://distillation.baulab.info/) / [Code](https://github.com/rohitgandikota/distillation)

**EEdit : Rethinking the Spatial and Temporal Redundancy for Efficient Image Editing**<br>
*Zexuan Yan, Yue Ma, Chang Zou, Wenteng Chen, Qifeng Chen, Linfeng Zhang*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2503.10270) / [Code](https://github.com/yuriYanZeXuan/EEdit)

**Energy-Guided Optimization for Personalized Image Editing with Pretrained Text-to-Image Diffusion Models**<br>
*Rui Jiang, Xinghe Fu, Guangcong Zheng, Teng Li, Taiping Yao, Xi Li*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2503.04215)

**h-Edit: Effective and Flexible Diffusion-Based Editing via Doob's h-Transform**<br>
*Toan Nguyen, Kien Do, Duc Kieu, Thin Nguyen*<br>
CVPR 2025.  / [PDF](https://arxiv.org/abs/2503.02187) / [Code](https://github.com/nktoan/h-edit)

**KV-Edit: Training-Free Image Editing for Precise Background Preservation**<br>
*Tianrui Zhu, Shiyi Zhang, Jiawei Shao, Yansong Tang*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2502.17363)  / [Project](https://xilluill.github.io/projectpages/KV-Edit/) / [Code](https://github.com/Xilluill/KV-Edit)

**PartEdit: Fine-Grained Image Editing using Pre-Trained Diffusion Models**<br>
*Aleksandar Cvejic, Abdelrahman Eldesokey, Peter Wonka*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2502.04050)  / [Project](https://gorluxor.github.io/part-edit/) / [Code](https://github.com/Gorluxor/partedit)

**Stable Flow: Vital Layers for Training-Free Image Editing**<br>
*Avrahami, Omri and Patashnik, Or and Fried, Ohad and Nemchinov, Egor and Aberman, Kfir and Lischinski, Dani and Cohen-Or, Daniel.*<br>
CVPR 2025.  / [PDF](https://arxiv.org/abs/2411.14430)  / [Project](https://omriavrahami.com/stable-flow/)

**HeadRouter: A Training-free Image Editing Framework for MM-DiTs by Adaptively Routing Attention Heads**<br>
*Xu, Yu and Tang, Fan and Cao, Juan and Zhang, Yuxin and Kong, Xiaoyu and Li, Jintao and Deussen, Oliver and Lee, Tong-Yee.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2411.15034)  / [Project](https://yuci-gpt.github.io/headrouter/)  / [Code](https://github.com/ICTMCG/HeadRouter)

**Unveil Inversion and Invariance in Flow Transformer for Versatile Image Editing**<br>
*Xu, Pengcheng and Jiang, Boyuan and Hu, Xiaobin and Luo, Donghao and He, Qingdong and Zhang, Jiangning and Wang, Chengjie and Wu, Yunsheng and Ling, Charles and Wang, Boyu.*<br>
CVPR 2025.  / [PDF](https://arxiv.org/abs/2411.15843)  / [Project](https://pengchengpcx.github.io/EditFT/)  / [Code](https://github.com/Pengchengpcx/FTEdit)

**GANTASTIC: GAN-based Transfer of Interpretable Directions for Disentangled Image Editing in Text-to-Image Diffusion Models**<br>
*Dalva, Yusuf and Yesiltepe, Hidir and Yanardag, Pinar.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2403.19645)  / [Project](https://gantastic.github.io/)

**Ledits++: Limitless image editing using text-to-image models**<br>
*Brack, Manuel and Friedrich, Felix and Kornmeier, Katharina and Tsaban, Linoy and Schramowski, Patrick and Kersting, Kristian and Passos, Apolinário.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2311.16711)  / [Project](https://leditsplusplus-project.static.hf.space/index.html)  / [Code](https://github.com/huggingface/diffusers/tree/main/src/diffusers/pipelines/ledits_pp)

**An edit friendly ddpm noise space: Inversion and manipulations**<br>
*Huberman-Spiegelglas, Inbar and Kulikov, Vladimir and Michaeli, Tomer.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2304.06140)  / [Project](https://inbarhub.github.io/DDPM_inversion)  / [Code](https://github.com/inbarhub/DDPM_inversion)

**Delta denoising score**<br>
*Hertz, Amir and Aberman, Kfir and Cohen-Or, Daniel.*<br>
ICCV 2023.  / [PDF](https://arxiv.org/abs/2304.07090v1)  / [Project](https://delta-denoising-score.github.io/)  / [Code](https://github.com/google/prompt-to-prompt/blob/main/DDS_zeroshot.ipynb)

**Masactrl: Tuning-free mutual self-attention control for consistent image synthesis and editing**<br>
*Cao, Mingdeng and Wang, Xintao and Qi, Zhongang and Shan, Ying and Qie, Xiaohu and Zheng, Yinqiang.*<br>
ICCV 2023.  / [PDF](https://arxiv.org/abs/2304.08465v1)  / [Project](https://ljzycmd.github.io/projects/MasaCtrl)  / [Code](https://github.com/TencentARC/MasaCtrl)

**Null-text inversion for editing real images using guided diffusion models**<br>
*Mokady, Ron and Hertz, Amir and Aberman, Kfir and Pritch, Yael and Cohen-Or, Daniel.*<br>
CVPR 2023.  / [PDF](https://arxiv.org/abs/2211.09794v1)  / [Project](https://null-text-inversion.github.io)  / [Code](https://github.com/google/prompt-to-prompt/#null-text-inversion-for-editing-real-images)

**Prompt-to-prompt image editing with cross attention control**<br>
*Hertz, Amir and Mokady, Ron and Tenenbaum, Jay and Aberman, Kfir and Pritch, Yael and Cohen-Or, Daniel.*<br>
ICLR 2023.  / [PDF](https://arxiv.org/abs/2208.01626)  / [Project](https://prompt-to-prompt.github.io)  / [Code](https://github.com/google/prompt-to-prompt)

**Blended Latent Diffusion**<br>
*Avrahami, Omri and Fried, Ohad and Lischinski, Dani.*<br>
SIGGRAPH 2023.  / [PDF](https://arxiv.org/abs/2206.02779)  / [Project](https://omriavrahami.com/blended-latent-diffusion-page/)  / [Code](https://github.com/omriav/blended-latent-diffusion)

**Blended Diffusion: Text-driven Editing of Natural Images**<br>
*Avrahami, Omri and Lischinski, Dani and Fried, Ohad.*<br>
CVPR 2022.  / [PDF](https://arxiv.org/abs/2111.14818)  / [Project](https://omriavrahami.com/blended-diffusion-page/)  / [Code](https://github.com/omriav/blended-diffusion)

## Personalization with AR Models

**TokenAR: Multiple Subject Generation via Autoregressive Token-level enhancement**<br>
*Haiyue Sun, Qingdong He, Jinlong Peng, Peng Tang, Jiangning Zhang, Junwei Zhu, Xiaobin Hu, Shuicheng Yan*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2510.16332) / [Code](https://github.com/lyrig/TokenAR)


**CoAR: Concept Injection into Autoregressive Models for Personalized Text-to-Image Generation**<br>
*Fangtai Wu, Mushui Liu, Weijie He, Wanggui He, Hao Jiang, Zhao Wang, Yunlong Yu*<br>
Arxiv 2025.  / [PDF](http://arxiv.org/abs/2508.07341) / [Code](https://github.com/KZF-kzf/CoAR)

**Emerging Properties in Unified Multimodal Pretraining**<br>
*Chaorui Deng, Deyao Zhu, Kunchang Li, Chenhui Gou, Feng Li, Zeyu Wang, Shu Zhong, Weihao Yu, Xiaonan Nie, Ziang Song, Guang Shi, Haoqi Fan*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2505.14683) / [Project](https://bagel-ai.org/) / [Code](https://github.com/bytedance-seed/BAGEL) / [Demo](https://demo.bagel-ai.org/)

**UniCTokens: Boosting Personalized Understanding and Generation via Unified Concept Tokens**<br>
*Ruichuan An, Sihan Yang, Renrui Zhang, Zijun Shen, Ming Lu, Gaole Dai, Hao Liang, Ziyu Guo, Shilin Yan, Yulin Luo, Bocheng Zou, Chaoqun Yang, Wentao Zhang*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2505.14671) / [Code](https://github.com/arctanxarc/UniCTokens)

**Mogao: An Omni Foundation Model for Interleaved Multi-Modal Generation**<br>
*Chao Liao, Liyang Liu, Xun Wang, Zhengxiong Luo, Xinyu Zhang, Wenliang Zhao, Jie Wu, Liang Li, Zhi Tian, Weilin Huang*<br>
Arxiv 2025.  / [PDF](https://www.arxiv.org/abs/2505.05472)

**Context-Aware Autoregressive Models for Multi-Conditional Image Generation**<br>
*Yixiao Chen, Zhiyuan Ma, Guoli Jia, Che Jiang, Jianjun Li, Bowen Zhou*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2505.12274) / [Project](https://context-ar.github.io/)

**Nexus-Gen: A Unified Model for Image Understanding, Generation, and Editing**<br>
*Hong Zhang, Zhongjie Duan, Xingjun Wang, Yuze Zhao, Weiyi Lu, Zhipeng Di, Yixuan Xu, Yingda Chen, Yu Zhang*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2504.21356) / [Code](https://github.com/modelscope/Nexus-Gen)

**YoChameleon: Personalized Vision and Language Generation**<br>
*Thao Nguyen, Krishna Kumar Singh, Jing Shi, Trung Bui, Yong Jae Lee, Yuheng Li*<br>
CVPR 2025.  / [PDF](https://arxiv.org/abs/2504.20998) / [Project](https://thaoshibe.github.io/YoChameleon/) / [Code](https://github.com/WisconsinAIVision/YoChameleon) / [Dataset](https://huggingface.co/datasets/thaoshibe/Mini-YoChameleon-Data)

**Personalized Text-to-Image Generation with Auto-Regressive Models**<br>
*Kaiyue Sun, Xian Liu, Yao Teng, Xihui Liu*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2504.13162) / [Code](https://github.com/KaiyueSun98/T2I-Personalization-with-AR)

**Transfer between Modalities with MetaQueries**<br>
*Xichen Pan, Satya Narayan Shukla, Aashu Singh, Zhuokai Zhao, Shlok Kumar Mishra, Jialiang Wang, Zhiyang Xu, Jiuhai Chen, Kunpeng Li, Felix Juefei-Xu, Ji Hou, Saining Xie*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2504.06256) / [Project](https://xichenpan.com/metaquery/)

**Fine-Tuning Visual Autoregressive Models for Subject-Driven Generation**<br>
*Jiwoo Chung, Sangeek Hyun, Hyunjun Kim, Eunseo Koh, MinKyu Lee, Jae-Pil Heo*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2504.02612) / [Code](https://github.com/jiwoogit/ARBooth)

**ILLUME+: Illuminating Unified MLLM with Dual Visual Tokenization and Diffusion Refinement**<br>
*Runhui Huang, Chunwei Wang, Junwei Yang, Guansong Lu, Yunlong Yuan, Jianhua Han, Lu Hou, Wei Zhang, Lanqing Hong, Hengshuang Zhao, Hang Xu*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2504.01934) / [Project](https://illume-unified-mllm.github.io/) / [Code](https://github.com/illume-unified-mllm/ILLUME_plus)

**Unified Autoregressive Visual Generation and Understanding with Continuous Tokens**<br>
*Lijie Fan, Luming Tang, Siyang Qin, Tianhong Li, Xuan Yang, Siyuan Qiao, Andreas Steiner, Chen Sun, Yuanzhen Li, Tao Zhu, Michael Rubinstein, Michalis Raptis, Deqing Sun, Radu Soricut*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2503.13436)

**Proxy-Tuning: Tailoring Multimodal Autoregressive Models for Subject-Driven Image Generation**<br>
*Yi Wu, Lingting Zhu, Lei Liu, Wandi Qiao, Ziqiang Li, Lequan Yu, Bin Li*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/pdf/2503.10125)

**ILLUME: Illuminating Your LLMs to See, Draw, and Self-Enhance**<br>
*Wang, Chunwei and Lu, Guansong and Yang, Junwei and Huang, Runhui and Han, Jianhua and Hou, Lu and Zhang, Wei and Xu, Hang.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2412.06673)

**MetaMorph: Multimodal Understanding and Generation via Instruction Tuning**<br>
*Tong, Shengbang and Fan, David and Zhu, Jiachen and Xiong, Yunyang and Chen, Xinlei and Sinha, Koustuv and Rabbat, Michael and LeCun, Yann and Xie, Saining and Liu, Zhuang.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2412.14164)  / [Project](https://tsb0601.github.io/metamorph/)

**Liquid: Language Models are Scalable Multi-modal Generators**<br>
*Wu, Junfeng and Jiang, Yi and Ma, Chuofan and Liu, Yuliang and Zhao, Hengshuang and Yuan, Zehuan and Bai, Song and Bai, Xiang.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2412.04332) / [Project](https://foundationvision.github.io/Liquid/) / [Code](https://github.com/FoundationVision/Liquid)

**X-Prompt: Towards Universal In-Context Image Generation in Auto-Regressive Vision Language Foundation Models**<br>
*Sun, Zeyi and Chu, Ziyang and Zhang, Pan and Wu, Tong and Dong, Xiaoyi and Zang, Yuhang and Xiong, Yuanjun and Lin, Dahua and Wang, Jiaqi.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2412.01824)  / [Code](https://github.com/SunzeY/X-Prompt)

**Puma: Empowering unified mllm with multi-granular visual generation**<br>
*Fang, Rongyao and Duan, Chengqi and Wang, Kun and Li, Hao and Tian, Hao and Zeng, Xingyu and Zhao, Rui and Dai, Jifeng and Li, Hongsheng and Liu, Xihui.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2410.13861)  / [Project](https://rongyaofang.github.io/puma/)  / [Code](https://github.com/rongyaofang/PUMA)

**Emu3: Next-token prediction is all you need**<br>
*Wang, Xinlong and Zhang, Xiaosong and Luo, Zhengxiong and Sun, Quan and Cui, Yufeng and Wang, Jinsheng and Zhang, Fan and Wang, Yueze and Li, Zhen and Yu, Qiying and {others}.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2409.18869)  / [Project](https://emu.baai.ac.cn/about)  / [Code](https://github.com/baaivision/Emu3)

**Show-o: One Single Transformer to Unify Multimodal Understanding and Generation**<br>
*Jinheng Xie, Weijia Mao, Zechen Bai, David Junhao Zhang, Weihao Wang, Kevin Qinghong Lin, Yuchao Gu, Zhijie Chen, Zhenheng Yang, Mike Zheng Shou*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2408.12528)  / [Project](https://showlab.github.io/Show-o/) / [Code](https://github.com/showlab/Show-o) / [Demo](https://huggingface.co/spaces/showlab/Show-o)

**Chameleon: Mixed-modal early-fusion foundation models**<br>
*Team, Chameleon.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2405.09818)

**Seed-x: Multimodal models with unified multi-granularity comprehension and generation**<br>
*Ge, Yuying and Zhao, Sijie and Zhu, Jinguo and Ge, Yixiao and Yi, Kun and Song, Lin and Li, Chen and Ding, Xiaohan and Shan, Ying.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2404.14396)  / [Code](https://github.com/AILab-CVC/SEED-X)

**Generative multimodal models are in-context learners**<br>
*Sun, Quan and Cui, Yufeng and Zhang, Xiaosong and Zhang, Fan and Yu, Qiying and Luo, Zhengxiong and Wang, Yueze and Rao, Yongming and Liu, Jingjing and Huang, Tiejun and Wang, Xinlong.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2312.13286)  / [Project](https://baaivision.github.io/emu2/)  / [Code](https://github.com/baaivision/Emu)

**Next-gpt: Any-to-any multimodal llm**<br>
*Wu, Shengqiong and Fei, Hao and Qu, Leigang and Ji, Wei and Chua, Tat-Seng.*<br>
ICML 2024.  / [PDF](https://arxiv.org/abs/2309.05519)  / [Project](https://next-gpt.github.io/)  / [Code](https://github.com/NExT-GPT/NExT-GPT)

**Emu: Generative pretraining in multimodality**<br>
*Sun, Quan and Yu, Qiying and Cui, Yufeng and Zhang, Fan and Zhang, Xiaosong and Wang, Yueze and Gao, Hongcheng and Liu, Jingjing and Huang, Tiejun and Wang, Xinlong.*<br>
ICLR 2024.  / [PDF](https://arxiv.org/abs/2307.05222v2)  / [Code](https://github.com/baaivision/Emu)

## Personalization with GANs 

### GAN Inversion

**Spatially-adaptive multilayer selection for gan inversion and editing**<br>
*Parmar, Gaurav and Li, Yijun and Lu, Jingwan and Zhang, Richard and Zhu, Jun-Yan and Singh, Krishna Kumar.*<br>
CVPR 2022.  / [PDF](https://arxiv.org/abs/2206.08357v1)  / [Project](https://www.cs.cmu.edu/~SAMInversion)  / [Code](https://github.com/adobe-research/sam_inversion)

**Mystyle: A personalized generative prior**<br>
*Nitzan, Yotam and Aberman, Kfir and He, Qiurui and Liba, Orly and Yarom, Michal and Gandelsman, Yossi and Mosseri, Inbar and Pritch, Yael and Cohen-Or, Daniel.*<br>
SIGGRAPH ASIA 2022.  / [PDF](https://arxiv.org/abs/2203.17272)  / [Project](https://mystyle-personalized-prior.github.io)  / [Code](https://github.com/google/mystyle)

**Style transformer for image inversion and editing**<br>
*Hu, Xueqi and Huang, Qiusheng and Shi, Zhengyi and Li, Siyuan and Gao, Changxin and Sun, Li and Li, Qingli.*<br>
CVPR 2022.  / [PDF](https://arxiv.org/abs/2203.07932v1)  / [Code](https://github.com/sapphire497/style-transformer)

**Near perfect gan inversion**<br>
*Feng, Qianli and Shah, Viraj and Gadde, Raghudeep and Perona, Pietro and Martinez, Aleix.*<br>
Arxiv 2022.  / [PDF](https://arxiv.org/abs/2202.11833)

**Hyperinverter: Improving stylegan inversion via hypernetwork**<br>
*Dinh, Tan M and Tran, Anh Tuan and Nguyen, Rang and Hua, Binh-Son.*<br>
CVPR 2022.  / [PDF](https://arxiv.org/abs/2112.00719)  / [Project](https://di-mi-ta.github.io/HyperInverter)  / [Code](https://github.com/VinAIResearch/HyperInverter)

**High-fidelity gan inversion for image attribute editing**<br>
*Wang, Tengfei and Zhang, Yong and Fan, Yanbo and Wang, Jue and Chen, Qifeng.*<br>
CVPR 2022.  / [PDF](https://arxiv.org/abs/2109.06590v4)  / [Project](https://tengfei-wang.github.io/HFGI)  / [Code](https://github.com/Tengfei-Wang/HFGI)

**Gan inversion for out-of-range images with geometric transformations**<br>
*Kang, Kyoungkook and Kim, Seongtae and Cho, Sunghyun.*<br>
ICCV 2021.  / [PDF](https://arxiv.org/abs/2108.08998v1)  / [Project](https://kkang831.github.io/assets/publications/9998_ICCV2021_BDInvert)  / [Code](https://github.com/kkang831/BDInvert_Release)

**Pivotal tuning for latent-based editing of real images**<br>
*Roich, Daniel and Mokady, Ron and Bermano, Amit H and Cohen-Or, Daniel.*<br>
ACM TOG 2022.  / [PDF](https://arxiv.org/abs/2106.05744)  / [Code](https://github.com/danielroich/PTI)

**E2Style: Improve the efficiency and effectiveness of StyleGAN inversion**<br>
*Wei, Tianyi and Chen, Dongdong and Zhou, Wenbo and Liao, Jing and Zhang, Weiming and Yuan, Lu and Hua, Gang and Yu, Nenghai.*<br>
TIP 2022.  / [PDF](https://arxiv.org/abs/2104.07661v2)  / [Code](https://github.com/wtybest/e2style)

**Restyle: A residual-based stylegan encoder via iterative refinement**<br>
*Alaluf, Yuval and Patashnik, Or and Cohen-Or, Daniel.*<br>
ICCV 2021.  / [PDF](https://arxiv.org/abs/2104.02699v2)  / [Project](https://yuval-alaluf.github.io/restyle-encoder)  / [Code](https://github.com/yuval-alaluf/restyle-encoder)

**Ensembling with deep generative views**<br>
*Chai, Lucy and Zhu, Jun-Yan and Shechtman, Eli and Isola, Phillip and Zhang, Richard.*<br>
CVPR 2021.  / [PDF](https://arxiv.org/abs/2104.14551v1)  / [Project](https://chail.github.io/gan-ensembling)  / [Code](https://github.com/chail/gan-ensembling)

**Designing an encoder for stylegan image manipulation**<br>
*Tov, Omer and Alaluf, Yuval and Nitzan, Yotam and Patashnik, Or and Cohen-Or, Daniel.*<br>
SIGGRAPH 2021.  / [PDF](https://arxiv.org/abs/2102.02766v1)  / [Code](https://github.com/omertov/encoder4editing)

**Improved stylegan embedding: Where are the good latents?**<br>
*Zhu, Peihao and Abdal, Rameen and Qin, Yipeng and Femiani, John and Wonka, Peter.*<br>
Arxiv 2020.  / [PDF](https://arxiv.org/abs/2012.09036)

**Style intervention: How to achieve spatial disentanglement with style-based generators?**<br>
*Liu, Yunfan and Li, Qi and Sun, Zhenan and Tan, Tieniu.*<br>
Arxiv 2020.  / [PDF](https://arxiv.org/abs/2011.09699)

**Encoding in style: a stylegan encoder for image-to-image translation**<br>
*Richardson, Elad and Alaluf, Yuval and Patashnik, Or and Nitzan, Yotam and Azar, Yaniv and Shapiro, Stav and Cohen-Or, Daniel.*<br>
CVPR 2021.  / [PDF](https://arxiv.org/abs/2008.00951v2)  / [Project](https://eladrich.github.io/pixel2style2pixel)  / [Code](https://github.com/eladrich/pixel2style2pixel)

**In-domain gan inversion for real image editing**<br>
*Zhu, Jiapeng and Shen, Yujun and Zhao, Deli and Zhou, Bolei.*<br>
ECCV 2020.  / [PDF](https://arxiv.org/abs/2004.00049v3)  / [Project](https://genforce.github.io/idinvert)  / [Code](https://github.com/genforce/idinvert_pytorch)

**Image2stylegan++: How to edit the embedded images?**<br>
*Abdal, Rameen and Qin, Yipeng and Wonka, Peter.*<br>
CVPR 2020.  / [PDF](https://arxiv.org/abs/1911.11544v2)

**Inverting layers of a large generator**<br>
*Bau, David and Zhu, Jun-Yan and Wulff, Jonas and Peebles, William and Strobelt, Hendrik and Zhou, Bolei and Torralba, Antonio.*<br>
ICLR 2019 Debugging Machine Learning Models Workshop.  / [PDF](https://debug-ml-iclr2019.github.io/cameraready/DebugML-19_paper_18.pdf)

**Image2stylegan: How to embed images into the stylegan latent space?**<br>
*Abdal, Rameen and Qin, Yipeng and Wonka, Peter.*<br>
ICCV 2019.  / [PDF](https://arxiv.org/abs/1904.03189v2)

**Invertibility of convolutional generative networks from partial measurements**<br>
*Ma, Fangchang and Ayaz, Ulas and Karaman, Sertac.*<br>
NIPS 2018.  / [PDF](https://proceedings.neurips.cc/paper/2018/hash/e0ae4561193dbf6e4cf7e8f4006948e3-Abstract.html)  / [Code](https://github.com/fangchangma/invert-generative-networks)

**Inverting the generator of a generative adversarial network**<br>
*Creswell, Antonia and Bharath, Anil Anthony.*<br>
IEEE TNNLS 2019.  / [PDF](https://ieeexplore.ieee.org/abstract/document/8520899)  / [Code](https://github.com/ToniCreswell/InvertingGAN)

**Solving linear inverse problems using gan priors: An algorithm with provable guarantees**<br>
*Shah, Viraj and Hegde, Chinmay.*<br>
IEEE ICASSP 2018.  / [PDF](https://arxiv.org/abs/1802.08406)

**Precise recovery of latent vectors from generative adversarial networks**<br>
*Lipton, Zachary C and Tripathi, Subarna.*<br>
ICLR 2017.  / [PDF](https://arxiv.org/abs/1702.04782)

**Generative visual manipulation on the natural image manifold**<br>
*Zhu, Jun-Yan and Krähenbühl, Philipp and Shechtman, Eli and Efros, Alexei A.*<br>
ECCV 2016.  / [PDF](https://arxiv.org/abs/1609.03552)  / [Project](https://www.cs.cmu.edu/~junyanz/projects/gvm)  / [Code](https://github.com/junyanz/iGAN)

**Unsupervised representation learning with deep convolutional generative adversarial networks**<br>
*Radford, Alec and Metz, Luke and Chintala, Soumith.*<br>
ICLR 2016.  / [PDF](https://arxiv.org/abs/1511.06434)

### Latent Editing

**HyperGAN-CLIP: A Unified Framework for Domain Adaptation, Image Synthesis and Manipulation**<br>
*Anees, Abdul Basit and Baykal, Ahmet Canberk and Kizil, Muhammed Burak and Ceylan, Duygu and Erdem, Erkut and Erdem, Aykut.*<br>
SIGGRAPH Asia 2024.  / [PDF](https://arxiv.org/abs/2411.12832v1)  / [Project](https://cyberiada.github.io/HyperGAN-CLIP)  / [Code](https://github.com/basitanees/HyperGAN-CLIP)

**Edit One for All: Interactive Batch Image Editing**<br>
*Nguyen, Thao and Ojha, Utkarsh and Li, Yuheng and Liu, Haotian and Lee, Yong Jae.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2401.10219)  / [Project](https://thaoshibe.github.io/edit-one-for-all/)  / [Code](https://github.com/WisconsinAIVision/edit-one-for-all)

**HyperEditor: Achieving Both Authenticity and Cross-Domain Capability in Image Editing via Hypernetworks**<br>
*Zhang, Hai and Wu, Chunwei and Cao, Guitao and Wang, Hailing and Cao, Wenming.*<br>
AAAI 2024.  / [PDF](https://arxiv.org/abs/2312.13537)

**Warping the residuals for image editing with stylegan**<br>
*Yildirim, Ahmet Burak and Pehlivan, Hamza and Dundar, Aysegul.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2312.11422)

**Exploring Attribute Variations in Style-based GANs using Diffusion Models**<br>
*Parihar, Rishubh and Balaji, Prasanna and Magazine, Raghav and Vora, Sarthak and Karmali, Tejan and Jampani, Varun and Babu, R Venkatesh.*<br>
NeurIPS 2023 Workshop on Diffusion Models.  / [PDF](https://arxiv.org/abs/2311.16052)

**Revisiting Latent Space of GAN Inversion for Real Image Editing**<br>
*Katsumata, Kai and Vo, Duc Minh and Liu, Bei and Nakayama, Hideki.*<br>
WACV 2024.  / [PDF](https://arxiv.org/abs/2307.08995)

**StylePrompter: All Styles Need Is Attention**<br>
*Zhuang, Chenyi and Gao, Pan and Smolic, Aljosa.*<br>
ACM MM 2023.  / [PDF](https://arxiv.org/abs/2307.16151v1)  / [Code](https://github.com/I2-Multimedia-Lab/StylePrompter)

**CLIP-guided StyleGAN Inversion for Text-driven Real Image Editing**<br>
*Baykal, Ahmet Canberk and Anees, Abdul Basit and Ceylan, Duygu and Erdem, Erkut and Erdem, Aykut and Yuret, Deniz.*<br>
ACM TOG 2023.  / [PDF](https://arxiv.org/abs/2307.08397v2)  / [Project](https://cyberiada.github.io/CLIPInverter)  / [Code](https://github.com/johnberg1/CLIPInverter)

**Drag your gan: Interactive point-based manipulation on the generative image manifold**<br>
*Pan, Xingang and Tewari, Ayush and Leimkühler, Thomas and Liu, Lingjie and Meka, Abhimitra and Theobalt, Christian.*<br>
SIGGRAPH 2023.  / [PDF](https://arxiv.org/abs/2305.10973)  / [Project](https://vcai.mpi-inf.mpg.de/projects/DragGAN)  / [Code](https://github.com/XingangPan/DragGAN)

**Deltaedit: Exploring text-free training for text-driven image manipulation**<br>
*Lyu, Yueming and Lin, Tianwei and Li, Fu and He, Dongliang and Dong, Jing and Tan, Tieniu.*<br>
CVPR 2023.  / [PDF](https://arxiv.org/abs/2303.06285)  / [Code](https://github.com/Yueming6568/DeltaEdit)

**One model to edit them all: Free-form text-driven image manipulation with semantic modulations**<br>
*Zhu, Yiming and Liu, Hongyu and Song, Yibing and Yuan, Ziyang and Han, Xintong and Yuan, Chun and Chen, Qifeng and Wang, Jue.*<br>
NeurIPS 2022.  / [PDF](https://arxiv.org/abs/2210.07883)  / [Code](https://github.com/kristen-rang/FFCLIP)

**Bridging clip and stylegan through latent alignment for image editing**<br>
*Zheng, Wanfeng and Li, Qiang and Guo, Xiaoyan and Wan, Pengfei and Wang, Zhongyuan.*<br>
Arxiv 2022.  / [PDF](https://arxiv.org/abs/2210.04506)

**clip2latent: Text driven sampling of a pre-trained stylegan using denoising diffusion and clip**<br>
*Pinkney, Justin NM and Li, Chuan.*<br>
BMVC 2022.  / [PDF](https://arxiv.org/abs/2210.02347)  / [Code](https://github.com/justinpinkney/clip2latent)

**CLIP-PAE: projection-augmentation embedding to extract relevant features for a disentangled, interpretable and controllable text-guided face manipulation**<br>
*Zhou, Chenliang and Zhong, Fangcheng and Öztireli, Cengiz.*<br>
SIGGRAPH 2023.  / [PDF](https://arxiv.org/abs/2210.03919)  / [Project](https://chenliang-zhou.github.io/CLIP-PAE)  / [Code](https://github.com/Chenliang-Zhou/CLIP-PAE)

**Rewriting geometric rules of a GAN.**<br>
*Wang, Sheng-Yu and Bau, David and Zhu, Jun-Yan.*<br>
SIGGRAPH 2022.  / [PDF](https://arxiv.org/abs/2207.14288v1)  / [Project](https://peterwang512.github.io/GANWarping)  / [Code](https://github.com/peterwang512/GANWarping)

**Towards diverse and faithful one-shot adaption of generative adversarial networks**<br>
*Zhang, Yabo and Yao, Mingshuai and Wei, Yuxiang and Ji, Zhilong and Bai, Jinfeng and Zuo, Wangmeng and {others}.*<br>
NeurIPS 2022.  / [PDF](https://arxiv.org/abs/2207.08736)  / [Code](https://github.com/YBYBZhang/DiFa)

**Contraclip: Interpretable gan generation driven by pairs of contrasting sentences**<br>
*Tzelepis, Christos and Oldfield, James and Tzimiropoulos, Georgios and Patras, Ioannis.*<br>
Arxiv 2022.  / [PDF](https://arxiv.org/abs/2206.02104)  / [Code](https://github.com/chi0tzp/ContraCLIP)

**Stylemc: Multi-channel based fast text-guided image generation and manipulation**<br>
*Kocasari, Umut and Dirik, Alara and Tiftikci, Mert and Yanardag, Pinar.*<br>
WACV 2022.  / [PDF](https://arxiv.org/abs/2112.08493v1)  / [Project](https://catlab-team.github.io/stylemc)  / [Code](https://github.com/catlab-team/stylemc)

**Hairclip: Design your hair by text and reference image**<br>
*Wei, Tianyi and Chen, Dongdong and Zhou, Wenbo and Liao, Jing and Tan, Zhentao and Yuan, Lu and Zhang, Weiming and Yu, Nenghai.*<br>
CVPR 2022.  / [PDF](https://arxiv.org/abs/2112.05142v2)  / [Code](https://github.com/wtybest/HairCLIP)

**Hyperstyle: Stylegan inversion with hypernetworks for real image editing**<br>
*Alaluf, Yuval and Tov, Omer and Mokady, Ron and Gal, Rinon and Bermano, Amit.*<br>
CVPR 2022.  / [PDF](https://arxiv.org/abs/2111.15666)  / [Project](https://yuval-alaluf.github.io/hyperstyle)  / [Code](https://github.com/yuval-alaluf/hyperstyle)

**One-shot generative domain adaptation**<br>
*Yang, Ceyuan and Shen, Yujun and Zhang, Zhiyi and Xu, Yinghao and Zhu, Jiapeng and Wu, Zhirong and Zhou, Bolei.*<br>
ICCV 2023.  / [PDF](https://arxiv.org/abs/2111.09876v1)  / [Project](https://genforce.github.io/genda)  / [Code](https://github.com/genforce/genda)

**Editgan: High-precision semantic image editing**<br>
*Ling, Huan and Kreis, Karsten and Li, Daiqing and Kim, Seung Wook and Torralba, Antonio and Fidler, Sanja.*<br>
NeurIPS 2021.  / [PDF](https://arxiv.org/abs/2111.03186v1)  / [Project](https://nv-tlabs.github.io/editGAN)  / [Code](https://github.com/nv-tlabs/editGAN_release)

**Predict, prevent, and evaluate: Disentangled text-driven image manipulation empowered by pre-trained vision-language model**<br>
*Xu, Zipeng and Lin, Tianwei and Tang, Hao and Li, Fu and He, Dongliang and Sebe, Nicu and Timofte, Radu and Van Gool, Luc and Ding, Errui.*<br>
CVPR 2022.  / [PDF](https://arxiv.org/abs/2111.13333v2)  / [Code](https://github.com/zipengxuc/PPE)

**Mind the gap: Domain gap control for single shot domain adaptation for generative adversarial networks**<br>
*Zhu, Peihao and Abdal, Rameen and Femiani, John and Wonka, Peter.*<br>
ICLR 2022.  / [PDF](https://arxiv.org/abs/2110.08398)  / [Project](https://zpdesu.github.io/MindTheGap)  / [Code](https://github.com/ZPdesu/MindTheGap)

**Warpedganspace: Finding non-linear rbf paths in gan latent space**<br>
*Tzelepis, Christos and Tzimiropoulos, Georgios and Patras, Ioannis.*<br>
ICCV 2021.  / [PDF](https://arxiv.org/abs/2109.13357v1)  / [Code](https://github.com/chi0tzp/WarpedGANSpace)

**Stylegan-nada: Clip-guided domain adaptation of image generators**<br>
*Gal, Rinon and Patashnik, Or and Maron, Haggai and Bermano, Amit H and Chechik, Gal and Cohen-Or, Daniel.*<br>
ACM TOG 2022.  / [PDF](https://arxiv.org/abs/2108.00946)  / [Project](https://stylegan-nada.github.io)  / [Code](https://github.com/rinongal/StyleGAN-nada)

**Styleclip: Text-driven manipulation of stylegan imagery**<br>
*Patashnik, Or and Wu, Zongze and Shechtman, Eli and Cohen-Or, Daniel and Lischinski, Dani.*<br>
ICCV 2021.  / [PDF](https://arxiv.org/abs/2103.17249v1)  / [Code](https://github.com/orpatashnik/StyleCLIP)

**The geometry of deep generative image models and its applications**<br>
*Wang, Binxu and Ponce, Carlos R.*<br>
ICLR 2021.  / [PDF](https://arxiv.org/abs/2101.06006)

**Hijack-gan: Unintended-use of pretrained, black-box gans**<br>
*Wang, Hui-Po and Yu, Ning and Fritz, Mario.*<br>
CVPR 2021.  / [PDF](https://arxiv.org/abs/2011.14107v3)  / [Code](https://github.com/hui-po-wang/hijackgan)

**Stylespace analysis: Disentangled controls for stylegan image generation**<br>
*Wu, Zongze and Lischinski, Dani and Shechtman, Eli.*<br>
CVPR 2021.  / [PDF](https://arxiv.org/abs/2011.12799v2)

**Styleflow: Attribute-conditioned exploration of stylegan-generated images using conditional continuous normalizing flows**<br>
*Abdal, Rameen and Zhu, Peihao and Mitra, Niloy J and Wonka, Peter.*<br>
ACM TOG 2021.  / [PDF](https://arxiv.org/abs/2008.02401)  / [Project](https://rameenabdal.github.io/StyleFlow)  / [Code](https://github.com/RameenAbdal/StyleFlow)

**The hessian penalty: A weak prior for unsupervised disentanglement**<br>
*Peebles, William and Peebles, John and Zhu, Jun-Yan and Efros, Alexei and Torralba, Antonio.*<br>
ECCV 2020.  / [PDF](https://arxiv.org/abs/2008.10599v1)  / [Project](https://www.wpeebles.com/hessian-penalty)  / [Code](https://github.com/wpeebles/hessian_penalty)

**Closed-form factorization of latent semantics in gans**<br>
*Shen, Yujun and Zhou, Bolei.*<br>
CVPR 2021.  / [PDF](https://arxiv.org/abs/2007.06600v4)  / [Project](https://genforce.github.io/sefa)  / [Code](https://github.com/genforce/sefa)

**Interfacegan: Interpreting the disentangled face representation learned by gans**<br>
*Shen, Yujun and Yang, Ceyuan and Tang, Xiaoou and Zhou, Bolei.*<br>
CVPR 2020.  / [PDF](https://arxiv.org/abs/2005.09635v2)  / [Project](https://genforce.github.io/interfacegan/)  / [Code](https://genforce.github.io/interfacegan)

**Ganspace: Discovering interpretable gan controls**<br>
*Härkönen, Erik and Hertzmann, Aaron and Lehtinen, Jaakko and Paris, Sylvain.*<br>
NeurIPS 2020.  / [PDF](https://arxiv.org/abs/2004.02546)  / [Code](https://github.com/harskish/ganspace)

**Stylegan2 distillation for feed-forward image manipulation**<br>
*Viazovetskyi, Yuri and Ivashkin, Vladimir and Kashin, Evgeny.*<br>
ECCV 2020.  / [PDF](https://arxiv.org/abs/2003.03581v2)  / [Code](https://github.com/EvgenyKashin/stylegan2-distillation)

**Unsupervised discovery of interpretable directions in the gan latent space**<br>
*Voynov, Andrey and Babenko, Artem.*<br>
ICML 2020.  / [PDF](https://arxiv.org/abs/2002.03754)  / [Code](https://github.com/anvoynov/GanLatentDiscovery)

**A spectral regularizer for unsupervised disentanglement**<br>
*Ramesh, Aditya and Choi, Youngduck and LeCun, Yann.*<br>
Arxiv 2018.  / [PDF](https://arxiv.org/abs/1812.01161)

## Related Benchmarks

**ImageBench**<br>
Public benchmark and comparison site for text-to-image models with side-by-side outputs, pass-rate summaries, and methodology pages.<br>
[Website](https://imagebench.ai)

## Related Surveys

**Personalized Generation In Large Model Era: A Survey**<br>
*Yiyan Xu, Jinghao Zhang, Alireza Salemi, Xinting Hu, Wenjie Wang, Fuli Feng, Hamed Zamani, Xiangnan He, Tat-Seng Chua*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2503.02614)

**Image Inversion: A Survey from GANs to Diffusion and Beyond**<br>
*Yinan Chen, Jiangning Zhang, Yali Bi, Xiaobin Hu, Teng Hu, Zhucun Xue, Ran Yi, Yong Liu, Ying Tai*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2502.11974)  / [Code](https://github.com/RyanChenYN/ImageInversion)

**Conditional Image Synthesis with Diffusion Models: A Survey**<br>
*Zhan, Zheyuan and Chen, Defang and Mei, Jian-Ping and Zhao, Zhenghe and Chen, Jiawei and Chen, Chun and Lyu, Siwei and Wang, Can.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2409.19365)  / [Code](https://github.com/zju-pi/Awesome-Conditional-Diffusion-Models)

**A Survey of Multimodal-Guided Image Editing with Text-to-Image Diffusion Models**<br>
*Shuai, Xincheng and Ding, Henghui and Ma, Xingjun and Tu, Rongcheng and Jiang, Yu-Gang and Tao, Dacheng.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2406.14555)  / [Code](https://github.com/xinchengshuai/Awesome-Image-Editing)

**A Survey on Personalized Content Synthesis with Diffusion Models**<br>
*Zhang, Xulu and Wei, Xiao-Yong and Zhang, Wengyu and Wu, Jinlin and Zhang, Zhaoxiang and Lei, Zhen and Li, Qing.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2405.05538)

**Controllable generation with text-to-image diffusion models: A survey**<br>
*Cao, Pu and Zhou, Feng and Song, Qing and Yang, Lu.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2403.04279)  / [Code](https://github.com/PRIV-Creation/Awesome-Controllable-T2I-Diffusion-Models)

**A Survey on Leveraging Pre-trained Generative Adversarial Networks for Image Editing and Restoration**<br>
*Ming Liu, Yuxiang Wei, Xiaohe Wu, Wangmeng Zuo, Lei Zhang*<br>
SCIS 2023. / [PDF](https://arxiv.org/abs/2207.10309) / [Code](https://github.com/csmliu/pretrained-GANs)

**GAN Inversion: A Survey**<br>
*Weihao Xia, Yulun Zhang, Yujiu Yang, Jing-Hao Xue, Bolei Zhou, Ming-Hsuan Yang*<br>
TPAMI 2022. / [PDF](https://arxiv.org/abs/2101.05278) / [Code](https://github.com/weihaox/GAN-Inversion)
