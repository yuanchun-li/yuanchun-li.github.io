---
layout: homepage
title: Yuanchun Li @ Peking University
---

<table style="border-style:none">
<tbody style="border-style:hidden">
<tr>
  <td><img width="256px" src="{{site.baseurl}}/static/figure/avatar_201603.jpg"></td>
  <td>
    <h1>Yuanchun Li (李元春)</h1>
    <p>PhD student</p>
    <p class="margin-small"><a href="http://www.sei.pku.edu.cn/">Software Engineering Institute</a></p>
    <p class="margin-small"><a href="http://eecs.pku.edu.cn/">School of Electronics Engineering and Computer Science</a></p>
    <p class="margin-small"><a href="http://www.pku.edu.cn/">Peking University</a></p>
    <p>Email: yli AT pku.edu.cn</p>
  </td>

</tr>
</tbody>
</table>

I'm a PhD Student in the Institute of Software of the School of Electronics Engineering and Computer Science (EECS) at Peking University.
My current research interests include
[mobile computing](https://en.wikipedia.org/wiki/Mobile_computing),
[mobile security](https://en.wikipedia.org/wiki/Mobile_security) and
[program analysis](https://en.wikipedia.org/wiki/Program_analysis).

## Education

|2016.9 - 2017.9(expected)|[Carnegie Mellon University](http://www.cmu.edu/)<br>Visiting Scholar. Advisors: [Jason Hong](http://www.cs.cmu.edu/~jasonh/) and [Yuvraj Agarwal](http://www.synergylabs.org/yuvraj/)|
|2014.9 - 2019.7(expected)|[Peking University](http://www.pku.edu.cn/)<br>Ph.D Student. Advisors: [Yao Guo](http://sei.pku.edu.cn/~yaoguo/), [Xiangqun Chen](https://www.coursera.org/instructor/chenxiangqun) and [Gang Huang](http://sei.pku.edu.cn/~huanggang/index_en.htm)|
|2010.9 - 2014.7|[Peking University](http://www.pku.edu.cn/)<br>Undergraduate Student|

## Current research projects

+ [DroidBot](https://github.com/ylimit/droidbot).
    + DroidBot is an automated test input generation tool in Android, mainly used for malware detection.
    This work was [reported by Honeynet](http://honeynet.org/node/1317) and
    presented as a poster at Honeynet workshop ([HNW2016](https://sanantonio2016.honeynet.org/)).
    This is an open source project and welcome to contribute!

+ [HybridFlow](https://github.com/ylimit/HybridFlow)
    + Many modern Android apps are hybrid, for example developed with multiple languages (Java + HTML for instance),
    which makes existing static analysis tools fail to produce correct result.
    HybridFlow is a static analysis tool targeting such complex hybrid apps.

+ [DeDroid](https://github.com/ylimit/DeDroid)
    + Many Android apps are minified by obfuscation tools like ProGuard and DexGuard,
    for example replacing meaningful identifiers into short meaningless symbols,
    which makes it difficult to understand the code directly.
    DeDroid aims to recover the minified identifiers using machine learning.

+ [PERUIM](https://github.com/ylimit/uiAnalysis)
    + PERUIM helps user understand and control permissions in UI level.
    Why UI level? Users understand UI components and know which permissions should be granted to certain UI components.
    For example, users want to grant `LOCATION` permission to a weather widget rather than an advertisement view.
    This work is published in [UbiComp2016](http://ubicomp.org/ubicomp2016/program/program.php).

+ [ReviewIntelligence](https://github.com/ylimit/app-review-search)
    + ReviewIntelligence mines comparative relations between apps from large-scale app store reviews.
    The comparative relations can help users find better apps and help developers improve their apps.

## Past projects

+ Fixing sensor-related energy bugs through automated sensing policy instrumentation. [ISLPED15]

## Publications

|[UbiComp2016]|**Yuanchun Li**, Yao Guo and Xiangqun Chen. "PERUIM: Understanding Mobile Application Privacy With Permission-UI Mapping" UbiComp 2016, Heidelberg, Germany, September 2016. **Honorable Mention Award!**|[PDF]({{site.baseurl}}/static/files/UbiComp2016.pdf)|
|[HNW2016]|**Yuanchun Li**, Hanno Lemoine and Hugo Gascon. "Improving Dynamic Analysis Coverage in Android with DroidBot." The Honeynet Project Annual Workshop 2016 (HNW2016)(**POSTER**)|[PDF]({{site.baseurl}}/static/files/HNW2016.pdf)|
|[ISLPED2015]|**Yuanchun Li**, Yao Guo, Junjun Kong, and Xiangqun Chen. "Fixing sensor-related energy bugs through automated sensing policy instrumentation." 2015 IEEE/ACM International Symposium on Low Power Electronics and Design (ISLPED), pp. 321-326. IEEE, 2015.|[PDF]({{site.baseurl}}/static/files/ISLPED2015.pdf)|

## Awards

+ UbiComp 2016 Honorable Mention Award

## Teaching

* Operating System Labs (Honor track). TA
    * Fall 2014, Spring 2015, Fall 2015
* Compiler Techniques. TA
    * Spring 2015
* Introduction to Computer System. TA
    * Fall 2013, Fall 2014

## List of Posts

I'm interested in painting and writing, and here are some of my works.

{% for post in site.posts %}
+ [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) {{ post.date | date_to_string }}
{% endfor %}