---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

You can find the full list of my papers on <img src="https://upload.wikimedia.org/wikipedia/commons/c/c7/Google_Scholar_logo.svg" width="16" height="16"> [Google Scholar](https://scholar.google.com/citations?user=RL_CijgAAAAJ&hl=en&oi=ao).

Publications
---------------------
[1] [Integrating Random Regret Minimization-Based Discrete Choice Models with Mixed Integer Linear Programming for Revenue Optimization](https://arxiv.org/abs/2402.03118), Published in Journal of Computer Science, Springer, IF:1.9 (Q1), June 2024.

**Abstract:** This paper explores the critical domain of Revenue Management (RM) within Operations Research (OR), focusing on intricate pricing dynamics. Utilizing Mixed Integer Linear Programming (MILP) models, the study enhances revenue optimization by considering product prices as decision variables and emphasizing the interplay between demand and supply. Recent advancements in Discrete Choice Models (DCMs), particularly those rooted in Random Regret Minimization (RRM) theory, are investigated as potent alternatives to established Random Utility Maximization (RUM) based DCMs. Despite the widespread use of DCMs in RM, a significant gap exists between cutting-edge RRM-based models and their practical integration into RM strategies. The study addresses this gap by incorporating an advanced RRM-based DCM into MILP models, addressing pricing challenges in both capacitated and uncapacitated supply scenarios. The developed models demonstrate feasibility and offer diverse interpretations of consumer choice behavior, drawing inspiration from established RUM-based frameworks. This research contributes to bridging the existing gap in the application of advanced DCMs within practical RM implementations.

**Recommended Citation:** @article{talebi2024integrating,
  title={Integrating Random Regret Minimization-Based Discrete Choice Models with Mixed Integer Linear Programming for Revenue Optimization},
  author={Talebi, Amirreza and Haeri, Sayed Pedram},
  journal={arXiv preprint arXiv:2402.03118},
  year={2024}
}

**Download Paper Here:** [[PDF](http://pedramhaeri.github.io/files/Paper3.pdf)] [[Springer](https://arxiv.org/abs/2402.03118)]



[2] [Enhanced Cooperative Perception for Autonomous Vehicles Using Imperfect Communication](https://arxiv.org/abs/2404.08013), Published in IEEE International Conference on Distributed Computing in Smart Systems and the Internet of Things (DCOSS-IoT).

**Abstract:** Sharing and joint processing of camera feeds and sensor measurements, known as Cooperative Perception (CP), has emerged as a new technique to achieve higher perception qualities. CP can enhance the safety of Autonomous Vehicles (AVs) where their individual visual perception quality is compromised by adverse weather conditions (haze as foggy weather), low illumination, winding roads, and crowded traffic. To cover the limitations of former methods, in this paper, we propose a novel approach to realize an optimized CP under constrained communications. At the core of our approach is recruiting the best helper from the available list of front vehicles to augment the visual range and enhance the Object Detection (OD) accuracy of the ego vehicle. In this two-step process, we first select the helper vehicles that contribute the most to CP based on their visual range and lowest motion blur. Next, we implement a radio block optimization among the candidate vehicles to further improve communication efficiency. We specifically focus on pedestrian detection as an exemplary scenario. To validate our approach, we used the CARLA simulator to create a dataset of annotated videos for different driving scenarios where pedestrian detection is challenging for an AV with compromised vision. Our results demonstrate the efficacy of our two-step optimization process in improving the overall performance of cooperative perception in challenging scenarios, substantially improving driving safety under adverse conditions. Finally, we note that the networking assumptions are adopted from LTE Release 14 Mode 4 side-link communication, commonly used for Vehicle-to-Vehicle (V2V) communication. Nonetheless, our method is flexible and applicable to arbitrary V2V communications.

**Recommended Citation:** @article{sarlak2024enhanced,
  title={Enhanced Cooperative Perception for Autonomous Vehicles Using Imperfect Communication},
  author={Sarlak, Ahmad and Alzorgan, Hazim and Boroujeni, Sayed Pedram Haeri and Razi, Abolfazl and Amin, Rahul},
  journal={arXiv preprint arXiv:2404.08013},
  year={2024}
}

**Download Paper Here:** [[PDF](http://pedramhaeri.github.io/files/Paper4.pdf)] [[IEEE Xplore](https://arxiv.org/abs/2404.08013)]



[3] [A Comprehensive Survey of Research Towards AI-enabled Unmanned Aerial Systems in Pre-, Active-, and Post-Wildfire Management](https://www.sciencedirect.com/science/article/pii/S1566253524001477), Published in Information Fusion Journal, Elsevier, IF:18.6 (Q1), August 2024.

**Abstract:** Wildfires have emerged as one of the most destructive natural disasters worldwide, causing catastrophic losses. These losses have underscored the urgent need to improve public knowledge and advance existing techniques in wildfire management. Recently, the use of Artificial Intelligence (AI) in wildfires, propelled by the integration of Unmanned Aerial Vehicles (UAVs) and deep learning models, has created an unprecedented momentum to implement and develop more effective wildfire management. Although existing survey papers have explored learning-based approaches in wildfire, drone use in disaster management, and wildfire risk assessment, a comprehensive review emphasizing the application of AI-enabled UAV systems and investigating the role of learning-based methods throughout the overall workflow of multi-stage wildfire management, including pre-fire (e.g., vision-based vegetation fuel measurement), active-fire (e.g., fire growth modeling), and post-fire tasks (e.g., evacuation planning) is notably lacking. This survey synthesizes and integrates state-of-the-science reviews and research at the nexus of wildfire observations and modeling, AI, and UAVs — topics at the forefront of advances in wildfire management, elucidating the role of AI in performing monitoring and actuation tasks from pre-fire, through the active-fire stage, to post-fire management. To this aim, we provide an extensive analysis of the existing remote sensing systems with a particular focus on the UAV advancements, device specifications, and sensor technologies relevant to wildfire management. We also examine the pre-fire and post-fire management approaches, including fuel monitoring, prevention strategies, as well as evacuation planning, damage assessment, and operation strategies. Additionally, we review and summarize a wide range of computer vision techniques in active-fire management, with an emphasis on Machine Learning (ML), Reinforcement Learning (RL), and Deep Learning (DL) algorithms for wildfire classification, segmentation, detection, and monitoring tasks. Ultimately, we underscore the substantial advancement in wildfire modeling through the integration of cutting-edge AI techniques and UAV-based data, providing novel insights and enhanced predictive capabilities to understand dynamic wildfire behavior.

**Recommended Citation:** Boroujeni, Sayed Pedram Haeri, et al. "A comprehensive survey of research towards ai-enabled unmanned aerial systems in pre-, active-, and post-wildfire management." Information Fusion (2024): 102369.

**Download Paper Here:** [[PDF](http://pedramhaeri.github.io/files/Paper1.pdf)] [[ScienceDirect](https://ieeexplore.ieee.org/abstract/document/9721496)]



[4] [IC-GAN: An Improved Conditional Generative Adversarial Network for RGB-to-IR Image Translation with Applications to Forest Fire Monitoring](https://www.sciencedirect.com/science/article/pii/S0957417423024648), Published in Expert Systems with Applications, Elsevier, IF:8.5 (Q1), March 2024.

**Abstract:** This paper introduces a novel Deep Learning (DL) architecture for inferring temperature information from aerial true-color RGB images by transforming them into Infrared Radiation (IR) domain. This work is motivated by a few facts. First, off-the-shelf contemporary drones are typically equipped only with regular cameras. Second, IR heat-mapping cameras are costly and heavy for payload-limited drones. Third, additional communication channels and power supply would be needed when including IR cameras. Finally, IR cameras provide lower resolution and shorter distance ranges than RGB cameras. Therefore, learning-based translation of aerial IR recordings to RGB images can be extremely useful not only for new tests but also for offline processing of the currently available forest fire datasets with RGB images. We offer an Improved Conditional-Generative Adversarial Network (IC-GAN), where matched IR images are used as a condition to guide the translation process by the generator. The U-Net-based generator is concatenated with a mapper module to transform the output into a stack of diverse color spaces with learnable parameters. To avoid the unnecessary penalization of pixel-level disparities and achieve structural similarity, we include clustering alignment to the loss function. The proposed framework is compared against several state-of-the-art methods, including U-Net, Efficient U-Net, GAN, and Conditional-GAN from both subjective (human perception) and objective evaluation perspectives. The results support our method’s efficacy, demonstrating a significant improvement of around 6% in PSNR, 15% in UQI, 9% in SSIM, and 23% in IoU metrics.

**Recommended Citation:** @article{boroujeni2024ic,
  title={Ic-gan: An improved conditional generative adversarial network for rgb-to-ir image translation with applications to forest fire monitoring},
  author={Boroujeni, Sayed Pedram Haeri and Razi, Abolfazl},
  journal={Expert Systems with Applications},
  volume={238},
  pages={121962},
  year={2024},
  publisher={Elsevier}
}

**Download Paper Here:** [[PDF](http://pedramhaeri.github.io/files/Paper5.pdf)] [[ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0957417423024648)]



[5] [FLAME Diffuser: Grounded Wildfire Image Synthesis using Mask Guided Diffusion](https://arxiv.org/abs/2403.034638), Submitted to ArXiv Preprint, January 2024.

**Abstract:** The rise of machine learning in recent years has brought benefits to various research fields such as wide fire detection. Nevertheless, small object detection and rare object detection remain a challenge. To address this problem, we present a dataset automata that can generate ground truth paired datasets using diffusion models. Specifically, we introduce a mask-guided diffusion framework that can fusion the wildfire into the existing images while the flame position and size can be precisely controlled. In advance, to fill the gap that the dataset of wildfire images in specific scenarios is missing, we vary the background of synthesized images by controlling both the text prompt and input image. Furthermore, to solve the color tint problem or the well-known domain shift issue, we apply the CLIP model to filter the generated massive dataset to preserve quality. Thus, our proposed framework can generate a massive dataset of that images are high-quality and ground truth-paired, which well addresses the needs of the annotated datasets in specific tasks.

**Recommended Citation:** @article{wang2024flame,
  title={FLAME Diffuser: Grounded Wildfire Image Synthesis using Mask Guided Diffusion},
  author={Wang, Hao and Boroujeni, Sayed Pedram Haeri and Chen, Xiwen and Bastola, Ashish and Li, Huayu and Razi, Abolfazl},
  journal={arXiv preprint arXiv:2403.03463},
  year={2024}
}

**Download Paper Here:** [[PDF](http://pedramhaeri.github.io/files/Paper6.pdf)] [[ArXiv](https://arxiv.org/abs/2403.034638)]




[6] [An Efficient High-Dimensional Gene Selection Approach Based on the Binary Horse Herd Optimization Algorithm for Biologicaldata Classification](https://link.springer.com/article/10.1007/s42044-024-00174-z), Published in Journal of Computer Science, Springer, IF:1.9 (Q1), February 2024.

**Abstract:** The Horse Herd Optimization Algorithm (HOA) is a new meta-heuristic algorithm inspired by the behaviors of horses of different ages. It was recently introduced to solve complex and high-dimensional problems. This paper proposes a binary version of the HOA, termed the Binary Horse Herd Optimization Algorithm (BHOA), designed to solve discrete problems and select prominent feature subsets. Additionally, this study introduces a novel hybrid feature selection framework that combines the BHOA with a Minimum Redundancy Maximum Relevance (MRMR) filter method. This hybrid approach, more computationally efficient, yields a beneficial subset of relevant and informative features. Recognizing feature selection as a binary problem, we have applied a new Transfer Function (TF), named the X-shape TF, which converts continuous problems into binary search spaces. Moreover, the Support Vector Machine (SVM) is employed to evaluate the efficiency of the proposed method on ten microarray datasets: Lymphoma, Prostate, Brain-1, DLBCL, SRBCT, Leukemia, Ovarian, Colon, Lung, and MLL. Compared to other state-of-the-art methods, such as the Gray Wolf (GW), Particle Swarm Optimization (PSO), and Genetic Algorithm (GA), our proposed hybrid method (MRMR-BHOA) demonstrates superior performance in terms of accuracy and minimal selected features. Experimental results also show that the X-shaped BHOA approach outperforms other methods.

**Recommended Citation:** @article{mehrabi2024efficient,
  title={An efficient high-dimensional gene selection approach based on the Binary Horse Herd Optimization Algorithm for biologicaldata classification},
  author={Mehrabi, Niloufar and Haeri Boroujeni, Sayed Pedram and Pashaei, Elnaz},
  journal={Iran Journal of Computer Science},
  pages={1--31},
  year={2024},
  publisher={Springer}
}

**Download Paper Here:** [[PDF](http://pedramhaeri.github.io/files/Paper7.pdf)] [[Springer](https://link.springer.com/article/10.1007/s42044-024-00174-z)]




[7] [Opinion Dynamics in Social Multiplex Networks with Mono and Bi-directional Interactions in the Presence of Leaders](https://arxiv.org/abs/2401.15857), Submitted to Journal of Complex Network, Oxford Academic, IF:2.1 (Q1), January 2024.

**Abstract:** We delve into the dynamics of opinions within a multiplex network using coordination games, where agents communicate either in a one-way or two-way interactions, and where a designated leader may be present. By employing graph theory and Markov chains, we illustrate that despite non-positive diagonal elements in transition probability matrices or decomposable layers, opinions generally converge under specific conditions, leading to a consensus. We further scrutinize the convergence rates of opinion dynamics in networks with one-way versus two-way interactions. We find that in networks with a designated leader, opinions converge towards the initial opinion of the leader, whereas in networks without a designated leader, opinions converge to a convex combination of the opinions of agents. Moreover, we emphasize the crucial role of designated leaders in steering opinion convergence within the network. Our experimental findings corroborate that the presence of leaders expedites convergence, with mono-directional interactions exhibiting notably faster convergence rates compared to bidirectional interactions.

**Recommended Citation:** @misc{talebi2024opinion,
      title={Opinion Dynamics in Social Multiplex Networks with Mono and Bi-directional Interactions in the Presence of Leaders}, 
      author={Amirreza Talebi and Sayed Pedram Haeri Boroujeni and Abolfazl Razi},
      year={2024},
      eprint={2401.15857},
      archivePrefix={arXiv},
      primaryClass={eess.SY}
}

**Download Paper Here:** [[PDF](http://pedramhaeri.github.io/files/Paper8.pdf)] [[Oxford Academic](https://arxiv.org/abs/2401.15857)]



[8] [Cooperative Perception for Connected Autonomous Vehicles Under Constrained V2V Networking](https://ieeexplore.ieee.org/abstract/document/10476810), Published in IEEE Asilomar Conference on Signals, Systems, and Computers.

**Abstract:** Cooperative Perception (CP) is a newly emerged technique that can be used to enhance the safety of Autonomous Vehicles (AVs) when relying merely on the AV's own camera may not yield accurate results. Examples of such conditions are delayed or low object detection accuracy under foggy weather, winding roads, and blocked camera vision by the front vehicle. A few CP methods have been recently proposed to enhance the quality of AV perception through cooperative perception. Despite their success, these methods have a few limitations, such as adopting unrealistic assumptions about perfect communication and unconstrained resources as well as having access to large training datasets. In this paper, we use the LTE Release 14 Mode 4 side-link communication to implement CP by selective V2V communication for situational awareness. Our method is based on a demand-response mechanism and solving an optimization problem to employ helper vehicles, considering networking performance metrics (such as packet drop rate), available resources (radio blocks in LTE-V), extended visual range (the total road segment covered), and more importantly the ultimate perception quality of the selected vehicles. Our preliminary results demonstrate a significant gain for the proposed method compared to a conventional single-camera vision.

**Recommended Citation:** @inproceedings{sarlak2023cooperative,
  title={Cooperative Perception for Connected Autonomous Vehicles Under Constrained V2V Networking},
  author={Sarlak, Ahmad and Boroujeni, Sayed Pedram Haeri and Alzorgan, Hazim and Amin, Rahul and Razi, Abolfazl and Rajoli, Hossein},
  booktitle={2023 57th Asilomar Conference on Signals, Systems, and Computers},
  pages={210--214},
  year={2023},
  organization={IEEE}
}

**Download Paper Here:** [[PDF](http://pedramhaeri.github.io/files/Paper9.pdf)] [[IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/10476810)]




[9] [A Hybrid Chimp Optimization Algorithm and Generalized Normal Distribution Algorithm with Opposition-Based Learning Strategy for Solving Data Clustering Problems](https://link.springer.com/article/10.1007/s42044-023-00160-x), Published in Journal of Computer Science, Springer, IF:1.9 (Q1), October 2023.

**Abstract:** This paper focuses on connectivity-based data clustering for categorizing similar and dissimilar data into distinct groups. Although classical clustering algorithms such as K-means are efficient techniques, they often trap in local optima and have a slow convergence rate in solving high-dimensional problems. To address these issues, many successful meta-heuristic optimization algorithms and intelligence-based methods have been introduced to attain the optimal solution in a reasonable time. In this study, we attempt to conceptualize a powerful approach using the three main components: Chimp Optimization Algorithm (ChOA), Generalized Normal Distribution Algorithm (GNDA), and Opposition-Based Learning (OBL) method. First, two versions of ChOA with two different dynamic coefficients and seven chaotic maps, entitled ChOA(I) and ChOA(II), are presented to achieve the best possible result for data clustering purposes. Second, a novel combination of ChOA and GNDA algorithms with the OBL strategy is devised to solve the major shortcomings of the original algorithms. Lastly, the proposed ChOAGNDA method is a Selective Opposition (SO) algorithm based on ChOA and GNDA, which can be used to tackle large and complex real-world optimization problems, particularly data clustering applications. In this study, eight benchmark datasets, including five datasets of the UCI machine learning repository and three challenging shape datasets, are used to investigate the general performance of the proposed method. The results are evaluated against several popular and recent state-of-the-art clustering techniques. Experimental results illustrate that the proposed work significantly outperforms other existing methods in terms of the Sum of Intra-Cluster Distances (SICD), Error Rate (ER), and convergence rate.

**Recommended Citation:** @article{haeri2024hybrid,
  title={A hybrid chimp optimization algorithm and generalized normal distribution algorithm with opposition-based learning strategy for solving data clustering problems},
  author={Haeri Boroujeni, Sayed Pedram and Pashaei, Elnaz},
  journal={Iran Journal of Computer Science},
  volume={7},
  number={1},
  pages={65--101},
  year={2024},
  publisher={Springer}
}

**Download Paper Here:** [[PDF](http://pedramhaeri.github.io/files/Paper10.pdf)] [[Springer](https://link.springer.com/article/10.1007/s42044-023-00160-x)]




[10] [A Novel Hybrid Gene Selection Based on Random Forest Approach and Binary Dragonfly Algorithm](https://ieeexplore.ieee.org/abstract/document/9633105), Published in IEEE Conference on Electrical Engineering, Computing Science and Automatic Control (CCE).

**Abstract:** Microarrays dataset contains a huge number of genes and a few samples. This issue can lead to the curse of dimensionality in large datasets. To overcome this challenge, gene selection is a method used for identifying the independent genes and removing redundant or noisy ones from the dataset. This study proposes a novel hybrid approach based on the combination of Random Forest Ranking (RFR) and Binary Dragonfly Algorithm (BDA) to identify the significant genes. The proposed method comprises two steps. In the first step, RFR is employed to remove irrelevant genes and select the subsets of optimal genes. In the second step, BDA is applied to select the most informative genes that can lead to the accurate detection of cancer. The BDA optimizer is a recently proposed metaheuristic algorithm that utilizes Naïve Bayes (NB) classifier as an evaluator. In this paper, four microarray datasets are used to evaluate the performance of the proposed hybrid approach. Experimental results illustrate that the proposed work significantly outperforms existing meta-heuristic methods regarding classification accuracy and the optimal number of selected genes.

**Recommended Citation:** @inproceedings{boroujeni2021novel,
  title={A novel hybrid gene selection based on random forest approach and binary dragonfly algorithm},
  author={Boroujeni, Sayed Pedram Haeri and Pashaei, Elnaz},
  booktitle={2021 18th International Conference on Electrical Engineering, Computing Science and Automatic Control (CCE)},
  pages={1--8},
  year={2021},
  organization={IEEE}
}

**Download Paper Here:** [[PDF](http://pedramhaeri.github.io/files/Paper11.pdf)] [[IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/9633105)]



[11] [Data Clustering using Chimp Optimization Algorithm](https://ieeexplore.ieee.org/abstract/document/9721483), Published in IEEE Conference on Computer Engineering and Knowledge (ICCKE)

**Abstract:** In recent decades, many successful meta-heuristic algorithms are widely applied to data clustering problems due to their powerful capabilities. The Chimp Optimization Algorithm (ChOA) is a recently proposed meta-heuristic search algorithm that is inspired by chimps' individual intelligence and sexual motivation in their group hunting. The good performance of ChOA in a variety of optimization problems, prove the superiority of this algorithm over other swarm-based intelligence. This study presents a novel approach according to ChOA for data clustering. ChOA, like other Swarm Intelligence-based Algorithms (SIAs), starts with a random population and then calculates an objective value for them. In data clustering problems the population of candidate solutions is the position vectors of the centroids, and the objective function is the sum of intra-cluster distances (SICDs) between each sample and its nearest centroid. Following that, ChOA attempts to optimize the population by finding the best position vectors of optimal centroids. There are four different kinds of chimps in this regard: driver, chaser, barrier, and attacker. Furthermore, four major hunting moves including driving, blocking, chasing, and attacking are considered to find the promising solution. In this research, four datasets of the UCI machine learning repository are used to evaluate the performance of the proposed new approach. Experimental results illustrate that the proposed work significantly outperforms other clustering algorithms regarding the objective value, Error Rate (ER), and some other statistical tests.

**Recommended Citation:** @inproceedings{boroujeni2021data,
  title={Data clustering using chimp optimization algorithm},
  author={Boroujeni, Sayed Pedram Haeri and Pashaei, Elnaz},
  booktitle={2021 11th international conference on computer engineering and knowledge (ICCKE)},
  pages={296--301},
  year={2021},
  organization={IEEE}
}

**Download Paper Here:** [[PDF](http://pedramhaeri.github.io/files/Paper12.pdf)] [[IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/9721483)]



[12] [Age Estimation Based on Facial Images using Hybrid Features and Particle Swarm Optimization](https://ieeexplore.ieee.org/abstract/document/9721496), Published in 11th ICCKE IEEE Conference, Iran, February 2022.

**Abstract:** Face images provide significant biological information. Face age estimation is one of the primary research directions in face images. The appearance of the face changes dynamically, and these changes are influenced by a variety of factors such as light, aging, makeup, beard, etc. The human face has many characteristics, including emotions, sex, race, age, etc. Face age estimation has numerous applications in biometrics, security, commercial, military, interaction with computers, and providing services to the individual. In this paper, the age estimation system is divided into four distinct stages. The first step is to extract local features including Gabor wavelets (GW), Local Binary Pattern (LBP), Local Phase Quantization (LPQ), and Histogram of Oriented Gradients (HOG). These attributes are then combined in the second step as a feature fusion method, which combines four different feature extraction methods. In the following step, Particle Swarm Optimization (PSO) as a meta-heuristic optimization algorithm is used to decrease the size of attributes and find optimal features. Finally, we used classification and regression methods to estimate the age and age groups. Initially, we used support vector machines (SVMs) to determine the age class, and then used support vector regression (SVRs) to estimate the ages within those groups. Finally, our algorithm was examined on two widely used databases, i.e. the FG-NET and the MORPH, to determine its effectiveness regarding aging estimates. In the FGNET dataset, we achieved an MAE of 3.34 years and 75.69 percent classification accuracy, and in the MORPH dataset, we obtained an MAE of 3.21 years and 81.66 percent classification accuracy.

**Recommended Citation:** Mehrabi, Niloufar, and Sayed Pedram Haeri Boroujeni. "Age estimation based on facial images using hybrid features and particle swarm optimization." 2021 11th International Conference on Computer Engineering and Knowledge (ICCKE). IEEE, 2021. 

**Download Paper Here:** [[PDF](http://pedramhaeri.github.io/files/Paper2.pdf)] [[IEEE Xplore](https://www.sciencedirect.com/science/article/pii/S1566253524001477)]
