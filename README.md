# Internship at Deep Learning Lab. , Seoul National University on Joint-Embedding Predictive Architecture 

# DESCRIPTION

Research codebase focusing on Self-Supervised Learning, Vision Transformers, and World Models (JEPA). Developed during my research internship at Seoul National University (SNU) under the supervision of Prof. Kim Tae-Wan.

# PAPERS

### LeCun, 2022 — A Path Towards Autonomous Machine Intelligence
**Authors:** Yann LeCun
**Year:** 2022
**Venue:** OpenReview (position paper)
**Link:** https://openreview.net/forum?id=BZ5a1r-kVsf

LeCun's vision paper introducing the JEPA (Joint Embedding Predictive Architecture) framework. Argues for world-model–based learning over generative and contrastive approaches. Covers hierarchical planning, intrinsic motivation, and the H-JEPA architecture.

### LeCun et al., 2006 — A Tutorial on Energy-Based Learning
**Authors:** Yann LeCun, Sumit Chopra, Raia Hadsell, Marc'Aurelio Ranzato, Fu Jie Huang
**Year:** 2006
**Venue:** Predicting Structured Data, MIT Press
**Link:** http://yann.lecun.com/exdb/publis/pdf/lecun-06.pdf

Foundational reference on Energy-Based Models (EBMs). Defines energy functions, loss functionals, and explains why contrastive methods are needed to shape the energy landscape. Essential background for understanding non-contrastive methods like JEPA.

### Chen et al., 2020 — A Simple Framework for Contrastive Learning (SimCLR)
**Authors:** Ting Chen, Simon Kornblith, Mohammad Norouzi, Geoffrey Hinton
**Year:** 2020
**Venue:** ICML
**Link:** https://arxiv.org/abs/2002.05709

Contrastive SSL with the **NT-Xent** loss (InfoNCE with cosine similarity + temperature). Key findings: composition of augmentations defines the task, a projection head helps, and large batches (more negatives) matter. Negatives come from the current batch only.

