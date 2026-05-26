<h1 align="center">Semantic Robustness Certification for Vision-Language Models</h1>
<h2 align="center"><strong>ICML 2026</strong></h2>

This code implements the semantic robustness certification framework from the following paper:

> Peiyu Yang, Paul Montague, Feng Liu, Andrew C. Cullen, Amardeep Kaur, Christopher Leckie, and Sarah M. Erfani
>
> [Semantic Robustness Certification for Vision-Language Models](https://example.com)

This repository provides tools for certifying whether a VLM prediction remains invariant under language-specified semantic transformations such as shape, style, size, material, illumination, viewpoint, or background changes. The core idea is to use text prompts as semantic proxies, construct a semantic transformation in the shared image-text embedding space, and analytically certify prediction-invariant intervals along the semantic extent.

The source code will be released after the completion of the required approval process.

## Citation

If you use this code, please cite:

```bibtex
@inproceedings{yang2026semanticcert,
  title     = {Semantic Robustness Certification for Vision-Language Models},
  author    = {Yang, Peiyu and Montague, Paul and Liu, Feng and Cullen, Andrew C. and Kaur, Amardeep and Leckie, Christopher and Erfani, Sarah M.},
  booktitle = {Proceedings of the 43rd International Conference on Machine Learning},
  year      = {2026}
}
```

## Acknowledgements

This codebase builds on Dassl.pytorch and CLIP-style prompt-learning infrastructure. We thank the authors of the underlying open-source projects for making their implementations available.
