---
title: 'Cloud Computed Machine Learning Based Real-Time Litter Detection using Micro-UAV Surveillance'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ashley Chung
  - Sean Kim
  - Ethan Kwok
  - admin
  - Erika Tan
  - Ryan Gamadia

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'

date: '2018-07-27T00:00:00Z'
doi: '10.1109/URTC45901.2018.9244800'

# Schedule page publish date (NOT publication's date).
publishDate: '2018-10-05T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 2018 IEEE MIT Undergraduate Research Technology Conference (URTC)
publication_short: IEEE MIT URTC

abstract: Litter can remain undetected and uncollected for extended periods of time, leading to detrimental consequences on the environment. Solutions to mitigating these effects focus on severe legal action directed towards offenders or litter collection events, all of which are not automated. Therefore, to reduce the amount of manual labor required for current solutions, this project aims to implement an automated micro-unmanned aerial vehicle (UAV) capable of real time litter detection from UAV surveillance footage. Performances of five different algorithms (two classifiers and three detectors) were compared after training them on various public images of litter on the Google Cloud Platform to determine the strongest models to utilize in the ensemble method. Out of the two ensemble models tested, one being a custom-built ensemble and the other being a bootstrap aggregating (bagging) ensemble, performance of the bagging ensemble demonstrates a significant improvement in performance over any individual model.

# Summary. An optional shortened abstract.
summary: Litter can remain undetected and uncollected for extended periods of time, leading to detrimental consequences on the environment.  The use of drones to detect this litter marks an important step towards solving this problem.  We test five different computer vision algorithms for litter detection using drone surveillance and show a bagging ensemble of these methods to have the highest performance.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/gset-drones/litter-detection.pdf'
url_code: 'https://github.com/XenonMolecule/CVML-GSET-Project'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=RWIr5zlDa6I'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Litter Detected in MicroUAV Serveillance Feed'
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