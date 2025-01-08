# easyLLM
Local deployed storm.

It has online mode: [New Conversation](https://storm.genie.stanford.edu/)



# 初始目标

- [stanford-oval/storm: An LLM-powered knowledge curation system that researches a topic and generates a full-length report with citations.](https://github.com/stanford-oval/storm)

storm 提供了完整的部署方法。



# 大模型辅助编程开发路线

一些工具路线实现对话并关联项目文件与LLM 交互：
- cursor/windsurf
- vscode + copilot 自带gpt4o,o1 preview, sonnet （edu 邮箱免费使用）
- vscode + roc line + 各种LLM（deepseek..）（OpenRoute 或gemini flash API 免费）



其他工具：
- 更好的让大模型阅读项目文件结构 [Repo Prompt](https://repoprompt.com/)；
- github 代码总结大师 [Gitingest](https://gitingest.com/)；



# LLM 资源

## API

- [kkkunny/free-llm-collect: 搜集免费的LLM（大语言模型）API（GPT、Claude、BingCopilot、Llama、Gemini）](https://github.com/kkkunny/free-llm-collect)
- [OpenRouter](https://openrouter.ai/)
  - 可以通过free 搜索，或升序选择便宜的模式：[Models: 'free' | OpenRouter](https://openrouter.ai/models?order=pricing-low-to-high&q=free)

- https://ai.google.dev/gemini-api/  Google 为所有开发者提供了 Gemini 的免费调用方式：只要频率不高于每分钟 15 次即可——对于 AI 辅助编程而言足矣。



## multiGPT

- [快速开始 | MetaGPT](https://docs.deepwisdom.ai/v0.7/zh/guide/get_started/quickstart.html)



# 其他资料

1. [AutoSurveys/AutoSurvey](https://github.com/AutoSurveys/AutoSurvey)
2. [binary-husky/gpt_academic: 为GPT/GLM等LLM大语言模型提供实用化交互接口，特别优化论文阅读/润色/写作体验，模块化设计，支持自定义快捷按钮&函数插件，支持Python和C++等项目剖析&自译解功能，PDF/LaTex论文翻译&总结功能，支持并行问询多种LLM模型，支持chatglm3等本地模型。接入通义千问, deepseekcoder, 讯飞星火, 文心一言, llama2, rwkv, claude2, moss等。](https://github.com/binary-husky/gpt_academic)
