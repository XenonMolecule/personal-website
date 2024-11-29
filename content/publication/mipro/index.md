---
title: 'Optimizing Instructions and Demonstrations for Multi-Stage Language Model Programs'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - kristaStar
  - adminStar
  - Josh Purtell
  - David Broman
  - Christopher Potts
  - Matei Zaharia
  - Omar Khattab

date: '2024-11-10T00:00:00Z'
doi: '10.18653/v1/2024.emnlp-main.525'

# Schedule page publish date (NOT publication's date).
publishDate: '2018-10-05T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 2024 Conference on Empirical Methods in Natural Language Processing (Main Conference)
publication_short: EMNLP 2024

abstract: Language Model Programs, i.e. sophisticated pipelines of modular language model (LM) calls, are increasingly advancing NLP tasks, but they require crafting prompts that are jointly effective for all modules. We study prompt optimization for LM programs, i.e. how to update these prompts to maximize a downstream metric without access to module-level labels or gradients. To make this tractable, we factorize our problem into optimizing the free-form instructions and few-shot demonstrations of every module and introduce several strategies to craft task-grounded instructions and navigate credit assignment across modules. Our strategies include (i) program- and data-aware techniques for proposing effective instructions, (ii) a stochastic mini-batch evaluation function for learning a surrogate model of our objective, and (iii) a meta-optimization procedure in which we refine how LMs construct proposals over time. Using these insights we develop MIPRO, a novel algorithm for optimizing LM programs. MIPRO outperforms baseline optimizers on five of seven diverse multi-stage LM programs using a best-in-class open-source model (Llama-3-8B), by as high as 13% accuracy. We have released our new optimizers and benchmark in DSPy at [http://dspy.ai](http://dspy.ai).

# Summary. An optional shortened abstract.
summary: We present MIPROv2, a language model program optimizer which improves both prompts and fewshot demonstrations for multistage language model programs.  Our strategies include (i) program- and data-aware techniques for proposing effective instructions, (ii) a stochastic mini-batch evaluation function for learning a surrogate model of our objective, and (iii) a meta-optimization procedure in which we refine how LMs construct proposals over time. MIPRO outperforms baseline optimizers on five of seven diverse multi-stage LM programs using a best-in-class open-source model (Llama-3-8B), by as high as 13% accuracy.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://aclanthology.org/2024.emnlp-main.525.pdf'
url_code: 'https://github.com/stanfordnlp/dspy'
url_dataset: 'https://github.com/stanfordnlp/dspy/tree/main/testing'
url_poster: ''
url_project: ''
url_slides: '/publication/mipro/Slides.pdf'
url_source: ''
url_video: 'https://youtu.be/cEiB7_Wl53g'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---