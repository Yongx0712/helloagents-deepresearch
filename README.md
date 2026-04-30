# 🧠 HelloAgents-DeepResearch
# （AI 深度研究智能体）
基于 HelloAgents 框架构建的 AI 深度研究智能体，支持自动联网搜索、信息分析、研究报告一站式生成 ✨

# 🎯 项目介绍
这是我自主开发的深度研究智能体项目，能够根据用户输入的研究主题，自动完成问题拆解、资料搜索、内容归纳、报告生成全流程工作。

# ✨ 核心功能
- 🤖 AI 自动拆解研究问题
- 🌐 联网搜索获取最新资料
- 🧩 多轮信息整合与验证
- 📝 自动生成 Markdown 研究报告
- 🛠️ 模块化设计，易于扩展

# 📁 项目结构
```bash
helloagents-deepresearch/
├── .vscode/
│   └── settings.json     # 编辑器配置文件
├── backend/
│   ├── agent.py          # 智能体核心逻辑
│   ├── main.py           # 项目入口
│   ├── tools.py          # 工具函数
│   ├── prompts.py        # 提示词模板
│   ├── config.py         # 配置文件
│   └── requirements.txt  # 依赖清单
├── frontend/
│   ├── src/              # 前端源码
│   ├── assets/           # 静态资源
│   ├── index.html        # 页面入口
│   └── package.json      # 前端依赖
├── .env                  # 环境变量
├── .gitignore            # Git 忽略文件
└── README.md             # 项目说明
```

# 🚀 安装与使用

## 1. 进入项目目录
```bash
cd F:\helloagents-deepresearch
```

## 2. 创建虚拟环境
```bash
运行
python -m venv venv
venv\Scripts\activate
```

## 3. 安装依赖
```bash
运行
pip install -r requirements.txt
```

## 4. 配置 API Key
```bash
env
LLM_API_KEY=你的API密钥
LLM_BASE_URL=https://api.deepseek.com/v1
LLM_MODEL_NAME=deepseek-chat
TAVILY_API_KEY=你的搜索密钥
```

## 5. 运行项目
```bash
运行
python backend/main.py
```

📌 使用说明  
运行后输入你想研究的主题，AI 会自动：  
- 拆解问题  
- 搜索资料  
- 整合信息  
- 生成研究报告  

⚠️ 注意事项  
- Python ≥ 3.10  
- 需要配置 LLM API Key  
- 在项目根目录运行  

📄 版权说明
本项目仅供学习、研究使用
