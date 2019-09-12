## 基于命令行的本地txt阅读器，上班摸鱼的好帮手。

### 使用方法
```
javac -encoding UTF-8 TxtReader.java
java TxtReader /home/abc.txt
```

|命令|说明|举例|
|:------------:|-----|-----|
|Enter|输入空串时跳转下一行，否则执行输入的指令，下面的说明忽略Enter|p + Enter(上一页)|
|t [NUM]|跳转到指定行|t 0(跳转到第一行)|
|<nobr>s [WORD] [NUM]</nobr>|搜索并跳转到指定文本，数字代表出现的顺序|s 第一章 1(跳转到"第一章"第一次出现的位置)|
|p|上一页|p|
|b [NUM]|跳转到指定书签|b 1(跳转到第一个书签)|
|b|保存书签|b|
|cls|清屏|cls|
|e|退出并保存进度|e|

### 效果![image.png](https://github.com/ghc931227/TxtReader/blob/master/%E8%BE%93%E5%87%BA%E6%95%88%E6%9E%9C.jpg)
![image.png](https://github.com/ghc931227/SlackerReader/blob/master/%E8%BE%93%E5%87%BA%E6%95%88%E6%9E%9C_cmd.jpg)
