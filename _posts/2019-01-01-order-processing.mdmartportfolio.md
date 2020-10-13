---
title: "AI - Cognitive automation speeds order processing"
date: 2019-12-01
tags: [AI, Computer vision, Deep Learning, Cloud]
header:
  image: "/images/order/header-order.png"
excerpt: "AI, Computer vision, Deep Learning, Cloud"
mathjax: "true"
---

## Decreasing order processes costs through automation

### Goal of the project
International companies have a lot of orders to process coming from different systems and so, in many different formats and many languages. 
Many companies are still wasting precious money and human work hours on manual order entry.
The goal of the project was to develop a tool to automate this order process, meaning to collect key information coming from different orders file formats and in several languages.

### My Role
My concept was to build an API we could request by sending a document. Then document will be process as following: using computer vision in order to split document in different areas of interests, using text recognition, translating text, extracting information and sending the answer.
I designed the cloud architecture and developed the diferent algorithms for the AI engine, except for the text recognition where I used cloud services.

![Alt text]({{ site.url }}{{ site.baseurl }}/images/order/order-ocr.png)

### A POC to increase efficiency through AI
The objective was to show to the teams of this company how AI could be an interesting way to process orders. 
Some other techniques exist today, such as RPA, and it could be interesting to couple RPA and AI to have a better efficiency and scalability.


