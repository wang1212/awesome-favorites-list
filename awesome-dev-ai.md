<div align="center">
  <h1>Awesome-AI-Dev-List</h1>

  <p>:heart: 收藏列表 - :+1: 人工智能领域相关技术，例如机器学习、深度学习、计算机视觉、自然语言处理等。</p>
  <p><i>Favorites list - Related technologies in the field of artificial intelligence, such as machine learning, deep learning, computer vision, natural language processing, etc.</i></p>
</div>

<br />

_（Recommend） :point_right: [awesome-artificial-intelligence](https://github.com/owainlewis/awesome-artificial-intelligence)_

## 目录

*Resource navigation list.*

- [资讯（News）](#资讯)
- [社区（Community）](#社区)
- [协议（Protocol）](#协议)
  - [MCP（Model Context Protocol）](#model-context-protocol)
  - [Skills](#skills)
- [资源（Resources）](#资源)
  - [云服务商（AI Model Cloud Service Provider）](#云服务商)
- [工具（Tools）](#工具)
- [开发框架（Development Framework）](#开发框架)
- [其它（Others）](#其它)

## 资讯

_News, also see 👉 [journals](awesome-dev-resource.md#技术期刊)._

- [Artificial Analysis](https://artificialanalysis.ai/) - AI 模型与服务供应商评测分析。
- [Hugging Face Blog](https://huggingface.co/blog/)
- [OpenAI News](https://openai.com/news/)
- [Google Research Blog](https://ai.googleblog.com/)
  - [Google Products News - Gemini](https://blog.google/products/gemini/)
  - [Google Developers](https://developers.google.com/)
  - [Google Labs](https://labs.google/)
- [Anthropic News](https://www.anthropic.com/news)
- [TestingCatalog News](https://www.testingcatalog.com/) - AI 领域资讯。
- [Dr. Andrew Ng](https://www.andrewng.org/) - 吴恩达的博客。
- [ruder.io](https://www.ruder.io/)
- [AI + a16z](https://a16z.com/ai/) - 全球风投机构 a16z 对 AI 领域的关注。
  - [The Top 100 Gen AI Apps](https://a16z.com/100-gen-ai-apps/) - 全球前 100 名生成式 AI 应用榜单，每 6 个月更新一次。
- [The 2025 AI Index Report](https://hai.stanford.edu/ai-index/2025-ai-index-report)
- [aigc.cn](https://www.aigc.cn/) - AI 相关产品导航。
- [猫目](https://maomu.com/) - AI 相关产品资讯，排行榜等等。

[`Go Top ↑`](#awesome-ai-dev-list)

## 社区

_Community._

- [Agentic AI Foundation](https://aaif.io/) - 开源智能体 AI 生态，非营利性组织。

- [Hugging Face](https://huggingface.co/) - 全球领先的协作共享开源 AI 模型社区。
  - [TensorFlow Hub](https://www.tensorflow.org/hub)
  - [魔搭](https://modelscope.cn/)
  - [飞桨](https://aistudio.baidu.com/)

- Image and Video generation models
  - [civitai](https://civitai.com/) - 一个致力于让人们分享和协作改进 Stable Diffusion 模型的开源平台。
  - [liblib](https://www.liblib.art/)
  - [ComfyUI](https://www.comfy.org/) - 开源的基于节点的生成式人工智能应用工作流构建工具。
  - [ml4a - Machine Learning for Art](https://ml4a.net/) - ml4a 是一系列工具和教育资源，将机器学习技术应用于艺术和创造力。
  - [Fooocus](https://github.com/lllyasviel/Fooocus) - 操作简化的图像生成应用，专注于提示和生成。

- Datasets, Experiments, and Competitions
  - [Kaggle](https://www.kaggle.com/)
  - [OpenML](https://www.openml.org/)
  - [_Awesome-Scientific-Datasets-and-LLMs_](https://github.com/open-sciencelab/Awesome-Scientific-Datasets-and-LLMs)

[`Go Top ↑`](#awesome-ai-dev-list)

## 协议

_Protocol._

### Model Context Protocol

_[Model Context Protocol](https://modelcontextprotocol.io/introduction) Resources._

- Extension
  - [MCP-UI](https://mcpui.dev/) - 基于 MCP 的交互式 UI 组件，**Anthropic 发起**。

- Awesome
  - [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers)
  - [awesome-mcp-clients](https://github.com/punkpeye/awesome-mcp-clients/)

- Tools
  - [Supergateway](https://github.com/supercorp-ai/supergateway) - 使用一个命令通过 SSE 或 WebSockets 运行基于 MCP stdio 的服务器。
  - [MCP Bundles (MCPB)](https://github.com/modelcontextprotocol/mcpb) - 包含本地 MCP 服务器和描述服务器及其功能的压缩包。

<details>
  <summary>Marketplace</summary>

  - [Smithery](https://smithery.ai/) - mcp servers.
  - [Glama MCP](https://glama.ai/mcp) - mcp clients、servers.
  - [MCP.so](https://mcp.so/)
  - [Awesome MCP Servers](https://mcpservers.org/)

</details>

### Skills

_[SKILL.md](https://agentskills.io/) Resources._

- [skills](https://github.com/anthropics/skills) - 官方的案例。
- [oai-skills](https://github.com/eliasjudin/oai-skills) - OpenAI 泄露的官方技能。

- Tools
  - [Skill_Seekers](https://github.com/yusufkaraaslan/Skill_Seekers) - 将文档网站、GitHub 存储库和 PDF 文件转换为 Claude AI 技能。
  - [skills.sh](https://skills.sh/) - 从任何 git 仓库将 Skills 一键安装到本地的多个编码代理。

<details>
  <summary>Marketplace</summary>

  - [superpowers](https://github.com/obra/superpowers)
  - https://github.com/ComposioHQ/awesome-claude-skills
  - https://github.com/BehiSecc/awesome-claude-skills
  - https://github.com/VoltAgent/awesome-claude-skills
  - https://github.com/travisvn/awesome-claude-skills
  - https://github.com/K-Dense-AI/claude-scientific-skills
  - https://github.com/huggingface/skills

</details>

### 其它

_Others._

- [AGENTS.md](https://agents.md/) - 一种简单、开放的编码代理指导格式，**AAIF 项目**。

- [Agent2Agent (A2A) Protocol](https://a2a-protocol.org/) - 旨在实现 AI 代理之间的无缝通信和协作，**Google 发起**。
  - [Agent Payments Protocol (AP2)](https://ap2-protocol.org/) - 旨在为开发者、商家和支付行业提供安全、可靠且可互操作的代理交易能力，**Google 发起**。
- [A2UI](https://github.com/google/A2UI/) - 一个面向代理的生成式 UI 的标准协议，**Google 发起**。
- [Agent–User Interaction (AG-UI) Protocol](https://docs.ag-ui.com/) - 开放、轻量级、基于事件的协议，它标准化了 AI 代理连接到面向用户的应用程序的方式。
- [Agent Client Protocol (ACP)](https://agentclientprotocol.com/) - 标准化了代码编辑器（IDE、文本编辑器等）和编码代理（使用生成式 AI 自主修改代码的程序）之间的通信。
- [agents.json](https://docs.wild-card.ai/agentsjson/introduction)

[`Go Top ↑`](#awesome-ai-dev-list)

## 资源

_Resources._

### 教程

_Tutorial._

- [Hugging Face Learn](https://huggingface.co/learn) - Hugging Face 发布的高质量教程。
- [AI GUIDE](https://ai-guide.future.mozilla.org/) - AI 指南，**Mozilla 发布**。
- [People + AI Guidebook](https://pair.withgoogle.com/guidebook) - 一套使用 AI 进行设计的方法、最佳实践和示例。
- [Awesome-LLM](https://github.com/Hannibal046/Awesome-LLM) - 大语言模型相关的论文资讯等。
- [Elicit Machine Learning Reading List](https://github.com/elicit/machine-learning-list) - 学习机器学习背景知识。
- [LeeDL-Tutorial](https://github.com/datawhalechina/leedl-tutorial) - 台湾大学李宏毅教授的深度学习教程。

- Prompt Engineering & Context Engineering
  - [Prompt Engineering Guide](https://www.promptingguide.ai/)
  - [Thinking-Claude](https://github.com/richards199999/Thinking-Claude) - 让 Claude 思考后再回答。
  - System Prompt
    - [CL4R1T4S](https://github.com/elder-plinius/CL4R1T4S) - 包含多个平台的完整系统提示词、指南和工具。
      - [L1B3RT4S](https://github.com/elder-plinius/L1B3RT4S) - LLMs 的越狱提示。
    - [system-prompts-and-models-of-ai-tools](https://github.com/x1xhlol/system-prompts-and-models-of-ai-tools)
  - [Prompting guide 101](https://services.google.com/fh/files/misc/gemini-for-google-workspace-prompting-guide-101.pdf)
    - [Generative AI prompt samples](https://cloud.google.com/vertex-ai/generative-ai/docs/prompt-gallery)
    - [How to prompt Gemini 2.5 Flash Image Generation for the best results](https://drive.google.com/file/d/1Pl9aeG1XuqQyvXBQhdpdY-iI4-XQR3wU/view?pli=1)
  - [god of prompt](https://www.godofprompt.ai/) - 不同领域的提示词模板。
  - [Fabric](https://github.com/danielmiessler/Fabric) - 提示词/模式集合。
  - [toon](https://github.com/toon-format/toon) - 面向标记的对象表示法 (TOON)，用于 LLM 提示的紧凑、易读、模式感知的 JSON。

### 云服务商

_AI Model Cloud Service Provider._

- General LLMs
  - [free-llm-api-resources](https://github.com/cheahjs/free-llm-api-resources) - 免费的 LLMs API 测试资源。
  - [OpenRouter](https://openrouter.ai/) - 以统一的接口提供不同 LLM 的服务。
  - [chutes](https://chutes.ai/)

- Image and Video generation models
  - [fal.ai](https://fal.ai/)

### 其它

_Others._

- [models.dev](https://models.dev/) - 不同 AI 模型的信息与能力统计。
- [terminal-bench](https://www.tbench.ai/) - 终端环境中人工智能代理的基准测试。

[`Go Top ↑`](#awesome-ai-dev-list)

## 工具

_Tools._

- [jsonformer](https://github.com/1rgs/jsonformer) - 让大模型输出 JSON 结构化的数据格式。

### Docs

- [llms.txt](https://llmstxt.org/) - 为网站生成 LLM 可读的上下文内容。
- Codebase Wiki
  - [Context7](https://context7.com/) - 为代码仓库提供最新的文档 MCP 服务。
  - [docfork](https://github.com/docfork/docfork-mcp) - 为代码仓库提供最新的文档 MCP 服务。
- Codebase 2 Prompt
  - [Repomix](https://repomix.com/) - 将整个代码库打包成一个 AI 友好的文件。
  - [code2prompt](https://github.com/mufeedvh/code2prompt)
- Codebase Analysis
  - [deepwiki](https://deepwiki.org/) - 在线为开源仓库提供文档 AI 问答服务。
    - [deepwiki-open](https://github.com/AsyncFuncAI/deepwiki-open)
  - [zread.ai](https://zread.ai/)

### CLIs

- [llm](https://github.com/simonw/llm) - 从命令行访问 LLMs，进行测试。

### Run LLMs Locally

- [ollama](https://ollama.com/)
- [LocalAI](https://localai.io/)
- [BrowserAI](https://github.com/sauravpanda/BrowserAI) - 在浏览器中借助 WebGPU 运行 LLMs。
- [LM Studio](https://lmstudio.ai/)

### JavaScript

- 模型加载（Backend and Model Access）
  - [Transformers.js](https://xenova.github.io/transformers.js/)

- 光学字符识别（OCR）
  - [tesseract.js](https://github.com/naptha/tesseract.js) - 支持 100 种语言的图像文本识别。

- 自然语言处理（NLP）
  - [compromise](http://compromise.cool/)
 
- 数据转换（Data conversion）
  - [Markdowner](https://md.dhr.wtf/) - 将网页转换为适合大语言模型处理的 Markdown 格式。
 
- 其它（Others）
  - [jscanify](https://colonelparrot.github.io/jscanify/) - 文档扫描库，能够检测和突出显示文档图像。
  - [stagehand](https://github.com/browserbase/stagehand) - 人工智能网页浏览工具，兼容 Playwright。

### Python

- [OpenLLM](https://github.com/bentoml/OpenLLM) - 大模型的微调、部署、监控等。
- [browser-use](https://github.com/browser-use/browser-use) - 将 AI 代理与浏览器连接。

- 模型加载（Backend and Model Access）
  - [transformers](https://github.com/huggingface/transformers)

- 文本处理（Text Processing）
  - [nltk](https://www.nltk.org/)
  - [spacy](https://spacy.io/)

- 信息抽取 (Information Extraction, IE)
  - [langExtract](https://github.com/google/langextract) - 文本提取，命名实体识别、关系提取、位置跟踪。
  - [OpenNRE](https://github.com/thunlp/OpenNRE) - 关系提取。
  - [flair](https://github.com/flairNLP/flair) - 命名实体识别、情感分析。

### C/C++

- [llama.cpp](https://github.com/ggml-org/llama.cpp) - 在本地运行 LLMs，并提供推理服务。

[`Go Top ↑`](#awesome-ai-dev-list)

## 开发框架

_Development Framework._

- Common
  - [LangChain](https://docs.langchain.com/) - 开发基于 LLMs 的应用程序。
  - [Metaflow](https://metaflow.org/) - 构建 AI/ML 系统的框架。
  - [Haystack](https://haystack.deepset.ai/) - 端到端的 NLP 框架，可构建基于 LLMs、Transformer 模型等的 NLP 应用，例如智能文档检索系统。
  - [mastra](https://mastra.ai/) - 开发 Agent 应用，支持工具调用、工作流、RAG 等等。
  - [OpenAI Agents SDK](https://openai.github.io/openai-agents-python/)
  - [pipecat](https://www.pipecat.ai/) - 语音和多模态会话人工智能应用的开发框架。
  - [Gradio](https://gradio.app/) - 快速构建机器学习应用。
  - [Streamlit](https://streamlit.io/) - 快速构建数据应用。

- RAG
  - [LlamaIndex](https://gpt-index.readthedocs.io/en/latest/index.html) - 数据框架，供 LLM 应用程序摄取、构建和访问私有或特定领域的数据。
  - [cognita](https://github.com/truefoundry/cognita) - 组件化、模块化方案。
  - [embedchain](https://github.com/embedchain/embedchain) - 构建 RAG 应用的框架。
  - [PrivateGPT](https://docs.privategpt.dev/overview) - 构建私有 RAG 应用的 SDK。
  - [llmware](https://llmware-ai.github.io/llmware/)

- Chatbot UI
  - [assistant-ui](https://github.com/Yonom/assistant-ui)
    - [Tool UI](https://www.tool-ui.com/)
  - [Vercel AI SDK - AI Elements](https://ai-sdk.dev/elements)
  - [nlux](https://docs.nlkit.com/nlux)

- Agent _[Multi-Agent Frameworks Comparison](https://multiagentbook.com/labs/frameworks/)_
  - [Vercel AI SDK](https://ai-sdk.dev)
  - [mastra](https://github.com/mastra-ai/mastra)
  - [@huggingface/agents](https://huggingface.co/blog/agents-js)
  - [AutoGen](https://microsoft.github.io/autogen/)
  - [SuperAGI](https://github.com/TransformerOptimus/SuperAGI)
  - [Langroid](https://langroid.github.io/langroid/)
  - [openai-agents](https://github.com/openai/openai-agents-python) - 构建多智能体工作流。
  - [VoltAgent](https://voltagent.dev/)
  - [Agent Development Kit](https://google.github.io/adk-docs/) - **Google 发布**。
  - [Genkit](https://github.com/firebase/genkit) - **Google 发布**。
  - [goose](https://block.github.io/goose/) - 本地优先的智能体开发框架，**AAIF 项目**。
  - [CopilotKit](https://www.copilotkit.ai/) - 构建传统应用中的 AI 智能体助理的框架。

- MCP Server
  - [FastMCP](https://gofastmcp.com/) - Python 用来构建标准 MCP 应用的框架。

- Low Code
  - [flowise](https://flowiseai.com/) - 开源 UI 可视化工具，用于构建定制的 LLM 编排流程和 AI 代理。

- Others
  - [LMQL](https://lmql.ai/) - LLMs 编程语言。
  - [Awesome AI Memory](https://github.com/topoteretes/awesome-ai-memory)

[`Go Top ↑`](#awesome-ai-dev-list)

## 其它

_Others._

- Open source pre-trained models
  - [FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) - 金融领域的预训练模型。
- Articals
  - [post-training-101](https://tokens-for-thoughts.notion.site/post-training-101)

[`Go Top ↑`](#awesome-ai-dev-list)
