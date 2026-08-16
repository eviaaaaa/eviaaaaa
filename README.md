<div align="center">

# Hi, I'm evilhero 👋

**AI 应用开发 · Python 后端开发**

关注 AI Agent、RAG、MCP 与后端工程，喜欢从实际问题出发完成分析、实现与验证。

[![Email](https://img.shields.io/badge/Email-w2278596667%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:w2278596667@gmail.com)

</div>

## 部分开源贡献

- **[Clash Verge Rev：修复快速重启时的 mixed-port 误判](https://github.com/clash-verge-rev/clash-verge-rev/pull/7732)** — 对齐 Unix TCP 端口探测与真实监听语义，兼顾残留连接复用及 macOS 地址重叠冲突检测。
- **[RAGFlow：通过 DOCX 图片懒加载降低峰值内存](https://github.com/infiniflow/ragflow/pull/13233)** — 引入惰性图片抽象，在保持解析输出一致的前提下降低图片密集型文档的峰值内存占用。
- **[RAGFlow：统一 DOCX 解析器的图片懒加载链路](https://github.com/infiniflow/ragflow/pull/13329)** — 将 QA 与 manual 解析策略迁移到统一抽象，消除重复实现并补充损坏图片流的安全回退。
- **[RAGFlow：解决多个 MCP Server 的工具重名冲突](https://github.com/infiniflow/ragflow/pull/14217)** — 分离 LLM 侧唯一函数名与服务端原始工具名，避免注册覆盖并保持 MCP 调用正确分发。
- **[Karakeep：修复结构化输出的模型兼容问题](https://github.com/karakeep-app/karakeep/pull/2926)** — 仅在存在 schema 时启用 JSON response format，兼容 DeepSeek 等 OpenAI-compatible providers。
- **[RAGFlow：通过 Tika 支持旧版 `.ppt` 文档解析](https://github.com/infiniflow/ragflow/pull/12932)** — 为 OLE2 PowerPoint 增加无新依赖的文本解析回退，替代已移除的 Aspose 路径。
- **[RAGFlow：修复 MCP 调用超时与空结果处理](https://github.com/infiniflow/ragflow/pull/13899)** — 将外部超时传递到实际 MCP 请求，并避免空内容响应触发越界异常。
- **[Epic Freebies Helper：修复领取弹窗与视觉验证码坐标转换](https://github.com/Ronchy2000/epic-freebies-helper/pull/11)** — 处理阻塞式设备弹窗，并将 GLM 区域框转换为 hCaptcha 所需的点击坐标。

## 技术栈

**AI 与智能体**<br />
`AI Agents` · `RAG` · `MCP` · `LangChain` · `LangGraph` · `PyTorch`

**语言与后端**<br />
<img height="42" src="https://skillicons.dev/icons?i=python,java,cpp,fastapi,spring&theme=dark" alt="Python, Java, C++, FastAPI and Spring Boot" />

**数据与工程**<br />
<img height="42" src="https://skillicons.dev/icons?i=postgres,mysql,redis,elasticsearch,docker,linux&theme=dark" alt="PostgreSQL, MySQL, Redis, Elasticsearch, Docker and Linux" />

## 个人项目

- **[满懂（Mandune）](https://github.com/FinLens-team/Mandune)**：基于证据的个人持仓复盘与风险边界分析应用，支持多主题报告、行情上下文、MCP/Atlas 图鉴和可追溯的分析结果。
- **[Daiboo](https://github.com/eviaaaaa/Daiboo)**：面向复杂网页任务的智能浏览器代理框架，基于 LLM 与 Playwright MCP 执行浏览器操作，并结合上下文压缩、人工审批、文档检索和任务经验复用能力。
- **招投标管理系统**：基于 Spring Boot 的多企业招投标全流程管理平台。
