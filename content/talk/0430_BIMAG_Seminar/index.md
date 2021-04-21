---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "An Introduction to Variational Inference"
event: BIMAG Journal Club
event_url:
location: IBS BIMAG
address:
  street:
  city:
  region:
  postcode:
  country:
summary: This is the first in 2-part tutorial on variational inference, and Bayesian non-parametric approach to (probability) density estimation.
abstract: The problem of approximating the posterior distribution (or density estimation in general) is a crucial problem in Bayesian statistics that has various applications in domains such as biology. MCMC sampling is the most widely used family of algorithms for approximating posteriors. However, if the underlying graphical model is too complex or the data is in very high dimensions or the amount of data is too large, then such sampling-based methodologies run into several problems. Variational inference (Jordan et al., 1999; Wainwright and Jordan, 2008) is a machine learning methodology that transforms the problem of approximating posterior densities to an optimization, which lets us circumvent all such problems. In this tutorial, I will introduce the basic theory behind variational inference and some basic applications of it in parameter inference and LDA, a generic statistical model for document topic modeling.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2021-04-30T12:30:00+09:00
date_end: 2021-04-30T14:00:00+09:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2020-10-27T01:47:47+09:00

authors: []
tags: ["Machine Learning", "Bayesian", "Variational Inference", "Graphical Model"]

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
projects: ["delay-distribution"]
---

References:

- Jordan, M. I., Ghahramani, Z., Jaakkola, T. S., Saul, L. K. (1999), "An Introduction to Variational Methods for Graphical Models," *Machine Learning*, 37, 183-233.
- Wainwright, M. J., Jordan, M. I. (2008), "Graphical Models, Exponential Families, and Variational Inference," *Foundations and Trends in Machine Learning*, 1(1-2) ,1-305.
- Blei, D. M., Ng, A. Y., Jordan, M. I. (2003), "Latent Diriclet Allocation," *Journal of Machine Learning Research*, 3, 993-1022.
- Hoffman, M. D., Blei, D. M., Wang, C., Paisley, J. (2013), "Stochastic Variational Inference," *Journal of Machine Learning Research*, 14, 1303-1347.
- **Blei, D. M., Kucukelbir, A., McAuliffe, J. D. (2017), "Variational Inference: A Review for Statisticians," *Journal of the American Statistical Association*, 518, 859-877.**
- Hoffman, M. D., Johnson, M. J. (2016), "ELBO surgery: yet another way to carve up the variational evidence lower bound," In *NeurIPS Workshop on Approximate Bayesian Inference*