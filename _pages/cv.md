---
layout: archive
title: "<span class='lang-zh'>简历</span><span class='lang-en'>CV</span>"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
{% include base_path %}

<div class="lang-zh" markdown="1">

## 教育背景

### 萨塞克斯大学（University of Sussex）- 人工智能与自适应系统 - 硕士

2024.09 – 2026.01

- **核心课程：**图像处理、自然语言处理、机器学习、动物与机器智能、智能系统技术、自适应系统、Python 编程
- **毕业论文：**Multi-Branch 3D Brain Tumor Segmentation: Integrating VAE Reconstruction and Uncertainty Quantification for Enhanced Clinical Decision Support

### 烟台大学 - 智能科学与技术 - 学士

2020.09 – 2024.06

- **GPA：**3.21/5.0（83.84/100）
- **毕业论文：**基于深度学习的用户表情识别系统
- **校内经历：**蓝翼青年志愿者协会副会长，组织开展数十次志愿服务活动

## 实习经历

### 海康威视 - 海康机器人｜产品技术支持工程师（AI 应用开发）

2025.11 – 2026.01

- 基于 YOLO 的器具智能分类识别系统（货架/料车/托盘等约 45 类）；负责数据标注规范、数据清洗、迁移学习与超参数优化，结合数据增强提升识别效果
- 使用 FastAPI 搭建推理服务与 RESTful API，提供批量识别接口与 Web 可视化界面
- 将识别结果接入 AMR 问答机器人，结合内部文档知识库，支持基于 RAG 的业务问答场景
- 开发 MaaS 平台 Excel 智能分析系统（Flask Web + SSE），实现万条级记录批量处理/分类，支持 Plotly 交互看板与 ReportLab PDF 报告生成
- 维护企业智能知识库平台（澜智/MaaS），参与知识库建立、上传、分类管理与文档整理

### 山东诺瑞特智能科技有限公司｜软件技术开发工程师

2023.07 – 2023.08

- 参与智能热水器控制器软件开发，提出并参与设计语音控制原型，集成语音识别 API 实现指令解析与语音反馈
- 设计 OCR 智能发票识别原型方案，自动读取票据信息并写入 ERP 管理系统

## 技能

- **Kaggle Expert：**Kaggle 排名 885 / 203347
- **编程/框架：**Python（PyTorch）、C、R、MySQL
- **英语：**CET-6，硕士期间全英文授课，能够无障碍阅读英文技术文档
- **学术服务：**IEEE SMC 2025（CCF C 类）会议审稿人
- **智能体平台：**Coze、Dify；擅长提示词工程与工作流设计并与 Python 程序结合
- **RPA：**影刀高级 RPA 技能证书
- **版本控制：**Git（分支管理、合并策略、冲突解决），具备团队协作与开源协作经验
- **数据科学：**数据预处理、特征工程、EDA、建模与可视化（pandas、Plotly 等）

## 竞赛获奖

- Kaggle Yale/UNC-CH - Geophysical Waveform Inversion 团队银牌（Top 5%，60/1388）
- Kaggle ARC Prize 2025 个人铜牌（Top 8%，109/1454）
- Kaggle BirdCLEF+ 2025 个人铜牌（Top 9%，168/2025）

## 项目经历

### 基于 Coze 平台的小说推文视频生成系统

- 构建多节点协同工作流：第二人称转换、智能分镜、图像生成、语音合成等，实现从小说文本到剪映草稿的自动化生成
- 设计分镜生成与提示词构造流程，集成语音合成与图像生成节点，并通过剪映插件自动创建草稿并批量处理

### 基于 Dify 平台的智能小红书内容创作专家系统

- 通过提示词工程与工作流实现从主题输入到图文内容的自动化生成
- 集成搜索/文案生成/图像生成/封面排版等节点，提升内容曝光与互动

### 基于机器学习的国际象棋与基于强化学习的奇偶游戏智能决策系统

- 决策树/KNN 等模型对国际象棋走法分类，从 FEN 提取 15 个特征，测试集准确率 84%，ROC AUC 0.9126
- 强化学习框架：Value Iteration 与 Q-learning 求解奇偶游戏，Value Iteration 2 次迭代收敛；Q-learning 3000 轮训练达到 80% 策略一致性

### 基于计算机视觉的颜色矩阵识别系统

- HSV 空间鲁棒颜色识别 + 自适应阈值/形态学处理，实现 4×4 彩色矩阵定位与识别
- 四点透视变换校正 + 黑色标记点自动检测与筛选，提升在倾斜/畸变场景下的准确性

### 共享单车需求预测

