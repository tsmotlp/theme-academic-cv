---
title: "M3NAS: Multi-Scale and Multi-Level Memory-Efficient Neural Architecture Search for Low-Dose CT Denoising"
authors:
- Zexin Lu
- Wenjun Xia
- Admin
- Mingzheng Hou
- Hu Chen
- Jiliu Zhou
- Hongming Shan
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
date: "2022-11-03T00:00:00Z"
doi: "10.1109/TMI.2022.3219286"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-11-03T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Medical Imaging, vol. 42, no. 3, pp. 850-863, 2022"
publication_short: ""

abstract: Lowering the radiation dose in computed tomography (CT) can greatly reduce the potential risk to public health. However, the reconstructed images from dose-reduced CT or low-dose CT (LDCT) suffer from severe noise which compromises the subsequent diagnosis and analysis. Recently, convolutional neural networks have achieved promising results in removing noise from LDCT images. The network architectures that are used are either handcrafted or built on top of conventional networks such as ResNet and U-Net. Recent advances in neural network architecture search (NAS) have shown that the network architecture has a dramatic effect on the model performance. This indicates that current network architectures for LDCT may be suboptimal. Therefore, in this paper, we make the first attempt to apply NAS to LDCT and propose a multi-scale and multi-level memory-efficient NAS for LDCT denoising, termed M3NAS. On the one hand, the proposed M3NAS fuses features extracted by different scale cells to capture multi-scale image structural details. On the other hand, the proposed M3NAS can search a hybrid cell- and network-level structure for better performance. In addition, M3NAS can effectively reduce the number of model parameters and increase the speed of inference. Extensive experimental results on two different datasets demonstrate that the proposed M3NAS can achieve better performance and fewer parameters than several state-of-the-art methods. In addition, we also validate the effectiveness of the multi-scale and multi-level architecture for LDCT denoising, and present further analysis for different configurations of super-net.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Medical Image Processing
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/abstract/document/9936653
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
