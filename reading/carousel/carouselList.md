
# 请求阅读顶部的滚动图片列表

## URL
http://v3.wufazhuce.com:8000/api/reading/carousel

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
      "id": "109",
      "title": "宠物是人类最好的暖手器",
      "cover": "http://image.wufazhuce.com/FkZo1hcTnPgGwnnVF1iLWHBBe0Dq",
      "bottom_text": "“水来我在水中等你，火来我在灰烬中等你。”",
      "bgcolor": "#3a2722",
      "pv_url": "http://v3.wufazhuce.com:8000/api/reading/carousel/pv/109"
    },
    {
      "id": "106",
      "title": "不正常人类症候群",
      "cover": "http://image.wufazhuce.com/FkkHaZO6iMT1tF9gtIv4_l7sr8dQ",
      "bottom_text": " 就算时空倒转重新选择，也想要过「不正常」的人生。",
      "bgcolor": "#000000",
      "pv_url": "http://v3.wufazhuce.com:8000/api/reading/carousel/pv/106"
    },
    {
      "id": "107",
      "title": "玩家",
      "cover": "http://image.wufazhuce.com/FnzElQ_wfubRltil-Ij4Isu3eMRZ",
      "bottom_text": "网络时代，根本就没有什么是真正的秘密。",
      "bgcolor": "#212f2f",
      "pv_url": "http://v3.wufazhuce.com:8000/api/reading/carousel/pv/107"
    },
    {
      "id": "108",
      "title": "那女孩对我说，说我是一个小偷",
      "cover": "http://image.wufazhuce.com/Fq9bcERG1d5NahszZTeOyfV5HvfO",
      "bottom_text": "“我只不过是一个女孩，站在心爱的男孩的面前，需要他爱我的一个女孩。”",
      "bgcolor": "#0d223d",
      "pv_url": "http://v3.wufazhuce.com:8000/api/reading/carousel/pv/108"
    },
    {
      "id": "105",
      "title": "要做你自己，因为没人想做你",
      "cover": "http://image.wufazhuce.com/FgA7ELCwoaD7NBJcpyKsF_jxdIS9",
      "bottom_text": "“我要有能做我自己的自由， 和敢做我自己的胆量。”",
      "bgcolor": "#fc553b",
      "pv_url": "http://v3.wufazhuce.com:8000/api/reading/carousel/pv/105"
    },
    {
      "id": "104",
      "title": "我的梦想就是成为你的梦想",
      "cover": "http://image.wufazhuce.com/FtKBspBPdeI80gd-KZHX3a1YYlVx",
      "bottom_text": "梦想还是要有的，万一实现了呢。",
      "bgcolor": "#1b4692",
      "pv_url": "http://v3.wufazhuce.com:8000/api/reading/carousel/pv/104"
    },
    {
      "id": "97",
      "title": "毛利文章精选",
      "cover": "http://image.wufazhuce.com/FuMLnn4LaZq25fR5St3QQX4gfPYI",
      "bottom_text": "失败者才不管别的有多重要。任性一回，不然一辈子都憋屈。",
      "bgcolor": "#2e2e2e",
      "pv_url": "http://v3.wufazhuce.com:8000/api/reading/carousel/pv/97"
    },
    {
      "id": "100",
      "title": "你看上去好讨厌哦",
      "cover": "http://image.wufazhuce.com/Fs_pmdYjetPtBgVUup5jqc57Wh0g",
      "bottom_text": "无可避免的，我们最终成了我们讨厌的人。",
      "bgcolor": "#727171",
      "pv_url": "http://v3.wufazhuce.com:8000/api/reading/carousel/pv/100"
    },
    {
      "id": "93",
      "title": "when can I see u again",
      "cover": "http://image.wufazhuce.com/Ft-qdMcLzjIWYp0ez_gaF-East7p",
      "bottom_text": "“千万别对自己残忍，快乐的时候就去快乐，今朝有酒今朝醉，别浪费了好时光去思考未来何时伤心掉眼泪。”",
      "bgcolor": "#2f2f37",
      "pv_url": "http://139.129.116.86:8000/api/reading/carousel/pv/93"
    }
  ]
}
```

## 列表项字段解析
|       字段        |       类型        |       含义        |
|-------------------|:-----------------:|:-----------------:|
|       id	        |       String	    |                   |
|       title	    |       String	    |                   |
|       cover	    |       String      |                   |
|       bottom_text	|       String	    |                   |
|       bgcolor	    |       String	    |                   |
|       pv_url	    |       String      |                   |