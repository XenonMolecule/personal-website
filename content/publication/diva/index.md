---
title: 'Distilling an End-to-End Voice Assistant Without Instruction Training Data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - William Held
  - Ella Li
  - admin 
  - Weiyan Shi
  - Yanzhe Zhang
  - Diyi Yang

date: '2024-10-03T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2018-10-05T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: Arxiv Preprint (Under Review)
publication_short: Arxiv

abstract: Voice assistants, such as Siri and Google Assistant, typically model audio and text separately, resulting in lost speech information and increased complexity. Recent efforts to address this with end-to-end Speech Large Language Models (LLMs) trained with supervised finetuning (SFT)
have led to models "forgetting" capabilities from text-only LLMs. Our work proposes an alternative paradigm for training Speech LLMs without instruction data, using the response of a text-only LLM to transcripts as self-supervision. Importantly, this process can be performed without annotated responses. We show that our Distilled Voice Assistant (DiVA) generalizes to Spoken Question Answering, Classification, and Translation. Furthermore, we show that DiVA better meets user preferences, achieving a 72% win rate compared with state-of-the-art models like Qwen 2 Audio, despite using >100x less training compute.

# Summary. An optional shortened abstract.
summary: DiVA is a new method to turn a text-only LLM to a Speech LLM using only weak supervision. DiVA learns to encode speech while preserving the underlying LLM output distribution using cross-modal context distillation between text and speech. DiVA Llama 3 8B is preferred by users to prior SoTA Speech LLMs and achieves competetive benchmark numbers, despite training with 100x less compute. DiVA was trained using entirely open-source code in Levanter, on 3.5k hours of publicly available ASR data from Common Voice, and is released under a Mozilla Public License.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2410.02678'
url_code: 'https://github.com/Helw150/levanter/blob/will/distill/src/levanter/models/via.py'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://diva-audio.github.io'
url_video: 'https://x.com/WilliamBarrHeld/status/1846581201194340658'

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