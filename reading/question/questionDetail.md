
# 请求问答文章详细信息

## URL
http://v3.wufazhuce.com:8000/api/question/${id}

## 参数
+ id    ————>     文章id

## 请求示例
+ http://v3.wufazhuce.com:8000/api/question/1511

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
    "question_id": "1511",
    "question_title": "情侣之间如何处理假性亲密的感情？",
    "question_content": "Kira问：我和男朋友恋爱三年了，看似还是很亲密，实际上心里清楚，很多感觉已经变味了，这种时候该怎么办？",
    "answer_title": "@大将军郭 答Kira：",
    "answer_content": "有一位来访者找我咨询，她原本是做销售工作，业绩很好，去年因为怀孕，老公希望她能换一个轻松的工作养胎，她虽然舍不得，但还是调动到了其他部门，现在生完孩子，还是想调回销售岗，因为那才是她擅长并喜欢的工作。她担心老公不同意，就说单位强制调岗，...",
    "question_makettime": "2016-10-27 23:00:00",
    "recommend_flag": "0",
    "charge_edt": "（责任编辑：卫天成 weitiancheng@wufazhuce.com）",
    "last_update_date": "2016-10-28 13:14:29",
    "web_url": "http://m.wufazhuce.com/question/1511",
    "read_num": "67901",
    "guide_word": "其实，爱人耐不住冷落，亲密耗不过沉默。",
    "praisenum": 1797,
    "sharenum": 923,
    "commentnum": 239
  }
}
```

## 列表项字段解析
|       字段        |       类型        |       含义        |
|-------------------|:-----------------:|:-----------------:|
|   question_id	    |       String	    |                   |
|   question_title  |   	String      |	                |
|   question_content|   	String      |	                |
|   answer_title    |   	String	    |                   |
|   answer_content  |   	String	    |                   |
|question_makettime |   	String      |	                |
|   recommend_flag	|       String      |	                |
|   charge_edt	    |       String	    |       责任编辑    |
|   last_update_date|	    String	    |                   |
|   web_url	        |       String	    |                   |
|   read_num        |   	String	    |                   |
|   guide_word	    |       String	    |                   |
|   praisenum	    |       Integer	    |                   |
|   sharenum	    |       Integer	    |                   |
|   commentnum	    |       Integer	    |                   |