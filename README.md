# fakenewsdetection
A repository for fake news detection.

# fake news detection Learning Resources
This Github repository summarizes a list of **fake news detection** resources. For more details and the categorization criteria, please refer to our [survey](). 

We will try our best to continuously maintain this Github Repository in a weekly manner.





## Contributing

Please help to contribute this list by contacting [me](http://fudanmas.com/#/pages/home/real) or add [pull request]()

Markdown format:
```markdown
- Paper Name. 
  [[link]](link) 
  [[code]](link).
  - Author 1, Author 2, Author 3. *Conference/Journal*, Year.
```
**Note**: In the same year, please place the conference paper before the journal paper, as journals are usually submitted a long time ago and therefore have some lag. (*i.e.*, Conferences-->Journals-->Preprints)


## Table of Contents
- [Survey](#survey)
- [Text-based Detection](#text-based-detection)
- [Multi-modal Detection](#multi-modal-detection) 
- [Using Social Context](#using-social-context)
  - [User Information](#user-information)
  - [Comment](#comment)
- [Fact-checking](#fact-checking)
- [Datasets](#Datasets)


## Survey
- An overview of online fake news: Characterization, detection, and discussion. [[link]](https://www.sciencedirect.com/science/article/pii/S0306457318306794)
  - X Zhang, AA Ghorbani. Information Processing & Management, 2020.

- The Future of False Information Detection on Social Media: New Perspectives and Trends. [[link]](https://dl.acm.org/doi/10.1145/3393880)
  -  B Guo, Y Ding, L Yao, Y Liang, Z Yu. ACM Computing Surveys, 2020.
  -  
- A survey of fake news: Fundamental theories, detection methods, and opportunities. [[link]](https://dl.acm.org/doi/10.1145/3395046)
  - Mingfu Xue, Jian Wang, Weiqiang Liu. ACM Computing Surveys, 2021.

- A unified perspective for disinformation detection and truth discovery in social sensing: A survey. [[link]](https://dl.acm.org/doi/10.1145/3477138)
  -  F Xu, VS Sheng, M Wang. ACM Computing Surveys, 2021.

- A Survey on Multimodal Disinformation Detection. [[link]](https://aclanthology.org/2022.coling-1.576/)
  -  F Alam, S Cresci, T Chakraborty, F Silvestri. *COLING*, 2022.

- A Survey on Automated Fact-Checking [[link]](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00454/109469/A-Survey-on-Automated-Fact-Checking).
    - Z Guo, M Schlichtkrull, A Vlachos. Transactions of the Association for Computational Linguistics, 2022.
## Text-based Detection
- Detect Rumors on Twitter by Promoting Information Campaigns with Generative Adversarial Learning.
  [[link]](https://dl.acm.org/doi/10.1145/3308558.3313741)
  [[code]](https://github.com/majingCUHK/Rumor_GAN)
  - J Ma, W Gao, KF Wong. *WWW*, 2019.
       
- Conquering cross-source failure for news credibility: Learning generalizable representations beyond content embedding.
  [[link]](https://dl.acm.org/doi/10.1145/3477495.3531816)
  - YH Huang, TW Liu, SR Lee.  *WWW*, 2020.
  - 
- MDFEND: Multi-domain fake news detection.
  [[link]](https://dl.acm.org/doi/10.1145/3459637.3482139)
  [[code]](https://github.com/kennqiang/MDFEND-Weibo21)
  - Q Nan, J Cao, Y Zhu, Y Wang, J Li. *CIKM*, 2021.
   
- Convolutional neural network with margin loss for fake news detection.
  [[link]](https://www.sciencedirect.com/science/article/pii/S0306457320309134)
  - MH Goldani, R Safabakhsh, S Momtazi. Information Processing & Management, 2021.
 
- Zoom Out and Observe: News Environment Perception for Fake News Detection.
  [[link]](https://aclanthology.org/2022.acl-long.311/)
  - Q Sheng, J Cao, X Zhang, R Li, D Wang. *ACL*, 2022.
 
- Contrastive domain adaptation for early misinformation detection: A case study on covid-19.
  [[link]](https://dlnext.acm.org/doi/10.1145/3511808.3557263)
  - Z Yue, H Zeng, Z Kou, L Shang, D Wang. *CIKM*, 2022.
    
- Generalizing to the future: Mitigating entity bias in fake news detection.
  [[link]](https://dl.acm.org/doi/10.1145/3477495.3531816)
  - Y Zhu, Q Sheng, J Cao, S Li, D Wang. *SIGIR*, 2022.
 
- Memory-guided multi-view multi-domain fake news detection.
  [[link]](https://ieeexplore.ieee.org/document/9802916)
  - Y Zhu, Q Sheng, J Cao, Q Nan, K Shu. IEEE Transactions on Knowledge and Data Engineering 2022.
    
- A network-based positive and unlabeled learning approach for fake news detection.
  [[link]](https://link.springer.com/article/10.1007/s10994-021-06111-6)
  - MC de Souza, BM Nogueira, RG Rossi, RM Marcacini. Machine Learning, 2022.

- Faking Fake News for Real Fake News Detection: Propaganda-loaded Training Data Generation.
  [[link]](https://arxiv.org/pdf/2203.05386.pdf)
  - KH Huang, K McKeown, P Nakov, Y Choi, H Ji. *ACL*, 2023.

- MetaAdapt: Domain Adaptive Few-Shot Misinformation Detection via Meta Learning.
  [[link]](https://arxiv.org/pdf/2305.12692.pdf)
  - Z Yue, H Zeng, Y Zhang, L Shang, D Wang. *ACL*, 2023.
 
- Improving rumor detection by promoting information campaigns with transformer-based generative adversarial learning.
  [[link]](https://ieeexplore.ieee.org/document/9540337)
  - J Ma, J Li, W Gao, Y Yang. IEEE Transactions on Knowledge and Data Engineering, 2023.
 
- Meta-prompt based learning for low-resource false information detection.
  [[link]](https://www.sciencedirect.com/science/article/pii/S030645732300016X)
  - Y Huang, M Gao, J Wang, J Yin, K Shu, Q Fan. Information Processing & Management, 2023.

=======
## Multi-modal Detection
- EANN: Event Adversarial Neural Networks for Multi-Modal Fake News Detection.
  [[link]](https://dl.acm.org/doi/10.1145/3219819.3219903)
  [[code]](https://github.com/yaqingwang/EANN-KDD18)
  - Y Wang, F Ma, Z Jin, Y Yuan, G Xun, K Jha, L Su, J Gao. *KDD*, 2018.

- MVAE: Multimodal Variational Autoencoder for Fake News Detection.
  [[link]](https://dl.acm.org/doi/10.1145/3308558.3313552)
  [[code]](https://github.com/dhruvkhattar/MVAE)
  - D Khattar, JS Goud, M Gupta, V Varma. *WWW*, 2019.
 
- Exploiting multi-domain visual information for fake news detection.
  [[link]](https://ieeexplore.ieee.org/document/8970940)
  - P Qi, J Cao, T Yang, J Guo, J Li. *ICDM*, 2019.
 
- Spotfake+: A multimodal framework for fake news detection via transfer learning.
  [[link]](https://dl.acm.org/doi/10.1145/3404835.3462871)
  - S Singhal, A Kabra, M Sharma, RR Shah. *AAAI*, 2020.
 
- Multimodal disentangled domain adaption for social media event rumor detection.
  [[link]](https://ieeexplore.ieee.org/document/9285217)
  - H Zhang, S Qian, Q Fang, C Xu. IEEE Transactions on Multimedia, 2020.
 
- Multimodal disentangled domain adaption for social media event rumor detection.
  [[link]](https://ieeexplore.ieee.org/document/9285217)
  - H Zhang, S Qian, Q Fang, C Xu. IEEE Transactions on Multimedia, 2020.
  
- Multimodal fusion network with latent topic memory for rumor detection.
  [[link]](https://ieeexplore.ieee.org/abstract/document/9428404)
  - J Chen, Z Wu, Z Yang, H Xie. *ICME*, 2021.
 
- Hierarchical multi-modal contextual attention network for fake news detection.
  [[link]](https://dl.acm.org/doi/10.1145/3404835.3462871)
  - S Qian, J Wang, J Hu, Q Fang, C Xu. *SIGIR*, 2021.
 
- Multimodal Fusion with Co-Attention Networks for Fake News Detection.
  [[link]](https://aclanthology.org/2021.findings-acl.226/)
  - Y Wu, P Zhan, Y Zhang, L Wang. *ACL*, 2021.
 
- Multimodal emergent fake news detection via meta neural process networks.
  [[link]](https://dl.acm.org/doi/10.1145/3447548.3467153)
  - Y Wang, F Ma, H Wang, K Jha, J Gao. *KDD*, 2021.
   
- Supervised Contrastive Learning for Multimodal Unreliable News Detection in COVID-19 Pandemic.
  [[link]](https://dl.acm.org/doi/10.1145/3459637.3482196)
  [[code]](https://github.com/WenjiaZh/BTIC)
  - W Zhang, L Gui, Y He. *CIKM*, 2021.
  
- A multimodal fake news detection model based on crossmodal attention residual and multichannel convolutional neural networks.
  [[link]](https://www.sciencedirect.com/science/article/pii/S0306457320309304)
  - C Song, N Ning, Y Zhang, B Wu. Information Processing & Management, 2021.

- Detecting fake news by exploring the consistency of multimodal data.
  [[link]](https://www.sciencedirect.com/science/article/pii/S0306457321001060)
  - J Xue, Y Wang, Y Tian, Y Li, L Shi, L Wei. Information Processing & Management, 2021.

- HAN, image captioning, and forensics ensemble multimodal fake news detection.
  [[link]](https://www.sciencedirect.com/science/article/pii/S0020025521002826)
  - P Meel, DK Vishwakarma. Information Sciences, 2021.

- Entity-Oriented Multi-Modal Alignment and Fusion Network for Fake News Detection.
  [[link]](https://ieeexplore.ieee.org/document/9495252)
  - P Li, X Sun, H Yu, Y Tian, F Yao. IEEE Transactions on Multimedia, 2021.
 
- Multi-modal meta multi-task learning for social media rumor detection.
  [[link]](https://ieeexplore.ieee.org/document/9376933)
  - H Zhang, S Qian, Q Fang, C Xu. IEEE Transactions on Multimedia, 2021.
 
- Multi-Modal Adversarial Adaptive Network for Misinformation Detection on Social Media [[link]](https://ieeexplore.ieee.org/abstract/document/9859648/).
  - L Zhang, P Zhang, X Zhu, L Liu, H Xu. *ICME*, 2022.

- AdaDebunk: An Efficient and Reliable Deep State Space Model for Adaptive Fake News Early Detection [[link]](https://dl.acm.org/doi/abs/10.1145/3511808.3557227).
  - K Li, B Guo, S Ren, Z Yu. *CIKM*, 2022.

- A Duo-generative Approach to Explainable Multimodal COVID-19 Misinformation Detection.
  [[link]](https://dl.acm.org/doi/10.1145/3485447.3512257)
  - L Shang, Z Kou, Y Zhang, D Wang. *WWW*, 2022.
  
- Cross-modal ambiguity learning for multimodal fake news detection.
  [[link]](https://dl.acm.org/doi/10.1145/3485447.3511968)
  - Y Chen, D Li, P Zhang, J Sui, Q Lv, L Tun. *WWW*, 2022.
    
- Leveraging Intra and Inter Modality Relationship for Multimodal Fake News Detection.
  [[link]](https://dl.acm.org/doi/10.1145/3487553.3524650)
  - S Singhal, T Pandey, S Mrig, RR Shah. *WWW*, 2022.
  
- Cross-modal knowledge distillation in multi-modal fake news detection.
  [[link]](https://ieeexplore.ieee.org/document/9747280/)
  - Z Wei, H Pan, L Qiao, X Niu, P Dong. *ICASSP*, 2022.
 
- Cross-Platform Multimodal Misinformation: Taxonomy, Characteristics and Detection for Textual Posts and Videos.
  [[link]](https://aaai.org/papers/00651-cross-platform-multimodal-misinformation-taxonomy-characteristics-and-detection-for-textual-posts-and-videos/)
  - N Micallef, M Sandoval-Castañeda, A Cohen. *ICWSM*, 2022.
 
- ARCNN framework for multimodal infodemic detection.
  [[link]](https://www.sciencedirect.com/science/article/pii/S0893608021004342)
  - C Raj, P Meel. Neural Networks, 2022.

- BCMF: A bidirectional cross-modal fusion model for fake news detection.
  [[link]](https://www.sciencedirect.com/science/article/pii/S0306457322001662)
  - C Yu, Y Ma, L An, G Li. Information Processing & Management, 2022.
  
- Causal Inference for Leveraging Image-text Matching Bias in Multi-modal Fake News Detection.
  [[link]](https://ieeexplore.ieee.org/document/9996587)
  - L Hu, Z Chen, ZZJ Yin, L Nie. IEEE Transactions on Knowledge and Data Engineering, 2022.
 
- Understanding the Use and Abuse of Social Media: Generalized Fake News Detection With a Multichannel Deep Neural Network.
  [[link]](https://ieeexplore.ieee.org/document/9956917)
  - RK Kaliyar, A Goswami, P Narang. IEEE Transactions on Computational Social Systems, 2022.

- Improving Generalization for Multimodal Fake News Detection [[link]](https://dl.acm.org/doi/abs/10.1145/3591106.3592230).
  - S Tahmasebi, S Hakimov, R Ewerth. *ICMR*, 2023.

- MRML: Multimodal Rumor Detection by Deep Metric Learning [[link]](https://ieeexplore.ieee.org/abstract/document/10096188).
  - L Peng, S Jian, D Li, S Shen. *ICASSP*, 2023.

- Graph Interactive Network with Adaptive Gradient for Multi-Modal Rumor Detection [[link]](https://dl.acm.org/doi/abs/10.1145/3591106.3592250).
  - T Sun, Z Qian, P Li, Q Zhu. *ICMR*, 2023.

- Multi-modal Fake News Detection on Social Media via Multi-grained Information Fusion [[link]](https://dl.acm.org/doi/abs/10.1145/3591106.3592271).
  - Y Zhou, Y Yang, Q Ying, Z Qian, X Zhang. *ICMR*, 2023.

- Detecting and grounding multi-modal media manipulation.
  [[link]](https://arxiv.org/pdf/2304.02556.pdf)
  [[code]](https://github.com/rshaojimmy/MultiModal-DeepFake)
  - R Shao, T Wu, Z Liu. *CVPR*, 2023.
  
- A Multimodal Framework for the Identification of Vaccine Critical Memes on Twitter.
  [[link]](https://dl.acm.org/doi/10.1145/3485447.3511968)
  - U Naseem, J Kim, M Khushi, AG Dunn. *WSDM*, 2023.

- Bootstrapping Multi-view Representations for Fake News Detection.
  [[link]](https://arxiv.org/pdf/2206.05741.pdf)
  [[code]](https://github.com/yingqichao/fnd-bootstrap)
  - Q Ying, X Hu, Y Zhou, Z Qian, D Zeng. *AAAI*, 2023.

- Multimodal fake news analysis based on image–text similarity.
  [[link]](https://ieeexplore.ieee.org/abstract/document/10049384)
  - X Zhang, S Dadkhah, AG Weismann. IEEE Transactions on Computational Social Systems, 2023.

- Multimodal fake news detection via progressive fusion networks.
  [[link]](https://www.sciencedirect.com/science/article/pii/S0306457322002217)
  - J Jing, H Wu, J Sun, X Fang, H Zhang. Information Processing & Management, 2023.
 
- Positive Unlabeled Fake News Detection Via Multi-Modal Masked Transformer Network.
  [[link]](https://ieeexplore.ieee.org/document/10089519)
  - J Wang, S Qian, J Hu, R Hong. IEEE Transactions on Multimedia, 2023.
## Using Social Context

### User Information
- Beyond News Contents: The Role of Social Context for Fake News Detection.
  [[link]](https://dl.acm.org/doi/10.1145/3289600.3290994)
  - K Shu, S Wang, H Liu. *WSDM*, 2019.

- GCAN: Graph-aware Co-Attention Networks for Explainable Fake News Detection on Social Media.
  [[link]](https://aclanthology.org/2020.acl-main.48/)
  [[code]](https://github.com/l852888/GCAN)
  - YJ Lu, CT Li. *ACL*, 2020.

- FANG: Leveraging Social Context for Fake News Detection Using Graph Representation.
  [[link]](https://dl.acm.org/doi/10.1145/3340531.3412046)
  [[code]](https://github.com/nguyenvanhoang7398/FANG)
  - VH Nguyen, K Sugiyama, P Nakov. *CIKM *, 2020.
 
- Hierarchical propagation networks for fake news detection: Investigation and exploitation.
  [[link]](https://ojs.aaai.org/index.php/ICWSM/article/view/7329)
  - K Shu, D Mahudeswaran, S Wang, H Liu. *ICWSM*, 2020.

- FNED: a deep network for fake news early detection on social media.
  [[link]](https://dl.acm.org/doi/10.1145/3386253)
  - Y Liu, YFB Wu. ACM Transactions on Information Systems, 2020.
   
- Data Fusion Oriented Graph Convolution Network Model for Rumor Detection.
  [[link]](https://ieeexplore.ieee.org/document/9240946)
  - K Yu, H Jiang, T Li, S Han, X Wu. IEEE Transactions on Network and Service Management, 2020.
   
- Discovering differential features: Adversarial learning for information credibility evaluation.
  [[link]](https://www.sciencedirect.com/science/article/pii/S002002551931151X)
  - L Wu, Y Rao, A Nazir, H Jin. Information Sciences, 2020.

- User Preference-aware Fake News Detection.
  [[link]](https://dl.acm.org/doi/abs/10.1145/3404835.3462990)
  [[code]](https://github.com/safe-graph/GNN-FakeNews)
  - Y Dou, K Shu, C Xia, PS Yu, L Sun. *SIGIR*, 2021.
 
- Rumor detection on social media with graph structured adversarial learning.
  [[link]](www.ijcai.org/Proceedings/2020/197)
  - X Yang, Y Lyu, T Tian, Y Liu, Y Liu, X Zhang. *IJCAI*, 2021.

- Embracing domain differences in fake news: Cross-domain fake news detection using multi-modal data.
  [[link]](https://ojs.aaai.org/index.php/AAAI/article/view/16134)
  - A Silva, L Luo, S Karunasekera, C Leckie. *AAAI*, 2021.
    
- Causal understanding of fake news dissemination on social media.
  [[link]](https://dl.acm.org/doi/10.1145/3447548.3467321)
  - L Cheng, R Guo, K Shu, H Liu. *KDD*, 2021.

- Temporally evolving graph neural network for fake news detection.
  [[link]](https://www.sciencedirect.com/science/article/pii/S0306457321001965)
  - C Song, K Shu, B Wu. Information Processing & Management, 2021.
    
- Propagation2Vec: Embedding partial propagation networks for explainable fake news early detection.
  [[link]](https://www.sciencedirect.com/science/article/pii/S030645732100114X)
  - A Silva, Y Han, L Luo, S Karunasekera. Information Processing & Management, 2021.
   
- Studying and understanding characteristics of post-syncing practice and goal in social network sites.
  [[link]](https://dl.acm.org/doi/10.1145/3457986)
  - P Zhang, B Liu, X Ding, T Lu, H Gu, N Gu. ACM Transactions on the Web, 2021.
   
- Mistr: A multiview structural-temporal learning framework for rumor detection.
  [[link]](https://ieeexplore.ieee.org/document/9524525)
  - J Li, P Bao, H Shen, X Li. IEEE Transactions on Big Data, 2021.
 
- Divide-and-Conquer: Post-User Interaction Network for Fake News Detection on Social Media.
  [[link]](https://dl.acm.org/doi/abs/10.1145/3485447.3512163)
  [[code]](https://github.com/qwerfdsaplking/MC-Fake)
  - E Min, Y Rong, Y Bian, T Xu, P Zhao, J Huang. *WWW*, 2022.
 
- Towards Fine-Grained Reasoning for Fake News Detection.
  [[link]](https://aaai.org/papers/05746-towards-fine-grained-reasoning-for-fake-news-detection/)
  - Y Jin, X Wang, R Yang, Y Sun, W Wang. *AAAI*, 2022.
    
- Reinforcement Subgraph Reasoning for Fake News Detection.
  [[link]](https://dl.acm.org/doi/10.1145/3534678.3539277)
  - R Yang, X Wang, Y Jin, C Li, J Lian, X Xie. *KDD*, 2022.
    
- Meta-Path-based Fake News Detection Leveraging Multi-level Social Context Information.
  [[link]](https://dl.acm.org/doi/10.1145/3511808.3557394)
  - J Cui, K Kim, SH Na, S Shin. *CIKM*, 2022.
    
- MFAN: Multi-modal Feature-enhanced Attention Networks for Rumor Detection.
  [[link]](www.ijcai.org/proceedings/2022/335)
  - J Zheng, X Zhang, S Guo, Q Wang, W Zang, Y Zhang. *IJCAI*, 2022.
    
- An integrated multi-task model for fake news detection.
  [[link]](https://ieeexplore.ieee.org/document/9339883)
  - Q Liao, H Chai, H Han, X Zhang. IEEE Transactions on Knowledge and Data Engineering, 2022.
   
- A hierarchical network-oriented analysis of user participation in misinformation spread on WhatsApp.
  [[link]](https://www.sciencedirect.com/science/article/pii/S0306457321002387)
  - GP Nobre, CHG Ferreira, JM Almeida. Information Processing & Management, 2022.
   
- A rumor & anti-rumor propagation model based on data enhancement and evolutionary game.
  [[link]](https://ieeexplore.ieee.org/abstract/document/9241026)
  - Y Xiao, W Li, S Qiang, Q Li, H Xiao. IEEE Transactions on Emerging Topics in Computing, 2022.

- Learning Sparse Alignments via Optimal Transport for Cross-Domain Fake News Detection [[link]](https://ieeexplore.ieee.org/abstract/document/10095281) [[code]](https://github.com/OceanTangWei/NOT).
  - W Tang, Z Ma, H Sun, J Wang. *ICASSP*, 2023.

- Unsupervised Rumor Detection Based on Propagation Tree VAE [[link]](https://ieeexplore.ieee.org/abstract/document/10103675).
  - L Fang, K Feng, K Zhao, A Hu, T, Li. IEEE Transactions on Knowledge and Data Engineering, 2023. 

- Preventing profiling for ethical fake news detection.
  [[link]](https://www.sciencedirect.com/science/article/pii/S0306457322003077)
  - L Allein, MF Moens, D Perrotta. Information Processing & Management, 2023.

### Comment


- Weak Supervision for Fake News Detection via Reinforcement Learning.
  [[link]](https://aaai.org/papers/00516-weak-supervision-for-fake-news-detection-via-reinforcement-learning/)
  - Y Wang, W Yang, F Ma, J Xu, B Zhong. *AAAI*, 2020.

- QSAN: A quantum-probability based signed attention network for explainable false information detection.
  [[link]](https://dl.acm.org/doi/10.1145/3340531.3411890)
  - T Tian, Y Liu, X Yang, Y Lyu, X Zhang. *CIKM*, 2020.
 
- Integrating Semantic and Structural Information with Graph Convolutional Network for Controversy Detection.
  [[link]](https://aclanthology.org/2020.acl-main.49/)
  - L Zhong, J Cao, Q Sheng, J Guo, Z Wang. *ACL*, 2020.
 
- EMET: Embeddings from multilingual-encoder transformer for fake news detection.
  [[link]](https://ieeexplore.ieee.org/document/9625796)
  - S Schwarz, A Theóphilo. *ICASSP*, 2020.
 
- SeRN: Stance extraction and reasoning network for fake news detection.
  [[link]](https://ieeexplore.ieee.org/document/9414787)
  - J Xie, S Liu, R Liu, Y Zhang. *ICASSP*, 2021.
  
- Poligraph: Intrusion-tolerant and distributed fake news detection system.
  [[link]](https://ieeexplore.ieee.org/document/9627681)
  - G Shan, B Zhao, JR Clavin, H Zhang. IEEE Transactions on Information Forensics and Security, 2021.
  
- What and Why Towards Duo Explainable Fauxtography Detection under Constrained Supervision.
  [[link]](https://ieeexplore.ieee.org/document/9627681)
  - Z Kou, D Zhang, L Shang. IEEE Transactions on Big Data, 2021.
  
- gDART: Improving rumor verification in social media with Discrete Attention Representations.
  [[link]](https://www.sciencedirect.com/science/article/pii/S0306457322000516)
  [[code]](https://github.com/saswataroy1987/gDART-Improving-rumor-verification-in-social-media-with-Discrete-Attention-Representations/tree/main)
  - S Roy, M Bhanu, S Saxena, S Dandapat. Information Processing & Management, 2022.
  
- Dynamic probabilistic graphical model for progressive fake news detection on social media platform.
  [[link]](https://dl.acm.org/doi/10.1145/3523060)
  - K Li, B Guo, J Liu, J Wang, H Ren, F Yi. ACM Transactions on Intelligent Systems and Technology, 2022.
  
- Explainable Detection of Fake News on Social Media Using Pyramidal Co-Attention Network.
  [[link]](https://ieeexplore.ieee.org/abstract/document/9908576)
  - F Khan, R Alturki, G Srivastava. IEEE Transactions on Computational Social Systems, 2022.

- Cross-Modal Adversarial Contrastive Learning for Multi-Modal Rumor Detection [[link]](https://ieeexplore.ieee.org/abstract/document/10096883).
  - T Zou, Z Qian, P Li, Q Zhu. *ICASSP*, 2023.

- Human Cognition-based Consistency Inference Networks for Multi-modal Fake News Detection.
  [[link]](https://ieeexplore.ieee.org/abstract/document/10138033/)
  - L Wu, P Liu, Y Zhao, P Wang. IEEE Transactions on Knowledge and Data Engineering, 2023.
## Fact-checking

- The Rise of Guardians: Fact-checking URL Recommendation to Combat Fake News [[link]](https://dl.acm.org/doi/abs/10.1145/3209978.3210037)
    - N Vo, K Lee. *SIGIR*, 2018.
  
- Attributed multi-relational attention network for fact-checking url recommendation.
  [[link]](https://dl.acm.org/doi/abs/10.1145/3357384.3358006)
  - D You, N Vo, K Lee, Q Liu. *CIKM*, 2019.

- Sentence-Level Evidence Embedding for Claim Verification with Hierarchical Attention Networks [[link]](https://ink.library.smu.edu.sg/sis_research/4557/).
    - J Ma, W Gao, S Joty, KF Wong. *ACL*, 2019.
  
- Learning from fact-checkers: Analysis and generation of fact-checking language.
  [[link]](https://dl.acm.org/doi/10.1145/3331184.3331248)
  [[code]](https://github.com/nguyenvo09/LearningFromFactCheckers)
  - N Vo, K Lee. *SIGIR*, 2019.

- DeClarE: Debunking Fake News and False Claims using Evidence-Aware Deep Learning [[link]](https://aclanthology.org/D18-1003/)
    - K Popat, S Mukherjee, A Yates, G Weikum. *EMNLP*, 2020.

- Fake News Detection via Knowledge-driven Multimodal Graph Convolutional Networks.
  [[link]](https://dl.acm.org/doi/10.1145/3372278.3390713)
  - Y Wang, S Qian, J Hu, Q Fang, C Xu. *ICMR*, 2020.
    
- Where Are the Facts? Searching for Fact-checked Information to Alleviate the Spread of Fake News.
  [[link]](https://aclanthology.org/2020.emnlp-main.621/)
  [[code]](https://github.com/nguyenvo09/EMNLP2020)
  - N Vo, K Lee. *EMNLP*, 2020.

- Evidence Inference Networks for Interpretable Claim Verification [[link]](https://ink.library.smu.edu.sg/sis_research/4557/).
    - L Wu, Y Rao, L Sun, W He. *AAAI*, 2021.

- Evidence-Aware Hierarchical Interactive Attention Networks for Explainable Claim Verification
    - L Wu, Y Rao, X Yang, W Wang, A Nazir. *IJCAI*, 2021.

- Mining Dual Emotion for Fake News Detection.
  [[link]](https://dl.acm.org/doi/10.1145/3442381.3450004)
  [[code]](https://github.com/RMSnow/WWW2021)
  - X Zhang, J Cao, X Li, Q Sheng, L Zhong. *WWW*, 2021.
 
- Kan: Knowledge-aware attention network for fake news detection.
  [[link]](https://aaai.org/papers/00081-kan-knowledge-aware-attention-network-for-fake-news-detection/)
  - Y Dun, K Tu, C Chen, C Hou, X Yuan. *AAAI*, 2021.

  
- Improving Fake News Detection by Using an Entity-enhanced Framework to Fuse Diverse Multimodal Clues.
  [[link]](https://dl.acm.org/doi/10.1145/3474085.3481548)
  - P Qi, J Cao, X Li, H Liu, Q Sheng, X Mi, Q He. *ACM MM*, 2021.
 
- Integrating pattern-and fact-based fake news detection via model preference learning.
  [[link]](https://dl.acm.org/doi/10.1145/3459637.3482440)
  [[code]](https://github.com/ICTMCG/Pref-FEND)
  - Q Sheng, X Zhang, J Cao, L Zhong. *CIKM*, 2021.
  
- Fact-enhanced synthetic news generation.
  [[link]](https://aaai.org/papers/13825-fact-enhanced-synthetic-news-generation/)
  - K Shu, Y Li, K Ding, H Liu. *AAAI*, 2021.
    
- Knowledge-aware multi-modal adaptive graph convolutional networks for fake news detection.
  [[link]](https://dl.acm.org/doi/abs/10.1145/3451215)
  - S Qian, J Hu, Q Fang, C Xu. ACM Transactions on Multimedia Computing, Communications, and Applications, 2021.

- Evidence-aware Fake News Detection with Graph Neural Networks [[link]](https://dl.acm.org/doi/abs/10.1145/3485447.3512122)
    - W Xu, J Wu, Q Liu, S Wu, L Wang. *WWW*, 2022.

- Open-Domain, Content-based, Multi-modal Fact-checking of Out-of-Context Images via Online Resources [[link]](https://openaccess.thecvf.com/content/CVPR2022/html/Abdelnabi_Open-Domain_Content-Based_Multi-Modal_Fact-Checking_of_Out-of-Context_Images_via_Online_Resources_CVPR_2022_paper.html)
    - S Abdelnabi, R Hasan, M Fritz. *CVPR*, 2022.

- GERE: Generative Evidence Retrieval for Fact Verification [[link]](https://dl.acm.org/doi/abs/10.1145/3477495.3531827)
    - J Chen, R Zhang, J Guo, Y Fan, X Cheng. *SIGIR*, 2022.

- Bias Mitigation for Evidence-aware Fake News Detection by Causal Intervention
    - J Wu, Q Liu, W Xu, S Wu. *SIGIR*, 2022.
  
- “This is Fake! Shared it by Mistake”: Assessing the Intent of Fake News Spreaders.
  [[link]](https://dl.acm.org/doi/10.1145/3485447.3512264)
  - X Zhou, K Shu, VV Phoha, H Liu. *WWW*, 2022.
  
- CrowdGraph: A Crowdsourcing Multi-modal Knowledge Graph Approach to Explainable Fauxtography Detection.
  [[link]](https://dl.acm.org/doi/10.1145/3555178)
  - Z Kou, Y Zhang, D Zhang, D Wang. *HCI*, 2022.

- EvidenceNet: Evidence Fusion Network for Fact Verification.
  [[link]](https://dl.acm.org/doi/abs/10.1145/3357384.3358006)
  - Z Chen, SC Hui, F Zhuang, L Liao, F Li, M Jia.  *WWW*, 2022.
  
- The impact of psycholinguistic patterns in discriminating between fake news spreaders and fact checkers.
  [[link]](https://www.sciencedirect.com/science/article/pii/S0169023X21000835)
  - A Giachanou, B Ghanem, EA Ríssola, P Rosso. Data & Knowledge Engineering, 2022.
    
- MetaDetector: Meta Event Knowledge Transfer for Fake News Detection.
  [[link]](https://dl.acm.org/doi/10.1145/3532851)
  - Y Ding, B Guo, Y Liu, Y Liang, H Shen. ACM Transactions on Intelligent Systems and Technology, 2022.


- FactKG: Fact Verification via Reasoning on Knowledge Graphs.
  [[link]](https://arxiv.org/pdf/2305.06590.pdf)
  - J Kim, S Park, Y Kwon, Y Jo, J Thorne, E Choi. *ACL*, 2023.

- Fact-Checking Complex Claims with Program-Guided Reasoning.
  [[link]](https://arxiv.org/pdf/2305.12744.pdf)
  - L Pan, X Wu, X Lu, A Luu, W Wang, M Kan, P Nakov. *ACL*, 2023.
    
- Counterfactual Debiasing for Fact Verification.
  [[link]](https://openreview.net/pdf?id=BddNTCq65yq)
  - W Xu, Q Liu, S Wu, L Wang. *ACL*, 2023.
  
- Inconsistent Matters: A Knowledge-guided Dual-consistency Network for Multi-modal Rumor Detection.
  [[link]](https://ieeexplore.ieee.org/document/10123962/)
  - M Sun, X Zhang, J Ma, S Xie, Y Liu. IEEE Transactions on Knowledge and Data Engineering, 2023.
