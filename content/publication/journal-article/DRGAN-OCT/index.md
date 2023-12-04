---
title: "Noise-Powered Disentangled Representation for Unsupervised Speckle Reduction of Optical Coherence Tomography Images"
authors:
- Admin
- Wenjun Xia
- Zexin Lu
- Yan Liu
- Hu Chen
- Jiliu Zhou
- Leyuan Fang
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
date: "2020-12-16T00:00:00Z"
doi: "10.1109/TMI.2020.3045207"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-16T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Medical Imaging, vol. 40, no. 10, pp. 2600-2614, 2020"
publication_short: ""

abstract: Due to its noninvasive character, optical coherence tomography (OCT) has become a popular diagnostic method in clinical settings. However, the low-coherence interferometric imaging procedure is inevitably contaminated by heavy speckle noise, which impairs both visual quality and diagnosis of various ocular diseases. Although deep learning has been applied for image denoising and achieved promising results, the lack of well-registered clean and noisy image pairs makes it impractical for supervised learning-based approaches to achieve satisfactory OCT image denoising results. In this paper, we propose an unsupervised OCT image speckle reduction algorithm that does not rely on well-registered image pairs. Specifically, by employing the ideas of disentangled representation and generative adversarial network, the proposed method first disentangles the noisy image into content and noise spaces by corresponding encoders. Then, the generator is used to predict the denoised OCT image with the extracted content features. In addition, the noise patches cropped from the noisy image are utilized to facilitate more accurate disentanglement. Extensive experiments have been conducted, and the results suggest that our proposed method is superior to the classic methods and demonstrates competitive performance to several recently proposed learning-based approaches in both quantitative and qualitative aspects.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Medical Image Processing
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/document/9296372
url_code: 'https://github.com/tsmotlp/DRGAN-OCT'
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
