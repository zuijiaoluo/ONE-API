
# 请求首页阅读底部的滚动文章列表

## URL
http://v3.wufazhuce.com:8000/api/reading/index

## HTTP请求方式
GET

## 数据返回格式
JSON

##是否需要登录
否

## 返回结果示例
```
{
  res: 0,
  data: {
    essay: [],
    serial: [],
    question: []
  }
}
```

## 数据解析
返回三个列表, 包含了三种类型的文章, 一般每个列表都是十个, 这个接口不必说太多了, 字段跟[essayList](../essay/getEssayListByMonth.md)、[serialList](../serial/getSerialListByMonth.md)、[questionList](../question/getQuestionListByMonth.md)都是一样, 请参考对比一下.