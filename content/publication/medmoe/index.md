---

title: "MedMoE: Modality-Specialized Mixture of Experts for Medical Vision-Language Understanding"
authors: 
- admin
- Gabriela Sanchez-Rodriguez
- Lingchao Mao
- Andrew J. Feola
- Jing Li
- Zsolt Kira


date: "2025"
doi: 

# Schedule page publish date (NOT publication's date).
publishDate: "2025-06-11"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["conference"]

# Publication name and optional abbreviated publication name.
publication: "*Workshop on Multimodal Foundation Models for Biomedicine in CVPR 2025*"
publication_short: "*Workshop on Multimodal Foundation Models for Biomedicine in CVPR 2025*"


abstract: Different medical imaging modalities capture diagnostic information at varying spatial resolutions, from coarse global patterns to fine-grained localized structures. However, most existing vision-language frameworks in the medical domain apply a uniform strategy for local feature extraction, overlooking the modality-specific demands. In this work, we present MedMoE, a modular and extensible vision-language processing framework that dynamically adapts visual representation based on the diagnostic context. MedMoE incorporates a Mixture-of-Experts (MoE) module conditioned on the report type, which routes multi-scale image features through specialized expert branches trained to capture modality-specific visual semantics. These experts operate over feature pyramids derived from a Swin Transformer backbone, enabling spatially adaptive attention to clinically relevant regions. This framework produces localized visual representations aligned with textual descriptions, without requiring modality-specific supervision at inference. Empirical results on diverse medical benchmarks demonstrate that MedMoE improves alignment and retrieval performance across imaging modalities, underscoring the value of modality-specialized visual representations in clinical vision-language systems.

# Summary. An optional shortened abstract.

summary: In this work, we introduce a modality aware MoE Vision-Language Model for medical diagnosis tasks.

tags:

featured: true

links:
- name: CVPRW 2025
  url: 
url_pdf: https://arxiv.org/pdf/2506.08356
url_poster: 'https://drive.google.com/file/d/1U04XHf45GpvgMzumYp5jbrohpNKHDWto/view?usp=sharing'

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


