---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Scotland Yard Ai"
summary: "Implemented Dijkstra’s shortest path finding algorithm and Design patterns for AI playing board game Scotland Yard"
authors: []
tags: []
categories: []
date: 2019-05-31T00:00:00Z

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Our coursework is to implement the logic and develop an AI to play the board game “Scotland Yard”, a game in which a team of players, as detectives must cooperate and track down a criminal around a board representing streets of London. The objective of our AI is to play as the criminal. We have agreed upon a greedy algorithm approach, to focus primarily on getting as far away from the other detectives. We also have an efficient division of labour.  My role is to implement Dijkstra’s path-finding algorithm, to score the distance between possible moves with the locations of other detectives. Meanwhile, my other coursemate worked on other factors of the scoring function.

Besides, we have familiarized ourselves with several design patterns. By using the visitor pattern, we can score different types of moves (could be a single move, double move, or even hidden moves on the board) with different mechanism without changing the source code of the classes. Other patterns such as strategy and iterator pattern have also been used.

Our AI had come third when being competed with humans. I am grateful for the accomplishment we have achieved, and how our knowledge and skills complement each other. Finally, I have learnt to be humble and supportive teammate throughout this collaborative experience.