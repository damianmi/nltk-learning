# 自然语言处理学习笔记
## 自然语言处理概念
从广义上讲，“自然语言处理”（Natural Language Processing 简称NLP）包含所有用计算机对自然语言进行的操作，从最简单的通过计数词出现的频率来比较不同的写作风格，到最复杂的完全“理解”人所说的话，至少要能达到对人的话语作出有效反应的程度。
### 自然语言处理的主要范畴
* 文本朗读（Text to speech）/语音合成（Speech synthesis）
* 语音识别（Speech recognition）
* 中文自动分词（Chinese word segmentation）
* 词性标注（Part-of-speech tagging）
* 句法分析（Parsing）
* 自然语言生成（Natural language generation）
* 文本分类（Text categorization）
* 信息检索（Information retrieval）
* 信息抽取（Information extraction）
* 文字校对（Text-proofing）
* 问答系统（Question answering）
* 机器翻译（Machine translation）
* 自动摘要（Automatic summarization）
* 文字蕴涵（Textual entailment）
### 自然语言处理的研究难点
* 单词的边界界定
* 词义的消歧
* 句法的模糊性
* 有瑕疵的或不规范的输入
* 语言行为与计划
### 技术公司
* InteracTIonsCorporaTIon
* Attensity
* DigitalReasoning
* NetBaseSolutions
* Quid
* AlphaSense
* VoiceBase
* Edgecase
* 清华大学自然语言处理与人文计算实验室
* 北京大学计算语言学教育部重点实验室
* 中科院计算所自然语言处理研究组
* 哈尔滨工业大学
* 搜狗
* 百度
* 科大讯飞
## 自然语言处理学习参考内容
http://www.nltk.org/
## 自然语言工具包（NLTK）
获取和处理语料库：nltk.corpus	语料库和词典的标准化接口<br>
字符串处理：nltk.tokenize,nltk.stem	分词，句子分解提取主干
搭配发现：nltk.collocations	t-检验，卡方，点互信息PMI
词性标识符：nltk.tag	n-gram，backoff，Brill，HMM，TnT
分类：nltk.classify,nltk.cluster	决策树，最大熵，贝叶斯，EM，k-means
分块：nltk.chunk	正则表达式，n-gram，命名实体
解析：nltk.parse	图表，基于特征，一致性，概率，依赖
语义解释：nltk.sem,nltk.inference	λ演算，一阶逻辑，模型检验
指标评测：nltk.metrics	精度，召回率，协议系数
概率与估计：nltk.probability	频率分布，平滑概率分布
应用：nltk.app,nltk.chat	图形化的关键词排序，分析器，WordNet查看器，聊天机器人
语言学领域的工作：nltk.toolbox	处理SIL工具箱格式的数据

