


###微信 iOS SDK `1.7.3`
```
1. 增强稳定性，适配iOS10
2. 修复小于32K的jpg格式缩略图设置失败的问题
```
- [文档][wechat_ios_api]
- [下载地址][wechat_ios_download] 

整理时间 2016.10.4

###微信 Android SDK `3.1.1`
```
暂无
```
- [文档][wechat_android_api]
- [下载地址][wechat_android_download] 

整理时间 2016.10.11

###腾讯 iOS SDK `3.1.0` `2016-05-17`
```
V3.1.0完整包更新了以下内容：
新增功能：
一键加群功能

修正以下功能：
1. 修正 log 文件从 document 目录移到Caches目录；
2. 修正通过h5 登录，分享到手Q提示账号不符合；
3. 修正分享到群部落；
4. 修正sdk添加游戏好友获取好友设置失败；
5. 修复登录webview界面，放大镜穿透的问题；
6. 支持cpu指令集版本由arm7、arm7s、arm64、i386 、x86_64 变更到 armv7、x86_64、arm64
```

- [文档][qq_ios_api]
- [下载地址][qq_ios_download] 
- [版本历史][qq_ios_version]

整理时间 2016.10.4

###腾讯 Android SDK `3.1.0` `2016-05-24`
```
V3.1.0 SDK基础包更新如下内容：
修正以下功能：
1. 解决arm64-v8a架构下，在H5登录页面输入完帐号密码后点击登录时的崩溃问题；
2. 解决因FloatMath在Android 6.0上被去掉而导致使用了FloatMath的TouchView编译不过问题；
3. 解决横屏应用分享时可能接收不到回调和界面异常的问题；
4. 优化安装包大小；
5. 其他bug修复。
```

- [文档][qq_android_api]
- [下载地址][qq_android_download] 

整理时间 2016.10.12

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

###环信IM(V2.0) iOS SDK `2.2.7` `2016-09-08`
```
SDK细节调整:

SDK中检查附件大小，附件大小不恰当时返回错误
群组批量加人时合并了加人请求，避免耗时随着人数增加
改善会话加载消息时的性能
```
- [介绍][easemob_ios]
- [文档][easemob_ios_api]
- [下载地址][easemob_ios_download] 
- [版本历史][easemob_ios_version]

整理时间 2016.10.5

###环信IM(V2.0) Android SDK `2.3.2` `2016-09-06`
```
新功能/改进：

web端和手机端同时登陆时可以同步接收自己在另外一端发送的消息
增加被kill后自启动的概率，需要在mianifests文件中加上以下声明
<service
android:name="com.easemob.chat.EMJobService"
android:permission="android.permission.BIND_JOB_SERVICE"
android:exported="true"
/>        
Bug Fix:

修复没有启动守护进程的bug
```
- [介绍][easemob_android]
- [文档][easemob_android_api]
- [下载地址][easemob_android_download] 
- [版本历史][easemob_android_version]

整理时间 2016.10.12

###有赞 iOS SDK `3.3.0` `2016-10-17`
```
1.优化登录接口容错;
2.优化登出接口;
3.废弃导航栏相关接口.
```
- [介绍][youzan_ios]
- [文档][youzan_ios_api]
- [下载地址][youzan_ios_download] 
- [版本历史][youzan_ios_version]

整理时间 2016.10.11

###有赞 Android SDK `3.0.2` `2016-08-18`
```
1.修改YouzanBrowser整体架构不再注入开发者对client使用过程;
2.支持跳转支付宝App支付;
3.部分bug修复;
4.移除YouzanBridge.
```
- [介绍][youzan_android]
- [文档][youzan_android_api]
- [下载地址][youzan_android_download] 
- [版本历史][youzan_android_version]

整理时间 2016.10.11

###支付宝 iOS SDK `15.2.0` `2016-08-23`
```
1. 增加支付宝支付和授权2.0体系服务；
2. 完全兼容1.0体系，授权和支付接口保持不变；
3. 订单组装问题修复。
```
- [介绍][alipay_ios]
- [文档][alipay_ios_api]
- [下载地址][alipay_ios_download] 
- [版本历史][alipay_ios_version]

整理时间 2016.10.22

###支付宝 Android SDK `15.2.4` `2016-10-11`
```
1. 新增readme.txt；
2. 修复了2.3系统crash的问题。
```
- [介绍][alipay_android]
- [文档][alipay_android_api]
- [下载地址][alipay_android_download] 
- [版本历史][alipay_android_version]

整理时间 2016.10.22



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
















