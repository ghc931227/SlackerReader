## 基于命令行的本地txt阅读器

### 使用方法
```
javac -encoding UTF-8 TxtReader.java
java TxtReader /home/abc.txt
```

|命令|说明|举例|
|----|-----|
|Enter|输入空串时跳转下一行，否则执行输入的指令，下面的说明忽略Enter|p + Enter(上一页)|
|t 数字|跳转到指定行|t 0(跳转到第一行)|
|s 文本 数字|搜索并跳转到指定文本，数字代表出现的顺序|s 第一章 1(跳转到"第一章"第一次出现的位置)|
|p|上一页|p|
|b 数字|跳转到指定书签|b 1(跳转到第一个书签)|
|b|保存书签|b|
|cls|清屏|cls|
|e|退出并保存进度|e|

### 效果![image.png](https://img.hacpai.com/file/2019/09/image-fe058bc1.png)
