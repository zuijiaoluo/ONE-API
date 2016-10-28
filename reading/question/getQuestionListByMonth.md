
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