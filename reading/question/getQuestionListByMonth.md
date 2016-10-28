
# 根据年月份请求问答文章列表

## URL
http://v3.wufazhuce.com:8000/api/question/bymonth/${year}-${month}

## 参数
+ year    ————>     年份
+ month   ————>     月份
+ 注意: 问答文章是2012年10月才开始有的, 所有如果请求年月份小于2012年10月的话, 将返回一个空列表

## 请求示例
+ http://v3.wufazhuce.com:8000/api/question/bymonth/2016-10

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
      "question_id": "1511",
      "question_title": "情侣之间如何处理假性亲密的感情？",
      "answer_title": "@大将军郭 答Kira：",
      "answer_content": "其实，爱人耐不住冷落，亲密耗不过沉默。",
      "question_makettime": "2016-10-27 21:00:00"
    },
    {
      "question_id": "1515",
      "question_title": "人人都骂渣男，那有没有渣女？",
      "answer_title": "@露易莎大能个儿 答最可爱的熊：",
      "answer_content": "女孩总会这样，当你拥有她们没有又得不到的事物时，她们往往会开始疯狂，会孤立，会造谣。企图让你远离她们的世界。",
      "question_makettime": "2016-10-26 21:00:00"
    },
    {
      "question_id": "1514",
      "question_title": "怎样看待那些测试别人是否还是好友的消息？",
      "answer_title": "暖小团答小晓：",
      "answer_content": "你没有任何资格决定别人按照什么方式而活。",
      "question_makettime": "2016-10-25 21:00:00"
    },
    {
      "question_id": "1513",
      "question_title": "出生顺序对人有影响吗？",
      "answer_title": "温义飞答夜芳：",
      "answer_content": "在有五个子女的家庭中，最年长和最年幼的孩子的教育水平差距，几乎等于白人与黑人的教育水平差距。\n",
      "question_makettime": "2016-10-24 21:00:00"
    },
    {
      "question_id": "1512",
      "question_title": "为什么保持童心很重要？",
      "answer_title": "@傅踢踢 答禄卡：",
      "answer_content": "我能想到最浪漫的事，就是保护世间所有的童心。",
      "question_makettime": "2016-10-23 21:00:00"
    },
    {
      "question_id": "1510",
      "question_title": "人为什么会吸毒？",
      "answer_title": "@lekli 答木小羽：",
      "answer_content": "在第一次吸食毒品后，吸毒者往往心存侥幸，觉得自己会是那个漏网之鱼，直到落入法网，才追悔莫及。",
      "question_makettime": "2016-10-22 21:00:00"
    },
    {
      "question_id": "1507",
      "question_title": "有耐心重要吗？",
      "answer_title": "@花大钱 答谢啥：",
      "answer_content": "所谓的忙碌都是假相，从一个场景中迅速抽身也不过是奔赴下一场虚无，每个人都太急躁太混乱了。",
      "question_makettime": "2016-10-21 21:00:00"
    },
    {
      "question_id": "1505",
      "question_title": "如何正确看待那些很low的朋友圈？",
      "answer_title": "@吴清缘很忧郁 答马勒：",
      "answer_content": "要知道，这个世界有趣的人很多，但并不是每一个有趣的人，都有趣在了朋友圈嘛。",
      "question_makettime": "2016-10-20 21:00:00"
    },
    {
      "question_id": "1509",
      "question_title": "不想用套路的人，是不是什么也得不到？",
      "answer_title": "达达令答阳阳：",
      "answer_content": "每一种生活都是活着，可是能够不刻意为难自己，那才是难得的部分。",
      "question_makettime": "2016-10-19 21:00:00"
    },
    {
      "question_id": "1508",
      "question_title": "与父母之间应该保持怎样的距离？",
      "answer_title": "红肚兜儿答生气的纸巾：",
      "answer_content": "亲生的孩子，也总要成年，总要有自己的一场人生要过，适时地退场，是父母必须要做的选择。",
      "question_makettime": "2016-10-18 21:00:00"
    },
    {
      "question_id": "1506",
      "question_title": "单亲家庭的母女关系会更脆弱吗？",
      "answer_title": "@高浩容 答微微：",
      "answer_content": "单亲妈妈是个过时的词汇，“单亲女性”更符合现今性别自由的价值。",
      "question_makettime": "2016-10-17 21:00:00"
    },
    {
      "question_id": "1504",
      "question_title": "如何有趣地回复“在干吗”？",
      "answer_title": "@三三坡 答麻乐乐：",
      "answer_content": "我时常因此迷惑，尽管我早就有心理准备，无论我积攒多少知识与经验，能做的也就是离“爱”更接近，那其实是一个我永远无法真正解开的谜语。",
      "question_makettime": "2016-10-16 21:00:00"
    },
    {
      "question_id": "1503",
      "question_title": "为何有些人喜欢艰苦的骑行或者徒步运动？",
      "answer_title": "冯慎行答依依：",
      "answer_content": "这种孤独就是剥开了包裹的心、脱离了背景的情绪，我们更容易将震撼和热泪，送给那些心向往之的景色和生活。",
      "question_makettime": "2016-10-15 21:00:00"
    },
    {
      "question_id": "1501",
      "question_title": "工作后如何继续成长？",
      "answer_title": "@小川叔 答布达佩斯小酒馆：",
      "answer_content": "能不能在乏味的重复里找到属于你的成长乐趣，这才是你的智慧。",
      "question_makettime": "2016-10-14 21:00:00"
    },
    {
      "question_id": "1502",
      "question_title": "该怎么看待婚前同居？",
      "answer_title": "@高浩容 答一二三：",
      "answer_content": "同居可能只是恋爱的一部分，而恋爱又是走向婚姻的一部分，但婚姻又是什么？婚姻不过是人生的一部分。",
      "question_makettime": "2016-10-13 21:00:00"
    },
    {
      "question_id": "1500",
      "question_title": "人与人之间的信任到底有多脆弱？",
      "answer_title": "@周宏翔 答潘大曼：",
      "answer_content": "有时候并非我们真正感到孤独，而是我们太敏感，太恐惧，太害怕受伤，才会让自己孤独。",
      "question_makettime": "2016-10-12 21:00:00"
    },
    {
      "question_id": "1499",
      "question_title": "被喜欢的人拉黑了怎么办？",
      "answer_title": "不辣答木易的朋友：",
      "answer_content": "人呐，始终都是一种健忘的畜生，自以为的深情说不定吃完一顿火锅就忘了。",
      "question_makettime": "2016-10-11 21:00:00"
    },
    {
      "question_id": "1497",
      "question_title": "鸡汤为何有毒？",
      "answer_title": "黄辉答熊小力：",
      "answer_content": "把作品当成产品，把作者当成“产品经理”，把读者粉丝变现成“广告价值”，这就是所谓大微们的“推文商业逻辑”。",
      "question_makettime": "2016-10-10 21:00:00"
    },
    {
      "question_id": "1498",
      "question_title": "人们为什么在看到特别漂亮壮观的景色时有想哭的冲动？",
      "answer_title": "冯慎行答哭鬼：",
      "answer_content": "和通常的认识有所差异，流泪并不是痛苦、悲伤的反应，而是一种压力调节的机制。",
      "question_makettime": "2016-10-09 21:00:00"
    },
    {
      "question_id": "1490",
      "question_title": "能说出来的委屈，都不叫委屈吗？",
      "answer_title": "朱欢尘答左小腿：",
      "answer_content": "能够同情别人是一种能力，它促使我们不会变得越来越极端和自我中心，即使自己本身也在逆境中，也仍然保持一颗敏感、平和的心脏。",
      "question_makettime": "2016-10-08 21:00:00"
    },
    {
      "question_id": "1492",
      "question_title": "为什么被家暴的女人很多都不反抗？",
      "answer_title": "@负二_Negative_2 答KL后退：",
      "answer_content": "我们看到的那些对欺凌逆来顺受，我们都替他（她）着急的，其实已经深陷“习得性无助”中无法自救了。",
      "question_makettime": "2016-10-07 21:00:00"
    },
    {
      "question_id": "1494",
      "question_title": "怎么做才是正确的借钱姿势？",
      "answer_title": "@杨小米 答虞姬虞昔：",
      "answer_content": "生活就是这样，一个问题接一个问题需要解决，但我想只要努力，总会过去的。",
      "question_makettime": "2016-10-06 21:00:00"
    },
    {
      "question_id": "1495",
      "question_title": "古代养宠物有危险吗？",
      "answer_title": "@辉城啊 答金文弧：",
      "answer_content": "在古代，养宠物最大的风险是政治风险。",
      "question_makettime": "2016-10-05 21:00:00"
    },
    {
      "question_id": "1496",
      "question_title": "作家会爱上笔下的人物吗？",
      "answer_title": "@蔡骏 答BonBon：",
      "answer_content": "人物既是作家在创造，到了一定阶段以后，也是人物根据其内在规律，他们自己在创造自己。",
      "question_makettime": "2016-10-04 21:00:00"
    },
    {
      "question_id": "1493",
      "question_title": "安吉丽娜·朱莉是中国女性学习的榜样吗？",
      "answer_title": "汤店长答皮特先生：",
      "answer_content": "没有人想要去探寻生活的意义，也没有人想要去要求更多，毕竟，女孩们都在抢着做一件看上去很有逻辑的事：在正确的年龄做正确的事情。",
      "question_makettime": "2016-10-03 21:00:00"
    },
    {
      "question_id": "1491",
      "question_title": "为什么吵架时总是男人保持沉默？",
      "answer_title": "@大将军郭 答萱萱：",
      "answer_content": "无论何时，记得保持适度的沟通，交流才是让关系保鲜的养分。",
      "question_makettime": "2016-10-02 21:00:00"
    },
    {
      "question_id": "1489",
      "question_title": "真的“凡事都有例外”吗？",
      "answer_title": "达达令答木木：",
      "answer_content": "生活就是一张巨大的网，每一个点线面的构成，都穿梭着我们不可控的因素。可是我们不应该把这份不可控当成是例外的必然存在。",
      "question_makettime": "2016-10-01 21:00:00"
    }
  ]
}
```

## 列表项字段解析

|       字段        |       类型        |       含义        |
|-------------------|:-----------------:|:-----------------:|
|   question_id	    |       String      |	                |
|   question_title	|       String      |	                |
|   answer_title    |	    String	    |                   |
|   answer_content	|       String      |                   |
|question_makettime	|       String	    |                   |