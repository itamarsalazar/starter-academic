---
title: "Detecting Violent Robberies in CCTV Videos Using Deep Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Morales Giorgio
- Salazar-Reque I F
- Telles Joel
- Diaz Daniel

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2019-05-12T00:00:00Z"
doi: "https://doi.org/10.1007/978-3-030-19823-7_23"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-08T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Artificial Intelligence Applications and Innovations. AIAI 2019.*
publication_short: In *Artificial Intelligence Applications and Innovations. AIAI 2019.*

abstract: Video surveillance through security cameras has become difficult due to the fact that many systems require manual human inspection for identifying violent or suspicious scenarios, which is practically inefficient. Therefore, the contribution of this paper is twofold. The presentation of a video dataset called UNI-Crime, and the proposal of a violent robbery detection method in CCTV videos using a deep-learning sequence model. Each of the 30 frames of our videos passes through a pre-trained VGG-16 feature extractor; then, all the sequence of features is processed by two convolutional long-short term memory (convLSTM) layers; finally, the last hidden state passes through a series of fully-connected layers in order to obtain a single classification result. The method is able to detect a variety of violent robberies (i.e., armed robberies involving firearms or knives, or robberies showing different level of aggressiveness) with an accuracy of 96.69%.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://link.springer.com/chapter/10.1007/978-3-030-19823-7_23'
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
