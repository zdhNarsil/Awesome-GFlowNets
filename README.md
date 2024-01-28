# Awesome GFlowNets   [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of resources about generative flow networks (GFlowNets).

## Table of Contents
- [Monograph \& Tutorial](#monograph)
- [Paper](#paper)
- [Workshop paper \& Note](#workshop)

<a name="monograph" />

## Monograph \& Tutorial
[GFlowNet Foundations](https://arxiv.org/abs/2111.09266) [theoretical framework]  
Yoshua Bengio, et al.

[GFlowNets for AI-Driven Scientific Discovery](https://arxiv.org/abs/2302.00615) [review paper]  
Moksh Jain, et al.

[The GFlowNet Tutorial](https://milayb.notion.site/The-GFlowNet-Tutorial-95434ef0e2d94c24aab90e69b30be9b3) [high level introduction]  
Yoshua Bengio. 

[GFlowNet Tutorial](https://colab.research.google.com/drive/1fUMwgu2OhYpQagpzU5mhe9_Esib3Q2VR) [PRACTICAL colab notebook]  
Emmanuel Bengio.

<a name="paper" />

## Paper

<!-- ### Modeling \& training -->

[A Theory of Non-Acyclic Generative Flow Networks](https://arxiv.org/abs/2312.15246)  
Leo Maxime Brunswic, et al. AAAI 2024.

[Generative Flow Networks as Entropy-Regularized RL](https://arxiv.org/abs/2310.12934)  
Daniil Tiapkin, et al. AISTATS 2024 oral. [[code](https://github.com/d-tiapkin/gflownet-rl)]  

[Order-Preserving GFlowNets](https://arxiv.org/abs/2310.00386)  
Yihang Chen, et al. ICLR 2024. [[code](https://github.com/yhangchen/OP-GFN)] 

[PhyloGFN: Phylogenetic inference with generative flow networks](https://arxiv.org/abs/2310.08774)  
Mingyang Zhou, et al. ICLR 2024.

[Pre-Training and Fine-Tuning Generative Flow Networks](https://arxiv.org/abs/2310.03419)  
Ling Pan, et al. ICLR 2024 spotlight.

[Diffusion Generative Flow Samplers: Improving learning signals through partial trajectory optimization](https://arxiv.org/abs/2310.02679) [practical continuous space sampler]   
Dinghuai Zhang, et al. ICLR 2024. [[code](https://github.com/zdhNarsil/Diffusion-Generative-Flow-Samplers)] 

[Amortizing intractable inference in large language models](https://arxiv.org/abs/2310.04363) [finetune LLMs as GFlowNets]  
Edward J. Hu, et al. ICLR 2024.  [[code](https://github.com/GFNOrg/gfn-lm-tuning)] 

[Learning Energy Decompositions for Partial Inference of GFlowNets](https://arxiv.org/abs/2310.03301)   
Hyosoon Jang, et al. ICLR 2024 oral.  

[Local Search GFlowNets](https://arxiv.org/abs/2310.02710)   
Minsu Kim, et al. ICLR 2024 spotlight. [[code](https://github.com/dbsxodud-11/ls_gfn)] 

[Delta-AI: Local objectives for amortized inference in sparse graphical models](https://arxiv.org/abs/2310.02423)  
Jean-Pierre Falet, et al. ICLR 2024. [[code](https://github.com/GFNOrg/Delta-AI/)] 

[Expected flow networks in stochastic environments and two-player zero-sum games](https://arxiv.org/abs/2310.02779)  
Marco Jiralerspong, et al. ICLR 2024. [[code](https://bit.ly/demoafn)] 

[Compositional Sculpting of Iterative Generative Processes
](http://arxiv.org/abs/2309.16115)   
Timur Garipov, et al.  NeurIPS 2023.  [[code]([https://bit.ly/demoafn](https://github.com/timgaripov/compositional-sculpting))] 

[Multi-Fidelity Active Learning with GFlowNets](https://arxiv.org/abs/2306.11715)  
Alex Hernandez-Garcia, et al. [[code](https://github.com/nikita-0209/mf-al-gfn)] 

[Joint Bayesian Inference of Graphical Structure and Parameters with a Single Generative Flow Network](https://arxiv.org/abs/2305.19366)  
Tristan Deleu, et al. NeurIPS 2023. [[code](https://github.com/tristandeleu/jax-jsp-gfn)]  

[Let the Flows Tell: Solving Graph Combinatorial Optimization Problems with GFlowNets](http://arxiv.org/abs/2305.17010)   
Dinghuai Zhang, et al. NeurIPS 2023 spotlight. [[code](https://github.com/zdhNarsil/GFlowNet-CombOpt)]

[Sample-efficient Multi-objective Molecular Optimization with GFlowNets](https://arxiv.org/abs/2302.04040)  
Yiheng Zhu, et al. NeurIPS 2023.

[DynGFN: Bayesian Dynamic Causal Discovery using Generative Flow Networks](https://arxiv.org/abs/2302.04178) [GFlowNet for Bayesian dynamical causal discovery]  
Lazar Atanackovic, et al. NeurIPS 2023. [[code](https://github.com/lazaratan/dyn-gfn)]  

[Stochastic Generative Flow Networks](https://arxiv.org/abs/2302.09465) [model-based GFlowNets for stochastic transitions]  
Ling Pan, et al. UAI 2023 spotlight. [[code](https://github.com/ling-pan/Stochastic-GFN)]  

[GFlowNet-EM for Learning Compositional Latent Variable Models](https://arxiv.org/abs/2302.06576) [GFlowNet for latent posterior]  
Edward J. Hu, et al. ICML 2023.   [[code](https://github.com/GFNOrg/GFlowNet-EM)]  

[Distributional GFlowNets with Quantile Flows](https://arxiv.org/abs/2302.05793) [distributional GFlowNets for stochastic rewards]  
Dinghuai Zhang, et al. TMLR.  [[code](https://github.com/zdhNarsil/Distributional-GFlowNets)]   

[Towards Understanding and Improving GFlowNet Training](https://arxiv.org/abs/2305.07170)  
Max W. Shen, et al. ICML 2023.  [[code]](https://github.com/maxwshen/gflownet)  

[Better Training of GFlowNets with
Local Credit and Incomplete Trajectories](http://arxiv.org/abs/2302.01687) [forward-looking GFlowNet]  
Ling Pan, et al. ICML 2023. [[code](https://github.com/ling-pan/FL-GFN)]  

[Unifying Generative Models with GFlowNets and Beyond](https://arxiv.org/abs/2209.02606)  
Dinghuai Zhang, et al. ICML 2022 Beyond Bayes workshop.

[A theory of continuous generative flow networks](https://arxiv.org/abs/2301.12594) [GFlowNet on continuous space]  
Salem Lahlou, et al. ICML 2023. [[code]](https://github.com/saleml/continuous-gfn)

[Multi-Objective GFlowNets](https://arxiv.org/abs/2210.12765)  
Moksh Jain, et al. ICML 2023.  [[code]](https://github.com/GFNOrg/multi-objective-gfn)    

[Learning GFlowNets from partial episodes for improved convergence and stability](https://arxiv.org/abs/2209.12782) [SubTB criterion]  
Kanika Madan, et al. ICML 2023 oral. [[code]](https://github.com/GFNOrg/gflownet/tree/subtb) 

[GFlowOut: Dropout with Generative Flow Networks](https://arxiv.org/abs/2210.12928)  
Dianbo Liu, et al. ICML 2023.  

[Generative Augmented Flow Networks](https://arxiv.org/abs/2210.03308) [enabling intermediate rewards]  
Ling Pan, et al. ICLR 2023 spotlight. [[code]](https://github.com/ling-pan/GAFN)  

[Robust Scheduling with GFlowNets](https://arxiv.org/abs/2302.05446)  
David Wei Zhang, et al. ICLR 2023. 

[GFlowNets and variational inference](https://arxiv.org/abs/2210.00580)  
Nikolay Malkin, et al. ICLR 2023. [[code]](https://github.com/GFNOrg/GFN_vs_HVI)  

[Trajectory Balance: Improved Credit Assignment in GFlowNets](https://arxiv.org/abs/2201.13259)  [trajectory balance (TB) criterion]  
Nikolay Malkin, et al. NeurIPS 2022. [[code]](https://github.com/GFNOrg/gflownet/tree/trajectory_balance)

[Bayesian Structure Learning with Generative Flow Networks](https://arxiv.org/abs/2202.13903) [causal graph Bayesian posterior]  
Tristan Deleu, et al. UAI 2022. [[code]](https://github.com/tristandeleu/jax-dag-gflownet)

[Generative Flow Networks for Discrete Probabilistic Modeling](https://arxiv.org/abs/2202.01361) [energy-based GFlowNet]    
Dinghuai Zhang, et al. ICML 2022. [[code]](https://github.com/zdhnarsil/EB_GFN)

[Biological Sequence Design with GFlowNets](https://arxiv.org/abs/2203.04115)  
Moksh Jain, et al. ICML 2022. [[code]](https://github.com/MJ10/BioSeq-GFN-AL)

[Flow Network based Generative Models for Non-Iterative Diverse Candidate Generation](https://arxiv.org/abs/2106.04399)  [first GFlowNet paper]    
Emmanuel Bengio, et al. NeurIPS 2021. [[blog post]](http://folinoid.com/w/gflownet) [[code]](https://github.com/GFNOrg/gflownet)

<a name="workshop" />

## Workshop paper \& Note

[DGFN: Double Generative Flow Networks](https://arxiv.org/abs/2310.19685)   
Elaine Lau, et al. NeurIPS 2023 Workshop on Generative AI and Biology (GenBio 2023).

[GFN-SR: Symbolic Regression with Generative Flow Networks](https://openreview.net/forum?id=r3fzEWnaY4)  
Sida Li, et al.  NeurIPS 2023 AI for Science Workshop.  

[Crystal-GFN: sampling crystals with desirable properties and constraints](https://arxiv.org/abs/2310.04925)  
Alex Hernandez-Garcia, et al. [[code](https://github.com/alexhernandezgarcia/gflownet)]

[Causal Inference in Gene Regulatory Networks with GFlowNet: Towards Scalability in Large Systems](https://arxiv.org/abs/2310.03579)  
Trang Nguyen, et al. 

[Probabilistic Generative Modeling for Procedural Roundabout Generation for Developing Countries](https://arxiv.org/abs/2310.03687)  
Zarif Ikram, et al. 
<!-- NeurIPS 2023 Workshop on Adaptive Experimental Design and Active Learning in the Real World.  -->

[An Empirical Study of the Effectiveness of Using a Replay Buffer on Mode Discovery in GFlowNets](https://arxiv.org/abs/2307.07674)  
Nikhil Vemgal, et al. ICML 2023 SPIGM workshop.

[Generative Flow Networks: a Markov Chain Perspective](https://arxiv.org/abs/2307.01422) [merge the initial and the terminal states]  
Tristan Deleu, et al.

[Thompson sampling for improved exploration in GFlowNets](https://arxiv.org/abs/2306.17693)  
Jarrid Rector-Brooks, et al. ICML 2023 SPIGM workshop.

[BatchGFN: Generative Flow Networks for Batch Active Learning](https://arxiv.org/abs/2306.15058)  
Shreshth A. Malik, et al. ICML 2023 SPIGM workshop. [[code](https://github.com/s-a-malik/batchgfn)]

[Goal-conditioned GFlowNets for Controllable Multi-Objective Molecular Design](https://arxiv.org/abs/2306.04620)   
Julien Roy, et al.

[Bayesian learning of Causal Structure and Mechanisms
with GFlowNets and Variational Bayes](https://arxiv.org/abs/2211.02763)  [DAG-GFlowNet with parameters]  
Mizu Nishikawa-Toomey, et al.  

[Evaluating Generalization in GFlowNets for Molecule Design](https://openreview.net/forum?id=JFSaHKNZ35b)  
Andrei Cristian Nica, et al. ICML 2022 MLDD workshop.

## Contact
If you have any suggestion or want to add your own work, please feel free to drop a message to [dinghuai.zhang@mila.quebec](mailto:dinghuai.zhang@mila.quebec).
