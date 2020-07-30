---
layout: proj
title: Sentencize.jl
date: 2020-07-25
---

A Julia package for splitting text into sentences.

---

[Repository](https://github.com/astariul/Sentencize.jl)
{:.lead}

---

## Project

Since recently I am learning **Julia**, and as exercice I decided to port the [python library `sentence-splitter`](https://github.com/berkmancenter/mediacloud-sentence-splitter) to Julia.

This library is using **regular expressions** and a list of non-breaking prefixes to find the sentences boundaries in a text.

## Experience

The main goal was to familiarize myself with the Julia syntax.

I had to dig deep in the Julia documentation to find how to apply the same regular expressions as in the python package (usage of *Unicode categories*).

Similarly to previous projects, I set up *Github Actions* for **Continuous testing**.
