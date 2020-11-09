---
title: "A Case Study of Deep Reinforcement Learning for Engineering Design: Application to Microfluidic Devices for Flow Sculpting"
authors:
- admin
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2015-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Mechanical Design"
publication_short: ""

abstract: Efficient exploration of design spaces is highly sought after in engineering applications. A spectrum of tools has been proposed to deal with the computational difficulties associated with such problems. In the context of our case study, these tools can be broadly classified into optimization and supervised learning approaches. Optimization approaches, while successful, are inherently data inefficient, with evolutionary optimization-based methods being a good example. This inefficiency stems from data not being reused from previous design explorations. Alternately, supervised learning-based design paradigms are data efficient. However, the quality of ensuing solutions depends heavily on the quality of data available. Furthermore, it is difficult to incorporate physics models and domain knowledge aspects of design exploration into pure-learning-based methods. In this work, we formulate a reinforcement learning (RL)-based design framework that mitigates disadvantages of both approaches. Our framework simultaneously finds solutions that are more efficient compared with supervised learning approaches while using data more efficiently compared with genetic algorithm (GA)-based optimization approaches. We illustrate our framework on a problem of microfluidic device design for flow sculpting, and our results show that a single generic RL agent is capable of exploring the solution space to achieve multiple design objectives. Additionally, we demonstrate that the RL agent can be used to solve more complex problems using a targeted refinement step. Thus, we address the data efficiency limitation of optimization-based methods and the limited data problem of supervised learning-based methods. The versatility of our framework is illustrated by utilizing it to gain domain insights and to incorporate domain knowledge. We envision such RL frameworks to have an impact on design science.


# Summary. An optional shortened abstract.
summary: This work demonstrates how a sequential engineering design problem of designing a microfluidic device can be formulated and solved using conventional deep reinforcement learning algorithms. We show that to leverage conventional off-the-shelf RL algorithms, proper engineering of the environment is crucial, particularly the state and reward representations. Furthermore, popular techniques such as hindsight experience replay and transfer learning can also be employed to improve the data efficiency and generalizability of the RL design policy. Results from this study showed that combinatorically large design spaces, which typically arise in engineering design, can be intelligently explore and exploited using reinforcement learning approaches.

tags:
- Source Themes
featured: false

# links:
# url_pdf: ''
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
url_source: 'https://asmedigitalcollection.asme.org/mechanicaldesign/article-abstract/141/11/111401/956254/A-Case-Study-of-Deep-Reinforcement-Learning-for?redirectedFrom=fulltext'
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
slides: ""
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
