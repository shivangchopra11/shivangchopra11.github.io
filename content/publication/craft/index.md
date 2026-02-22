---

title: "CRAFT: Curriculum Rank Adversarial Fine-Tuning for Robust Vision Language Models"
authors: 
- admin
- Shaunak Halbe
- Chengyue Huang
- Brisa Maneechotesuwan
- Zsolt Kira.

date: "2026"
doi:

# Schedule page publish date (NOT publication's date).
publishDate: "2026-02-20"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["conference"]

# Publication name and optional abbreviated publication name.
publication: "*Accepted at CVPR, 2026*"
publication_short: "*Accepted at CVPR, 2026*"


abstract: Fine-tuning approaches for Vision-Language Models (VLMs) face a critical three-way trade-off between In-Distribution (ID) accuracy, Out-of-Distribution (OOD) generalization, and adversarial robustness. Existing robust fine-tuning strategies resolve at most two axes of this trade-off. Generalization-preserving methods retain ID/OOD performance but leave models vulnerable to adversarial attacks, while adversarial training improves robustness to targeted attacks but degrades ID/OOD accuracy. Our key insight is that the robustness trade-off stems from two geometric failures: sharp, anisotropic minima in parameter space and unstable feature representations that deform under perturbation. To address this, we propose GRACE (Gram-aligned Robustness via Adaptive Curvature Estimation), a unified fine-tuning framework that jointly regularizes the parameter-space curvature and feature-space invariance for VLMs. Grounded in Robust PAC-Bayes theory, GRACE employs adaptive weight perturbations scaled by local curvature to promote flatter minima, combined with a feature alignment loss that maintains representation consistency across clean, adversarial, and OOD inputs. On ImageNet fine-tuning of CLIP models, GRACE simultaneously improves ID accuracy by 10.8%, and adversarial accuracy by 8.9% while maintaining 57.0% OOD accuracy (vs. 57.4% zero-shot baseline). Geometric analysis confirms that GRACE converges to flatter minima without feature distortion across distribution shifts, providing a principled step toward generalized robustness in foundation VLMs.

# Summary. An optional shortened abstract.

summary: In this work, we propose GRACE, a unified low-rank fine-tuning framework designed to enhance both out-of-distribution (OOD) and adversarial robustness by integrating adaptive adversarial weight perturbations into a curriculum-driven Low-Rank Adaptation (LoRA) framework.

tags:


featured: false

links:
- name: CVPR 2026
#   url: https://doi.org/10.48550/arXiv.2401.09082
# url_pdf: https://proceedings.mlr.press/v229/kuhar23a/kuhar23a.pdf

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---


