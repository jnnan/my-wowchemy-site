---
title: 'ADS-B Message Authentication Using Features of Signal in Transition Regions'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Shutong Qi
  - Feixiang Luo
  - Jun Wang
  - Wenfeng Wang

# Author notes (optional)
author_notes: ""

date: '2019-12-27T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2019-12-27T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Signal, Information and Data Processing*
publication_short: "ICSIDP"

abstract: Automatic Dependent Surveillance - Broadcast (ADS-B) is an essential communication protocol used in modern air traffic control. However, lacking security measures such as authentication and encryption, ADS-B messages can be forged and modified easily by malicious attackers. This paper addresses the problem of authenticating an ADS-B message by means of specific emitter identification (SEI), employing the unintentional modulation on pulse (UMOP). A complete identification system is presented, including data acquisition, feature extraction and classification. In order to create the feature vector for classification, the transition region in a pulse is first delimited and then used for extraction of UMOP features through Hilbert-Huang Transform. The performance of the method is tested by real signal from 30 ADS-B transmitters. Our proposed method is shown to achieve an recognition ratio of over 94 %, and performs better under low SNR compared with two previous techniques. It is demonstrated that the SEI technique proposed can be used as an additional tool to enhance the security of ADS-B protocol.

# Summary. An optional shortened abstract.
summary: This paper addresses the problem of authenticating an ADS-B message by means of specific emitter identification (SEI), employing the unintentional modulation on pulse (UMOP).

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - ""

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
