---
title: '延性-脆性遷移挙動を表現するための結合力埋込型構成則'

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

date: '2026-06-02T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-04-04T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 計算工学講演会講演論文集
publication_short: 第31回計算工学講演会講演論文集

abstract: The contribution of this study is to propose a cohesive-embedded constitutive law combining a cohesive zone model and an enhanced Rousselier model to accurately simulate fracture behavior in the ductile-to-brittle transition (DBT) region. At low temperature, brittle fracture occurs with little plastic deformation due to the increase in yield strength and reduced fracture toughness. The process of stress release due to the crack propagation is realized by a local equilibrium state between principal stresses and cohesive tractions. At room temperature, ductile fracture caused by void nucleation, growth, and coalescence is represented by the enhanced Rousselier model as a shrinkage of the yield surface. Furthermore, at DBT temperature, initial ductile tearing transits to brittle fracture because void growth reduces the effective cross-sectional area of a specimen, thereby degrading fracture toughness. Our proposed law represents DBT behavior by incorporating the void volume fraction into the critical energy release rate defined in the cohesive zone model. Additionally, temperature-dependent plastic hardening behavior is approximated by Voce hardening law which depends on temperature. The capability of our proposed constitutive law is demonstrated by comparison with experimental results of compact tension specimens at low, room, and DBT temperatures.



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
