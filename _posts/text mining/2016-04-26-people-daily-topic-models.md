---
layout: single
title: "男女选秀弥漫与娱乐机器轰鸣 ——试对《人民日报》的娱乐话语进行文本挖掘与可视化 （2005-2016）"
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/unsplash-image-3.jpg
  cta_label: "Read More"
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "本研究选取了内地媒介市场化的代表节目形态之一，选秀节目，作为分析的对象；而选秀节目如雨后春笋，秉着见微知著的精神，又选取了“音乐类选秀节目”作为分析的重点。本研究通过中文LDA主题模型的方法，分析党报《人民日报》过去１２年间对音乐类选秀节目的话语主题，从而归纳其主旨，并对结果进行可视化。"
modified: 2016-04-26T11:55:22-04:00
comments: true
author_profile: true
author: "张昕之"
---

{% include toc title="Table" icon="file-text" %}

# 一、研究背景：政治与娱乐之相爱相杀

政经与娱乐似乎总是一对相爱相杀的苦主。如果信奉《娱乐之死》（Amusing Ourselves to Death）的主旨，那么娱乐是莫谈国事的麻醉剂；如果信奉Lifestyle Politics，那么看似与政经无关的内容一样发人深省。在某些以市场导向的国家（见Hallin &amp; Mancini (2004)的划分），万般皆商，布什和川普都可以上电视胡说八道，有媲美电影<em>Spotlight</em>主角的记者，也有如电影<em>Nightcrawler</em>男主角这样的骗子，一切矛盾都是交易（马克吐温说：我们可以用金钱买到最好的政府；肯尼迪还说，人是生而不平等的），总有办法大事化小、小事化了，彼此相安无事。

然而在以意识形态为主导的威权体制（authoritarian state）下，男女相爱莺歌燕舞似乎总显得不合时宜。 以前苏联为例子，Zhu（2001）曾援引美籍俄裔社会学家 Vladimir Shlapentokh (1986) 有关“苏维埃意识形态功能”（functions of Soviet ideology）的论述来解释当时前苏联媒介三方面的功能：一道德、二合法化、三命令。Zhu（2001）概括道（p.6)：所谓媒介“道德功能”就是“说服人民接受国家或社会的利益，超越个人利益以及要求人民为整体的利益而牺牲个人”，所谓“合法化功能”就是要求“人民接受制度的合法性和当权者的领导地位，并且不从事任何实际的反对行动”，至于“命令功能”则是“对那些服从或逃避思想意识运动者实施奖赏或制裁。” 不难发现，如果将此和施拉姆（1964）对媒介功能的论述生硬对照，施拉姆论述中一条非常重要的大众媒介的“娱乐休闲消遣”功能不见踪影。


