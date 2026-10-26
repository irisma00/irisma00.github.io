---
title: 'The Geometry of Logic: Stratification Induces Semantic Structure and Robust Reasoning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Cristina Videira Lopes
  - Yuangang Li
  - Justin Tian Jin Chen
  - Alberto Krone-Martins
  - admin
  - Md Rakib Hossain Misu

date: '2026-09-26'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-09-26'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['manuscript']

# Publication name and optional abbreviated publication name.
publication: Under review. Preprint on arXiv.
publication_short: Under Review

abstract: >-
  Transformer-based language models perform well on symbolic tasks, yet it remains unclear whether they learn generalizable rules or rely on statistical shortcuts. Mechanistic studies link algorithmic behavior to structured internal representations, motivating the hypothesis that robust reasoning benefits from separating values from the types that control their manipulation. Can making this separation an architectural primitive improve the learnability and generalization of logical mechanisms? We introduce STRAT (STratified Registers And Types), which partitions the residual stream into orthogonal Data and Type subspaces and uses Type-based attention and gating to govern Data transformations. Controlled arithmetic ablations identify three failure modes associated with data-control interference: the Linear Trap, Gradient Wall, and Open Gate Trap. Mechanistic analysis reveals interpretable logical structure, and in arithmetic, STRAT reduces median OOD error 35-fold relative to a Transformer baseline. On each of 11 datasets spanning 10 tasks, STRAT outperforms the Transformer baseline in mean accuracy, by 26 percentage points on average, with both models trained from 10 base examples per dataset using identical task-specific augmentation where applicable. Under distribution shift, STRAT's mean accuracy drops by only 2.39 percentage points, compared with 11.75 for the Transformer.

# Summary. An optional shortened abstract.
summary: A transformer architecture that partitions the residual stream into orthogonal Data and Type subspaces, improving out-of-distribution generalization and robustness on symbolic reasoning tasks.

tags: [LLMs]

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://arxiv.org/abs/2609.32927'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
