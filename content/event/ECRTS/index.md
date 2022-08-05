---
title: Unikernel-Based Real-Time Virtualization under Deferrable Servers: Analysis and Realization

event: 34th Euromicro Conference on Real-Time Systems
event_url: https://www.ecrts.org/

location: Modena, Italy

summary: A technical Talk in ECRTS 2022 about "Unikernel-based real-time virtualization".
abstract: 'For cyber-physical systems, real-time virtualization optimizes the hardware utilization by consolidating multiple systems into the same platform, while satisfying the timing constraints of their real-time tasks. This paper considers virtualization based on unikernels, i.e., single address space
kernels usually constructed by using library operating systems. Each unikernel is a guest operating system in the virtualization and hosts a single real-time task.

We consider deferrable servers in the virtualization platform to schedule the unikernel-based guest operating systems and analyze the worst-case response time of a sporadic real-time task under such a virtualization architecture. Throughout synthesized tasksets, we empirically show that our analysis outperforms the restated analysis derived from the state-of-the-art, which is based on Real-Time Calculus. Furthermore, we provide insights on implementation-specific issues and offer evidence that the proposed scheduling architecture can be effectively implemented on top of the Xen hypervisor while incurring acceptable overhead.'
# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2022-07-05T08:30:00Z'
date_end: '2022-07-08T17:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2022-08-04T00:00:00Z'

authors: []
tags: [Real-Time Systems]

# Is this a featured talk? (true/false)
featured: true

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: 'https://github.com/tu-dortmund-ls12-rt/unikernel-based_deferrable_server_analysis'
url_pdf: 'https://drops.dagstuhl.de/opus/volltexte/2022/16323/pdf/LIPIcs-ECRTS-2022-6.pdf'
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects:
#  - example
---

Further event details can be found in the [offical website](https://www.ecrts.org/).
