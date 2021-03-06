## lecture 1: introduction

这一讲是绪论，简单记两句。

新 CS224N 的幻灯比起原来 CS224d 的有改进(可惜视频只能看旧的)。一个细节是每一讲开头会给出 Lecture Plan，告诉你有哪些主要内容，方便你把握脉络。Lecture 1 的主要内容：
* 什么是 NLP，人类语言的特点
* 什么是深度学习
* 课程相关说明
* 为什么理解语言很困难
* 深度学习在 NLP 上的应用简介

人类语言是一种 discrete/symbolic/categorical signaling system. 大部分单词只是语言之外实体的一种符号（symbols for an extra-linguistic entity)。

传统的机器学习在实践中常常要把大部分时间用在人工选择特征上，而且对领域相关的知识要求比较高。而深度学习则让机器自动去学习好的特征，节省了人的工作量。约从 2010 年起，深度学习的表现开始在很多领域超过了其他机器学习技术，最先是语音识别和图像识别领域，后来才是 NLP。

为什么 NLP 很困难？因为，对人类语言的理解有赖于真实世界知识、常识、上下文等一系列复杂因素。另外，语言中常常有语义含糊或歧义的情况，不像编程语言那么严格清晰。

本讲展示了深度学习在 NLP 不同问题上的应用，包括构词分析、句法分析、语义分析、情感分析、问答、机器翻译等。Richard Socher 演示了 Metamind 的几个例子，蛮神奇的。最难得的是，这些不同层面或领域的问题，采用的深度学习模型架构其实都差不多，说明这一技术具有很强的通用性。
