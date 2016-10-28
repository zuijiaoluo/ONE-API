
# 根据年月份请求短篇文章列表

## URL
http://v3.wufazhuce.com:8000/api/essay/bymonth/${year}-${month}

## 参数
+ year    ————>     年份
+ month   ————>     月份
+ 注意: 音乐是2012年10月才开始有的, 所有如果请求年月份小于2012年10月的话, 将返回一个空列表

## 请求示例
+ http://v3.wufazhuce.com:8000/api/essay/bymonth/2016-10

## HTTP请求方式
GET

## 数据返回格式
JSON

##是否需要登录
否

## 返回结果示例
```
{
  "res": 0,
  "data": [
    {
      "content_id": "1571",
      "hp_title": "所有的乡愁都是因为馋",
      "hp_makettime": "2016-10-27 21:00:00",
      "guide_word": "这就是我不喜欢小地方的原因，一点恩怨要计较一辈子。大都市多好，人和人没有恩仇，只求利益。",
      "author": [
        {
          "user_id": "7405600",
          "user_name": "林壁炫",
          "web_url": "http://image.wufazhuce.com/FiZhR_TblAfNhMBbHJ3GxEz9lnEp",
          "desc": "文坛小可爱，华籍美人，翘臀大厨。公众号：wochan321",
          "wb_name": "@林壁炫。"
        }
      ],
      "has_audio": true
    },
    {
      "content_id": "1569",
      "hp_title": "高危职业介绍所",
      "hp_makettime": "2016-10-26 21:00:00",
      "guide_word": "所有人都是因公殉职，死得其所，正能量破表，幸福指数肯定会飙升的。我们得携手共建自杀率为零的和谐地球呀。是不是这个道理？",
      "author": [
        {
          "user_id": "7416783",
          "user_name": "天宫雁",
          "web_url": "http://image.wufazhuce.com/FrDiAV50kyMoBbj55INFWxCjQzWc",
          "desc": "写小说，写剧本，脑波不在服务区。",
          "wb_name": "@天宫雁"
        }
      ],
      "has_audio": true
    },
    {
      "content_id": "1570",
      "hp_title": "蟑螂恋人",
      "hp_makettime": "2016-10-25 21:00:00",
      "guide_word": "有那么一刻，我甚至觉得嘴里咀嚼着的不是米饭，而是那一颗颗淡黄色的剧毒灭蟑药。\r\n",
      "author": [
        {
          "user_id": "4814759",
          "user_name": "慢三",
          "web_url": "http://image.wufazhuce.com/FnU9azoSPSIVIskGeS_W7Tn9w6P8",
          "desc": "慢三，作家。自诩为“致郁系”领军人物，负能量传播使者。",
          "wb_name": "@慢三"
        }
      ],
      "has_audio": true
    },
    {
      "content_id": "1568",
      "hp_title": "一九九九年的国庆节",
      "hp_makettime": "2016-10-24 21:00:00",
      "guide_word": "一九九九年的国庆节即将来临前的那段时间，山竹时常觉得自己的脑子里住进了一片云，把什么东西都罩住了，所以很多事情都不明不白的。",
      "author": [
        {
          "user_id": "5540827",
          "user_name": "与路",
          "web_url": "http://image.wufazhuce.com/FqsR2GNvE2NfQuRQmBkE5MRn6x19",
          "desc": "作家，重度白日梦患者。",
          "wb_name": ""
        }
      ],
      "has_audio": true
    },
    {
      "content_id": "1567",
      "hp_title": "猫头鹰医生从来不哭",
      "hp_makettime": "2016-10-23 21:00:00",
      "guide_word": "小孩还是应该哭的。",
      "author": [
        {
          "user_id": "4814798",
          "user_name": "李诞",
          "web_url": "http://image.wufazhuce.com/Fqh_S8nIYqKW11HlWHry8YP8lPBm",
          "desc": "李诞，一米八三大诗人，谐星。作品《笑场》。",
          "wb_name": "@自扯自蛋"
        }
      ],
      "has_audio": true
    },
    {
      "content_id": "1566",
      "hp_title": "头发",
      "hp_makettime": "2016-10-22 21:00:00",
      "guide_word": "头发是件要紧的事，几乎是性别意识觉醒的同时，罗拉认识到了这一点。",
      "author": [
        {
          "user_id": "7408396",
          "user_name": "陈秋韵",
          "web_url": "http://image.wufazhuce.com/FgKOYQW39G0b8NuUz4DTTLlWoV86",
          "desc": "建筑师。",
          "wb_name": "@万能乙方陈秋韵。"
        }
      ],
      "has_audio": true
    },
    {
      "content_id": "1565",
      "hp_title": "阿祥早点铺",
      "hp_makettime": "2016-10-21 21:00:00",
      "guide_word": "老年人有一种类似吃茶叶蛋的习惯，越是心里堵的事，越是不情愿拿到台面上来讲，成天只讲点无关紧要的。",
      "author": [
        {
          "user_id": "7367746",
          "user_name": "王占黑",
          "web_url": "http://image.wufazhuce.com/FmzvvB7h1h88M3WfIySeDSGZn49V",
          "desc": "还没毕业，也没工作。WeChat：wangzhanhei",
          "wb_name": ""
        }
      ],
      "has_audio": true
    },
    {
      "content_id": "1564",
      "hp_title": "十九年后吹来的风",
      "hp_makettime": "2016-10-20 21:00:00",
      "guide_word": "有些人就是会令你终生难忘，却永远记不住他们名字。",
      "author": [
        {
          "user_id": "4814921",
          "user_name": "郑执",
          "web_url": "http://image.wufazhuce.com/FgN24DwFxg7HZACRAk8t93EsDzbn",
          "desc": "郑执，作家、编剧。@郑执",
          "wb_name": "郑执"
        }
      ],
      "has_audio": true
    },
    {
      "content_id": "1563",
      "hp_title": "报警器",
      "hp_makettime": "2016-10-19 21:00:00",
      "guide_word": "世间所有的爱情都早已经被描述过，所有的偷情都没有想象中的特别。",
      "author": [
        {
          "user_id": "5553837",
          "user_name": "红拂夜奔不复还",
          "web_url": "http://image.wufazhuce.com/Fm_g-UA9hsglGgy6ipgdd19USTo8",
          "desc": "红拂夜奔不复还，编剧。",
          "wb_name": "@红拂夜奔不复还"
        }
      ],
      "has_audio": true
    },
    {
      "content_id": "1561",
      "hp_title": "像火焰像灰烬 ",
      "hp_makettime": "2016-10-18 21:00:00",
      "guide_word": "她知道此刻如果她失声痛哭，只会让这个充满意外的下午变得更加荒唐。可是，她的生活不就是因为自己的荒唐而变得更加荒唐了吗。",
      "author": [
        {
          "user_id": "7381968",
          "user_name": "程姬",
          "web_url": "http://image.wufazhuce.com/FuppaH0wjw--gmhDoi0I69c7bGP7",
          "desc": "电影工作者。",
          "wb_name": "@小程师傅。"
        }
      ],
      "has_audio": true
    },
    {
      "content_id": "1562",
      "hp_title": "生存大师",
      "hp_makettime": "2016-10-17 21:00:00",
      "guide_word": "我并非只是生存，而是生活在荒野里。",
      "author": [
        {
          "user_id": "4814755",
          "user_name": "徐畅",
          "web_url": "http://image.wufazhuce.com/FqZwhVU1uaXzED9h5rQCymJi_XWG",
          "desc": "徐畅，小说作者、编剧、野外生存爱好者。",
          "wb_name": "@徐畅--- 。"
        }
      ],
      "has_audio": true
    },
    {
      "content_id": "1559",
      "hp_title": "我妻子的双重生活",
      "hp_makettime": "2016-10-16 21:00:00",
      "guide_word": "每个人的人生只要偏离十五度，都可能是一部犯罪小说。",
      "author": [
        {
          "user_id": "4813719",
          "user_name": "方悄悄",
          "web_url": "http://image.wufazhuce.com/Fo2PCL_TVgwous_0vNapDhMT60_x",
          "desc": "作家，「一个」常驻作者。已出版小说集《看了高兴的爱情故事》《世界上到底有没有百分之百的异性恋》。",
          "wb_name": "@方悄悄诺娃"
        }
      ],
      "has_audio": true
    },
    {
      "content_id": "1560",
      "hp_title": "前五百天",
      "hp_makettime": "2016-10-15 21:00:00",
      "guide_word": "他们不说恋爱前五百天，他们就说前五百天。他们不想争论爱情是什么时候开始的。",
      "author": [
        {
          "user_id": "7292819",
          "user_name": "沈诞琦",
          "web_url": "http://image.wufazhuce.com/FvyzCEjoM6VsOYbNIKbbnL-i4jEj",
          "desc": "咨询管理师。",
          "wb_name": ""
        }
      ],
      "has_audio": true
    },
    {
      "content_id": "1557",
      "hp_title": "教堂恋人",
      "hp_makettime": "2016-10-14 21:00:00",
      "guide_word": "北山人常说：对天上的月亮神魂颠倒，对地上的硬币视而不见。",
      "author": [
        {
          "user_id": "7374963",
          "user_name": "单桐兴",
          "web_url": "http://image.wufazhuce.com/FtOIL7BskeYMiIH90UlWcLp50Hhg",
          "desc": "编剧。",
          "wb_name": "@少年单的奇幻漂流。"
        }
      ],
      "has_audio": true
    },
    {
      "content_id": "1556",
      "hp_title": "闺蜜",
      "hp_makettime": "2016-10-13 21:00:00",
      "guide_word": "这是她报复他的方式，是一记无声的耳光，宣告她已经不在乎他的狗屁爱情了。",
      "author": [
        {
          "user_id": "4814882",
          "user_name": "胡弃暗",
          "web_url": "http://image.wufazhuce.com/FjLJsypAEhAaxUIRE050ux_KixD-",
          "desc": "大龄文青。",
          "wb_name": "@胡弃暗2013"
        }
      ],
      "has_audio": true
    },
    {
      "content_id": "1558",
      "hp_title": "云想衣裳",
      "hp_makettime": "2016-10-12 21:00:00",
      "guide_word": "“岂止衣裳不知道放哪了。你现在年轻，不知道的还多着呢。”",
      "author": [
        {
          "user_id": "4814689",
          "user_name": "吴浩然",
          "web_url": "http://image.wufazhuce.com/FmOhi8FLn8coSUAU2neYOx6P1w0h",
          "desc": "青年作家。",
          "wb_name": "@浩然习比"
        }
      ],
      "has_audio": true
    },
    {
      "content_id": "1554",
      "hp_title": "她在捉些什么",
      "hp_makettime": "2016-10-11 21:00:00",
      "guide_word": "这一夜阿明睡在绿色的垃圾桶里，她多么舒服啊，又是多么安详。",
      "author": [
        {
          "user_id": "7367746",
          "user_name": "王占黑",
          "web_url": "http://image.wufazhuce.com/FmzvvB7h1h88M3WfIySeDSGZn49V",
          "desc": "还没毕业，也没工作。WeChat：wangzhanhei",
          "wb_name": ""
        }
      ],
      "has_audio": true
    },
    {
      "content_id": "1555",
      "hp_title": "消失的人鱼",
      "hp_makettime": "2016-10-10 21:00:00",
      "guide_word": "若人鱼所渴望的都未得偿所愿，当她们的心中涌起生而为人的不满，记忆会苏醒，一旦苏醒，必须回到大海。",
      "author": [
        {
          "user_id": "4814711",
          "user_name": "姚瑶",
          "web_url": "http://image.wufazhuce.com/FgQOEmoDXTqafhlK3D0jk8PNgItR",
          "desc": "作家，翻译，独立摄影师。@姚瑶vagrancy",
          "wb_name": "@姚瑶vagrancy"
        }
      ],
      "has_audio": true
    },
    {
      "content_id": "1553",
      "hp_title": "明天",
      "hp_makettime": "2016-10-09 21:00:00",
      "guide_word": "酒是好东西，试图让别人明白自己是噩梦，酒是美梦，会温暖你，治愈你。",
      "author": [
        {
          "user_id": "4814676",
          "user_name": "刘文",
          "web_url": "http://image.wufazhuce.com/Fgs5kZ36FmPNRo7BqSBisRvcSodM",
          "desc": "审计师，青年写作者。@刘文tracy",
          "wb_name": ""
        }
      ],
      "has_audio": true
    },
    {
      "content_id": "1552",
      "hp_title": "海那边的人",
      "hp_makettime": "2016-10-08 21:00:00",
      "guide_word": "要想在这个艰难的世界上活下去，我们这样的人必须摆出善良的姿态，小心翼翼地将自己罪行隐藏，那堵没有尽头的墙壁永远在那里，无法逾越。",
      "author": [
        {
          "user_id": "4814795",
          "user_name": "李维北",
          "web_url": "http://image.wufazhuce.com/FtYBiYEg2U6ggmLKgBZOsTKRqmJG",
          "desc": "李维北，青年作者。新书《用你的名字写个故事》即将上市。",
          "wb_name": "@李维北"
        }
      ],
      "has_audio": true
    },
    {
      "content_id": "1551",
      "hp_title": "葬礼",
      "hp_makettime": "2016-10-07 21:00:00",
      "guide_word": "这两个月里，我时常想象奶奶死去，顺顺当当地就把这事儿接受了，因为她的死已成定局。",
      "author": [
        {
          "user_id": "5553895",
          "user_name": "秋名",
          "web_url": "http://image.wufazhuce.com/FvZX7Jldv1jvJwkWYAUiJ5oHMrkT",
          "desc": "秋名，青年写作者。@秋名xcl，微信公众号：秋名书店",
          "wb_name": "@秋名xcl"
        }
      ],
      "has_audio": true
    },
    {
      "content_id": "1550",
      "hp_title": "良宵",
      "hp_makettime": "2016-10-06 21:00:00",
      "guide_word": "走进铁门，在阴湿、幽暗的楼道里，他的欲望更加强烈。他凶猛地想要占有一个人。",
      "author": [
        {
          "user_id": "4814755",
          "user_name": "徐畅",
          "web_url": "http://image.wufazhuce.com/FqZwhVU1uaXzED9h5rQCymJi_XWG",
          "desc": "徐畅，小说作者、编剧、野外生存爱好者。",
          "wb_name": "@徐畅--- 。"
        }
      ],
      "has_audio": true
    },
    {
      "content_id": "1548",
      "hp_title": "寂寞芳心俱乐部",
      "hp_makettime": "2016-10-05 21:00:00",
      "guide_word": "我们相识的时候，就像两个走了很久的赶路人，突然在一个岔口相遇。我们疲惫得只想就地坐下，连去谈论身后的那条路的力气也没有。",
      "author": [
        {
          "user_id": "4814812",
          "user_name": "林西拿",
          "web_url": "http://image.wufazhuce.com/FsTtJA_RBWpXIPoKIKUcYch57P1V",
          "desc": "学生、90后写作者。",
          "wb_name": "@林西拿"
        }
      ],
      "has_audio": true
    },
    {
      "content_id": "1547",
      "hp_title": "他没有名字，他叫9527",
      "hp_makettime": "2016-10-04 21:00:00",
      "guide_word": "我们小区刚有人入住的时候，9527是第一个来摆摊卖水果的。男人离不开啤酒，女人离不开水果，这是自古的道理。",
      "author": [
        {
          "user_id": "5541614",
          "user_name": "绒绒",
          "web_url": "http://image.wufazhuce.com/FnT7-zyYmZeammnFD1IuG14i2Nkg",
          "desc": "一个喜欢讲故事的梦想家，已出版《输一回吧，姑娘》。",
          "wb_name": "@小绒绒往前走"
        }
      ],
      "has_audio": true
    },
    {
      "content_id": "1544",
      "hp_title": "奔丧",
      "hp_makettime": "2016-10-03 21:00:00",
      "guide_word": "死掉的人其实是他自己，他正在给自己送葬。白色的纸钱漫天飞舞，打在他脸上，等到他把纸钱从脸上抠起来时，他才发现自己已经哭了。",
      "author": [
        {
          "user_id": "4814913",
          "user_name": "远子",
          "web_url": "http://image.wufazhuce.com/FpxK_69dEyDmVThtzxgiKz0iV4bD",
          "desc": "远子，作家。@远子归",
          "wb_name": ""
        }
      ],
      "has_audio": true
    },
    {
      "content_id": "1549",
      "hp_title": "莲花落",
      "hp_makettime": "2016-10-02 21:00:00",
      "guide_word": "提了一口气，他开了嗓。他狠狠地咬着每一个字，就像咬着自己的心。",
      "author": [
        {
          "user_id": "6864616",
          "user_name": "赵中豪",
          "web_url": "http://image.wufazhuce.com/FhChfNO6UXcsRmiOBqo52Ku5_Ebl",
          "desc": "青年写作者，编剧，待业青年。",
          "wb_name": "@赵中豪2309"
        }
      ],
      "has_audio": true
    },
    {
      "content_id": "1546",
      "hp_title": "杀人报道",
      "hp_makettime": "2016-10-01 21:00:00",
      "guide_word": "死人不会说话——光这点就很美了，但更妙的是，我要死人通过我的这支笔来说出她们的故事，因为美的东西是不应该深埋于地下的。",
      "author": [
        {
          "user_id": "4814715",
          "user_name": "孔龙",
          "web_url": "http://image.wufazhuce.com/FnokT0hC0BMJZeD_PahCmDUJ0Tm9",
          "desc": "警察，青年写作者，微信公众号：孔龙故事。",
          "wb_name": "@孔龙loong "
        }
      ],
      "has_audio": true
    }
  ]
}
```

## 列表项字段解析
|       字段        |       类型        |       含义        |
|-------------------|:-----------------:|:-----------------:|
|       content_id  |	    String      |	                |
|       hp_title	|       String	    |                   |
|       hp_makettime|	    String	    |   格式（2016-07-31 21:00:00）|
|       guide_word	|       String      |                   |
|       author	    |       Array	    |**这个字段类型是array, 要特别注意一点**|
|       has_audio	|       Boolean	    |   是否有音频      |