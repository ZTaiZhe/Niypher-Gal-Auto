# Niypher-Gal-Auto
匿影 Gal 自动化本地化国际化支持引擎
项目名称： Niypher-Gal-Auto (匿影 Gal 自动化本地化引擎)
​项目背景： 针对大型 Galgame 汉化过程中文本量大（通常 100万+ Token）、人设易崩坏的痛点。
​技术架构：
​Backend: Go / Python (FastAPI)
​Frontend: Next.js (用于人工审核翻译界面)
​AI Engine: 接入 Xiaomi MiMo (GLM/MiniMax) 接口，利用长上下文能力维持长达 128k 窗口的世界观一致性。
​Deployment: Docker 容器化部署。
