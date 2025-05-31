---

title: "Active Data Discovery: Mining Unknown Data using Submodular Information Measures"
authors: 
- Suraj Kothawad
- admin
- Saikat Ghosh
- Rishabh Iyer


date: "2022"
doi: 

# Schedule page publish date (NOT publication's date).
publishDate: "2022-06-17"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["conference"]

# Publication name and optional abbreviated publication name.
publication: "*RealML Workshop in International Conference on Machine Learning (ICML), 2023*"
publication_short: "*RealML Workshop in International Conference on Machine Learning (ICML), 2023*"


abstract: Active Learning is a very common yet powerful framework for iteratively and adaptively sampling subsets of the unlabeled sets with a human in the loop with the goal of achieving labeling efficiency. Most real world datasets have imbalance either in classes and slices, and correspondingly, parts of the dataset are rare. As a result, there has been a lot of work in designing active learning approaches for mining these rare data instances. Most approaches assume access to a seed set of instances which contain these rare data instances. However, in the event of more extreme rareness, it is reasonable to assume that these rare data instances (either classes or slices) may not even be present in the seed labeled set, and a critical need for the active learning paradigm is to efficiently discover these rare data instances. In this work, we provide an active data discovery framework which can mine unknown data slices and classes efficiently using the submodular conditional gain and submodular conditional mutual information functions. We provide a general algorithmic framework which works in a number of scenarios including image classification and object detection and works with both rare classes and rare slices present in the unlabeled set. We show significant accuracy and labeling efficiency gains with our approach compared to existing state-of-the-art active learning approaches for actively discovering these rare classes and slices.

# Summary. An optional shortened abstract.

summary: 

tags:

featured: false

links:
- name: ICMLW 2023
  url: 
url_pdf: https://arxiv.org/pdf/2206.08566
url_poster: 'https://drive.google.com/file/d/1aYv9u2AYyO5BY6BRyRD2w4-vENYHyLvv/view?usp=sharing'

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


