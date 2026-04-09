# 🌟 Hung-yi Lee Machine Learning 2021 | 机器学习笔记与作业实战

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-ee4c2c.svg)
![Status](https://img.shields.io/badge/Status-In%20Progress-success.svg)

## 📖 项目简介

本项目用于记录学习**李宏毅老师 2021 版机器学习课程 (Hung-yi Lee ML 2021)** 的完整过程。仓库包含了个人的课堂学习笔记、理论推导以及全部 15 个编程作业（Homework）的 PyTorch 代码实现。

课程主页：[Machine Learning 2021 Spring](sslocal://flow/file_open?url=https%3A%2F%2Fspeech.ee.ntu.edu.tw%2F~hylee%2Fml%2F2021-spring.php&flow_extra=eyJsaW5rX3R5cGUiOiJjb2RlX2ludGVycHJldGVyIn0=)

---

## 📂 目录结构

建议按照以下结构组织代码与笔记：

```text
LHY_ML_2021/
├── README.md               # 项目主文档
├── Notes/                  # 课堂笔记与数学推导 (Markdown 格式)
│   ├── HW01_Regression.md  
│   └── ...
├── Homeworks/              # 课程代码作业 (Jupyter Notebook / Python)
│   ├── HW01/               # 回归任务：COVID-19 确诊人数预测
│   │   ├── hw1.ipynb       # 核心作业代码
│   │   └── requirements.txt# 当前作业依赖
│   └── ...
└── Utils/                  # 通用工具代码（如数据加载、可视化脚本等）
```

---

## 🚀 学习进度与作业清单

- [ ] **HW01: Regression (回归)** - 预测 COVID-19 确诊人数
- [ ] **HW02: Classification (分类)** - 预测个体收入水平
- [ ] **HW03: CNN (卷积神经网络)** - 图像分类 (Food-11 数据集)
- [ ] **HW04: Self-Attention (自注意力机制)** - 说话人识别 (Speaker Identification)
- [ ] **HW05: Transformer** - 机器翻译 (Machine Translation)
- [ ] **HW06: GAN (生成对抗网络)** - 动漫人脸生成 (Anime Face Generation)
- [ ] **HW07: BERT** - 抽取式问答 (Extractive QA)
- [ ] **HW08: AutoEncoder (自编码器)** - 图像异常检测 (Anomaly Detection)
- [ ] **HW09: Explainable AI (可解释性 AI)** - 解释 CNN 模型行为
- [ ] **HW10: Adversarial Attack (对抗攻击)** - 图像白盒/黑盒攻击
- [ ] **HW11: Domain Adaptation (领域自适应)** - 图像跨域分类
- [ ] **HW12: Reinforcement Learning (强化学习)** - 代理玩打砖块游戏 (Play Breakout)
- [ ] **HW13: Network Compression (网络压缩)** - 模型剪枝与知识蒸馏
- [ ] **HW14: Life-long Learning (终身学习)** - 缓解灾难性遗忘
- [ ] **HW15: Meta Learning (元学习)** - 少样本图像分类 (Few-shot Classification)

---

## 🛠️ 环境依赖与运行说明

本项目主要基于 `Python 3.8+` 和 `PyTorch` 构建。建议使用 Conda 或 venv 创建虚拟环境运行：

```bash
# 1. 克隆仓库到本地
git clone https://github.com/YourUsername/LHY_ML_2021.git
cd LHY_ML_2021

# 2. 安装基础依赖 (根据具体 HW 目录下的 requirements 安装)
pip install jupyter torch torchvision matplotlib numpy pandas

# 3. 启动 Jupyter Notebook 开始实验
jupyter notebook
```

> **⚠️ 注意事项 (Notes):**
> 机器学习任务会产生大量的训练数据集 (Dataset) 和模型权重文件 (Model Checkpoints)。为避免仓库体积过大，`.gitignore` 文件已配置忽略 `*.pth`, `*.ckpt`, `*.npy` 以及 `data/`, `models/` 等目录。请根据每次作业的官方说明自行下载数据并放置在本地对应的文件夹中。

---

*Talk is cheap. Show me the code.*
