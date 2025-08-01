# 周佳楠的学术主页 | Jia'nan Zhou's Academic Website

**四川大学软件学院2023级本科生，专注于人工智能、计算机视觉与AI安全研究**

![Academic Pages template example](images/homepage.png "Academic Pages template example")

## 个人简介 | About Me

**周佳楠 (Jia'nan Zhou)**，四川大学软件学院2023级本科生。原就读于水利水电学院，后转入软件工程专业。目前同时修读大一与大二课程，学业任务紧张，但仍保持了较高的成绩。

**Zhou Jianan** is an undergraduate student (Class of 2023) at the School of Software Engineering, Sichuan University. Originally admitted to the School of Water Conservancy and Hydropower, he later transferred to software engineering. Currently, he is taking both freshman and sophomore courses simultaneously, maintaining strong academic performance despite a heavy workload.

## 研究兴趣 | Research Interests

- **人工智能记忆系统** (AI Memory Systems)
- **AI安全** (AI Security) 
- **计算机视觉** (Computer Vision)
- **多模态交互系统** (Multimodal Interaction Systems)

## 主要项目 | Major Projects

### 🏆 NUS暑期工作坊 | NUS Summer Workshop
- **Visual Computing小组**: 2025.4.22-2025.7.22，获得团队最佳人气奖和一等奖
- **成就**: 在新加坡国立大学视觉计算暑期工作坊中展现出色的技术能力和创新思维

### 🔬 IDS LAB 四川大学 | IDS LAB, Sichuan University
- **LLM记忆系统安全研究**: 2025.7.25至今，专注于大语言模型记忆系统的安全攻防
- **研究方向**: 探索记忆系统的攻击和防御机制

### 🤖 人工智能与计算机视觉 | AI & Computer Vision
- **CycleGAN改进项目**: 实现既能进行风格迁移又能从随机噪声生成动漫头像
- **OpenFace项目**: 使用CMake与Visual Studio构建特征提取工具

### 🔒 AI系统与安全研究 | AI Systems & Security
- **记忆系统研究**: 研究MemoryOS与mem0等记忆系统，尝试迁移content poisoning攻击
- **攻击实验设计**: 设计完整的攻击实验与评估逻辑

### 🎯 多模态交互系统 | Multimodal Interaction Systems
- **智能面试评测系统**: 基于Flask + MySQL + Vue 3 + Element Plus的多模态系统
- **集成功能**: 讯飞API、OpenFace与大模型评分机制

### 💾 数据库与事务管理 | Database & Transaction Management
- **事务调度系统**: 支持Wound-Wait协议的事务调度系统

### 📈 量化交易研究 | Quantitative Trading Research
- **多因子交易策略**: BollingerStrategy类，结合多种技术指标

## 技术能力 | Technical Skills

### 编程语言 | Programming Languages
- **C++**: 算法与数据结构实现
- **Python**: 深度学习、数据分析、Flask后端开发
- **Java**: Spring Boot、JDBC框架应用
- **JavaScript/TypeScript**: Vue、React前端开发

### 深度学习框架 | Deep Learning Frameworks
- **PyTorch**: 主要深度学习框架
- **TensorFlow**: 基础用法了解
- **数据分析**: pandas、numpy等工具

### 系统开发 | System Development
- **数据库**: MySQL、MongoDB设计与优化
- **Web开发**: Flask、Spring Boot、Vue.js、Element Plus
- **版本控制**: Git、GitHub项目管理

## 联系方式 | Contact

- 📍 **地址**: 成都，四川，中国
- 📧 **邮箱**: [ranger13love@163.com](mailto:ranger13love@163.com)
- 🔗 **GitHub**: [ranger1213123](https://github.com/ranger1213123)
- 🏫 **学校**: [四川大学](https://www.scu.edu.cn)

---

# Getting Started

This website is built using the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template and hosted on [GitHub Pages](https://pages.github.com).

1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Click the "Use this template" button in the top right.
1. On the "New repository" page, enter your public repository name as "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and add your content.
1. Upload any files (like PDFs, .zip files, etc.) to the `files/` directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.
1. Check status by going to the repository settings, in the "GitHub pages" section
1. (Optional) Use the Jupyter notebooks or python scripts in the `markdown_generator` folder to generate markdown files for publications and talks from a TSV file.

See more info at https://academicpages.github.io/

## Running locally

When you are initially working on your website, it is very useful to be able to preview the changes locally before pushing them to GitHub. To work locally you will need to:

1. Clone the repository and made updates as detailed above.

### Using a different IDE
1. Make sure you have ruby-dev, bundler, and nodejs installed
    
    On most Linux distribution and [Windows Subsystem Linux](https://learn.microsoft.com/en-us/windows/wsl/about) the command is:
    ```bash
    sudo apt install ruby-dev ruby-bundler nodejs
    ```
    If you see error `Unable to locate package ruby-bundler`, `Unable to locate package nodejs `, run the following:
    ```bash
    sudo apt update && sudo apt upgrade -y
    ```
    then try run `sudo apt install ruby-dev ruby-bundler nodejs` again.

    On MacOS the commands are:
    ```bash
    brew install ruby
    brew install node
    gem install bundler
    ```
1. Run `