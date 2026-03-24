# ScaleEdit-12M: Scaling Open-Source Image Editing Data Generation via Multi-Agent Framework

<div align="center">

[![arXiv](https://img.shields.io/badge/ArXiv-2603.20644-b31b1b?logo=arxiv)](https://arxiv.org/abs/2603.20644)&nbsp;
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Dataset-ScaleEdit--12M-yellow)](https://huggingface.co/datasets/InternVL-U/ScaleEdit-12M)&nbsp;

</div>

## 📌 Abstract
Instruction-based image editing has emerged as a key capability for unified multimodal models (UMMs), yet constructing large-scale, diverse, and high-quality editing datasets without costly proprietary APIs remains challenging. Previous image editing datasets either rely on closed-source models for annotation, which prevents cost-effective scaling, or employ fixed synthetic editing pipelines, which suffer from limited quality and generalizability. To address these challenges, we propose ScaleEditor, a fully open-source hierarchical multi-agent framework for end-to-end construction of large-scale, high-quality image editing datasets. Our pipeline consists of three key components: source image expansion with world-knowledge infusion, adaptive multi-agent editing instruction-image synthesis, and a task-aware data quality verification mechanism. Using ScaleEditor, we curate ScaleEdit-12M, the largest open-source image editing dataset to date, spanning 23 task families across diverse real and synthetic domains. Fine-tuning UniWorld-V1 and Bagel on ScaleEdit yields consistent gains, improving performance by up to 10.4% on ImgEdit and 35.1% on GEdit for general editing benchmarks and by up to 150.0% on RISE and 26.5% on KRIS-Bench for knowledge-infused benchmarks. These results demonstrate that open-source, agentic pipelines can approach commercial-grade data quality while retaining cost-effectiveness and scalability. Both the framework and dataset will be open-sourced.

![Overview of ScaleEdit-12M](assets/teaser.png)

## 🔥 News
- **[2026/03/24]** 🔥ScaleEdit-12M is released on [[arXiv]](https://arxiv.org/abs/2603.20644). 
- **[2026/03/06]** 🔥InternVL-U **technical report** released.  Check it out on [[arXiv]](https://arxiv.org/abs/2603.09877). 

## ✅ TODO
- [ ] Release ScaleEdit-12M dataset
- [ ] Release ScaleEdit-1M subset
- [ ] Release ScaleEditor framework

## 🛠️ Highlights

- **ScaleEditor**: a fully open-source, multi-agent framework tailored for the cost-effective construction of large-scale, high-quality image editing datasets. It seamlessly integrates source image expansion, adaptive instruction-image synthesis, and rigorous multi-dimensional quality verification.
- **ScaleEdit-12M**: the largest high-quality, open-source image editing dataset to date. Comprising 12 million rigorously verified instruction-image pairs, it encompasses a wide spectrum of local and global editing tasks across diverse real and synthetic visual domains.   
- **Broad Generalization**: We demonstrate the broad generalization of ScaleEdit-12M by fine-tuning leading foundation models (*eg.*, UniWorld-V1 and Bagel). The resulting models consistently surpass those trained on other open-source datasets across diverse benchmarks, proving that our open-source pipeline can rival commercial APIs.

![Overview of ScaleEdit-12M](assets/pipeline.png)

## 🌟 Citation
```bibtex
@article{chen2026scaleedit,
  title={ScaleEdit-12M: Scaling Open-Source Image Editing Data Generation via Multi-Agent Framework},
  author={Chen, Guanzhou and Cui, Erfei and Tian, Changyao and Yang, Danni and Yang, Ganlin and Qiao, Yu and Li, Hongsheng and Luo, Gen and Zhang, Hongjie},
  journal={arXiv preprint arXiv:2603.20644},
  year={2026}
}
```