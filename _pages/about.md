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

My current research interests can be summarized as **Edge AI**, which includes the following two aspects:
- **Edge AI Efficiency** - Building systems to improve the efficiency of AI models, or designing AI models that can run efficiently at the edge.
- **Edge AI Reliability** - Improving the reliability of AI models deployed at the edge, by making them more robust, generalizable, and privacy-preserving.

I’ve published more than 20 research papers in premier venues such as ICSE, FSE, ISSTA, SIGIR, UbiComp, MobiCom, and ICLR, including a best paper nomination in UbiComp 2016 and a best paper in IS-EUD 2017. Some of the papers have become popular open-source tools ([DroidBot](https://github.com/honeynet/droidbot/), [PrivacyStreams](https://github.com/PrivacyStreams/), [Humanoid](https://github.com/yzygitzh/Humanoid), etc.) in the area.

<p style="border-radius: 5px; border:5px; border-style:solid; border-color:#841E46; padding: 1em; background-color: #841E46; color: #FFFFFF">Our team is recruiting PostDocs, PhD students, engineers, and interns. Please feel free to contact me if you are interested.</p>

## News

- 📢 **2022/03** -- Our paper "Representational Continuity for Unsupervised Continual Learning" got accepted to ICLR 2022 (Oral presentation)!
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

- Enhancing AI reliability
  - Adversarial attacks & defense ([ICSE22](/publications/#ICSE22), [FSE20](/publications/#FSE20), [Arxiv21](/publications/#Arxiv21))
  - Backdoor attacks & defense ([ICSE21](/publications/#ICSE21), [ICSE22](/publications/#ICSE22))
  - Overcoming distribution shift ([UbiComp21](/publications/#UbiComp21), [ICLR22](/publications/#ICLR22))
- Improving AI efficiency
  - Systems support for AI ([MobiCom21](/publications/#MobiCom21))
  - Model design/compression for efficiency
- Protecting AI privacy
  - Data privacy ([FSE21](/publications/#FSE21), [UbiComp21](/publications/#UbiComp21), [UbiComp17a](/publications/#UbiComp17a))
  - Model privacy ([ISSTA21](/publications/#ISSTA21))

## Selected Recent Publications

| Venue | Authors & Title | Tags & Links |
|----|----|----|
| [ICSE 2022] | Ziqi Zhang<sup>(s)</sup>, **Yuanchun Li\***, Jindong Wang, Bingyan Liu, Ding Li, Xiangqun Chen, Yao Guo, Yunxin Liu. “ReMoS: Reducing Defect Inheritance in Transfer Learning via Relevant Model Slicing” | |
| [ESEC/FSE 2021] | Chengxu Yang<sup>(s)</sup>, **Yuanchun Li\***, Mengwei Xu, Zhenpeng Chen, Yunxin Liu, Gang Huang, Xuanzhe Liu. "TaintStream: Fine-grained Taint Tracking for Big Data Platforms through Dynamic Code Translation" | [[pdf]]({{site.baseurl}}/static/files/FSE2021_TaintStream.pdf) [[code]](https://github.com/privacystreams/TaintStream) |
| [ISSTA 2021] | **Yuanchun Li**, Ziqi Zhang, Bingyan Liu, Ziyue Yang, Yunxin Liu. "ModelDiff: Testing-based DNN Similarity Comparison for Model Reuse Detection" | [[arxiv]](https://arxiv.org/pdf/2106.08890.pdf) [[code]](https://github.com/ylimit/ModelDiff) |
| [SIGIR 2021] | **Yuanchun Li**, Oriana Riva. "Glider: A reinforcement learning approach to extract UI scripts from websites" | [[pdf]]({{site.baseurl}}/static/files/SIGIR2021_Glider.pdf) |
| [ICSE 2021] | **Yuanchun Li**, Jiayi Hua, Haoyu Wang, Chunyang Chen, Yunxin Liu. "DeepPayload: Black-box Backdoor Attack on Deep Learning Models through Neural Payload Injection" | [[arxiv]](https://arxiv.org/pdf/2101.06896.pdf) |
| [UbiComp 2021]  | Bingyan Liu<sup>(s)</sup>, **Yuanchun Li\***, Yao Guo, Xiangqun Chen, Yunxin Liu. "PMC: A Privacy-preserving Deep Learning Model Customization Framework for Edge Computing" | [[pdf]]({{site.baseurl}}/static/files/UbiComp2021_PMC.pdf) [[code]](https://github.com/ziqi-zhang/NNSlicer) |
| [ESEC/FSE 2020] | Ziqi Zhang<sup>(s)</sup>, **Yuanchun Li\***, Yao Guo, Xiangqun Chen, Yunxin Liu. "Dynamic Slicing for Deep Neural Networks." | [[arxiv]](https://arxiv.org/pdf/2009.13747.pdf) [[code]](https://github.com/ziqi-zhang/NNSlicer) |
| [UbiComp 2017] | **Yuanchun Li**, Fanglin Chen, Toby Jia-jun Li, Yao Guo, Gang Huang, Matthew Fredrikson, Yuvraj Agarwal, Jason I. Hong. "PrivacyStreams: Enabling Transparency in Personal Data Processing for Mobile Apps." | [[pdf]]({{site.baseurl}}/static/files/UbiComp2017_PrivacyStreams.pdf) <a class="github-button" href="https://github.com/PrivacyStreams/PrivacyStreams" data-show-count="true" aria-label="Star PrivacyStreams/PrivacyStreams on GitHub">Star</a> |
| [ICSE 2017] | **Yuanchun Li**, Ziyue Yang, Yao Guo and Xiangqun Chen. "DroidBot: A Lightweight UI-Guided Test Input Generator for Android." | [[pdf]]({{site.baseurl}}/static/files/ICSE2017_DroidBot.pdf) <a class="github-button" href="https://github.com/honeynet/droidbot" data-show-count="true" aria-label="Star honeynet/droidbot on GitHub">Star</a> |
| [UbiComp 2016] | **Yuanchun Li**, Yao Guo, Xiangqun Chen. "PERUIM: Understanding Mobile Application Privacy With Permission-UI Mapping." <span style="color:red">Honorable Mention Award!</span> | [[pdf]]({{site.baseurl}}/static/files/UbiComp2016_PERUIM.pdf) |


<script async defer src="https://buttons.github.io/buttons.js"></script>
