# ChineseDiachronicCorpus
ChineseDiachronicCorpus，中文历时语料库，横跨六十余年，包括腾讯历时新闻2009-2016，人民日报历时语料1946-2003，参考消息历时语料1957-2002。基于历时流通语料库，可用于历时语言变化计算、语言监测、社会文化变迁研究提供基础性的语料支持。

# 为什么中文开放数据集如此之难
有的时候我在想，chineseldc基本停滞了，后面除了gluedata benchmark，国内数据集开源为什么这么难？我想了一想，不当当是侵权的问题，有很多原因【不一定对】：  
1）研究导向。数据集属于很底层、初级的工作，头部研究注意力放在深度学习上（近年来有好转，比如ccl近2年的best paper 都有侧重），基础数据没人做；    
2）版权保护。虽然国家没有出台官方的抓取即违法的政策，但这是大趋势，这个也制约了数据的发布和公开。  
3）研究保护。国内开源生态不乐观，发出去，就等着被抄，花费大量人力、物力、财力标注的语料，可能发布出去就直接被使用，形成竞争壁垒。   
4）缺乏引导。近年来有意识的在搞平台，比如百度搞千言，民间搞glue benchmark，但最怕做成摆货架。 目前开放了很多的基础评测资源，大大多都是针对英文的【没办法，要国际化，要文章】。   
得语言者得天下，得语言资源者，分得天下。中文语言资源，不应该是这幅模样。  

# 项目的由来
语言是人类重要的交际工具，同时也是社会的镜子，语言记录并反映了社会，对语言记录进行挖掘、计算，可以从各个层面对社会进行解读。例如，基于语料库进行词语考察，以反映单个词语在不同时间周期中的使用及变动情况。  以语料为载体，挖掘出属于某个特定时间周期的社会特点，例如年度关键词、年度人物、年度流行语；对词语进行文化计算，如颜色计算、性别计算、观点计算等，以考察整个社会对某一事物、看法的演变。  
当前，开源可用的中文历时语料库较少。代表性的有北京语言大学国家语言资源监测与研究平面媒体中心DCC动态流通语料库，其对国内数十家报纸媒体进行监测，也有中国传媒大学网络媒体中心的历时语料库可以使用。  
当前，随着网络技术的发展以及采集技术的相对成熟，构建起历时语料库变得越来越容易，这就使得向外界共享历时语料库变得更为便利且必要。  
本项目，旨在通过公开收集的方式，从网络媒体和平面媒体两个角度出发，形成腾讯新闻、人民日报、参考消息三大历时语料库，以供社会开放使用。  

# 项目的用途

那么，基于这个语料库，能够做什么呢？总结了下，至少可以从词语考察、语义计算、热度计算、文化计算、媒体对比、语法研究等六个方面开展工作。  

| 用途名称| 技术手段| 应用场景|
| :--- | :---: | :---: |
| 词语考察|分词、词频统计| 通用词表等编写| 
| 语义计算| 共现词、MI搭配、依存搭配| 搭配等语义词典编写| 
| 热度计算| 流通度计算、术语提取 | 流行语等发布| 
| 文化计算| 颜色计算、性别计算| 文化变迁|
| 媒体对比|媒体差异计算| 传播学研究| 
| 语法研究| 语法模式检索| 语法教材与词典编写| 


# 项目的获取

对于如何获取数据，下表是对数据集的介绍，需要使用的可以开放下载使用，因涉及版权问题，暂只放数据来源。免责声明：该项目由公开渠道收集而成，不可商用，仅可用于科学研究，若有侵权，可联系删除。  

| 数据名称 | 时间跨度 | 数据大小  |数据来源 |
| :--- | :---: | :---: | :--- |
| 腾讯新闻 | 2009-2016 | 5GB| https://auto.qq.com/l/201104/scrollnews_15.htm |
| 人民日报 | 1946-2003 | 3.44GB | http://www.laoziliao.net/rmrb/ |
| 参考消息 | 1957-2002 | 1.1GB | http://www.laoziliao.net/ckxx/ |


# 关于作者
刘焕勇，中国科学院软件研究所，兼任数据地平线科技算法总监，专注金融、情报两大领域，从事事件抽取、事件演化、情感分析、事理（知识）图谱、常识推理、语言资源构建与应用等研发工作。如有自然语言处理、知识图谱、事理图谱、社会计算、语言资源建设等问题或合作，可联系我：  
1、我的github项目介绍：https://liuhuanyong.github.io  
2、我的csdn技术博客：https://blog.csdn.net/lhy2014  
3、我的联系方式: 刘焕勇，中国科学院软件研究所，lhy_in_blcu@126.com.  
4、我的共享知识库项目：刘焕勇，数据地平线，http://www.openkg.cn/organization/datahorizon.  
5、我的工业项目：刘焕勇，数据地平线，大规模实时事理学习系统：https://xueji.datahorizon.cn.  
6、我的工业项目：刘焕勇，数据地平线，面向事件和语义的自然语言处理工具箱：https://nlp.datahorizon.cn  
