layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume

{% include base_path %}

## Education

- **MSc, Artificial Intelligence & Big Data Computing**, The Hong Kong Polytechnic University, Hong Kong SAR (09/2023–01/2025)  
  GPA 3.34/4.0, Rank 10/44
- **BEng, Cyber Engineering**, Dalian University of Technology (Project 985/211), Dalian, China (09/2019–06/2023)  
  GPA 84.2/100, Rank 48/119

## Research Experience

### Research Assistant, Prof. Wei Wang’s Lab (01/2025–present), Guangzhou, China
- Build a tripartite NSFC grant rewriting workflow combining lexical, paragraph, and structural optimization for entity-preserving style transfer.
- Develop beam-search-enhanced thought-chain generators via DeepSeek Reasoner and design position-aware mapping to enforce NSFC structural compliance.
- Curate annotated paraphrase databases and multi-agent collaboration tags to expand domain knowledge and prompt clusters.

### Efficient Federated Learning for LLM Fine-tuning (01/2024–01/2025), Hong Kong SAR  
Supervisor: [Dr. Zhaorui Zhang](https://www.polyu.edu.hk/comp/people/academic-staff/dr-zhang-zhaorui/)
- Proposed **SplitFT**, an adaptive split learning system for GPT-2-sized models that tunes client cut layers according to data quality and post-round perplexity.
- Integrated LoRA-based parameter-efficient tuning with selective rank control, reducing client bandwidth usage while improving non-IID accuracy by 6%.
- Benchmarked LoRA split federated learning across heterogeneous token-length datasets using Dirichlet and IID sampling; first-author paper submitted to IJCAI.

### Personalized Device–Cloud Recommendation System (12/2022–06/2023), Dalian, China  
Supervisor: [Prof. Weifeng Sun](http://faculty.dlut.edu.cn/wfsun/zh_CN/index.htm)
- Designed a hybrid news recommender that balances device and cloud computation, mixing ItemCF/UserCF/YouTubeDNN recalls with cold-start handling.
- Replaced memory-heavy similarity stages with embedding-based matrices and engineered a multi-factor rerank (accuracy, freshness, popularity) to sustain engagement.

## Course Projects

- **Different LoRA Schedules for BERT Fine-tuning (02/2024–04/2024)** — Investigated partial-module LoRA strategies with [Dr. Bo Yang](https://www.polyu.edu.hk/comp/people/academic-staff/dr-yang-bo/); showed comparable accuracy with 2–7× fewer transmitted parameters.
- **Characterizing Browser-based Crypto Mining (09/2023–12/2023)** — With [Dr. Xiapu Luo](https://www4.comp.polyu.edu.hk/~csxluo/) and [Prof. Hao Zhou](https://moonzhh.github.io/), captured malicious scripts via Wireshark, static/dynamic signatures, and CPU trend analysis to propose detection heuristics.
- **Survey of Vector Databases in the LLM Era (09/2023–12/2023)** — Summarized 50+ papers for [Prof. Qing Li](https://www.polyu.edu.hk/comp/people/academic-staff/prof-li-qing/), covering indexing, query strategies, and LLM-aligned applications.

## Awards

- Huawei Future Star Award (Top 2%, 2021–2022)
- Second Prize of Social Practice at DUT (Twice, Top 1.5%, 2020–2021)
- Excellent Student & Student Leader Prizes (Twice, Top 1.5%, 2020–2021)
- Third Prize, Asia and Pacific Mathematical Contest in Modeling (2020)
- Community Contribution Award (Top 3%, 2020–2021)

## Leadership & Service

- President, Huawei Smart Base Association, Dalian (09/2022–09/2023)
- Leader, Social Practice Team, Dalian (01/2020–12/2022)
- Minister, Student Committee of Software Technology School, Dalian (09/2021–06/2022)

## Skills

- **Languages:** English (IELTS 6.5), Mandarin (native)
- **Programming:** Python (NumPy, Pandas), Java, C++, MATLAB
- **Specialized tools:** LoRA & federated learning pipelines, Wireshark/network forensics, intelligent recommender system development

## Publications

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

## Talks

<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html  %}
{% endfor %}</ul>

## Teaching

<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
