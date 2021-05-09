---
title: "Replacing FC layers in a CNN could improve robustness against adversarial attacks"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Salazar-Reque I F
- Otazu Aldana G
- Huaman Bustamante S G

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2020-06-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-06-08T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *CIFAR DLRL Summer School*
publication_short: In *CIFAR DLRL Summer School*

abstract: 
Current neural networks for image classifications consist of layers of neurons performing simple computations, which approximate linear functions. As these functions approximate linear classifiers, the training of such networks is simplified. On the flip side, linear classifiers are intrinsically susceptible for adversarial small perturbations that could flip an image across a classification boundary, creating misclassifications that are imperceptible for human beings. Although adversarial examples are calculated from a particular network architecture, they generalize to different network architectures. In this contribution, we report that, after training, replacing the last fully connected segment for an algorithm that operates by proximity highly improves CNN robustness against adversarial perturbations. We have tested our modified network in the MNIST database using adversarial examples. By varying the perturbation amplitude, we show that for an amplitude perturbation of 0.25 our model performs at least 55% of accuracy whereas the standard network collapses to 15 percent.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://github.com/itamarsalazar/starter-academic/blob/master/content/publication/2020_CPA_DLRLsummerSchool/POSTER_DLRL_IFSR.pdf'
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
