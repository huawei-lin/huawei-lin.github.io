---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a Ph.D. Candidate (2022.08-) in Computing Information & Science here at Rochester Institute of Technology (RIT) supervised by Prof. [Weijie Zhao](https://www.cs.rit.edu/~wjz/). My research interests span <b> LLMs, AI Privacy & Security, and Scalable & Trustworthy Machine Learning</b>.

Prior to RIT, I worked as a research assistant at the Institute of Computer Vision (ICV), Shenzhen University, China, and was supervised by Prof.  [Linlin Shen](https://scholar.google.com/citations?user=AZ_y9HgAAAAJ&hl=en&oi=ao) (**Honorary Professor** at the University of Nottingham, UK). Besides, I used to work as a software engineer (intern) at AI Lab of ByteDance inc. (TikTok's Parent Company).

I got the bachelor's degree in Computer Science and Technology in July 2021. I was the leader of a project funded by the <b>National Ministry of Education of China</b> for undergraduates in 2019. During my period of undergraduate, I received an <b>ACM-ICPC Asia Bronze Medal</b> in the ACM-ICPC International Collegiate Programming Contest, and a <b>Silver Medal</b> in the ACM-ICPC Shaanxi Province Contest of China.

My curriculum vitae can be found at [here](https://drive.google.com/file/d/18xKzvnbkC4ZS7h3TAZIDJ3zHus1fwi6l/view?usp=sharing).
<br />
<br />

<!--comment
<font color="red">🔥 I am actively looking for research/engineer internship opportunities in Large Language Models (LLMs), Computer Vision and Machine Learning for the summer of 2024. <b>More research experience and papers about LLMs can be found at my <a href="https://drive.google.com/file/d/18xKzvnbkC4ZS7h3TAZIDJ3zHus1fwi6l/view?usp=sharing">CV</a>.</b></font><br>
-->

<font color="red"><b>[News]</b></font>
**Apr. 16, 2024: I will be joining Amazon as an Applied Scientist Intern in Boston this summer, focusing on large language models and multimodal systems. 🎉🎉🎉**<br />
**Feb. 26, 2024**: We released an easy-to-run implementation for finetuning large language models (LLMs) such as llama and gemma, supporting full parameter finetuning, LoRA, and QLoRA. Please feel free to star, fork, and make your own contributions. [[Github Repo](https://github.com/huawei-lin/LLMsEasyFinetune)]<br />
**Feb. 12, 2024**: Invited as a reviewer for KDD 2024.<br />
**Oct. 02, 2023**: Invited as a reviewer for NeurIPS 2023 GLFrontiers Workshop.<br />
**Aug. 05, 2023**: Received the KDD’23 Student Travel Award. Thanks to KDD!<br />
**May. 16, 2023**: Our paper ([Machine Unlearning in Gradient Boosting Decision Trees](https://dl.acm.org/doi/10.1145/3580305.3599420)) is accepted by KDD 2023! [[Promotion Video](https://www.youtube.com/watch?v=4dQlNfnULVw), [Poster](https://drive.google.com/file/d/1US2ISzh62dzb4vCdkICU99_a1iZOPL-B/view?usp=sharing)]<br />
**Sep. 12, 2022**: Our paper ([Activation Template Matching Loss for Explainable Face Recognition](https://arxiv.org/abs/2207.02179)) is accepted by the 2023 IEEE Conference on Automatic Face and Gesture Recognition ([FG 2023](https://fg2023.ieee-biometrics.org/))!

<!--comment
# Education
**Rochester Institute of Technology (RIT)**, Rochester, NY  
Aug. 2022 - Present  
Ph.D. Candidate in Computing Information & Science | Advisor: Prof. [Weijie Zhao](https://www.cs.rit.edu/~wjz/)  


**Shaanxi University of Science and Technology (SUST)**, Xi’an, China  
Sept. 2017 - July 2021  
B.S. in Computer Science & Technology  
Thesis: Design and Implementation of Topological Function Classification Software for Medical Image **(Outstanding undergraduate thesis, Score: 90/100)** -->


# Tech Talks
- **"Machine Unlearning in Gradient Boosting Decision Trees"** at Long Beach, CA, Aug. 9, 2023. [[Slides](https://drive.google.com/file/d/10tW2yhb4KN8lzF7kLuiv3TuiGcZVY_Ye/view?usp=sharing), [Video](https://drive.google.com/file/d/1Z6Yt__cE1WUsutKMr0agOvihKKM0iezc/view?usp=sharing)]
- **"Activation Template Matching Loss for Explainable Face Recognition"** at Rochester Institute of Technology, Nov. 17, 2022. [[Slides](https://drive.google.com/file/d/1UHgZc83fyBefR02C4Njez3vZF73AlcbL/view?usp=share_link), [Video](https://drive.google.com/file/d/1z6NpJFiIeZarlte1Uae7k-9ylisulDho/view?usp=share_link)]
- **"Toward Explainable Face Recognition"** at Shenzhen University, Oct. 28, 2021. [[Slides](https://drive.google.com/file/d/1Ax8IrluTPnQXBLMgfP4DLSyxwwbMEbN7/view?usp=sharing)]
- **"Trust in Black-Box Models: Interpretability & Explainability for Deep Learning"** at Shenzhen University, Aug. 13, 2021. [[Slides](https://drive.google.com/file/d/1ONd7Hd28wyHqLOCck6z2pq_Z3wreSbwm/view?usp=sharing)]


# Selected Publications
- **Huawei Lin**, Jun Woo Chung, Yingjie Lao, Weijie Zhao, [Machine Unlearning in Gradient Boosting Decision Trees](https://dl.acm.org/doi/10.1145/3580305.3599420). KDD 2023.
- **Huawei Lin**, Haozhe Liu, Qiufu Li, Linlin Shen, [Activation Template Matching Loss for Explainable Face Recognition](https://arxiv.org/abs/2207.02179). 2023 IEEE 17th International Conference on Automatic Face and Gesture Recognition (FG), 2023

- Yong Qi, **Huawei Lin**, Yanping Li, Jiashu Chen, [Parameter-free Attention in fMRI Decoding](https://ieeexplore.ieee.org/document/9386094). IEEE Access, 2021.
- Yong Qi, Menzhe Qiu, **Huawei Lin**, Jiashu Chen, Yanping Li, Huaiguang Lei, [Research on Gender-related Fingerprint Features](https://arxiv.org/abs/2108.08233). 2021.

<!--comment
<br />
<br />
-  Yong Qi, **Huawei Lin**, Yanping Li, [Task fMRI brain decoding and visualization method based on convolutional neural network](https://worldwide.espacenet.com/patent/search?q=pn%3DCN111681292A). CN111681292A, 2020.
- Yong Qi, Yang Yang, **Huawei Lin**, Yunfan Zuo, Chenglong Yu, [Ceramic ornamentation extraction method based on convolutional neural network and image processing](https://worldwide.espacenet.com/patent/search?q=pn%3DCN111814550A). CN111814550A, 2020.
- Yong Qi, **Huawei Lin**,  Chenglong Yu, Jiaoxing Hou, [Method for measuring pore radius in porous material scanning electron microscope image](https://worldwide.espacenet.com/patent/search?q=pn%3DCN111024581A). CN111024581A, 2019.
-->

# Research Experience 
<div class='paper-box'><div class='paper-box-image'><div><img src='images/researchExpImg/GBDTunlearning.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Machine Unlearning in Gradient Boosting Decision Trees (GBDT)** 
- Propose an unlearning framework that efficiently and effectively unlearns a given collection of data **without retraining** the model from scratch.
- Introduce a collection of techniques, including random split point selection and random partitioning layers training, to the training process of the original tree models to ensure that the trained model requires few subtree retrainings during the unlearning.
- To the best of our knowledge, this is the **first work** that considers machine unlearning on GBDT.

[[Paper](https://dl.acm.org/doi/10.1145/3580305.3599420), [Code](https://github.com/huawei-lin/OnlineBoosting), [Slides](https://drive.google.com/file/d/10tW2yhb4KN8lzF7kLuiv3TuiGcZVY_Ye/view?usp=sharing), [Video](https://drive.google.com/file/d/1Z6Yt__cE1WUsutKMr0agOvihKKM0iezc/view?usp=sharing), [Poster](https://drive.google.com/file/d/1US2ISzh62dzb4vCdkICU99_a1iZOPL-B/view?usp=sharing)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/researchExpImg/abstract_ECLoss.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Activation Template Matching Loss for Explainable Face Recognition** 
- Propose a novel method named Explainable Channel Loss (ECLoss) to construct an **explainable face recognition network**, which can **directly explain** that what face recognition networks have learned.  
- To the best of our knowledge, this is the **first method** to construct a feature level explainable face recognition network that does not require any additional dataset or manual annotation.  

[[Paper](https://arxiv.org/abs/2207.02179), [Slides](https://drive.google.com/file/d/1Ax8IrluTPnQXBLMgfP4DLSyxwwbMEbN7/view?usp=sharing), [Video](https://drive.google.com/file/d/1z6NpJFiIeZarlte1Uae7k-9ylisulDho/view?usp=share_link)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/researchExpImg/GA-1-scaled.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Parameter-free Attention in fMRI Decoding** 
- Led a team working on a research project that was selected as a National Training Program of Innovation and Entrepreneurship for Undergraduates and funded by **the Chinese National Ministry of Education**.
- Proposed a parameter-free attention module named **Parameter-free Attention Module (SAM)** to reduce the average error rate by **1.2%-3.1%** while without involving any parameter.
  
[[Paper](https://ieeexplore.ieee.org/document/9386094), [Poster](https://drive.google.com/file/d/1BvnTwlea7ZaXAQAIPwMVrukGKHA2nYDj/view?usp=sharing), [Patent](https://worldwide.espacenet.com/patent/search?q=pn%3DCN111681292A)]
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/researchExpImg/fingerprint_GA-scaled.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Gender-Related Feature Extraction from Fingerprints** 
- Designed an architecture called **Dense Dilated Convolution ResNet (DDCResNet)** to improve the decoding performance of the feature extraction algorithms.
- Achieved an average extraction accuracy of **95%**, which significantly exceeds traditional feature extraction methods.
- **Improved the interpretability** of the algorithms by using Gradient-weighted Class Activation Mapping (Grad-CAM) to visualize the high-score regions of gender information in fingerprint images.
  
[[Paper](https://arxiv.org/abs/2108.08233)]
  
</div>
</div>


# Internship Experience

**Institute of Computer Vision, Shenzhen University**, Shenzhen, China  
July 2021 - July 2022  
Research Assistant | Supervisor: Prof. [Linlin Shen](https://scholar.google.com/citations?user=AZ_y9HgAAAAJ&hl=en&oi=ao)  
- Responsible for **interpretability and explainability** on deep learning, especially on Biometrics.  
- Propose a novel method named Explainable Channel Loss (ECLoss) to construct an **explainable face recognition** network, which can **directly explain** that what face recognition networks have learned.
- To the best of our knowledge, this is the **first method** to construct a feature level explainable face recognition network that does not require any additional dataset or manual annotation.
<br />


**AI Lab, ByteDance Inc.**, Beijing, China  
Oct. 2020 - July 2021  
Software Engineer
- Responsible for **Audio Recognition and Understanding** research and development, and technical supports for ByteDance’s applications, including **TikTok**.  
- Proposed Stream Audio Understanding Chain method which enabled **real-time audio processing** and achieved precise extraction of information from audios, including speakers’ genders, tones, emotions, etc.  
- Designed a pipeline processing flow that significantly increased the throughput of CPUs and reduced processing time by **65%**, by optimizing the usage of CPUs/GPUs using multiprocessing and multithreading.  


# Fellowships & Awards
## Fellowships
- **KDD23, Student Travel Awards**&emsp;*Aug. 2023*
- Zhou Lian Academic Scholarship **(Only 1 of ~20,000 Students)**&emsp;*Oct. 2020*
- Academic Innovation and Technology Scholarship (Only 10 of ~20,000 Students)&emsp;*May 2020*
- **IAPR/IEEE Winter School on Biometrics 2020, Student Travel Grants**&emsp;*Jan. 2020*
- Academic Innovation and Technology Scholarship (Only 10 of ~20,000 Students)&emsp;*May 2019*

## Awards
- ACM-ICPC National Programming Contest (Shaanxi), Bronze Medal&emsp;*June 2021*
- **ACM-ICPC Programming Contest (Shaanxi Province), Silver Medal**&emsp;*Sept. 2020*
- ACM-ICPC National Programming Contest (Shaanxi), Bronze Medal&emsp;*June 2020*
- ACM-ICPC National Programming Contest (Yinchuan), Bronze Medal&emsp;*May 2019*
- **ACM-ICPC Asia Regional Contest, Bronze Medal&emsp;*Nov. 2018***
- ACM-ICPC Chinese Collegiate Programming Contest, Bronze Medal&emsp;*Jan. 2018*


# Professional Services

## Reviewer
- KDD 2024
- NeurIPS 2023 GLFrontiers Workshop

## Open Source Project Contribution
We have a team dedicated to building open-source AI systems about Artificial General Intelligence (AGI), Generative AI (GAI) and Large Language Models (LLMs). [[Website](https://www.dynamonai.com/), [GitHub](https://github.com/DynamonAI)]
- [llama.cpp](https://github.com/ggerganov/llama.cpp/)
- [LLMsEasyFinetune](https://github.com/huawei-lin/LLMsEasyFinetune)
- [paper-assistant](https://github.com/DynamonAI/paper-assistant)

# TECHNICAL SKILLS
- Programming Languages: **C/C++, Python, Go, Java, Shell**, HTML
- Deep Learning Tools: **PyTorch, CUDA, Keras, TensorFlow**
- Deep Learning Packages: **Transformers, DeepSpeed, FSDP, PEFT, OpenAI**
- Others: **Slurm, MATLAB, Docker, Hadoop**, Kubernetes, Kafka

<!--

# Teaching Experience
- Student Lecturer *at* **National Olympiad in Informatics**: **Algorithm Design (C/C++)** (192 hours, 2 years)
- Lecturer *at* Algorithm Summer Camp 2019: **Introduction to Deep Learning** (48 hours)
- Lecturer *at* Algorithm Summer Camp 2018: **Application of Algorithms (C/C++)** (48 hours)

# Activities
- **Captain of SUST Programming Competition Team, 2017-2020**
- ByteDance Program Camp, 2022, Online
- VALSE (Vision And Learning SEminar), 2021, Hangzhou, Zhejiang Province, China
- The 15-th Chinese Conference on Biometric Recognition (CCBR), 2021, Online
- ByteDance Program Camp Spring Special Part, 2021, Beijing, China
- The 3-rd Chinese Conference on Pattern Recognition and Computer Vision (PRCV), 2020, Xi’an, Shaanxi Province, China
- The IAPR/IEEE Winter School on Biometrics, 2020, Shenzhen, Guangdong Province, China
- The China Society of Image and Graphics Conference (CSIG), 2019, Xi’an, Shaanxi Province, China
- The Wanna-fly Programming Camp, 2019, Qinhuangdao, Hebei Province, China
- Member of College Football Team, 2017 - 2019
- Member of Robot-Master Society, 2017 - 2018

# Technical skills & Hobbies
- Contributed to the Chinese Software Developer Community by sharing technical experience and knowledge on site via blogs which own <b>530,000 views</b> on average. [(website)](https://winsoul.blog.csdn.net/)
- Praised by the school three times for good prize in programming contest and were recorded on the official website.[[1]]( https://www.sust.edu.cn/info/1071/6309.htm) [[2]]( https://www.sust.edu.cn/info/1071/7227.htm) [[3]](https://www.sust.edu.cn/info/1073/8667.htm)
- <b>Pursue a PhD degree in Computer Science and make impactful contributions to my chosen academic fields.</b>
-->

---
<div align='left'>
  <script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=150&t=n&d=bwNfa6whNVk72dhUDuSXp-khWF8RfXT6R9iParduWmM'></script>
</div> 

