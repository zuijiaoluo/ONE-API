
# 根据类型请求评论列表数据

## URL
http://v3.wufazhuce.com:8000/api/comment/praiseandtime/${type}/${id}/${index}

## 参数
+ type      ————>       ('essay'、'serial'、'question'、'music'、'movie')分别代表短篇、连载、问答、音乐、电影
+ id        ————>       id
+ index     ————>       ONE APP中分页拉取规则都是一样的, 拉取第一页时id字段一定得传0, 会返回一个评论信息列表, 列表中每一项都会有一个id字段, 拉取第n页时id等于上一次所拉取到的列表最后一项的id,
比如, 第一次拉取到的列表最后一项信息id字段等于34613, 则拉取第二页时令index == 34613. 当返回列表为空时, 则代表没有下一页数据了

## 请求示范
+ http://v3.wufazhuce.com:8000/api/comment/praiseandtime/movie/141/0
+ http://v3.wufazhuce.com:8000/api/comment/praiseandtime/movie/141/34613
+ http://v3.wufazhuce.com:8000/api/comment/praiseandtime/movie/141/34176

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
  "data": {
    "count": 162,
    "data": [
      {
        "id": "33930",
        "quote": "",
        "content": "同样认为，这是一部需要内心世界还藏着一个孩子，才能读懂的电影。",
        "praisenum": 3,
        "device_token": "",
        "del_flag": "0",
        "reviewed": "1",
        "user_info_id": "10089",
        "input_date": "2016-10-20 00:04:55",
        "created_at": "2016-10-20 00:04:55",
        "updated_at": "2016-10-20 11:24:39",
        "user": {
          "user_id": "257039",
          "user_name": "逝去的过客",
          "web_url": "http://tp3.sinaimg.cn/1771228674/180/40009059813/0"
        },
        "touser": null,
        "score": "98",
        "type": 1
      },
      {
        "id": "33871",
        "quote": "",
        "content": "我知道它在反复，但我不懂得那是伤害。",
        "praisenum": 2,
        "device_token": "",
        "del_flag": "0",
        "reviewed": "1",
        "user_info_id": "10089",
        "input_date": "2016-10-19 23:15:21",
        "created_at": "2016-10-19 23:15:21",
        "updated_at": "2016-10-20 10:49:07",
        "user": {
          "user_id": "7403443",
          "user_name": "　 　",
          "web_url": "http://wx.qlogo.cn/mmopen/mIuibiaBIGnQHyr7VkDN0tX0WoNku6icTCWPZXXmhqrhxUV3WWo9zmUOUuchy2UbeP0MhGRd7hr9jqX7sO9gU5Eib3M8RAI6ia9am/0"
        },
        "touser": null,
        "score": "0",
        "type": 1
      },
      {
        "id": "33829",
        "quote": "",
        "content": "快乐当然有一点 不过寂寞更强烈",
        "praisenum": 1,
        "device_token": "",
        "del_flag": "0",
        "reviewed": "1",
        "user_info_id": "10089",
        "input_date": "2016-10-19 22:33:01",
        "created_at": "2016-10-19 22:33:01",
        "updated_at": "2016-10-20 11:25:55",
        "user": {
          "user_id": "7403287",
          "user_name": "过往",
          "web_url": "http://q.qlogo.cn/qqapp/1104596227/971A6FCF919A24A278477EBD2E543AB0/40"
        },
        "touser": null,
        "score": "86",
        "type": 1
      },
      {
        "id": "33812",
        "quote": "",
        "content": "现在我偷偷的哭，然后大声的笑。“这是一个金色的梦，我听到了他孤独的心，就像你一样。”一个人看完电影，一个人回家，我望着天空，真的、真的孤独极了。还好我还有一个梦是唯美的、纯净的、温暖的。",
        "praisenum": 5,
        "device_token": "",
        "del_flag": "0",
        "reviewed": "1",
        "user_info_id": "10089",
        "input_date": "2016-10-19 22:20:58",
        "created_at": "2016-10-19 22:20:58",
        "updated_at": "2016-10-20 11:25:55",
        "user": {
          "user_id": "3001894",
          "user_name": "smile_糊涂蛋",
          "web_url": "http://tp2.sinaimg.cn/3044749185/180/5709119191/1"
        },
        "touser": null,
        "score": "98",
        "type": 1
      },
      {
        "id": "33697",
        "quote": "",
        "content": "支持斯皮尔伯格，支持那些持续把我们儿时幻想搬上银幕的人们。",
        "praisenum": 2,
        "device_token": "",
        "del_flag": "0",
        "reviewed": "1",
        "user_info_id": "10089",
        "input_date": "2016-10-19 19:03:38",
        "created_at": "2016-10-19 19:03:38",
        "updated_at": "2016-10-20 11:24:24",
        "user": {
          "user_id": "6900784",
          "user_name": "GraviTy",
          "web_url": "http://image.wufazhuce.com/FscBrlq9A2b_SjFFOM226qjaQP07"
        },
        "touser": null,
        "score": "99",
        "type": 1
      },
      {
        "id": "33691",
        "quote": "",
        "content": "所谓真善美，所谓童真，一切的出发点无非都是美好的，别抹灭了它",
        "praisenum": 1,
        "device_token": "",
        "del_flag": "0",
        "reviewed": "1",
        "user_info_id": "10089",
        "input_date": "2016-10-19 15:57:24",
        "created_at": "2016-10-19 15:57:24",
        "updated_at": "2016-10-19 16:01:16",
        "user": {
          "user_id": "5336067",
          "user_name": "雨后阳光下的影子",
          "web_url": "http://tp4.sinaimg.cn/2123434475/50/5741481256/1"
        },
        "touser": null,
        "score": "83",
        "type": 1
      },
      {
        "id": "33689",
        "quote": "",
        "content": "我给98分不是说这电影有多完美，而是觉得它基于过去的奇幻，它依然能有所突破，让人觉得故事与剧情点到正中下怀的感觉，特别的止痒。",
        "praisenum": 3,
        "device_token": "",
        "del_flag": "0",
        "reviewed": "1",
        "user_info_id": "10089",
        "input_date": "2016-10-19 14:39:34",
        "created_at": "2016-10-19 14:39:34",
        "updated_at": "2016-10-19 14:43:40",
        "user": {
          "user_id": "4175093",
          "user_name": "文字诠释一种心情",
          "web_url": "http://tp4.sinaimg.cn/2753922695/180/5631327496/1"
        },
        "touser": null,
        "score": "98",
        "type": 1
      },
      {
        "id": "33687",
        "quote": "",
        "content": "一个孩子的童话故事，注定没什么太大的跌宕起伏，有的地方确实快睡着了，但是放屁是本片最大的看点！！！",
        "praisenum": 1,
        "device_token": "",
        "del_flag": "0",
        "reviewed": "1",
        "user_info_id": "10089",
        "input_date": "2016-10-19 13:34:27",
        "created_at": "2016-10-19 13:34:27",
        "updated_at": "2016-10-19 13:40:02",
        "user": {
          "user_id": "4619882",
          "user_name": "Casablanca",
          "web_url": "http://image.wufazhuce.com/Fm8TDjj1WbQJHuFPzhmq3iCykgbL"
        },
        "touser": null,
        "score": "90",
        "type": 1
      },
      {
        "id": "33682",
        "quote": "",
        "content": "没有什么多感动没有什么大道理，但是每次回想都会想到BFG的笑容，那么慈祥那么舒心，超级温暖，超级大暖男。很爱那个\"小老头\"",
        "praisenum": 3,
        "device_token": "",
        "del_flag": "0",
        "reviewed": "1",
        "user_info_id": "10089",
        "input_date": "2016-10-19 11:36:51",
        "created_at": "2016-10-19 11:36:51",
        "updated_at": "2016-10-19 11:44:27",
        "user": {
          "user_id": "5566338",
          "user_name": "南栀i",
          "web_url": "http://q.qlogo.cn/qqapp/1104596227/61949AEA21327C3F03C0ABEB9EA85CD7/40"
        },
        "touser": null,
        "score": "100",
        "type": 1
      },
      {
        "id": "33678",
        "quote": "",
        "content": "周末去看这部电影期待了好久 看的过程里确实会笑到不知道为什么最后看完心里特别难受 只有小时候才会有这么多的美好 长大以后完全不同 我的圆梦巨人在远方是不是也能听到我对他说的话 不远万里",
        "praisenum": 1,
        "device_token": "",
        "del_flag": "0",
        "reviewed": "1",
        "user_info_id": "10089",
        "input_date": "2016-10-19 10:54:23",
        "created_at": "2016-10-19 10:54:23",
        "updated_at": "2016-10-19 11:02:49",
        "user": {
          "user_id": "4404390",
          "user_name": "没有人像你",
          "web_url": "http://image.wufazhuce.com/Fgrmd1wdt2BcUGaiwN27pR4CgAlB"
        },
        "touser": null,
        "score": "88",
        "type": 1
      },
      {
        "id": "33677",
        "quote": "",
        "content": "就仿佛看动画片的感觉吧。很舒服",
        "praisenum": 0,
        "device_token": "",
        "del_flag": "0",
        "reviewed": "1",
        "user_info_id": "10089",
        "input_date": "2016-10-19 10:42:01",
        "created_at": "2016-10-19 10:42:01",
        "updated_at": "2016-10-19 10:53:29",
        "user": {
          "user_id": "5685014",
          "user_name": "HUANG MM🍒",
          "web_url": "http://wx.qlogo.cn/mmopen/hLxK5cQqoPYoaAGjxZJfWJeks43HSXXnNcO4Gqh1QmxyI5n1WaJ1zDOCtZtVQgrNYiaU0AdEmC595MjMlIxDJAIxMiap3kYa8g/0"
        },
        "touser": null,
        "score": "82",
        "type": 1
      },
    ]
  }
}
```

## 列表项字段解析
|       字段        |       类型        |       含义        |
|-------------------|:-----------------:|:-----------------:|
|       id	        |       String	    |                   |
|       quote	    |       String      |       引用        |
|       content     |   	String      |   发表的评论内容  |
|       praisenum   |   	Integer     |	                |
|       device_token|   	String	    |                   |
|       del_flag    |   	String      |	                |
|       reviewed    |   	String      |	                |
|       user_info_id|   	String      |	                |
|       input_date	|       String      |	                |
|       created_at  |   	String      |	                |
|       updated_at  |	    String	    |                   |
|       user        |   	Object	    |   发表者的信息    |
|       touser      |       Object	    |这条信息所回复的那个人|
|       score       |   	String	    |评分（只有电影的评论才有该字段）|
|       type	    |       Integer	    |   0代表是热门评论，1是普通评论|

