
# 请求阅读顶部的滚动图片详细信息

## URL
http://v3.wufazhuce.com:8000/api/reading/carousel/${id}

## 参数
id  ————>  简略信息中的id

## 请求示例
http://v3.wufazhuce.com:8000/api/reading/carousel/109

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
      "item_id": "1495",
      "title": "古代养宠物有危险吗？",
      "author": "@辉城啊 答金文弧：",
      "introduction": "先说结论，风险非常大。\n \n古代不比现代，养宠物不但有道德的非议，更有政治上的风险。\n \n古代中国，",
      "web_url": "",
      "number": 0,
      "type": "3"
    },
    {
      "item_id": "434",
      "title": "闲着也是闲着，不如养只狗",
      "introduction": "你想，谁喜欢一只垂头丧气的狗呢？",
      "author": "李元",
      "web_url": "",
      "number": 0,
      "type": "1"
    },
    {
      "item_id": "1467",
      "title": "如何看待给宠物实施安乐死？",
      "author": "忧郁的道格答飞翔的吉娃娃：",
      "introduction": "这个问题会让人觉得难以回答，是因为其本身便有着复杂的面向。简单而言，将宠物送去安乐死的行为，在多数情",
      "web_url": "",
      "number": 0,
      "type": "3"
    },
    {
      "item_id": "998",
      "title": "宠物猫的生活是怎么样的？",
      "author": "刘吧唧答流浪的狼：",
      "introduction": "早上4：30。醒来，巡视领地，确认狗同伴的安全。早上4：38。前往水源处，饮水，发现储存食粮的地方只",
      "web_url": "",
      "number": 0,
      "type": "3"
    },
    {
      "item_id": "581",
      "title": "如果宠物会说话他们会跟你说什么？",
      "author": "网友答@一个App工作室：",
      "introduction": "@牧易说：在家能穿上衣服吗？@破茧不是咸鱼：爱上一匹野狗，可你却不爱遛狗，这让我感到绝望……@庄天才",
      "web_url": "",
      "number": 0,
      "type": "3"
    },
    {
      "item_id": "857",
      "title": "每辆车下面都躲着一只猫",
      "introduction": "它们和我们大部分人类一样聪明，一旦被外面的世界吓到过，就喜欢找个角落缩在一隅，不争不抢，不声不响。晴天时小心翼翼地晒苍白的皮，雨天时心安理得地舔干净的毛。",
      "author": "王若虚",
      "web_url": "",
      "number": 0,
      "type": "1"
    },
    {
      "item_id": "1471",
      "title": "没有狗在叫",
      "introduction": "孩子们常因为学习不好挨打，理由都是一个，“你们他妈还学不好，你们没爹吗？”",
      "author": "李诞",
      "web_url": "",
      "number": 0,
      "type": "1"
    },
    {
      "item_id": "336",
      "title": "熊猫吃素为什么还这么肥？",
      "author": "知乎用户金晨羽答严小熊：",
      "introduction": "人类和牛羊的消化系统区别在于：人类无法消化纤维素，因此富含纤维素的素食对我们来说是减肥食品，但对于能",
      "web_url": "",
      "number": 0,
      "type": "3"
    },
    {
      "item_id": "1387",
      "title": "你的宠物都做过哪些让你懵逼的事情？",
      "author": "网友答@一个App工作室：",
      "introduction": "@Cherry7x：他吃了我八双鞋！没错是吃！不是咬！八双！\r\n \r\n@姚婷Winter：抱着我的腿",
      "web_url": "",
      "number": 0,
      "type": "3"
    },
    {
      "item_id": "934",
      "title": "猫语症",
      "introduction": "我只是很遗憾，奶奶是我的第一个病人，我却没有想过治好她。",
      "author": "张寒寺",
      "web_url": "",
      "number": 0,
      "type": "1"
    }
  ]
}
```

## 列表项字段解析
|       字段        |       类型        |       含义        |
|-------------------|:-----------------:|:-----------------:|
|       item_id	    |       String	    |       文章id      |
|       title	    |       String	    |                   |
|       author	    |       String	    |                   |
|       introduction|	    String	    |                   |
|       web_url	    |       String	    |                   |
|       number	    |       Integer	    |                   |
|       type	    |       String	    |       1 或 2 或 3 |

+ type == '1'   essay(短篇)类型
+ type == '2'   serial(连载)类型
+ type == '3'   question(问答)类型