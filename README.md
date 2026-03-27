# UW-VOS: A Large-Scale Dataset for Underwater Video Object Segmentation

[![arXiv](https://img.shields.io/badge/arXiv-2603.24006-b31b1b.svg)](https://arxiv.org/abs/2603.24006)

This is the official repository for the paper "UW-VOS: A Large-Scale Dataset for Underwater Video Object Segmentation". 

> 🚀 **Updates:**
> The complete dataset and evaluation scripts will be fully open-sourced and released in this repository soon. Stay tuned!

<!--## 📖 Abstract
Underwater Video Object Segmentation (VOS) is essential for marine exploration, yet open-air methods suffer significant degradation due to color distortion, low contrast, and prevalent camouflage. A primary hurdle is the lack of high-quality training data. To bridge this gap, we introduce **UW-VOS**, the first large-scale underwater VOS benchmark comprising 1,431 video sequences across 409 categories with 309,295 mask annotations, constructed via a semi-automatic data engine with rigorous human verification. We further propose **SAM-U**, a parameter-efficient framework that adapts SAM2 to the underwater domain. By inserting lightweight adapters into the image encoder, SAM-U achieves state-of-the-art performance with only ~2\% trainable parameters. Extensive experiments reveal that existing methods experience an average 13-point $\mathcal{J}$ \& $\mathcal{F}$ drop on UW-VOS, while SAM-U effectively bridges this domain gap. Detailed attribute-based analysis further identifies small targets, camouflage, and exit-re-entry as critical bottlenecks, providing a roadmap for future research in robust underwater perception.

<!--## 🖼️ Teaser -->
## 📝 TODO List
- [x] Release arXiv paper.
- [ ] Release the UW-VOS benchmark dataset.
- [ ] Release evaluation scripts and metrics.
- [ ] Release training and testing code.

<!--## 🗂️ Data Preparation

The **UW-VOS** benchmark dataset is now officially released! 
We host our complete dataset on Hugging Face for fast and stable downloading.
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-UW--VOS%20Dataset-blue)](https://huggingface.co/datasets/your-username/UW-VOS)
