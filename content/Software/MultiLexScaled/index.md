---
author: Maurits van der Veen
categories:
- text preprocessing
- sentiment analysis
date: "2021-12-10"
draft: false
excerpt: "**High-quality dictionary-based sentiment analysis**\n\n

Sentiment analysis (the measurement of the positivity or negativity of texts) is one of the most widely used tools in computational text analysis. MultiLexScaled is a sentiment analysis tool that can be applied off-the-shelf, has been proven to work well across a range of domains, and obtains performance comparable to dedicated machine learning applications."
layout: single
links:
- icon: github
  icon_pack: fab
  name: "Github repository"
  url: https://github.com/amaurits/MultiLexScaled
subtitle: High-performance dictionary-based sentiment analysis
title: MultiLexScaled
---

#### Lexicon-based sentiment analysis, using multiple lexica and scaled against representative text corpora.

Easy-to-use, high-quality sentiment analysis. Instead of trying to develop yet another general-purpose sentiment analysis lexicon, we average across 8 widely-used ones that have different strengths and weaknesses. In addition, we calibrate against a set of representative texts and adjust each individual lexicon's score so that its mean is 0 (the neutral point) and the standard deviation is 1. We rescale the final average so that its standard deviation is 1 as well, to produce a sentiment measure that is readily interpretable (relative to the benchmark used for scaling). MultiLexScaled outperforms other widely-used sentiment analysis dictionaries on a range of different test sets.

The Github repository contains all the code and notebooks needed to apply MultiLexScaled to a corpus of texts, along with a paper explaining the method in more detail.
