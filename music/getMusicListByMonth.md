
# 根据年月份请求音乐列表

## URL
http://v3.wufazhuce.com:8000/api/music/bymonth/${year}-${month}

## 参数
+ year    ————>     年份
+ month   ————>     月份
+ 注意: 音乐是2016年1月才开始有的, 所有如果请求年月份小于2016年1月的话, 将返回一个空列表

## 请求示范
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
    },
    {
      "id": "1077",
      "title": "十万嬉皮",
      "cover": "http://image.wufazhuce.com/Fry8Ubk-q1agIyVb2tpZMUbN4tCu",
      "platform": "1",
      "music_id": "1769863610",
      "author": {
        "user_id": "5682778",
        "user_name": "万能青年旅店",
        "web_url": "http://image.wufazhuce.com/FiGPHOksQqe6fF__styiTmX21Ufj",
        "desc": "知名摇滚乐队"
      }
    },
    {
      "id": "1076",
      "title": "这个世界会好吗(2015动静版)",
      "cover": "http://image.wufazhuce.com/FvxdE3SwewSdW7Bu8nxTGxolB6jS",
      "platform": "2",
      "music_id": "http://music.wufazhuce.com/lmaMBNwJadpH8UbtE7FMYdkTRwsC",
      "author": {
        "user_id": "4814789",
        "user_name": "李志",
        "web_url": "http://image.wufazhuce.com/Fj4nGvdv40grnkuAPzD6nkiHeWIR",
        "desc": "独立音乐人"
      }
    },
    {
      "id": "1072",
      "title": "喜帖街",
      "cover": "http://image.wufazhuce.com/FuFtyGaqrEDhR_P0JDQemw53UljV",
      "platform": "1",
      "music_id": "2138265",
      "author": {
        "user_id": "6985795",
        "user_name": "谢安琪",
        "web_url": "http://image.wufazhuce.com/FlvIH06Bkx2zfuC9qzdIiftfJjpX",
        "desc": "香港歌手，演员"
      }
    },
    {
      "id": "1075",
      "title": "Better Together",
      "cover": "http://image.wufazhuce.com/Ft1lFkMQn-TL_jiYP1MhQqovzI9r",
      "platform": "1",
      "music_id": "2080363",
      "author": {
        "user_id": "6257704",
        "user_name": "Jack Johnson",
        "web_url": "http://image.wufazhuce.com/Fm786xsDJp-EAdKlUb-9R9CKlEfN",
        "desc": "美国冲浪手，民谣歌手，导演"
      }
    },
    {
      "id": "1066",
      "title": "追逐太阳的人",
      "cover": "http://image.wufazhuce.com/FlrJJJp3nEUSi4TPPojBB1wRZTkk",
      "platform": "1",
      "music_id": "1776408557",
      "author": {
        "user_id": "5850168",
        "user_name": "冬子",
        "web_url": "http://image.wufazhuce.com/FkoTrAHYbjTtXuoerK_RWD2e0cy_",
        "desc": "民谣音乐人"
      }
    },
    {
      "id": "1069",
      "title": "不要告别",
      "cover": "http://image.wufazhuce.com/FsIIlPWpv6lW0IwTMOwAyoZIbBcJ",
      "platform": "1",
      "music_id": "379175",
      "author": {
        "user_id": "6887398",
        "user_name": "杨乃文",
        "web_url": "http://image.wufazhuce.com/Fq-uadlU2oYclijbUz38pF2L85uF",
        "desc": "台湾歌手"
      }
    },
    {
      "id": "1074",
      "title": "Blowin In The Wind",
      "cover": "http://image.wufazhuce.com/FvgTIlo1mAMeWeoCk8w0ZhvjVbfW",
      "platform": "1",
      "music_id": "1771388737",
      "author": {
        "user_id": "6109670",
        "user_name": "Bob Dylan",
        "web_url": "http://image.wufazhuce.com/FgU8zKcMNDfw86dxUEzcKrdVjBsX",
        "desc": "美国民谣、摇滚代表人物"
      }
    },
    {
      "id": "1071",
      "title": "Cave",
      "cover": "http://image.wufazhuce.com/FtZEcmyGmSoaqlB5nz6tWK_lc-JH",
      "platform": "1",
      "music_id": "1776416000",
      "author": {
        "user_id": "7372099",
        "user_name": "Future Orients",
        "web_url": "http://image.wufazhuce.com/Fml7Ky3ioeLgHHdxibSMVrGT4Vhp",
        "desc": "独立摇滚乐队"
      }
    },
    {
      "id": "1073",
      "title": "又见炊烟",
      "cover": "http://image.wufazhuce.com/FlZj-253junFnlNckUWIW0-1P8uz",
      "platform": "1",
      "music_id": "98382",
      "author": {
        "user_id": "7375645",
        "user_name": "邓丽君",
        "web_url": "http://image.wufazhuce.com/FsbX-5Xqh-3XxqH1L_Z228YyN2p5",
        "desc": "华语天后"
      }
    },
    {
      "id": "1070",
      "title": "牡丹亭外",
      "cover": "http://image.wufazhuce.com/FpP1PWp6aO7CusvNqoTkLYm6Qiiv",
      "platform": "1",
      "music_id": "3468491",
      "author": {
        "user_id": "4814942",
        "user_name": "陈升",
        "web_url": "http://image.wufazhuce.com/FpLNh5paOlhRI_rsj_v21InBCF7P",
        "desc": "华语唱作人"
      }
    },
    {
      "id": "1068",
      "title": "电台情歌",
      "cover": "http://image.wufazhuce.com/FgGe62lQIiTteO5kZjJlRNx8tKN2",
      "platform": "1",
      "music_id": "382560",
      "author": {
        "user_id": "6951736",
        "user_name": "莫文蔚",
        "web_url": "http://image.wufazhuce.com/FoHW13Dup6n1gVJZ2PB4V8SKUUq9",
        "desc": "香港歌手、演员"
      }
    },
    {
      "id": "1065",
      "title": "Birthday Resistance",
      "cover": "http://image.wufazhuce.com/FoXaDoyp_19rh1FNOFIvWdHyt6ow",
      "platform": "1",
      "music_id": "3320667",
      "author": {
        "user_id": "6790597",
        "user_name": "world's end girlfriend",
        "web_url": "http://image.wufazhuce.com/Fs8yxF2rfuuMoxOw4dVRpbsEmCUk",
        "desc": "日本后摇乐队"
      }
    },
    {
      "id": "1062",
      "title": "浪费",
      "cover": "http://image.wufazhuce.com/FhEXRqBrcVbely6P-TuDNvmTzPtP",
      "platform": "1",
      "music_id": "1771093941",
      "author": {
        "user_id": "6144260",
        "user_name": "林宥嘉",
        "web_url": "http://image.wufazhuce.com/FlQyxQX7RdnZRsqVAhH5qgV6vXo6",
        "desc": "台湾歌手"
      }
    },
    {
      "id": "514",
      "title": "守门员",
      "cover": "http://image.wufazhuce.com/FmdUmY20bk_2_3x0d78MJH5L_i6y",
      "platform": "2",
      "music_id": "http://music.wufazhuce.com/lvTtbE7Kdl3W82sACxU5PIQmnAqr",
      "author": {
        "user_id": "5816551",
        "user_name": "Chinese Football",
        "web_url": "http://image.wufazhuce.com/FhOKuHjySGa7D9Fm-nPUkmcAT7Of",
        "desc": "摇滚乐队"
      }
    },
    {
      "id": "1056",
      "title": "和那些人一样",
      "cover": "http://image.wufazhuce.com/FhxmITRxNwvMK5wmZVlW2YyEBG3f",
      "platform": "1",
      "music_id": "1774020885",
      "author": {
        "user_id": "5571827",
        "user_name": "声音玩具",
        "web_url": "http://image.wufazhuce.com/FiUlXZqcRwFuFBwwTz6eVOiy4v20",
        "desc": "摇滚乐队"
      }
    },
    {
      "id": "1064",
      "title": "梦中人",
      "cover": "http://image.wufazhuce.com/Fpn0hSna1DGbnsXiXHkyfO6h2GO9",
      "platform": "1",
      "music_id": "147228",
      "author": {
        "user_id": "6152900",
        "user_name": "王菲",
        "web_url": "http://image.wufazhuce.com/Fs5rePuLUatcWX-3AWbZSEUn5Kmh",
        "desc": "歌手，演员"
      }
    },
    {
      "id": "1058",
      "title": "Bad Blood",
      "cover": "http://image.wufazhuce.com/FpG63qPV3v4Vl7aCmSbsrOb8wqiK",
      "platform": "2",
      "music_id": "http://music.wufazhuce.com/lhzaye2_i0ojHYvb9G-HSo-1s2Oa",
      "author": {
        "user_id": "6234752",
        "user_name": "Elenore",
        "web_url": "http://image.wufazhuce.com/FlJ_n8JBYpwJniNn44T1obAJaxc2",
        "desc": "摇滚乐队"
      }
    },
    {
      "id": "1061",
      "title": "十面埋伏",
      "cover": "http://image.wufazhuce.com/FqBLsgW7Ao7DAiaIJMTrHviw3DjM",
      "platform": "1",
      "music_id": "1770763647",
      "author": {
        "user_id": "6143263",
        "user_name": "陈奕迅",
        "web_url": "http://image.wufazhuce.com/FsIczsxqXczFMw_IUISKz4y9n8uA",
        "desc": "香港著名歌手，演员"
      }
    },
    {
      "id": "1063",
      "title": "请你不要睡好吗？",
      "cover": "http://image.wufazhuce.com/FkSgnC5DV0fKhRzU0bEyVSjco4xv",
      "platform": "1",
      "music_id": "173406",
      "author": {
        "user_id": "5524692",
        "user_name": "at17",
        "web_url": "http://image.wufazhuce.com/FjfbidYeEmJPYNXDZ6UegAjp5QBH",
        "desc": "香港组合"
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

## [关于platform跟music_id字段](./musicDetail.md)
