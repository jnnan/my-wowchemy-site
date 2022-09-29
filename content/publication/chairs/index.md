---
title: 'UAV navigation in high dynamic environments: A deep reinforcement learning approach'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Tong Guo
  - admin
  - Biyue Li
  - Xi Zhu
  - Ya Wang
  - Wenbo Du

# Author notes (optional)
author_notes: ""

date: '2020-06-27T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-06-27T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Chinese Journal of Aeronautics*
publication_short: ""

abstract: Unmanned Aerial Vehicle (UAV) navigation is aimed at guiding a UAV to the desired destinations along a collision-free and efficient path without human interventions, and it plays a crucial role in autonomous missions in harsh environments. The recently emerging Deep Reinforcement Learning (DRL) methods have shown promise for addressing the UAV navigation problem, but most of these methods cannot converge due to the massive amounts of interactive data when a UAV is navigating in high dynamic environments, where there are numerous obstacles moving fast. In this work, we propose an improved DRL-based method to tackle these fundamental limitations. To be specific, we develop a distributed DRL framework to decompose the UAV navigation task into two simpler sub-tasks, each of which is solved through the designed Long Short-Term Memory (LSTM) based DRL network by using only part of the interactive data. Furthermore, a clipped DRL loss function is proposed to closely stack the two sub-solutions into one integral for the UAV navigation problem. Extensive simulation results are provided to corroborate the superiority of the proposed method in terms of the convergence and effectiveness compared with those of the state-of-the-art DRL methods.

# Summary. An optional shortened abstract.
summary: In this work, we propose an improved DRL-based UAV navigation method to tackle the problem of convergencen when a UAV is navigating in high dynamic environments.

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