# 二、针对内地官媒话语的研究举隅
针对如今（八十年代末至今）内地，有一系列针对媒体角色、媒介话语的出色的研究。 如He (2000) 的论述，主旨大思想岌岌可危，然而大环境不变、市场化却以雨后春笋的当今，媒体被迫一奴侍二主：一方面要严守宣传纪律，另一方面又要与早已原罪满满的商业巨擘和驱逐蝇头小利的投机者厮杀，否则只能与江南皮革厂一样倒闭。Lee, He, and Huang (2006， 2007) 以及Zhao (2000) 等学者援引西方市场-媒介关系的论述细致分析了内地媒体和市场的互动关系。
而在媒介话语方面，Ng, Ye, and Lee (2011) 曾经分析了党报《人民日报》对于“全球化”的话语。 其立意很直接：在社会主义（或者未来的共产主义）的主导下，大谈特谈带着万恶资本主义的“全球化”、蔚蓝色是不正确的，否则怎么向和资本主义战斗终生的马克思恩格等前辈交代？然而众所周知，拥抱全球化、与国际接轨、加入WTO是官方力推的政策并为之付出了大量艰辛，这组矛盾在党报上如何自圆其说的？研究者发现党报强调中国是国际社会的一部分、全球化是积极健康的等话语，维护了其话语的正统性。
受之前这类研究——党媒-社会-市场三者的关系——的启发，本小小研究试图考察“宣传”与“娱乐”、“坚守把握主旨思想”与“向钱进”之间看似不可调和的矛盾，是如何在党媒上中和的。在当今内地的大环境下，正如为了迎接上级检查、讨好领导而弄虚作假毫无底线一样，媒体一样可以为了金钱和收视率毫无底线。而与地方媒体和商业小报不同，党媒对待“娱乐”“选秀”乃至“文化产业”的态度就很重要，不是简单地说支持不支持，这背后体现的是官方对待社会议题的决策：一方面，“娱乐”是媒介市场化的重要手段，中介化的（mediated，　见media spectacle的论述）“娱乐”可以强有力鼓励消费、拉动经济（用脑了喝六个核桃渴了喝金罐加多宝想唱歌了喝猛牛酸酸乳）、发展文化产业、对外走出去、对内不折腾；而另一方面，正如之前已经指出的，娱乐选秀和官方的意识形态——虽然不能说有本质上的冲突——但是仍然是格格不入的。娱乐的靡靡之音麻木人的心灵让人不再关注国家大事，娱乐没有底线、哗众取宠、催熟儿童、恶搞伴娘、自拍炫富、污；更糟糕的是，娱乐营造大V，演唱会有大屏幕，可迅速号召群众，海选、草根、万众参与、程序透明、选举、投票，这些词语在当下总显得有些刺眼和让人担忧 （注：尽管Meng (2009) 的论述以及Cui and Lee (2010) 富有洞察的访谈已经告诉我们，这种担忧其实是我们多氯了）。
注意，这几方面虽然不在一个分析层面上（前者是事实和结果，中者是基于归纳之上的道德判断，后者是基于演绎的假设），把它们并列起来打擂台确有诡辩之嫌，但是党媒在这个问题上的话语再现（the discursive representation）确实形成了一个经验上的悖论（an empirical puzzle）：党媒对于娱乐选秀节目的话语是怎样的？——究竟是视其为拯救市场的灵丹妙药而加以赞颂发扬、还是道德沦丧的洪水猛兽而加以鞭笞禁止？

# 三、《人民日报》与文本挖掘——词频分析与主题建模（topic modeling）

方法上，本研究选取了内地媒介市场化的代表节目形态之一，选秀节目，作为分析的对象；而选秀节目如雨后春笋，秉着见微知著的精神，又选取了“音乐类选秀节目”作为分析的重点。本研究通过中文LDA主题模型的方法，分析党报《人民日报》过去１２年间对音乐类选秀节目的话语主题，从而归纳其主旨，并对结果进行可视化。对数据和方法汇报如下：
一，在“人民日报国内版全文光盘”数据库采用关键词检索相关报道，关键词包括两类：第一类是节目形态的关键词，如“真人秀” (n=166，表示全库第一次搜索的返回结果)；“选秀节目” (n=121)；第二类是节目名称，节目名称来自于对国内音乐类选秀节目的论述，包括“ 超级女声” (n=32)；“快乐女声” (n=2)，“快乐男声” (n=11)；“超级男声”(n=3)，“中国好声音”(n=141)；“中国达人秀” (n=23)，“梦想中国” (ch28, n=26)，“加油好男儿”(n=1)；“绝对唱响”(n=1)；“第一次心动”(n=4)；“青春之星”(n=2)；“中国最强音”(n=14)； “最美和声”(n=9)，“中国好歌曲”(n=16) 。所有新闻、专题报道、以及评论都包括在内。删除重复篇目及毫不相关篇目之后，得最终分析样本378 篇。报道的时间包括2003年 到2016年，即涵盖了最早火起来的《超级女声》 以及新近热播的《中国好声音》的时间段。
二、将报道文本进行预处理后， 采用了一种文本挖掘的方法：LDA主题模型(topic modeling)。 接下来，将报告详细的技术处理方法，包括代码、解释说明，和相应的结论。需要指出，本文的技术分析基本参照了本网另一位成员谈和的文章<code>《LDAvis——用R做中文LDA主题模型可视化分析》</code>以及王成军博士的文章<code>《对《政府工作报告》进行文本挖掘》</code>，特此鸣谢。本文旨在用相似的方法分析《人民日报 》，在代码上以复制（replicate） 为主，所有代码运行的结果、以及对结果的讨论，全部为本文之责（故以下技术部分，所有本研究的做法一律用第一人称“我”表示）。

