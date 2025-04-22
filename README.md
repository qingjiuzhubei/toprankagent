🧠 TopRankAgent - Discover Top Agents
全球 GPTs 与 MCP 智能体服务器评测与推荐平台




📌 项目简介
TopRankAgent 是一个致力于打造最全、最新、最实用的 智能体（Agent）和多模型计算节点（MCP）评测平台。我们的目标是帮助 AI 从业者、开发者和爱好者快速选择合适的智能体服务节点（如 LoopGPT、AutoGPT 等）与最优算力资源（MCP Server）。

该平台通过评测性能、响应速度、支持模型、地区可用性等维度，为用户提供：

🌍 智能体工具与平台汇总

🚀 MCP Server 节点实时测速

🧪 可部署 Agent 兼容性测试

🎯 推荐最优配置与节点组合

🗞 推送评测更新给注册会员

访问平台 👉 https://toprankagent.com

🎯 核心功能
🔎 Agent 探索页：分类展示主流开源 Agent（AutoGPT、BabyAGI、SuperAgent 等）

🧭 MCP 性能评测：全球不同地区的 AI Server 节点速度与延迟对比

🧠 AI 模型支持信息：每个 MCP 支持的 LLM、Embedding、语音等模型一览

📈 排名推荐系统：基于访问量、评分、测速结果的智能排序

📬 会员订阅推送：更新自动推送，支持邮箱 & Telegram

🧩 技术栈

后端	前端	数据库	部署	工具
Laravel 10	Blade + TailwindCSS	MySQL / Redis	Nginx / Supervisor	GitHub Actions, Crontab
🚧 当前进度（完成度：80%）
 Agent & MCP 数据抓取与分类

 MCP 节点测速系统

 用户收藏 / 评论系统

 网站前端 UI 与页面架构

 邮件订阅系统（开发中）

 MCP 自动测速周期任务优化中

🧭 快速开始（开发环境）
bash
复制
编辑
git clone https://github.com/qingjiuzhubei/toprankagent.git
cd toprankagent
cp .env.example .env
composer install
php artisan key:generate
php artisan migrate --seed
npm install && npm run dev
php artisan serve
📮 贡献 & 加入我们
欢迎提交 issue 或 PR，一起共建全球最权威的智能体与算力节点评测平台！

📧 邮件联系：admin@toprankagent.com
📣 Telegram交流群：即将开放

📄 License
This project is open-sourced under the MIT license.




<img width="1333" alt="image" src="https://github.com/user-attachments/assets/f264d78a-cb1a-4433-9e82-2bb40dd76679" />
