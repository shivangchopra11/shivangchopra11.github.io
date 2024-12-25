---

title: "CRAFT: Curriculum Rank Adversarial Fine-Tuning for Robust Vision Language Models"
authors: 
- admin
- Chengyue Huang
- Brisa Maneechotesuwan
- Zsolt Kira.

date: "2024"
doi:

# Schedule page publish date (NOT publication's date).
publishDate: "2024-12-20"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "*Under review at the IEEE/CVF Conference on computer vision and pattern recognition (CVPR), 2025*"
publication_short: "*Under review at the IEEE/CVF Conference on computer vision and pattern recognition (CVPR), 2025*"


abstract: Existing Vision-Language Models (VLMs) have demonstrated remarkable zero-shot performance across various visual domains and tasks. However, recent studies have shown that fine-tuning VLMs on downstream tasks results in loss of generalization and decreased robustness against distribution shifts. To address this issue, we propose Curriculum Rank Adversarial Fine-Tuning (CRAFT), a unified low-rank fine-tuning framework designed to enhance both out-of-distribution (OOD) and adversarial robustness by integrating adaptive adversarial weight perturbations into a curriculum-driven Low-Rank Adaptation (LoRA) framework. CRAFT is grounded in three key insights (1) constrained parameter updates preserve OOD generalization, (2) promoting a flat weight-loss landscape enhances OOD robustness, and (3) adversarial training with adaptive perturbation budgets mitigate catastrophic forgetting. By progressively increasing the rank of weight updates and perturbations over the course of training, CRAFT balances task-specific adaptation with robustness, yielding flatter minima and enhanced OOD robustness. Through comprehensive empirical experiments, we demonstrate that CRAFT preserves VLMs' zero-shot abilities while adapting to specific tasks, outperforming state-of-the-art adversarial and robust fine-tuning approaches in both natural and adversarial distribution shifts. When fine-tuned on DomainNet and ImageNet datasets, CRAFT shows state-of-the-art ID performance while improving average OOD performance by 12% and 10% respectively over the vanilla fine-tuning baseline.

# Summary. An optional shortened abstract.

summary: 

tags:


featured: false

links:
# - name: DOI
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