## 分析文本的获取

首先把检索得出的文章合并到一个文档里，我的做法是每行一个自然段。这里有三点需要注意：1）检索文章使用的是手动下载保存的方法，没有使用爬虫程序（因为图书馆帐号不欢迎此类程序），因此在数据获取方面，我的方法比较低能； 2）将378个文档合并成一个文档，我使用的是word的merge file功能（insert – object – text）， 这个功能比较好操作，但是注意每次merge的文档有数量限制， R和python应该有相应的包； 3）保存为txt文档时，注意使用UTF-8 作为encoding。

## 使用R进行数据分析
进入R， 安装和加载所需要的包。代码如下：


```r
＃安装三个包 - 本文中，所有长注释
# 写在相应代码之前，
install.packages("jiebaR")　＃“结巴”，一个较多人推荐的中文分词插件
install.packages("lda")　＃LDA，处理主题模型
install.packages("LDAvis")  # 用于可视化
＃加载　
library(jiebaR)
library(lda)
library(LDAvis)
```

接下来创建分词器，加载词典， 这里在文件选取上用了<code>file.choose()</code>，从而使得文档调用变成了点窗口的方式，初学者可能对长路经不习惯。 另外，我暂时没有加载所谓的“用户词典”，仅仅是加载了“停用词典” ，在“停用词典”里，我添加了年份、“人民日报”、“作者”、“版面”等与主题无关的词以及节目名称。


```r
cutter <- worker(bylines = T,stop_word = file.choose())
```                                                                                                         

现在载入需要分析的文本

```r  
comments_seg <- cutter[file.choose()]
```                                                                                                             

这一步执行完之后，（在和分析文本的同一文件夹内）会生成一个txt，如我这个就叫做party_master_merged.segment.2016-04-26_11_51_24.txt. 就是分好的词。
接下来的几步，以及代码的注释，完全和与谈和（2015）的帖子相同，再次表示感谢。同时我自己增加了一些注意事项，新手可以吸取我复制这些代码时的教训。
以下这几行代码是读取分词结果，注意，要选取上一步生成的文件、即分词的结果，而不要选取原始的文本

```r  
comments_segged<- readLines(file.choose(),encoding="UTF-8")
comments <- as.list(comments_segged)
doc.list <- strsplit(as.character(comments),split=" ")
term.table <- table(unlist(doc.list))
term.table <- sort(term.table, decreasing = TRUE)  
```                                                                                                             

这个term table 就是词频排序。然后我依照谈和的帖子的操作，把单个的字和出现小于5次的词删除。读者可自行调整，比如“污”这个意味深长的单字就不见了。

```r
del <- term.table < 5| nchar(names(term.table))<2   #把不符合要求的筛出来，使用了一个“或”语句 ( |)
term.table <- term.table[!del]   #把不符合要求的、也就是集合（del）里的元素，从table里去掉
vocab <- names(term.table)    #创建词库，用于下一步分析
```                                                                                                             

大家可以对比一下执行上一面一段代码之前和之后的词频。使用head()命令可以看一个数据的表头。大家可以感受一下表一和表二的区别。

```r                                                 
head(term.table)
```                                                                                                             

表一：筛除单个的字和出现小于5次的词之前排名前五名的词

    节目 中国 文化 中 年 观众
    2243 2166 1702 1279 939 824


