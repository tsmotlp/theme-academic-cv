---
title: 'Disentanglement network for unsupervised speckle reduction of optical coherence tomography images'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Wenjun Xia
  - Zexin Lu
  - Yan Liu
  - Jiliu Zhou
  - Leyuan Fang
  - Yi Zhang

# Author notes (optional)
author_notes:
  -
  -
  -
  -
  -
  -
  - "Corresponding Author"

date: '2020-09-29T00:00:00Z'
doi: '10.1007/978-3-030-59722-1_65'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-09-29T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Medical Image Computing and Computer Assisted Intervention–MICCAI 2020, pp. 675-684*
publication_short: In *MICCAI 2020*

abstract: Optical coherence tomography (OCT) has received increasing attention in the diagnosis of ophthalmic diseases due to its noninvasive character. However, the speckle noise associated with the low coherence interferometric imaging modality has considerably negative influence on its clinical application. Moreover, the lack of clean and corresponding noisy OCT image pairs makes it difficult for supervised learning-based approaches to achieve satisfactory denoising results. Therefore, inspired by the idea of disentangled representation and generative adversarial network (GAN), we propose an unsupervised OCT image speckle reduction algorithm which firstly disentangles the noisy image into content and noise spaces by corresponding encoders. Then the generator is used to predict denoised OCT image only with the extracted content features. In addition, the pure noise patches which are cut from the noisy image are utilized to ensure a purer disentanglement. Extensive experiments have been conducted and the results suggest that our proposed method demonstrates competitive performance with respect to other state-of-the-art approaches.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Medical Image Processing

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://link.springer.com/chapter/10.1007/978-3-030-59722-1_65'
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
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
