---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Research Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Junior Researcher
    company: Barcelona Supercomputing Center
    company_url: 'https://bsc.es'
    company_logo: BSC-blue
    location: Barcelona, Spain
    date_start: '2025-08-01'
    date_end: 
    decsription: |2-
        * _Computer Architecture for Parallel Paradagms (CAPP)_ group
        * Under supervison of Prof. Osman Unsal and Prof. Adrian Cristal
        * Working on the implementation of a dedicated hardware unit for efficient execution of our proposed tiling algorithm for sparse tensor algebra acceleration.
    
  - title: Research Assistant
    company: Sharif University of Technology
    company_url: 'https://sharif.edu'
    company_logo: sharif
    location: Tehran, Iran
    date_start: '2023-07-01'
    date_end: '2025-06-30'
    decsription: |2-
        * _High-Performance Computing Architecture and Network (HPCAN)_ group
        * Under supervison of Prof. Hamid Sarbazi-Azad
        * Worked on tiling in sparse tensor algebra acceleration (collaborating with Dr. Hajar Falahati & Dr. Negin Mahani).
        * Contributed to two other projects
            1) _CSA-PIM_: Exploiting carry-save adder to reduce shift operations in Processing-in-Memory systems based on DRAM (collaborating with Dr. Nezam Rohbani)
            2) _Fullex_: Improving the representation of sparse tensors to reduce the number of intermediate matrices in outer-product-based matrix multiplication.


design:
  columns: '2'
---
