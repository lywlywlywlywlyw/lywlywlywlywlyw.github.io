---
layout: archive
title: "<span class='lang-zh'>简历</span><span class='lang-en'>CV</span>"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
{% include base_path %}

<div class="lang-zh">

<div class="cv-card">
  <h2><i class="fas fa-flask"></i> 研究兴趣</h2>
  <ul class="cv-chip-list">
    <li class="cv-chip">智能体（Agent）</li>
    <li class="cv-chip">工作流（Workflow）与编排</li>
    <li class="cv-chip">检索增强生成（RAG）</li>
  </ul>
</div>

<div class="cv-card">
  <h2><i class="fas fa-graduation-cap"></i> 教育背景</h2>

  <div class="cv-entry">
    <h3>萨塞克斯大学（University of Sussex）- 人工智能与自适应系统 - 硕士</h3>
    <div class="cv-meta">2024.09 – 2026.01</div>
    <ul>
      <li><strong>核心课程：</strong>图像处理、自然语言处理、机器学习、动物与机器智能、智能系统技术、自适应系统、Python 编程</li>
      <li><strong>毕业论文：</strong>Multi-Branch 3D Brain Tumor Segmentation: Integrating VAE Reconstruction and Uncertainty Quantification for Enhanced Clinical Decision Support</li>
    </ul>
  </div>

  <div class="cv-entry">
    <h3>烟台大学 - 智能科学与技术 - 学士</h3>
    <div class="cv-meta">2020.09 – 2024.06</div>
    <ul>
      <li><strong>GPA：</strong>3.21/5.0（83.84/100）</li>
      <li><strong>毕业论文：</strong>基于深度学习的用户表情识别系统</li>
      <li><strong>校内经历：</strong>蓝翼青年志愿者协会副会长，组织开展数十次志愿服务活动</li>
    </ul>
  </div>
</div>

<div class="cv-card">
  <h2><i class="fas fa-briefcase"></i> 实习经历</h2>

  <div class="cv-entry">
    <h3>海康威视 - 海康机器人｜产品技术支持工程师（AI 应用开发）</h3>
    <div class="cv-meta">2025.11 – 2026.01</div>
    <ul>
      <li>基于 YOLO 的器具智能分类识别系统（货架/料车/托盘等约 45 类）；负责数据标注规范、数据清洗、迁移学习与超参数优化，结合数据增强提升识别效果</li>
      <li>使用 FastAPI 搭建推理服务与 RESTful API，提供批量识别接口与 Web 可视化界面</li>
      <li>将识别结果接入 AMR 问答机器人，结合内部文档知识库，支持基于 RAG 的业务问答场景</li>
      <li>开发 MaaS 平台 Excel 智能分析系统（Flask Web + SSE），实现万条级记录批量处理/分类，支持 Plotly 交互看板与 ReportLab PDF 报告生成</li>
      <li>维护企业智能知识库平台（澜智/MaaS），参与知识库建立、上传、分类管理与文档整理</li>
    </ul>
  </div>

  <div class="cv-entry">
    <h3>山东诺瑞特智能科技有限公司｜软件技术开发工程师</h3>
    <div class="cv-meta">2023.07 – 2023.08</div>
    <ul>
      <li>参与智能热水器控制器软件开发，提出并参与设计语音控制原型，集成语音识别 API 实现指令解析与语音反馈</li>
      <li>设计 OCR 智能发票识别原型方案，自动读取票据信息并写入 ERP 管理系统</li>
    </ul>
  </div>
</div>

