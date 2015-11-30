#### 说明
MarkDown是为了简化大家编写<a name="top">[HTML](#html)</a>（网页）语言的繁琐，不易掌握而生的，但是MarkDown的语法最终还是会被编译成HTML语言，只不过对大家而言是不透明的，所以MarkDown编辑器是支持HTML语言的，所以如果MarKDown的部分语法如果满足不了你的需求，你是可以寻求HTML语言支持的。

强烈推荐先下载Mou，用Mou打开此文档

[Mou](http://25.io/mou/)的下载

###目录 （<font color=red>页面内跳转</font>）
- [1.字体](#1)
  * [1.1 加粗](#1.1)
  * [1.2 斜体](#1.2)
  * [1.3 删除线](#1.3)
  * [1.4 高亮](#1.3)
  * [1.5 颜色 && HTML](#1.4)
- [2.横线](#2)
- [3.表格](#3)
- [4.多选框](#4)


- ### <empty id="1">字体</empty>
#H1#
##H2
###H3
####h4
#####h5
######h6

<!-- empty标记是为了页内跳转，可能有些编辑器不能识别 -->
- ### <empty id="1.1">加粗</empty>
**这是粗体**

- ### <empty id="1.2">斜体</empty>
*这是斜体*

- ###  <empty id="1.3">斜体</empty>删除线
~~这是删除线~~

- ### 高亮
`高亮文字`

- ###  <empty id="1.4">颜色</empty>
<font color=red>红色的内容</font> <br> 换行
<font color =blue> <u> 下划线 </u> </font>

### MARK: <empty id="2">横线</empty>
---
***


### <empty id=3>表格</empty> <br> (** <font color=red>注意对齐方式: ,表格内加粗，变斜.. **</font>) 


|left alignment  |middle center |right alignment              |
|:---------------|:------------:|----------------------------:|
|left            |`center`      |<font color=blue>right</font>|
|*left1*         |**center1**   |~~right1~~                   |
|left2           |center2       |<u>right2</u>                |


### <empty id=4>多选框</empty>, 有些编辑器可能不识别像Mou
+ **我喜欢的运动**
  - [x] 游泳
  - [x] 篮球，足球，乒乓球，羽毛球，台球...
  - [x] 跑步
  - [ ] 呵呵 

### 列表
* 读书
  * 结网
    * 第一章
    * 第一节
    * 哦 My god
  * 启示录
* 写作
* Coding


+ 读书
+ 写作
+ Coding


- 读书
- 写作
- Coding


1. 读书
2. 写作
3. Coding

---
### 链接
- 1.1 文本链接
  - [百度](http://www.baidu.com "Baidu全球中文搜索引擎")
- 1.2 隐式链接
  -   *隐式链接， 系统自动识别，需要加http*
  -    <http://www.baidu.com>
- 1.3 引用链接(鼠标悬停是会显示注释的哦~)
  
	- [云账户][1] 
	- [1]是引用标签， [1]:可以放在文章任意位置, 任何[1]都会被识别
	- [Hunter], [Hunter], [Hunter]
  [1]:https://www.yunzhanghu.com "云账户is a diffent pocker"
  [Hunter]: http://github.com/youran1024  "You know Hunter?"
  
- 1.4 图片链接
  
  ![yun](https://www.yunzhanghu.com/img/logo.png "云账户 is a pocket")


### Whrite the Code Change the world
```
typedef void(^InvestCallBackBlock)(InvestCallBackMethod, NSDictionary *);

static inline UIColor * ht_hexColor(uint color)
{
    float r = (color&0xFF0000) >> 16;
    float g = (color&0xFF00) >> 8;
    float b = (color&0xFF);
    
    return [UIColor colorWithRed:r/255.0f green:g/255.0f blue:b/255.0f alpha:1.0f];
}

```

页内跳转
<a href="#html"></a> 
<sign id=html></sign>[ **`HTML`** ]:"网页编程语言，比MarkDown要难学，但是很强大哦~" 




> **Powered by [Mr.Yang](https://github.com/youran1024)**
> >**Copy right @[云账户](https://www.yunzhanghu.com/)**
>>> Thanks for your reading , if you like 点32个赞吧~
>>>>好无耻的人啊，还要赞！