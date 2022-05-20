## Android studio windows network reponse 中文亂碼問題


讓 Android Studio 的 console 顯示 UTF-8 (non-ASCII)
解决方案：

1：全局搜索"双击shift",搜索Edit Custom VM Options；

2：进入第一个文件中， 添加‘-Dfile.encoding=UTF-8’

3：修改出问题的文件的编码，在Android studio右下角重新选择UTF-8

4：重启As   
————————————————
版权声明：本文为CSDN博主「xuwb123xuwb」的原创文章，遵循CC 4.0 BY-SA版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/xuwb123xuwb/article/details/105102253

https://www.jianshu.com/p/5a4f93b3c60d


然后清除缓存重启Android Studio

![image](https://user-images.githubusercontent.com/97726463/169598183-798ad1bf-5188-4ae4-b8ab-da8fb02a6ed0.png)
