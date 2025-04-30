# 🚀 QTXD_WebPlatform · 智能副业系统展示平台

![GitHub stars](https://img.shields.io/github/stars/feizei150/QTXD_WebPlatform?style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/feizei150/QTXD_WebPlatform?style=flat-square)
![License](https://img.shields.io/github/license/feizei150/QTXD_WebPlatform?style=flat-square)

📌 **QTXD_WebPlatform** 是整个 QTXD_AI_system 的“对外门户”，用于集中展示项目成果、开放申请入口、接入激活码机制和未来扩展的 AI 工具交互平台。

---

## ✨ 核心功能亮点

| 模块 | 功能说明 |
|------|----------|
| 🎯 主页面展示 | 首页聚合导航入口，展示自动赚钱系统、党建生成系统、数据分析模块等 |
| 📨 激活码系统 | 提交用户信息表单，自动接入 Notion 数据库记录和验证 |
| 🌐 动态页面 | 可集成 Notion 数据、视频发布结果、任务完成状态等实时信息 |
| 🛠️ 模块扩展 | 支持挂接 AI 智能写作、视频生成等独立子模块 |

---

## 📂 目录结构说明

QTXD_WebPlatform/ 
├── app.py # 主入口文件 
├── write_chatgpt_to_notion.py # 提交内容写入 Notion 
├── write_chatgpt_to_obsidian.py # 提交内容写入 Obsidian 
├── .gitignore 
├── README.md


---

## 🚀 启动方式（本地开发）

```bash
# 安装依赖
pip install -r requirements.txt

# 启动服务
python app.py

🔮 示例页面（可扩展）
🌍 首页链接：https://qingtianxiaodou.com

🗂️ 激活页路径：/activate

📄 项目模块页：

/ai-income

/party

/thesis-tools

📈 适用场景

想搭建一个属于自己的 AI 项目展示网站

想用网页方式提交用户信息，并写入 Notion 自动记录

想打造一个“自己的官网 + 智能体入口”

想对外提供系统服务（写作、生成、发布等）
📌 作者与版权
由 feizei150 开发维护，欢迎 Star 🌟 和 Issue 🙌
项目基于 MIT 协议开源，放心使用！
