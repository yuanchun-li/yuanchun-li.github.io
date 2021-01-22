---
title: 'Past projects'
date: 2016-11-10
permalink: /posts/past_projects/
tags:
  - research
  - deprecated
---


+ [HybridFlow](https://github.com/ylimit/HybridFlow) - 
Many modern Android apps are hybrid, for example developed with multiple languages (Java + HTML for instance),
which makes existing static analysis tools fail to produce correct result.
HybridFlow is a static analysis tool targeting such complex hybrid apps.
    
    Researchers in KAIST and IBM did the similar thing and their paper was published in ASE 2016. 
    [Read their paper](http://dl.acm.org/citation.cfm?id=2970368).
    
+ [DeDroid](https://github.com/ylimit/DeDroid) - 
Many Android apps are minified by obfuscation tools like ProGuard and DexGuard,
for example replacing meaningful identifiers into short meaningless symbols,
which makes it difficult to understand the code directly.
DeDroid aims to recover the minified identifiers using machine learning.
    
    Researchers in ETH Zurich did the similar thing and their paper was published in CCS 2016.
    [Read their paper](www.srl.inf.ethz.ch/papers/deguard.pdf) or [Try their demo](http://apk-deguard.com/).

+ Mobile Sensing Optimization - 
Using app instrumentation techniques to rewrite Android sensing apps in order to save their battery life.
The idea is simple: changing sampling frequency based on context,
for example slowing down sample frequency of accelerometer when the user is not moving.

    This work was published in ISLPED 2015.
