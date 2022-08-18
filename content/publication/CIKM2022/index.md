---
title: 'Dismantling Complex Networks by a Neural Model Trained from Tiny Networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Bang Wang

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

# date: '2022-07-01T00:00:00Z'
doi: 'https://doi.org/10.1145/3511808.3557290'

# # Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 31st ACM International Conference on Information and Knowledge Management*
publication_short: In *CIKM'22*

abstract: Can we employ one neural model to efficiently dismantle many complex yet unique networks? This article provides an affirmative answer. Diverse real-world systems can be abstracted as complex networks each consisting of many functional nodes and edges. Percolation theory has indicated that removing only a few vital nodes can cause the collapse of whole network. However, finding the least number of such vital nodes is a rather challenging task for large networks due to its NP-hardness. Previous studies have proposed many centrality measures and heuristic algorithms to tackle this network dismantling (ND) problem. Different from theirs, this article tries to approach the ND task by designing a neural model which can be trained from tiny synthetic networks but will be applied for various real-world networks. It seems a discouraging mission at first sight, as network sizes and topologies are quite different across distinct real-world networks. Nonetheless, this article initiates insightful efforts of designing and training a neural influence ranking model (NIRM). Experiments on fifteen real-world networks validate its effectiveness for its mostly requiring fewer vital nodes to dismantle a network, compared with the state-of-the-art competitors. The key to its success lies in that our NIRM can efficiently encode both local structural and global topological signals for ranking nodes, in addition to our innovative labelling method in training dataset construction.

# Summary. An optional shortened abstract.
summary: This article tries to approach the ND task by designing a neural model which can be trained from tiny synthetic networks but will be applied for various real-world networks.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2208.07792.pdf'
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
image:
  caption: '(logo.png)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
