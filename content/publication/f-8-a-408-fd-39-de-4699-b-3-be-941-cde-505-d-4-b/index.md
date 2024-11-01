---
title: Hypervolume-Guided Decomposition for Parallel Expensive Multiobjective Optimization

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Liang Zhao
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-04-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.053940Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Evolutionary Computation*'
publication_short: ''

doi: 10.1109/TEVC.2023.3265347

abstract: 'The hypervolume metric is widely used to guide the search in multiobjective
  optimization. However, in parallel expensive multiobjective optimization, the hypervolume-based
  multi-point expected improvement (EI) suffers from high computational overhead and
  scales poorly with the batch size. To address this issue, we integrate hypervolume-based
  EI with the MOEA/D framework and propose a novel EI, named the expected direction-based
  hypervolume improvement (DirHV-EI). The DirHV-EI only measures the hypervolume improvement
  within each axis-parallel box induced by the modified Tchebycheff scalarization.
  Thus, it has a simple analytical expression that can be easily computed. Theoretical
  analysis indicates that the maximization of our proposed improvement function can
  help to maximize both the weighted hypervolume and the Tchebycheff improvement metrics.
  Using DirHV-EI, we design a decomposition-based Bayesian optimization algorithm,
  called DirHV-EGO, for solving expensive multiobjective optimization problems. At
  each iteration, the MOEA/D is used to maximize the DirHV-EI values with respect
  to a number of direction vectors in a collaborative manner, and a number of candidate
  solutions can be obtained. Then, a submodularity-based greedy selection strategy
  is used to select multiple query points from the candidates. Experimental results
  on both benchmark instances and real-world problems show that our proposed algorithm
  is an efficient and effective method for parallel expensive multiobjective optimization.
  © 2023 IEEE. '

# Summary. An optional shortened abstract.
summary: ''

tags:
- Decomposition
- efficient global optimization
- expected improvement
- expensive multiobjective optimization
- Hypervolume

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
