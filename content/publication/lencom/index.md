---

title: "Refining Text-to-Image Generation: Towards Accurate Training-Free Glyph-Enhanced Image Generation"
authors: 
- Sanyam Lakhanpal
- admin
- Vinija Jain
- Aman Chadha
- Man Luo


date: "2024"
doi: 

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-25"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["conference"]

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV), 2025*"
publication_short: "*Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV), 2025*"


abstract: Over the past few years, Text-to-Image (T2I) generation approaches based on diffusion models have gained significant attention. However, vanilla diffusion models often suffer from spelling inaccuracies in the text displayed within the generated images. The capability to generate visual text is crucial, offering both academic interest and a wide range of practical applications. To produce accurate visual text images, state-of-the-art techniques adopt a glyph-controlled image generation approach, consisting of a text layout generator followed by an image generator that is conditioned on the generated text layout. Nevertheless, our study reveals that these models still face three primary challenges, prompting us to develop a testbed to facilitate future research. We introduce a benchmark, LenCom-Eval, specifically designed for testing models' capability in generating images with Lengthy and Complex visual text. Subsequently, we introduce a training-free framework to enhance the two-stage generation approaches. We examine the effectiveness of our approach on both LenCom-Eval and MARIO-Eval benchmarks and demonstrate notable improvements across a range of evaluation metrics, including CLIPScore, OCR precision, recall, F1 score, accuracy, and edit distance scores. For instance, our proposed framework improves the backbone model, TextDiffuser, by more than 23\% and 13.5\% in terms of OCR word F1 on LenCom-Eval and MARIO-Eval, respectively. Our work makes a unique contribution to the field by focusing on generating images with long and rare text sequences, a niche previously unexplored by existing literature.

# Summary. An optional shortened abstract.

summary: In this work, we introduce a training-free framework to enhance the capability of Diffusion Models to generate visual text.

tags:

featured: false

links:
- name: WACV 2025
  url: 
url_pdf: https://arxiv.org/pdf/2403.16422

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


