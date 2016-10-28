
# 请求图文详细信息

## URL
http://v3.wufazhuce.com:8000/api/hp/detail/${id}

## 参数
音乐id

## 请求示例
+ http://v3.wufazhuce.com:8000/api/hp/detail/1507

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
    "hpcontent_id": "1507",
    "hp_title": "VOL.1482",
    "author_id": "-1",
    "hp_img_url": "http://image.wufazhuce.com/FjLd4Qb4FgUfKN8AKV8VMtbZdB0L",
    "hp_img_original_url": "http://image.wufazhuce.com/FjLd4Qb4FgUfKN8AKV8VMtbZdB0L",
    "hp_author": "爱情Ⅱ&Jiangdada 作品",
    "ipad_url": "http://image.wufazhuce.com/FlzpPNccTaIUg4h4qAVz6lmCC_YQ",
    "hp_content": "爱情是许诺之地，是一条两人得以逃脱洪水的方舟。 by 朱利安·巴恩斯",
    "hp_makettime": "2016-10-27 21:00:00",
    "last_update_date": "2016-10-24 15:02:31",
    "web_url": "http://m.wufazhuce.com/one/1507",
    "wb_img_url": "",
    "praisenum": 7384,
    "sharenum": 318,
    "commentnum": 0
  }
}
```

## 列表项字段解析
|       字段        |       类型        |       含义        |
|-------------------|:-----------------:|:-----------------:|
|   hpcontent_id    |   	String      |	                |
|   hp_title	    |       String	    |                   |
|   author_id       |   	String	    |                   |
|   hp_img_url      |	    String      |                   |
|hp_img_original_url|	    String      |                   |
|   hp_author	    |       String	    |                   |
|   ipad_url	    |       String      |                   |
|   hp_content	    |       String      |                   |
|   hp_makettime    |   	String      |	                |
|   last_update_date|	    String      |	                |
|   web_url         |   	String      |	                |
|   wb_img_url	    |       String	    |                   |
|   praisenum       |   	Integer	    |                   |
|   sharenum	    |       Integer	    |                   |
|   commentnum	    |       Integer	    |                   |