表二：筛除之后

    节目 中国 文化 观众 发展 电视
    2243 2166 1702 824 816 796

### 词频分析
下面进行词频分析， 使用<code>head</code>命令一览排名前50的词语：

表三：排名前50的词语（《人民日报》， 2003-2016）

    节目（2243），中国（2166），文化（1702），观众（824），发展（816），电视（796），音乐（712），社会（614），媒体（554），创新（498），市场（498），娱乐（496），声音（486），内容（477），选秀（465），生活（452），模式（451），艺术（407），电视台（405），卫视（395），孩子（375），工作（370），电影（363），制作（348），传统（342），时代（342），网络（339），明星（338），一种（323），品牌（321），传播（318），全国（297），收视率（295），电视节目（294），创作（293），播出（292），国家（291），原创（284），方式（281），世界（281），精神（280），产业（278），平台（277），新闻（263），文艺（262），作品（259），企业（257），互联网（252），演出（251），国际（246）


单纯看这个表格意思不大。然而，如果将此列表与之前王成军做的47年间的《政府工作报告》关键词加以比较，我们惊讶地欧亨利一般地发现，过去半个世纪以来出现在国务院《政府工作报告》之首的“发展”一词，同样出现在党报对娱乐选秀节目的报道中，且排名第五（816次），仅次于节目、中国、文化、观众。 更加夺目的是，若干涉及国计民生重大发展的词汇，如“创新”、“社会”“中国”，“工作”，“国际”，“企业”等，同样是两个语篇中共同的高频词。

表四：排名前50的词语（《政府工作报告》， 1969-2016）

    发展（139）， 建设（68）， 经济（67）， 改革（62）， 推进（62）， 创新（56）， 加快（42）， 加强（41）， 政府（40）， 促进（37）， 实施（36）， 增长（36）， 企业（35）， 政策（35）， 推动（34）， 社会（34）， 中国（32）， 提高（31）， 我们（30）， 全面（28）， 完善（27）， 扩大（26）， 工作（26）， 制度（26）， 实现（25）， 就业（24）， 人民（24）， 支持（24）， 坚持（23）， 我国（22）， 国家（21）， 一批（21）， 创业（21）， 安全（21）， 农村（20）， 合作（20）， 国际（20）， 继续（19）， 地方（19）， 服务（19）， 投资（19）， 积极（19）， 取得（19）， 基本（18）， 落实（18）， 加大（18）， 机制（18）， 今年（18）， 地区（17）， 问题（17）


因此，一个仓促的结论似乎是这样的：仅词频这个角度来说，党媒对于音乐选秀类节目的话语似乎更倾向于市场化的一面，并且将选秀节目拓展至国家发展的一部分，并将之与国家宏观调控发展的策略进行接合（articulation）。 如刚才所展示的，创新、社会、国际、市场、模式、卫视、制作、网络、收视率、产业这一系列只可能出现在新闻联播头条的、与张学友张国荣张家辉张涵宇张惠妹张少涵张含韵张雨琪章子怡邓紫琪等毫无关系的词语，赫然榜上。 不过，在政府工作报告中的高频词，如建设、经济、改革、推进、农村等基础建设的议题则暂时没有出现。

## 主题建模

```r
get.terms <- function(x) {
  index <- match(x, vocab)  
  index <- index[!is.na(index)]    rbind(as.integer(index - 1), as.integer(rep(1, length(index))))   
}
documents <- lapply(doc.list, get.terms)

K <- 10   #主题数 – 这一步可以任意指定
G <- 5000    #迭代次数 – 我不知道这一步的意思是什么
alpha <- 0.10   
eta <- 0.02

library(lda)
set.seed(360)
```                                                                                                             

完成以上工作后，可以一窥结果。注意到 <code>lda.collapsed.gibbs.sampler</code> 这个命令下的各个参数，根据理论，应该是可变的，读者可以自行调节比对不同参数下的结果。我尝试了两种主题模型的方法，一为析出10个主题，一为析出5个主题，其他参数维持不变。代码如下，注意这段代码的运行时间略长（大约4 分钟左右，对于惯用SPSS和STATA的人来说这个时间不短）：

