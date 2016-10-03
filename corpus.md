# 语料库

建立样本库是数据挖掘、人工智能研究不可缺少的基础工作。

语料库是指以文本类型为样本的数据集。有的语料库重在数量，有的则关注加工。

推荐资料：

图片分类的TED(李飞飞) https://www.ted.com/talks/fei_fei_li_how_we_re_teaching_computers_to_understand_pictures?language=zh-cn

儿童习得语言的资料TED记录：单词的诞生http://open.163.com/movie/2011/7/E/J/M77TUGO7R_M77TUSJEJ.html

## 语料库列表
- 语料库在线 http://www.cncorpus.org/
- 现代汉语语料库 http://ccl.pku.edu.cn/corpus.asp?item=1
- 古代汉语语料库 http://ccl.pku.edu.cn/corpus.asp?item=2
- 汉英双语语料库 http://ccl.pku.edu.cn/corpus.asp?item=3
- HSK动态作文语料库 http://202.112.195.192:8060/hsk/login.asp
- 北京口语语料查询系统 http://www.blcu.edu.cn/yys/6_beijing/6_beijing_chaxun.asp
- 现代汉语平衡语料库 http://rocling.iis.sinica.edu.tw/new/20corpus.htm
- LIVAC共時語料庫 http://www.livac.org/index.php
- 兰开斯特汉语语料库 http://ling.cass.cn/dangdai/LCMC/LCMC.htm
- 洛杉矶加州大学汉语语料库 http://www.lancs.ac.uk/fass/projects/corpus/UCLA/
- 中文新闻分类语料库 http://www.nlpir.org/?action-viewnews-itemid-145
- NLPIR 500万条twitter内容语料库 http://www.nlpir.org/?action-viewnews-itemid-263
- NLPIR微博博主语料库100万条 http://www.nlpir.org/?action-viewnews-itemid-232
- 現代漢語語料庫詞頻統計 http://elearning.ling.sinica.edu.tw/CWordfreq.html
- 欢迎关注新浪微博【对外汉语北京】
- 中文句結構樹資料庫 http://turing.iis.sinica.edu.tw/treesearch/
- 搜狗文本分类语料库 http://www.sogou.com/labs/dl/c.html
- 哈工大信息检索研究室对外共享语料库 http://ir.hit.edu.cn/demo/ltp/Sharing_Plan.htm
- 传媒大学文本语料库 http://ling.cuc.edu.cn/RawPub/
- 词语研究资源库 对外汉语北京 http://ling.cuc.edu.cn/newword/web/index.asp
- BFSU CQPweb多语言在线语料库检索平台 http://www.iresearch.ac.cn/paper/detail.php?ItemID=6358
- 英汉双语平行语料库 http://www.luweixmu.com/ec-corpus/
- babel 汉英平行语料库 http://icl.pku.edu.cn/icl_groups/parallel/default.htm
- 中国法律法规汉英平行语料库（大陆） http://corpus.zscas.edu.cn/lawcorpus1/index.asp
- 国家语言资源监测与研究中心 http://www.clr.org.cn/

## 样本收集方法

## 语料库加工方法

### 词语切分

#### 汉语自动分词技术

1. 概念
通过计算机把组成汉语文本的字串自动转换为词串的过程
2. 目的
    - TTS或语音合成： 只有正确切词，才能知道正确的发音
    - 信息检索： 分词有助于提高信息检索的准确率
    - 词语的计量分析：词频统计等
    - 深层汉语分析的基础：句法分析、语义分析等
3. 基本方法
    - 最大匹配法(MM)
        - 正向最大匹配法(MM)
        - 逆向最大匹配法(RMM)
4. 评价标准
    - 准确率(precision)
      准确率（P）＝切分结果中正确分词数/切分结果中所有分词数*100%
    - 召回率(recall)
      召回率（R）＝切分结果中正确分词数/标准答案中所有分词数*100%
    - F-评价(F-measure综合准确率和召回率的评价指标)
      F-指标＝2PR/(P+R)
5. 关键问题
    - 切分歧义（消解）：一个字串有不止一种切分结果
    - 未登录词识别：专有名词、新词

### 词性标注

## 其他相关内容
### 构建语料库的原则
语料库应该具有代表性、结构性、平衡性、规模需求并制定语料的元数据规范，各个原则具体介绍如下：

* 代表性：在应用领域中，不是根据量而划分是否是语料库，而是在一定的抽样框架范围内采集而来的，并且在特定的抽样框架内做到代表性和普遍性。
* 结构性：有目的的收集语料的集合，必须以电子形式存在，计算机可读的语料集合结构性体现在语料库中语料记录的代码，元数据项、数据类型、数据宽度、取值范围、完整性约束。
* 平衡性：主要体现在平缓因子：学科、年代、文体、地域、登载语料的媒体、使用者的年龄、性别、文化背景、阅历、预料用途（私信/广告等），根据实际情况选择其中一个或者几个重要的指标作为平衡因子，最常见的平衡因子有学科、年代、文体、地域等。
* 规模性：大规模的语料对语言研究特别是对自然语言研究处理很有用的，但是随着语料库的增大，垃圾语料越来越多，语料达到一定规模以后，语料库功能不能随之增长，语料库规模应根据实际情况而定。
* 元数据：元数据对于研究语料库有着重要的意义，我们可以通过元数据了解语料的时间、地域、作者、文本信息等；还可以构建不同的子语料库；除此外，还可以对不同的子语料对比；另外还可以记录语料知识版权、加工信息、管理信息等。

参考：[【NLP】大数据之行，始于足下：谈谈语料库知多少](http://www.cnblogs.com/baiboy/p/ylk.html)
