---
layout: homepage
title: Yuanchun Li @ Peking University
---

<table style="border-style:none">
<tbody style="border-style:hidden">
<tr>
  <td><img width="256px" src="{{site.baseurl}}/static/figure/avatar_201603.jpg"></td>
  <td>
    <h2>Yuanchun Li 李元春</h2>
    <p>PhD Student</p>
    <p>Institute of Software, School of EECS, Peking University</p>
    <p>yuanchun.li [AT] pku [dot] edu [dot] cn</p>
  </td>

</tr>
</tbody>
</table>

I'm a Ph.D student in the Institute of Software at Peking University, advised by 
[Yao Guo](http://sei.pku.edu.cn/~yaoguo/),
[Xiangqun Chen](https://www.coursera.org/instructor/chenxiangqun)
and [Gang Huang](http://sei.pku.edu.cn/~huanggang/index_en.htm).
I was also advised by [Jason Hong](http://www.cs.cmu.edu/~jasonh/) and [Yuvraj Agarwal](http://www.synergylabs.org/yuvraj/)
when I was a visiting student in the Human-Computer Interaction Institute at Carnegie Mellon University.
My research interests lie in the fields of mobile computing, security and privacy, and software engineering.

    
## Publications

- **Yuanchun Li**, Fanglin Chen, Toby Jia-jun Li, Yao Guo, Gang Huang, Matthew Fredrikson, Yuvraj Agarwal, Jason I. Hong. "PrivacyStreams: Enabling Transparency in Personal Data Processing for Mobile Apps." IMWUT aka. UbiComp 2017. [[PDF]]({{site.baseurl}}/static/files/UbiComp2017_PrivacyStreams.pdf)

    [![UbiComp2017](https://img.shields.io/badge/UbiComp-2017-brightgreen.svg)](http://ubicomp.org/ubicomp2017/) <a class="github-button" href="https://github.com/PrivacyStreams/PrivacyStreams" data-show-count="true" aria-label="Star PrivacyStreams/PrivacyStreams on GitHub">Star</a>

- **Yuanchun Li**, Baoxiong Jia, Yao Guo, Xiangqun Chen. "Mining User Reviews for Mobile App Comparisons." UbiComp 2017. IMWUT aka. UbiComp 2017. [[PDF]]({{site.baseurl}}/static/files/UbiComp2017_mining-user-reviews.pdf)

    [![UbiComp2017](https://img.shields.io/badge/UbiComp-2017-brightgreen.svg)](http://ubicomp.org/ubicomp2017/)

- Haoyu Wang, **Yuanchun Li**, Yao Guo, Yuvraj Agarwal, Jason I. Hong. "Understanding the Purpose of Permission Use in Mobile Apps." ACM Transactions on Information Systems (TOIS).

    [![TOIS2017](https://img.shields.io/badge/TOIS-2017-brightgreen.svg)](http://tois.acm.org/)

- **Yuanchun Li**, Ziyue Yang, Yao Guo and Xiangqun Chen. "DroidBot: A Lightweight UI-Guided Test Input Generator for Android." ICSE 2017 Demo Track. Buenos Aires, Argentina, May 2017. [[PDF]]({{site.baseurl}}/static/files/DroidBot_ICSE2017.pdf)

    [![ICSE-C2017](https://img.shields.io/badge/ICSE--C-2017-brightgreen.svg)](http://icse2017.gatech.edu/) <a class="github-button" href="https://github.com/honeynet/droidbot" data-show-count="true" aria-label="Star honeynet/droidbot on GitHub">Star</a>

- Toby Jia-Jun Li, **Yuanchun Li**, Fanglin Chen and Brad A. Myers. "Programming IoT Devices by Demonstration Using Mobile Apps." International Symposium on End User Development (IS-EUD 2017).

    [![IS-EUD2017](https://img.shields.io/badge/IS--EUD-2017-brightgreen.svg)](http://iseud2017.tue.nl/) [![Best Paper Award](https://img.shields.io/badge/Award-Best%20Paper-orange.svg)]()

- **Yuanchun Li**, Yao Guo and Xiangqun Chen. "PERUIM: Understanding Mobile Application Privacy With Permission-UI Mapping." UbiComp 2016, Heidelberg, Germany, September 2016. [[PDF]]({{site.baseurl}}/static/files/UbiComp2016.pdf)

    [![UbiComp2016](https://img.shields.io/badge/UbiComp-2016-brightgreen.svg)](http://ubicomp.org/ubicomp2016/) [![Honorable Mention Award](https://img.shields.io/badge/Award-Honorable%20Mention-orange.svg)]()

- **Yuanchun Li**, Yao Guo, Junjun Kong, and Xiangqun Chen. "Fixing sensor-related energy bugs through automated sensing policy instrumentation." 2015 IEEE/ACM International Symposium on Low Power Electronics and Design (ISLPED 2016), pp. 321-326. IEEE, 2015. [[PDF]]({{site.baseurl}}/static/files/ISLPED2015.pdf)

    [![ISLPED2015](https://img.shields.io/badge/ISLPED-2015-brightgreen.svg)](http://islped.org/2015/)

## Honors, Grants and Awards

+ IS-EUD 2017 Best Paper Award
+ 2016 Bosch/Bezirk Internet of Things Hackathon - 1st place ($1000)
+ UbiComp 2016 Best Paper Honorable Mention Award
+ Google Summer of Code 2016 ($5500)
+ Merit Student at Peking University 2016
+ Google Summer of Code 2015 ($5500)

## Teaching

* Operating System Labs (Honor track). TA
    * Fall 2014, Spring 2015, Fall 2015, Spring 2016
* Compiler Techniques. TA
    * Spring 2015
* Introduction to Computer System. TA
    * Fall 2013, Fall 2014

## Others

{% for post in site.posts %}
+ [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) {{ post.date | date_to_string }}
{% endfor %}
