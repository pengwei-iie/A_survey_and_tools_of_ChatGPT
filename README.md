# A_survey_and_tools_of_ChatGPT
Some survey and tools of ChatGPT or ChatGPT-Style Model.

为了整理相关的类ChatGPT工具，写下这篇文档，仅供学术研究:smile:。以下工具来源于github项目收集和整理，喜欢的朋友可以star!

## 二维码制作demo，让你的名片不再黑白

这个还挺有意思的，直接去上面申请就好，然后使用命令 /qrart 和 prompt

![image](https://github.com/pengwei-iie/A_survey_and_tools_of_ChatGPT/assets/30322673/73305041-9c70-491a-b13f-748b6844ef54)

下图是自己做的一个demo

![qrcode-ok](https://github.com/pengwei-iie/A_survey_and_tools_of_ChatGPT/assets/30322673/be64cb7a-aed6-44db-a808-472c9a4b0122)

[访问链接](https://discord.com/)

## pdf, word 文档阅读功能

claude.ai 直接出了类似chatpdf的工具，直接杀死一系列好吧

支持同时对最多 5 个 10 MB 以内文档同时进行总结分析。支持 pdf、text、csv 等格式。

目前已经面向 UK 和 US 用户免费开放使用，有兴趣的人可以科学尝试一下，在 GPT-4 需要付费订阅的情况下，这是一个不错的替代选择。

<img width="537" alt="43a8b6498fc80ad21e1edaa34a2a94b" src="https://github.com/pengwei-iie/A_survey_and_tools_of_ChatGPT/assets/30322673/76289abb-cc65-4bdb-ba36-f623356dd9ce">

[访问链接](https://claude.ai/chat/b4a8bef8-009e-44ea-a395-cf1cbcadcf6a)

## 为ChatGPT/GLM提供图形交互界面，特别优化论文阅读/润色/写作体验

这个厉害了，非常适合学术研究的人使用！

[访问链接](https://github.com/binary-husky/gpt_academic)

<div align="center">

功能（⭐= 近期新增功能） | 描述
--- | ---
一键润色 | 支持一键润色、一键查找论文语法错误
一键中英互译 | 一键中英互译
一键代码解释 | 显示代码、解释代码、生成代码、给代码加注释
[自定义快捷键](https://www.bilibili.com/video/BV14s4y1E7jN) | 支持自定义快捷键
模块化设计 | 支持自定义强大的[函数插件](https://github.com/binary-husky/gpt_academic/tree/master/crazy_functions)，插件支持[热更新](https://github.com/binary-husky/gpt_academic/wiki/%E5%87%BD%E6%95%B0%E6%8F%92%E4%BB%B6%E6%8C%87%E5%8D%97)
[自我程序剖析](https://www.bilibili.com/video/BV1cj411A7VW) | [函数插件] [一键读懂](https://github.com/binary-husky/gpt_academic/wiki/chatgpt-academic%E9%A1%B9%E7%9B%AE%E8%87%AA%E8%AF%91%E8%A7%A3%E6%8A%A5%E5%91%8A)本项目的源代码
[程序剖析](https://www.bilibili.com/video/BV1cj411A7VW) | [函数插件] 一键可以剖析其他Python/C/C++/Java/Lua/...项目树
读论文、[翻译](https://www.bilibili.com/video/BV1KT411x7Wn)论文 | [函数插件] 一键解读latex/pdf论文全文并生成摘要
Latex全文[翻译](https://www.bilibili.com/video/BV1nk4y1Y7Js/)、[润色](https://www.bilibili.com/video/BV1FT411H7c5/) | [函数插件] 一键翻译或润色latex论文
批量注释生成 | [函数插件] 一键批量生成函数注释
Markdown[中英互译](https://www.bilibili.com/video/BV1yo4y157jV/) | [函数插件] 看到上面5种语言的[README](https://github.com/binary-husky/gpt_academic/blob/master/docs/README_EN.md)了吗？
chat分析报告生成 | [函数插件] 运行后自动生成总结汇报
[PDF论文全文翻译功能](https://www.bilibili.com/video/BV1KT411x7Wn) | [函数插件] PDF论文提取题目&摘要+翻译全文（多线程）
[Arxiv小助手](https://www.bilibili.com/video/BV1LM4y1279X) | [函数插件] 输入arxiv文章url即可一键翻译摘要+下载PDF
Latex论文一键校对 | [函数插件] 仿Grammarly对Latex文章进行语法、拼写纠错+输出对照PDF
[谷歌学术统合小助手](https://www.bilibili.com/video/BV19L411U7ia) | [函数插件] 给定任意谷歌学术搜索页面URL，让gpt帮你[写relatedworks](https://www.bilibili.com/video/BV1GP411U7Az/)
互联网信息聚合+GPT | [函数插件] 一键[让GPT从互联网获取信息](https://www.bilibili.com/video/BV1om4y127ck)回答问题，让信息永不过时
⭐Arxiv论文精细翻译 ([Docker](https://github.com/binary-husky/gpt_academic/pkgs/container/gpt_academic_with_latex)) | [函数插件] 一键[以超高质量翻译arxiv论文](https://www.bilibili.com/video/BV1dz4y1v77A/)，目前最好的论文翻译工具
⭐[实时语音对话输入](https://github.com/binary-husky/gpt_academic/blob/master/docs/use_audio.md) | [函数插件] 异步[监听音频](https://www.bilibili.com/video/BV1AV4y187Uy/)，自动断句，自动寻找回答时机
公式/图片/表格显示 | 可以同时显示公式的[tex形式和渲染形式](https://user-images.githubusercontent.com/96192199/230598842-1d7fcddd-815d-40ee-af60-baf488a199df.png)，支持公式、代码高亮
多线程函数插件支持 | 支持多线调用chatgpt，一键处理[海量文本](https://www.bilibili.com/video/BV1FT411H7c5/)或程序
启动暗色[主题](https://github.com/binary-husky/gpt_academic/issues/173) | 在浏览器url后面添加```/?__theme=dark```可以切换dark主题
[多LLM模型](https://www.bilibili.com/video/BV1wT411p7yf)支持 | 同时被GPT3.5、GPT4、[清华ChatGLM2](https://github.com/THUDM/ChatGLM2-6B)、[复旦MOSS](https://github.com/OpenLMLab/MOSS)同时伺候的感觉一定会很不错吧？
⭐ChatGLM2微调模型 | 支持加载ChatGLM2微调模型，提供ChatGLM2微调辅助插件
更多LLM模型接入，支持[huggingface部署](https://huggingface.co/spaces/qingxu98/gpt-academic) | 加入Newbing接口(新必应)，引入清华[Jittorllms](https://github.com/Jittor/JittorLLMs)支持[LLaMA](https://github.com/facebookresearch/llama)和[盘古α](https://openi.org.cn/pangu/)
更多新功能展示 (图像生成等) …… | 见本文档结尾处 ……

</div>

## 微软接入绘图功能

每个账户一开始有10次快速生成的机会，后面不需要额外的付费，但是速度会慢一些。

<img src="https://user-images.githubusercontent.com/30322673/227185546-c2391749-7332-4e02-8064-3ab8146708a3.png" width="500px">

<img src="https://user-images.githubusercontent.com/30322673/227156241-aa4ce181-3963-4d0b-b85b-35ce054a49c5.png" width="500px">

[访问链接](https://www.bing.com/images/create)

## 文心一言

添加到互补速度还是挺快的，具体可以参考下面的[访问链接](yiyan.baidu.com)

C端用户：访问 yiyan.baidu.com，点击『立即体验』，目前可排队体验文心一言

<img src="https://user-images.githubusercontent.com/30322673/227157660-f95f022d-aeee-4c26-8034-af409b557c71.png" width="500px">

## GPT-4 report reading & API list

OpenAI 官网技术报告和API申请接口

- [Report](https://arxiv.org/abs/2303.08774)
- [Join API](https://openai.com/waitlist/gpt-4-api)


## 重磅发布 Copilot X
 
GitHub 将 Copilot 升级为 Copilot X

可以给出bug的意见：

<img src="https://user-images.githubusercontent.com/30322673/227186166-7419ae7f-bbc0-4123-8628-1d1d97c51ff8.png" width="500px">

最新的 GitHub Copilot X 采用了 OpenAI 最新的 GPT-4 模型，也引入了聊天、语音功能，支持拉取请求，回答文档上的问题等等。

 [Copilot Chat 申请 waitlist](https://github.com/github-copilot/chat_waitlist_signup/join)

## 利用ChatGPT做【翻译】、【翻译评价】和【自然语言理解】的评测

来源京东

 - [翻译](https://github.com/Romainpkq/ChatGPT4MT)
 - [翻译评价](https://github.com/Coldmist-Lu/ErrorAnalysis_Prompt)
 - [自然语言理解](https://github.com/WHU-ZQH/ChatGPT-vs.-BERT)

## ChatGLM-6B

来源清华——ChatGLM-6B 是一个开源的、支持中英双语的对话语言模型，基于 General Language Model (GLM) 架构，具有 62 亿参数。结合模型量化技术，用户可以在消费级的显卡上进行本地部署（INT4 量化级别下最低只需 6GB 显存）。ChatGLM-6B 使用了和 ChatGPT 相似的技术，针对中文问答和对话进行了优化。经过约 1T 标识符的中英双语训练，辅以监督微调、反馈自助、人类反馈强化学习等技术的加持，62 亿参数的 ChatGLM-6B 已经能生成相当符合人类偏好的回答。

[访问链接](https://github.com/THUDM/ChatGLM-6B)
   
 ## ChatReviewer
 
来源投稿群大佬。自动审论文的AI助手ChatReviewer，其可以根据论文pdf文件自动生成一份审稿意见。此外其中还包含ChatResponse工具，可自动根据审稿人的评论来生成一对一的回复内容。

![image](https://user-images.githubusercontent.com/30322673/227186420-285d9076-52ae-43f6-8498-d645f553c343.png)

 
 [访问链接](https://github.com/nishiwen1214/ChatReviewer)
 
 ## 反检测机制
 
来源投稿群大佬。可以去判断生成的文本是否由机器产生的。

<img src="https://user-images.githubusercontent.com/30322673/227186670-7cafd222-19d7-448c-b30f-cd04d6d2bb1a.png" width="500px">

 [访问链接](https://github.com/Hello-SimpleAI/chatgpt-comparison-detection)
 
 ## ChatPaper
 
一款论文总结工具，根据用户输入的关键词，自动在arxiv上下载最新的论文，再利用ChatGPT3.5的API接口的总结能力，将论文总结为固定的格式。

![image](https://user-images.githubusercontent.com/30322673/227186773-2c7fb770-2964-4bdb-918d-de8b8a9f2030.png)

 [访问链接](https://github.com/kaixindelele/ChatPaper)
 
 ## Researchgpt
 
一款读论文的工具，可以将论文下载下来，或者直接输入论文的网页链接，然后对其进行提问。帮助不想看论文的你或者需要调研新领域的你！
 
![image](https://user-images.githubusercontent.com/30322673/227422907-4158e8ca-66bb-46fb-af5e-ed3e60be26b3.png)

 [访问链接](https://github.com/mukulpatnaik/researchgpt)

 ## Chat-extension
 
开发的 Chrome 插件，提供了另一种快速阅读论文的工作流。

![930ce956af9ede6cacd3ec274b69d14](https://user-images.githubusercontent.com/30322673/228812844-6289f424-e7f3-49cc-a996-42476ef50e2d.jpg)

 [访问链接](https://github.com/sailist/chatgpt-enhancement-extension)
  
  ## 标注工具
  
 开源数据标注工具🥔Potato，支持几乎所有类型的文本标注任务，只需要通过简单配置就可以生成一个面向标注者的web页面，支持数据管理，标注质量管理等功能，模版库已覆盖20+项目
 
 ![image](https://user-images.githubusercontent.com/30322673/227186890-021f4fdb-d9cb-4e1e-8c33-2903e190d9ef.png)
  
 [访问链接](https://github.com/davidjurgens/potato)
 
 ## ChatGPT-ToolBox
  
 由ChatGPT负责编写的ChatGPT工具箱。除了向ChatGPT提供必要的数据，尽可能不由人类写任何代码。
  
 [访问链接](https://github.com/bigemon/ChatGPT-ToolBox)
 
 感谢大佬们的开源，新的项目持续更新中... :smile:

 下面是一些paper或者博文阅读
 
 # Paper or Blogs
 
 ## Copilot X 3-23 来源 新智元
 
 GPT-4加强版Copilot来了！刚刚，GitHub发布了新一代代码生成工具GitHub Copilot X，动嘴写代码不再是梦。
 
 [访问链接](https://mp.weixin.qq.com/s/ATxJXbXOH9cQnx6VSkTB6A)

 ## 微软必应再进化！接入DALL·E模型 3-22 来源 Cver
 
 微软正式宣布，必应搜索引擎接入了 OpenAI 的 DALL·E 模型，增加了 AI 生成图像的功能。
 
 [访问链接](https://mp.weixin.qq.com/s/omJTedz-8EuTcJG4cFk3Ng)
 
 ## 人工智能 Firefly 3-21 来源 Adobe PS
 
 Adobe Firefly，Adobe的创意生成式AI模型集。它将Adobe创意及数字体验应用的强大功能与人工智能结合，帮助设计师提升设计的效率，突破创意的边界。
 
 [访问链接](https://mp.weixin.qq.com/s/5sYKV-5NU0yr2flvvDziOw)
 
 ## ChatGPT被玩疯了，开始放飞自我 2-24 来源 CSDN
 
 ChatGPT版微软必应上线不到10天…就被网友玩坏了 (3.23更新 有些问题已经得到解决)
 
 [访问链接](https://blog.csdn.net/ganxiwu9686/article/details/129133768?spm=1001.2014.3001.5501)
 
 ## 复旦 MOSS 2-28 来源 CSDN
 
 复旦团队发布国内首个模型MOSS 类ChatGPT
 
 [访问链接](https://blog.csdn.net/ganxiwu9686/article/details/129133768?spm=1001.2014.3001.5501)
