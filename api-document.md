
###微信 iOS SDK `1.7.3`
```
1. 增强稳定性，适配iOS10
2. 修复小于32K的jpg格式缩略图设置失败的问题
```
- [文档][wechat_ios_api]
- [下载地址][wechat_ios_download] 
- [版本历史][wechat_ios_version]

整理时间 2016.10.4

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

###微博 iOS SDK
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

###环信IM iOS SDK `V2.2.7` `2016-09-08`
```
SDK细节调整:

SDK中检查附件大小，附件大小不恰当时返回错误
群组批量加人时合并了加人请求，避免耗时随着人数增加
改善会话加载消息时的性能
```
- [文档][easemob_ios_api]
- [下载地址][easemob_ios_download] 
- [版本历史][easemob_ios_version]

整理时间 2016.10.5





[wechat_ios_api]: https://open.weixin.qq.com/cgi-bin/showdocument?action=dir_list&t=resource/res_list&verify=1&id=1417694084&token=&lang=zh_CN
[wechat_ios_download]: https://open.weixin.qq.com/cgi-bin/showdocument?action=dir_list&t=resource/res_list&verify=1&id=open1419319164&token=&lang=zh_CN
[wechat_ios_version]: https://github.com/github-xiaogang/ApiDocument/blob/master/wechat/ios/version.txt


[qq_ios_api]: http://wiki.open.qq.com/wiki/IOS_API%E8%B0%83%E7%94%A8%E8%AF%B4%E6%98%8E
[qq_ios_download]: http://wiki.open.qq.com/wiki/mobile/SDK%E4%B8%8B%E8%BD%BD
[qq_ios_version]: http://wiki.open.qq.com/wiki/IOS_API%E8%B0%83%E7%94%A8%E8%AF%B4%E6%98%8E

[weibo_ios_api]: http://open.weibo.com/wiki/IOS_SDK
[weibo_ios_download]: https://github.com/sinaweibosdk/weibo_ios_sdk
[weibo_ios_version]: https://github.com/sinaweibosdk/weibo_ios_sdk

[easemob_ios_api]: http://docs.easemob.com/start/300iosclientintegration/10prepareforsdkimport
[easemob_ios_download]: http://www.easemob.com/download/im
[easemob_ios_version]: http://docs.easemob.com/start/300iosclientintegration/110release_note


















