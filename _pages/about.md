---
permalink: /
title: ""
excerpt: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Research Assistant Professor at the [Institute for AI Industry Research (AIR)](http://air.tsinghua.edu.cn/), [Tsinghua University](https://www.tsinghua.edu.cn/en/index.htm). I received a Ph.D. degree and a Bachelor's degree in Computer Science, both from [Peking University](https://cs.pku.edu.cn/English/Home.htm). I had also worked as a Visiting PhD Student at [Carnegie Mellon University](https://hcii.cmu.edu/). Before joining AIR, I was a Senior Researcher in the [Systems Research Group](https://www.microsoft.com/en-us/research/group/systems-and-networking-research-group-asia/) at [Microsoft Research Asia (MSRA)](https://www.msra.cn/).

My research interests can be summarized as **intelligent systems software**, which includes the following two aspects:
- **Systems and software supports for AI** - Building systems and tools to improve AI, including its reliability, privacy, and efficiency.
- **AI for fundamental software and systems** - Revolutionalizing today's systems and software with AI, such as program synthesis, automated testing, and self-organized systems.

I’ve published more than 20 research papers in premier venues such as ICSE, FSE, ISSTA, SIGIR, UbiComp, and MobiCom, including a best paper nomination in UbiComp 2016 and a best paper in IS-EUD 2017. Some of the papers have become popular open-source tools ([DroidBot](https://github.com/honeynet/droidbot/), [PrivacyStreams](https://github.com/PrivacyStreams/), [Humanoid](https://github.com/yzygitzh/Humanoid), etc.) in the area.

<p style="border-radius: 5px; border:5px; border-style:solid; border-color:#841E46; padding: 1em; background-color: #841E46; color: #FFFFFF">Our team is recruiting PostDocs, PhD students, engineers, and interns. Please feel free to contact me if you find our research interesting.</p>

## News

- 📢 **2021/12** -- Our paper "ReMoS: Reducing Defect Inheritance in Transfer Learning via Relevant Model Slicing" is accepted to ICSE 2022. It discusses the defect inheritance problem during transfer learning. I believe the security of pretrained models is an important problem since pretraining is increaingly popular.
- 📢 **2021/11** -- I recently left MSRA and joined the Institute for AI Industry Research (AIR) at Tsinghua University as a Research Assistant Professor. Many thanks to my mentors and colleagues at MSRA.

[More...](/news/)
    
## Current Research

<style>
table { border: none; }
table th { border: none; }
table td { border: none; }
table th:first-of-type {
    width: 15%;
}
table th:nth-of-type(2) {
    width: 70%;
}
table th:nth-of-type(3) {
    width: 15%;
}
</style>

<!-- CCF-A badge [![CCF-A](https://img.shields.io/badge/CCF-A-brightgreen.svg)](#) -->

### Systems and software for AI

- Enhancing AI reliability
  - Adversarial attacks ([ICSE22](/publications/#ICSE22), [FSE20](/publications/#FSE20), [Arxiv21](/publications/#Arxiv21))
  - Backdoor attacks ([ICSE21](/publications/#ICSE21), [ICSE22](/publications/#ICSE22)).
- Protecting AI privacy
  - Data privacy ([FSE21](/publications/#FSE21), [UbiComp21](/publications/#UbiComp21), [UbiComp17a](/publications/#UbiComp17a))
  - Model privacy ([ISSTA21](/publications/#ISSTA21)).
- Improving AI efficiency and adaptivity on the edge ([MobiCom21](/publications/#MobiCom21)).

### AI for systems and software

- AI-based automated testing 
  - Automated mobile app testing ([ICSE17](/publications/#ICSE17), [ASE19](/publications/#ASE19)).
- AI-powered program synthesis
  - The synthesis of UI scripts ([SIGIR21](/publications/#SIGIR21), [ISEUD17](/publications/#ISEUD17)).
- AI for self-organized systems.

<!-- | Venue | Authors & Title | Tags & Links |
|----|----|----|
| [ESEC/FSE 2021] | Chengxu Yang<sup>(intern)</sup>, **Yuanchun Li\***, Mengwei Xu, Zhenpeng Chen, Yunxin Liu, Gang Huang, Xuanzhe Liu. "TaintStream: Fine-grained Taint Tracking for Big Data Platforms through Dynamic Code Translation" | [[pdf]]({{site.baseurl}}/static/files/FSE2021_TaintStream.pdf) [[code]](https://github.com/privacystreams/TaintStream) |
| [ISSTA 2021] | **Yuanchun Li**, Ziqi Zhang, Bingyan Liu, Ziyue Yang, Yunxin Liu. "ModelDiff: Testing-based DNN Similarity Comparison for Model Reuse Detection" | [[arxiv]](https://arxiv.org/pdf/2106.08890.pdf) [[code]](https://github.com/ylimit/ModelDiff) |
| [SIGIR 2021] | **Yuanchun Li**, Oriana Riva. "Glider: A reinforcement learning approach to extract UI scripts from websites" | [[pdf]]({{site.baseurl}}/static/files/SIGIR2021_Glider.pdf) |
| [ICSE 2021] | **Yuanchun Li**, Jiayi Hua, Haoyu Wang, Chunyang Chen, Yunxin Liu. "DeepPayload: Black-box Backdoor Attack on Deep Learning Models through Neural Payload Injection" | [[arxiv]](https://arxiv.org/pdf/2101.06896.pdf) |
| [UbiComp 2021]  | Bingyan Liu<sup>(intern)</sup>, **Yuanchun Li\***, Yao Guo, Xiangqun Chen, Yunxin Liu. "PMC: A Privacy-preserving Deep Learning Model Customization Framework for Edge Computing" | [[pdf]]({{site.baseurl}}/static/files/UbiComp2021_PMC.pdf) [[code]](https://github.com/ziqi-zhang/NNSlicer) |
| [ESEC/FSE 2020] | Ziqi Zhang<sup>(intern)</sup>, **Yuanchun Li\***, Yao Guo, Xiangqun Chen, Yunxin Liu. "Dynamic Slicing for Deep Neural Networks." | [[arxiv]](https://arxiv.org/pdf/2009.13747.pdf) [[code]](https://github.com/ziqi-zhang/NNSlicer) |
| [ASE 2019 tool] | **Yuanchun Li**, Ziyue Yang*, Yao Guo, Xiangqun Chen. "Humanoid: a deep learning-based approach to automated black-box Android app testing." | [[arxiv]](https://arxiv.org/abs/1901.02633) <a class="github-button" href="https://github.com/yzygitzh/Humanoid" data-show-count="true" aria-label="Star Humanoid on GitHub">Star</a> |
| [BigData 2018] | **Yuanchun Li**, Ziyue Yang, Yao Guo, Xiangqun Chen, Yuvraj Agarwal, and Jason Hong. "Automated Extraction of Personal Knowledge from Smartphone Push Notifications." | [[arxiv]](https://arxiv.org/pdf/1808.02013.pdf) |
| [UbiComp 2017] | **Yuanchun Li**, Fanglin Chen, Toby Jia-jun Li, Yao Guo, Gang Huang, Matthew Fredrikson, Yuvraj Agarwal, Jason I. Hong. "PrivacyStreams: Enabling Transparency in Personal Data Processing for Mobile Apps." | [[pdf]]({{site.baseurl}}/static/files/UbiComp2017_PrivacyStreams.pdf) <a class="github-button" href="https://github.com/PrivacyStreams/PrivacyStreams" data-show-count="true" aria-label="Star PrivacyStreams/PrivacyStreams on GitHub">Star</a> |
| [UbiComp 2017] | **Yuanchun Li**, Baoxiong Jia, Yao Guo, Xiangqun Chen. "Mining User Reviews for Mobile App Comparisons." | [[pdf]]({{site.baseurl}}/static/files/UbiComp2017_mining-user-reviews.pdf) |
| [ICSE 2017 tool] | **Yuanchun Li**, Ziyue Yang, Yao Guo and Xiangqun Chen. "DroidBot: A Lightweight UI-Guided Test Input Generator for Android." | [[pdf]]({{site.baseurl}}/static/files/ICSE2017_DroidBot.pdf) <a class="github-button" href="https://github.com/honeynet/droidbot" data-show-count="true" aria-label="Star honeynet/droidbot on GitHub">Star</a> |
| [IS-EUD 2017] | Toby Jia-Jun Li, **Yuanchun Li**, Fanglin Chen and Brad A. Myers. "Programming IoT Devices by Demonstration Using Mobile Apps." <span style="color:red">Best Paper Award!</span> | [[pdf]](http://www.cs.cmu.edu/~NatProg/papers/IoT-IS-EUD2017.pdf) |
| [UbiComp 2016] | **Yuanchun Li**, Yao Guo, Xiangqun Chen. "PERUIM: Understanding Mobile Application Privacy With Permission-UI Mapping." <span style="color:red">Honorable Mention Award!</span> | [[pdf]]({{site.baseurl}}/static/files/UbiComp2016_PERUIM.pdf) |
| [ISLPED 2015] | **Yuanchun Li**, Yao Guo, Junjun Kong, and Xiangqun Chen. "Fixing sensor-related energy bugs through automated sensing policy instrumentation." | [[pdf]]({{site.baseurl}}/static/files/ISLPED2015.pdf) | -->


<script async defer src="https://buttons.github.io/buttons.js"></script>
