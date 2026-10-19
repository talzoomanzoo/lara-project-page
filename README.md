# LaRA

**LaRA: Layer-wise Representation Analysis for Detecting Data Contamination in RL Post-Training**

Minju Gwak, Minseo Kwak, Dongseok Lee, Guijin Son, Alan Ritter, Jaehyung Kim

Yonsei University · Seoul National University · Georgia Institute of Technology

**Findings of EMNLP 2026**

[Paper](https://arxiv.org/abs/2605.29888) · [PDF](https://arxiv.org/pdf/2605.29888) · [Repository](https://github.com/talzoomanzoo/lara)

This repository contains the static project website for LaRA. Paper details follow [arXiv v2](https://arxiv.org/abs/2605.29888v2), revised August 31, 2026.

## Overview

LaRA studies data contamination in reinforcement-learning post-trained language models through their internal representations. It measures perturbation sensitivity, directional collapse, and local representation variability, then combines deviations across layers into a contamination score. See the paper for the experimental setup, results, and limitations.

## Website

- `index.html`: paper details, abstract, method overview, resource links, search metadata, and citation.
- `static/css/`: styles inherited from the academic project page template.
- Other files in `static/` are inherited template assets; sample media are not displayed on the LaRA page.

To preview locally, run from the repository root:

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000. No build step is required.

For GitHub Pages, configure the repository's Pages settings to deploy from the desired branch and the repository root. Add paper-specific figures, videos, or a social preview image when available, and reference them from `index.html`.

## Citation

```bibtex
@misc{gwak2026lara,
  title={LaRA: Layer-wise Representation Analysis for Detecting Data Contamination in RL Post-Training},
  author={Minju Gwak and Minseo Kwak and Dongseok Lee and Guijin Son and Alan Ritter and Jaehyung Kim},
  year={2026},
  eprint={2605.29888},
  archivePrefix={arXiv},
  primaryClass={cs.LG},
  doi={10.48550/arXiv.2605.29888},
  url={https://arxiv.org/abs/2605.29888}
}
```

## Attribution and license

The paper abstract is reproduced from [LaRA on arXiv](https://arxiv.org/abs/2605.29888v2) under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

The website is based on the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template), adapted from [Nerfies](https://nerfies.github.io/). The website template is licensed under [Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/). This website license is separate from the paper's license.