<div class="cv-card">
  <h2><i class="fas fa-cogs"></i> 技能</h2>
  <ul class="cv-chip-list">
    <li class="cv-chip">Python / PyTorch</li>
    <li class="cv-chip">FastAPI / Flask</li>
    <li class="cv-chip">Computer Vision</li>
    <li class="cv-chip">RAG</li>
    <li class="cv-chip">Coze / Dify</li>
    <li class="cv-chip">Plotly</li>
    <li class="cv-chip">Git</li>
  </ul>
  <ul>
    <li><strong>Kaggle Expert：</strong>Kaggle 排名 835 of 200,422</li>
    <li><strong>编程/框架：</strong>Python（PyTorch）、C、R、MySQL</li>
    <li><strong>英语：</strong>CET-6，硕士期间全英文授课，能够无障碍阅读英文技术文档</li>
    <li><strong>学术服务：</strong>IEEE SMC 2025（CCF C 类）会议审稿人</li>
    <li><strong>智能体平台：</strong>Coze、Dify；擅长提示词工程与工作流设计并与 Python 程序结合</li>
    <li><strong>RPA：</strong>影刀高级 RPA 技能证书</li>
    <li><strong>版本控制：</strong>Git（分支管理、合并策略、冲突解决），具备团队协作与开源协作经验</li>
    <li><strong>数据科学：</strong>数据预处理、特征工程、EDA、建模与可视化（pandas、Plotly 等）</li>
  </ul>
</div>

<div class="cv-card">
  <h2><i class="fas fa-award"></i> 竞赛获奖</h2>
  <ul>
    <li>Kaggle Yale/UNC-CH - Geophysical Waveform Inversion 团队银牌（Top 5%，60/1388）</li>
    <li>Kaggle ARC Prize 2025 个人铜牌（Top 8%，109/1454）</li>
    <li>Kaggle BirdCLEF+ 2025 个人铜牌（Top 9%，168/2025）</li>
  </ul>
</div>

<div class="cv-card">
  <h2><i class="fas fa-project-diagram"></i> 项目经历</h2>

  <div class="cv-entry">
    <h3>基于 Coze 平台的小说推文视频生成系统</h3>
    <ul>
      <li>构建多节点协同工作流：第二人称转换、智能分镜、图像生成、语音合成等，实现从小说文本到剪映草稿的自动化生成</li>
      <li>设计分镜生成与提示词构造流程，集成语音合成与图像生成节点，并通过剪映插件自动创建草稿并批量处理</li>
    </ul>
  </div>

  <div class="cv-entry">
    <h3>基于 Dify 平台的智能小红书内容创作专家系统</h3>
    <ul>
      <li>通过提示词工程与工作流实现从主题输入到图文内容的自动化生成</li>
      <li>集成搜索/文案生成/图像生成/封面排版等节点，提升内容曝光与互动</li>
    </ul>
  </div>

  <div class="cv-entry">
    <h3>基于机器学习的国际象棋与基于强化学习的奇偶游戏智能决策系统</h3>
    <ul>
      <li>决策树/KNN 等模型对国际象棋走法分类，从 FEN 提取 15 个特征，测试集准确率 84%，ROC AUC 0.9126</li>
      <li>强化学习框架：Value Iteration 与 Q-learning 求解奇偶游戏，Value Iteration 2 次迭代收敛；Q-learning 3000 轮训练达到 80% 策略一致性</li>
    </ul>
  </div>

  <div class="cv-entry">
    <h3>基于计算机视觉的颜色矩阵识别系统</h3>
    <ul>
      <li>HSV 空间鲁棒颜色识别 + 自适应阈值/形态学处理，实现 4×4 彩色矩阵定位与识别</li>
      <li>四点透视变换校正 + 黑色标记点自动检测与筛选，提升在倾斜/畸变场景下的准确性</li>
    </ul>
  </div>

  <div class="cv-entry">
    <h3>共享单车需求预测</h3>
    <ul>
      <li>构建时间/天气/节假日等特征工程，对比随机森林与 SVM，使用网格搜索优化超参数，输出需求预测支持调度</li>
    </ul>
  </div>

  <div class="cv-entry">
    <h3>电商广告投放效果分析与客户细分</h3>
    <ul>
      <li>OneHotEncoder + MinMaxScaler 处理 889 个渠道 13 维特征，KMeans 聚类并用轮廓系数选择 4 类（0.502），识别高转化/精准/流量/低效渠道，为投放优化提供依据</li>
    </ul>
  </div>
