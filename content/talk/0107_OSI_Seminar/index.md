---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Topics not covered by anyone... (kind of)"
event: OSI Lab NeurIPS Seminar
event_url:
location: Zoom
address:
  street:
  city:
  region:
  postcode:
  country:
summary: This talk covers 4 NeurIPS 2020 papers (all of which are theory-heavy), that I thought were interesting, whose topics were not covered by anyone in OSI Lab.
abstract: First 2 papers are directly related to my current research topic of uncovering the inner working of deep learning in general. First paper by Daneshmand et al. gives a rigorous proof that characterizes the effect of batch normalization(BN) in deep linear networks; BN preserves the rank of hidden representation, whose lower bound is dependent on the width of the network and independent of the depth. Second paper by Maennel et al. theoretically and empirically confirms that the first layer of the neural network learns the first principal component of the input data, when trained with random labels. Third paper by Rubin-Delanchy gives a first theoretical characterization of the so-called manifold-hypothesis by proving that a manifold structure, whose Hausdorff dimension is given explicitly, is sure to arise in spectral embedding of latent position model. Fourth paper by Nadjahi et al. gives a full theoretical characterization of the recently-introduced sliced probability divergences. Topological characterizations include metric properties and convergence properties while statistical characterizations include sample complexity and projection complexity.


# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2021-01-07T15:30:00+09:00
date_end: 2021-01-07T16:30:00+09:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2020-10-27T01:47:47+09:00

authors: []
tags: ["Batch normalization", "SGD", "Deep learning", "Graphs", "GAN", "Sliced Probability Divergence"]

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

Last 2 papers aren't related to my current topics, but they are expected to be in short time ;)

Papers discussed in the talk:
- Daneshmand, H., Kohler, J., Bach, F., Hofmann, T., Lucchi, A. Batch normalization provably avoids rank collapse for randomly initialized deep networks. In *NeurIPS*, 2020.
- Maennel, H., Alabdulmohsin, I., Tolstikhin, I., Baldock, R. J. N., Bousquet, O., Gelly, S., Keysers, D. What do neural networks learn when trained with random labels? In *NeurIPS*, 2020. (*Spotlight paper!*)
- Rubin-Delanchy, P. Manifold structure in graph embeddings. In *NeurIPS*, 2020. (*Spotlight paper!*)
- Nadjahi, K., Durmus, A., Chizat, L., Kolouri, S., Shahrampour, S., Şimşekli, U. Statistical and Topological Properties of Sliced Probability Divergences? In *NeurIPS*, 2020. (*Spotlight paper!*)