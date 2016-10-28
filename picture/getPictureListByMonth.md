
# 根据年月份请求图文列表

## URL
http://v3.wufazhuce.com:8000/api/hp/bymonth/${year}-${month}

## 参数
+ year    ————>     年份
+ month   ————>     月份
+ 注意: 图文是2012年10月才开始有的, 所有如果请求年月份小于2012年10月的话, 将返回一个空列表

## 请求示范
+ http://v3.wufazhuce.com:8000/api/hp/bymonth/2015-9
+ http://v3.wufazhuce.com:8000/api/hp/bymonth/2016-10

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
      "hpcontent_id": "1509",
      "hp_title": "VOL.1480",
      "author_id": "-1",
      "hp_img_url": "http://image.wufazhuce.com/FvtnvNYhM9UAtIMiUgiZ5BaqUrjB",
      "hp_img_original_url": "http://image.wufazhuce.com/FvtnvNYhM9UAtIMiUgiZ5BaqUrjB",
      "hp_author": "无题&顾均 作品",
      "ipad_url": "http://image.wufazhuce.com/FqEl8aqDKRJXm4NImW_zSTt_AltB",
      "hp_content": "这世上，即便是极简单的事，也会因众人凑在一块儿而变得复杂。虽然看似复杂，但人生的本质，也许其实什么都不是。 from 《豆腐匠的哲学》",
      "hp_makettime": "2016-10-25 21:00:00",
      "last_update_date": "2016-10-25 12:26:19",
      "web_url": "http://m.wufazhuce.com/one/1509",
      "wb_img_url": "",
      "praisenum": 6627,
      "sharenum": 409,
      "commentnum": 0
    },
    {
      "hpcontent_id": "1505",
      "hp_title": "VOL.1479",
      "author_id": "-1",
      "hp_img_url": "http://image.wufazhuce.com/FgjWw_drWl1FgKT7jHS13UrAvFNK",
      "hp_img_original_url": "http://image.wufazhuce.com/FgjWw_drWl1FgKT7jHS13UrAvFNK",
      "hp_author": "远行&陈曦Stanley 作品",
      "ipad_url": "http://image.wufazhuce.com/FgjWw_drWl1FgKT7jHS13UrAvFNK",
      "hp_content": "只做自己喜欢的事，和无论做什么事都能从中发现乐趣，这是两种很了不起的能力。我们一直都在追求前一种，可实现前一种的途经，只有后一种。by 李诞",
      "hp_makettime": "2016-10-24 21:00:00",
      "last_update_date": "2016-10-21 16:54:14",
      "web_url": "http://m.wufazhuce.com/one/1505",
      "wb_img_url": "",
      "praisenum": 20227,
      "sharenum": 1861,
      "commentnum": 0
    },
    {
      "hpcontent_id": "1506",
      "hp_title": "VOL.1478",
      "author_id": "-1",
      "hp_img_url": "http://image.wufazhuce.com/FtaXVOoRVMsEu0-FjeMf4RDGe52C",
      "hp_img_original_url": "http://image.wufazhuce.com/FtaXVOoRVMsEu0-FjeMf4RDGe52C",
      "hp_author": "刹那&豆腐君 作品",
      "ipad_url": "http://image.wufazhuce.com/FkgT_WherCMeS1WqW3p0FIELJis4",
      "hp_content": "于是记忆，与其说是我们身体里的过去，不如说是我们活在当下的证明。 by 保罗·奥斯特",
      "hp_makettime": "2016-10-23 23:00:00",
      "last_update_date": "2016-10-23 17:44:19",
      "web_url": "http://m.wufazhuce.com/one/1506",
      "wb_img_url": "",
      "praisenum": 16189,
      "sharenum": 541,
      "commentnum": 0
    },
    {
      "hpcontent_id": "1504",
      "hp_title": "VOL.1477",
      "author_id": "-1",
      "hp_img_url": "http://image.wufazhuce.com/Fmr5cPZBBptxwBLAYUaNwTb5qNHX",
      "hp_img_original_url": "http://image.wufazhuce.com/Fmr5cPZBBptxwBLAYUaNwTb5qNHX",
      "hp_author": "布罗莫火山星空&桂林大河 作品",
      "ipad_url": "http://image.wufazhuce.com/FnsezQt8ZoBQosOKNAqdJkTTIrql",
      "hp_content": "认识你愈久，愈觉得你是我人生行路中一处清喜的水泽。几次想忘于世，总在山穷水尽处又悄然相见，算来即是一种不舍 。 from 《四月裂帛》",
      "hp_makettime": "2016-10-22 23:00:00",
      "last_update_date": "2016-10-19 14:19:02",
      "web_url": "http://m.wufazhuce.com/one/1504",
      "wb_img_url": "",
      "praisenum": 25542,
      "sharenum": 1435,
      "commentnum": 0
    },
    {
      "hpcontent_id": "1497",
      "hp_title": "VOL.1476",
      "author_id": "-1",
      "hp_img_url": "http://image.wufazhuce.com/Ft61Qjc786WdKB8c-FiqiQkHblc0",
      "hp_img_original_url": "http://image.wufazhuce.com/Ft61Qjc786WdKB8c-FiqiQkHblc0",
      "hp_author": "阳台耍流氓&陈阿花 作品",
      "ipad_url": "http://image.wufazhuce.com/FhhLYhqE4n6ZTRIPzYabNqsx4Fu_",
      "hp_content": "许多年过去了，人们说陈年旧事可以被埋葬，然而我终于明白这是错的，因为往事会自行爬上来。 by 卡勒德·胡赛尼",
      "hp_makettime": "2016-10-21 21:00:00",
      "last_update_date": "2016-10-19 12:13:57",
      "web_url": "http://m.wufazhuce.com/one/1497",
      "wb_img_url": "",
      "praisenum": 22467,
      "sharenum": 973,
      "commentnum": 0
    }
  ]
};
```

## 列表项字段解析
|       字段        |       类型        |       含义        |
|-------------------|:-----------------:|:-----------------:|
|   hpcontent_id    |	    String      |           id      |
|     hp_title      |	    String      |图片左下角文字     |
|     author_id     |	    String      |	作者id          |
|     hp_img_url    |	    String      |   图片地址        |
|hp_img_original_url|	    String      |                   |
|     hp_author     |	    String      |	图片右下角文字  |
|       ipad_url    |	    String      |                   |
|     hp_content    |	    String      |   文本            |
|     hp_makettime  |	    String      |	时间，格式2016-10-25 21:00:00|
|   last_update_date|	    String      |	时间，格式2016-10-25 21:00:00|
|     web_url       |	    String      |	                |
|     wb_img_url    |   	String      |                   |
|     praisenum     |	    Integer     |	    点赞数      |
|     sharenum      |	    Integer     |	    分享数      |
|     commentnum    |	    Integer     |	    评论数      |