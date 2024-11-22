# awesome Backdoor Resources

#### Why Backdoor Learning?
Backdoor learning is an emerging research area focusing on the security issues in the training process of machine learning algorithms. It is critical for ensuring the safe adoption of third-party training resources or models in real-world applications.

## News
* 2023/7/24: Added ten ICLR'23 papers. All papers from this conference have been included.
* 2023/7/23: Added seven NeurIPS'22 papers and four AAAI'23 papers. All papers from these conferences are now included.

## Survey
- **Backdoor Learning: A Survey**  
  [Yiming Li, Yong Jiang, Zhifeng Li, and Shu-Tao Xia]  
  *IEEE Transactions on Neural Networks and Learning Systems*, 2022  
  [[pdf]](https://www.researchgate.net/publication/343006441_Backdoor_Learning_A_Survey)

- **Backdoor Attacks and Countermeasures on Deep Learning: A Comprehensive Review**  
  [Yansong Gao et al.]  
  arXiv, 2020  
  [[pdf]](https://arxiv.org/pdf/2007.10760.pdf)

- **Data Security for Machine Learning: Data Poisoning, Backdoor Attacks, and Defenses**  
  [Micah Goldblum et al.]  
  *IEEE Transactions on Pattern Analysis and Machine Intelligence*, 2022  
  [[pdf]](https://arxiv.org/pdf/2012.10544.pdf)

- **A Comprehensive Survey on Poisoning Attacks and Countermeasures in Machine Learning**  
  [Zhiyi Tian et al.]  
  *ACM Computing Surveys*, 2022  
  [[link]](https://dl.acm.org/doi/10.1145/3551636)

- **Backdoor Attacks and Defenses in Federated Learning: State-of-the-art, Taxonomy, and Future Directions**  
  [Xueluan Gong et al.]  
  *IEEE Wireless Communications*, 2022  
  [[link]](https://ieeexplore.ieee.org/abstract/document/9806416)

- **Backdoor Attacks against Voice Recognition Systems: A Survey**  
  [Baochen Yan, Jiahe Lan, and Zheng Yan]  
  arXiv, 2023  
  [[pdf]](https://arxiv.org/pdf/2307.13643)

- **A Survey of Neural Trojan Attacks and Defenses in Deep Learning**  
  [Jie Wang, Ghulam Mubashar Hassan, and Naveed Akhtar]  
  arXiv, 2022  
  [[pdf]](https://arxiv.org/pdf/2202.07183.pdf)

- **Threats to Pre-trained Language Models: Survey and Taxonomy**  
  [Shangwei Guo et al.]  
  arXiv, 2022  
  [[pdf]](https://arxiv.org/pdf/2202.06862.pdf)
 
以下是经过精简后的内容，保留了前沿且最值得关注的部分：

---

## Toolbox
- [BackdoorBox](https://github.com/THUYimingLi/BackdoorBox)
- [TrojanZoo](https://github.com/ain-soph/trojanzoo)
- [OpenBackdoor](https://github.com/thunlp/OpenBackdoor)
- [BackdoorBench](https://github.com/SCLBD/BackdoorBench)
- [ART (Adversarial Robustness Toolbox)](https://github.com/Trusted-AI/adversarial-robustness-toolbox)

## Dissertation and Thesis
- **Poisoning-based Backdoor Attacks in Computer Vision**  
  [[pdf]](https://www.researchgate.net/publication/370233769_Poisoning-based_Backdoor_Attacks_in_Computer_Vision)  
  - *Yiming Li, Ph.D. Dissertation, Tsinghua University, 2023*

- **Un-fair Trojan: Targeted Backdoor Attacks against Model Fairness**  
  [[pdf]](https://digitalcommons.njit.edu/cgi/viewcontent.cgi?article=3010&context=theses)  
  - *Nicholas Furth, Master Thesis, New Jersey Institute of Technology, 2022*

- **Check Your Other Door: Creating Backdoor Attacks in the Frequency Domain**  
  [[pdf]](file:///C:/Users/Rainbow/Downloads/Thesis_Hasan_Hammoud.pdf)  
  - *Hasan Abed Al Kader Hammoud, Master Thesis, King Abdullah University of Science and Technology, 2022*

- **Detecting Backdoored Neural Networks with Structured Adversarial Attacks**  
  [[pdf]](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2021/EECS-2021-90.pdf)  
  - *Charles Yang, Master Thesis, University of California at Berkeley, 2021*

- **Geometric Properties of Backdoored Neural Networks**  
  [[pdf]](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2021/EECS-2021-78.pdf)  
  - *Dominic Carrano, Master Thesis, University of California at Berkeley, 2021*

## Image and Video Classification
### Poisoning-based Attack
#### 2023
- **Revisiting the Assumption of Latent Separability for Backdoor Defenses**
  [[pdf]](https://openreview.net/pdf?id=_wSHsgrVali)
  [[code]](https://github.com/Unispac/Circumventing-Backdoor-Defenses)
  - Xiangyu Qi, Tinghao Xie, Yiming Li, Saeed Mahloujifar, and Prateek Mittal. *ICLR*, 2023.

- **Few-shot Backdoor Attacks via Neural Tangent Kernels**
  [[pdf]](https://openreview.net/pdf?id=a70lGJ-rwy)
  [[code]](https://github.com/SewoongLab/ntk-backdoor)
  - Jonathan Hayase and Sewoong Oh. *ICLR*, 2023.

- **Color Backdoor: A Robust Poisoning Attack in Color Space**
  [[pdf]](https://openaccess.thecvf.com/content/CVPR2023/papers/Jiang_Color_Backdoor_A_Robust_Poisoning_Attack_in_Color_Space_CVPR_2023_paper.pdf)
  - Wenbo Jiang, Hongwei Li, Guowen Xu, and Tianwei Zhang. *CVPR*, 2023.


#### 2022
- **Untargeted Backdoor Watermark: Towards Harmless and Stealthy Dataset Copyright Protection**
  [[pdf]](https://www.researchgate.net/publication/363766436_Untargeted_Backdoor_Watermark_Towards_Harmless_and_Stealthy_Dataset_Copyright_Protection)
  [[code]](https://github.com/THUYimingLi/Untargeted_Backdoor_Watermark)
  - Yiming Li, Yang Bai, Yong Jiang, Yong Yang, Shu-Tao Xia, and Bo Li. *NeurIPS*, 2022.

- **DEFEAT: Deep Hidden Feature Backdoor Attacks by Imperceptible Perturbation and Latent Representation Constraints**
  [[pdf]](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhao_DEFEAT_Deep_Hidden_Feature_Backdoor_Attacks_by_Imperceptible_Perturbation_and_CVPR_2022_paper.pdf)
  - Zhendong Zhao, Xiaojun Chen, Yuexin Xuan, Ye Dong, Dakui Wang, and Kaitai Liang. *CVPR*, 2022.

- **Marksman Backdoor: Backdoor Attacks with Arbitrary Target Class**
  [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2022/file/fa0126bb7ebad258bf4ffdbbac2dd787-Paper-Conference.pdf)
  - Khoa D Doan, Yingjie Lao, and Ping Li. *NeurIPS*, 2022.

- **An Invisible Black-box Backdoor Attack through Frequency Domain**
  [[pdf]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136730396.pdf)
  [[code]](https://github.com/SoftWiser-group/FTrojan)
  - Tong Wang, Yuan Yao, Feng Xu, Shengwei An, Hanghang Tong, and Ting Wang. *ECCV*, 2022.

- **BppAttack: Stealthy and Efficient Trojan Attacks against Deep Neural Networks via Image Quantization and Contrastive Adversarial Learning**
  [[pdf]](https://arxiv.org/pdf/2205.13383.pdf)
  [[code]](https://github.com/RU-System-Software-and-Security/BppAttack)
  - Zhenting Wang, Juan Zhai, and Shiqing Ma. *CVPR*, 2022.

- **Dynamic Backdoor Attacks Against Machine Learning Models**
  [[pdf]](https://arxiv.org/pdf/2003.03675.pdf)
  - Ahmed Salem, Rui Wen, Michael Backes, Shiqing Ma, and Yang Zhang. *EuroS&P*, 2022. 

- **Imperceptible Backdoor Attack: From Input Space to Feature Representation**
  [[pdf]](https://arxiv.org/pdf/2205.03190.pdf)
  [[code]](https://github.com/Ekko-zn/IJCAI2022-Backdoor)
  - Nan Zhong, Zhenxing Qian, and Xinpeng Zhang. *IJCAI*, 2022.

Certainly! Here's the updated content, with only the most relevant and cutting-edge research preserved:

---

#### 2021
- **Invisible Backdoor Attack with Sample-Specific Triggers.**  
  [[pdf]](https://arxiv.org/pdf/2012.03816.pdf) [[code]](https://github.com/yuezunli/ISSBA)  
  Yuezun Li, Yiming Li, Baoyuan Wu, Longkang Li, Ran He, and Siwei Lyu. *ICCV*, 2021.

- **Manipulating SGD with Data Ordering Attacks.**  
  [[pdf]](https://arxiv.org/pdf/2104.09667.pdf)  
  Ilia Shumailov, Zakhar Shumaylov, Dmitry Kazhdan, Yiren Zhao, Nicolas Papernot, Murat A. Erdogdu, and Ross Anderson. *NeurIPS*, 2021.

- **Backdoor Attack with Imperceptible Input and Latent Modification.**  
  [[pdf]](https://proceedings.neurips.cc/paper/2021/file/9d99197e2ebf03fc388d09f1e94af89b-Paper.pdf)  
  Khoa Doan, Yingjie Lao, and Ping Li. *NeurIPS*, 2021.

- **LIRA: Learnable, Imperceptible and Robust Backdoor Attacks.**  
  [[pdf]](https://openaccess.thecvf.com/content/ICCV2021/papers/Doan_LIRA_Learnable_Imperceptible_and_Robust_Backdoor_Attacks_ICCV_2021_paper.pdf)  
  Khoa Doan, Yingjie Lao, Weijie Zhao, and Ping Li. *ICCV*, 2021.

- **Blind Backdoors in Deep Learning Models.**  
  [[pdf]](https://arxiv.org/pdf/2005.03823.pdf) [[code]](https://github.com/ebagdasa/backdoors101)  
  Eugene Bagdasaryan, and Vitaly Shmatikov. *USENIX Security*, 2021.

- **Deep Feature Space Trojan Attack of Neural Networks by Controlled Detoxification.**  
  [[pdf]](https://arxiv.org/pdf/2012.11212.pdf) [[code]](https://github.com/Megum1/DFST)  
  Siyuan Cheng, Yingqi Liu, Shiqing Ma, and Xiangyu Zhang. *AAAI*, 2021.

- **WaNet - Imperceptible Warping-based Backdoor Attack.**  
  [[pdf]](https://openreview.net/pdf?id=eEn8KTtJOx) [[code]](https://github.com/VinAIResearch/Warping-based_Backdoor_Attack-release)  
  Tuan Anh Nguyen, and Anh Tuan Tran. *ICLR*, 2021.

- **Sleeper Agent: Scalable Hidden Trigger Backdoors for Neural Networks Trained from Scratch.**  
  [[pdf]](https://arxiv.org/pdf/2106.08970.pdf) [[code]](https://github.com/hsouri/Sleeper-Agent)  
  Hossein Souri, Micah Goldblum, Liam Fowl, Rama Chellappa, and Tom Goldstein. arXiv, 2021.

- **Robust Backdoor Attacks against Deep Neural Networks in Real Physical World.**  
  [[pdf]](https://arxiv.org/pdf/2104.07395.pdf)  
  Mingfu Xue, Can He, Shichang Sun, Jian Wang, and Weiqiang Liu. arXiv, 2021.


更新后的内容如下，删除了过时、无用、广告及非前沿内容，保留了值得关注的最新研究成果：

### Non-poisoning-based Attack 
#### Weights-oriented Attack
- Handcrafted Backdoors in Deep Neural Networks.
  [[pdf]](https://openreview.net/pdf?id=6yuil2_tn9a)
  - Sanghyun Hong, Nicholas Carlini, and Alexey Kurakin. *NeurIPS*, 2022.

- Hardly Perceptible Trojan Attack against Neural Networks with Bit Flips.
  [[pdf]](https://arxiv.org/pdf/2207.13417.pdf)
  [[code]](https://github.com/jiawangbai/HPT)
  - Jiawang Bai, Kuofeng Gao, Dihong Gong, Shu-Tao Xia, Zhifeng Li, and Wei Liu. *ECCV*, 2022.

- How to Inject Backdoors with Better Consistency: Logit Anchoring on Clean Data.
  [[pdf]](https://arxiv.org/pdf/2109.01300.pdf)
  - Zhiyuan Zhang, Lingjuan Lyu, Weiqiang Wang, Lichao Sun, and Xu Sun. *ICLR*, 2022.

- Versatile Weight Attack via Flipping Limited Bits.
  [[pdf]](https://arxiv.org/pdf/2207.12405.pdf)
  - Jiawang Bai, Baoyuan Wu, Zhifeng Li, and Shu-Tao Xia. arXiv, 2022.

- Toward Realistic Backdoor Injection Attacks on DNNs using Rowhammer.
  [[pdf]](https://www.researchgate.net/profile/Saad-Islam-3/publication/355367637_Toward_Realistic_Backdoor_Injection_Attacks_on_DNNs_using_Rowhammer/links/62222bd93c53d31ba4a674a5/Toward-Realistic-Backdoor-Injection-Attacks-on-DNNs-using-Rowhammer.pdf)
  - M. Caner Tol, Saad Islam, Berk Sunar, and Ziming Zhang. 2022.

#### Structure-modified Attack
- LoneNeuron: a Highly-Effective Feature-Domain Neural Trojan Using Invisible and Polymorphic Watermarks.
  [[pdf]](https://www.ittc.ku.edu/~bluo/download/liu2022ccs.pdf)
  - Zeyan Liu, Fengjun Li, Zhu Li, and Bo Luo. *CCS*, 2022.

- Towards Practical Deployment-Stage Backdoor Attack on Deep Neural Networks.
  [[pdf]](https://arxiv.org/pdf/2111.12965.pdf)
  [[code]](https://github.com/Unispac/Subnet-Replacement-Attack)
  - Xiangyu Qi, Tinghao Xie, Ruizhe Pan, Jifeng Zhu, Yong Yang, and Kai Bu. *CVPR*, 2022.

- Hiding Needles in a Haystack: Towards Constructing Neural Networks that Evade Verification.
  [[link]](https://dl.acm.org/doi/10.1145/3531536.3532966)
  [[code]](https://github.com/szegedai/hiding-needles-in-a-haystack)
  - Árpád Berta, Gábor Danner, István Hegedűs, and Márk Jelasity. *ACM IH&MMSec*, 2022.

- FooBaR: Fault Fooling Backdoor Attack on Neural Network Training.
  [[link]](https://ieeexplore.ieee.org/document/9756234)
  [[code]](https://github.com/martin-ochoa/foobar)
  - Jakub Breier, Xiaolu Hou, Martín Ochoa, and Jesus Solano. *IEEE Transactions on Dependable and Secure Computing*, 2022.

- BadRes: Reveal the Backdoors through Residual Connection.
  [[pdf]](https://arxiv.org/pdf/2209.07125.pdf)
  - Mingrui He, Tianyu Chen, Haoyi Zhou, Shanghang Zhang, and Jianxin Li. arXiv, 2022.

- Architectural Backdoors in Neural Networks.
  [[pdf]](https://arxiv.org/pdf/2206.07840.pdf)
  - Mikel Bober-Irizar, Ilia Shumailov, Yiren Zhao, Robert Mullins, and Nicolas Papernot. arXiv, 2022.

- Planting Undetectable Backdoors in Machine Learning Models.
  [[pdf]](https://arxiv.org/pdf/2204.06974.pdf)
  - Shafi Goldwasser, Michael P. Kim, Vinod Vaikuntanathan, and Or Zamir. arXiv, 2022.

以下是更新后的内容，仅保留最前沿和最值得关注的研究成果：

### Non-poisoning-based Attack 
#### Weights-oriented Attack
- **Handcrafted Backdoors in Deep Neural Networks.**  
  *Sanghyun Hong, Nicholas Carlini, Alexey Kurakin.* NeurIPS, 2022.  
  [[pdf]](https://openreview.net/pdf?id=6yuil2_tn9a)

- **Hardly Perceptible Trojan Attack against Neural Networks with Bit Flips.**  
  *Jiawang Bai, Kuofeng Gao, Dihong Gong, Shu-Tao Xia, Zhifeng Li, Wei Liu.* ECCV, 2022.  
  [[pdf]](https://arxiv.org/pdf/2207.13417.pdf) [[code]](https://github.com/jiawangbai/HPT)

- **ProFlip: Targeted Trojan Attack with Progressive Bit Flips.**  
  *Huili Chen, Cheng Fu, Jishen Zhao, Farinaz Koushanfar.* ICCV, 2021.  
  [[pdf]](https://openaccess.thecvf.com/content/ICCV2021/papers/Chen_ProFlip_Targeted_Trojan_Attack_With_Progressive_Bit_Flips_ICCV_2021_paper.pdf)

- **How to Inject Backdoors with Better Consistency: Logit Anchoring on Clean Data.**  
  *Zhiyuan Zhang, Lingjuan Lyu, Weiqiang Wang, Lichao Sun, Xu Sun.* ICLR, 2022.  
  [[pdf]](https://arxiv.org/pdf/2109.01300.pdf)

- **Toward Realistic Backdoor Injection Attacks on DNNs using Rowhammer.**  
  *M. Caner Tol, Saad Islam, Berk Sunar, Ziming Zhang.* 2022.  
  [[pdf]](https://www.researchgate.net/profile/Saad-Islam-3/publication/355367637_Toward_Realistic_Backdoor_Injection_Attacks_on_DNNs_using_Rowhammer/links/62222bd93c53d31ba4a674a5/Toward-Realistic-Backdoor-Injection-Attacks-on-DNNs-using-Rowhammer.pdf)

#### Structure-modified Attack
- **LoneNeuron: a Highly-Effective Feature-Domain Neural Trojan Using Invisible and Polymorphic Watermarks.**  
  *Zeyan Liu, Fengjun Li, Zhu Li, Bo Luo.* CCS, 2022.  
  [[pdf]](https://www.ittc.ku.edu/~bluo/download/liu2022ccs.pdf)

- **Towards Practical Deployment-Stage Backdoor Attack on Deep Neural Networks.**  
  *Xiangyu Qi, Tinghao Xie, Ruizhe Pan, Jifeng Zhu, Yong Yang, Kai Bu.* CVPR, 2022.  
  [[pdf]](https://arxiv.org/pdf/2111.12965.pdf) [[code]](https://github.com/Unispac/Subnet-Replacement-Attack)

- **Hiding Needles in a Haystack: Towards Constructing Neural Networks that Evade Verification.**  
  *Árpád Berta, Gábor Danner, István Hegedűs, Márk Jelasity.* ACM IH&MMSec, 2022.  
  [[link]](https://dl.acm.org/doi/10.1145/3531536.3532966) [[code]](https://github.com/szegedai/hiding-needles-in-a-haystack)

- **DeepPayload: Black-box Backdoor Attack on Deep Learning Models through Neural Payload Injection.**  
  *Yuanchun Li, Jiayi Hua, Haoyu Wang, Chunyang Chen, Yunxin Liu.* ICSE, 2021.  
  [[pdf]](https://arxiv.org/pdf/2101.06896.pdf)

- **Architectural Backdoors in Neural Networks.**  
  *Mikel Bober-Irizar, Ilia Shumailov, Yiren Zhao, Robert Mullins, Nicolas Papernot.* arXiv, 2022.  
  [[pdf]](https://arxiv.org/pdf/2206.07840.pdf)

- **Planting Undetectable Backdoors in Machine Learning Models.**  
  *Shafi Goldwasser, Michael P. Kim, Vinod Vaikuntanathan, Or Zamir.* arXiv, 2022.  
  [[pdf]](https://arxiv.org/pdf/2204.06974.pdf)

Sure! Here’s an updated version, focused on only the most cutting-edge and valuable content:

---

#### Model Diagnosis Based Empirical Defense
- **Complex Backdoor Detection by Symmetric Feature Differencing.**  
  [[pdf]](https://www.cs.purdue.edu/homes/taog/docs/CVPR22_Liu.pdf)  
  *CVPR 2022*  
  - Detects backdoor by comparing differential features to distinguish injected anomalies.
  
- **Post-Training Detection of Backdoor Attacks for Multi-Attack Scenarios.**  
  [[pdf]](https://arxiv.org/pdf/2201.08474.pdf)  
  *ICLR 2022*  
  - Effective post-training detection of backdoor attacks in various conditions.
  
- **Randomized Channel Shuffling: Minimal-Overhead Backdoor Detection.**  
  [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2022/file/db1d5c63576587fc1d40d33a75190c71-Paper-Conference.pdf)  
  *NeurIPS 2022*  
  - Detects backdoors without requiring clean datasets.

- **SCALE-UP: Efficient Black-box Backdoor Detection via Analyzing Scaled Prediction Consistency.**  
  [[pdf]](https://openreview.net/pdf?id=o0LFPcoFKnr)  
  *ICLR 2023*  
  - Highly efficient black-box detection by checking prediction consistency on scaled inputs.
  
#### Poison Suppression-Based Empirical Defense
- **Backdoor Defense via Decoupling the Training Process.**  
  [[pdf]](https://openreview.net/pdf?id=TySnJ-0RdKI)  
  *ICLR 2022*  
  - A method to decouple poisoned and clean training to suppress backdoors.

- **Trap and Replace: Trapping Backdoor Attacks into Replaceable Subnetworks.**  
  [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2022/file/ea06e6e9e80f1c3d382317fff67041ac-Paper-Conference.pdf)  
  *NeurIPS 2022*  
  - Redirects backdoor attacks into a subnetwork that can be easily removed.

- **Mask and Restore: Test-Time Blind Backdoor Defense with Masked Autoencoder.**  
  [[pdf]](https://arxiv.org/pdf/2303.15564.pdf)  
  *arXiv 2023*  
  - Uses masked autoencoders to identify and eliminate backdoors at test time.

#### Federated Learning Paradigm
- **FLIP: Provable Defense Framework for Backdoor Mitigation in Federated Learning.**  
  [[pdf]](https://openreview.net/pdf?id=Xo2E217_M4n)  
  *ICLR 2023*  
  - Federated learning defense framework providing strong guarantees against backdoor attacks.

- **On the Vulnerability of Backdoor Defenses for Federated Learning.**  
  [[link]](https://ojs.aaai.org/index.php/AAAI/article/view/26393)  
  *AAAI 2023*  
  - Evaluates weaknesses in common defenses, revealing risks in federated learning setups.

- **Neurotoxin: Durable Backdoors in Federated Learning.**  
  [[pdf]](https://arxiv.org/pdf/2206.10341.pdf)  
  *ICML 2022*  
  - Demonstrates backdoors that are difficult to remove in federated learning contexts.

以下是对内容进行清理和保留前沿内容后的版本：

### Transfer Learning
- **Incremental Learning, Incremental Backdoor Threats**. *IEEE Transactions on Dependable and Secure Computing*, 2022.  
  [Wenbo Jiang et al.] [[link]](https://ieeexplore.ieee.org/abstract/document/9872528/)

- **Robust Backdoor Injection with the Capability of Resisting Network Transfer**. *Information Sciences*, 2022.  
  [Le Feng et al.] [[link]](https://www.sciencedirect.com/science/article/pii/S002002552201043X)

- **Anti-Distillation Backdoor Attacks: Backdoors Can Really Survive in Knowledge Distillation**. *ACM MM*, 2021.  
  [Yunjie Ge et al.] [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3474085.3475254)

- **Architectural Backdoors in Neural Networks**. arXiv, 2022.  
  [Mikel Bober-Irizar et al.] [[pdf]](https://arxiv.org/pdf/2206.07840.pdf)

### Reinforcement Learning
- **Provable Defense against Backdoor Policies in Reinforcement Learning**. *NeurIPS*, 2022.  
  [Shubham Kumar Bharti et al.] [[pdf]](https://openreview.net/pdf?id=11WmFbrIt26) [[code]](https://github.com/skbharti/Provable-Defense-in-RL)

- **MARNet: Backdoor Attacks against Cooperative Multi-Agent Reinforcement Learning**. *IEEE Transactions on Dependable and Secure Computing*, 2022.  
  [Yanjiao Chen et al.] [[link]](https://ieeexplore.ieee.org/abstract/document/9894692)

- **BACKDOORL: Backdoor Attack against Competitive Reinforcement Learning**. *IJCAI*, 2021.  
  [Lun Wang et al.] [[pdf]](https://arxiv.org/pdf/2105.00579.pdf)

### Semi-Supervised and Self-Supervised Learning
- **Backdoor Attacks on Self-Supervised Learning**. *CVPR*, 2022.  
  [Aniruddha Saha et al.] [[pdf]](https://arxiv.org/pdf/2105.10123) [[code]](https://github.com/UMBCvision/SSL-Backdoor)

- **Poisoning and Backdooring Contrastive Learning**. *ICLR*, 2022.  
  [Nicholas Carlini et al.] [[pdf]](https://arxiv.org/pdf/2106.09667.pdf)

- **BadEncoder: Backdoor Attacks to Pre-trained Encoders in Self-Supervised Learning**. *IEEE S&P*, 2022.  
  [Jinyuan Jia et al.] [[pdf]](https://arxiv.org/pdf/2108.00352.pdf) [[code]](https://github.com/jjy1994/BadEncoder)

### Quantization
- **RIBAC: Towards Robust and Imperceptible Backdoor Attack against Compact DNN**. *ECCV*, 2022.  
  [Huy Phan et al.] [[pdf]](https://arxiv.org/pdf/2208.10608.pdf) [[code]](https://github.com/huyvnphan/ECCV2022-RIBAC)

- **Qu-ANTI-zation: Exploiting Quantization Artifacts for Achieving Adversarial Outcomes**. *NeurIPS*, 2021.  
  [Sanghyun Hong et al.] [[pdf]](https://arxiv.org/pdf/2110.13541.pdf) [[code]](https://github.com/Secure-AI-Systems-Group/Qu-ANTI-zation)

### Natural Language Processing
- **TrojText: Test-time Invisible Textual Trojan Insertion**. *ICLR*, 2023.  
  [Qian Lou et al.] [[pdf]](https://openreview.net/pdf?id=ja4Lpp5mqc2) [[code]](https://github.com/UCF-ML-Research/TrojText)

- **Defending against Backdoor Attacks in Natural Language Generation**. *AAAI*, 2023.  
  [Xiaofei Sun et al.] [[link]](https://ojs.aaai.org/index.php/AAAI/article/view/25656)

- **BadPrompt: Backdoor Attacks on Continuous Prompts**. *NeurIPS*, 2022.  
  [Xiangrui Cai et al.] [[pdf]](https://openreview.net/pdf?id=rlN6fO3OrP) [[code]](https://github.com/papersPapers/BadPrompt)

- **Moderate-fitting as a Natural Backdoor Defender for Pre-trained Language Models**. *NeurIPS*, 2022.  
  [Biru Zhu et al.] [[pdf]](https://openreview.net/forum?id=C7cv9fh8m-b) [[code]](https://github.com/thunlp/Moderate-fitting)

- **PICCOLO: Exposing Complex Backdoors in NLP Transformer Models**. *IEEE S&P*, 2022.  
  [Yingqi Liu et al.] [[pdf]](https://www.cs.purdue.edu/homes/taog/docs/SP22_Liu.pdf) [[code]](https://github.com/PurduePAML/PICCOLO)

Sure! I've removed the outdated, non-cutting-edge, and unnecessary content to retain only the most advanced and worthwhile references. Here is the updated version:

---

### Graph Neural Networks
- Transferable Graph Backdoor Attack. [[pdf]](https://arxiv.org/pdf/2207.00425.pdf) *RAID*, 2022.
- More is Better (Mostly): On the Backdoor Attacks in Federated Graph Neural Networks. [[pdf]](https://arxiv.org/pdf/2202.03195.pdf) *ACSAC*, 2022.
- Link-Backdoor: Backdoor Attack on Link Prediction via Node Injection. [[pdf]](https://arxiv.org/pdf/2208.06776.pdf) [[code]](https://github.com/Seaocn/Link-Backdoor) arXiv, 2022.
- Neighboring Backdoor Attacks on Graph Convolutional Network. [[pdf]](https://arxiv.org/pdf/2201.06202.pdf) arXiv, 2022.

### Point Cloud
- A Backdoor Attack against 3D Point Cloud Classifiers. [[pdf]](https://arxiv.org/pdf/2104.05808.pdf) [[code]](https://github.com/zhenxianglance/PCBA) *ICCV*, 2021.
- Imperceptible and Robust Backdoor Attack in 3D Point Cloud. [[pdf]](https://arxiv.org/pdf/2208.08052.pdf) arXiv, 2022.

### Acoustics Signal Processing
- Toward Stealthy Backdoor Attacks against Speech Recognition via Elements of Sound. [[pdf]](https://arxiv.org/abs/2307.08208.pdf) [[code]](https://github.com/HanboCai/BadSpeech_SoE) *IEEE TIFS*, 2024.
- Inaudible Backdoor Attack via Stealthy Frequency Trigger Injection in Audio Spectrogram. [[link]](https://dl.acm.org/doi/abs/10.1145/3636534.3649345) *ACM MobiCom*, 2024.
- SilentTrig: An imperceptible backdoor attack against speaker identification with hidden triggers. [[link]](https://www.sciencedirect.com/science/article/pii/S0167865523003495) *Pattern Recognition Letters*, 2024.
- Devil in the Room: Triggering Audio Backdoors in the Physical World. [[pdf]](https://www.usenix.org/system/files/sec23winter-prepub-166-chen.pdf) *USENIX*, 2023.

### Medical Science
- FIBA: Frequency-Injection based Backdoor Attack in Medical Image Analysis. [[pdf]](https://arxiv.org/pdf/2112.01148.pdf) *CVPR*, 2022.

### Vision Transformer
- You Are Catching My Attention: Are Vision Transformers Bad Learners Under Backdoor Attacks? [[pdf]](https://openaccess.thecvf.com/content/CVPR2023/papers/Yuan_You_Are_Catching_My_Attention_Are_Vision_Transformers_Bad_Learners_CVPR_2023_paper.pdf) *CVPR*, 2023.
- TrojViT: Trojan Insertion in Vision Transformers. [[pdf]](https://openaccess.thecvf.com/content/CVPR2023/papers/Zheng_TrojViT_Trojan_Insertion_in_Vision_Transformers_CVPR_2023_paper.pdf) *CVPR*, 2023.

### Diffusion Model
- How to Backdoor Diffusion Models? [[pdf]](https://openaccess.thecvf.com/content/CVPR2023/papers/Chou_How_to_Backdoor_Diffusion_Models_CVPR_2023_paper.pdf) [[code]](https://github.com/IBM/BadDiffusion) *CVPR*, 2023.
- TrojDiff: Trojan Attacks on Diffusion Models With Diverse Targets. [[pdf]](https://openaccess.thecvf.com/content/CVPR2023/papers/Chen_TrojDiff_Trojan_Attacks_on_Diffusion_Models_With_Diverse_Targets_CVPR_2023_paper.pdf) [[code]](https://github.com/chenweixin107/TrojDiff) *CVPR*, 2023.

### Cybersecurity
- VulnerGAN: A Backdoor Attack through Vulnerability Amplification against Machine Learning-based Network Intrusion Detection Systems. [[link]](http://scis.scichina.com/en/2022/170303.pdf) [[code]](https://github.com/liuguangrui-hit/VulnerGAN-py) *Information Sciences*, 2022.

### Detection and Tracking
- Clean-image Backdoor: Attacking Multi-label Models with Poisoned Labels Only. [[pdf]](https://openreview.net/pdf?id=rFQfjDC9Mt) [[code]](https://github.com/RU-System-Software-and-Security/UNICORN) *ICLR*, 2023.
- Untargeted Backdoor Attack against Object Detection. [[pdf]](https://arxiv.org/pdf/2211.05638) [[code]](https://github.com/Chengxiao-Luo/Untargeted-Backdoor-Attack-against-Object-Detection) *ICASSP*, 2023.

### Evaluation and Discussion
- Distilling Cognitive Backdoor Patterns within an Image. [[pdf]](https://openreview.net/pdf?id=S3D9NLzjnQ5) [[code]](https://github.com/HanxunH/CognitiveDistillation) *ICLR*, 2023.
- BackdoorBox: A Python Toolbox for Backdoor Learning. [[pdf]](https://www.researchgate.net/publication/359439455_BackdoorBox_A_Python_Toolbox_for_Backdoor_Learning) [[code]](https://github.com/THUYimingLi/BackdoorBox) *ICLR Workshop*, 2023.
- A Unified Evaluation of Textual Backdoor Learning: Frameworks and Benchmarks. [[pdf]](https://arxiv.org/pdf/2206.08514.pdf) [[code]](https://github.com/thunlp/OpenBackdoor) *NeurIPS*, 2022.

### Others
- The Dark Side of AutoML: Towards Architectural Backdoor Search. [[pdf]](https://openreview.net/pdf?id=bsZULlDGXe) [[code]](https://github.com/ain-soph/nas_backdoor) *ICLR*, 2023.
- Backdoor Attacks Against Deep Image Compression via Adaptive Frequency Trigger. [[pdf]](https://openaccess.thecvf.com/content/CVPR2023/papers/Tan_Backdoor_Attacks_Against_Deep_Image_Compression_via_Adaptive_Frequency_Trigger_CVPR_2023_paper.pdf) *CVPR*, 2023.


## Competition
- [Trojan Detection Challenge](https://trojandetection.ai/)
- [IARPA TrojAI Competition](https://pages.nist.gov/trojai/docs/about.html)
