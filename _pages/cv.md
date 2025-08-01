---
layout: archive
title: "简历 / CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## 教育背景 / Education
======
* **四川大学软件学院** | School of Software Engineering, Sichuan University
  * 软件工程专业 | Software Engineering
  * 2023级本科生 | Class of 2023
  * 核心课程成绩 | Core Course Grades:
    - 数据结构与算法 (Data Structures & Algorithms): 95分
    - 程序设计 (Programming): 93分
    - 离散数学 (Discrete Mathematics): 90分

## 项目经历 / Projects
======

### 🏆 NUS暑期工作坊 | NUS Summer Workshop
* **Visual Computing小组** | Visual Computing Team
  * 时间：2025.4.22 - 2025.7.22
  * 成就：获得团队最佳人气奖和一等奖
  * 内容：参与新加坡国立大学视觉计算暑期工作坊，在团队协作中展现出色的技术能力和创新思维
  * 技术栈：计算机视觉、深度学习、团队协作

### 🔬 IDS LAB 四川大学 | IDS LAB, Sichuan University
* **LLM记忆系统安全研究** | LLM Memory System Security Research
  * 时间：2025.7.25 - 至今
  * 研究方向：LLM记忆系统模块的安全攻防
  * 内容：专注于大语言模型记忆系统的安全研究，探索记忆系统的攻击和防御机制
  * 技术栈：大语言模型、安全攻防、记忆系统

### 🤖 人工智能与计算机视觉 | AI & Computer Vision
* **CycleGAN改进项目** | Improved CycleGAN Project
  * 实现既能进行风格迁移又能从随机噪声生成动漫头像的图像生成系统
  * 基于PyTorch框架，改进CycleGAN架构
  * 技术栈：Python, PyTorch, OpenCV

* **OpenFace项目** | OpenFace Project
  * 使用CMake与Visual Studio构建特征提取工具
  * 与Python后端集成，实现人脸特征分析
  * 技术栈：C++, CMake, Python, OpenCV

### 🔒 AI系统与安全研究 | AI Systems & Security
* **记忆系统研究** | Memory Systems Research
  * 研究MemoryOS与mem0等记忆系统架构
  * 尝试迁移content poisoning攻击技术
  * 设计完整的攻击实验与评估逻辑
  * 精读多篇ASE、S&P等顶级会议论文

### 🎯 多模态交互系统 | Multimodal Interaction Systems
* **智能面试评测系统** | Intelligent Interview Evaluation System
  * 面向高校学生的多模态智能面试评测系统
  * 后端：Flask + MySQL，前端：Vue 3 + Element Plus
  * 集成讯飞API（语音识别、人脸识别）、OpenFace与大模型评分机制
  * 实现对面试过程的语音、表情和逻辑的综合分析

### 💾 数据库与事务管理 | Database & Transaction Management
* **事务调度系统** | Transaction Scheduling System
  * 实现支持Wound-Wait协议的事务调度系统
  * 包含事务表、锁表、等待队列与操作模拟等模块
  * 解决并发与死锁问题
  * 技术栈：Java, MySQL, 并发编程

### 📈 量化交易研究 | Quantitative Trading Research
* **增强型多因子交易策略** | Enhanced Multi-Factor Trading Strategy
  * 实现BollingerStrategy类
  * 结合布林通道、RSI、MACD与成交量确认
  * 实现多指标信号生成
  * 技术栈：Python, pandas, numpy, matplotlib

### 🚌 课程与团队项目 | Course & Team Projects
* **校车管理系统** | School Bus Management System
  * 基于《软件工程导论》理论开发
  * 应用瀑布模型、原型法与敏捷方法
  * 完成需求分析、数据库设计与系统实现
  * 技术栈：Java, Spring Boot, MySQL, Vue.js

## 技术技能 / Technical Skills
======
### 编程语言 | Programming Languages
* **C++**: 算法与数据结构实现，系统级编程
* **Python**: 深度学习、数据分析、Web后端开发
* **Java**: Spring Boot、JDBC框架应用
* **JavaScript/TypeScript**: Vue.js、React前端开发

### 深度学习框架 | Deep Learning Frameworks
* **PyTorch**: 主要深度学习框架，模型训练与部署
* **TensorFlow**: 基础用法了解
* **数据分析工具**: pandas, numpy, matplotlib, scikit-learn

### 系统开发 | System Development
* **数据库**: MySQL, MongoDB设计与优化
* **Web开发**: Flask, Spring Boot, Vue.js, Element Plus
* **版本控制**: Git, GitHub项目管理
* **开发工具**: Visual Studio, PyCharm, VS Code

## 研究兴趣 / Research Interests
======
* 人工智能记忆系统 (AI Memory Systems)
* AI安全 (AI Security)
* 计算机视觉 (Computer Vision)
* 多模态交互系统 (Multimodal Interaction Systems)

## 语言能力 / Languages
======
* **中文**: 母语 (Native)
* **英语**: 流利 (Fluent)

## 联系方式 / Contact
======
* **邮箱**: ranger13love@163.com
* **GitHub**: [ranger1213123](https://github.com/ranger1213123)
* **地址**: 成都，四川，中国

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* 积极参与开源项目贡献
* 参与学术会议论文阅读与讨论
