---
title: "ECG signal classification using convolutional neural networks"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

# Author notes (optional)
author_notes:
- "Equal contribution"

date: "2020-05-01T00:00:00Z"
doi: "10.32016/1.71.08"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Zeszyty Naukowe Wydziału Elektrotechniki i Automatyki Politechniki Gdańskiej
publication_short: 

abstract: Automation and improvement of diagnostic process is a vital element of medicine development and patient’s condition self-control. For a long time different ECG signal classification methods exist and are successfully applied, nevertheless their accuracy is not always satisfying enough. The lack of identification of an existing abnormality, which is very similar to a normal heartbeat is the biggest issue - for example premature ventricular contraction. Over the past few years there was a rapid development of an artificial intelligence tool - deep neural networks. They characterise by a high classification ability even the most complicated patterns in the form of time series or images, often based on features unnoticeable for human eye. In this paper the approach to electrocardiography (ECG) analysis was presented, taking into consideration a single heartbeat. The aim of this research was diagnosis of six different types of beat that may indicate arrhythmia occurrence. The study were performed on the public database MIT-BIH Arrhythmia Database. In order to enhance feature extraction quality of the analysed signal the time-space decomposition was made using wavelet transform. The satisfying performance with 92.4% accuracy and 96.5% specificity were accomplished. The achieved results may be used to develop an automatic heartbeat classification system that would significantly contribute medicians in the arduous process of data analysis.

# Summary. An optional shortened abstract.
summary: In this paper the deep learning approach to electrocardiography (ECG) analysis was presented, taking into consideration a single heartbeat.

tags: [EKG, arrhythmia, convolutional neural networks, deep learning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# url_pdf: 'https://eia.pg.edu.pl/documents/10623/32925502/ZN_WEiAPG_71.pdf'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

# {{% callout note %}}
# Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /callout %}}

# {{% callout note %}}
# Create your slides in Markdown - click the *Slides* button to check out the example.
# {{% /callout %}}

# Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
