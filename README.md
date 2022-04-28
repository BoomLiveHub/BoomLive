# BoomLive
BoomLive企业版目前使用BoomLive_overseasTest.plist,
1.release中上传新版本ipa后修改plist中对应tag，注意应用的名字保持一致
2将BoomLive_overseasTest.plist中software-package修改为对应tag，image路径不用改
3.将raw模式外链提交后台itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/BoomLiveHub/BoomLive/master/BoomLive_overseasTest.plist
4.外链可在浏览器上安装，需要梯子，raw.githubusercontent.com国内需要连代理访问，因此决定plist放在自己服务器上
5.itms-services://?action=download-manifest&url=https://live.halocherry.com/html/iosDownload/BoomLive.plist目前使用的最新的在贺磊那里放着
