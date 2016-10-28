
# 根据年月份请求连载文章列表

## URL
http://v3.wufazhuce.com:8000/api/serialcontent/bymonth/${year}-${month}

## 参数
+ year    ————>     年份
+ month   ————>     月份
+ 注意: 连载文章是2016年1月才开始有的, 所有如果请求年月份小于2016年1月的话, 将返回一个空列表

## 请求示例
+ http://v3.wufazhuce.com:8000/api/serialcontent/bymonth/2016-10

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
      "id": "194",
      "serial_id": "33",
      "number": "14",
      "title": "玩家·第十四话",
      "excerpt": "“你不相信自由意志？” “也许它不是假的，但我更相信……” “命运。”",
      "read_num": "12900",
      "maketime": "2016-10-27 21:00:00",
      "author": {
        "user_id": "4813765",
        "user_name": "夜X",
        "web_url": "http://image.wufazhuce.com/Fkr-24izoJEPeeKJ0Zwga9xB325N",
        "desc": "作家，编剧。公众号：不投币故事贩卖机"
      },
      "has_audio": false
    },
    {
      "id": "193",
      "serial_id": "33",
      "number": "13",
      "title": "玩家·第十三话",
      "excerpt": "周致淑开始一五一十地告诉陆仁甲什么是假的——",
      "read_num": "31300",
      "maketime": "2016-10-25 21:00:00",
      "author": {
        "user_id": "4813765",
        "user_name": "夜X",
        "web_url": "http://image.wufazhuce.com/Fkr-24izoJEPeeKJ0Zwga9xB325N",
        "desc": "作家，编剧。公众号：不投币故事贩卖机"
      },
      "has_audio": false
    },
    {
      "id": "192",
      "serial_id": "33",
      "number": "12",
      "title": "玩家·第十二话",
      "excerpt": "枪林弹雨也无法阻挡繁殖的欲望。也或者它本来就与死亡形影不离。",
      "read_num": "53000",
      "maketime": "2016-10-22 21:00:00",
      "author": {
        "user_id": "4813765",
        "user_name": "夜X",
        "web_url": "http://image.wufazhuce.com/Fkr-24izoJEPeeKJ0Zwga9xB325N",
        "desc": "作家，编剧。公众号：不投币故事贩卖机"
      },
      "has_audio": false
    },
    {
      "id": "191",
      "serial_id": "33",
      "number": "11",
      "title": "玩家·第十一话",
      "excerpt": "每个自慰过的男人都会告诉你，手不懂得羞愧，也没有荣誉感可言，它唯一会做的就是行动，行动，行动。",
      "read_num": "71900",
      "maketime": "2016-10-20 21:00:00",
      "author": {
        "user_id": "4813765",
        "user_name": "夜X",
        "web_url": "http://image.wufazhuce.com/Fkr-24izoJEPeeKJ0Zwga9xB325N",
        "desc": "作家，编剧。公众号：不投币故事贩卖机"
      },
      "has_audio": false
    },
    {
      "id": "190",
      "serial_id": "33",
      "number": "10",
      "title": "玩家·第十话",
      "excerpt": "吾爱吾师，但吾更爱真理。一个男人像亚里士多德爱柏拉图那样爱一个女人，应该已经够了——毕竟他们可是希腊人呐。",
      "read_num": "54100",
      "maketime": "2016-10-18 21:00:00",
      "author": {
        "user_id": "4813765",
        "user_name": "夜X",
        "web_url": "http://image.wufazhuce.com/Fkr-24izoJEPeeKJ0Zwga9xB325N",
        "desc": "作家，编剧。公众号：不投币故事贩卖机"
      },
      "has_audio": false
    },
    {
      "id": "189",
      "serial_id": "33",
      "number": "9",
      "title": "玩家·第九话",
      "excerpt": "在女朋友面前把自己比做乌龟，对一个男人来说说明了什么？陆仁甲不知道，只知道自己很认真。",
      "read_num": "64900",
      "maketime": "2016-10-15 21:00:00",
      "author": {
        "user_id": "4813765",
        "user_name": "夜X",
        "web_url": "http://image.wufazhuce.com/Fkr-24izoJEPeeKJ0Zwga9xB325N",
        "desc": "作家，编剧。公众号：不投币故事贩卖机"
      },
      "has_audio": false
    },
    {
      "id": "188",
      "serial_id": "33",
      "number": "8",
      "title": "玩家·第八话",
      "excerpt": "想完这些，他就像刚刚从马拉松跑回雅典的裴里庇第斯一样，闭上了双眼。",
      "read_num": "52700",
      "maketime": "2016-10-13 21:00:00",
      "author": {
        "user_id": "4813765",
        "user_name": "夜X",
        "web_url": "http://image.wufazhuce.com/Fkr-24izoJEPeeKJ0Zwga9xB325N",
        "desc": "作家，编剧。公众号：不投币故事贩卖机"
      },
      "has_audio": false
    },
    {
      "id": "187",
      "serial_id": "33",
      "number": "7",
      "title": "玩家·第七话",
      "excerpt": "愤怒是治疗恐惧的良方，而它自身的副作用大小因人而异。陆仁甲克服它只用了大概二十秒的时间。",
      "read_num": "52900",
      "maketime": "2016-10-11 21:00:00",
      "author": {
        "user_id": "4813765",
        "user_name": "夜X",
        "web_url": "http://image.wufazhuce.com/Fkr-24izoJEPeeKJ0Zwga9xB325N",
        "desc": "作家，编剧。公众号：不投币故事贩卖机"
      },
      "has_audio": false
    },
    {
      "id": "186",
      "serial_id": "33",
      "number": "6",
      "title": "玩家·第六话",
      "excerpt": "“哦，天哪。”陆仁甲知道周致淑是对的。这姑娘实在太聪明了，居然揭开了谜底，而这谜底实在太糟糕了。",
      "read_num": "67800",
      "maketime": "2016-10-08 21:00:00",
      "author": {
        "user_id": "4813765",
        "user_name": "夜X",
        "web_url": "http://image.wufazhuce.com/Fkr-24izoJEPeeKJ0Zwga9xB325N",
        "desc": "作家，编剧。公众号：不投币故事贩卖机"
      },
      "has_audio": false
    },
    {
      "id": "185",
      "serial_id": "33",
      "number": "5",
      "title": "玩家·第五话",
      "excerpt": "但陆仁甲几乎忘记了，生活之所以像生活而不像程序，就在于它尽管经过精心安排，还是会出岔子。",
      "read_num": "61300",
      "maketime": "2016-10-06 21:00:00",
      "author": {
        "user_id": "4813765",
        "user_name": "夜X",
        "web_url": "http://image.wufazhuce.com/Fkr-24izoJEPeeKJ0Zwga9xB325N",
        "desc": "作家，编剧。公众号：不投币故事贩卖机"
      },
      "has_audio": false
    },
    {
      "id": "184",
      "serial_id": "33",
      "number": "4",
      "title": "玩家·第四话",
      "excerpt": "5W，你到底是不慎容纳了一些怪胎，还是本身就是按照一个怪胎集中营来设计的？",
      "read_num": "61700",
      "maketime": "2016-10-04 21:00:00",
      "author": {
        "user_id": "4813765",
        "user_name": "夜X",
        "web_url": "http://image.wufazhuce.com/Fkr-24izoJEPeeKJ0Zwga9xB325N",
        "desc": "作家，编剧。公众号：不投币故事贩卖机"
      },
      "has_audio": false
    },
    {
      "id": "183",
      "serial_id": "33",
      "number": "3",
      "title": "玩家·第三话",
      "excerpt": "什么叫做好好表现？是指再也不提出“发一笔横财”这种荒唐的事件，还是不管事件多荒唐都努力完成它？陆仁甲自己也没想明白。",
      "read_num": "72300",
      "maketime": "2016-10-01 21:00:00",
      "author": {
        "user_id": "4813765",
        "user_name": "夜X",
        "web_url": "http://image.wufazhuce.com/Fkr-24izoJEPeeKJ0Zwga9xB325N",
        "desc": "作家，编剧。公众号：不投币故事贩卖机"
      },
      "has_audio": false
    }
  ]
}
```

## 列表项字段解析
|       字段        |       类型        |       含义        |
|-------------------|:-----------------:|:-----------------:|
|       id	        |       String	    |                   |
|       serial_id	|       String	    |   **这两个id得区分好**|
|       number	    |       String	    |                   |
|       title   	|       String	    |                   |
|       excerpt	    |       String      |       描述文字    |
|       read_num	|       String	    |                   |
|       maketime	|       String	    |格式（2016-06-30 21:00:00）|
|       author	    |       Object	    |                   |
|       has_audio   |	    Boolean 	|连载文章一般都没有音频|