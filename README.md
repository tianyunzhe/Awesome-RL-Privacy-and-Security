# Awesome-RL-Privacy-and-Security
 A curated list of papers and resources in RL privacy &amp; security.
## Contents
- [Survey](#awesome-suvey-papers)
- [RL Security](#Awesome-RL-Security-Papers)
   - [Backdoor Attack](#backdoor-attack) 
   - [Backdoor Defense](#backdoor-defense) 
- [RL Privacy](#Awesome-RL-Privacy-Papers)
   - [Environment Privacy Attack](#environment-privacy-attack)
   - [Model Privacy Attack](#model-privacy-attack)
   - [Reward Privacy Attack](#reward-privacy-attack)
   - [Privacy-preserving RL](#privacy-preserving-rl)



## Awesome-Suvey-Papers
* [2022-Artificial Intelligence Review] **New Challenges in Reinforcement Learning: A Survey of Security and Privacy** [[Paper](https://link.springer.com/article/10.1007/s10462-022-10348-5)]

* [2024-ACM Computing Surveys] **Security and Privacy Issues in Deep Reinforcement Learning: Threats and Countermeasures** [[Paper](https://dl.acm.org/doi/full/10.1145/3640312)]

## Awesome-RL-Security-Papers

### Backdoor Attack

#### Single-agent RL

* [2019-arXiv] **Design of Intentional Backdoors in Sequential Models** [[Paper](https://arxiv.org/pdf/1902.09972)]

* [2020-DAC] **TrojDRL: Evaluation of Backdoor Attacks on Deep Reinforcement Learning** [[Paper](https://ieeexplore.ieee.org/abstract/document/9218663)]

* [2021-ICLR workshop] **Poisoning Deep Reinforcement Learning Agents with In-Distribution Triggers** [[Paper](https://arxiv.org/pdf/2106.07798.pdf)][[Code](https://github.com/trojai/trojai_rl)]

* [2021-TIFS] **Stop-and-Go: Exploring Backdoor Attacks on Deep Reinforcement Learning-based Traffic Congestion Control Systems** [[Paper](https://ieeexplore.ieee.org/abstract/document/9541185)]

* [2022-arXiv] **Execute Order 66: Targeted Data Poisoning for Reinforcement Learning** [[Paper](https://arxiv.org/abs/2201.00762)]

* [2022-GLOBALCOM] **A Temporal-Pattern Backdoor Attack to Deep Reinforcement Learning** [[Paper](https://arxiv.org/pdf/2205.02589)][[Code](https://github.com/EboYu/DRLBackdoor)]

* [2023-Peer-to-Peer Netw. Appl.] **Backdoor Attacks Against Deep Reinforcement Learning based Traffic Signal Control Systems** [[Paper](https://link.springer.com/article/10.1007/s12083-022-01434-0#citeas)]

* [2024-S&P] **BAFFLE: BAFFLE: Hiding Backdoors in Offline Reinforcement Learning Datasets** [[Paper](https://csdl-downloads.ieeecomputer.org/proceedings/sp/2024/3130/00/313000a218.pdf?Expires=1716773052&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9jc2RsLWRvd25sb2Fkcy5pZWVlY29tcHV0ZXIub3JnL3Byb2NlZWRpbmdzL3NwLzIwMjQvMzEzMC8wMC8zMTMwMDBhMjE4LnBkZiIsIkNvbmRpdGlvbiI6eyJEYXRlTGVzc1RoYW4iOnsiQVdTOkVwb2NoVGltZSI6MTcxNjc3MzA1Mn19fV19&Signature=WtKv8jcDNSqJqbHpdDtstLiEXhirPQgjbd2BfZYbUvGQgs7qfvq8SiTSduiLgYIPkdTvg7J08r65Oxnz5Eh71vXRupc9oPkiAevkeXT1Lzg40TA0lMmwgQlLEU--87YPT5eoBtoim4rCwfjR5F17FQ-NeXtT-dEN8nNJ~jwjEnbsY0nkp3uYzce0gStjKYxHEhzCaKyvGiyHBx85vKRiT3qLNOPBWCkjsWRi8OUoDwOG~HIsudgGoUP-XBF0tFhMyJj8634bMvQYS5fwatm1KmqZ4EqsPtqWO5i4vVlbXU-zpV7PTa3NLZPLZ2lXMn3gDbn5dFrPxugL6-0FwdXKQw__&Key-Pair-Id=K12PMWTCQBDMDT)][[Code](https://github.com/2019ChenGong/Offline_RL_Poisoner/)]

* [2024-AAAI] **BadRL: Sparse Targeted Backdoor Attack Against Reinforcement Learning** [[Paper](https://arxiv.org/pdf/2312.12585.pdf)][[Code](https://github.com/7777777cc/code)]

#### Multi-agent RL

* [2021-IJCAI] **BACKDOORL: Backdoor Attack against Competitive Reinforcement Learning** [[Paper](https://arxiv.org/pdf/2105.00579.pdf)][[Code](https://github.com/wanglun1996/multi_agent_rl_backdoor_videos)]

* [2022-arXiv] **Backdoor Attacks on Multiagent Collaborative Systems** [[Paper](https://arxiv.org/pdf/2211.11455.pdf)]

* [2023-TDSC] **MARNet: Backdoor Attacks Against Cooperative Multi-Agent Reinforcement Learning** [[Paper](https://ieeexplore.ieee.org/abstract/document/9894692)]

* [2023-COSE] **One4All: Manipulate One Agent to Poison the Cooperative Multi-Agent Reinforcement Learning** [[Paper](https://www.sciencedirect.com/science/article/pii/S0167404822003972)]

* [2023-GLOBECOM] **Backdoor Attacks on Multi-Agent Reinforcement Learning-based Spectrum Management**[[Paper](https://ieeexplore.ieee.org/abstract/document/10437779)]
### Backdoor Defense

#### Single-agent RL

* [2022-NeurIPS] **Provable Defense against Backdoor Policies in Reinforcement Learning** [[Paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/5e67e6a814526079ad8505bf6d926fb6-Paper-Conference.pdf)][[Code](https://github.com/skbharti/Provable-Defense-in-RL)]

* [2023-arXiv] **Recover Triggered States: Protect Model Against Backdoor Attack in Reinforcement Learning** [[Paper](https://arxiv.org/pdf/2304.00252.pdf)]

* [2023-NeurIPS] **BIRD: Generalizable Backdoor Detection and Removal for Deep Reinforcement Learning** [[Paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/802e90325f4c8546e13e5763b2ecab88-Paper-Conference.pdf)]

* [2024] **SHINE: Shielding Backdoors in Deep Reinforcement Learning** [[Paper](https://openreview.net/forum?id=AKAlVyunxA)]

#### Multi-agent RL
* [2023-ICCV] **PolicyCleanse: Backdoor Detection and Mitigation for Competitive Reinforcement Learning** [[Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Guo_PolicyCleanse_Backdoor_Detection_and_Mitigation_for_Competitive_Reinforcement_Learning_ICCV_2023_paper.pdf)]

* [2023-ACM J. Auton. Transport. Syst.] **Backdozer: A Backdoor Detection Methodology for DRL-based Traffic Controllers** [[Paper](https://dl.acm.org/doi/pdf/10.1145/3639828)]



## Awesome-RL-Privacy-Papers

### Environment Privacy Attack

* [2019-AAMAS] **How You Act Tells a Lot: Privacy-Leaking Attack on Deep Reinforcement Learning** [[Paper](https://www.ifaamas.org/Proceedings/aamas2019/pdfs/p368.pdf)][[Code](https://github.com/xinleipan/gym-gridworld)]


* [2023-Access] **Membership Inference Attacks Against Temporally Correlated Data in Deep Reinforcement Learning** [[Paper](https://arxiv.org/pdf/2109.03975.pdf)]

* [2023-Connection Science] **Empirical study of privacy inference attack against deep reinforcement learning models** [[Paper](https://www.tandfonline.com/doi/pdf/10.1080/09540091.2023.2211240)]

* [2023-arXiv] **Your Room is not Private: Gradient Inversion Attack on Reinforcement Learning** [[Paper](https://arxiv.org/pdf/2306.09273)]
  
* [2023-arXiv] **Value-Based Membership Inference Attack on Actor-Critic Reinforcement Learning** [[Paper](https://openreview.net/pdf?id=wKIxJKTDmX-)]



### Model Privacy Attack
* [2019-arXiv] **Adversarial Exploitation of Policy Imitation** [[Paper](https://arxiv.org/pdf/1906.01121.pdf)]

* [2021-Asia CCS] **Stealing Deep Reinforcement Learning Models for Fun and Profit** [[Paper](https://arxiv.org/pdf/2006.05032.pdf)]

### Reward Privacy Attack


* [2022-AAAI] **How Private Is Your RL Policy? An Inverse RL Based Analysis Framework** [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/20772)][[Code](https://github.com/magnetar-iiith/PRIL)]

### Privacy-preserving RL

* [2020-arXiv] **Preventing Imitation Learning with Adversarial Policy Ensembles** [[Paper](https://arxiv.org/pdf/2002.01059.pdf)]

* [2021-AAMAS] **Deceptive Reinforcement Learning for Privacy-Preserving Planning** [[Paper](https://arxiv.org/pdf/2102.03022.pdf)]

* [2021-SRDS] **Protecting Reward Function of Reinforcement Learning via Minimal and Non-catastrophic Adversarial Trajectory** [[Paper](https://ieeexplore.ieee.org/abstract/document/9603589)]

* [2023-ICAPS] **Deceptive Reinforcement Learning in Model-Free Domains** [[Paper](https://arxiv.org/pdf/2303.10838)]


* [2023-arXiv] **Reinforcement Unlearning** [[Paper](https://arxiv.org/pdf/2312.15910)]

* [2024-AISTATS] **Privacy-Constrained Policies via Mutual Information Regularized Policy Gradients** [[Paper](https://proceedings.mlr.press/v238/j-cundy24a/j-cundy24a.pdf)]




