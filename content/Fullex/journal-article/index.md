---
title: "Fullex: A Full-Dense Approach to Matrix Multiplication in Sparse Structures"
authors:
- Danial Farsi
- Mahdi Pazooki
- admin
- Hajar Falahati
- Negin Mahani
- Hakem Beitolahi
- Adiran Cristal
- Osman Unsal


# Schedule page publish date (NOT publication's date).
# publishDate: "2022-07-04T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: '<a href="https://spice.cs.umd.edu/#:~:text=Fullex\%3A\%20A\%20Full\%2Ddense\%20Approach\%20to\%20Matrix\%20Multiplication\%20in\%20Sparse\%20Structures">SPICE 2025 Workshop</a>, co-located with MICRO 2025, Seoul, Korea, October 18, 2025 (peer-reviewed workshop paper).'
publication_short: ""

abstract: Matrix multiplication is a fundamental operation in deep neural networks (DNNs); however, modern workloads are often highly sparse, resulting in irregular memory access patterns and poor locality. Outer product formulations offer greater reuse and compression opportunities compared to inner product approaches, but they incur overhead due to the generation of many intermediate partial matrices. Prior methods attempt to mitigate this by merging sparse columns, but they remain limited—typically merging only around 68.3%—because they overlook deeper correlations between computation and data. In this work, we present _Fullex_, a matrix reformation technique that enhances sparsity support in outer product-based multiplication. Our key observation is that all entries of a column are multiplied by the same operands, enabling two opportunities; (1) rearranging entries across rows to increase column merging, and (2) detecting repetition within a column to reuse computation and free capacity for further merging. Fullex further employs differential data representation to improve compression in highly sparse matrices. Evaluated on 20 sparse workloads from synthetic benchmarks and the SuiteSparse collection, Fullex delivers 1.45x speedup, 33.2% energy reduction, and a 41.9% decrease in partial matrices over SpArch, a state-of-the-art sparse matrix multiplication architecture, while incurring negligible metadata overhead.


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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
---

