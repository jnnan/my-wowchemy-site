---
title: 'A-HOI: Articulated Human-Object Interaction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Tengyu Liu
  - Zhexuan Cao
  - Jieming Cui
  - Yixin Chen
  - He Wang
  - Yixin Zhu
  - Siyuan Huang

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

abstract: Fine-grained capturing of 3D Human-Object Interactions (HOIs) boosts human activity understanding and facilitates downstream visual tasks, including action recognition, holistic scene reconstruction, and human motion synthesis. Despite its significance, most existing works assume that humans interact with rigid ob jects, limiting their scope. In this paper, we address the challenging problem of Articulated Human-Object Interaction (A-HOI), wherein whole human bod7 ies interact with articulated objects, whose parts are connected by prismatic or revolute joints. We present Capturing Human and Articulated-object InteRac9 tionS (CHAIRS), a large-scale motion-captured A-HOI dataset, consisting of 16.2 hours of versatile interactions between 46 participants and 74 rigid and articulated sittable objects. CHAIRS provides 3D meshes of both humans and articulated objects during the entire interactive process, as well as the realistic and physically plausible part-level interactions. We show the value of CHAIRS with a new chal lenging task: Kinematic-Agnostic Human and Object Pose Estimation (KA-HOPE). Leveraging the interactions between human and object parts, we devise the very first model to tackle the joint estimation of human and object poses during interac tions, which significantly outperforms the baseline models and shows improved generalizability across kinematic structures. We hope CHAIRS will promote the community toward more fine-grained interaction understanding between humans and 3D scenes.

# Summary. An optional shortened abstract.
summary: We present CHAIRS, a large-scale multi-view RGB-D dataset with diverse and high-quality 3D meshes of human and articulated objects. (ii) We design a new task of KA-HOPE, agnostic to variations in object kinematics.

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
