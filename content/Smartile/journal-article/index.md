---
title: "Smartile: A Dynamic Sparsity-Pattern-Aware Tiling Strategy for Sparse Tensor Algebra Acceleration"
authors:
- admin
- Hajar Falahati
- Negin Mahani
- Adrian Cristal
- Osman Unsal
- Hamid Sarbazi-Azad


# Schedule page publish date (NOT publication's date).
# publishDate: "2025-07-04T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Under review at ISCA 2026"
publication_short: ""

abstract: Tiling is a widely used approach to increase arithmetic intensity and data reuse in tensor algebra workloads; however, it becomes challenging for large and highly sparse tensors due to the irregular distribution of nonzero elements across the tensor. While coordinate space tiling (CST) and position space tiling (PST) offer distinct advantages, they either lack sparsity pattern support or incur high preprocessing and runtime costs. Several solutions attempt to address these issues but fall short for large tensors with highly nonuniform sparsity patterns. In this work, we introduce _Smartile_, a dynamic tiling strategy that provides sparsity pattern support by employing a divide-and-conquer approach. We first introduce _Distance From Uniform (DFU)_, a lightweight method for assessing a tensor's sparsity pattern using Kullback-Leibler divergence, which is then used in our recursive tile construction algorithm. We further design a hardware unit to realize Smartile, demonstrating the feasibility of integrating our tiling strategy into existing accelerators. Across a suite of 67 sparse tensor algebra workloads, we show that Smartile achieves an average speedup ranging from 2x to 6x over DRT, Swiftiles, RASSM, and HYTE, with only 0.6% area overhead.


# Summary. An optional shortened abstract.


featured: false

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 


# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: ['Smartile']
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
---

