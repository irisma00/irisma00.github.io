---
title: 'Memorization: A Close Look at Books'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Ian Domingo
  - Alberto Krone-Martins
  - Pierre Baldi
  - Cristina Videira Lopes

date: '2025-08-01'
doi: '10.18653/v1/2025.l2m2-1.13'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-08-01'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['workshop']

# Publication name and optional abbreviated publication name.
publication: In Proceedings of the 1st Workshop on Large Language Model Memorization (L2M2 2025), Association for Computational Linguistics, Vienna, Austria.
publication_short: In ACL L2M2 2025, Vienna, Austria

abstract: We investigate how completely books can be retrieved from language models. Using Llama 3 70B and a prefix-prompting extraction method, we reconstruct "Alice's Adventures in Wonderland" with high fidelity from merely the opening 500 tokens, and observe strong extraction on other books as well, though success rates vary considerably across titles and correlate with book popularity, suggesting training-data duplication plays a role. We also document how instruction-tuning in Llama 3.1 reversed earlier safeguards designed to prevent memorization, tracing these changes to a small weight subset in lower transformer layers. This work demonstrates weaknesses in current mitigation approaches and offers tools for examining how fine-tuning influences verbatim recall in aligned language models.

# Summary. An optional shortened abstract.
summary: Extracting full books from Llama models via prefix prompting, and showing that instruction-tuning can undo alignment's memorization mitigations.

tags: [LLMs]

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://doi.org/10.18653/v1/2025.l2m2-1.13'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
