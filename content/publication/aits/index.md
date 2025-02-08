---

title: "Symbiotic Artificial Intelligence: Order Picking And Ambient Sensing"
authors: 
- Zhe Ming Chng
- Calix Tang
- Darshan Krishnaswamy
- Haoyang Yang
- admin
- Jon Womack
- Thad Starner

date: "2023"
doi: "https://doi.org/10.1109/ICASSPW59220.2023.10193633"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-06-10"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["Conference"]

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the 2023 IEEE International Conference on Acoustics, Speech, and Signal Processing Workshops (ICASSPW)*"
publication_short: "*Proceedings of the 2023 IEEE International Conference on Acoustics, Speech, and Signal Processing Workshops (ICASSPW)*"


abstract: Using egocentric video and head motion data from 67 order picking tasks (244 picks;149 orders), we learn visual models of the 10 objects picked to fulfill the orders. Boundary segmentations of the four actions (pick, carry, place, carry empty) of order picking had an average test RMSE of 1.11 seconds using computer vision and 5.53 seconds using only head motion (≈39.8 seconds/task). The 10 objects were clustered with 93.8% accuracy using weak supervision provided by the picks (which could occur in any order) specified in the tasks. We apply the 10 resulting models on independent test data to recognize three objects involving 50 tasks (185 picks;98 orders) and 10 objects involving 10 tasks (35 picks;24 orders). Accuracy was up to 90.3% and 69.1%, respectively. We propose order picking as a practical use case of egocentric Symbiotic AI, where ambient sensing is used without explicit supervision to train an agent which can then help the user improve task speed and accuracy. 

# Summary. An optional shortened abstract.

summary: Using egocentric video and head motion data from 67 order picking tasks (244 picks;149 orders), we learn visual models of the 10 objects picked to fulfill the orders.

tags:

featured: true

links:
- name: ICASSPW 2023
  url: 
url_pdf: https://ieeexplore.ieee.org/abstract/document/10193633

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


