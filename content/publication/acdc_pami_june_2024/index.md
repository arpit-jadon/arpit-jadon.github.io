---
title: "ACDC: The adverse conditions dataset with correspondences for robust semantic driving scene perception"
authors:
  - Christos Sakaridis*
  - Haoran Wang*
  - Ke Li
  - Rene Zurbruegg
  - admin
  - Wim Abbeloos
  - Daniel Olmeda Reino
  - Luc Van Gool
  - and Dengxin Dai
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2024-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-06-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Submitted for review to IEEE T-PAMI"
publication_short: ""

abstract: Level-5 driving automation requires a robust visual perception system that can parse input images under any condition. However, existing driving datasets for dense semantic perception are either dominated by images captured under normal conditions or are small in scale. To address this, we introduce ACDC, the Adverse Conditions Dataset with Correspondences for training and testing methods for diverse semantic perception tasks on adverse visual conditions. ACDC consists of a large set of 8012 images, half of which (4006) are equally distributed between four common adverse conditions- fog, nighttime, rain, and snow. Each adverse-condition image comes with a high-quality pixel-level panoptic annotation, a corresponding image of the same scene under normal conditions, and a binary mask that distinguishes between intra-image regions of clear and uncertain semantic content. 1503 of the corresponding normal-condition images feature panoptic annotations, raising the total annotated images to 5509. ACDC supports the standard tasks of semantic segmentation, object detection, instance segmentation, and panoptic segmentation, as well as the newly introduced uncertainty-aware semantic segmentation. A detailed empirical study demonstrates the challenges that the adverse domains of ACDC pose to state-of-the-art supervised and unsupervised approaches and indicates the value of our dataset in steering future progress in the field.


# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://people.ee.ethz.ch/~csakarid/ACDC_v2/ACDC_The_Adverse_Conditions_Dataset_with_Correspondences_for_Robust_Semantic_Driving_Scene_Perception-Sakaridis+Wang+Li+Zurbruegg+Jadon+Abbeloos+Olmeda_Reino+Van_Gool+Dai-arXiv_2024.pdf
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: 'https://acdc.vision.ee.ethz.ch/'
url_arxiv: 'https://arxiv.org/abs/2104.13395'
url_supplement: 'https://people.ee.ethz.ch/~csakarid/ACDC_v2/Supplement-ACDC_The_Adverse_Conditions_Dataset_with_Correspondences_for_Robust_Semantic_Driving_Scene_Perception-Sakaridis+Wang+Li+Zurbruegg+Jadon+Abbeloos+Olmeda_Reino+Van_Gool+Dai-arXiv_2024.pdf'
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
slides: example
---
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
