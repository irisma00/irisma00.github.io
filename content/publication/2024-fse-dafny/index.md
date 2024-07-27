---
title: 'Towards AI-Assisted Synthesis of Verified Dafny Methods'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Md Rakib Hossain Misu
  - Cristina Videira Lopes
  - admin
  - James Noble

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-02-2'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-02-02'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper']

# Publication name and optional abbreviated publication name.
publication: In ACM International Conference on the Foundations of Software Engineering (FSE 2024)
publication_short: In FSE 2024

abstract: Large stochastic language models show great promise in many domains, including programming. A promise is easy to make but hard to keep, and language models often fail to keep their promises when applied to programming, generating erroneous code. One promising avenue to keep models honest is to have them generate code in a language that supports formal verification`:` if and when that is adopted, the model would provide proof along with the code, and that proof would be automatically verified. Unfortunately, existing large language models show a severe lack of proficiency in verified programming languages. <br>In this paper we demonstrate how to improve two pretrained models’ proficiency in the Dafny verified programming language. Using 178 programming problems from the MBPP dataset, we prompt two contemporary models (GPT-4 and PaLM-2 ) to generate methods in Dafny. We use three different types of prompts`:` a direct contextless prompt, a second one that includes a signature of the method and test cases, and a third one that decomposes the problem into steps and includes dynamically chosen similar examples. Our results show that GPT-4 is better than PaLM-2 , but that, in both models, the third prompt greatly improves the success of the generation task with respect to the direct prompt. With the third prompt, GPT-4 was able to generate verified (and human-evaluated) Dafny methods in 58\% of the cases, while the first prompt generated verified (and human-evaluated) methods in only 19\% of the cases. Surprisingly, the second prompt had the worst performance, with only 10\%. <br>One tangible contribution of our work is a collection of 153 MBPP problems that are implemented and formally verified in Dafny, 50 of which were written by us and 103 were automatically synthesized by GPT-4 . Additionally, our results demonstrate that the benefits of formal program verification (proof of correctness) are now within reach of large stochastic language models used to generate code. These results also demonstrate that program verification systems can likewise benefit from incorporating large language models, whether to synthesize code wholesale, to generate specifications, or to construct internal verification annotations such as loop invariants, that are hard for programmers and verification tools to find directly. (e.g. legal arguments, transport signaling, structural engineering, etc.) where solutions must be correct, and where that correctness needs to be verifiable by existing formal tools, or explained to (and understood by) designers and end-users.

# Summary. An optional shortened abstract.
summary: LLM shows “great promise” in code synthesis. Can LLM keep "the promise" to ensure that its synthesis code is formally correct?

tags: [LLMs]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/abs/10.1145/3643763'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''



# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

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

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/). -->
