---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

**I am currently an Excellence Postdoc (卓越百人博士后) at the School of Computer Science and Engineering, Beihang University (BUAA), advised by Prof. <a href="https://myjianxin.github.io/" target="_blank"><b>Jianxin Li</b></a>.**

Previously, I was a Visiting Scholar at the Department of Computer Science, Kent State University (KSU), United State, advised by Prof. <a href="https://www.cs.kent.edu/~xlian/index.html" target="_blank"><b>Xiang Lian</b></a> and Prof. <a href="https://scholar.google.com/citations?user=lNQmMTMAAAAJ" target="_blank"><b>Ruoming Jin</b></a>. 

I received my Ph.D. Degree in June, 2025 from East China Normal University (ECNU), China, supervised by Prof. <a href="https://faculty.ecnu.edu.cn/_s43/cms_en/main.psp" target="_blank"><b>Mingsong Chen</b></a>.

I obtained my Bachelor Degree in June, 2020 from Guangxi Normal University (GXNU), China, supervised by Prof. <a href="http://www.cs.gxnu.edu.cn/2015/0915/c4858a94329/pagem.htm" target="_blank"><b>Xianxian Li</b></a> and Prof. <a href="http://www.cs.gxnu.edu.cn/wjl/listm.htm" target="_blank"><b>Jingli wu</b></a>.

My research interests mainly include:

- ***Graph Data Mining and Analysis***

  - Graph Query Processing and Optimization

  - Graph Learning

- ***Big Data***

  - Efficient GNN Training

  - Time Series Data

  - Transportation Optimization

<!-- I have published more than 30 papers at top conferences and journals such as VLDB, ICDE, AAAI, IJCAI. -->

I have published more than 30 papers <a href='https://scholar.google.com/citations?user=7O_KB40AAAAJ&hl'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> at top conferences and journals such as SIGMOD, VLDB, ICDE, AAAI, IJCAI.

Here are the links to some of my professional websites: <b><a a href="CV.pdf" target="_blank">Resume</a></b>, <b><a href="https://scholar.google.com/citations?user=7O_KB40AAAAJ&hl" target="_blank">Google Scholar</a></b>, and <b><a href="https://dblp.uni-trier.de/pid/192/4957-1.html" target="_blank">DBLP</a></b>.

<font color=blue>
<b>I am open to collaborating in the fields of data mining and artificial intelligence. Please reach out if you are interested. (yutongye@buaa.edu.cn)</b>
</font>


# 🔥 News
- *2026.08*: &nbsp;🎉🎉 Our paper got accepted by IEEE TCAD (<font color=red><b>CCF-A</b></font>)! 
- *2026.07*: &nbsp;🎉🎉 Our paper got accepted by ESWEEK (CODES) 2026 (<font color=red><b>CCF-B</b></font>)! 
- *2026.05*: &nbsp;🎉🎉 Our paper got accepted by KDD 2026 (<font color=red><b>CCF-A</b></font>)! 
- *2026.05*: &nbsp;🎉🎉 Our paper got accepted by IJCAI 2026 (<font color=red><b>CCF-A</b></font>)! 
- *2026.04*: &nbsp;🎉🎉 Our paper got accepted by ICS 2026 (<font color=red><b>CCF-B</b></font>)! 
- *2026.02*: &nbsp;🎉🎉 Our paper got accepted by ICDE 2026 (<font color=red><b>CCF-A</b></font>)! 
- *2025.12*: &nbsp;🎉🎉 Our paper got accepted by JSA 2025 (<font color=red><b>CCF-B</b></font>)! 
- *2025.08*: &nbsp;🎉🎉 Our paper got accepted by SIGMOD 2026 (<font color=red><b>CCF-A</b></font>)! 
- *2025.08*: &nbsp;🎉🎉 Our paper got accepted by CIKM 2025 (<font color=red><b>CCF-B</b></font>)!
- *2025.07*: &nbsp;🎉🎉 Our paper got accepted by VLDB 2025 (<font color=red><b>CCF-A</b></font>)!
- *2025.07*: &nbsp;🎉🎉 Our paper got accepted by SEKE 2025 (<font color=red><b>CCF-C</b></font>)!
- *2025.04*: &nbsp;🎉🎉 Our paper got accepted by IJCAI 2025 (<font color=red><b>CCF-A</b></font>)!

# 📝 Publications 

<sup>#</sup> Equal Contribution

## Journal

