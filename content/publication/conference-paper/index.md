---
title: "Graph Attention based Proposal 3D ConvNets for Action Detection"
authors:
- Jun Li
- Xianglong Liu
- admin
date: "2020-04-01T00:00:00Z"
doi: "10.1609/aaai.v34i04.5893"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-04-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the AAAI Conference on Artificial Intelligence*
publication_short: In *AAAI 2020*

abstract: The recent advances in 3D Convolutional Neural Networks (3D CNNs) have shown promising performance for untrimmed video action detection, employing the popular detection framework that heavily relies on the temporal action proposal generations as the input of the action detector and localization regressor. In practice the proposals usually contain strong intra and inter relations among them, mainly stemming from the temporal and spatial variations in the video actions. However, most of existing 3D CNNs ignore the relations and thus suffer from the redundant proposals degenerating the detection performance and efficiency. To address this problem, we propose graph attention based proposal 3D ConvNets (AGCN-P-3DCNNs) for video action detection. Specifically, our proposed graph attention is composed of intra attention based GCN and inter attention based GCN. We use intra attention to learn the intra long-range dependencies inside each action proposal and update node matrix of Intra Attention based GCN, and use inter attention to learn the inter dependencies between different action proposals as adjacency matrix of Inter Attention based GCN. Afterwards, we fuse intra and inter attention to model intra long-range dependencies and inter dependencies simultaneously. Another contribution is that we propose a simple and effective framewise classifier, which enhances the feature presentation capabilities of backbone model. Experiments on two proposal 3D ConvNets based models (P-C3D and P-ResNet) and two popular action detection benchmarks (THUMOS 2014, ActivityNet v1.3) demonstrate the state-of-the-art performance achieved by our method. Particularly, P-C3D embedded with our module achieves average mAP 3.7% improvement on THUMOS 2014 dataset compared to original model.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://aaai.org/ojs/index.php/AAAI/article/view/5893/5749
url_code: '#'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
