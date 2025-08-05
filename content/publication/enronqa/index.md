---
title: 'EnronQA: Towards Personalized RAG over Private Documents'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Danmei Xu
  - Chris Nivera
  - Daniel Campos

date: '2025-06-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2018-10-05T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: ArXiv Preprint
publication_short: ArXiv Preprint

abstract: Retrieval Augmented Generation (RAG) has become one of the most popular methods for bringing knowledge-intensive context to large language models (LLM) because of its ability to bring local context at inference time without the cost or data leakage risks associated with fine-tuning. A clear separation of private information from the LLM training has made RAG the basis for many enterprise LLM workloads as it allows the company to augment LLM's understanding using customers' private documents. Despite its popularity for private documents in enterprise deployments, current RAG benchmarks for validating and optimizing RAG pipelines draw their corpora from public data such as Wikipedia or generic web pages and offer little to no personal context. Seeking to empower more personal and private RAG we release the EnronQA benchmark, a dataset of 103,638 emails with 528,304 question-answer pairs across 150 different user inboxes. EnronQA enables better benchmarking of RAG pipelines over private data and allows for experimentation on the introduction of personalized retrieval settings over realistic data. Finally, we use EnronQA to explore the tradeoff in memorization and retrieval when reasoning over private documents.

# Summary. An optional shortened abstract.
summary: Retrieval Augmented Generation (RAG) has become one of the most popular methods for bringing knowledge-intensive context to large language models (LLM) because of its ability to bring local context at inference time without the cost or data leakage risks associated with fine-tuning. A clear separation of private information from the LLM training has made RAG the basis for many enterprise LLM workloads as it allows the company to augment LLM's understanding using customers' private documents. Despite its popularity for private documents in enterprise deployments, current RAG benchmarks for validating and optimizing RAG pipelines draw their corpora from public data such as Wikipedia or generic web pages and offer little to no personal context. Seeking to empower more personal and private RAG we release the EnronQA benchmark, a dataset of 103,638 emails with 528,304 question-answer pairs across 150 different user inboxes. EnronQA enables better benchmarking of RAG pipelines over private data and allows for experimentation on the introduction of personalized retrieval settings over realistic data. Finally, we use EnronQA to explore the tradeoff in memorization and retrieval when reasoning over private documents.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2505.00263v1'
url_code: ''
url_dataset: 'https://huggingface.co/datasets/MichaelR207/enron_qa_0922'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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