```r
fit10 <- lda.collapsed.gibbs.sampler(documents = documents, K = 10, vocab = vocab, num.iterations = G, alpha = alpha, eta = eta, initial = NULL, burnin = 0, compute.log.likelihood = TRUE)
fit5 <- lda.collapsed.gibbs.sampler(documents = documents, K = 5, vocab = vocab, num.iterations = G, alpha = alpha, eta = eta, initial = NULL, burnin = 0, compute.log.likelihood = TRUE)
```                                                                                                             

下面，处理并展示结果，使用<code>top.topic.words</code> 命令，前两个参数的意思是（以第一行为例）：抽取fit10这个结果中的主题，20表示每个主题下展示10个词语。

```r
top.words10 <- top.topic.words(fit10$topics, 10, by.score=TRUE)
top.words5 <- top.topic.words(fit5$topics, 10, by.score=TRUE)
top.words
top.words5
```                                                                                                             

结果如下，10个主题看起来是这样：
表五：主题模型：析出10个主题，每个主题下10个词语

    [,1]     [,2]     [,3]   [,4]   [,5]  [,6]   [,7]   [,8]    [,9]    [,10]   
    [1,] "媒体" "中国" "音乐" "文化" "节目" "生活" "记者" "孩子" "节目" "品牌"  
    [2,] "互联网" "文化" "演出" "工作" "娱乐" "梦想" "北京" "电影" "卫视" "市场"  
    [3,] "网络" "世界" "观众" "群众" "选秀" "真实" "科普" "儿童" "电视" "企业"  
    [4,] "内容" "传统" "歌手" "发展" "文化" "故事" "评论" "学生" "播出" "加多"  
    [5,] "视频" "文学" "歌曲" "改革" "社会" "一种" "活动" "阿富汗" "模式" "发展"  
    [6,] "平台" "民族" "中国" "建设" "电视" "观众" "24" "学习" "电视台" "中国"  
    [7,] "音乐" "历史" "春晚" "创新" "观众" "社会" "休假" "家长" "中国" "创新"  
    [8,] "用户" "作家" "比赛" "干部" "媒体" "精神" "新疆" "记者" "制作" "产业"  
    [9,] "传播" "新西兰" "舞台" "社会" "明星" "情感" "文艺" "教育" "电视节目" "经济"  
    [10,] "网站" "时代" "艺术" "管理" "收视率" "人生" "本报" "美国" "频道" "文化产业"


表六：主题模型：析出5个主题，每个主题下10个词语

    [,1]   [,2]   [,3]     [,4]     [,5]      
    [1,] "发展" "文化" "电影" "孩子" "节目"  
    [2,] "文化" "生活" "媒体" "记者" "电视"  
    [3,] "品牌" "社会" "互联网" "演出" "卫视"  
    [4,] "工作" "作品" "视频" "北京" "选秀"  
    [5,] "创新" "音乐" "网络" "学生" "收视率"  
    [6,] "建设" "创作" "音乐" "上海" "播出"  
    [7,] "企业" "艺术" "内容" "活动" "电视台"  
    [8,] "改革" "精神" "用户" "工作" "观众"  
    [9,] "服务" "时代" "平台" "台湾" "明星"  
    [10,] "加多" "民族" "产业" "阿富汗" "电视节目"


可以大致看出，党媒对于娱乐选秀的话语主题可以比较武断地大致分为四大类： 1）文化产业发展（发展、品牌、改革、服务）； 2）新媒体与媒介融合（电影、互联网、视频、用户、平台）， 3）媒介的社会影响与国际影响（孩子、演出、北京、阿富汗、美国），以及 4）节目形态（选秀、明星、电视节目）等。

# 四、对主题建模的可视化初探
最后，对以上主题进行可视化。代码如下（同样的，感谢谈和（2015）的帖子）

