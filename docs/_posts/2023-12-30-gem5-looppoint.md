---
layout: post
author: Alen
title:  "LoopPoint with gem5"
published: true
hidden: true
excerpt_separator: <!--more-->
tags: [gem5, sampling, simulation]
image: /img/gem5logolong.gif
hero_height: is-fullwidth
summary: |-
    The gem5 simulator now supports LoopPoint methodology for the sampled simulation and checkpointing of multi-threaded workloads.
---

The gem5 simulator now supports the LoopPoint methodology for the sampled simulation of multi-threaded workloads.
Checkout the [script](https://github.com/gem5/gem5/blob/stable/src/python/gem5/resources/looppoint.py) and Zhantong's [talk](https://www.gem5.org/assets/files/workshop-isca-2023/slides/looppoint-in-the-gem5-simulator.pdf) at the [gem5 workshop](https://www.gem5.org/events/isca-2023) to know more.

We have also released the representative ELFies of a subset of the multi-threaded SPEC CPU2017 benchmarks [here](https://looppoint.github.io/hpca2023/). You will be able to simulate them on gem5 and Sniper using the corresponding config files.
