---
title: "A Neural Anisotropic View of Underspecification in Deep Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Ortiz-Jimenez G
- Salazar-Reque I F
- Apostolos M
- Moosavi-Dezfooli SM 
- Frossard P


# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-05-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-08T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *Robust and Reliable Machine Learning in the Real World at the ICLR 2021*
publication_short: In *Robust and Reliable Machine Learning in the Real World at the ICLR 2021*

abstract: The underspecification of most machine learning pipelines means that we cannot rely solely on validation performance to assess the robustness of deep learning systems to naturally occurring distribution shifts. Instead, making sure that a neural network can generalize across a large number of different situations requires to understand the specific way in which it solves a task. In this work, we propose to study this problem from a geometric perspective with the aim to understand two key characteristics of neural network solutions in underspecified settings:How is the geometry of the learned function related to the data representation? And, are deep networks always biased towards simpler solutions, as conjectured in recent literature?  We show that the way neural networks handle the underspecification of these problems is highly dependent on the data representation, affecting both the geometry and the complexity of the learned predictors. Our results highlight that understanding the architectural inductive bias in deep learning is fundamental to address the fairness, robustness, and generalization of these systems..

# Summary. An optional shortened abstract.
summary: How an artificial neural network will behave when multiple solutions for a single task exist?
Will they pick the "simplest" one, as some literature suggest? In this work, we found that CNNs sometimes prefer complex non-robust solutions even though a simpler and robust one exist.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2104.14372.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**IFSR**](https://itamarsalazar.netlify.app/)'
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

<!--{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->

Share this post:
