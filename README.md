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

- A survey of fake news: Fundamental theories, detection methods, and opportunities. [[link]](https://dl.acm.org/doi/10.1145/3395046)
  - Mingfu Xue, Jian Wang, Weiqiang Liu. ACM Computing Surveys, 2021.

- The Future of False Information Detection on Social Media: New Perspectives and Trends. [[link]](https://dl.acm.org/doi/10.1145/3393880)
  -  B Guo, Y Ding, L Yao, Y Liang, Z Yu. ACM Computing Surveys, 2020.

- A Survey on Multimodal Disinformation Detection. [[link]](https://aclanthology.org/2022.coling-1.576/)
  -  F Alam, S Cresci, T Chakraborty, F Silvestri. *COLING*, 2022.
## Text-based Detection
- Detect Rumors on Twitter by Promoting Information Campaigns with Generative Adversarial Learning.
  [[link]](https://dl.acm.org/doi/10.1145/3308558.3313741)
  [[code]](https://github.com/majingCUHK/Rumor_GAN)
  - J Ma, W Gao, KF Wong. *WWW*, 2019.
   
- Convolutional neural network with margin loss for fake news detection.
  [[link]](https://www.sciencedirect.com/science/article/pii/S0306457320309134)
  - MH Goldani, R Safabakhsh, S Momtazi. Information Processing & Management, 2021.
 
  
- MDFEND: Multi-domain fake news detection.
  [[link]](https://dl.acm.org/doi/10.1145/3459637.3482139)
  [[code]](https://github.com/kennqiang/MDFEND-Weibo21)
  - Q Nan, J Cao, Y Zhu, Y Wang, J Li. *CIKM*, 2021.
 

- Memory-guided multi-view multi-domain fake news detection.
  [[link]](https://ieeexplore.ieee.org/document/9802916)
  - Y Zhu, Q Sheng, J Cao, Q Nan, K Shu. IEEE Transactions on Knowledge and Data Engineering 2022.

=======
## Multi-modal Detection
- EANN: Event Adversarial Neural Networks for Multi-Modal Fake News Detection. [[link]](https://dl.acm.org/doi/abs/10.1145/3219819.3219903) [[code]](https://github.com/yaqingwang/EANN-KDD18).
  - W Yaqing, Fenglong Ma, Zhiwei Jin, Ye Yuan, Guangxu Xun, Kishlay Jha, Lu Su, and Jing Gao.

- Multi-Modal Adversarial Adaptive Network for Misinformation Detection on Social Media [[link]](https://ieeexplore.ieee.org/abstract/document/9859648/).
  - L Zhang, P Zhang, X Zhu, L Liu, H Xu, ICME, 2022.

- Improving Generalization for Multimodal Fake News Detection [[link]](https://dl.acm.org/doi/abs/10.1145/3591106.3592230).
  - S Tahmasebi, S Hakimov, R Ewerth, ICMR, 2023.

- MRML: Multimodal Rumor Detection by Deep Metric Learning [[link]](https://ieeexplore.ieee.org/abstract/document/10096188).
  - L Peng, S Jian, D Li, S Shen, ICASSP, 2023.

- Graph Interactive Network with Adaptive Gradient for Multi-Modal Rumor Detection [[link]](https://dl.acm.org/doi/abs/10.1145/3591106.3592250).
  - T Sun, Z Qian, P Li, Q Zhu, ICMR, 2023.

- AdaDebunk: An Efficient and Reliable Deep State Space Model for Adaptive Fake News Early Detection [[link]](https://dl.acm.org/doi/abs/10.1145/3511808.3557227).
  - K Li, B Guo, S Ren, Z Yu, CIKM, 2022.

- Multi-modal Fake News Detection on Social Media via Multi-grained Information Fusion [[link]](https://dl.acm.org/doi/abs/10.1145/3591106.3592271).
- Y Zhou, Y Yang, Q Ying, Z Qian, X Zhang, ICMR, 2023.

## Multi-modal Detection
- EANN: Event Adversarial Neural Networks for Multi-Modal Fake News Detection.
  [[link]](https://dl.acm.org/doi/10.1145/3219819.3219903)
  [[code]](https://github.com/yaqingwang/EANN-KDD18)
  - Y Wang, F Ma, Z Jin, Y Yuan, G Xun, K Jha, L Su, J Gao. *KDD*, 2018.

- MVAE: Multimodal Variational Autoencoder for Fake News Detection.
  [[link]](https://dl.acm.org/doi/10.1145/3308558.3313552)
  [[code]](https://github.com/dhruvkhattar/MVAE)
  - D Khattar, JS Goud, M Gupta, V Varma. *WWW*, 2019.
    
- A multimodal fake news detection model based on crossmodal attention residual and multichannel convolutional neural networks.
  [[link]](https://www.sciencedirect.com/science/article/pii/S0306457320309304)
  - C Song, N Ning, Y Zhang, B Wu. Information Processing & Management, 2021.
 
- Exploiting multi-domain visual information for fake news detection.
  [[link]](https://ieeexplore.ieee.org/document/8970940)
  - P Qi, J Cao, T Yang, J Guo, J Li. *ICDM*, 2019.
 
- Hierarchical multi-modal contextual attention network for fake news detection.
  [[link]](https://dl.acm.org/doi/10.1145/3404835.3462871)
  - S Qian, J Wang, J Hu, Q Fang, C Xu. *SIGIR*, 2021.
 

- Detecting fake news by exploring the consistency of multimodal data.
  [[link]](https://www.sciencedirect.com/science/article/pii/S0306457321001060)
  - J Xue, Y Wang, Y Tian, Y Li, L Shi, L Wei. Information Processing & Management, 2021.

- HAN, image captioning, and forensics ensemble multimodal fake news detection.
  [[link]](https://www.sciencedirect.com/science/article/pii/S0020025521002826)
  - P Meel, DK Vishwakarma. Information Sciences, 2021.

 
- Spotfake+: A multimodal framework for fake news detection via transfer learning.
  [[link]](https://dl.acm.org/doi/10.1145/3404835.3462871)
  - S Singhal, A Kabra, M Sharma, RR Shah. *AAAI*, 2020.

- Multimodal Fusion with Co-Attention Networks for Fake News Detection.
  [[link]](https://aclanthology.org/2021.findings-acl.226/)
  - Y Wu, P Zhan, Y Zhang, L Wang. *ACL*, 2021.
## Using Social Context

### User Information
- Learning Sparse Alignments via Optimal Transport for Cross-Domain Fake News Detection [[link]](https://ieeexplore.ieee.org/abstract/document/10095281) [[code]](https://github.com/OceanTangWei/NOT).
  - W Tang, Z Ma, H Sun, J Wang, ICASSP, 2023.

- Unsupervised Rumor Detection Based on Propagation Tree VAE [[link]](https://ieeexplore.ieee.org/abstract/document/10103675).
  - L Fang, K Feng, K Zhao, A Hu, T, Li, TKDE, 2023. 



- GCAN: Graph-aware Co-Attention Networks for Explainable Fake News Detection on Social Media.
  [[link]](https://aclanthology.org/2020.acl-main.48/)
  [[code]](https://github.com/l852888/GCAN)
  - YJ Lu, CT Li. *ACL*, 2020.


- FANG: Leveraging Social Context for Fake News Detection Using Graph Representation.
  [[link]](https://dl.acm.org/doi/10.1145/3340531.3412046)
  [[code]](https://github.com/nguyenvanhoang7398/FANG)
  - VH Nguyen, K Sugiyama, P Nakov. *CIKM *, 2020.

- Temporally evolving graph neural network for fake news detection.
  [[link]](https://www.sciencedirect.com/science/article/pii/S0306457321001965)
  - C Song, K Shu, B Wu. Information Processing & Management, 2021.

- Beyond News Contents: The Role of Social Context for Fake News Detection.
  [[link]](https://dl.acm.org/doi/10.1145/3289600.3290994)
  - K Shu, S Wang, H Liu. *WSDM*, 2019.

- User Preference-aware Fake News Detection.
  [[link]](https://dl.acm.org/doi/abs/10.1145/3404835.3462990)
  [[code]](https://github.com/safe-graph/GNN-FakeNews)
  - Y Dou, K Shu, C Xia, PS Yu, L Sun. *SIGIR*, 2021.

- FNED: a deep network for fake news early detection on social media.
  [[link]](https://dl.acm.org/doi/10.1145/3386253)
  - Y Liu, YFB Wu. ACM Transactions on Information Systems, 2020.
 
- Hierarchical propagation networks for fake news detection: Investigation and exploitation.
  [[link]](https://ojs.aaai.org/index.php/ICWSM/article/view/7329)
  - K Shu, D Mahudeswaran, S Wang, H Liu. *ICWSM*, 2020.
 
    
- Propagation2Vec: Embedding partial propagation networks for explainable fake news early detection.
  [[link]](https://www.sciencedirect.com/science/article/pii/S030645732100114X)
  - A Silva, Y Han, L Luo, S Karunasekera. Information Processing & Management, 2021.
 
- Rumor detection on social media with graph structured adversarial learning.
  [[link]](www.ijcai.org/Proceedings/2020/197)
  - X Yang, Y Lyu, T Tian, Y Liu, Y Liu, X Zhang. *IJCAI*, 2021.


- Embracing domain differences in fake news: Cross-domain fake news detection using multi-modal data.
  [[link]](https://ojs.aaai.org/index.php/AAAI/article/view/16134)
  - A Silva, L Luo, S Karunasekera, C Leckie. *AAAI*, 2021.
 
    
 
### Comment
- Cross-Modal Adversarial Contrastive Learning for Multi-Modal Rumor Detection [[link]](https://ieeexplore.ieee.org/abstract/document/10096883).
  - T Zou, Z Qian, P Li, Q Zhu, ICASSP, 2023.

- Weak Supervision for Fake News Detection via Reinforcement Learning.
  [[link]](https://aaai.org/papers/00516-weak-supervision-for-fake-news-detection-via-reinforcement-learning/)
  - Y Wang, W Yang, F Ma, J Xu, B Zhong. *AAAI*, 2020.
 
  
- Weak Supervision for Fake News Detection via Reinforcement Learning.
  [[link]](https://aaai.org/papers/00516-weak-supervision-for-fake-news-detection-via-reinforcement-learning/)
  - Y Wang, W Yang, F Ma, J Xu, B Zhong. *AAAI*, 2020.
## Fact-checking
- A Survey on Automated Fact-Checking [[link]](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00454/109469/A-Survey-on-Automated-Fact-Checking).
    - Z Guo, M Schlichtkrull, A Vlachos. Transactions of the ACL, 2022.

- Evidence-aware Fake News Detection with Graph Neural Networks [[link]](https://dl.acm.org/doi/abs/10.1145/3485447.3512122)
    - W Xu, J Wu, Q Liu, S Wu, L Wang, WWW, 2022.

- Open-Domain, Content-based, Multi-modal Fact-checking of Out-of-Context Images via Online Resources [[link]](https://openaccess.thecvf.com/content/CVPR2022/html/Abdelnabi_Open-Domain_Content-Based_Multi-Modal_Fact-Checking_of_Out-of-Context_Images_via_Online_Resources_CVPR_2022_paper.html)
    - S Abdelnabi, R Hasan, M Fritz, CVPR, 2022.

- Sentence-Level Evidence Embedding for Claim Verification with Hierarchical Attention Networks [[link]](https://ink.library.smu.edu.sg/sis_research/4557/).
    - J Ma, W Gao, S Joty, KF Wong. ACL, 2019.

- Evidence Inference Networks for Interpretable Claim Verification [[link]](https://ink.library.smu.edu.sg/sis_research/4557/).
    - L Wu, Y Rao, L Sun, W He. AAAI, 2021.

- GERE: Generative Evidence Retrieval for Fact Verification [[link]](https://dl.acm.org/doi/abs/10.1145/3477495.3531827)
    - J Chen, R Zhang, J Guo, Y Fan, X Cheng, SIGIR, 2022.

- Where Are the Facts? Searching for Fact-checked Information to Alleviate the Spread of Fake News [[link]](https://aclanthology.org/2020.emnlp-main.621/)
    - N Vo, K Lee, EMNLP, 2020.

- DeClarE: Debunking Fake News and False Claims using Evidence-Aware Deep Learning [[link]](https://aclanthology.org/D18-1003/)
    - K Popat, S Mukherjee, A Yates, G Weikum, EMNLP, 2020.

- Evidence-Aware Hierarchical Interactive Attention Networks for Explainable Claim Verification
    - L Wu, Y Rao, X Yang, W Wang, A Nazir, IJCAI, 2021.

-  The Rise of Guardians: Fact-checking URL Recommendation to Combat Fake News [[link]](https://dl.acm.org/doi/abs/10.1145/3209978.3210037)
    - N Vo, K Lee, SIGIR, 2018.

- Bias Mitigation for Evidence-aware Fake News Detection by Causal Intervention
    - J Wu, Q Liu, W Xu, S Wu, SIGIR, 2022.

- Fake News Detection via Knowledge-driven Multimodal Graph Convolutional Networks.
  [[link]](https://dl.acm.org/doi/10.1145/3372278.3390713)
  - Y Wang, S Qian, J Hu, Q Fang, C Xu. *ICMR*, 2020.
 
    
- Where Are the Facts? Searching for Fact-checked Information to Alleviate the Spread of Fake News.
  [[link]](https://aclanthology.org/2020.emnlp-main.621/)
  [[code]](https://github.com/nguyenvo09/EMNLP2020)
  - N Vo, K Lee. *EMNLP*, 2020.
 
- Mining Dual Emotion for Fake News Detection.
  [[link]](https://dl.acm.org/doi/10.1145/3442381.3450004)
  [[code]](https://github.com/RMSnow/WWW2021)
  - X Zhang, J Cao, X Li, Q Sheng, L Zhong. *WWW*, 2021.
 
    
- Kan: Knowledge-aware attention network for fake news detection.
  [[link]](https://aaai.org/papers/00081-kan-knowledge-aware-attention-network-for-fake-news-detection/)
  - Y Dun, K Tu, C Chen, C Hou, X Yuan. *AAAI*, 2021.
## Datasets

## Other

- ReCOVery: A Multimodal Repository for COVID-19 News Credibility Research.
  [[link]](https://dl.acm.org/doi/10.1145/3340531.3412880)
  [[code]](http://coronavirus-fakenews.com)
  - X Zhou, A Mulay, E Ferrara, R Zafarani. *CIKM *, 2020.

- Toward a better performance evaluation framework for fake news classification.
  [[link]](https://ojs.aaai.org/index.php/ICWSM/article/view/7279)
  - L Bozarth, C Budak. *ICWSM*, 2020.
 
    
- Can the crowd identify misinformation objectively? The effects of judgment scale and assessor's background.
  [[link]](https://dl.acm.org/doi/10.1145/3397271.3401112)
  - K Roitero, M Soprano, S Fan, D Spina. *SIGIR*, 2020.
