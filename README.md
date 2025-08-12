# UNCAGE: Contrastive Attention Guidance for Masked Generative Transformers in Text-to-Image Generation

**Paper Link**: [arXiv](https://arxiv.org/abs/2508.05399)

## Abstract 
<img width="1691" height="571" alt="teaser" src="https://github.com/user-attachments/assets/cba188b3-f405-4eac-a045-4c1b5788b71c" />


       

Text-to-image (T2I) generation has been actively studied using Diffusion Models and Autoregressive Models. Recently, Masked Generative Transformers have gained attention as an alternative to Autoregressive Models to overcome the inherent limitations of causal attention and autoregressive decoding through bidirectional attention and parallel decoding, enabling efficient and high-quality image generation. However, compositional T2I generation remains challenging, as even state-of-the-art Diffusion Models often fail to accurately bind attributes and achieve proper text-image alignment. While Diffusion Models have been extensively studied for this issue, Masked Generative Transformers exhibit similar limitations but have not been explored in this context. To address this, we propose **Unmasking with Contrastive Attention Guidance (UNCAGE)**, a novel training-free method that improves compositional fidelity by leveraging attention maps to prioritize the unmasking of tokens that clearly represent individual objects. UNCAGE consistently improves performance in both quantitative and qualitative evaluations across multiple benchmarks and metrics, with negligible inference overhead.

## 🚧 Code Release Coming Soon

Thank you for your interest in our work!

We are actively working on preparing the codebase for public release. The code, along with documentation and example usage, will be made available here once it is ready.

Stay tuned!

*For questions or collaboration inquiries, please contact us or open an issue.*


## 📖 Citation

If you find this useful, please cite:

```bibtex
@article{kang2025uncage,
  title={UNCAGE: Contrastive Attention Guidance for Masked Generative Transformers in Text-to-Image Generation},
  author={Kang, Wonjun and Ahn, Byeongkeun and Lee, Minjae and Galim, Kevin and Oh, Seunghyuk and Koo, Hyung Il and Cho, Nam Ik},
  journal={arXiv preprint arXiv:2508.05399},
  year={2025}
}
```
