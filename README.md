## 声明
以下所有 API 均由 [「ONE · 一个」](http://wufazhuce.com/)提供，[本人](https://github.com/lipeiwei-szu)采取非正常手段获取。获取跟共享的行为或许有侵犯权益的嫌疑。若被告知需停止共享与使用，本人会及时删除此页面与整个项目。
请您了解相关情况，并保证不侵犯[「ONE · 一个」](http://wufazhuce.com/)的利益，并遵守开源协议

## 缘由说明
该文档源自于我之前所做的一个基于[React-Native](https://github.com/facebook/react-native)框架的跨平台APP, 这套程序代码兼容iOS、Android双平台，实现了[「ONE · 一个」](http://www.wandoujia.com/apps/one.hh.oneclient)80%的功能，包含图文、阅读、音乐、电影四大版块的功能，如果想更加详细地了解，请点击[ReactNativeOne](https://github.com/lipeiwei-szu/ReactNativeOne)

## API说明
+ 获取该接口文档的软硬件环境是Mac、Charles抓包软件、Android端「ONE · 一个」V3.5.0版本的APP
+ 「ONE · 一个」的消息以 JSON 格式输出
+ 到目前为止，我开发这个APP所使用到的API HTTP Method 均为 GET

## 模块

### 图文模块
+ [获取首页最新的图文id列表](./picture/pictureIdList.md)
+ [根据id获取图文详细信息](./picture/pictureDetail.md)
+ [根据年月份获取图文详细信息列表](./picture/getPictureListByMonth.md)

### 阅读模块
+ [获取阅读顶部的滚动图片列表](./reading/carousel/carouselList.md)
+ [根据id获取顶部滚动图片点击进去的详细信息](./reading/carousel/carouselDetail.md)
+ [获取首页最新的文章列表](./reading/index/getLatestArticleList.md)
+ [根据年月份获取短篇文章列表](./reading/essay/getEssayListByMonth.md)
+ [根据id获取短篇文章详细信息](./reading/essay/essayDetail.md)
+ [根据年月份获取连载文章列表](./reading/serial/getSerialListByMonth.md)
+ [根据id获取连载文章详细信息](./reading/serial/serialDetail.md)
+ [根据年月份获取问答文章列表](./reading/question/getQuestionListByMonth.md)
+ [根据id获取问答文章详细信息](./reading/question/questionDetail.md)

### 音乐模块
+ [获取首页最新的音乐id列表](./music/musicIdList.md)
+ [根据id获取音乐详细信息](./music/musicDetail.md)
+ [根据年月份获取音乐简略信息列表](./music/getMusicListByMonth.md)
+ [关于如何播放虾米音乐](https://github.com/naoyeye/xiamiRun)

### 电影模块
+ [分页获取电影简略信息列表](./movie/movieList.md)
+ [根据id获取电影详细信息](./movie/movieDetail.md)
+ [根据id获取电影故事信息](./movie/movieStory.md)

## 评论模块
+ [根据类型分页获取评论](./comment/comment.md)