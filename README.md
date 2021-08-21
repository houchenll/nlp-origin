# nlp-learner


## 视频
- [贪心学院 NLP 自然语言处理][1]  
- [cs224n深度学习自然语言处理课程][57]
  - [DeepNLP-models-Pytorch][58] - Pytorch implementations of various Deep NLP models in cs-224n(Stanford Univ)
  - [nlp-tutorial][59] - Natural Language Processing Tutorial for Deep Learning Researchers


## 文章 & ppt
- [The Illustrated BERT, ELMo, and co. (How NLP Cracked Transfer Learning)][36] - bert、ELMO的图解

### NLG
- [Ehud Reiter's Blog][43] - 北大万小军教授强力推荐，该博客对NLG技术、评价与应用进行了深入的探讨与反思
- [自然语言生成：让机器掌握自动创作的本领 - 开放域对话生成及在微软小冰中的实践][45]
- [Evaluating Natural Language Generation with BLEURT][48]


## 院校研究
- [XLORE][39] - XLORE是融合中英文维基和百度百科，对百科知识进行结构化和跨语言链接构建的多语言知识图谱，是中英文知识规模较平衡的大规模多语言知识图谱
- [THU AI TR][40] - 以AMiner全球科技情报大数据挖掘服务平台为基础，聘请领域顶级专家作为顾问，采用人工智能自动生成技术，以严谨，严肃，负责的态度，为您提供深刻的科技洞察报告
    - [2018 自然语言处理 研究报告][41]
    - [2018 机器翻译与人工智能研究报告][42]


## github

### 整理汇集
- [funNLP][2] - 中文NLP资源库，在入门到熟悉NLP的过程中，用到了很多github上的包，遂整理了一下，分享在这里
- [awesome-nlp][20] - A curated list of resources dedicated to Natural Language Processing (NLP)

### 分词
- [jieba][49] - 结巴中文分词
- [pyhanlp][50] - 中文分词 词性标注 命名实体识别 依存句法分析 新词发现 关键词短语提取 自动摘要 文本分类聚类 拼音简繁 自然语言处理

### 过滤
- [textfilter][3] - 敏感词过滤的几种实现+某1w词敏感词库。敏感词包括政治、脏话等话题词汇。其原理主要是基于词典的查找（项目中的keyword文件）

### 检测 & 判断
- [langid][4] - Stand-alone language identification system
- [ngender][7] - 根据姓名来判断性别

### 抽取信息
- [cocoNLP][8] - A Chinese information extraction tool: 邮箱、手机号、身份证号、手机归属地/运营商、地址信息、时间点、人名
- [wordninja][18] - 无空格英文串分割、抽取单词

### 词库 & 语料库
- [Chinese-abbreviation-dataset][10] - 中文缩写库。This is a corpus of Chinese abbreviation, including negative full forms
- [funNLP中文词库][13] - 包括：IT、NLP、中文分词、中文缩写、中文谣言、中英日文名字、停用词、公司名字、动物、医学、历史名人、古诗、同义、反义、否定、地名、成语、拆字、敏感词、汽车品牌、汽车零件、法律、繁简体转换、职业、诗词短句、财经、食物
- [Chinese_from_dongxiexidian][14] - 中文数据预处理材料，包括分词词典和中文停用词。分词词典: 综合了百度、搜狗等词库，以及手动整理的若干人名和新近出现的热词。中文停用词: 综合了"百度停用词表"，"哈工大停用词表"，"四川大学机器学习实验室停用词表"等若干停用词表，取交集并去除了不需要的标点符号和英文单词。
- [chinese_dictionary][17] - 同义词表，反义词表，否定词表
- [Company-Names-Corpus][22] - 公司名语料库。机构名语料库。公司简称,缩写,品牌词,企业名。可用于中文分词、机构名实体识别。
- [chinese-poetry][23] - 最全中华古诗词数据库, 唐宋两朝近一万四千古诗人, 接近5.5万首唐诗加26万宋诗. 两宋时期1564位词人，21050首词
- [清华大学开放中文词库][24] - 包括：IT、财经、成语、地名、历史名人、诗词、医学、饮食、法律、汽车、动物
- [chinese_chatbot_corpus][25] - 中文公开聊天语料库
- [Chinese_Rumor_Dataset][26] - 中文谣言数据
- [couplet-dataset][52] - 70万条对联数据库
- [The-Big-Username-Blocklist][54] - 用户名黑名单列表
- [CrimeKgAssitant][55] - 罪名法务智能项目,内容包括856项罪名知识图谱, 基于280万罪名训练库的罪名预测,基于20W法务问答对的13类问题分类与法律资讯问答功能
- [weixin_public_corpus][56] - 微信公众号语料库

### 情感分析
- [SentiBridge][12] - 判断词汇情感值，目前词典包含三个领域语料的抽取结果：新闻、旅游、餐饮，共计30万对
- [python-girlfriend-mood][27] - 分析女朋友聊天时的情绪波动

### BERT
- [BERT_Paper_Chinese_Translation][29] - BERT论文中文翻译
- [bert-Chinese-classification-task][30] - bert中文分类实践
- [BERT-Classification-Tutorial][31] - bert中文标注实践
- [transformers][32] - bert pytorch实现
- [BERT-BiLSTM-CRF-NER][33] - bert用于中文命名实体识别 tensorflow版本
- [bert-utils][34] - 一行代码使用BERT生成句向量，BERT做文本分类、文本相似度计算
- [Kashgari][35] - bert 基于 keras 的封装分类标注框架 Kashgari，几分钟即可搭建一个分类或者序列标注模型

### NLU
- [hardNLU][51] - 整理的一些难理解的句子

### NLG
- [awesome-text-generation][44] - 文本生成相关资源汇总
- [awesome-nlg][47] - A curated list of resources dedicated to Natural Language Generation (NLG)
- [文本生成控制][46]
- [seq2seq-couplet][53] - 自动对对联

### 其它
- [ls0f/phone][5] - 中国国内手机号码归属地库
- [AfterShip/phone][6] - With a given country and phone number, validate and reformat the mobile phone number to the E.164 standard
- [Chinese-Names-Corpus][9] - 中文人名语料库。人名生成器。中文姓名,姓氏,名字,称呼,日本人名,翻译人名,英文人名。可用于中文分词、人名实体识别
- [chaizi][11] - 漢語拆字字典
- [python-pinyin][15] - 将汉字转为拼音。可以用于汉字注音、排序、检索
- [nstools][16] - 中文繁简互转
- [common-regex][19] - 常用正则表达式
- [Chinese-Word-Vectors][21] - 100+ Chinese Word Vectors 上百种预训练中文词向量
- [MatchZoo][28] - Facilitating the design, comparison and sharing of deep text matching models. 文本相似度匹配算法的集合
- [texar][37] - Toolkit for Machine Learning, Natural Language Processing, and Text Generation, in TensorFlow.
- [ComplexEventExtraction][38] - 中文复合事件抽取，包括条件事件、因果事件、顺承事件、反转事件等事件抽取，并形成事理图谱


## 博主

### 文章

### 视频
[正弦啵 - 哔哩][60]  



[1]: https://www.bilibili.com/video/BV1yK4y1E7n4
[2]: https://github.com/fighting41love/funNLP
[3]: https://github.com/observerss/textfilter
[4]: https://github.com/saffsd/langid.py
[5]: https://github.com/ls0f/phone
[6]: https://github.com/AfterShip/phone
[7]: https://github.com/observerss/ngender
[8]: https://github.com/fighting41love/cocoNLP
[9]: https://github.com/wainshine/Chinese-Names-Corpus
[10]: https://github.com/zhangyics/Chinese-abbreviation-dataset
[11]: https://github.com/kfcd/chaizi
[12]: https://github.com/rainarch/SentiBridge
[13]: https://github.com/fighting41love/funNLP/tree/master/data
[14]: https://github.com/wissyhost/Chinese_from_dongxiexidian
[15]: https://github.com/mozillazg/python-pinyin
[16]: https://github.com/skydark/nstools/tree/master/zhtools
[17]: https://github.com/guotong1988/chinese_dictionary
[18]: https://github.com/keredson/wordninja
[19]: https://github.com/houchenll/common-regex
[20]: https://github.com/keon/awesome-nlp
[21]: https://github.com/Embedding/Chinese-Word-Vectors
[22]: https://github.com/wainshine/Company-Names-Corpus
[23]: https://github.com/chinese-poetry/chinese-poetry
[24]: http://thuocl.thunlp.org/
[25]: https://github.com/codemayq/chinese_chatbot_corpus
[26]: https://github.com/thunlp/Chinese_Rumor_Dataset
[27]: https://github.com/CasterWx/python-girlfriend-mood/
[28]: https://github.com/NTMC-Community/MatchZoo
[29]: https://github.com/yuanxiaosc/BERT_Paper_Chinese_Translation
[30]: https://github.com/NLPScott/bert-Chinese-classification-task
[31]: https://github.com/Socialbird-AILab/BERT-Classification-Tutorial
[32]: https://github.com/huggingface/transformers
[33]: https://github.com/macanv/BERT-BiLSTM-CRF-NER
[34]: https://github.com/terrifyzhao/bert-utils
[35]: https://github.com/BrikerMan/Kashgari
[36]: https://jalammar.github.io/illustrated-bert/
[37]: https://github.com/asyml/texar
[38]: https://github.com/liuhuanyong/ComplexEventExtraction
[39]: https://xlore.org/
[40]: https://reports.aminer.cn/
[41]: https://static.aminer.cn/misc/article/nlp.pdf
[42]: https://static.aminer.cn/misc/article/translation.pdf
[43]: https://ehudreiter.com/
[44]: https://github.com/ChenChengKuan/awesome-text-generation
[45]: https://drive.google.com/file/d/1Mdna3q986k6OoJNsfAHznTtnMAEVzv5z/view
[46]: https://github.com/harvardnlp/Talk-Latent/blob/master/main.pdf
[47]: https://github.com/tokenmill/awesome-nlg
[48]: https://ai.googleblog.com/2020/05/evaluating-natural-language-generation.html
[49]: https://github.com/fxsjy/jieba
[50]: https://github.com/hankcs/pyhanlp
[51]: https://github.com/fighting41love/hardNLU
[52]: https://github.com/wb14123/couplet-dataset
[53]: https://github.com/wb14123/seq2seq-couplet
[54]: https://github.com/marteinn/The-Big-Username-Blocklist
[55]: https://github.com/liuhuanyong/CrimeKgAssitant
[56]: https://github.com/nonamestreet/weixin_public_corpus
[57]: http://web.stanford.edu/class/cs224n/
[58]: https://github.com/DSKSD/DeepNLP-models-Pytorch
[59]: https://github.com/graykode/nlp-tutorial
[60]: https://space.bilibili.com/244865478