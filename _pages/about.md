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

I am a Ph.D. Candidate (2022.08-) in Computing Information & Science here at Rochester Institute of Technology (RIT) supervised by Prof. [Weijie Zhao](https://www.cs.rit.edu/~wjz/). I previously interned at Amazon (AGI, Foundation Models) and ByteDance (Audio & Speech Processing). My research interests span <b>GenAI, LLMs, AI Privacy & Security, and Scalable & Trustworthy Machine Learning</b>.

Prior to RIT, I worked as a research assistant at the Institute of Computer Vision (ICV), Shenzhen University, China, and was supervised by Prof.  [Linlin Shen](https://scholar.google.com/citations?user=AZ_y9HgAAAAJ&hl=en&oi=ao) (**Honorary Professor** at the University of Nottingham, UK). I got the bachelor's degree in Computer Science and Technology in July 2021. I was the leader of a project funded by the Ministry of Education of China for undergraduates in 2019. I received several <b>ACM-ICPC Medals</b> during my undergraduate.

<font color="blue">In support of open science, I **open-source the code for all my first-author research papers**. If you have any questions or suggestions, do not hesitate to contact me.</font>

My curriculum vitae can be found at [here](https://drive.google.com/file/d/18xKzvnbkC4ZS7h3TAZIDJ3zHus1fwi6l/view?usp=sharing). 

<br />

<font color="red">🔥 I am actively looking for research internship opportunities in Large Language Models, Computer Vision and Machine Learning for 2025 (Spring/Summer/Fall/Winter). <b>More research experience and papers (under review) can be found at my <a href="https://drive.google.com/file/d/18xKzvnbkC4ZS7h3TAZIDJ3zHus1fwi6l/view?usp=sharing">CV</a>.</b></font><br>

<div style="max-height: 400px; overflow-y: auto; border: 0.5px solid #ccc; padding: 10px; border-radius: 5px; line-height: 1.8;">
  <span style="color:red;"><b>[News]</b></span><br />
  <b>May 20, 2025</b>: We released <b>VTBench</b>, a comprehensive benchmark evaluating over 20 visual tokenizers from recent state-of-the-art autoregressive image generation models. Our study reveals that current discrete tokenizers significantly lag behind continuous VAEs, particularly in high-resolution reconstruction, multilingual text preservation, and fine-grained detail fidelity. The <a href="https://arxiv.org/abs/2505.13439" target="_blank">paper</a>, <a href="https://github.com/huawei-lin/VTBench" target="_blank">codebase</a>, <a href="https://huggingface.co/datasets/huaweilin/VTBench" target="_blank">dataset</a>, and <a href="https://huggingface.co/spaces/huaweilin/VTBench" target="_blank">interactive demo</a> are all publicly available. Come try it out!<br />
  <b>May 6, 2025</b>: I will be joining Amazon as an Applied Scientist Intern in Bellevue, WA this summer, focusing on LLM agents. 🎉🎉🎉<br />
  <b>Apr. 20, 2025</b>: Invited to speak in a tutorial of "LLMs and Copyright Risks" at NAACL 2025. [<a href="https://drive.google.com/file/d/1kgIy-WO9kAj6fyF4YqFh-hgtLJKNLJ_I/view?usp=sharing" target="_blank">Slides</a>, <a href="https://drive.google.com/file/d/1KJ4g92mRZBS2UBkPWOiOSj8zA8jF7lz3/view?usp=sharing" target="_blank">Video</a>]<br />
  <b>Apr. 11, 2025</b>: Invited as a reviewer for NeurIPS 2025.<br />
  <b>Apr. 4, 2025</b>: One paper is accepted by SIGIR 2025! 🎉🎉🎉<br />
  <b>Mar. 22, 2025</b>: Invited as a reviewer for ACL ARR 2025.<br />
  <b>Mar. 17, 2025</b>: Invited as a reviewer for ICML 2025.<br />
  <b>Jan. 26, 2025</b>: Invited as a reviewer for IEEE Transactions on Dependable and Secure Computing.<br />
  <b>Jan. 22, 2025</b>: One paper is accepted by NAACL 2025! 🎉🎉🎉<br />
  <b>Aug. 23, 2024</b>: Invited as a reviewer for ICLR 2025.<br />
  <b>Jul. 21, 2024</b>: Invited as a reviewer for ACL ARR 2024.<br />
  <b>Jul. 12, 2024</b>: Invited as a reviewer for KDD 2025.<br />
  <b>May. 16, 2024</b>: Our paper (<a href="https://aclanthology.org/2024.acl-long.48/" target="_blank">Token-wise Influential Training Data Retrieval for Large Language Models</a>) is accepted by ACL 2024! In this paper, we propose RapidIn, a scalable framework for estimating the influence of each training data sample on LLMs.<br />
  <b>Apr. 16, 2024</b>: I will be joining Amazon as an Applied Scientist Intern in Boston this summer, focusing on large language models and multimodal systems. 🎉🎉🎉<br />
  <b>Feb. 26, 2024</b>: We released an easy-to-run implementation for finetuning large language models (LLMs) such as llama and gemma, supporting full parameter finetuning, LoRA, and QLoRA. Please feel free to star, fork, and make your own contributions. <a href="https://github.com/huawei-lin/LLMsEasyFinetune" target="_blank">[Github Repo]</a><br />
  <b>Feb. 12, 2024</b>: Invited as a reviewer for KDD 2024.<br />
  <b>Oct. 02, 2023</b>: Invited as a reviewer for NeurIPS 2023 GLFrontiers Workshop.<br />
  <b>Aug. 05, 2023</b>: Received the KDD’23 Student Travel Award. Thanks to KDD!<br />
  <b>May. 16, 2023</b>: Our paper (<a href="https://dl.acm.org/doi/10.1145/3580305.3599420" target="_blank">Machine Unlearning in Gradient Boosting Decision Trees</a>) is accepted by KDD 2023! 
  <a href="https://www.youtube.com/watch?v=4dQlNfnULVw" target="_blank">[Promotion Video]</a>, 
  <a href="https://drive.google.com/file/d/1US2ISzh62dzb4vCdkICU99_a1iZOPL-B/view?usp=sharing" target="_blank">[Poster]</a><br />
  <b>Sep. 12, 2022</b>: Our paper (<a href="https://arxiv.org/abs/2207.02179" target="_blank">Activation Template Matching Loss for Explainable Face Recognition</a>) is accepted by the 2023 IEEE Conference on Automatic Face and Gesture Recognition (<a href="https://fg2023.ieee-biometrics.org/" target="_blank">FG 2023</a>)!
</div>

<!--
<font color="red"><b>[News]</b></font>
**Apr. 11, 2025**: Invited as a reviewer for NeurIPS 2025.<br />
**Apr. 5, 2025**: **I will be joining NEC Labs America as a Research Intern this summer, focusing on Trustworthy LLMs.**<br />
**Apr. 4, 2025**: One paper is accepted by SIGIR 2025! 🎉🎉🎉<br />
**Mar. 22, 2025**: Invited as a reviewer for ACL ARR 2025.<br />
**Mar. 17, 2025**: Invited as a reviewer for ICML 2025.<br />
**Jan. 26, 2025**: Invited as a reviewer for IEEE Transactions on Dependable and Secure Computing.<br />
**Jan. 22, 2025**: One paper is accepted by NAACL 2025! 🎉🎉🎉<br />
**Aug. 23, 2024**: Invited as a reviewer for ICLR 2025.<br />
**Jul. 21, 2024**: Invited as a reviewer for ACL ARR 2024.<br />
**Jul. 12, 2024**: Invited as a reviewer for KDD 2025.<br />
**May. 16, 2024**: Our paper ([Token-wise Influential Training Data Retrieval for Large Language Models](https://aclanthology.org/2024.acl-long.48/)) is accepted by ACL 2024! In this paper, we propose RapidIn, a scalable framework for estimating the influence of each training data sample on LLMs.<br />
**Apr. 16, 2024: I will be joining Amazon as an Applied Scientist Intern in Boston this summer, focusing on large language models and multimodal systems. 🎉🎉🎉**<br />
**Feb. 26, 2024**: We released an easy-to-run implementation for finetuning large language models (LLMs) such as llama and gemma, supporting full parameter finetuning, LoRA, and QLoRA. Please feel free to star, fork, and make your own contributions. [[Github Repo](https://github.com/huawei-lin/LLMsEasyFinetune)]<br />
**Feb. 12, 2024**: Invited as a reviewer for KDD 2024.<br />
**Oct. 02, 2023**: Invited as a reviewer for NeurIPS 2023 GLFrontiers Workshop.<br />
**Aug. 05, 2023**: Received the KDD’23 Student Travel Award. Thanks to KDD!<br />
**May. 16, 2023**: Our paper ([Machine Unlearning in Gradient Boosting Decision Trees](https://dl.acm.org/doi/10.1145/3580305.3599420)) is accepted by KDD 2023! [[Promotion Video](https://www.youtube.com/watch?v=4dQlNfnULVw), [Poster](https://drive.google.com/file/d/1US2ISzh62dzb4vCdkICU99_a1iZOPL-B/view?usp=sharing)]<br />
**Sep. 12, 2022**: Our paper ([Activation Template Matching Loss for Explainable Face Recognition](https://arxiv.org/abs/2207.02179)) is accepted by the 2023 IEEE Conference on Automatic Face and Gesture Recognition ([FG 2023](https://fg2023.ieee-biometrics.org/))!

-->


<!--comment
# Education
**Rochester Institute of Technology (RIT)**, Rochester, NY  
Aug. 2022 - Present  
Ph.D. Candidate in Computing Information & Science | Advisor: Prof. [Weijie Zhao](https://www.cs.rit.edu/~wjz/)  


**Shaanxi University of Science and Technology (SUST)**, Xi’an, China  
Sept. 2017 - July 2021  
B.S. in Computer Science & Technology  
Thesis: Design and Implementation of Topological Function Classification Software for Medical Image **(Outstanding undergraduate thesis, Score: 90/100)** -->

# Publications & Pre-prints
2025
- **Huawei Lin**, Tong Geng, Zhaozhuo Xu, Weijie Zhao, [VTBench: Evaluating Visual Tokenizers for Autoregressive Image Generation](https://arxiv.org/abs/2505.13439). arXiv preprint, arXiv:2505.13439, 2025.
- **Huawei Lin**, Yingjie Lao, Tong Geng, Tan Yu, Weijie Zhao, [UniGuardian: A Unified Defense for Detecting Prompt Injection, Backdoor Attacks and Adversarial Attacks in Large Language Models](https://arxiv.org/abs/2502.13141). arXiv preprint, arXiv:2502.13141, 2025.
- **Huawei Lin**, Jun Woo Chung, Yingjie Lao, Weijie Zhao, [Online Gradient Boosting Decision Tree: In-Place Updates for Efficient Adding/Deleting Data](https://arxiv.org/abs/2502.01634). arXiv preprint, arXiv:2502.01634, 2025.
- Jun Woo Chung, **Huawei Lin**, Weijie Zhao, [Locality-Sensitive Indexing for Graph-Based Approximate Nearest Neighbor Search](https://easychair.org/my/conference?conf=sigir2025). SIGIR 2025.
- Yanzhou Pan, **Huawei Lin**, Yide Ran, Jiamin Chen, Xiaodong Yu, Weijie Zhao, Denghui Zhang, Zhaozhuo Xu, [ALinFiK: Learning to Approximate Linearized Future Influence Kernel for Scalable Third-Parity LLM Data Valuation](https://arxiv.org/abs/2503.01052). NAACL 2025.

2024
- **Huawei Lin**, Yingjie Lao, Weijie Zhao, [DMin: Scalable Training Data Influence Estimation for Diffusion Models](https://arxiv.org/abs/2412.08637). arXiv preprint, arXiv:2412.08637, 2024.
- **Huawei Lin**, Jikai Long, Zhaozhuo Xu, Weijie Zhao, [Token-wise Influential Training Data Retrieval for Large Language Models](https://aclanthology.org/2024.acl-long.48/). ACL 2024.

2023
- **Huawei Lin**, Jun Woo Chung, Yingjie Lao, Weijie Zhao, [Machine Unlearning in Gradient Boosting Decision Trees](https://dl.acm.org/doi/10.1145/3580305.3599420). KDD 2023.
- **Huawei Lin**, Haozhe Liu, Qiufu Li, Linlin Shen, [Activation Template Matching Loss for Explainable Face Recognition](https://arxiv.org/abs/2207.02179). 2023 IEEE 17th International Conference on Automatic Face and Gesture Recognition (FG), 2023

# Tech Talks
- **"LLMs and Copyright Risks: An Example of Future Directions"** at NAACL, Albuquerque, NM, May. 3, 2025. [[Slides](https://drive.google.com/file/d/1kgIy-WO9kAj6fyF4YqFh-hgtLJKNLJ_I/view?usp=sharing), [Video](https://drive.google.com/file/d/1KJ4g92mRZBS2UBkPWOiOSj8zA8jF7lz3/view?usp=sharing)]
- **"Influence Estimation for Large Language Models and Diffusion Models"** at Rochester Institute of Technology, Apr. 1, 2025. [[Slides](https://drive.google.com/file/d/1W2-wyKHWFlcER5u8pYPhOPEIs3Da6f1c/view?usp=sharing)]
- **"Token-wise Influential Training Data Retrieval for Large Language Models"** at ACL Virtual Poster Session, Aug. 12, 2024. [[Slides](https://drive.google.com/file/d/1dS3GrD9z2INOZZ84zBpXlgM0Fbs0-XVt/view?usp=sharing), [Video](https://www.youtube.com/watch?v=B5XO7b5jHWU)]
- **"Toward Explainable Large Language Models via Influence Estimation"** at Boston, MA, May. 23, 2024. [[Poster](https://drive.google.com/file/d/1xX5z5L74_WACKMjo3c2T7AXmfuEQGMLZ/view)]
- **"Machine Unlearning in Gradient Boosting Decision Trees"** at KDD, Long Beach, CA, Aug. 9, 2023. [[Slides](https://drive.google.com/file/d/10tW2yhb4KN8lzF7kLuiv3TuiGcZVY_Ye/view?usp=sharing), [Video](https://drive.google.com/file/d/1Z6Yt__cE1WUsutKMr0agOvihKKM0iezc/view?usp=sharing)]
- **"Activation Template Matching Loss for Explainable Face Recognition"** at Rochester Institute of Technology, Nov. 17, 2022. [[Slides](https://drive.google.com/file/d/1UHgZc83fyBefR02C4Njez3vZF73AlcbL/view?usp=share_link), [Video](https://drive.google.com/file/d/1z6NpJFiIeZarlte1Uae7k-9ylisulDho/view?usp=share_link)]
- **"Toward Explainable Face Recognition"** at Shenzhen University, Oct. 28, 2021. [[Slides](https://drive.google.com/file/d/1Ax8IrluTPnQXBLMgfP4DLSyxwwbMEbN7/view?usp=sharing)]
- **"Trust in Black-Box Models: Interpretability & Explainability for Deep Learning"** at Shenzhen University, Aug. 13, 2021. [[Slides](https://drive.google.com/file/d/1ONd7Hd28wyHqLOCck6z2pq_Z3wreSbwm/view?usp=sharing)]



# Research Experience

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/researchExpImg/UniGuardian_overview.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**UniGuardian: A Unified Defense for Detecting Prompt Injection, Backdoor Attacks and Adversarial Attacks in Large Language Models** 
- We define Prompt Trigger Attacks (PTA) as a unified category encompassing prompt injection, backdoor, and adversarial attacks.
- We analyze their common mechanisms and demonstrate, both theoretically and empirically, the behavioral distinctions of LLMs when processing injected versus clean prompts.
- We introduce UniGuardian, a novel training-free, inference-time detection mechanism that efficiently detects multiple attack types.

[[Paper](https://arxiv.org/abs/2502.13141), [Code](https://github.com/huawei-lin/UniGuardian)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/researchExpImg/OnlineGBDT_overview.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Online Gradient Boosting Decision Tree: In-Place Updates for Efficient Adding/Deleting Data** 
- We introduce an **efficient in-place online learning framework** for gradient boosting models supporting incremental and decremental learning, extensible to finetuning and transfer learning.
- We present optimizations to reduce the cost of incremental and decremental learning, making adding or deleting a small data fraction substantially faster than retraining.
- This is the first work to introduce an in-place unified incremental and decremental learning approach for GBDT, enabling **real-time addition and deletion** of data within the model without training from scratch.

[[Paper](https://arxiv.org/abs/2502.01634), [Code](https://github.com/huawei-lin/InplaceOnlineGBDT)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2024</div><img src='images/researchExpImg/DMin_overview.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**DMin: Scalable Training Data Influence Estimation for Diffusion Models** 
- We introduce DMin, a scalable influence estimation framework for diffusion models that efficiently identifies the most influential training samples for a given test generation **in seconds**.
- DMin is the first **highly scalable framework** that enables stable influence estimation on diffusion models with billions of parameters.
- To overcome storage and computational limitations, DMin employs a gradient compression technique, reducing storage from around **40 GB to 80 KB** per sample while maintaining accuracy, enabling feasible influence estimation on large models and datasets.

[[Paper](https://arxiv.org/abs/2412.08637), [Code](https://github.com/huawei-lin/DMin)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/researchExpImg/RapidIn_overview.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Token-wise Influential Training Data Retrieval for Large Language Models** 
- We present RapidIn that **estimates the influence** of each training data for a given LLM generation.
- We apply a collection of techniques to cache the gradients of LLMs by compressing gradient vectors by over **200,000x** in the caching stage, and achieve a **6,326x** speedup in the retrieval stage, enabling estimating the influence of the entire dataset for any test generation within minutes.
- We utilize **multi-GPU parallelization** to substantially accelerate the caching and retrieval.

[[Paper](https://aclanthology.org/2024.acl-long.48/), [Code](https://github.com/huawei-lin/RapidIn), [Poster](https://drive.google.com/file/d/1xX5z5L74_WACKMjo3c2T7AXmfuEQGMLZ/view?usp=sharing), [Slides](https://drive.google.com/file/d/1dS3GrD9z2INOZZ84zBpXlgM0Fbs0-XVt/view?usp=sharing), [Video](https://www.youtube.com/watch?v=B5XO7b5jHWU)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD 2023</div><img src='images/researchExpImg/GBDTunlearning.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Machine Unlearning in Gradient Boosting Decision Trees (GBDT)** 
- Propose an unlearning framework that efficiently and effectively unlearns a given collection of data **without retraining** the model from scratch.
- Introduce a collection of techniques, including random split point selection and random partitioning layers training, to the training process of the original tree models to ensure that the trained model requires few subtree retrainings during the unlearning.
- To the best of our knowledge, this is the **first work** that considers machine unlearning on GBDT.

[[Paper](https://dl.acm.org/doi/10.1145/3580305.3599420), [Code](https://github.com/huawei-lin/OnlineBoosting), [Slides](https://drive.google.com/file/d/10tW2yhb4KN8lzF7kLuiv3TuiGcZVY_Ye/view?usp=sharing), [Video](https://drive.google.com/file/d/1Z6Yt__cE1WUsutKMr0agOvihKKM0iezc/view?usp=sharing), [Poster](https://drive.google.com/file/d/1US2ISzh62dzb4vCdkICU99_a1iZOPL-B/view?usp=sharing)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">FG 2023</div><img src='images/researchExpImg/abstract_ECLoss.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Activation Template Matching Loss for Explainable Face Recognition** 
- Propose a novel method named Explainable Channel Loss (ECLoss) to construct an **explainable face recognition network**, which can **directly explain** that what face recognition networks have learned.  
- To the best of our knowledge, this is the **first method** to construct a feature level explainable face recognition network that does not require any additional dataset or manual annotation.  

[[Paper](https://arxiv.org/abs/2207.02179), [Slides](https://drive.google.com/file/d/1Ax8IrluTPnQXBLMgfP4DLSyxwwbMEbN7/view?usp=sharing), [Video](https://drive.google.com/file/d/1z6NpJFiIeZarlte1Uae7k-9ylisulDho/view?usp=share_link)]

</div>
</div>



# Internship Experience

**Amazon - AGI (Foundation Models)**, Boston, MA  
May 2024 - Present  
Applied Scientist Intern | Advisor: [Rajath Kumar](https://scholar.google.com/citations?user=sI0wlX8AAAAJ), [Raphael Petegrosso](https://scholar.google.com/citations?user=fqDBr9gAAAAJ)
- Responsible for an Auto Prompting project on LLMs inference.
- Proposed an unsupervised self-improving framework for LLMs inference that enhances generation quality
across various downstream tasks. The proposed framework can generate multiple diverse outputs and detect
potential hallucinations by certainty score.
- The paper draft was submitted for internal review.
<br />


**Shenzhen University - Institute of Computer Vision**, Shenzhen, China  
July 2021 - July 2022  
Research Assistant | Supervisor: Prof. [Linlin Shen](https://scholar.google.com/citations?user=AZ_y9HgAAAAJ&hl=en&oi=ao)  
- Responsible for **interpretability and explainability** on deep learning, especially on Biometrics.  
- Propose a novel method named Explainable Channel Loss (ECLoss) to construct an **explainable face recognition** network, which can **directly explain** that what face recognition networks have learned.
- To the best of our knowledge, this is the **first method** to construct a feature level explainable face recognition network that does not require any additional dataset or manual annotation.
<br />


**ByteDance Inc. - AI Lab**, Beijing, China  
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

## Conference Reviewer
- NeurIPS 2025
- ICML 2025
- ICLR 2025
- ACL ARR 2024, 2025
- KDD: 2024, 2025
- NeurIPS 2023 GLFrontiers Workshop

## Journal Reviewer
- IEEE Transactions on Dependable and Secure Computing
- IEEE Access


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