```r                                                 
theta <- t(apply(fit10$document_sums + alpha, 2, function(x) x/sum(x)))  
phi <- t(apply(t(fit10$topics) + eta, 2, function(x) x/sum(x)))  
term.frequency <- as.integer(term.table)   
doc.length <- sapply(documents, function(x) sum(x[2, ]))
library(LDAvis)
json <- createJSON(phi = phi, theta = theta,
                   doc.length = doc.length, vocab = vocab,
                   term.frequency = term.frequency)
summary(json)
serVis(json, out.dir = './vis', open.browser = FALSE)
```                                                                                                             

执行完以上命令之后，系统会生成一个文件夹，用Firefox打开index.html文件，就可以见到下图，如图一所示：


![topic-graph1](http://oaf2qt3yk.bkt.clouddn.com/da222cad2fad1cb5fd6fb270b7cf192e.png)

图二是针对之前的十个主题进行的分布（我注意到，这里的主题编号和之前R生成的十个主题有一点不一样，比如这里的主题2，应该是之前表五中的主题5，我不知道是否我运算的问题，但是经过比对之后发现两者大致相同），旨在可视化以下内容：主题与主题之间的关系如何？主题与主题之间的距离如何？将鼠标移到相应的代表主题的圆圈上，可以看到该主题下的词频分布（右边的bar chart）。比如主题2：


![topic-graph2](http://oaf2qt3yk.bkt.clouddn.com/3cbf3bd2edb11b37c7169d39357fca65.png)


主题2的关键词包括节目、娱乐、文化、选秀、社会、电视、观众等。 这些和电视文化有关。 再看另一典型的主题，主题6：

![topic-graph3](http://oaf2qt3yk.bkt.clouddn.com/e199045c38fd7b413f2ebe18a260ab3a.png)

图三在此


主题6更像是关于节目的硬件产业，如媒体、互联网、平台、内容等。 类似之前说到的媒介融合和媒介产业发展。
最后是不相关的、与众不同骨骼惊奇的主题10，见图四：

![topic-graph4](http://oaf2qt3yk.bkt.clouddn.com/dc9d4de4290b045c550fe13dbce5ee99.png)

图四在此


图四更多的是一些类似社会影响议题，如记者、北京、科普等等。从词频分布上看有些杂词还没有处理干净，还有一些没有意义的词语。至于更加细致的对于每一类的详细地解释及解释，这里就不再赘述了，毕竟Discussion 部分是公认的“魔幻现实小说体”。
总体而言，这个小作品仅仅是从传统的针对媒介建构（constructionist）的研究出发——如之前用过的对framing alignment进行定量分析、以及运用Gamson 等人提出的“意识形态包裹”（ideological packages） 中的 “建构器具”（framing devices ） 对报道话语进行主观解读——多走一小步，用文本挖掘的方法生硬武断（brutal）地检视话题内在的规律。没有上下文脉络以及对字词句段篇章浑然一体触摸玩味的文本挖掘是没有意义的（尽管“玩味”是何物，本身就是一个无法证伪的伪命题）。 我们很难断定 Zipf 与巴赫金谁对文字的敏感性更胜一筹，也无法判断机器学习的结果是否可以与拉康学派所谓想象的能指进行有效的对话，这或许也是话语分析中cohesion 与 coherence 之间的分野。事实上，运用解读传统（the interpretative approach）的方法、基于语言学的方法（如critical discourse analysis）也许同样可以得出与本文相同的结论，但也可能因为选篇和立意的不同，得出完全相反的结论。这就仰赖于本文前半部分的理论探讨（比如分析层面的选取），以及行文的内在逻辑（internal consistency）和结果的解释力（explanatory power）。 可惜这些都是本文无法、也是作者现阶段尚未够资历去探讨的话题。

未来针对现有这些资料的下一步研究可以有两个：一是进行历时分析；二是将媒介话语与现实社会的一些指标结合起来，比如针对娱乐节目的管理规定。对于题目一，王成军的帖子是很好的一个起点。对于题目二，我过去粗浅地对比过中港两地电视剧管理的规定（Zhang, 2010），但是对于社会指标应该有比规定更为可操作化的指标。这样一来，针对相应话题可视化的可能性也大大拓展。然而要真正实现这些题目，还得诚邀各路豪杰共商大计。最后，该研究技术路线比较朴素，行文仓促，做工也非常粗糙，很多代码的意思还弄得不是很透彻。希望媒体和学者朋友多加批评。

## References
<p>Cui, L., &amp; Lee, F. L. (2010). Becoming extra-ordinary: Negotiation of media power in the case of Super Girls’ Voice in China. Popular Communication, 8(4), 256-272.</p>
<p>Gamson, W. A., &amp; Modigliani, A. (1989). Media discourse and public opinion on nuclear power: A constructionist approach. American journal of sociology, 1-37.</p>
<p>Hallin, D. C., &amp; Mancini, P. (2004). Comparing media systems: Three models of media and politics. Cambridge University Press.</p>
<p>He, Z. (2000). Working with a dying ideology: Dissonance and its reduction in Chinese journalism. Journalism Studies, 1(4), 599-616.</p>
<p>Lee, C. C., He, Z., &amp; Huang, Y. (2006). ‘Chinese Party Publicity Inc.’conglomerated: the case of the Shenzhen press group. Media, Culture &amp; Society, 28(4), 581-602.</p>
<p>Lee, C. C., He, Z., &amp; Huang, Y. (2007). Party-market corporatism, clientelism, and media in Shanghai. The Harvard International Journal of Press/Politics, 12(3), 21-42.</p>
<p>Meng, B. (2009). Who needs democracy if we can pick our favorite girl? Super Girl as media spectacle. Chinese Journal of Communication, 2(3), 257-272.</p>
<p>Ng, S. H., Ye, J., &amp; Lee, C. C. (2011). Media Discourse on Globalization in China: A Social—Psychological Analysis. Journal of Language and Social Psychology, 30(2), 139-157.</p>
<p>Postman, N. (2006). Amusing ourselves to death: Public discourse in the age of show business. Penguin.</p>
<p>Schramm, W (1964). Mass media and national development: the role of information in the developing countries, Stanford University Press, Stanford, Calif.</p>
<p>Shlapentokh, V. (1986). Soviet public opinion and ideology: Mythology and pragmatism in interaction. Praeger Publishers.</p>
<p>Zhang, X. (2010). Comparing the content regulations of TV drama between mainland China and Hong Kong: A case of criminal drama (中港電視劇內容管理管窺：以警匪、犯罪、涉案題材為例). Media Digest [Hong Kong: Radio Television Hong Kong], 2010(4), 4-5. Fulltext: http://rthk.hk/mediadigest/20100422_76_122599.html</p>
<p>Zhao, Y. (2000). From commercialization to conglomeration: The transformation of the Chinese press within the orbit of the party state. Journal of Communication, 50(2), 3-26.</p>
<p>祝建華. (2001). 中文傳播研究之理論化與本土化: 以受眾及媒介效果的整合理論為例. 新聞學研究, (68), 1-22.</p>
<p>谈和（2015） LDAvis——用R做中文LDA主题模型可视化分析。 计算传播网。URL：http://computational-communication.com/2015/12/ldavis/#comment-151</p>
<p>王成军（2015） 对《政府工作报告》进行文本挖掘。 计算传播网。<a href="http://computational-communication.com/2016/03/%E5%AF%B9%E3%80%8A%E6%94%BF%E5%BA%9C%E5%B7%A5%E4%BD%9C%E6%8A%A5%E5%91%8A%E3%80%8B%E8%BF%9B%E8%A1%8C%E6%96%87%E6%9C%AC%E6%8C%96%E6%8E%98/">URL</a></p>
