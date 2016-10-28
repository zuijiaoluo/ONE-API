
# 根据年月份请求音乐列表

## URL
http://v3.wufazhuce.com:8000/api/music/bymonth/${year}-${month}

## 参数
+ year    ————>     年份
+ month   ————>     月份
+ 注意: 音乐是2016年1月才开始有的, 所有如果请求年月份小于2016年1月的话, 将返回一个空列表

## 请求示例
+ http://v3.wufazhuce.com:8000/api/music/bymonth/2016-10

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
      "id": "1086",
      "title": "成都",
      "cover": "http://image.wufazhuce.com/FqoPbaj1J-ndd2M6crvp1sgfS_62",
      "platform": "2",
      "music_id": "http://music.wufazhuce.com/lsObPs5v_KBby0Oe5Uq_eUoWYOYt",
      "author": {
        "user_id": "4814909",
        "user_name": "赵雷",
        "web_url": "http://image.wufazhuce.com/FqSbe5II8bmsJmCUweOTo9bk2vDC",
        "desc": "民谣歌手"
      }
    },
    {
      "id": "1085",
      "title": "知名不具",
      "cover": "http://image.wufazhuce.com/FiC2P5Wslqx9Q736BCf-oTZa02Bn",
      "platform": "2",
      "music_id": "http://music.wufazhuce.com/lsBGUVmioGen5mueIlrNb_jILgov",
      "author": {
        "user_id": "4814939",
        "user_name": "阿肆",
        "web_url": "http://image.wufazhuce.com/FsF1NYlsChpQdPS0b7QNRda_-wtr",
        "desc": "阿肆，独立音乐人、写作者。"
      }
    },
    {
      "id": "1081",
      "title": "光を映す影",
      "cover": "http://image.wufazhuce.com/FvErL--Rho1Cb6UaVxHHURv8kGIf",
      "platform": "1",
      "music_id": "1769152804",
      "author": {
        "user_id": "6790597",
        "user_name": "world's end girlfriend",
        "web_url": "http://image.wufazhuce.com/Fs8yxF2rfuuMoxOw4dVRpbsEmCUk",
        "desc": "日本后摇乐队"
      }
    },
    {
      "id": "1078",
      "title": "OK",
      "cover": "http://image.wufazhuce.com/FvBFSuNg-yIOxPUuOBQzBldZlPX_",
      "platform": "1",
      "music_id": "1769172107",
      "author": {
        "user_id": "7397973",
        "user_name": "Julie Peel",
        "web_url": "http://image.wufazhuce.com/FoANC5KVjUfwEI67mr5wPCVBLD7f",
        "desc": "法国歌手"
      }
    },
    {
      "id": "1082",
      "title": "A Thousand Kisses Deep",
      "cover": "http://image.wufazhuce.com/FhuQXh8DiSjlRreY4AD6AFREvTdS",
      "platform": "1",
      "music_id": "1014583",
      "author": {
        "user_id": "7404853",
        "user_name": "Leonard Cohen",
        "web_url": "http://image.wufazhuce.com/Fq3WyGonL2C76koG3q3IBcqjc2Rf",
        "desc": "加拿大音乐人、作家、演员"
      }
    },
    {
      "id": "1083",
      "title": "念念不忘",
      "cover": "http://image.wufazhuce.com/Fg5B-uz4n19_3dR-UMD06ywmXg45",
      "platform": "1",
      "music_id": "1773505815",
      "author": {
        "user_id": "7301409",
        "user_name": "麦浚龙",
        "web_url": "http://image.wufazhuce.com/FhIG92IaDhfILVWP0AKDg5kQtco9",
        "desc": "香港歌手"
      }
    },
    {
      "id": "1080",
      "title": "Duet",
      "cover": "http://image.wufazhuce.com/FtU90jksFzTFmjDD8HZlZme-1VP5",
      "platform": "2",
      "music_id": "http://music.wufazhuce.com/lpqLtknIFju11GbznoXxwzHaTLlM",
      "author": {
        "user_id": "7401911",
        "user_name": "Rachael Yamagata",
        "web_url": "http://image.wufazhuce.com/FpxBfbIYVBIwGtxiDHMJFYEmSZIF",
        "desc": "美国唱作人"
      }
    },
    {
      "id": "1079",
      "title": "不如不见",
      "cover": "http://image.wufazhuce.com/FgvbbNP6tWpiLoQ1X_1tYTrMv6ft",
      "platform": "1",
      "music_id": "384554",
      "author": {
        "user_id": "6143263",
        "user_name": "陈奕迅",
        "web_url": "http://image.wufazhuce.com/FsIczsxqXczFMw_IUISKz4y9n8uA",
        "desc": "香港著名歌手，演员"
      }
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
|       platform	|       String	    |       1 或 2      |
|       music_id	|       String	    |                   |
|       author	    |       Object      |                   |

## [关于platform跟music_id字段](./musicDetail.md#关于platform跟music_id字段)
