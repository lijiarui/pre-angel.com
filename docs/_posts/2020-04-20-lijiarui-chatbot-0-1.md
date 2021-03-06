---
title: AI与人，“替代”还是 “共生”
author: jiarui-li
categories: news
tags:
  - chatbot
  - juzibot
  - luqi
image: assets/2020/04-lijiarui-chatbot-0-1/teaser.jpg
---
> 在过去的几百年里，每次革命都在摧毁一些职业的同时创造一些新的工作岗位。人工智能时代也是一样，单纯的智能不会解决所有的问题，机器和人将协同工作。让机器做机器擅长的事情，让人类发挥人类的特长，让人工智能拓展人类智能。机器与人，和而共生，彼此关爱，共享未来。

对于人工智能的能力，基于我过去服务客户的经历，有一些自己的思考，以下内容选自我的新书：[《Chatbot从0到1：对话式交互设计实践指南》](https://item.jd.com/12630213.html)，欢迎关注。

## 1. 很抱歉，我做了一个 59 分的机器人

“0 到 100，你给你的机器人打多少分？”这是第一次见陆奇博士的时候，他问我的问题。

那是一个深秋，在雕刻时光咖啡厅里，作为 YC 中国的第一批成员，我们团队和陆奇博士的第一次 Office Hour。

我非常绝望的看着我的合伙人，前亚马逊工程师[高原](https://pre-angel.com/peoples/yuan-gao/)，想到过去 2 年我们做过的大大小小的项目，有上市公司的客户，也有初创公司的客户，无一不对所谓的 Chatbot 失望。而在这一刻，我不得不向我们的导师坦白，我们做了让人失望的产品。

“我给我们的机器人打 59 分，但是我会和我的客户说这只是 40 分的机器人，尽可能地降低用户预期，并引导真人和机器人共同为客户服务。”

我深吸了一口冷气，然后一口气说完。要知道，在一个各大企业都在号称 90%的准确率的人工智能元年，我需要多大的勇气才敢承认，我的创业项目并不是“酷炫 fancy” 的。

没想到的是，陆奇博士竟然跟我的想法一样。

> 在 2014 年发起“小冰”项目的时候，我认为人工智能已迎来拐点，移动互联网使数据和服务进一步结构化，而这些结构化的数据和服务，可以很方便地与人工智能小冰对接，“就像电影《超能陆战队》中的‘大白’，任何一个类别的信息、知识与服务，都可以像插卡那样与小冰对接，这可能颠覆未来的互联网行业。”我认为那时已经能搭建一个 90 分的 Chatbot 了，但是，我过于乐观了。
> 来自：陆奇博士

于是，那个下午及后来的很多封邮件往来中，我和陆奇博士探讨了很多如何接受智能对话的现状，以及使用人机协作逐步构建一个 90 分的对话系统的方法及路径。

## 2. 对话智能解决重复思考

尽管人工智能技术对人类社会带来的变革与工业革命相较可能规模更大，来势更为迅猛，随之而发展起来的机器人注定将取代很多人类的工作。但本质上，这个替代人类工作的过程，和工业时代并没有太多差异。

笔者认为，工业革命解决了“重复体力劳动”的事情，人工智能未来解决“重复脑力劳动”的事情。

关于大众想象中的智能，李开复老师在他的书《人工智能》中是这样描述的：

普通群众所遐想的人工智能属于强人工智能，它属于通用型机器人，也就是20世纪 60 年代人工智能研究人员提出的理念。它能够和人类一样对世界进行感知和交互，通过自我学习的方式对所有领域进行记忆、推理和解决问题。

这样的强人工智能需要具备以下能力：

- 存在不确定因素时进行推理、使用策略、解决问题、制定决策的能力。
- 知识表示的能力，包括常识性知识的表示能力。
- 规划能力。
- 学习能力。
- 使用自然语言进行交流沟通的能力。
- 将上述能力整合起来实现既定目标的能力。

这些能力在常人看来都很简单，因为自己都具备。但由于技术的限制，计算机很难具备以上能力，这也是为什么现阶段人工智能很难达到常人思考的水平。

在笔者看来，“通过自我学习的方式对所有领域进行记忆、推理和解决问题”，是机器和人 大的区别，也是机器无法解决的问题。

我们可以从心理学家的说法中寻找答案：在《思考，快与慢》这本书中，作者将人类思考和认知工作分成了两个系统来处理：系统 1 是快思考：无意识、快速、不怎么费脑力、无须推理。系统 2 是慢思考：需要调动注意力、过程更慢、费脑力、需要推理。解决问题时，系统 1 先出面，遇到搞不定的事情，系统 2 会出面解决。

而人工智能只能解决系统 1 的部分，通过大量的数据训练，帮助机器训练一个比人脑反应更加迅速的 24 小时运转的大脑。而对应到系统 2 的部分，需要结合常识和所学的知识进行推理，才能进一步得出结论。

## 3. “替代”还是“共生”

智能对话的核心价值，应该在解决问题的能力上，而不是停留在具体是人还是机器回答的这个表面问题上。

迄今为止，没有任何已知的途径和方法能够和人类一样对世界进行感知和交互、通过自我学习的方式解决所有领域的问题。各种“奇点”假说推论未来人工智能技术可能以指数级成长，却忽略了这样的指数级成长需要的是一系列可能需要百年甚至永远都不可能实现的重大技术发明和突破。

而解决的唯一方式，唯有“共生”。将大量的、重复的、耗时的事务交给机器人，让员工从疲于应付的情况下解放出来，让员工发挥主观能动性，去执行具有更高价值，有创造性，需要情感投入的事务，而让机器人不知疲倦地、全天候地、更加快速精确地执行烦琐重复的事务。例如，在客户服务中，未来实现高效人工智能的道路是协作，协作可以通过两种主要方式应用。

### 3.1 增强人类智慧

宏观上看，机器所掌握的用户信息比任何一个员工都多。这时，机器可以扩充员工的大脑。在和用户沟通的时候，机器可以给出这个用户的所有信息辅助回答。机器通过分析，给出推荐的下一步操作，让员工主动选择。

### 3.2 增强人的能力

人是需要休息的，在同一个时间段能处理的信息量是极其有限的，而 24 小时持续运转、消息并发量极大的机器的即时回复和快速查找功能，正好可以增强人的能力。例如，使用智能对话处理初始客户查询，因为这些请求大多数都很简单且易于理解。一旦机器人无法处理更多请求，系统就通过自动客户服务流程传递给人工，极大地增强了运营团队的响应速度和并发处理能力。

这种人机协作的处理方式，在不增加人力的情况下，实现了更高的交互量，进而降低了每次交互的平均成本，并提高了客户满意度。同时，随着机器交互越来越多，企业有了足够的数据和流程，可以进一步探索自动化流程。有了数据的支撑，就可以加快决策流程并计算出明确的投资回报率。

就像工业机器替代体力劳动者那样，越来越多的脑力劳动者也会因智能机器人的加入得以解放，随之而来的是工作流的调整和组织的重构。

在过去的几百年里，每次革命都在摧毁一些职业的同时创造一些新的工作岗位。人工智能时代也是一样，单纯的智能不会解决所有的问题，机器和人将协同工作。孙正义曾预测，未来 30 年，将有 100 亿人类和 100 亿机器人共同生活在地球上，人类和机器人并不是你死我活的关系，而是共生。张小龙也说：“希望我们的产品能成为用户的朋友，而不仅仅是工具。”笔者认为，这句话套用到人工智能时代同样适用。让机器做机器擅长的事情，让人类发挥人类的特长，让人工智能拓展人类智能。机器与人，和而共生，彼此关爱，共享未来。

## 4. 关于 《Chatbot 从 0 到 1》

本书由陆奇等大咖亲自作序，陆奇博士的做序内容见： [陆奇：Chatbot将成为未来的基础设施和重要的人机交互窗口](https://pre-angel.com/juzibot-chatbot-0-1/)

![pic-1](/assets/2020/04-lijiarui-chatbot-0-1/buy-book.png)

### 4.1 本书摘要：

[《Chatbot从0到1：对话式交互设计实践指南》](https://item.jd.com/12630213.html)内容共5部分:

- 第1部分从人工智能的发展带动对话式交互引出Chatbot的应用场景及其分类；
- 第2部分和第3部分从需求分析、流程设计、数据处理、对话脚本撰写、系统搭建、对话任务测评、平台渠道集成、运营反馈等方面，对Chatbot的整个生命周期进行了详细分析和介绍；
- 第4部分通过案例分析，对Chatbot进行了实践；
- 第5部分总结了目前对话式交互的局限性，并展望了基于人工智能发展Chatbot的机会。

### 4.2 目标读者：

[《Chatbot从0到1：对话式交互设计实践指南》](https://item.jd.com/12630213.html)适合希望从事Chatbot行业的读者阅读，尤其是正在考虑将业务切入 Chatbot领域的决策者，即将或正在从事Chatbot专业工作的产品经理和项目经理，以及希望了解Chatbot领域工作流程的开发人员。

![pic-2](/assets/2020/04-lijiarui-chatbot-0-1/chatbot-0-1.jpg)

[《Chatbot从0到1：对话式交互设计实践指南》购买链接](https://item.jd.com/12630213.html)
