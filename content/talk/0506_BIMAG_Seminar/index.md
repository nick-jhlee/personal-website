---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Introduction to Bayesian ML/DL, with Application to Parameter Inference of Coupled Non-linear ODEs - Part 2"
event: BIMAG Journal Club
event_url:
location: IBS BIMAG
address:
  street:
  city:
  region:
  postcode:
  country:
summary: In this talk, we cover the basics of variational inference and its application to parameter inference of coupled non-linear ODEs.
abstract: The problem of approximating the posterior distribution (or density estimation in general) is a crucial problem in Bayesian statistics, in which intractable integrals often become the computational bottleneck. MCMC sampling is the most widely used family of algorithms for approximating posteriors. However, if the underlying graphical model is too complex or the data is in very high dimensions, then such sampling-based methodologies run into several problems. Variational inference (Jordan et al., 1999; Wainwright and Jordan, 2008) is a family of machine learning methodologies that transforms the problem of approximating posterior densities to an optimization, which lets us circumvent all such problems. In the first part, I will introduce the general framework of variational inference and some underlying theory, accompanied by an illustrative example of LDA (Blei et al., 2003). In the second part, I will introduce some recent works on applying variational inference to parameter inference of coupled non-linear ODEs arising in various biological contexts.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2021-05-06T12:30:00+09:00
date_end: 2021-05-06T14:00:00+09:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2020-10-27T01:47:47+09:00

authors: []
tags: ["Machine Learning", "Bayesian Inference", "Variational Inference", "ODE"]

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
projects: ["plant-circadian"]
---



References for Variational Inference:

- **Blei, D. M., Kucukelbir, A., McAuliffe, J. D. (2017), "Variational Inference: A Review for Statisticians," *Journal of the American Statistical Association*, 518, 859-877.**
- Hoffman, M. D., Blei, D. M., Wang, C., Paisley, J. (2013), "Stochastic Variational Inference," *Journal of Machine Learning Research*, 14, 1303-1347.
- Blei, D. M., Ng, A. Y., Jordan, M. I. (2003), "Latent Diriclet Allocation," *Journal of Machine Learning Research*, 3, 993-1022.
- Wainwright, M. J., Jordan, M. I. (2008), "Graphical Models, Exponential Families, and Variational Inference," *Foundations and Trends in Machine Learning*, 1(1-2), 1-305.
- Jordan, M. I., Ghahramani, Z., Jaakkola, T. S., Saul, L. K. (1999), "An Introduction to Variational Methods for Graphical Models," *Machine Learning*, 37, 183-233.



References for V.I.-based ODE Parameter Inference:

- **Ghosh, S., Birrell, P. J., Angelis, D. D. (2021), "Variational inference for nonlinear ordinary differential equations," *Proceedings of the 24th International Conference on Artificial Intelligence and Statistics (AISTATS)*.**
- Gorbach, N. S., Bauer, S., Buhmann, J. M. (2017), "Scalable Variational Inference for Dynamical Systems," *Advances in Neural Information Processing Systems (NIPS),* 30.