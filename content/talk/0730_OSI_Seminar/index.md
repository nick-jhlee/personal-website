---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Poisson Learning: Graph Based Semi-Supervised Learning At Very Low Label Rates"
event: OSI Lab Seminar
event_url:
location: Zoom
address:
  street:
  city:
  region:
  postcode:
  country:
summary: This talk introduces the paper "Poisson Learning - Graph Based Semi-Supervised Learning At Very Low Label Rates" (Calder et al., ICML'20).
abstract: We propose a new framework, called Poisson learning, for graph based semi-supervised learning at very low label rates. Poisson learning is motivated by the need to address the degeneracy of Laplacian semi-supervised learning in this regime. The method replaces the assignment of label values at training points with the placement of sources and sinks, and solves the resulting Poisson equation on the graph. The outcomes are provably more stable and informative than those of Laplacian learning. Poisson learning is efficient and simple to implement, and we present numerical experiments showing the method is superior to other recent approaches to semi-supervised learning at low label rates on MNIST, FashionMNIST, and Cifar-10. We also propose a graph-cut enhancement of Poisson learning, called Poisson MBO, that gives higher accuracy and can incorporate prior knowledge of relative class sizes.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2021-07-30T14:30:00+09:00
date_end: 2021-07-30T16:30:00+09:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2020-10-27T01:47:47+09:00

authors: []
tags: ["Graphs", "Semi-Supervised Learning", "PDE Theory"]

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
url_slides:

url_code:
url_pdf:
url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

Papers discussed in the talk:

- **Main:** Calder, J., Cook, B., Thorpe, M., Slepčev, D. Poisson Learning: Graph Based Semi-Supervised Learning At Very Low Label Rates. In *ICML*, 2020.