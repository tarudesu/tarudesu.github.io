---
permalink: /
title: ""
excerpt: ""
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

I am presently serving as a lecturer at the University of Information Technology, Vietnam National University Ho Chi Minh City. 
- As an undergraduate, I focused on social media text mining under the mentorship of [Dr. Kiet Van Nguyen](https://www.researchgate.net/profile/Kiet-Nguyen-14) and [Assoc. Prof. Ngan Luu-Thuy Nguyen](https://dblp.org/pid/174/4407.html).
- During my master's studies, I had the privilege of being supervised by [Prof. Sakriani Sakti](https://hai-lab.naist.jp/profile/ssakti/index.html), where I delved into zero-resource speech processing and speech-to-speech translation. This work sparked a profound interest in linguistics and motivated me to explore this field further.

Currently, I am passionate about leveraging AI to preserve and revive endangered languages. Also, my research is centered on the automatic generation of data to address the challenges of limited resources.

---

I am also <span style="color: #FF8C00; font-weight: bold;">exploring the possibility of enrolling in a Ph.D. program</span> in the Spring of 2025.

# 🔥 News
- *2024.08*: &nbsp;🎉🎉 I have started my role as a visiting scholar at [HRL Laboratory](https://hlr.github.io/team/) under the guidance of [Dr. Parisa Kordjamshidi](https://www.cse.msu.edu/~kordjams/) at Michigan State University, USA!
- *2024.06*: &nbsp;🎉🎉 Our paper "ViHateT5: Enhancing Hate Speech Detection in Vietnamese With A Unified Text-to-Text Transformer Model" has been accepted at [**ACL 2024**](https://2024.aclweb.org/) (Rank A*)!
- *2024.03:* &nbsp;🎉🎉 I was selected by the USAID PHER Visiting Scholar Program to receive funding for a research visit to a US institute!

# 📝 Publications 

## Conferences

- ViHateT5: Enhancing Hate Speech Detection in Vietnamese With A Unified Text-to-Text Transformer Model. **Luan Thanh Nguyen**. The 62nd Annual Meeting of the Association for Computational Linguistics (*ACL 2024*) [[Paper](https://arxiv.org/pdf/2405.14141), [GitHub](https://github.com/tarudesu/ViHateT5), [HuggingFace](https://huggingface.co/collections/tarudesu/vihatet5-vietnamese-hate-speech-detection-with-t5-66501594d93e8d70825a718e)] 

- Gendec: A Machine Learning-Based Framework for Gender Detection from Japanese Names. Duong Tien Pham, **Luan Thanh Nguyen**. The International Conference on Intelligent Systems Design and Applications (*ISDA 2023*) [[Paper](https://arxiv.org/pdf/2311.11001), [HuggingFace](https://huggingface.co/collections/tarudesu/gendec-gender-detection-from-japanese-names-65e0a5b9a0c6304cf49a99ed)] 

- VGSAlign: Bilingual Speech Alignment of Unpaired and Untranscribed Languages using Self-Supervised Visually Grounded Speech Models. **Luan Thanh Nguyen**, Sakriani Sakti. The 2nd Annual Meeting of the Special Interest Group on Under-resourced Languages (*SIGUL 2023*) [[Paper](https://www.isca-archive.org/sigul_2023/nguyen23_sigul.pdf)]

- SMTCE: A Social Media Text Classification Evaluation Benchmark and BERTology Models for Vietnamese. **Luan Thanh Nguyen**, Kiet Van Nguyen, Ngan Luu-Thuy Nguyen. The 36th Pacific Asia Conference on Language, Information and Computation (*PACLIC 2022*) [[Paper](https://aclanthology.org/2022.paclic-1.31.pdf)]

- SPBERTQA: A Two-Stage Question Answering System Based on Sentence Transformers for Medical Texts. Nhung Thi-Hong Nguyen, Phuong Phan-Dieu Ha, **Luan Thanh Nguyen**, Kiet Van Nguyen, and Ngan Luu-Thuy Nguyen. The 15th International Conference on Knowledge Science, Engineering and Management (*KSEM 2022*) [[Paper](https://arxiv.org/pdf/2206.09600), [Dataset](https://huggingface.co/datasets/tarudesu/ViHealthQA)]

- SA2SL: From Aspect-Based Sentiment Analysis to Social Listening System for Business Intelligence. Luong Luc Phan, Phuc Huynh Pham, Kim Thi-Thanh Nguyen, Sieu Khai Huynh, Tham Thi Nguyen, **Luan Thanh Nguyen**, Tin Van Huynh, and Kiet Van Nguyen. The 14th International Conference on Knowledge Science, Engineering and Management (*KSEM 2021*) [[Paper](https://arxiv.org/pdf/2105.15079), [GitHub & Dataset](https://github.com/LuongPhan/UIT-ViSFD)]

- UIT-E10dot3 at SemEval-2021 Task 5: Toxic Spans Detection with Named Entity Recognition and Question-Answering Approaches. Phu Gia Hoang, **Luan Thanh Nguyen**, and Kiet Van Nguyen. The 15th International Workshop on Semantic Evaluation (*SemEval-2021*) [[Paper](https://aclanthology.org/2021.semeval-1.125.pdf)]

- Vietnamese Complaint Detection on E-Commerce Websites. Nhung Thi-Hong Nguyen, Phuong Phan-Dieu Ha, **Luan Thanh Nguyen**, Kiet Van Nguyen, and Ngan Luu-Thuy Nguyen. The 20th International Conference on New Trends in Intelligent Software Methodologies, Tools and Techniques (*SoMeT 2021*) [[Paper](https://arxiv.org/pdf/2104.11969), [Dataset](https://huggingface.co/datasets/tarudesu/ViOCD)]

- Constructive and Toxic Speech Detection for Open-Domain Social Media Comments in Vietnamese. **Luan Thanh Nguyen**, Kiet Van Nguyen, and Ngan Luu-Thuy Nguyen. The 34th International Conference on Industrial, Engineering & Other Applications of Applied Intelligent Systems (*IEA/AIE 2021*) [[Paper](https://arxiv.org/pdf/2103.10069), [GitHub](https://github.com/tarudesu/ViCTSD), [Dataset](https://huggingface.co/datasets/tarudesu/ViCTSD)]

- BANANA at WNUT-2020 Task 2: Identifying COVID-19 Information on Twitter by Combining Deep Learning and Transfer Learning Models. Tin Van Huynh, **Luan Thanh Luan**, and Son T. Luu. The Sixth Workshop on Noisy User-generated Text (*W-NUT 2020*) [[Paper](https://aclanthology.org/2020.wnut-1.50.pdf)]

## Journals
- VLSP 2021-ViMRC Challenge: Vietnamese Machine Reading Comprehension. Kiet Van Nguyen, Son Quoc Tran, **Luan Thanh Nguyen**, Tin Van Huynh, Son T. Luu, Ngan Luu-Thuy Nguyen. VNU Journal of Science: Computer Science and Communication Engineering (*Volume 38*) [[Paper](https://jcsce.vnu.edu.vn/index.php/jcsce/article/view/340), [Website](https://vlsp.org.vn/vlsp2021/eval/mrc)]

## In-progress
- CENSOR - Hide What You Don’t Like! End-to-End Audio-based Toxic Spans Detection. **Luan Thanh Nguyen**. (Under review)

- ZeST: A Zero-resourced Speech-to-Speech Translation Approach for Unknown, Unpaired, and Untranscribed Languages. Sakriani Sakti, **Luan Thanh Nguyen**. (Under review)

# 🎖 Honors and Awards
- *2024:* “USAID PHER Visiting Scholar Program” by [USAID Partnership for Higher Education Reform](https://phervietnam.org/), USA.
- *2022:* “Collaborative Education Program Scholarship” by [Japan Advanced Institute of Science and Technology](https://www.jaist.ac.jp/english/), Japan.
- *2022:* “Excellent Achievement in Scientific Research and Achieved Scholarship for Master Program” by [INSTITUTE OF BIG DATA, VinGroup Innovation Foundation (VinIF)](https://vinif.org/en/), Vietnam.
- *2021:* “Typical 5-Good Students of Vietnam National University” by [Vietnam National University Ho Chi Minh City](https://vnuhcm.edu.vn/), Vietnam.
- *2021:* “Good achievement in scientific research” by [Vietnam National University Ho Chi Minh City](https://vnuhcm.edu.vn/), Vietnam.
- *2020:* “Short-term Exchange Student Program between UIT and Saga
University”, Japan - IPP 2020 by [Saga University](https://www.saga-u.ac.jp/en/), Japan.
- *2018*: “Third place winner in UIT Young Creative Idea” by [UIT @ Vietnam National University Ho Chi Minh City](https://en.uit.edu.vn/), Vietnam.
- *2017*: "Third place winner in UIT Singing Festival" by [UIT @ Vietnam National University Ho Chi Minh City](https://en.uit.edu.vn/), Vietnam.

# 📖 Educations
---
### Master of Science in Information Science
- **Location:** Japan Advanced Institute of Science and Technology  
- **Duration:** 2021 - 2023  
- **Thesis:** Zero-resourced Speech-to-Speech Translation for Unpaired and Untranscribed Languages Based on Visually Grounded Self-Supervised Speech Models  
- **Grade:** 100/100  
- **Supervisor:** [Prof. Sakriani Sakti](https://hai-lab.naist.jp/profile/ssakti/index.html)  
- **Awards:**
  - "Outstanding Dedications and Contributions in Research" by HA3CI Laboratory, JAIST. 2023.

### Bachelor of Science in Information Technology
- **Location:** University of Information Technology, Vietnam National University Ho Chi Minh City  
- **Duration:** 2017 - 2021  
- **Thesis:** Constructive and Toxic Speech Detection for Open-domain Social Media Comments in Vietnamese  
- **Grade:** 9.9/10  
- **Supervisor:** [Dr. Kiet Van Nguyen](https://www.researchgate.net/profile/Kiet-Nguyen-14)  
- **Awards:**
  - Valedictorian graduation (Top 1%).
  - "Best Thesis Defense Award" by The Faculty of Information Science and Engineering, UIT, VNU-HCM. 2021.


# 📚 Research Projects
- *2024 - 2026:* Textless Approaches To Vietnamese Direct Speech-To-Speech Translation. Principal Investigator. VNU-HCM Project (C2024-26-10). (In progress)

# 💻 Professional Experiences
- *2024.08 - 2024.11:* Visiting Scholar at HRL Laboratory, Michigan State University. USA.
- *2024.04 - Present:* Lecturer at UIT, VNU-HCM. Vietnam.
- *2022.10 - 2023.09:* Laboratory Assistant at HA3CI Laboratory, JAIST. Japan.
- *2021.10 - 2024.03:* Teaching Assistant at UIT, VNU-HCM. Vietnam.
- *2020.09 - 2021.06:* Student Teaching Assistant at UIT, VNU-HCM. Vietnam.
- *2020.03:* Short-term Exchange Student at Saga University. Japan.
