
# 请求首页中展示的图文id列表

## URL
http://v3.wufazhuce.com:8000/api/hp/idlist/0

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
    "1507",
    "1508",
    "1509",
    "1505",
    "1506",
    "1504",
    "1497",
    "1503",
    "1498",
    "1502"
  ]
}
```

## 列表项字段解析
注意: 已经Charles软件查询, 拿到的id list类型都是string, 而不是number, 所以写javascript的时候要小心, 千万不要跟number直接用强等于(===)去比较