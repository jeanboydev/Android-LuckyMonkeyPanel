# Android-LuckyMonkeyPanel

![](https://img.shields.io/badge/platform-Android-brightgreen.svg) ![](https://img.shields.io/badge/language-java-yellow.svg) ![](https://img.shields.io/badge/license-Apache--2.0-blue.svg)

## 简介 ##
幸运转盘，类似老虎机的抽奖活动效果。

> 圆形转盘详见：https://github.com/jeanboydev/Android-WheelFortune

## 截图 ##

<img src="https://github.com/jeanboydev/Android-LuckyMonkeyPanel/blob/master/resources/Screenshot_20170426-113157.jpg" width="360px" height="640px" />	<img src="https://github.com/jeanboydev/Android-LuckyMonkeyPanel/blob/master/resources/lucky.gif" width="360px" height="640px" />

- gif比较模糊可以看下视频演示

[视频演示效果](https://github.com/jeanboydev/Android-LuckyMonkeyPanel/blob/master/resources/device-2017-04-26-112438.mp4)


## 使用 ##

开始
```Java
lucky_panel.startGame();
```

停止
```Java
int stayIndex = new Random().nextInt(8);//这里为了演示取得随机数
lucky_panel.tryToStop(stayIndex);//stayIndex 为最后停止的位置
```

## 关于我

如果对你有帮助，请 star 一下，然后 follow 我，给我增加一下分享动力，谢谢！

如果你有什么疑问或者问题，可以提交 issue 和 request，发邮件给我 jeanboy@foxmail.com 。

或者加入下面的 QQ 群来一起学习交流。

<a target="_blank" href="http://shang.qq.com/wpa/qunwpa?idkey=0b505511df9ead28ec678df4eeb7a1a8f994ea8b75f2c10412b57e667d81b50d"><img border="0" src="http://pub.idqqimg.com/wpa/images/group.png" alt="Android技术进阶：386463747" title="Android技术进阶：386463747"></a>

## License

    Copyright 2017 jeanboy

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
