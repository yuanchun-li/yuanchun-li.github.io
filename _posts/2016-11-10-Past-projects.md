---
title: 'Some interesting open-source projects that I worked on before'
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

