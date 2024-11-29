---
title: 'Having Beer after Prayer? Measuring Cultural Bias in Large Language Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Tarek Naous
  - admin 
  - Alan Ritter
  - Wei Xu

date: '2023-05-23T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2018-10-05T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: 62nd Annual Meeting of the Association for Computational Linguistics (Main Conference)
publication_short: ACL 2024

abstract: Are language models culturally biased? It is important that language models conform to the cultural aspects of the communities they serve. However, we show in this paper that language models suffer from a significant bias towards Western culture when handling and generating text in Arabic, often preferring, and producing Western-fitting content as opposed to the relevant Arab content. We quantify this bias through a likelihood scoring-based metric using naturally occurring contexts that we collect from online social media. Our experiments reveal that both Arabic monolingual and multilingual models exhibit bias towards Western culture in eight different cultural aspects (person names, food, clothing, location, literature, beverage, religion, and sports). Models also tend to exhibit more bias when prompted with Arabic sentences that are more linguistically aligned with English. These findings raise concerns about the cultural relevance of current language models. Our analyses show that providing culture-indicating tokens or culturally-relevant demonstrations to the model can help in debiasing.

# Summary. An optional shortened abstract.
summary: Are language models culturally biased? It is important that language models conform to the cultural aspects of the communities they serve. However, we show in this paper that language models suffer from a significant bias towards Western culture when handling and generating text in Arabic, often preferring, and producing Western-fitting content as opposed to the relevant Arab content. We quantify this bias through a likelihood scoring-based metric using naturally occurring contexts that we collect from online social media.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://aclanthology.org/2024.acl-long.862.pdf'
url_code: ''
url_dataset: 'https://github.com/tareknaous/camel'
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