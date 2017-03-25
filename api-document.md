


###微信 iOS SDK `1.7.6`
```
1. 提高稳定性
2 修复mta崩溃
3  新增接口支持开发者关闭mta数据统计上报
```
- [文档][wechat_ios_api]
- [下载地址][wechat_ios_download] 

整理时间 2017.3.25

###微信 Android SDK `4.0.2`
```
暂无
```
- [文档][wechat_android_api]
- [下载地址][wechat_android_download] 

整理时间 2017.3.25

###腾讯 iOS SDK `3.1.3` `2016-12-06`
```
V3.1.3完整包更新了以下内容：
1、内部网络接口全面支持https
2、修复和第三方hook消息转发可能Crash的问题
3、支持cpu指令集补充对模拟器的支持
```

- [文档][qq_ios_api]
- [下载地址][qq_ios_download] 
- [版本历史][qq_ios_version]

整理时间 2017.3.25

###腾讯 Android SDK `3.1.3` `2016-12-06`
```
V3.1.3基础包更新了以下内容：
1、内部网络接口全面支持https
2、修复和第三方hook消息转发可能Crash的问题
3、支持cpu指令集补充对模拟器的支持
```

- [文档][qq_android_api]
- [下载地址][qq_android_download] 

整理时间 2017.3.25

###微博 iOS SDK `3.1.4` `2016-07-12`
```
由于iOS10的发布，原有ATS设置在iOS10上会出现https网络访问限制的问题，为了确保好的应用体验，我们需要采取如下措施：

<key>sina.com.cn</key>
<dict>
<key>NSIncludesSubdomains</key>
<true/>
<key>NSThirdPartyExceptionAllowsInsecureHTTPLoads</key>
<true/>
<key>NSExceptionMinimumTLSVersion</key>
<string>TLSv1.0</string>
<key>NSThirdPartyExceptionRequiresForwardSecrecy</key>
<false/>
</dict>

需要在每一个域名下添加NSExceptionMinimumTLSVersion这样的key，值的部分为TLSv1.0
```
- [文档][weibo_ios_api]
- [下载地址][weibo_ios_download] 
- [版本历史][weibo_ios_version]

整理时间 2016.10.5

###微博 Android SDK `3.1.1` `2015-06-16`
```
优化网页授权
优化网页分享
增加社会化评论组件
增加社会化关注组件
增加微博支付功能接口
增加微博短信授权方式
```
- [文档][weibo_android_api]
- [下载地址][weibo_android_download] 
- [版本历史][weibo_android_version]

整理时间 2016.10.12

###环信IM(V2.0) iOS SDK `2.3.1` `2017-02-17`
```
新功能/改进:

修改HttpsOnly参数默认值,默认设置为NO(由于苹果强制ATS政策延缓, 所以SDK默认关闭httpsOnly)
[[EaseMob sharedInstance].chatManager setIsUseHttpsOnly:YES];//设置httpsonly,YES开启,NO关闭
增加获取日志压缩文件路径接口(具体上传日志方式可由开发者决定, Demo是通过邮件的形式上报日志)
优化群组过多时重连卡顿问题
修复离线已读回执有时丢失问题
修复SDK收到特殊消息闪退问题
```
- [介绍][easemob_ios]
- [文档][easemob_ios_api]
- [下载地址][easemob_ios_download] 
- [版本历史][easemob_ios_version]

整理时间 2017.3.25

###环信IM(V2.0) Android SDK `2.3.4` `2017-02-10`
```
新功能/改进：

修复R1版本使用华为推送报错的问题
增加修改群描述方法EMGroupManager::changeGroupDescription()
EMChat::setServerAddress()方法支持设置https地址
EMContactManager增加addContactListener(EMContactListener contactListener)方法，方便app在不同类里监听好友变动
Bug Fix:

修复REST短时间内发多条相同内容的消息，客户端只显示一条的bug
修复搜索有时候返回结果不对的bug
修复上个版本出现的个别情况下堆栈溢出的问题
```
- [介绍][easemob_android]
- [文档][easemob_android_api]
- [下载地址][easemob_android_download] 
- [版本历史][easemob_android_version]

整理时间 2017.3.25

###有赞 iOS SDK `4.0.4` `2017-02-18`
```
1.适配有赞新域名
```
- [介绍][youzan_ios]
- [文档][youzan_ios_api]
- [下载地址][youzan_ios_download] 
- [版本历史][youzan_ios_version]

整理时间 2017.3.25

###有赞 Android SDK `3.1.0` `2017-02-18`
```
1.适配有赞域名切换;

2.优化以及累积bug修复;
```
- [介绍][youzan_android]
- [文档][youzan_android_api]
- [下载地址][youzan_android_download] 
- [版本历史][youzan_android_version]

整理时间 2017.3.25

###支付宝 iOS SDK `15.2.1` `2016-12-24`
```
更新点：
1. webview屏蔽alipayjsbridge的调用。
```
- [介绍][alipay_ios]
- [文档][alipay_ios_api]
- [下载地址][alipay_ios_download] 
- [版本历史][alipay_ios_version]

整理时间 2017.3.25

###支付宝 Android SDK `15.3.3` `2016.12.22`
```
更新点：
1. 体验优化。
```
- [介绍][alipay_android]
- [文档][alipay_android_api]
- [下载地址][alipay_android_download] 
- [版本历史][alipay_android_version]

