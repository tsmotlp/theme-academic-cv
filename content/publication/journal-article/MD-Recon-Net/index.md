---
title: "Md-recon-net: A parallel dual-domain convolutional neural network for compressed sensing mri"
authors:
- Maosong Ran
- Wenjun Xia
- Admin
- Zexin Lu
- Peng Bao
- Yan Liu
- Huaiqiang Sun
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
-
- "Corresponding Author"
date: "2020-05-06T00:00:00Z"
doi: "10.1109/TRPMS.2020.2991877"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-05-06T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Radiation and Plasma Medical Sciences, vol. 5, no. 1, pp. 120-135, 2020"
publication_short: ""

abstract: Compressed sensing magnetic resonance imaging (CS-MRI) is a theoretical framework that can accurately reconstruct images from undersampled k-space data with a much lower sampling rate than the one set by the classical Nyquist-Shannon sampling theorem. Therefore, CS-MRI can efficiently accelerate acquisition time and relieve the psychological burden on patients while maintaining high imaging quality. The problems with traditional CS-MRI reconstruction are solved by iterative numerical solvers, which usually suffer from expensive computational cost and the lack of accurate handcrafted priori. In this article, inspired by deep learning's (DL's) fast inference and excellent end-to-end performance, we propose a novel cascaded convolutional neural network called MRI dual-domain reconstruction network (MD-Recon-Net) to facilitate fast and accurate magnetic resonance imaging reconstruction. Especially, different from existing DL-based methods, which operate on single domain data or both domains in a certain order, our proposed MD-Recon-Net contains two parallel and interactive branches that simultaneously perform on k-space and spatial domain data, exploring the latent relationship between k-space and the spatial domain. The simulated experimental results show that the proposed method not only achieves competitive visual effects to several state-of-the-art methods but also outperforms other DL-based methods in terms of model scale and computational cost.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Medical Image Processing
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/abstract/document/9084142
url_code: 'https://github.com/Deep-Imaging-Group/MD-Recon-Net'
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
