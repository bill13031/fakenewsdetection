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

- Weak Supervision for Fake News Detection via Reinforcement Learning.
  [[link]](https://aaai.org/papers/00516-weak-supervision-for-fake-news-detection-via-reinforcement-learning/)
  - Y Wang, W Yang, F Ma, J Xu, B Zhong. *AAAI*, 2020.
 
  
- Weak Supervision for Fake News Detection via Reinforcement Learning.
  [[link]](https://aaai.org/papers/00516-weak-supervision-for-fake-news-detection-via-reinforcement-learning/)
  - Y Wang, W Yang, F Ma, J Xu, B Zhong. *AAAI*, 2020.
## Fact-checking

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
