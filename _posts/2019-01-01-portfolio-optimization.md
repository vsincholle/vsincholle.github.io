---
title: "AI - Portfolio optimization for F&B industry"
date: 2019-01-01
tags: [AI, Machine Learning, Customer experience, Cloud]
header:
  image: "/images/portfolio/Food-Beverage-Banner.jpg"
excerpt: "AI, Machine Learning, Customer experience, Cloud"
mathjax: "true"
---

## Ingredients portfolio rationalization

### Goal of the project
In general, an optimized portfolio of assets must generate the highest possible return and at the same time not exceed a specified risk for a given investment horizon. Of course when we talk about food products portfolio, logic is globally the same one but with some differences. In F&B industry, you could manage thousands of ingredients because each of your customer want a unique product with specific attributes such as taste, colour, viscosity, organic ingredients, etc. and of course business is changing and evolving rapidtly because customers needs do. Portfolio optimization for F&B industry is more about portoflio rationalization: how to streamline the existing application portfolio with an explicit goal of improving efficiency, reducing complexity, standardizing the technology platform, eliminating redundant ingredients,etc. The goal of project was to optimize the ingredients portfolio in that way without having any impact for the customer, the company needs to produce products with the same quality and keeping the same attributes (such as taste, colour, organic, etc.)

### My Role
In order to do that, the concept was to define the profile of an ingredient. Of course this a multi-dimensional profile, and it includes a sensory profile (define by sensory experts), an attributes profile (organic, kosher, halal, etc.) and an economic profile. Based on these profiles, we created an euclidian distance matrix between each product to start clustering. Initial algorithm was written in R by a datascientist. My work was to validate the mathematical model and to optimize it. I coded the model into Python and I used parallelisation techniques. Then I designed some data visualizations and I created all the Cloud infrastructure to deploy the overall model.

![Alt text]({{ site.url }}{{ site.baseurl }}/images/portfolio/tasting-session.jpg)

### A tasty tool for the existing portfolio
Our solution gave nice results and I had the opportunity to test it in real by doing a tasting session, comparing several products based on ingredients given by the model. Very appreciated for the amateur cooking I am :)