- 构建时间/天气/节假日等特征工程，对比随机森林与 SVM，使用网格搜索优化超参数，输出需求预测支持调度

### 电商广告投放效果分析与客户细分

- OneHotEncoder + MinMaxScaler 处理 889 个渠道 13 维特征，KMeans 聚类并用轮廓系数选择 4 类（0.502），识别高转化/精准/流量/低效渠道，为投放优化提供依据

## 出版物

<ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

</div>

<div class="lang-en" markdown="1">

## Education

### University of Sussex - M.S. in Artificial Intelligence and Adaptive Systems

2024.09 – 2026.01

- **Core Courses:** Image Processing, Natural Language Processing, Machine Learning, Intelligence in Animals and Machines, Intelligent Systems Techniques, Adaptive Systems, Python Programming
- **Thesis:** Multi-Branch 3D Brain Tumor Segmentation: Integrating VAE Reconstruction and Uncertainty Quantification for Enhanced Clinical Decision Support

### Yantai University - B.S. in Intelligent Science and Technology

2020.09 – 2024.06

- **GPA:** 3.21/5.0 (83.84/100)
- **Thesis:** User Facial Expression Recognition System Based on Deep Learning
- **Activities:** Vice President of a volunteer association; organized dozens of volunteering events

## Internship Experience

### Hikvision Robotics - Product Technical Support Engineer (AI Application Development)

2025.11 – 2026.01

- Developed a YOLO-based equipment classification system (~45 categories). Defined labeling rules, cleaned datasets, fine-tuned a pretrained YOLO model and optimized hyperparameters with augmentation
- Built inference services and RESTful APIs with FastAPI; provided batch recognition APIs and a web visualization interface
- Integrated results into an AMR Q&A assistant with internal document knowledge base to support RAG-based business Q&A
- Built an Excel intelligent analysis system on MaaS (Flask Web + SSE) for large-scale batch processing, with Plotly dashboards and ReportLab PDF report generation
- Maintained enterprise knowledge base platforms (LanZhi/MaaS): building, uploading, categorizing, and documentation organization

### Shandong Norite Intelligent Technology Co., Ltd. - Software Development Engineer

2023.07 – 2023.08

- Contributed to smart water heater controller development; proposed a voice-control prototype integrating a speech recognition API for command parsing and voice feedback
- Designed an OCR invoice recognition prototype to extract fields and write into an ERP system

## Skills

- **Kaggle Expert:** Rank 885 / 203,347
- **Programming:** Python (PyTorch), C, R, MySQL
- **English:** CET-6; fully English-taught master program; able to read technical documentation fluently
- **Academic Service:** Reviewer for IEEE SMC 2025 (CCF-C)
- **Agent Platforms:** Coze, Dify; prompt engineering and workflow design integrated with Python
- **RPA:** Certified (Yingdao advanced)
- **Version Control:** Git (branching, merging, conflict resolution)
- **Data Science:** preprocessing, feature engineering, EDA, modeling, and visualization (pandas/Plotly)

## Awards

- Kaggle Yale/UNC-CH - Geophysical Waveform Inversion (Team Silver, Top 5%, 60/1388)
- Kaggle ARC Prize 2025 (Individual Bronze, Top 8%, 109/1454)
- Kaggle BirdCLEF+ 2025 (Individual Bronze, Top 9%, 168/2025)

## Projects

### Novel-to-Video Generation System (Coze)

- Built a multi-stage workflow (2nd-person rewriting, storyboard generation, text-to-image prompts, TTS) to automatically generate CapCut drafts from novels

### Xiaohongshu Content Creation Expert System (Dify)

- Implemented an automated workflow from topic input to full content generation via prompt engineering and workflow orchestration

### Chess Move Classification & Odd-Even Game Decision Making

- Trained decision tree / KNN models for chess move classification; extracted 15 features from FEN, achieved 84% accuracy and ROC AUC 0.9126
- Built a reinforcement learning framework (Value Iteration, Q-learning) for odd-even games; fast convergence and 80% policy consistency after 3000 episodes

### Color Matrix Recognition (Computer Vision)

- Implemented a robust 4×4 color matrix recognition pipeline with HSV-based classification, adaptive thresholding, and morphology
- Added perspective correction via four-point transform and marker detection to improve robustness under viewpoint distortions

### Bike Sharing Demand Forecasting

- Engineered temporal/weather/holiday features; compared Random Forest vs SVM, tuned hyperparameters via grid search for demand forecasting

### E-commerce Ad Performance Analytics & Customer Segmentation

- Processed 889 channels with 13-dim features; used OneHotEncoder and MinMaxScaler; applied KMeans and selected k=4 via Silhouette Score (0.502)

## Publications

<ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

</div>
