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
    <p class="margin-small"><a href="http://eecs.pku.edu.cn/">School of Electronics Engineering and Computer Science</a></p>
    <p class="margin-small"><a href="http://www.pku.edu.cn/">Peking University</a></p>
    <p>yuanchun.li [AT] pku [dot] edu [dot] cn</p>
  </td>

</tr>
</tbody>
</table>

I'm a PhD Student in the School of Electronics Engineering and Computer Science (EECS) at Peking University (PKU).
My current research interests include
[mobile computing](https://en.wikipedia.org/wiki/Mobile_computing),
[mobile security](https://en.wikipedia.org/wiki/Mobile_security) and
[program analysis](https://en.wikipedia.org/wiki/Program_analysis).

## Education

|2016.9 - 2017.9(expected)|[Carnegie Mellon University](http://www.cmu.edu/)<br>Visiting Scholar. Advisors: [Jason Hong](http://www.cs.cmu.edu/~jasonh/) and [Yuvraj Agarwal](http://www.synergylabs.org/yuvraj/)|
|2014.9 - 2019.7(expected)|[Peking University](http://www.pku.edu.cn/)<br>Ph.D Student. Advisors: [Yao Guo](http://sei.pku.edu.cn/~yaoguo/), [Xiangqun Chen](https://www.coursera.org/instructor/chenxiangqun) and [Gang Huang](http://sei.pku.edu.cn/~huanggang/index_en.htm)|
|2010.9 - 2014.7|[Peking University](http://www.pku.edu.cn/)<br>Undergraduate Student|

## Current research

+ **Privacy-aware Programming**
    + [PrivacyStreams](https://privacystreams.github.io) is a framework for privacy-friendly personal data processing.
    It makes it much easier for Android app developers to access and process personal data.
    As a positive side-effect, it makes the data processing pipeline more transparent.

+ **Privacy-aware UI for users**
    + [PERUIM](https://github.com/ylimit/uiAnalysis) is aimed to help Android app users understand permissions in UI level.
    Why UI level? Because on one hand UI is easy for users to understand, and on the other hand UI is related to app's actual behavior (code).
    For example, users want to grant `LOCATION` permission to a weather widget rather than an advertisement view.

+ **App Market Intelligence**
    + [Comparative Review Analysis](https://github.com/ylimit/app-review-search)
    In this project, we mine competitive relations between apps from large-scale app store reviews.
    The comparative relations can help users find better apps and help developers improve their apps.

+ **Static Analysis and Dynamic Analysis**
    + [DroidBot](https://github.com/ylimit/droidbot) - An automated test input generation tool in Android mainly used for malware detection.
    This work is under the support of [the Honeynet Project](http://honeynet.org/node/1317) and [Google Summer of Code](https://developers.google.com/open-source/gsoc/).
    
## Publications

- Haoyu Wang, **Yuanchun Li**, Yao Guo, Yuvraj Agarwal, Jason Hong. "Understanding the Purpose of Permission Use in Mobile Apps." ACM Transactions on Information Systems (**TOIS**) (accepted).

- **Yuanchun Li**, Ziyue Yang, Yao Guo and Xiangqun Chen. "DroidBot: A Lightweight UI-Guided Test Input Generator for Android." **ICSE 2017 Demo Track**. Buenos Aires, Argentina, May 2017. [PDF]({{site.baseurl}}/static/files/DroidBot_ICSE2017.pdf)

- Toby Jia-Jun Li, **Yuanchun Li**, Fanglin Chen and Brad A. Myers. "Programming IoT Devices by Demonstration Using Mobile Apps." To appear in Proceedings of the International Symposium on EndUser Development (**IS-EUD 2017**).

- **Yuanchun Li**, Yao Guo and Xiangqun Chen. "PERUIM: Understanding Mobile Application Privacy With Permission-UI Mapping." **UbiComp 2016**, Heidelberg, Germany, September 2016. **Honorable Mention Award!** [PDF]({{site.baseurl}}/static/files/UbiComp2016.pdf)

- **Yuanchun Li**, Yao Guo, Junjun Kong, and Xiangqun Chen. "Fixing sensor-related energy bugs through automated sensing policy instrumentation." 2015 IEEE/ACM International Symposium on Low Power Electronics and Design (**ISLPED 2016**), pp. 321-326. IEEE, 2015. [PDF]({{site.baseurl}}/static/files/ISLPED2015.pdf)

## Honors, Grants and Awards

+ 2016 Bosch/Bezirk Internet of Things Hackathon - 1st place ($1000)
+ UbiComp 2016 Best Paper Honorable Mention Award
+ Google Summer of Code 2016 ($5500)
+ Merit Student at Peking University 2016
+ Google Summer of Code 2015 ($5500)

## Teaching

* Operating System Labs (Honor track). TA
    * Fall 2014, Spring 2015, Fall 2015
* Compiler Techniques. TA
    * Spring 2015
* Introduction to Computer System. TA
    * Fall 2013, Fall 2014

## Others

{% for post in site.posts %}
+ [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) {{ post.date | date_to_string }}
{% endfor %}
