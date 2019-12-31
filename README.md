## 基于命令行的本地txt阅读器，上班摸鱼的好帮手。

### 使用方法
```
javac -encoding UTF-8 TxtReader.java
java TxtReader /home/abc.txt
```
### 效果![image.png](https://github.com/ghc931227/TxtReader/blob/master/%E8%BE%93%E5%87%BA%E6%95%88%E6%9E%9C.jpg)
![image.png](https://github.com/ghc931227/SlackerReader/blob/master/%E8%BE%93%E5%87%BA%E6%95%88%E6%9E%9C_cmd.jpg)


### 命令说明:

```
Enter: 输入空串时跳转下一行，否则执行输入的指令，下面的说明忽略Enter.
t <NUM>: 跳转到指定行.
s <WORD> [NUM]: 搜索并跳转到指定文本，数字代表出现的顺序. [NUM]未指定时,从当前行数开始搜寻第一个匹配结果.
p: 上一页
b: 保存书签
b <NUM>: 跳转到指定书签
cls: 清屏
e: 退出并保存进度
```