***Statistics: PVLDB - 2, TCAD - 2, TIFS - 1, TSC - 1, JSA - 2, IJHPCA - 1, JS - 1, JCSC - 1, JPCS - 1, IET-ITS - 1***

**[J13]** Zhe Feng, **Yutong Ye<sup>#</sup>**, Jianxun Zhou, Wenbin Guo, Lihua Xu, Wendong Lu, Yunlai Zhu, Zuyu Xu, Zuheng Wu, and Yuehua Dai. [SpiceDiff-Agent: Simulation-Efficient LLM-Guided Planning for Specification-Driven Analog Circuit Netlist Repair](). IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (**IEEE TCAD, CCF-A**), 2026. (IF=2.9).

**[J12]** Jiepin Ding, Jun Xia, **Yutong Ye**, and Mingsong Chen. [Effective reinforcement learning-based dynamic flexible job shop scheduling using two-stage dispatching](https://www.sciencedirect.com/science/article/pii/S1383762125003364). Journal of Systems Architecture (**JSA, CCF-B**), 2025. (IF=4.5).

**[J11]** Qi Wen, **Yutong Ye**, Xiang Lian, and Mingsong Chen. [S^3AND: Efficient Subgraph Similarity Search Under Aggregated Neighbor Difference Semantics](https://www.vldb.org/pvldb/vol18/p3708-wen.pdf). Proceedings of the Very Large Data Bases Conferences Endowment (**PVLDB, CCF-A**), 2025. (IF=2.86).

**[J10]** Shuhui Liang, **Yutong Ye**, and Jingli Wu. [An Effective Hybrid Optimization Algorithm for Static Rebalance Problem of Bicycle-sharing System](https://ietresearch.onlinelibrary.wiley.com/doi/10.1049/itr2.70050). IET Intelligent Transport Systems (**IET-ITS, CCF-C**), 2025. (IF=2.8).

**[J9]** **Yutong Ye**, Xiang Lian, and Mingsong Chen. [Efficient Exact Subgraph Matching via GNN-based Path Dominance Embedding](https://vldb.org/pvldb/volumes/17/paper/Efficient%20Exact%20Subgraph%20Matching%20via%20GNN-based%20Path%20Dominance%20Embedding). Proceedings of the Very Large Data Bases Conferences Endowment (**PVLDB, CCF-A**), 2024. (IF=2.86).

**[J8]** Yaning Yang, Xiao Du, **Yutong Ye**, Jiepin Ding, Ting Wang, Mingsong Chen, Keqin Li. [Multi-objective Deep Reinforcement Learning for Function Offloading in Serverless Edge Computing](https://ieeexplore.ieee.org/abstract/document/10740030). IEEE Transactions on Services Computing (**IEEE TSC, CCF-A**), 2024. (IF=5.5).

**[J7]** Zhusen Liu, Weizheng Wang, **Yutong Ye**, Nan Min, Zhenfu Cao, Lu Zhou, Zhe Liu. [Collusion-Resilient Cloud-Assisted Two-Party Computation Scheme in Heterogeneous Mobile Cloud Computing](https://ieeexplore.ieee.org/abstract/document/10601195/). IEEE Transactions on Information Forensics and Security (**IEEE TIFS, CCF-A**), 2024. (IF=6.3).

**[J6]** Jiepin Ding, Jun Xia, **Yutong Ye**, Yuan Ma, and Mingsong Chen. [Knowledge-based Effective Dispatch for Job Shop Scheduling](https://www.worldscientific.com/doi/abs/10.1142/S0218126624502608). Journal of Circuits, Systems and Computers (**JCSC, SCI**), 2024. (IF=1.55).

**[J5]** **Yutong Ye**, Jiepin Ding, Ting Wang, Junlong Zhou, Xian Wei, and Mingsong Chen. [FairLight: Fairness-Aware Autonomous Traffic Signal Control with Hierarchical Action Space](https://ieeexplore.ieee.org/abstract/document/9969874). IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (**IEEE TCAD, CCF-A**), 2022. (IF=2.9).

**[J4]** Wupan Zhao, **Yutong Ye**, Jiepin Ding, Ting Wang, Tongquan Wei, and Mingsong Chen. [IPDALight: Intensity-and Phase Duration-aware Traffic Signal Control based on Reinforcement Learning](https://www.sciencedirect.com/science/article/pii/S1383762121002587). Journal of Systems Architecture (**JSA, CCF-B**), 2022. (IF=4.5).

**[J3]** **Yutong Ye**, Hongyin Zhu, Chaoying Zhang, and Binghai Wen. [Efficient Graphic Processing Unit Implementation of the Chemical-Potential Multiphase Lattice Boltzmann Method](https://journals.sagepub.com/doi/full/10.1177/1094342020968272). The International Journal of High-Performance Computing Applications (**IJHPCA, SCI**), 2021. (IF=3.1).

**[J2]** Fengru Ling, Gang Huang, Hao Tang, Mengmeng Geng, **Yutong Ye**, and Zhangrong Qin. [A Lattice Boltzmann Simulation of Coalescence-induced Droplet Jumping on Superhydrophobic Surfaces](https://iopscience.iop.org/article/10.1088/1742-6596/1300/1/012094/meta). Journal of Physics: Conference Series (**JPCS, EI**), 2019. (IF=0.48).

**[J1]** Jingli Wu, **Yutong Ye**, and Yong Wu. [Roadside Unit Deployment Algorithm based on Useful Contribution](https://www.jos.org.cn/josen/article/abstract/18005?st=article_issue). Journal of Software (**JS, CCF-A**), 2018. (IF=2.66).


## Conference

***Statistics: SIGMOD - 1, ICDE - 2, KDD - 1, AAAI - 1, IJCAI - 3, CVPR - 1, DAC - 1, RTSS - 1, CIKM - 1, CODES - 1, ICS - 1, ICASSP - 2, COGSCI - 1, KSEM - 1, ICPADS - 1, SEKE - 1***

**[C20]** Zhe Feng, **Yutong Ye<sup>#</sup>**, Jianxun Zhou, Wenbin Guo, Lihua Xu, Wendong Lu, Yunlai Zhu, Zuyu Xu, Zuheng Wu, and Yuehua Dai. [SpiceDiff-Agent: Simulation-Efficient LLM-Guided Planning for Specification-Driven Analog Circuit Netlist Repair](). IEEE/ACM Embedded Systems Week (**ESWEEK (CODES), CCF-B**), Barcelona, Spain, October 4-9, 2026.

**[C19]** Yuhan Wang, Yibo Ding, **Yutong Ye**, Mufan Zhao, Wenbo Zhang, Ruijie Wang, and Jianxin Li. [G^2LoRA: Gradient Orthogonal Low-Rank Adaptation Framework for Graph Continual Learning on Text-Attributed Graphs](). Conference on Knowledge Discovery and Data Mining (**KDD, CCF-A**), Jeju, Korea, August 9-13, 2026. 

**[C18]** Yiyang Zhang, Yutong Ye, Yingbo Zhou, Nan Zhang, Xiang Lian, and Mingsong Chen. [Similarity-guided Structural Matching Learning for Graph Dataset Condensation](). International Joint Conference on Artificial Intelligence (**IJCAI, CCF-A**), Bremen, Germany, August 15-21, 2026. 

**[C17]** Wujie Xiong, Hao Zhou, **Yutong Ye**, Ruoming Jin, and Lei Xu. [CipherSkip: Efficient Sparse Matrix Multiplication with FHE](). ACM International Conference on Supercomputing (**ICS, CCF-B**), Belfast, Northern Ireland, United Kingdom, July 6-9, 2026. 

**[C16]** Yang Liu, Mengyi Yan, Jiao Xue, Weilong Ren, **Yutong Ye**, Haoyi Zhou, Zhumin Chen, and Jianxin Li. [SPARQ: A Cost-Efficient Framework for Offline Table Question Answering via Adaptive Routing](). IEEE International Conference on Data Engineering (**ICDE, CCF-A**), Montréal, Canada, May 4-8, 2026. 

**[C15]** **Yutong Ye**, Xiang Lian, Nan Zhang, and Mingsong Chen. [Continuous Subgraph Matching via Cost-Model-based Dynamic Vertex Dominance Embeddings](https://dl.acm.org/doi/abs/10.1145/3769774). International Conference on Management of Data (**SIGMOD, CCF-A**), Bengaluru, India, May 31-June 5, 2026. 

**[C14]** Qi Wen, Yiyang Zhang, **Yutong Ye**, Yingbo Zhou, Nan Zhang, Xiang Lian and Mingsong Chen. [GCLS$^2$: Towards Efficient Community Detection Using Graph Contrastive Learning with Structure Semantics.](https://dl.acm.org/doi/abs/10.1145/3746252.3761327). The Conference on Information and Knowledge Management (**CIKM, CCF-B**), Seoul, Korea, Novemeber 10-14, 2025 (Acceptance Rate: 21.7%).

**[C13]** Yuyang Wang, **Yutong Ye**, Yingbo Zhou, Qi Wen, Xiang Lian, Xian Wei and Mingsong Chen. [MuseCNN: Embedding-Guided Polyphonic Music Accompaniment Generation](). International Conference on Software Engineering and Knowledge Engineering (**SEKE, CCF-C**), Pompeii, Italy, September 29-30, 2025. (Acceptance Rate: 36%).

**[C12]** Li Sun, Suyang Zhou, Bowen Fang, Hechuan Zhang, Junda Ye, **Yutong Ye**, Philip Yu. [Trace: Structural Riemannian Bridge Matching for Transferable Source Localization](https://ijcai-preprints.s3.us-west-1.amazonaws.com/2025/1963.pdf). International Joint Conference on Artificial Intelligence (**IJCAI, CCF-A**), Montreal, Canada, August 16-22, 2025. (Acceptance Rate: 19.3%).

**[C11]** Yingbo Zhou, Zhihao Yue, **Yutong Ye**, Pengyu Zhang, Xian Wei, and Mingsong Chen. [EqGAN: Reformation-based Feature Equalization Fusion for Few-shot Image Generation](https://ieeexplore.ieee.org/abstract/document/10888354/). IEEE International Conference on Acoustics, Speech, and Signal Processing (**ICASSP, CCF-B**), Hyderabad, India, Apr. 6-11, 2025.

**[C10]** Yingbo Zhou, Pengyu Zhang, **Yutong Ye**, Zhihao Yue, Xian Wei, and Mingsong Chen. [FiTGAN: Content Fusion with Style Transformation for Few-shot Image Generation](https://ieeexplore.ieee.org/abstract/document/10888773). IEEE International Conference on Acoustics, Speech, and Signal Processing (**ICASSP, CCF-B**), Hyderabad, India, Apr. 6-11, 2025.

**[C9]** Yingbo Zhou, **Yutong Ye**, Pengyu Zhang, Xian Wei, and Mingsong Chen. [Exact Fusion via Feature Distribution Matching for Few-shot Image Generation](https://openaccess.thecvf.com/content/CVPR2024/html/Zhou_Exact_Fusion_via_Feature_Distribution_Matching_for_Few-shot_Image_Generation_CVPR_2024_paper.html). Conference on Computer Vision and Pattern Recognition (**CVPR, CCF-A**), Seattle, USA, Jun. 17-21, 2024. (Acceptance Rate: 24%).

**[C8]** Nan Zhang, **Yutong Ye**, Xiang Lian, and Mingsong Chen. [Top-L Most Influential Community Detection Over Social Networks](https://ieeexplore.ieee.org/abstract/document/10639540). IEEE International Conference on Data Engineering (**ICDE, CCF-A**), Utrecht, Netherlands, May. 13-17, 2024. (Acceptance Rate: 20%).

**[C7]** Xiao Du, **Yutong Ye**, Pengyu Zhang, Yaning Yang, Mingsong Chen, and Ting Wang. [Situation-Dependent Causal Influence-Based Cooperative Multi-Agent Reinforcement Learning](https://ojs.aaai.org/index.php/AAAI/article/view/29684). AAAI Conference on Artificial Intelligence (**AAAI, CCF-A**), Vancouver, Canada, Feb. 20-27, 2024. (Acceptance Rate: 24%).

**[C6]** Yang Yu, Yingbo Zhou, Yaokang Zhu, **Yutong Ye**, Liangyu Chen, and Mingsong Chen. [ECKT: Enhancing Code Knowledge Tracing via Large Language Models](https://escholarship.org/uc/item/8001b5mp). Cognitive Science Society Annual Conference (**COGSCI, CCF-B**), Rotterdam, Netherlands, Jul. 24-27, 2024.

**[C5]** **Yutong Ye**, Zhiwei Ling, Yaning Yang, Xian Wei, Chen Cheng, Su Chen, and Mingsong Chen. [Brief Industry Paper: RTLight: Digital Twin-based Real-Time Federated Traffic Signal Control](https://ieeexplore.ieee.org/abstract/document/10406112). Real-Time Systems Symposium (**RTSS, CCF-A**), Taipei, China, Dec. 5-8, 2023. (Acceptance Rate: 28%).

**[C4]** Jiali Wang, **Yutong Ye**, Ting Wang, and Mingsong Chen. [LWSA: A Learning-Based Workflow Scheduling Algorithm for Energy-Efficient UAV Delivery System](https://ieeexplore.ieee.org/abstract/document/10476313). IEEE International Conference on Parallel and Distributed Systems (**ICPADS, CCF-C**), Ocean Flower Island, China, Dec. 17-21, 2023. (Acceptance Rate: 37%).

**[C3]** **Yutong Ye**, Yingbo Zhou, Jiepin Ding, Ting Wang, Mingsong Chen, and Xiang Lian. [InitLight: Initial Model Generation for Traffic Signal Control Using Adversarial Inverse Reinforcement Learning](https://dl.acm.org/doi/abs/10.24963/ijcai.2023/550). International Joint Conference on Artificial Intelligence (**IJCAI, CCF-A**), Macao, China, Aug. 19-25, 2023. (Acceptance Rate: 14%).

**[C2]** **Yutong Ye**, Wupan Zhao, Tongquan Wei, Shiyan Hu, and Mingsong Chen. [FedLight: Federated Reinforcement Learning for Autonomous Multi-Intersection Traffic Signal Control](https://ieeexplore.ieee.org/abstract/document/9586175). Design Automation Conference (**DAC, CCF-A**), San Francisco, USA, Jun. 23-27, 2021. (Acceptance Rate: 23%).

**[C1]** Jingli Wu, Yong Wu, Jinyan Wang, and **Yutong Ye**. [A Parthenogenetic Algorithm for Deploying the Roadside Units in Vehicle Networks](https://link.springer.com/chapter/10.1007/978-3-319-99247-1_8). International Conference on Knowledge Science, Engineering and Management (**KSEM, CCF-C**), Changchun, China, Aug. 17-19, 2018. (Acceptance Rate: 18%).



## Technical Report

***Statistics: Technical Report - 18***

**[R18]** Yuhan Wang, Yibo Ding, **Yutong Ye**, Mufan Zhao, Wenbo Zhang, Ruijie Wang, and Jianxin Li. [G2LoRA: Gradient Orthogonal Low-Rank Adaptation Framework for Graph Continual Learning on Text-Attributed Graphs](https://arxiv.org/abs/2606.01873). arXiv: 2606.01873, 2026.

**[R17]** Xuefei Wang, Jialu Wang, Fengbo Zhang, Yihan Hu, Di Zhang, **Yutong Ye**, Yikun Ban, Jun Han, and Ruijie Wang. [MasFACT: Continual Multi-Agent Topology Learning via Geometry-Aware Posterior Transfer](https://arxiv.org/abs/2605.17361). arXiv: 2605.17361, 2026.

**[R16]** Yingbo Zhou, **Yutong Ye**, Zhiwei Ling, Shuhao Li, Rui Qian, Jian Xiong, Li Sun, and Dejing Dou. [PAMNet: Cycle-aware Phase-Amplitude Modulation Network for Multivariate Time Series Forecasting](https://arxiv.org/abs/2605.02938). arXiv: 2605.02938, 2026.

**[R15]** Yingbo Zhou, **Yutong Ye**, Shuhao Li, Rui Qian, Qiang Huang, Lemao Liu, Li Sun, and Dejing Dou. [PAMod: Modeling Cyclical Shifts via Phase-Amplitude Modulation for Non-stationary Time Series Forecasting](https://arxiv.org/abs/2605.00466). arXiv: 2605.00466, 2026.

**[R14]** **Yutong Ye**, Weilong Ren, Yang Liu, Mengyi Yan, Ruijie Wang, Li Sun, Jianxin Li, and Philip S. Yu. [LIVE: Learnable Monotonic Vertex Embedding for Efficient Exact Subgraph Matching (Technical Report)](https://arxiv.org/abs/2604.19116). arXiv: 2604.19116, 2026.

**[R13]** Beibei Xu, **Yutong Ye**, Chuyun Shen, Yingbo Zhou, Cheng Chen, and Mingsong Chen. [HyEvo: Self-Evolving Hybrid Agentic Workflows for Efficient Reasoning](https://arxiv.org/abs/2603.19639). arXiv: 2603.19639, 2026.

**[R12]** Wujie Xiong, Hao Zhou, **Yutong Ye**, Ruoming Jin, and Lei Xu. [Scaling Sparse Matrix Computation for Secure Outsourced Computing](https://eprint.iacr.org/2026/297). Cryptology ePrint Archive, Paper 2026/297, 2025.

**[R11]** Qi Wen, Xiang Lian, Nan Zhang, **Yutong Ye**, and Mingsong Chen. [S3GND: An Effective Learning-Based Approach for Subgraph Similarity Search Under Generalized Neighbor Difference Semantics (Technical Report)](https://arxiv.org/abs/2602.19167v2). arXiv: 2602.19167, 2026.

**[R10]** Qi Wen, **Yutong Ye**, Xiang Lian, and Mingsong Chen. [S3AND: Efficient Subgraph Similarity Search Under Aggregated Neighbor Difference Semantics (Technical Report)](https://arxiv.org/abs/2505.00393). arXiv: 2505.00393, 2025.

**[R9]** **Yutong Ye**, Yingbo Zhou, Zhusen Liu, Xiao Du, Hao Zhou, Xiang Lian, and Mingsong Chen. [FitLight: Federated Imitation Learning for Plug-and-Play Autonomous Traffic Signal Control](https://arxiv.org/abs/2502.11937). arXiv: 2502.11937, 2025.

**[R8]** Nan Zhang, **Yutong Ye**, Yuyang Wang, Xiang Lian, and Mingsong Chen. [Effective Community Detection Over Streaming Bipartite Networks (Technical Report)](https://arxiv.org/abs/2411.01424). arXiv:2411.01424, 2024.

**[R7]** Qi Wen, Yiyang Zhang, **Yutong Ye**, Yingbo Zhou, Nan Zhang, Xiang Lian, and Mingsong Chen. [GCLS^2: Towards Efficient Community Detection using Graph Contrastive Learning with Structure Semantics](https://arxiv.org/abs/2410.11273). arXiv:2410.11273, 2024.

**[R6]** **Yutong Ye**, Xiang Lian, Nan Zhang, and Mingsong Chen. [Dynamic Subgraph Matching via Cost-Model-based Vertex Dominance Embeddings (Technical Report)](https://arxiv.org/abs/2407.16660). arXiv:2407.16660, 2024.

**[R5]** Qi Wen, Nan Zhang, <b>Yutong Ye</b>, Xiang Lian, Mingsong Chen. [Reverse Influential Community Search Over Social Networks (Technical Report)](https://arxiv.org/abs/2405.01510). arXiv:2405.01510, 2024.

**[R4]** Xiao Du, **Yutong Ye**, Pengyu Zhang, Yaning Yang, Mingsong Chen, Ting Wang. [Situation-Dependent Causal Influence-Based Cooperative Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2312.09539). arXiv:2312.09539, 2023.

**[R3]** Nan Zhang, <b>Yutong Ye</b>, Xiang Lian, and Mingsong Chen. [Top-L Most Influential Community Detection Over Social Networks (Technical Report)](https://arxiv.org/abs/2311.13162). arXiv:2311.13162, 2023.

**[R2]** **Yutong Ye**, Xiang Lian, and Mingsong Chen. [Efficient Exact Subgraph Matching via GNN-based Path Dominance Embedding (Technical Report)](https://arxiv.org/abs/2309.15641). arXiv:2309.15641, 2023.

**[R1]** Yingbo Zhou, Zhihao Yue, **Yutong Ye**, Pengyu Zhang, Xian Wei, and Mingsong Chen. [EqGAN: Feature Equalization Fusion for Few-shot Image Generation](https://arxiv.org/abs/2307.14638). arXiv:2307.14638, 2023.




# 💻 Research Projects and Grants

- **[PI]** Postdoctoral Fellowship Program of China Postdoctoral Science Foundation (CPSF), 240K RMB. (国家资助博士后研究人员计划C档资助)

- **[PI]** Research on Deep Learning Modeling and Processing Mechanisms for Complex Graph Queries. General Program of the China Postdoctoral Science Foundation (CPSF), 80K RMB. (中国博士后科学基金资助面上资助)

-	**[PI]** Youth Talents Support Project - Doctoral Student Special Program, China Association for Science and Technology, 40K RMB. (中国科协青年人才托举工程博士生专项)

-	**[PI]** Research on Intelligent Transportation System Based on Deep Learning. East China Normal University Academic Innovation Promotion Program for Excellent Doctoral Students, 30K RMB. (华东师范大学优秀博士生学术创新能力提升计划)

-	**[PI]** Study of Droplet Merging and Bouncing Phenomena using the Lattice Boltzmann Method. National Undergraduate Training Programs for Innovation and Entrepreneurship, 14K RMB. (国家级大学生创新创业训练计划)

-	**[PI]** Parallel Algorithm Design and Optimization of Chemical Potential Lattice Boltzmann Method Based on GPU Computing. National Undergraduate Training Programs for Innovation and Entrepreneurship, 7K RMB. (省级大学生创新创业训练计划)

-	**[PI]** Research on RSU Deployment Problem based on Intelligent Optimization Algorithm, National Undergraduate Training Programs for Innovation and Entrepreneurship, 4K RMB. (省级大学生创新创业训练计划)

- **[Co-PI]** Research on intelligent landslide identification and early warning driven by physics and data. Shanghai Cross-innovation Science and Education Integration Fund (Intelligent Science and Technology Category IV Peak Discipline), 50K RMB. (上海市智能科学与技术IV类高峰学科“交叉创新科教融合基金”)

-	**[Co-PI]** Research on scheduling optimization of green manufacturing and trusted services under crowd intelligence environment. Shanghai Cross-innovation Science and Education Integration Fund (Intelligent Science and Technology Category IV Peak Discipline), 50K RMB. (上海市智能科学与技术IV类高峰学科“交叉创新科教融合基金”)

- **[RA]**  Intelligent computing of big data on network behavior. The National Science Fund for Distinguished Young Scholars. 4M RMB. (国家杰出青年科学基金项目)

-	**[RA]** Key technologies and applications of information-physical fusion in smart cities. National Key Research and Development Program, 17M RMB. (国家重点研发计划重点专项)

- **[RA]** Collaborative Research: PPoSS: Planning: Efficient and scalable learning and management of distributed probabilistic graphs. U.S. National Science Foundation, 101K USD. (美国国家自然科学基金)

-	**[RA]** Research on key technologies for efficient and trustworthy construction of cyber-physical systems under uncertain environments. Natural Science Foundation of China, 0.65M RMB. (国家自然科学基金面上项目)

-	**[RA]** Research on key technologies for efficient and trusted construction of cloud-end cyber-physical systems. Natural Science Foundation of China, 0.54M RMB. (国家自然科学基金面上项目)



# 📐 Teaching

## Teaching Assistant for:
-	Cloud Computing Technology (Fall 2021)  
Location: Room 102, TianJiaBing Hall, East China Normal University (Putuo Campus)  
Office hour: 18:00pm - 20:45pm, Wednesday  
Instructor: Prof. Ting Wang



# 💬 Talks and Presentations

- **[Invited Talk]** Research on Intelligent Traffic Signal Control Based on Reinforcement Learning. China Computer Federation Embedded Systems Technical Committee (CCF ESTC), Xian, China, Aug. 15-17, 2025.

-	**[Invited Talk]** Learning-based Graph Query Optimization. Next-Generation Big Graph Learning and Analytics (co-located with IEEE BigData 2024), Washington D.C., Dec. 15, 2024

-	**[Oral]** Efficient Exact Subgraph Matching via GNN-based Path Dominance Embedding. International Conference on Very Large Databases (VLDB), Guangzhou, China, Aug. 26-30, 2024.

-	**[Poster]** Exact Fusion via Feature Distribution Matching for Few-shot Image Generation. Conference on Computer Vision and Pattern Recognition (CVPR), Seattle, USA, Jun. 17-21, 2024.

-	**[Oral]** Situation-Dependent Causal Influence-Based Cooperative Multi-Agent Reinforcement Learning. AAAI Conference on Artificial Intelligence (AAAI), Vancouver, Canada, Feb. 20-27, 2024. 

-	**[Poster]** Brief Industry Paper: RTLight: Digital Twin-based Real-Time Federated Traffic Signal Control. Real-Time Systems Symposium (RTSS), Taipei, China, Dec. 5-8, 2023.

-	**[Oral]** InitLight: Initial Model Generation for Traffic Signal Control Using Adversarial Inverse Reinforcement Learning. International Joint Conference on Artificial Intelligence (IJCAI), Macao, China, Aug. 19-25, 2023.

-	**[Oral]** FedLight: Federated Reinforcement Learning for Autonomous Multi-Intersection Traffic Signal Control. Design Automation Conference (DAC), San Francisco, USA, Jun. 23-27, 2021.



# 🎓 Professional Services

***Statistics: Journal Reviewer - 6, Conference/Workshop Reviewer - 11, External Conference Reviewer - 13, External Journal Reviewer - 8***

## Journal Reviewer for:
- Transactions on Machine Learning Research (TMLR)

- IEEE Transactions on Computers (TC)

- IEEE Transactions on Big Data (TBD)

- Knowledge and Information Systems (KIS)

-	Data & Knowledge Engineering (DKE)

-	Frontiers in Big Data (FBD)

- Journal of Circuits, Systems, and Computers (JCSC)

## Program Committee (PC) Member and Reviewer for:
-	ACM SIGMOD ARI (Availability & Reproducibility Initiative): 2024

- International Conference on Very Large Data Bases (VLDB): 2026

- ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD): 2026

-	International Conference on Machine Learning (ICML): 2025, 2026

-	Conference on Neural Information Processing Systems (NeurIPS): 2024, 2025, 2026

-	ACM The Web Conference (WWW): 2025, 2026

-	International Conference on Learning Representations (ICLR): 2025, 2026

- AAAI Conference on Artificial Intelligence (AAAI): 2026

- International Joint Conference on Artificial Intelligence (IJCAI-ECAI): 2026

- ACM International Conference on Information and Knowledge Management (CIKM): 2026

-	International Conference on Artificial Intelligence and Statistics (AISTATS): 2025, 2026

-	The European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases (ECML-PKDD): 2025, 2026

- Web Information Systems Engineering Conference (WISE): 2026

-	International Workshop on Next-Generation Big Graph Learning and Analytics (in conjunction with IEEE BigData Conference 2024)

## External Conference Reviewer for
-	International Conference on Very Large Data Bases (VLDB): 2024, 2025, 2026

-	IEEE International Conference on Data Engineering (ICDE): 2025, 2026

-	International Conference on Extending Database Technology (EDBT): 2024, 2025

-	ACM International Conference on Information and Knowledge Management (CIKM): 2024, 2025

-	ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD): 2023, 2024

-	International Joint Conference on Artificial Intelligence (IJCAI): 2024, 2025

-	The European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases (ECML-PKDD): 2023, 2025

-	Pacific Asia Knowledge Discovery and Data Mining (PAKDD): 2024, 2025, 2026

-	International Conference on Database Systems for Advanced Applications (DASFAA): 2023

-	The Asia Pacific Web (APWeb) and Web-Age Information Management (WAIM) Joint International Conference on Web and Big Data (APWeb-WAIM): 2023, 2024, 2025, 2026

-	International Conference on Advanced Data Mining and Applications (ADMA): 2023, 2024

-	IEEE International Conference on Robotics and Automation (ICRA): 2024

-	Design Automation Test in Europe (DATE): 2023

## External Journal Reviewer for
-	IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD)

-	Journal of Systems Architecture (JSA)

-	Journal of Circuits, Systems and Computers (JCSC)

- IEEE Transactions on Services Computing (IEEE TSC)

- IEEE Transactions on Information Forensics and Security (IEEE TIFS)

-	ACM Journal of Data and Information Quality (JDIQ)

-	The International Journal of High-Performance Computing Applications (IJHPCA)

- IET Intelligent Transport Systems (IET-ITS)



# 🏆 Honors and Awards
- *2025*, Outstanding Doctoral Dissertation Award of CCF Embedded Systems Technical Committee. 中国计算机学会嵌入式系统专委博士学位论文激励计划

- *2025*, Outstanding Graduate of Shanghai. 上海市优秀毕业生

-	*2024*, Youth Talents Support Project (Doctoral Student Special Program), China Association for Science and Technology. 中国科协青年人才托举工程博士生专项（首批）

-	*2023*, China National Scholarship (Ph.D. Student). 国家奖学金

-	*2023*, Grant Program for Global Research Visits, East China Normal University. 华东师范大学访学资助

-	*2023*, Outstanding Student of Software Engineering Institute, East China Normal University. 软件工程学院“杰出学生青年”

- *2022*, Chinese Scholarship Council (Joint Doctoral Program). 留学基金委联培资助

-	*2020*, Outstanding Graduate of Guangxi Province. 广西区优秀毕业生

- *2019*, President Scholarship of Guangxi Normal University. 校长奖学金

-	*2019*, China National Scholarship (Undergraduate Student). 国家奖学金

-	*2018*, China National Scholarship (Undergraduate Student). 国家奖学金