整理时间 2017.3.25



[wechat_ios_api]: https://open.weixin.qq.com/cgi-bin/showdocument?action=dir_list&t=resource/res_list&verify=1&id=1417694084&token=&lang=zh_CN
[wechat_ios_download]: https://open.weixin.qq.com/cgi-bin/showdocument?action=dir_list&t=resource/res_list&verify=1&id=open1419319164&token=&lang=zh_CN
[wechat_ios_version]: https://open.weixin.qq.com/cgi-bin/showdocument?action=dir_list&t=resource/res_list&verify=1&id=1417694084&token=&lang=zh_CN

[wechat_android_api]: https://open.weixin.qq.com/cgi-bin/showdocument?action=dir_list&t=resource/res_list&verify=1&id=1417751808&token=&lang=zh_CN
[wechat_android_download]: https://open.weixin.qq.com/cgi-bin/showdocument?action=dir_list&t=resource/res_list&verify=1&id=open1419319167&token=&lang=zh_CN
[wechat_android_version]: https://open.weixin.qq.com/cgi-bin/showdocument?action=dir_list&t=resource/res_list&verify=1&id=1417751808&token=&lang=zh_CN

[qq_ios_api]: http://wiki.open.qq.com/wiki/IOS_API%E8%B0%83%E7%94%A8%E8%AF%B4%E6%98%8E
[qq_ios_download]: http://wiki.open.qq.com/wiki/mobile/SDK%E4%B8%8B%E8%BD%BD
[qq_ios_version]: http://wiki.open.qq.com/wiki/IOS_API%E8%B0%83%E7%94%A8%E8%AF%B4%E6%98%8E

[qq_android_api]: http://wiki.open.qq.com/wiki/%E5%88%9B%E5%BB%BA%E5%B9%B6%E9%85%8D%E7%BD%AE%E5%B7%A5%E7%A8%8B
[qq_android_download]: http://wiki.open.qq.com/wiki/mobile/SDK%E4%B8%8B%E8%BD%BD
[qq_android_version]: http://wiki.open.qq.com/wiki/%E5%88%9B%E5%BB%BA%E5%B9%B6%E9%85%8D%E7%BD%AE%E5%B7%A5%E7%A8%8B

[weibo_ios_api]: http://open.weibo.com/wiki/IOS_SDK
[weibo_ios_download]: https://github.com/sinaweibosdk/weibo_ios_sdk
[weibo_ios_version]: https://github.com/sinaweibosdk/weibo_ios_sdk

[weibo_android_api]: http://open.weibo.com/wiki/Android_SDK%E8%AF%B4%E6%98%8E%E6%96%87%E6%A1%A3
[weibo_android_download]: https://github.com/sinaweibosdk/weibo_android_sdk
[weibo_android_version]: https://github.com/sinaweibosdk/weibo_android_sdk

[easemob_ios]: http://docs.easemob.com/start/start
[easemob_ios_api]: http://docs.easemob.com/start/300iosclientintegration/10prepareforsdkimport
[easemob_ios_download]: http://www.easemob.com/download/im
[easemob_ios_version]: http://docs.easemob.com/start/300iosclientintegration/110release_note

[easemob_android]: http://docs.easemob.com/start/start
[easemob_android_api]: http://docs.easemob.com/start/200androidcleintintegration/10androidsdkimport
[easemob_android_download]: http://www.easemob.com/download/im
[easemob_android_version]: http://docs.easemob.com/start/200androidcleintintegration/160androidreleasenote

[youzan_ios]: http://open.youzan.com/sdk/doc#415
[youzan_ios_api]: http://open.youzan.com/sdk/doc#20
[youzan_ios_download]: http://open.youzan.com/sdk/doc#417
[youzan_ios_version]: http://open.youzan.com/sdk/doc#421

[youzan_android]: http://open.youzan.com/sdk/doc#415
[youzan_android_api]: http://open.youzan.com/sdk/doc#30
[youzan_android_download]: http://open.youzan.com/sdk/doc#417
[youzan_android_version]: http://open.youzan.com/sdk/doc#422

[alipay_ios]: https://doc.open.alipay.com/docs/doc.htm?spm=a219a.7629140.0.0.20pcDR&treeId=193&articleId=105051&docType=1
[alipay_ios_api]: https://doc.open.alipay.com/docs/doc.htm?spm=a219a.7629140.0.0.oIB0l5&treeId=193&articleId=105295&docType=1
[alipay_ios_download]: https://doc.open.alipay.com/doc2/detail.htm?treeId=54&articleId=104509&docType=1
[alipay_ios_version]: https://doc.open.alipay.com/doc2/detail.htm?treeId=54&articleId=104509&docType=1

[alipay_android]: https://doc.open.alipay.com/docs/doc.htm?spm=a219a.7629140.0.0.20pcDR&treeId=193&articleId=105051&docType=1
[alipay_android_api]: https://doc.open.alipay.com/docs/doc.htm?spm=a219a.7629140.0.0.3SIiTz&treeId=193&articleId=105296&docType=1
[alipay_android_download]: https://doc.open.alipay.com/doc2/detail.htm?treeId=54&articleId=104509&docType=1
[alipay_android_version]: https://doc.open.alipay.com/doc2/detail.htm?treeId=54&articleId=104509&docType=1
















