## Learning Abstract World Models with a Group-Structured Latent Space

We are pleased to announce the publication of the research paper titled "Learning Abstract World Models with a Group-Structured Latent Space" on arXiv.
This work was co-authored by Thomas Delliaux\*, Nguyen-Khanh Vu\* (ETH Zürich), Vincent François-Lavet (VU Amsterdam), Elise van der Pol (Microsoft Research AI for Science, Amsterdam), Emmanuel Rahchelson. (*Equal contribution) 

TL;DR: We train an abstract world model in which part of the abstract space has an explicit group structure, to reflect the rotational symmetry present in the environment. The model's generalization capacity is then evaluated using both qualitative and quantitative metrics.

### Abstract

Learning meaningful abstract models of Markov Decision Processes (MDPs) is
crucial for improving generalization from limited data. In this work, we show how geometric priors can be imposed on the low-dimensional representation manifold of a learned transition model. We incorporate known symmetric structures via appropriate choices of the latent space and the associated group actions, which encode prior knowledge about invariances in the environment. In addition, our framework allows the embedding of additional unstructured information alongside these symmetries. We show experimentally that this leads to better predictions of the latent transition model than fully unstructured approaches, as well as better learning on downstream RL tasks, in environments with rotational and translational features, including in first-person views of 3D environments. Additionally, our experiments show that this leads to simpler and more disentangled representations.

### Key Findings
- A contrastive objective is used to jointly learn the transition model and the latent space. Additionally, a disentanglement objective enables the model to combine both regular features and features with a group structure.
- The latent space learned by the model equipped with the group-structured prior is visually more interpretable than that of its counterpart without the prior, in both low-dimensional and high-dimensional environments.
- The abstract world model with the group-structured latent space exhibits better generalization performance than the one without the prior when evaluated using the 'Hit at k' and 'Mean Reciprocal Rank' metrics.
- Combining DDQN with a learned abstract world model that includes a geometric prior outperforms both the baseline DDQN and the model without the geometric prior when trained with limited data.
  
### Publication Details

* **Title**: Learning Abstract World Models with a Group-Structured Latent Space
* **Link to Publication**: Read the full paper [here](https://arxiv.org/abs/2506.01529)
