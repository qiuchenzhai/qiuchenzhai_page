---
title: 'Projected Multi-Agent Consensus Equilibrium for Ptychographic Image Reconstruction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Qiuchen Zhai
  - Brendt Wohlberg
  - Gregery T. Buzzard
  - Charles A. Bouman

# Author notes (optional)
author_notes:
 - ''
 - ''

date: '2021-OCT'
doi: '10.1109/IEEECONF53345.2021.9723357'

# # Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Asilomar Conference*
publication_short: In *55th Asilomar*

abstract: Ptychography is a computational imaging technique using multiple, overlapping, coherently illuminated snapshots to achieve nanometer resolution by solving a nonlinear phase-field recovery problem. Ptychography is vital for imaging of manufactured nanomaterials, but existing algorithms have computational shortcomings that limit large-scale application.In this paper, we present the Projected Multi-Agent Consensus Equilibrium (PMACE) approach for solving the ptychography inversion problem. This approach extends earlier work on MACE, which formulates an inversion problem as an equilibrium among multiple agents, each acting independently to update a full reconstruction. In PMACE, each agent acts on a portion (projection) corresponding to one of the snapshots, and these updates to projections are then combined to give an update to the full reconstruction. The resulting algorithm is easily parallelized, with convergence properties inherited from convergence results associated with MACE. We apply our method on simulated data and demonstrate that it outperforms competing algorithms in both reconstruction quality and convergence speed.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2111.14240v2'
url_code: 'https://github.com/cabouman/ptycho_pmace'
url_dataset: 'https://drive.google.com/drive/folders/1feA5LdkEjVJhqhyFRu7ErgqwKa9Nbkxp?usp=share_link'
url_poster: 'https://engineering.purdue.edu/~bouman/publications/pdf/Asilomar2021-Qiuchen-poster.pdf'
# url_project: 
# url_slides: 
# url_source: 
url_video: 'https://youtu.be/cBpaJMESKfo'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

# Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
