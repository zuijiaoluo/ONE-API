
# 请求短篇文章详细信息

## URL
http://v3.wufazhuce.com:8000/api/essay/${id}

## 参数
+ id    ————>     文章id

## 请求示例
+ http://v3.wufazhuce.com:8000/api/essay/1571

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
    "content_id": "1571",
    "hp_title": "所有的乡愁都是因为馋",
    "sub_title": "",
    "hp_author": "林壁炫",
    "auth_it": "文坛小可爱，华籍美人，翘臀大厨。公众号：wochan321",
    "hp_author_introduce": "（责任编辑：郭佳杰 guojiajie@wufazhuce.com）",
    "hp_content": "人生有味，食之八九。有说舌头比脑袋忠贞，反正在荣华街，哪个远游的人回来，都要先去花记大排档饱餐一顿，吃招牌卤水糕烧番薯，吃生猛海货新鲜时蔬，味道是寻常味，也是人在他乡朝思暮想，一定要吃到肚胀人呆，一颗心才算真正归来。<br>\r\n<br>\r\n花记是荣华的味觉图腾，无人去计较它其实是舶来。数十年前老板一家迁来，在花神庙边盘了店面升起炉火，起初没...",
    "hp_makettime": "2016-10-27 23:00:00",
    "wb_name": "",
    "wb_img_url": "",
    "last_update_date": "2016-10-27 22:58:30",
    "web_url": "http://m.wufazhuce.com/article/1571",
    "guide_word": "这就是我不喜欢小地方的原因，一点恩怨要计较一辈子。大都市多好，人和人没有恩仇，只求利益。",
    "audio": "http://music.wufazhuce.com/lpoqn8ZrcPJvPkmkuI53S-9Q355Z",
    "author": [
      {
        "user_id": "7405600",
        "user_name": "林壁炫",
        "web_url": "http://image.wufazhuce.com/FiZhR_TblAfNhMBbHJ3GxEz9lnEp",
        "desc": "文坛小可爱，华籍美人，翘臀大厨。公众号：wochan321",
        "wb_name": "@林壁炫。"
      }
    ],
    "praisenum": 1634,
    "sharenum": 521,
    "commentnum": 251
  }
}
```

## 列表项字段解析
|       字段        |       类型        |       含义        |
|-------------------|:-----------------:|:-----------------:|
|   content_id      |	    String      |	                |
|   hp_title        |	    String      |                   |
|   sub_title	    |       String	    |                   |
|   hp_author	    |       String	    |                   |
|   auth_it         |	    String      |                   |
|hp_author_introduce|	    String	    |   编辑人员信息    |
|   hp_content	    |       String	    |   文章内容        |
|   hp_makettime    |   	String      |                   |
|   wb_name	        |       String	    |                   |
|   wb_img_url	    |       String      |                   |
|   last_update_date|	    String      |	                |
|   web_url	        |       String	    |                   |
|   guide_word	    |       String      |                   |
|   audio	        |       String      |   音频文件地址    |
|   author      	|       Array	    |**注意类型是array**|
|   praisenum       |	    Integer 	|                   |
|   sharenum        |	    Integer	    |                   |
|   commentnum      |   	Integer	    |                   |