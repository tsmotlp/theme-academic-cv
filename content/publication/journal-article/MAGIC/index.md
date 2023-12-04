---
title: "MAGIC: Manifold and graph integrative convolutional network for low-dose CT reconstruction"
authors:
- Wenjun Xia
- Zexin Lu
- Admin
- Zuoqiang Shi
- Yan Liu
- Hu Chen
- Jiliu Zhou
- Yi Zhang
author_notes:
- 
- 
- 
- 
- 
- 
-
- "Corresponding Author"
date: "2021-06-10T00:00:00Z"
doi: "10.1109/TMI.2021.3088344"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-06-10T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Medical Imaging, vol. 40, no. 12, pp. 3459-3472, 2021"
publication_short: ""

abstract: Low-dose computed tomography (LDCT) scans, which can effectively alleviate the radiation problem, will degrade the imaging quality. In this paper, we propose a novel LDCT reconstruction network that unrolls the iterative scheme and performs in both image and manifold spaces. Because patch manifolds of medical images have low-dimensional structures, we can build graphs from the manifolds. Then, we simultaneously leverage the spatial convolution to extract the local pixel-level features from the images and incorporate the graph convolution to analyze the nonlocal topological features in manifold space. The experiments show that our proposed method outperforms both the quantitative and qualitative aspects of state-of-the-art methods. In addition, aided by a projection loss component, our proposed method also demonstrates superior performance for semi-supervised learning. The network can remove most noise while maintaining the details of only 10% (40 slices) of the training data labeled.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Medical Image Processing
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/abstract/document/9450848
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
