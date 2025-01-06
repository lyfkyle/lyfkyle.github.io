---
title: "Ab Initio Particle-based Object Manipulation"
authors:
- Siwei Chen
- Xiao Ma
- admin
- David Hsu
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2021-07-19T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-07-19T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Robotics Science and System 2021*
publication_short: In *RSS 2021*

abstract: This paper presents Particle-based Object Manipulation (Prompt), a new approach to robot manipulation of novel objects ab initio, without prior object models or pre-training on a large object data set. The key element of Prompt is a particle-based object representation, in which each particle represents a point in the object, the local geometric, physical, and other features of the point, and also its relation with other particles. Like the model-based analytic approaches to manipulation, the particle representation enables the robot to reason about the object's geometry and dynamics in order to choose suitable manipulation actions. Like the data-driven approaches, the particle representation is learned online in real-time from visual sensor input, specifically, multi-view RGB images. The particle representation thus connects visual perception with robot control. Prompt combines the benefits of both model-based reasoning and data-driven learning. We show empirically that Prompt successfully handles a variety of everyday objects, some of which are transparent. It handles various manipulation tasks, including grasping, pushing, etc,. Our experiments also show that Prompt outperforms a state-of-the-art data-driven grasping method on the daily objects, even though it does not use any offline training data.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Robotics
  - Manipulation

# Display this page in the Featured widget?
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/abs/2107.08865
url_code: 'https://github.com/AdaCompNUS/Prompt'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=wwabkhh9aAQ'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---