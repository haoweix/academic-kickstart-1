---
title: "SPECT/CT scatter estimation using a deep
convolutional neural network: implementation in
Y-90 imaging"
authors:
- admin
- Hongki Lim
- Jeffrey A. Fessler
- Yuni K. Dewaraja
date: "2020-02-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE NSS/MIC*
publication_short: In *NSS/MIC*

abstract: Monte Carlo (MC) based scatter modeling in Y-90 bremsstrahlung SPECT has demonstrated improved image quality and quantitative accuracy, but at the expense of computational complexity. We present a deep learning approach for SPECT/CT scatter estimation that substantially reduces the computation time. Once trained, our deep Convolutional Neural Network (CNN) takes the projections from the SPECT camera and CT-based attenuation map as input and outputs the scatter projections. MC simulated digital phantom data, where true scatter is known, is used during the training process and the network is trained to match the MC scatter estimation. For our network, Adam is used as optimizer, the learning rate is 1e-4, the mean square error is used as loss, the batch size is 32, and we train this CNN with 100 epochs. In testing with a hot sphere phantom simulation and a liver phantom measurement, visual image quality and contrast recovery was similar with the CNN and MC scatter estimation methods, but the CNN scatter estimate was generated in a fraction of the time needed for the MC scatter estimation ( about 1 min for CNN vs 1-2 hours for MC). The short processing time with CNN while maintaining accuracy has high clinical significance for quantitative Y-90 SPECT imaging.

# Summary. An optional shortened abstract.
summary: Monte Carlo (MC) based scatter modeling in Y-90 bremsstrahlung SPECT has demonstrated improved image quality and quantitative accuracy, but at the expense of computational complexity. We present a deep learning approach for SPECT/CT scatter estimation that substantially reduces the computation time. Once trained, our deep Convolutional Neural Network (CNN) takes the projections from the SPECT camera and CT-based attenuation map as input and outputs the scatter projections.

tags:
- scatter estimation
featured: true

links:
- name: Custom Link
  url: http://example.org
url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
url_code: '#'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: '[**System Diagram**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---





