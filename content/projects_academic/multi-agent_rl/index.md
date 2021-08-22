---
title: Multi-Agent Deep Reinforcment Learning
summary: Multi-agent implementation of the popular Reinforcement Learning algorithms.
subtitle: Multi-agent implementation of the popular Reinforcement Learning algorithms.

tags:
- Deep Learning
- Reinforcement Learning
- Multi Agent
- Pursuit Evasion

date: "2019-08-31T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Reinforcement Learning
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: Project Code
  url: https://github.com/dhavalsalwala/rl-algos/tree/master/rltechniques/multi_agent

url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:
---

<p style='text-align: justify;'>
Pursuit is a standard task for benchmarking multi-agent algorithms. The pursuit-evasion domain consists of two sets of agents: evaders and pursuers. The evaders are trying to avoid pursuers, while the pursuers are trying to catch the evaders. The action and observation spaces in this problem are discrete. The agents interact on a two-dimensional grid, and an evader is considered caught if it is surrounded by pursuers on four sides. In order to catch the evaders, the pursuers must learn to cooperate by trapping the evaders on all sides. When the pursuers catch an evader, they receive a reward. The evaders follow a uniform random policy. The domain contains obstacles through which the agents cannot pass. Each pursuer receives a range-limited observation of its surroundings, and must choose between five actions Stay, Go East, Go West, Go South, Go North. The observations contain information about the agent’s surroundings, including the location of nearby pursuers, evaders, and obstacles.
</p>

