# BoomLive
BoomLive企业版目前使用BoomLive_overseasTest.plist,
1.release中上传新版本ipa后修改plist中对应tag
2将BoomLive_overseasTest.plist中software-package修改为对应tag，image路径不用改
3.将raw模式外链提交后台itms-services:///?action=download-manifest&url=https://raw.githubusercontent.com/BoomLiveHub/BoomLive/master/BoomLive_overseasTest.plist