</div>

{% assign cv_pubs = site.publications | where: "published", true %}
{% if cv_pubs and cv_pubs.size > 0 %}

<div class="cv-card">
  <h2><i class="fas fa-book"></i> 出版物</h2>
  <ul>{% for post in cv_pubs reversed %}
      {% include archive-single-cv.html %}
    {% endfor %}</ul>
</div>
{% endif %}

</div>

<div class="lang-en">

<div class="cv-card">
  <h2><i class="fas fa-flask"></i> Research Interests</h2>
  <ul class="cv-chip-list">
    <li class="cv-chip">Agents</li>
    <li class="cv-chip">Workflow orchestration</li>
    <li class="cv-chip">RAG (retrieval-augmented generation)</li>
  </ul>
</div>

<div class="cv-card">
  <h2><i class="fas fa-graduation-cap"></i> Education</h2>

  <div class="cv-entry">
    <h3>University of Sussex - M.S. in Artificial Intelligence and Adaptive Systems</h3>
    <div class="cv-meta">2024.09 – 2026.01</div>
    <ul>
      <li><strong>Core Courses:</strong> Image Processing, Natural Language Processing, Machine Learning, Intelligence in Animals and Machines, Intelligent Systems Techniques, Adaptive Systems, Python Programming</li>
      <li><strong>Thesis:</strong> Multi-Branch 3D Brain Tumor Segmentation: Integrating VAE Reconstruction and Uncertainty Quantification for Enhanced Clinical Decision Support</li>
    </ul>
  </div>

  <div class="cv-entry">
    <h3>Yantai University - B.S. in Intelligent Science and Technology</h3>
    <div class="cv-meta">2020.09 – 2024.06</div>
    <ul>
      <li><strong>GPA:</strong> 3.21/5.0 (83.84/100)</li>
      <li><strong>Thesis:</strong> User Facial Expression Recognition System Based on Deep Learning</li>
      <li><strong>Activities:</strong> Vice President of a volunteer association; organized dozens of volunteering events</li>
    </ul>
  </div>
</div>

<div class="cv-card">
  <h2><i class="fas fa-briefcase"></i> Internship Experience</h2>

  <div class="cv-entry">
    <h3>Hikvision Robotics - Product Technical Support Engineer (AI Application Development)</h3>
    <div class="cv-meta">2025.11 – 2026.01</div>
    <ul>
      <li>Developed a YOLO-based equipment classification system (~45 categories). Defined labeling rules, cleaned datasets, fine-tuned a pretrained YOLO model and optimized hyperparameters with augmentation</li>
      <li>Built inference services and RESTful APIs with FastAPI; provided batch recognition APIs and a web visualization interface</li>
      <li>Integrated results into an AMR Q&A assistant with internal document knowledge base to support RAG-based business Q&A</li>
      <li>Built an Excel intelligent analysis system on MaaS (Flask Web + SSE) for large-scale batch processing, with Plotly dashboards and ReportLab PDF report generation</li>
      <li>Maintained enterprise knowledge base platforms (LanZhi/MaaS): building, uploading, categorizing, and documentation organization</li>
    </ul>
  </div>

  <div class="cv-entry">
    <h3>Shandong Norite Intelligent Technology Co., Ltd. - Software Development Engineer</h3>
    <div class="cv-meta">2023.07 – 2023.08</div>
    <ul>
      <li>Contributed to smart water heater controller development; proposed a voice-control prototype integrating a speech recognition API for command parsing and voice feedback</li>
      <li>Designed an OCR invoice recognition prototype to extract fields and write into an ERP system</li>
    </ul>
  </div>
</div>

