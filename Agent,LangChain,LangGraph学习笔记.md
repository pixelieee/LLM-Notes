# Agent,LangChain,LangGraph,LLM学习资源整理

## 手写Agent

### 1. 通义千问实现模块化Agent

​	视频：[手把手带你从0到1实现大模型agent](https://www.bilibili.com/video/BV1Sz421m7Rr/?share_source=copy_web&vd_source=903df22429e412249f19f6838f855e27)

​	代码：[agent_from_0to1](https://github.com/Yazooliu/agent_from_0t1)

### 2. 通义千问实现简易Agent

​	视频：[通义千问-一起写个agent吧！](https://www.bilibili.com/video/BV1QF4m177Rx/?share_source=copy_web&vd_source=903df22429e412249f19f6838f855e27)

​	代码：[agent](https://github.com/owenliang/agent)

## LangChain

### 1. LangChain入门

- 模型，提示和解析器
- 记忆
- 链
- 基于文档的问答
- 评估
- Agent

​	官方视频：[LangChain for LLM Application Development](https://learn.deeplearning.ai/courses/langchain/lesson/1/introduction)

​	中文字幕：[(超爽中英!) 2024公认最好的【吴恩达LangChain+RAG】教程！更适合中国宝宝体质，全程干货无废话，学完成为AGI大佬！（附课件+代码）](https://www.bilibili.com/video/BV1TJ4zemETf/?share_source=copy_web&vd_source=903df22429e412249f19f6838f855e27)

​	官方代码：在官方视频侧栏的Jupyter NoteBook中点击File->Open

### 2. LangChian进阶

- OpenAI 函数调用
- LangChain 表达式语言(LCEL)
- LangChain中的OpenAI函数调用
- Tagging and Extraction 标记和提取
- 工具和路由
- 对话Agent

​	官方视频：[Functions,Tools and Agents with LangChain](https://learn.deeplearning.ai/courses/functions-tools-agents-langchain/lesson/1/introduction)

​	中文字幕：[吴恩达《使用LangChain的函数、工具和代理》|Functions, Tools and Agents with LangChain（GPT4-中英字幕）]( https://www.bilibili.com/video/BV1oG411k7HU/?share_source=copy_web&vd_source=903df22429e412249f19f6838f855e27)

​	官方代码：在官方视频侧栏的Jupyter NoteBook中点击File->Open

## LangGraph

### 1. LangGraph更快速构建多智能体

- 从零搭建Agent
- LangGraph组件
- 智能体化搜索工具
- 持久性和流
- 循环中的人工操作
- 实现写文章的Agent
- LangChain资源

​	官方视频：[AI Agents in LangGraph](https://learn.deeplearning.ai/courses/ai-agents-in-langgraph/lesson/1/introduction)

​	中文字幕：[吴恩达&langchain《用LangGraph搭建智能体|AI Agents in LangGraph》【短课英字可关】](https://www.bilibili.com/video/BV1bi421v7oD/?p=3&share_source=copy_web&vd_source=903df22429e412249f19f6838f855e27)

​	官方代码：在官方视频旁边的Jupyter NoteBook中点击File->Open

## LangChain,LangGraph结合本地LLM（自定义方法）

- [一起学大模型-动手写一写LangChain调用本地大模型（1）](https://blog.csdn.net/kljyrx/article/details/139361629?fromshare=blogdetail&sharetype=blogdetail&sharerId=139361629&sharerefer=PC&sharesource=Pure12321&sharefrom=from_link)
- [一起学大模型-动手写一写LangChain调用本地大模型（2）](https://blog.csdn.net/kljyrx/article/details/139362030?fromshare=blogdetail&sharetype=blogdetail&sharerId=139362030&sharerefer=PC&sharesource=Pure12321&sharefrom=from_link)
- [【教程】LLM集成进LangChain工具，并实现本地知识库的问答](https://blog.csdn.net/qq_36187610/article/details/131900517?fromshare=blogdetail&sharetype=blogdetail&sharerId=131900517&sharerefer=PC&sharesource=Pure12321&sharefrom=from_link)
- [langchain加载本地中文模型的4种方法](https://blog.csdn.net/2401_85373691/article/details/141824975?fromshare=blogdetail&sharetype=blogdetail&sharerId=141824975&sharerefer=PC&sharesource=Pure12321&sharefrom=from_link)
- 官方教程：[How to create a custom LLM class](https://python.langchain.com/docs/how_to/custom_llm/)
- 官方教程：[How to create a custom chat model class](https://python.langchain.com/docs/how_to/custom_chat_model/)
- 官方文档：[language_models](https://python.langchain.com/api_reference/core/language_models.html)
- 稳定大模型输出格式：[利用Prediction Guard在LangChain中保护你的模型输出](https://blog.csdn.net/bhawfgrcbtwny/article/details/142350243)

## QwenAgent,LangChain,LangGraph结合本地LLM (部署方法)

- qwen_agent与本地部署的qwen如何适配(ollama或vllm部署)：[QwenLM/Qwen-Agent/issue94](https://github.com/QwenLM/Qwen-Agent/issues/94),[QwenLM/Qwen-Agent/issue95](https://github.com/QwenLM/Qwen-Agent/issues/95)
- dashscope与OpenAI接口兼容：[OpenAI Chat 接口兼容](https://help.aliyun.com/zh/dashscope/developer-reference/compatibility-of-openai-with-dashscope)
- ollama支持langchain_openai.ChatOpenAI接口：[ollama与ChatOpenAI接口](https://blog.csdn.net/qq_40582088/article/details/140605223?fromshare=blogdetail&sharetype=blogdetail&sharerId=140605223&sharerefer=PC&sharesource=Pure12321&sharefrom=from_link)
- ollama部署llama3.2，结合openai接口：[ollama llama3.2](https://blog.csdn.net/qq_39749966/article/details/136594143?fromshare=blogdetail&sharetype=blogdetail&sharerId=136594143&sharerefer=PC&sharesource=Pure12321&sharefrom=from_link)
- FASTAPI部署Qwen-VL-Chat：[qwen-vl-chat FASTAPI](https://blog.csdn.net/liukangjie520/article/details/140270326?fromshare=blogdetail&sharetype=blogdetail&sharerId=140270326&sharerefer=PC&sharesource=Pure12321&sharefrom=from_link)
- Qwen2-VL vllm部署：[Qwen2-VL Deployment](https://github.com/QwenLM/Qwen2-VL?tab=readme-ov-file#deployment) (ollama不支持Qwen2-VL。注意vllm=0.6.1, transformer=4.45.0, 文中的pip install git+https://github.com/huggingface/transformers@21fac7abba2a37fae86106f87fcf9974fd1e3830 改为：pip install git+https://github.com/huggingface/transformers@21fac7abba2a37fae86106f87fcf9974fd1e3830  accelerate)
- langchain中 create_openai_tools_agent或create_openai_functions_agent与qwen模型不支持的问题：[qwen langchain](https://github.com/QwenLM/Qwen2.5/issues/15)
- 本地部署的LLM的function调用：几乎所有的开源推理框架(vllm,SGLang,ollama,llama.cpp等)中都没有实现函数调用[issue](https://github.com/QwenLM/Qwen2.5/issues/474#issuecomment-2148834159)
- 如何用vllm对qwen2-vl-72b进行推理？[link](https://github.com/QwenLM/Qwen2-VL/issues/518)

## VLLM, 通义千问等

官方社区文档（通义千问、VLLM，API使用）：[qwen chat model API使用](https://python.langchain.com/api_reference/community/chat_models/langchain_community.chat_models.tongyi.ChatTongyi.html#langchain_community.chat_models.tongyi.ChatTongyi)，[llms.vllm.VLLM](https://python.langchain.com/api_reference/community/llms/langchain_community.llms.vllm.VLLM.html)，[qwen llms API 使用](https://python.langchain.com/api_reference/community/llms/langchain_community.llms.tongyi.Tongyi.html#langchain_community.llms.tongyi.Tongyi)

Agent: [Qwen2-VL-Agent(Function Calling&Tool Calling)](https://github.com/QwenLM/Qwen2-VL?tab=readme-ov-file#function-calling),[[the function calling example]](https://github.com/QwenLM/Qwen-Agent/blob/main/examples/qwen2vl_function_calling.py),[[the agent example]](https://github.com/QwenLM/Qwen-Agent/blob/main/examples/qwen2vl_assistant_tooluse.py)

qwen_agent源码：[Qwen-Agent](https://github.com/QwenLM/Qwen-Agent)

## Qwen_Agent相关

- 用户描述不能调用对应的function[link](https://github.com/QwenLM/Qwen-Agent/issues/346)
- 无法自动选择tool [link](https://github.com/QwenLM/Qwen-Agent/issues/344vllm)
- 不用GUI的Group Agent demo [link](https://github.com/QwenLM/Qwen-Agent/issues/342)
- function_call调用问题 [link](https://github.com/QwenLM/Qwen-Agent/issues/339)
- function_call重试次数限制 [link](https://github.com/QwenLM/Qwen-Agent/issues/33)
- vllm部署的qwen2vl qwen2vl_function_calling.py报错 [link](https://github.com/QwenLM/Qwen-Agent/issues/336)
- 如何自己添加工具 [link](https://github.com/QwenLM/Qwen-Agent/issues/5)
- qwen2 vl agent vllm不支持视频输入 [link](https://github.com/QwenLM/Qwen2-VL/issues/113)
- qwen2 vl 目前不支持ollama部署 [link](https://github.com/QwenLM/Qwen2-VL/issues/7)

## RAG,MultiModal

### Chat with Videos: 

- 交互式Demo和多模态RAG系统架构
- 多模态嵌入
- 预处理视频
- 从向量库中进行多模态检索
- LVLMs介绍
- 使用多模态Langchain进行多模态RAG

官方视频：[MultiModal RAG: Chat with Videos](https://learn.deeplearning.ai/courses/multimodal-rag-chat-with-videos/lesson/8/conclusion)

中文字幕：[吴恩达《多模态RAG：与视频对话|Multimodal RAG: Chat with Videos》中英字幕（豆包](https://www.bilibili.com/video/BV1mUtTehEsy/?share_source=copy_web&vd_source=903df22429e412249f19f6838f855e27)

官方代码：在官方视频侧栏的Jupyter NoteBook中点击File->Open

## LLMs,RLHF

### 1. 大模型预训练

- [大模型预训练看这个视频就够了](https://www.bilibili.com/video/BV1xhYtewEum/?share_source=copy_web&vd_source=903df22429e412249f19f6838f855e27) [[code]](代码：https://github.com/RethinkFun/LLM)
- [从零开始训练大模型](https://www.bilibili.com/video/BV1a14y1o7fr/?share_source=copy_web&vd_source=903df22429e412249f19f6838f855e27) [[知乎article]](https://zhuanlan.zhihu.com/p/636270877)

### 2. SFT监督微调

- [大模型微调看这个视频就够了 SFT NEFTune](https://www.bilibili.com/video/BV1gmWDeLEMZ/?share_source=copy_web&vd_source=903df22429e412249f19f6838f855e27) [[code]](https://github.com/RethinkFun/sft/tree/main)

### 3. RLHF PPO

- [RLHF原理 吴恩达](【吴恩达《从人类反馈中进行强化学习RLHF, Reinforcement Learning from Human Feedback》（中英字幕）】 https://www.bilibili.com/video/BV1R94y1P7QX/?share_source=copy_web&vd_source=903df22429e412249f19f6838f855e27)

- [代码实现大模型强化学习(PPO)，看这个视频就够了](https://www.bilibili.com/video/BV1rixye7ET6/?share_source=copy_web&vd_source=903df22429e412249f19f6838f855e27) [[code]](https://github.com/RethinkFun/trian_ppo/tree/main/train_ppo)

- [基于TRL框架训练大语言模型,DPO,PPO方法.](https://www.bilibili.com/video/BV1bu4y1w7Dz/?share_source=copy_web&vd_source=903df22429e412249f19f6838f855e27) [[code]](https://github.com/lansinuote/Simple_TRL)

- [RLHF训练法从零复现,代码实战,大语言模型训练](https://www.bilibili.com/video/BV13r42177Hk/?share_source=copy_web&vd_source=903df22429e412249f19f6838f855e27) [[code]](https://github.com/lansinuote/Simple_TRL)

## Qwen源码

- [Qwen源码解析](https://blog.csdn.net/weixin_43214046/article/details/140097346)

- [一文彻底搞懂Qwen2源码解析](https://blog.csdn.net/2201_75499313/article/details/142674883)
- [Qwen2源码解析](https://zhuanlan.zhihu.com/p/707921243)
- [Qwen2-VL源码](https://github.com/huggingface/transformers/tree/main/src/transformers/models/qwen2_vl)
- [Qwen2源码](https://github.com/huggingface/transformers/tree/main/src/transformers/models/qwen2)
- [llama源码](https://github.com/huggingface/transformers/tree/main/src/transformers/models/llama)

## 其他学习资源

- 官方试验文档：[video_captioning](https://python.langchain.com/api_reference/experimental/video_captioning.html)
- LangGraph官方文档：[LangGraph](https://langchain-ai.github.io/langgraph/reference/)
- LangChain基础教程：[Langchain Tutorials](https://python.langchain.com/docs/tutorials/)
- LangChain实践教程：[How to Tutorials](https://python.langchain.com/docs/how_to/)
- prompt设计：[prompt hub](https://smith.langchain.com/hub)
- vllm支持模型：[vllm models](https://docs.vllm.ai/en/latest/models/supported_models.html)
- ollama支持模型：[ollama models](https://ollama.com/)
- llamacpp 支持模型 [llamacpp models](https://github.com/ggerganov/llama.cpp/tree/master/models)
