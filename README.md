# 目前为测试版本，不保证翻译质量

<img src="https://img.shields.io/badge/-building-green">

# [下载地址](https://aga-text-zh.pages.dev/translater-Chinese-ver0.10.zip)
![USE](https://user-images.githubusercontent.com/65057243/113544219-76b7b880-961a-11eb-8f15-58b779a4e94b.png)
# 文件放在游戏目录下，然后运行游戏即可 如出现字体缺少，请按ALT+F

# 点击  点我更新字库.bat 自动安装最新字库
![image](https://user-images.githubusercontent.com/65057243/113663655-002fbf00-96dd-11eb-83df-90f2fa82bc7e.png)




#目前使用翻译+字典
## 修改翻译来源（目前使用百度翻译API）（修改完成才可以正常使用） 
### 请修改BepInEx\config\AutoTranslatorConfig.ini
``` shell
[Baidu]
BaiduAppId=
BaiduAppSecret=
DelaySeconds=1
```



## 百度翻译api免费使用，请自行申请https://fanyi-api.baidu.com/       选择 通用翻译api 
#### 注api 1秒钟只能调用1次

BUG反馈请到[问题](https://github.com/AGA-Translation/translater/issues)

# 已知BUG
# 1.角色主界面头顶名字无法正常显示

![image](https://user-images.githubusercontent.com/65057243/113663270-505a5180-96dc-11eb-8780-3943cf76edc5.png)


# 2.部分文字第一次翻译（无字典时）会占用过多区间，这种情况在缓存一次后恢复正常

![ME D_C}387Q7Q10@$~E8_PY](https://user-images.githubusercontent.com/65057243/113663282-56e8c900-96dc-11eb-909d-83797bd97604.png)

# 次要问题
## 由于游戏字体不支持简体中文，翻译机将才用系统默认字体
## 因为技术问题暂时无法使用类似游戏内的字体来加载翻译

# 程序或者字库更新请关注群  点击链接加入群聊【AGA重要更新内容通知】：https://jq.qq.com/?_wv=1027&k=f0vEJyDZ


## BASE ON

[bbepis's XUnity.AutoTranslator](https://github.com/bbepis/XUnity.AutoTranslator)|[Aceship's Alice-Gear-Aegis-EN-Text](https://github.com/Aceship/Alice-Gear-Aegis-EN-Text)|[phantasmx's translation_patch](https://github.com/phantasmx/AGA-mods/blob/master/translation_patch.zip)
