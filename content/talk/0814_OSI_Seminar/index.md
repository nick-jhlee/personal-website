---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Heavy-tail behaviour of SGD? - Part 1"
event: OSI Lab Seminar
event_url:
location: Zoom
address:
  street:
  city:
  region:
  postcode:
  country:
summary: This talk introduces a rather new approach to analyzing SGD, from the perspective of heavy-tail behaviors. 
abstract: One of the popular ways of analyzing the behavior of SGD and SGDm(SGD with momentum) is by considering it as a discretization of Langevin-type SDE. Up till 2019, it was widely assumed that the SGN has a finite variance, leading to the analysis of Brownian-driven SDE. Over the last 2 years, this finite variance assumption has been challenged (primarily by Prof. Umut Şimşekli) by claims that the SGN is actually heavy-tailed; as a consequence, the SDE of interest is actually driven by a Lévy motion. This talk gives a detailed overview of this new way of thinking about SGD/SGDm by going through some of the key papers(ICML2019, ICML2020, arXiv)+related papers.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2020-08-14T14:30:00+09:00
date_end: 2020-08-14T16:30:00+09:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2020-10-27T01:47:47+09:00

authors: []
tags: ["Stochastic Optimization", "SGD", "SDE", "heavy-tail", "Lévy process"]

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
projects: ["practical-deep-learning"]
---

Papers discussed in the talk:
- **Main:** Şimşekli, U., Sagun, L., and Gürbüzbalaban, M. A Tail-Index Analysis of Stochastic Gradient Noise in Deep Neural Networks. In *ICML*, 2019.
- Şimşekli, U. Fractional Langevin Monte Carlo: Exploring Lévy Driven Stochastic Differential Equations for Markov Chain Monte Carlo. In *ICML*, 2017.
- Şimşekli, U., Zhu, L., Teh, Y. W., and Gürbüzbalaban, M. Fractional Underdamped Langevin Dynamics: Retargeting SGD with Momentum under Heavy-Tailed Gradient Noise. In *ICML*, 2020.
