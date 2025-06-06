---
title: "Look Beneath the Surface: Exploiting Fundamental Symmetry for Sample-Efficient Offline RL"

date: 2023-09-22

publishDate: 2023-10-09T08:07:44.014393Z

authors: ["Peng Cheng", "Xianyuan Zhan", "Zhihao Wu", "Wenjia Zhang", "Shoucheng Song", "Han Wang", "Youfang Lin", "Li Jiang"]

publication_types: ["paper-conference"]

abstract: "Offline reinforcement learning (RL) offers an appealing approach to real-world tasks by learning policies from pre-collected datasets without interacting with the environment. However, the performance of existing offline RL algorithms heavily depends on the scale and state-action space coverage of datasets. Real-world data collection is often expensive and uncontrollable, leading to small and narrowly covered datasets and posing significant challenges for practical deployments of offline RL. In this paper, we provide a new insight that leveraging the fundamental symmetry of system dynamics can substantially enhance offline RL performance under small datasets. Specifically, we propose a Time-reversal symmetry (T-symmetry) enforced Dynamics Model (TDM), which establishes consistency between a pair of forward and reverse latent dynamics. TDM provides both well-behaved representations for small datasets and a new reliability measure for OOD samples based on compliance with the T-symmetry. These can be readily used to construct a new offline RL algorithm (TSRL) with less conservative policy constraints and a reliable latent space data augmentation procedure. Based on extensive experiments, we find TSRL achieves great performance on small benchmark datasets with as few as 1% of the original samples, which significantly outperforms the recent offline RL algorithms in terms of data efficiency and generalizability."

featured: false

publication: "*Advances in Neural Information Processing Systems (NeurIPS 2023)*"

url_pdf: "https://proceedings.neurips.cc/paper_files/paper/2023/file/181a027913d36bc0a8857c0da661d621-Paper-Conference.pdf"

projects: 
  - Algorithms 
  - AIoT

tags:
  - Algorithms 
  - AIoT
---

