---
layout: archive
title: "CV-en"
permalink: /cv-en/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Computer Science and Technology, [**ECUST**](https://www.ecust.edu.cn/en/), Sep 2023 - Jun 2026 (expected)
  * **GPA**: 3.55/4.0
  * **Awards and Honors**: Third Prize in "HUAWEI Cup" The 20th China Post-Graduate Mathematical Contest in Modeling; Excellent Student Cadre、Social Work of ECUST
* M.S. in Computer Science and Technology, [**E**ast **C**hina **U**niversity of **S**cience and **T**echnology](https://www.ecust.edu.cn/en/), Sep 2021 - Jun 2023 
  * **GPA**: 3.44/4.0
  * **CET-6**: 539, proficient in reading and writing, good at listening and speaking 
* B.S. in Software Engineering, [**Z**heng**z**hou **U**niversity of **L**ight **I**ndustry](https://en.zzuli.edu.cn/), Sep 2015 - Jun 2019
  * **GPA**: 3.57/4.0
  * **Awards and Honors**: National Motivational Scholarship, National Scholarship, First Prize for Band C in 2018 National English Competition for College Students; Merit Student of Henan Province, Excellent Graduate of Henan Province

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

Project experience
======
* **[Orient Securities](https://www.dfzq.com.cn/osoa/views/english/home/index.shtml) Intelligent Code Quality Assessment and Open Source Governance Method**
  * **Role**: Project Lead, **Duration**: Oct 2024 – Sep 2025
    * **Project Background**: Detect anomalous code submissions from external contractors and analyzing software component composition.
    * **Main work**:
      * Utilize PTM to **vectorize code change contents from submissions**; computed both **string-based and vector-based similarities** to identify exact and approximate file-level code changes for manual labeling. 
      * **Construct a file-level Java code clone dataset** using submission metadata, similarity features, and labels; conducted **ML model training, hyperparameter tuning, feature engineering, evaluation, and deployment**, then aggregated file-level predictions to submission-level anomaly detection. 
      * Explore fine-tuning PTMs and Large Language Models (LLMs) directly on raw code changes, evaluated performance and deployment feasibility. The **ML + PTM-based anomaly detection system** has been deployed in production **with an accuracy of 85%**.

* **Orient Securities Intelligent Code Quality Assessment Method**
  * **Role**: Member / Project Lead, **Duration**: Oct 2023 – Sep 2024
    * **Project Background**: Develop an automated system for detecting duplicate and similar code submissions across departments from external contractors, and for analyzing long-term submission trends.
    * **Main work**:
      * Leverage **PyDriller and Multiprocessing** to parallelly extract historical commit records from multiple repositories, improving data preprocessing efficiency. 
      * Extract modified files and identifiers from each commit and computed pairwise **Jaccard similarity** to detect duplicate or similar submissions based on predefined thresholds.
      * Employ the **Java metrics tool (CK)** to calculate cohesion, coupling, and complexity metrics after each commit, using their temporal variation to assist in identifying potential duplicate or similar code behaviors.

Work experience
======
* **IT Operations Engineer**, Apr 2021 – Sep 2021
  * [China International Intellectech (Shanghai) Co., Ltd.](https://www.ciicsh.com/ciicsh/498473/498475/index.html)
  * **Duties**: 
    * Station at [Siemens Healthineers Ltd.](https://www.siemens-healthineers.com/), providing on-site technical support for employees, coordinating with external vendors, and maintaining server rooms and IT infrastructure.
    * Manage daily maintenance of office equipment (laptops, workstations, etc.), including asset management, troubleshooting, and hardware replacement.
    * Perform installation, initialization, configuration, and issue diagnosis of operating systems and office software to ensure a stable and efficient working environment.

* **Technical Support Engineer**, Intern: Apr 2019 – Aug 2019 • Full-time: Aug 2019 – Jul 2020
  * [Shanghai Wicresoft Company,. Ltd.](https://en.wicresoft.com/aboutUs.html)
  * **Duties**: 
    * Represent the Microsoft support team, providing technical support for Microsoft products and services via email communication in English.
    * Serve a diverse global user base including enterprise, commercial, educational (domestic and international), and individual clients.
    * Support both desktop (Windows / macOS) and mobile (Android / iOS) platforms for SharePoint Online, OneDrive for Business, Teams, and related Microsoft 365 subscription services.
    * Deliver tailored technical solutions based on customer requirements, collected and validated feedback, and escalated recurring or critical issues to relevant internal teams.

Campus experience
======
* [Graduate Affairs Office, Party Committee](https://gschool.ecust.edu.cn/12704/list.htm) in ECUST, Assistant, Oct 2021 – Sep 2023<br>
**Responsibilities**: Assist in handling the full range of graduate affairs, including admissions, scholarships, financial aid, housing management, and graduation procedures.
* [Computer Association](https://baike.baidu.com/item/%E9%83%91%E5%B7%9E%E8%BD%BB%E5%B7%A5%E4%B8%9A%E5%AD%A6%E9%99%A2%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%88%B1%E5%A5%BD%E8%80%85%E5%8D%8F%E4%BC%9A/15444041) of ZZULI, Director of Propaganda and Technical Departments, Oct 2016 – Oct 2018<br>
**Responsibilities**: Plan and organize technical workshops and volunteer repair activities to serve the university community.
* [Office of Career Planning and Employment Promotion for College Students](https://cs.zzuli.edu.cn/jycy/main.htm) in College of Computer and Communication Engineering, ZZULI, Deputy Director, Jul 2017 – Jul 2018<br>
**Responsibilities**: Organize graduate employment programs, coordinated campus recruitment events, and facilitated communication between enterprises and academic departments.
* [Entrepreneurship Center for College Students](http://123.57.15.95/?about/) in College of Computer and Communication Engineering, ZZULI, Deputy Director of Animation Department, Jun 2017 – Jun 2018<br>
**Responsibilities**: Manage external project collaborations, and trained and guided members to participate in computer design competitions.

Skills
======
* **Software Quality Assurance & Intelligent Code Analysis**: Experienced in software defect prediction, defect severity classification, and vulnerability detection. Familiar with code understanding and generation tasks, including commit classification, code clone detection, patch identification, and code summarization. Knowledgeable in static program analysis methods and common tools.
* **Machine Learning & Large Language Model Applications**: Proficient in classical **Machine Learning (ML)** methods (LR, GBDT, MLP), **Deep Learning (DL)** architectures (TextCNN, LSTM, Transformer), and **Pre-Trained Models (PTMs)** (BERT, BART, T5), with expertise in optimization strategies such as feature engineering, model ensemble, hyperparameter tuning, feature extraction, and interpretability analysis. Experienced in applying and fine-tuning **Large Language Models (LLMs)** (Llama, DeepSeek, etc.) using LoRA techniques based on <em>Llama-Factory</em> and <em>vLLM</em>.
* **Data Analysis & Modeling**: Skilled in **data processing and visualization** with Python (NumPy, Pandas, SciPy, Matplotlib). Experienced in **model training, fine-tuning, and evaluation** using frameworks such as Scikit-learn, PyTorch, and Transformers. Proficient in **statistical significance testing and effect size analysis**.
* **Testing & System Operations**: Knowledgeable in software testing, databases, and networking. Familiar with tools such as **Pytest and Wireshark** for code and network issue analysis. Proficient in Windows and Linux systems, with basic familiarity with macOS. Capable of **independent hardware maintenance and troubleshooting**.
* **Common Tools & Software**: Proficient in **Office and Acrobat** for documentation. Familiar with **text, image, and video processing software** (CorelDRAW, Photoshop, Premiere, Nero). Experienced in **3D modeling** (3ds Max) and **virtualization platforms** (VMware, WSL).


Self-Evaluation
======
* Positive and open-minded personality with strong communication and teamwork skills.
* Fast learner, able to quickly acquire new knowledge and apply it effectively in practical work.
* Detail-oriented and highly responsible, capable of maintaining consistent performance under pressure.
* Committed to continuous self-improvement, eager to take on new challenges, broaden knowledge, and enhance professional expertise.


