---
title: "CT reconstruction with PDF: Parameter-dependent framework for data from multiple geometries and dose levels"
authors:
- Wenjun Xia
- Zexin Lu
- Admin
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
- "Corresponding Author"
date: "2021-06-04T00:00:00Z"
doi: "10.1109/TMI.2021.3085839"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-06-04T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Medical Imaging, vol. 40, no. 11, pp. 3065-3076, 2021"
publication_short: ""

abstract: The current mainstream computed tomography (CT) reconstruction methods based on deep learning usually need to fix the scanning geometry and dose level, which significantly aggravates the training costs and requires more training data for real clinical applications. In this paper, we propose a parameter-dependent framework (PDF) that trains a reconstruction network with data originating from multiple alternative geometries and dose levels simultaneously. In the proposed PDF, the geometry and dose level are parameterized and fed into two multilayer perceptrons (MLPs). The outputs of the MLPs are used to modulate the feature maps of the CT reconstruction network, which condition the network outputs on different geometries and dose levels. The experiments show that our proposed method can obtain competitive performance compared to the original network trained with either specific or mixed geometry and dose level, which can efficiently save extra training costs for multiple geometries and dose levels.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Medical Image Processing
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/abstract/document/9446923
url_code: 'https://github.com/xiawj-hub/PDF'
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
