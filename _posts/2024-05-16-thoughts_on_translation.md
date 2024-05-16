---
title: Thoughts on Translation
date: 2024-05-16 12:00:00 +0900
categories: [NLP, MT]
tags: [MT]
---

I've done various types of translation work and noticed that document translation, real-time interpretation, and movie translation each have different requirements, leading to varied outputs. For example, document translations aim to retain as much detail as possible, while real-time interpretation focuses on conveying the essence of what has been spoken. Movie translations fall somewhere in between; while details are necessary for understanding the movie, there is limit in time and space to show the subtitles and you don't want viewers to spend most of their time reading instead of watching because they're too verbose. In fact, it is actually recommended that translators remove, reorder, or rephrase sentences as necessary to achieve this balance. The difference in translation approaches may result in discrepancies that may confuse the models during training or render models trained for a specific type of translation less effective for others. I have to note that in some cases, the briefness of interpretations may be a limitation of the interpreter rather than a requirement (humans have a rather short attention span - or context window if you will).