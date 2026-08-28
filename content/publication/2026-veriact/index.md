---
title: 'VeriAct: Beyond Verifiability -- Agentic Synthesis of Correct and Complete Formal Specifications'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Md Rakib Hossain Misu
  - admin
  - Cristina Videira Lopes

date: '2026-03-31'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-03-31'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['manuscript']

# Publication name and optional abbreviated publication name.
publication: Under review. Preprint on arXiv.
publication_short: Under review

abstract: Formal specifications are essential for software reliability, yet automatically creating high-quality ones remains difficult. We compare classical and prompt-based methods for generating Java Modeling Language specifications and find that, while these approaches achieve high verifier-acceptance rates, verifier acceptance does not reliably indicate correctness. We introduce Spec-Harness, an evaluation framework using symbolic verification to assess specification quality, and show that many verifier-approved specifications are actually flawed, either over- or under-constraining system behavior. To address this, we develop VeriAct, an agent-driven system that iteratively synthesizes and refines specifications through a closed loop of LLM-driven planning, code execution, verification, and feedback. Testing on benchmark datasets demonstrates VeriAct produces specifications that are both verifiable and genuinely correct.

# Summary. An optional shortened abstract.
summary: An agentic system that iteratively synthesizes and refines formal specifications, going beyond verifier acceptance to ensure genuine correctness and completeness.

tags: [Formal Verification, LLMs]

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://arxiv.org/abs/2604.00280'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
