# learngit1

learngit on 20160608

这里是大标题(一级标题)
=

这里是中级标题(二级标题)
-

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

#和后面内容之间要加一个空格，否则就像这样，没有标题的样式


这是一段普通文本，
直接使用回车不能换行,<br>
要使用\<br>

  
  Hello,大家好，我是单行文本(实现方式:行前面加两个制表符tab键)
  这里是多行文本
  多行文本的实现和单行文本的差不多
  就是在每一行前面加两个制表符键(tab键)

你好，我是`高亮`文字。

[这是一个超链接,跳转到bing搜索](http://www.bing.com)

[这是一个超链接,鼠标悬停在上面试试](http://www.bing.com "悬停显示")


注意：要想显示上面圆点的效果,*和后面的文字之间要加一个空格，否则显示为普通星号

* 编程语言
	* 脚本语言
		* 伟大的Python

下面是一种特殊的结构,请看:
>数据结构
>>树
>>>二叉树
>>>>平衡二叉树
>>>>>满二叉树

![看我漂亮吗?](http://mmbiz.qpic.cn/mmbiz/gugMAt70dZpiaWVFQUic0VW0gKESHCYR5PNxWKuVYrx9dvhd1OZSsOW8DbRXLzT8EaR9hQK0p3uyebOSuvoMVanQ/640?tp=webp&wxfrom=5&wx_lazy=1 "鼠标指上去显示的文字.")

插入图片的方法:
叹号!+方括号[如果图片地址不对，显示不出来，则显示这里的文字]+括号(图片地址URL)

如果不加叹号,就会变成普通的文本。

下面这个图片是带超链接功能的:

![baidu][baiduid]

[baiduid]:http://www.baidu.com/img/bdlogo.gif "百度Logo"

[![bing]](http://www.bing.com)
[bing]:http://tse2.mm.bing.net/th?id=OIP.hRtZ0IypTEV1ksbdQ3u_7QE8DF&w=270&h=168&c=7&qlt=90&o=4&pid=1.7 "bing的log"

下面是一段Java语言的代码片段:

```
public static void main(Stirng[] args){
	System.out.println("Hello world!");
}
```

>块注释

*斜体文字*
_斜体文字_

**粗体文字**
__粗体文字__

*实现无序列表
* 昵称:果冻虾仁
* 别名:隔壁老王
* 英文名:Jelly

+实现无序列表
+ 昵称:果冻虾仁
+ 别名:隔壁老王
+ 英文名:Jelly

-实现无序列表
- 昵称:果冻虾仁
- 别名:隔壁老王
- 英文名:Jelly

有序列表:

1. 昵称:果冻虾仁
2. 别名:隔壁老王
3. 英文名:Jelly

脚注:

hello [^hello]

分割线:

---

表格：
* 编程语言
	* 脚本语言
		* 伟大的Python

|项目|价格|数量|
|----|----|----|
|电脑|1000|1|
|手机|200|3|
|平板|400|7|

### 流程图
```flow
st=>start:Start
e=>end
op=>operation:My Operation
cond=>condition:Yes or No?

st->op->cond
cond(yes)->e
cond(no)->op
```
----

LaTeX公式
* $表示行内公式
质能守恒方程: $`E=mc^2`$来表达

This math is inline $`a^2+b^2=c^2`$.

This is on a separate line
```math
a^2+b^2=c^2
```

Sometimes you want to :monkey: around a bit and add some :star2: to your :speech_balloon:. Well we have a gift for you:

:zap: You can use emoji anywhere GFM is supported. :v:

You can use it to point out a :bug: or warn about :speak_no_evil: patches. And if someone improves your really :snail: code, send them some :birthday:. People will :heart: you for that.

If you are new to this, don't be :fearful:. You can easily join the emoji :family:. All you need to do is to look up on the supported codes.

Consult the [Emoji Cheat Sheet](http://emoji.codes) for a list of all supported emoji codes. :thumbsup:
