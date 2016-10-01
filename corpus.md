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
