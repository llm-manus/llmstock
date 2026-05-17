AI Agent 股票异动风控机器人（支持美股+A股）
AI Agent Stock Volatility Risk Control Robot (US & A-Shares Supported)
📌 项目简介 | Introduction
本项目为慕课网实战课程（ID：982） 配套源码，基于 AI Agent 构建全自动化股票异动风控系统，同时适配美股与A 股两大市场。
This project is the supporting source code for the practical course (ID: 982) on imooc.com. It builds a fully automated stock volatility risk control system based on AI Agent, compatible with both US stocks and A-shares.
整合 AI 感知、推理、决策能力，实现 7×24 小时行情监控、异动识别与智能预警，可直接用于个人风控或二次开发学习。
Integrating AI perception, reasoning and decision-making capabilities, it enables 24/7 market monitoring, anomaly identification and intelligent early warning. It can be directly used for personal risk management or secondary development learning.
✨ 核心功能 | Core Features
- ✅ 双市场支持：适配美股熔断、A 股涨跌停规则
Dual-market support: Adapts to US stock circuit breakers and A-share price limit rules
- ✅ 实时监控：7×24 小时抓取行情数据，毫秒级响应
Real-time monitoring: Captures market data 24/7 with millisecond-level response
- ✅ 智能识别：融合 RSI/MACD 指标、量价异常、市场情绪多维分析
Intelligent identification: Integrates RSI/MACD indicators, volume-price anomalies and market sentiment analysis
- ✅ 自动预警：邮件 / 消息推送异动提醒，自定义风控阈值
Automatic early warning: Sends anomaly alerts via email/message with customizable risk control thresholds
- ✅ 可扩展架构：模块化设计，支持新增市场与风控策略
Scalable architecture: Modular design supporting new markets and risk control strategies
🛠️ 技术栈 | Tech Stack
后端 Backend
- Python、AI Agent 框架
- 行情 API（美股 / A 股）、Redis、MySQL
- 数据分析：Pandas、NumPy、TA-Lib
部署 Deployment
- Docker、Git、Linux
👥 适用人群 | Target Users
- 金融科技开发者、量化交易爱好者
- AI Agent 实战学习者、风控系统开发人员
- 想搭建个人股票监控工具的投资者
🚀 快速开始 | Quick Start
1. 克隆仓库：git clone [仓库地址]
2. 安装依赖：pip install -r requirements.txt
3. 配置行情 API 密钥与风控参数
4. 启动项目：python main.py
📚 配套课程 | Supporting Course
慕课网实战课程：https://coding.imooc.com/class/982.html
⚠️ 声明 | Disclaimer
本项目为学习演示用途，不构成投资建议。实盘使用请自行完善风控逻辑，开发者不承担任何投资风险。
This project is for learning and demonstration purposes only and does not constitute investment advice. Please improve the risk control logic independently for live trading; the developer bears no investment risks.
要不要我帮你把这份 [README.md](README.md) 导出成可直接复制的纯文本文件？
