---
title: "Neural Randomized Planning for Whole Body Robot Motion"
authors:
- admin
- Yuchen Ma
- David Hsu
- Panpan Cai
date: "2024-05-18T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-05-18T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Robot motion planning has made vast advances over the past decades, but the challenge remains, robot mobile manipulators struggle to plan long-range whole-body motion in common household environments in real time, because of high-dimensional robot configuration space and complex environment geometry. To tackle the challenge, this paper proposes Neural Randomized Planner (NRP), which combines a global sampling-based motion planning (SBMP) algorithm and a local neural sampler. Intuitively, NRP uses the search structure inside the global planner to stitch together learned local sampling distributions to form a global sampling distribution adaptively. It benefits from both learning and planning. Locally, it tackles high dimensionality by learning to sample in promising regions from data, with a rich neural network representation. Globally, it composes the local sampling distributions through planning and exploits local geometric similarity to scale up to complex environments. Experiments both in simulation and on a real robot show \NRP yields superior performance compared to some of the best classical and learning-enhanced SBMP algorithms. Further, despite being trained in simulation, NRP demonstrates zero-shot transfer to a real robot operating in novel household environments, without any fine-tuning or manual adaptation.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Robotics
  - Motion Planning
  - Whole-body Manipulation

featured: true

links:
url_pdf: https://arxiv.org/abs/2405.11317
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=edA8QFGHJt4&list=PLKXStPcSzMYOlLd0TGNZKoYKbWou1xPFS&index=8'

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
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
