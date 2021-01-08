---
title: "An Algorithm for Plant Disease Visual Symptom Detection in Digital Images Based on Superpixels"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Salazar-Reque I F
- Huaman Gustavo
- Kemper Guillermo
- Telles Joel
- Diaz Daniel

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2019-01-01T00:00:00Z"
doi: "https://doi.org/10.18517/ijaseit.9.1.5322"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-08T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *International Journal on Advanced Science, Engineering and Information Technology*
publication_short: In *International Journal on Advanced Science, Engineering and Information Technology*

abstract: Quantifying diseased areas in plant leaves is an important procedure in agriculture, as it contributes to crop monitoring and decision-making for crop protection. It is, however, a time-consuming and very subjective manual procedure whose automation is, therefore, highly expected. This work proposes a new method for the automatic segmentation of diseased leaf areas. The method used the Simple Linear Iterative Clustering (SLIC) algorithm to group similar-color pixels together into regions called superpixels. The color features of superpixel clusters were used to train artificial neural networks (ANNs) for the classification of superpixels as healthy or not healthy. These network parameters were heuristically tuned by choosing the network with the best classification performance to obtain the automatic segmentation of the diseased areas. The performance of the classifier was measured by comparing its automatic segmentations with those manually made from a database with public and private images divided into nine groups by visual symptom and plant. The mean error of the area obtained was always below 11%, and the average F-score was 0.67, which is higher than that found by the other two approaches reported in the literature (0.57 and 0.58) and used here for comparison.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'http://insightsociety.org/ojaseit/index.php/ijaseit/article/download/5322/pdf_1015'
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
