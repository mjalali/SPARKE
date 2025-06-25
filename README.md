# SPARKE Diversity Guidance for Diffusion Models homepage

The Project page for paper: [SPARKE: Scalable Prompt-Aware Diversity Guidance in Diffusion Models via RKE Score
](https://arxiv.org/abs/2506.10173).

## Abstract
Diffusion models have demonstrated exceptional performance in high-fidelity image synthesis and prompt-based generation. However, achieving sufficient diversity—particularly within semantically similar prompts—remains a critical challenge. Prior methods use diversity metrics as guidance signals, but often neglect prompt awareness or computational scalability.

In this work, we propose **SPARKE**: _Scalable Prompt-Aware Diversity Guidance in Diffusion Models via RKE Score_. SPARKE leverages **conditional entropy** to guide the sampling process with respect to prompt-localized diversity. By employing **Conditional Latent RKE Score Guidance**, we reduce the computational complexity from $\mathcal{O}(n^3)$ to $\mathcal{O}(n)$, enabling efficient large-scale generation. We integrate SPARKE into several popular diffusion pipelines and demonstrate improved diversity without additional inference overhead.


See the project Github Code: [https://github.com/mjalali/sparke-diffusers](https://github.com/mjalali/sparke-diffusers).

## Bibtex Citation
To cite this work, please use the following BibTeX entries:

SPARKE Diversity Guidance:
```bibtex
@article{jalali2025sparke,
    author = {Mohammad Jalali and Haoyu Lei and Amin Gohari and Farzan Farnia},
    title = {SPARKE: Scalable Prompt-Aware Diversity Guidance in Diffusion Models via RKE Score},
    journal = {arXiv preprint arXiv:2506.10173},
    year = {2025},
    url = {https://arxiv.org/abs/2506.10173},
}
```

RKE Score:
```bibtex
@inproceedings{jalali2023rke,
    author = {Jalali, Mohammad and Li, Cheuk Ting and Farnia, Farzan},
    booktitle = {Advances in Neural Information Processing Systems},
    pages = {9931--9943},
    title = {An Information-Theoretic Evaluation of Generative Models in Learning Multi-modal Distributions},
    url = {https://openreview.net/forum?id=PdZhf6PiAb},
    volume = {36},
    year = {2023}
}
```

