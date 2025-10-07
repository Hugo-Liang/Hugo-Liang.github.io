---
layout: archive
title: "CV-zh"
permalink: /cv-zh/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

教育经历
======
* 华东理工大学，计算机科学与技术，博士，2023.09-2026.06（预计）
  * <strong>平均绩点</strong>：3.55/4.0
  * <strong>奖励与荣誉</strong>: “华为杯”第二十届中国研究生数学建模竞赛三等奖; 优秀学生干部、优秀社会工作
* 华东理工大学，计算机科学与技术，硕士，2021.09-2023.06
  * <strong>平均绩点</strong>：3.44/4.0
  * <strong>外语能力</strong>: CET-6<sub>(539)</sub>，听说良好，读写熟练 
* 郑州轻工业大学，软件工程，本科，2015.09-2019.06
  * <strong>平均绩点</strong>：3.57/4.0
  * <strong>奖励与荣誉</strong>: 国家励志奖学金, 国家奖学金, 2018年全国大学生英语竞赛（NECCS）C类一等奖; 河南省三好学生, 河南省优秀毕业生

论文发表
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

项目经历
======
* 东方证券代码质量智能评估及开源治理方法，负责人，2024.10.01 -> 2025.09.23
  * <strong>项目背景</strong>：针对公司外包人员的异常代码提交检测与软件成分分析。
  * <strong>主要工作</strong>：
    * 使用PTM将提交文件的代码变更内容向量化，结合字符串相似度与向量相似度计算，基于阈值筛选精确与近似相似的文件级代码变更，支持后续人工标注。
    * 基于文件提交信息、相似度特征与标注结果，构建文件级Java代码克隆数据集；在此基础上完成机器学习模型的训练、调参、特征工程、评估与部署，并将预测结果聚合至提交级进行异常检测。
    * 探索将PTM与LLM应用于原始代码变更内容的微调，在文件级克隆数据集上进行性能评估与部署可行性分析。当前基于ML与PTM的异常提交检测系统已在生产环境落地，精确度达到85%。

* 东方证券代码质量智能评估方法，成员/负责人，2023.10.01 -> 2024.09.30
  * <strong>项目背景</strong>：针对公司各部门外包人员的重复与相似代码提交进行自动化检测与趋势分析。
  * <strong>主要工作</strong>：
    * 基于PyDriller与Multiprocessing并行提取项目仓库的历史提交记录，提升数据预处理效率。
    * 从提交中抽取涉及文件与标识符，计算两两提交的Jaccard相似度，并通过阈值筛选识别标识符相似或涉及文件重复的代码提交对。
    * 借助Java 代码度量工具（CK）计算提交后的内聚、耦合与复杂度指标，结合指标随提交变化的趋势，辅助识别存在重复文件或相似代码的提交行为。

工作经历
======
* IT运维工程师，2021.04.19 -> 2025.09.10
  * [中智上海经济技术合作有限公司](https://www.ciicsh.com/ciicsh/zjzz281/zzsh/index.html)
  * <strong>工作内容</strong>: 
    * 驻场[西门子医疗系统有限公司](https://www.siemens-healthineers.cn/)，为员工提供日常办公技术支持，并负责供应商对接、机房与服务器维护。
    * 负责办公设备（笔记本、工作站等）的日常维护，包括资产管理、故障排查与硬件更换。
    * 执行操作系统与办公软件的安装、初始化配置、问题诊断与修复，保障办公环境的稳定与高效运行。

* 技术支持工程师，2019.04.15 -> 2019.08.01（实习） -> 2020.07.10（在职）
  * [上海微创软件股份有限公司](https://www.wicresoft.com/aboutUs.html)
  * <strong>工作内容</strong>: 
    * 代表微软团队，通过邮件为全球客户提供Microsoft 产品与服务技术支持，工作语言以英语为主。
    * 服务对象涵盖企业、商业、教育机构（国内外）及个人用户（海外），支持场景广泛。
    * 主要支持产品包括桌面端（Windows / macOS）与移动端（Android / iOS）的SharePoint Online、OneDrive for Business、Teams及相关Microsoft 365 订阅服务。
    * 根据客户需求提供解决方案，收集并验证客户反馈，及时向相关团队提交热点问题与服务故障。

  
个人技能
======
* <strong>软件质量保障与代码智能分析</strong>：具备软件缺陷预测、缺陷报告严重性分级、漏洞检测等研究与实践经验。熟悉代码理解与生成相关任务，包括代码提交分类、代码克隆检测、漏洞补丁识别与代码摘要生成。了解静态程序分析方法与常用工具。
* <strong>机器学习与大模型应用</strong>：掌握经典ML方法（LR、GBDT、MLP）、DL方法（TextCNN、LSTM、Transformer）与PTM（BERT、BART、T5）及相关优化策略（特征工程、模型集成、超参调优、特征提取、可解释性分析）。具备LLM（Llama、DeepSeek等）使用与LoRA微调经验（基于Llama-Factory + vLLM）。
* <strong>数据分析与建模</strong>：熟练使用 Python 进行数据处理与可视化（NumPy、Pandas、SciPy、Matplotlib）。熟悉模型训练、微调与测试框架搭建和调优（Scikit-learn、PyTorch、Transformers）。掌握统计学显著性检验与效应量分析方法。
* <strong>测试与系统运维</strong>：具备软件测试、数据库及网络相关知识，熟悉Pytest、Wireshark等工具，能够进行代码与网络问题分析。熟悉Windows / Linux系统，了解macOS；具备软硬件维护与故障排查能力，可独立完成硬件设备拆装。
* <strong>常用工具与软件</strong>：熟练使用Office、Acrobat办公软件。熟悉图像、视频与文本处理软件（CDR、PS、PR、Nero）。具备三维建模（3ds Max）与虚拟化平台（VMware、WSL）使用经验。


