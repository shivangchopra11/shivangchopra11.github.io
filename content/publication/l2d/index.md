---

title: "Learning to Discern: Imitating Heterogeneous Human Demonstrations with Preference and Representation Learning"
authors: 
- Sachit Kuhar
- Shuo Cheng
- admin
- Matthew Bronars
- Danfei Xu

date: "2022"
doi: "https://doi.org/10.1007/978-3-030-45442-5_33"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-10-22"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the 7th Annual Conference on Robot Learning (CoRL)*"
publication_short: "*Proceedings of the 7th Annual Conference on Robot Learning (CoRL)*"


abstract: Practical Imitation Learning (IL) systems rely on large human demonstration datasets for successful policy learning. However, challenges lie in maintaining the quality of collected data and addressing the suboptimal nature of some demonstrations, which can compromise the overall dataset quality and hence the learning outcome. Furthermore, the intrinsic heterogeneity in human behavior can produce equally successful but disparate demonstrations, further exacerbating the challenge of discerning demonstration quality. To address these challenges, this paper introduces Learning to Discern (L2D), an offline imitation learning framework for learning from demonstrations with diverse quality and style. Given a small batch of demonstrations with sparse quality labels, we learn a latent representation for temporally embedded trajectory segments. Preference learning in this latent space trains a quality evaluator that generalizes to new demonstrators exhibiting different styles. Empirically, we show that L2D can effectively assess and learn from varying demonstrations, thereby leading to improved policy performance across a range of tasks in both simulations and on a physical robot.

# Summary. An optional shortened abstract.

summary: In this work, we introduce Learning to Discern (L2D), an offline imitation learning framework for learning from demonstrations with diverse quality and style.

tags:


featured: false

links:
- name: CoRL 2023
  url: 
url_pdf: https://proceedings.mlr.press/v229/kuhar23a/kuhar23a.pdf

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


