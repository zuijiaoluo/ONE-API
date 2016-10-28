
# 分页请求电影信息列表

## URL
http://v3.wufazhuce.com:8000/api/movie/list/${id}

## 参数
ONE APP中分页拉取规则都是一样的, 拉取第一页时id字段一定得传0, 会返回一个电影信息列表, 列表中每一项都会有一个id字段, 拉取第n页时id等于上一次所拉取到的列表最后一项的id,
比如, 第一次拉取到的列表最后一项电影信息id字段等于198, 则拉取第二页时令id == 198. 当返回列表为空时, 则代表没有下一页数据了

## 请求示例
+ http://v3.wufazhuce.com:8000/api/movie/list/0

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
      "id": "145",
      "title": "侠探杰克：永不回头",
      "verse": "",
      "verse_en": "",
      "score": "73",
      "revisedscore": "0",
      "releasetime": "2016-10-21 00:00:00",
      "scoretime": "2016-10-22 00:00:00",
      "cover": "http://image.wufazhuce.com/FrN3ohkTuop315TPw8_3JR3-Sj4u",
      "servertime": 1477451008
    },
    {
      "id": "144",
      "title": "惊天破",
      "verse": "",
      "verse_en": "",
      "score": "76",
      "revisedscore": "0",
      "releasetime": "2016-10-20 18:00:00",
      "scoretime": "2016-10-21 18:00:00",
      "cover": "http://image.wufazhuce.com/FlW32pyUx12pj8OlIbgyqAE6r1gg",
      "servertime": 1477451008
    },
    {
      "id": "146",
      "title": "机械师2：复活",
      "verse": "",
      "verse_en": "",
      "score": "83",
      "revisedscore": "0",
      "releasetime": "2016-10-21 00:00:00",
      "scoretime": "2016-10-22 00:00:00",
      "cover": "http://image.wufazhuce.com/FqK1M9DKNJj9QQSJpkfqBlszfnvL",
      "servertime": 1477451008
    },
    {
      "id": "147",
      "title": "龙珠Z：复活的弗利萨",
      "verse": "",
      "verse_en": "",
      "score": "78",
      "revisedscore": "0",
      "releasetime": "2016-10-21 00:00:00",
      "scoretime": "2016-10-22 00:00:00",
      "cover": "http://image.wufazhuce.com/FiEEN19MMrQHR5x6swuYNWBqJwQl",
      "servertime": 1477451008
    },
    {
      "id": "143",
      "title": "勇士",
      "verse": "",
      "verse_en": "",
      "score": "75",
      "revisedscore": "0",
      "releasetime": "2016-10-14 00:00:00",
      "scoretime": "2016-10-15 00:00:00",
      "cover": "http://image.wufazhuce.com/Fle9u8kbcvRDrqq1cUwABb1Bl93J",
      "servertime": 1477451008
    }
  ]
}
```

## 列表项字段解析
|       字段         |       类型        |       含义        |
|-------------------|:-----------------:|:-----------------:|
|       id	        |       String	    |                   |
|       title       |	    String      |	    标题        |
|       verse       |	    String      |                   |
|       verse_en    |	    String      |                   |
|       score       |	    String      |	                |
|       revisedscore|	    String      |	                |
|       releasetime |	    String      |	格式(2016-10-21 00:00:00)|
|       scoretime	|       String      |	格式同上        |
|       cover       |	    String      |	封面图片        |
|       servertime  |	    Integer     |	                |