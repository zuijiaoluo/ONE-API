
# 请求连载文章详细信息

## URL
http://v3.wufazhuce.com:8000/api/serialcontent/${id}

## 参数
+ id    ————>     简略信息中的id字段, 而不是serial_id

## 请求示例
+ http://v3.wufazhuce.com:8000/api/serialcontent/194

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
    "id": "194",
    "serial_id": "33",
    "number": "14",
    "title": "玩家·第十四话",
    "excerpt": "“你不相信自由意志？” “也许它不是假的，但我更相信……” “命运。”",
    "content": "2015年7月9日星期四<br>\r\n<br>\r\n一年零六个月以来，徐杰第一次孤身一人从“皇豪”中走出来。身边没有女生，并不是因为他的搭讪实力退步了，而仅仅是因为不想。<br>\r\nbr>\r\n<br>\r\n（《玩家》第一季终。本周六开始连载张寒寺的最新长篇《昨日重现》）.....",
    "charge_edt": "（责任编辑：金子棋）",
    "read_num": "12900",
    "maketime": "2016-10-27 21:00:00",
    "last_update_date": "2016-10-27 19:48:55",
    "audio": "",
    "web_url": "http://m.wufazhuce.com/serial/194",
    "input_name": "10008",
    "last_update_name": "黄..",
    "author": {
      "user_id": "4813765",
      "user_name": "夜X",
      "web_url": "http://image.wufazhuce.com/Fkr-24izoJEPeeKJ0Zwga9xB325N",
      "desc": "作家，编剧。公众号：不投币故事贩卖机"
    },
    "praisenum": 255,
    "sharenum": 12,
    "commentnum": 74
  }
}
```

## 列表项字段解析
|       字段        |       类型        |       含义        |
|-------------------|:-----------------:|:-----------------:|
|       id          |   	String	    |                   |
|       serial_id   |	    String	    |                   |
|       number	    |       String	    |                   |
|       title	    |       String      |                   |
|       excerpt	    |       String	    |                   |
|       content	    |       String	    |       文章正文    |
|       charge_edt	|       String	    |       责任编辑    |
|       read_num	|       String	    |                   |
|       maketime	|       String	    |                   |
|   last_update_date|	    String	    |                   |
|       audio	    |       String      |       是否有音频  |
|       web_url	    |       String      |	                |
|       input_name	|       String	    |                   |
|   last_update_name|   	String	    |                   |
|       author      |   	Object	    |       作者信息    |
|       praisenum	|       Integer	    |                   |
|       sharenum	|       Integer     |                   |
|       commentnum	|       Integer	    |                   |