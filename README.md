# CreateShortVideo
python实现实时自动生成短视频

基本思路
通过公开的API以及爬虫爬取网络无版权图片，视频，音频到本地，
结合图像识别，图像语义分割，NLP等深度学习技术,
实现对不同的图片，视频场景，追加文案，并设置相应的背景音频，
并自动发布到短视频网站。


项目目前不够完善，文档等会持续优化

ver:2020/11/22

	1.追加图片自动下载模块

	2.追加音频下载模块

	3.追加静态视频py文件

	4.文案搜索API

ver:2020/11/24 

    追加文本情感分析 
    使用百度情绪分析API后期搭建nlp检测模型
    追加特效 淡入淡出 

ver:2020/11/25 
    
    修改视频中文显示bug 

    追加中文短句翻译为英文

    追加动态视频剪辑     
ver:2020/12/01
    追加诗词API
    优化文件夹结构
参考并致谢: 
https://github.com/xingag/tools_python.git  
https://github.com/CcphAmy/NetEaseCloudMusic-nonmembership-list-download  
https://api.uixsj.cn/hitokoto/get?type=hitokoto&code=json  
