---
title: '結合力埋込型弾塑性構成則および確率論的選点法を用いた脆性延性遷移領域のバラつき評価'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - 松井晟進
  - 新宅勇一
  - 寺田賢二郎

# Author notes (optional)
#author_notes:
  #- 'Equal contribution'
  #- 'Equal contribution'

date: '2024-10-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 計算力学講演会講演論文集
publication_short: 第37回計算力学講演会

abstract: The contribution of this study is to present a numerical analysis method by combined use of a cohesive-traction embedded elasto-plastic constitutive law based on hyper-elastic model and a stochastic collocation (SC) method which can efficiently calculate statistics. A cohesive-traction embedded elasto-plastic constitutive law has been proposed by combining Gurson-Tvergaad-Needleman (GTN) model with cohesive zone model to realize the change of fracture behavior associated with transition from brittle to ductile failure at different temperature. GTN model enables us to represent the shrink of the yield surface depending on the void volume fraction. On the other hand, the cohesive zone model realizes the process of stress release due to brittle failure. In order to represent the interaction of uncertainties between ductile fracture and brittle fracture in brittle-to-ductile transition region, we conduct finite element analysis using a cohesive-traction embedded elasto-plastic constitutive law that takes the effects of voids into account in both the yield function of GTN model and exponential type of cohesive zone model. By applying sparse grid to SC method, we calculate the dispersion of fracture toughness values using the Charpy impact test, and verify the validity of proposed method through comparison with experimental results.


# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags:
  #- Ductille-to-brittle transition region
  #- Charpy impact test
  #- Dispersion of fracture toughness
  #- GTN model
  #- Cohesive zone model
  #- Stochastic collocation method

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
#hugoblox:
  #ids:
    #doi: 10.5555/123456

# Custom links
#links:
  #- type: pdf
    #url: ""
  #- type: code
    #url: https://github.com/HugoBlox/kit
  #- type: dataset
    #url: https://github.com/HugoBlox/kit
  #- type: slides
    #url: https://www.slideshare.net/
  #- type: source
    #url: https://github.com/HugoBlox/kit
  #- type: video
    #url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: true

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
slides: ""
---



