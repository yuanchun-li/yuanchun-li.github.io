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

Yuanchun Li a PhD Student in the School of Electronics Engineering and Computer Science (EECS) at Peking University (PKU).
He's research interests lie generally in the fields of ubiquitous computing, security and privacy, and software engineering.
Specifically, he is dedicated to creating software systems that can make our digital world more secure and privacy-friendly.

## Education

|2014.9 - 2019.7(expected)|[Peking University](http://www.pku.edu.cn/)<br>Ph.D Student. Advisors: [Yao Guo](http://sei.pku.edu.cn/~yaoguo/), [Xiangqun Chen](https://www.coursera.org/instructor/chenxiangqun) and [Gang Huang](http://sei.pku.edu.cn/~huanggang/index_en.htm)|
|2016.9 - 2017.9(expected)|[Carnegie Mellon University](http://www.cmu.edu/)<br>Visiting Scholar. Advisors: [Jason Hong](http://www.cs.cmu.edu/~jasonh/) and [Yuvraj Agarwal](http://www.synergylabs.org/yuvraj/)|
|2010.9 - 2014.7|[Peking University](http://www.pku.edu.cn/)<br>Undergraduate Student|

## Featured projects

+ [PrivacyStreams](https://github.com/PrivacyStreams/PrivacyStreams) 
<!-- Place this tag where you want the button to render. -->
<a class="github-button" href="https://github.com/PrivacyStreams/PrivacyStreams" data-show-count="true" aria-label="Star PrivacyStreams/PrivacyStreams on GitHub">Star</a>
    + A framework for privacy-friendly personal data processing.
    It makes it much easier for app developers to access and process personal data.
    As a positive side-effect, it makes the data processing pipeline more transparent.

+ [DroidBot](https://github.com/honeynet/droidbot) 
<!-- Place this tag where you want the button to render. -->
<a class="github-button" href="https://github.com/honeynet/droidbot" data-show-count="true" aria-label="Star honeynet/droidbot on GitHub">Star</a>
    + An automated test input generator in Android mainly used for running dynamic analysis for Android apps.
    
## Publications

- **Yuanchun Li**, Fanglin Chen, Toby Jia-jun Li, Yao Guo, Gang Huang, Matthew Fredrikson, Yuvraj Agarwal, Jason Hong. "PrivacyStreams: Enabling Transparency in Personal Data Processing for Mobile Apps." **UbiComp 2017**. (accepted)

- **Yuanchun Li**, Baoxiong Jia, Yao Guo, Xiangqun Chen. "Mining User Reviews for Mobile App Comparisons." **UbiComp 2017**. (accepted)

- Haoyu Wang, **Yuanchun Li**, Yao Guo, Yuvraj Agarwal, Jason Hong. "Understanding the Purpose of Permission Use in Mobile Apps." ACM Transactions on Information Systems (**TOIS**) (accepted).

- **Yuanchun Li**, Ziyue Yang, Yao Guo and Xiangqun Chen. "DroidBot: A Lightweight UI-Guided Test Input Generator for Android." **ICSE 2017 Demo Track**. Buenos Aires, Argentina, May 2017. [PDF]({{site.baseurl}}/static/files/DroidBot_ICSE2017.pdf)

- Toby Jia-Jun Li, **Yuanchun Li**, Fanglin Chen and Brad A. Myers. "Programming IoT Devices by Demonstration Using Mobile Apps." International Symposium on End User Development (**IS-EUD 2017**). LNCS, vol. 10303. **Best Paper Award.**

- **Yuanchun Li**, Yao Guo and Xiangqun Chen. "PERUIM: Understanding Mobile Application Privacy With Permission-UI Mapping." **UbiComp 2016**, Heidelberg, Germany, September 2016. **Honorable Mention Award.** [PDF]({{site.baseurl}}/static/files/UbiComp2016.pdf)

- **Yuanchun Li**, Yao Guo, Junjun Kong, and Xiangqun Chen. "Fixing sensor-related energy bugs through automated sensing policy instrumentation." 2015 IEEE/ACM International Symposium on Low Power Electronics and Design (**ISLPED 2016**), pp. 321-326. IEEE, 2015. [PDF]({{site.baseurl}}/static/files/ISLPED2015.pdf)

## Honors, Grants and Awards

+ IS-EUD 2017 Best Paper Award
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
