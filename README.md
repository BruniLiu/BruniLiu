# Hi! I'm Bruni

Research-oriented undergraduate exploring the frontiers of **multimodal learning** and **next-token prediction**. I build unified token interfaces across modalities.

## Overview

I study whether perception can be treated as prediction: represent images and text in a shared token space and let a single model evolve that space forward. Concretely, I design PDE-driven alternatives to self-attention and evaluate them on captioning, retrieval, and cross-modal indexing.

## Research Focus

- **Emu3 as a Unified Interface**  
  Studying next-token prediction as a general API for vision–language tasks, with extensions to image↔text retrieval and cross-modal indexing.

- **CLIP + GPT-2 Captioning (PKU Summer School 2025)**  
  A lightweight captioning pipeline aligning CLIP embeddings to GPT-2 for sequence generation.  
  Project: <https://github.com/Bruni-coder/multimodal-captioning-via-clip-gpt2>

## Interests

Multimodal retrieval and representation learning; attention-free architectures; federated learning and privacy; graph-based modeling with PyTorch Geometric.

## Selected Technical Directions

- **Attention alternatives:** PDE-style continuous evolution, token-field dynamics, and stability/complexity trade-offs.  
- **Unified tokenization:** constructing `[image_tokens] + text_tokens` training formats for next-token objectives.  
- **Evaluation beyond BLEU:** retrieval-style metrics, latency/throughput under long contexts, and robustness to token sparsity.  
- **Graph priors:** when and how graph structure benefits multimodal token propagation.

## Projects

- **PDEformer (research code, WIP)**  
  Prototype of PDE-driven token evolution with image–text inputs; focuses on stability, step size control, and inference latency.
- **CLIP-GPT2 Captioning**  
  Minimal, readable baseline for image captioning; useful as a sanity check and ablation bed.  
  Repo: <https://github.com/Bruni-coder/multimodal-captioning-via-clip-gpt2>

## Collaboration

I welcome academic discussion and lightweight collaborations around attention alternatives, unified token interfaces, and evaluation protocols for multimodal NTP systems.

## Contact

- Email: **lnubruni@gmail.com**  
- GitHub Issues: open an issue on any relevant repository
