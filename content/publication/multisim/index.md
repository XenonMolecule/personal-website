---
title: 'Revisiting non-English Text Simplification: A Unified Multilingual Benchmark'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin 
  - Tarek Naous
  - Wei Xu

date: '2023-07-10T00:00:00Z'
doi: '10.18653/v1/2023.acl-long.269'

# Schedule page publish date (NOT publication's date).
publishDate: '2018-10-05T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 61st Annual Meeting of the Association for Computational Linguistics
publication_short: ACL 2023

abstract: Recent advancements in high-quality, large-scale English resources have pushed the frontier of English Automatic Text Simplification (ATS) research. However, less work has been done on multilingual text simplification due to the lack of a diverse evaluation benchmark that covers complex-simple sentence pairs in many languages. This paper introduces the MultiSim benchmark, a collection of 27 resources in 12 distinct languages containing over 1.7 million complex-simple sentence pairs. This benchmark will encourage research in developing more effective multilingual text simplification models and evaluation metrics. Our experiments using MultiSim with pre-trained multilingual language models reveal exciting performance improvements from multilingual training in non-English settings. We observe strong performance from Russian in zero-shot cross-lingual transfer to low-resource languages. We further show that few-shot prompting with BLOOM-176b achieves comparable quality to reference simplifications outperforming fine-tuned models in most languages. We validate these findings through human evaluation.

# Summary. An optional shortened abstract.
summary: We release the MultiSim benchmark, a collection of 27 resources in 12 distinct languages containing over 1.7 million complex-simple sentence pairs. This benchmark will encourage research in developing more effective multilingual text simplification models and evaluation metrics. Our experiments using MultiSim with pre-trained multilingual language models reveal exciting performance improvements from multilingual training in non-English settings.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/multisim/2023.acl-long.269.pdf'
url_code: 'https://github.com/xenonmolecule/multisim'
url_dataset: 'https://huggingface.co/datasets/MichaelR207/MultiSim'
url_poster: 'publication/multisim/MultiSimPoster.pdf'
url_project: ''
url_slides: 'publication/multisim/MultiSim_slides.pdf'
url_source: ''
url_video: 'https://www.youtube.com/watch?v=RWIr5zlDa6I'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Example sentence pairs in the MultiSim dataset in English, Japanese, Urdu, and Russian'
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