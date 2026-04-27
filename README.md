- 你好，我是 周佳凯 [@zhoujiakai](https://github.com/zhoujiakai)
- 关注领域：AI、Web3、计算机视觉、软件工程
- 正在学习：AI、Web3
- 公众号：周佳凯对话空间.
- 个人知识库：[openpaper](https://github.com/zhoujiakai/openpaper)
- 个人工作流 Skills：[openskill](https://github.com/zhoujiakai/openskill)

## 技能

### AI 应用开发

- LangChain、LlamaIndex — RAG、工具调用、MCP、多 Agent 协作
- Prompt 工程，Chroma/FAISS 向量数据库构建 RAG 知识库，文档 ETL 流程
- AI 编程工具：Claude Code / Cursor，MCP Server 与 Agent Skills 开发

### 计算机视觉

- 目标检测、姿态估计、多目标跟踪、PPOCR、OpenCV
- RTSP 视频流接入，模型端侧部署与优化

### 后端开发

- Python3（装饰器、生成器、异步编程），FastAPI，Pydantic
- 微服务架构：FastAPI + SQLAlchemy，Celery 异步任务队列
- MySQL、PostgreSQL（分库分表、索引优化、ORM 映射、慢查询分析）
- Redis（多级缓存架构、分布式锁、缓存雪崩/穿透方案、哨兵集群）
- Docker 容器化，Nginx 反向代理部署，Serverless 平台
- Prometheus + Grafana 监控告警，全链路追踪

---

## 经验

### AI 方向

**技术栈：** Python, LangChain, FastAPI, Celery, RAG, Chroma, FAISS, OpenAI API

- RAG 知识库搭建：基于 LangChain 搭建文档 ETL 管线，完成多格式文档的解析、分块与向量化，存入 Chroma 向量数据库
- Prompt 工程与调优：设计结构化 Prompt 模板，通过 Few-shot 和思维链（CoT）引导输出，问答准确率提升至 85% 以上
- Agent 接口封装：基于 FastAPI 封装 Agent 调用接口，集成工具调用、记忆管理和多轮对话，通过 Celery 处理长耗时推理请求，接口响应优化至 3 秒以内
- 跨团队协作：将 AI 能力融入业务工作流，支持文档智能摘要、自动问答、任务调度等核心场景，服务内部用户 200+

### 视觉方向

**技术栈：** Python, OpenCV, YOLOv5, OpenPose, DeepSort

- 多源视频流接入与融合：支持 RTSP 协议接入摄像头、热成像等多类设备，实现 7×24 小时实时视频流分析
- 目标检测与跟踪：基于 YOLOv5 + OpenPose + DeepSort 组合方案，处理准确率达 90% 以上，推理速度优化至 25 FPS 以上
- 姿态与行为识别：通过人体检测框几何特征分析、连续帧序列变化检测（pHash）等手段实现行为识别，误报率控制在 5% 以内
- 多模态数据融合：融合热成像温度数据与视觉检测结果，结合多源传感器数据与定位系统，实现多模态联合分析，预警响应时间小于 2 秒

### MLOps / 部署运维

**技术栈：** PySide, Docker, Bash, 边缘设备部署

- 端侧部署：将 YOLO 模型量化后部署到边缘开发板，实现本地离线推理，降低云端依赖
- 自动化部署：编写 Bash 脚本实现 Ubuntu 环境下一键安装部署，将现场部署时间从 2 小时缩短至 15 分钟
- 运维工具：基于 PySide 开发桌面运维工具，支持现场快速调试和系统配置
- 系统集成：集成人脸识别 API、语音播报等外部服务，构建完整的自动化处理闭环

---

## 开源项目

- [openpaper](https://github.com/zhoujiakai/openpaper) — 个人知识库，系统性收集 AI / CV / Web3 / 软件工程等领域的论文、书籍与播客
- [openbiteagle](https://github.com/zhoujiakai/openbiteagle) — 基于 LangGraph 多阶段推理流水线的 Web3 新闻 AI 投资分析平台，自动生成带置信度的买入/卖出建议
- [openvision](https://github.com/zhoujiakai/openvision) — 计算机视觉工程合集：YOLOv11 端侧部署与推理、阿里云人脸识别对接、RTSP 多路视频流异步采集
- [opentaskapi](https://github.com/zhoujiakai/opentaskapi) — FastAPI 异步任务管理后端：分层架构设计，集成 API Key 认证、缓存加速、异步邮件通知
- [openmeeting](https://github.com/zhoujiakai/openmeeting) — 一站式浏览器会议平台，融合会议日程管理与 WebRTC 实时视频会议
- [openfishing](https://github.com/zhoujiakai/openfishing) — 安卓抓鱼小游戏，Android 原生客户端 + Java Servlet 后端 + MySQL 全栈架构
