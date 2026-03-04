AI Daily Hub: 深度复盘与智能日程助手
AI Daily Hub 是一个“AI 原生”的单文件个人管理工具。它打破了传统清单工具只记录、不思考的局限，通过集成 Google Gemini 1.5 Flash 和 Jina Reader，为用户提供从“任务抓取”到“深度复盘”的闭环体验。

🌟 核心功能
⚡ 极简形态：全工具仅一个 HTML 文件，无需安装，本地运行，双击即用。

🔍 智能链接解析：粘贴 URL 后，利用 r.jina.ai 自动抓取网页正文，并由 AI 自动生成真实标题和深度摘要，解决“只藏不看”的痛点。

🧠 全上下文复盘 (Review)：

维度融合：AI 会同时调取你的“任务完成情况”与“笔记链接内容”，进行交叉关联分析。

拟人化教练：摆脱生硬的模版，AI 以深度成长教练的口吻进行点评，直击拖延或精力分配问题。

动态探问：根据当日记录生成个性化反思题，并支持针对回答的进一步互动反馈。

🛡️ 隐私至上：无后端服务器。API Key 和所有日程数据均存储在浏览器的 localStorage 中，数据随你而走。

🚀 快速上手
获取 API Key：前往 Google AI Studio 获取免费的 Gemini API Key。

启动：下载本项目中的 daily-planner.html，直接用浏览器打开。

配置：点击页面右上角 Settings 填入 Key。

体验 AI：

在笔记区粘贴一个技术文章链接，观察 AI 提取标题和摘要。

完成一天的任务后，进入 AI Review 体验三阶段深度对谈。

🛠️ 技术架构
Language: Vanilla JavaScript (ES6+), HTML5, CSS3.

AI Model: Google Gemini 1.5 pro (API-based).

CORS Solutions: Jina Reader API (用于突破跨域抓取限制).

Data Persistence: Browser LocalStorage API.

📄 开源协议 (License)
本项目采用 CC 1.0 许可协议。

署名 (Attribution)：您可以自由分享和修改，但必须给出适当的署名。

非商业性使用 (NonCommercial)：您不得将本作品用于商业目的。

相同方式共享 (ShareAlike)：如果您对本作品进行二次创作，必须采用相同的协议分发。

💡 开发哲学
“记录只是开始，复盘才是增长。这个工具不希望成为你的另一个负担清单，而是希望成为你每天工作结束时，那个能陪你聊聊深度思考的伙伴。”