<div class="cv-card">
  <h2><i class="fas fa-cogs"></i> Skills</h2>
  <ul class="cv-chip-list">
    <li class="cv-chip">Python / PyTorch</li>
    <li class="cv-chip">FastAPI / Flask</li>
    <li class="cv-chip">Computer Vision</li>
    <li class="cv-chip">RAG</li>
    <li class="cv-chip">Coze / Dify</li>
    <li class="cv-chip">Plotly</li>
    <li class="cv-chip">Git</li>
  </ul>
  <ul>
    <li><strong>Kaggle Expert:</strong> Rank 835 of 200,422</li>
    <li><strong>Programming:</strong> Python (PyTorch), C, R, MySQL</li>
    <li><strong>English:</strong> CET-6; fully English-taught master program; able to read technical documentation fluently</li>
    <li><strong>Academic Service:</strong> Reviewer for IEEE SMC 2025 (CCF-C)</li>
    <li><strong>Agent Platforms:</strong> Coze, Dify; prompt engineering and workflow design integrated with Python</li>
    <li><strong>RPA:</strong> Certified (Yingdao advanced)</li>
    <li><strong>Version Control:</strong> Git (branching, merging, conflict resolution)</li>
    <li><strong>Data Science:</strong> preprocessing, feature engineering, EDA, modeling, and visualization (pandas/Plotly)</li>
  </ul>
</div>

<div class="cv-card">
  <h2><i class="fas fa-award"></i> Awards</h2>
  <ul>
    <li>Kaggle Yale/UNC-CH - Geophysical Waveform Inversion (Team Silver, Top 5%, 60/1388)</li>
    <li>Kaggle ARC Prize 2025 (Individual Bronze, Top 8%, 109/1454)</li>
    <li>Kaggle BirdCLEF+ 2025 (Individual Bronze, Top 9%, 168/2025)</li>
  </ul>
</div>

<div class="cv-card">
  <h2><i class="fas fa-project-diagram"></i> Projects</h2>

  <div class="cv-entry">
    <h3>Novel-to-Video Generation System (Coze)</h3>
    <ul>
      <li>Built a multi-stage workflow (2nd-person rewriting, storyboard generation, text-to-image prompts, TTS) to automatically generate CapCut drafts from novels</li>
    </ul>
  </div>

  <div class="cv-entry">
    <h3>Xiaohongshu Content Creation Expert System (Dify)</h3>
    <ul>
      <li>Implemented an automated workflow from topic input to full content generation via prompt engineering and workflow orchestration</li>
    </ul>
  </div>

  <div class="cv-entry">
    <h3>Chess Move Classification & Odd-Even Game Decision Making</h3>
    <ul>
      <li>Trained decision tree / KNN models for chess move classification; extracted 15 features from FEN, achieved 84% accuracy and ROC AUC 0.9126</li>
      <li>Built a reinforcement learning framework (Value Iteration, Q-learning) for odd-even games; fast convergence and 80% policy consistency after 3000 episodes</li>
    </ul>
  </div>

  <div class="cv-entry">
    <h3>Color Matrix Recognition (Computer Vision)</h3>
    <ul>
      <li>Implemented a robust 4×4 color matrix recognition pipeline with HSV-based classification, adaptive thresholding, and morphology</li>
      <li>Added perspective correction via four-point transform and marker detection to improve robustness under viewpoint distortions</li>
    </ul>
  </div>

  <div class="cv-entry">
    <h3>Bike Sharing Demand Forecasting</h3>
    <ul>
      <li>Engineered temporal/weather/holiday features; compared Random Forest vs SVM, tuned hyperparameters via grid search for demand forecasting</li>
    </ul>
  </div>

  <div class="cv-entry">
    <h3>E-commerce Ad Performance Analytics & Customer Segmentation</h3>
    <ul>
      <li>Processed 889 channels with 13-dim features; used OneHotEncoder and MinMaxScaler; applied KMeans and selected k=4 via Silhouette Score (0.502)</li>
    </ul>
  </div>
</div>

{% assign cv_pubs = site.publications | where: "published", true %}
{% if cv_pubs and cv_pubs.size > 0 %}

<div class="cv-card">
  <h2><i class="fas fa-book"></i> Publications</h2>
  <ul>{% for post in cv_pubs reversed %}
      {% include archive-single-cv.html %}
    {% endfor %}</ul>
</div>
{% endif %}

</div>
