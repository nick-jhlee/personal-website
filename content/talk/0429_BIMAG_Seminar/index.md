---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Introduction to Bayesian ML/DL, with Application to Parameter Inference of Coupled Non-linear ODEs - Part 1"
event: BIMAG Journal Club
event_url:
location: IBS BIMAG
address:
  street:
  city:
  region:
  postcode:
  country:
summary: In this talk, we cover the basics of Gaussian proces and its application to parameter inference of coupled non-linear ODEs.
abstract: Gaussian process(GP) is a stochastic process such that the joint distribution of arbitrary finite subset of the random variables is a multivariate normal. It plays a fundamental role in Bayesian machine learning as it can be interpreted as a prior over functions (Rasmussen and Williams, 2006), hence providing a nonparametric approach to various tasks. In the first part, I will introduce the general framework of GP and some underlying theory, accompanied by a typical example: GP regression, also known as Kringing.
In the second part, I will introduce some recent works on applying GP to parameter inference of coupled non-linear ODEs arising in various biological contexts.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2021-04-29T12:30:00+09:00
date_end: 2021-04-29T14:00:00+09:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2020-10-27T01:47:47+09:00

authors: []
tags: ["Machine Learning", "Bayesian Inference", "Gaussian Process", "ODE"]

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


References for GP:
- **Gaussian Processes for Machine Learning (C. E. Rasmussen and Chris Williams, the MIT press, 2006)**
- 


References for GP-based ODE Parameter Inference:
- **Yang, S., Wong, S. W. K., Kou, S.C. (2021), "Inference of dynamic systems from noisy and sparse data via manifold-constrained Gaussian processes," *Proceedings of the National Academy of Sciences of the United States of America (PNAS),* 118(15).**
 - Wenk, P., Gotovos, Al., Bauer, S., Gorbach, N. S., Krause, A., Buhmann, J. M. (2019), "Fast Gaussian process based gradient matching for parameter
identification in systems of nonlinear ODEs," *Proceedings of the 22nd International Conference on Artificial Intelligence and Statistics (AISTATS),* 89, 1351-1360.
- Gorbach, N. S., Bauer, S., Buhmann, J. M. (2017), "Scalable Variational Inference for Dynamical Systems," *Advances in Neural Information Processing Systems (NIPS),* 30.
- Macdonald, B., Higham, C., Husmeier, D. (2015), "Controversy in mechanistic modelling with Gaussian processes," *Proceedings of the 32nd International Conference on Machine Learning (ICML)*.
- Wang, Y., Barber, D. (2014), "Gaussian Processes for Bayesian Estimation in Ordinary Differential Equations," *Proceedings of the 31st International Conference on Machine Learning (ICML)*.
- Dondelinger, F., Filippone, M., Rogers, S., Husmeler, D. (2013), "ODE parameter inference using adaptive gradient matching with Gaussian processes," *Proceedings of the 16th International Conference on Artificial Intelligence and Statistics (AISTATS)*.
- Calderhead, B., Girolami, M., Lawrence, N. (2008), "Accelerating Bayesian Inference over Nonlinear Differential Equations with Gaussian Processes," *Advances in Neural Information Processing Systems (NIPS),* 21.

