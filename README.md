# zhang-light主题

### 灵感来源

- 本主题以Tsundoku Light主题为模板进行修改
- 字体配色采用了Obsidian中Orange主题中的7中彩虹配色
- 主题页面背景灵感来自于BluePrint-From-Tsundoku-main的格子主题

### 主题截图

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gz54x8db4gj31hc0smna9.jpg)

![image_1.png](https://tva1.sinaimg.cn/large/0082QUidly1gz54yb0m7qj31hc0smtkz.jpg)

![image_2.png](https://tva1.sinaimg.cn/large/0082QUidly1gz54ymxg7wj31hc0smti3.jpg)

![image_3.png](https://tva1.sinaimg.cn/large/0082QUidly1gz54yuy83pj31hc0smk6k.jpg)

### 主题介绍

- 本主题旨在模拟真实笔记本的感觉，用手写字体，格子背景来模仿真实的笔记本纸张
- 背景样式默认为格子图，此外还可以实现圆点图，横线图。
	- 可以从theme.css中找到“设置页面背景”相关代码
	- 然后将需要的代码取消注释，将不需要的代码注释掉即可
- 标签页采用了类似于iPad上软件的标签页，每个标签页自适应长度
	- 如果想要固定标签页宽度，可以从theme.css中找到“标签页样式”相关代码
	- 将`/* flex: none !important; */` 和`/* min-width: 12em; */` 取消注释
- 标题样式h1-h6下方加了固定长度圆角矩形衬底，不会根据文字内容自适应匹配长度
- 表格单行和双行颜色不同，鼠标悬浮时会有高亮显示；表格列边框不明显
- 对引用块和超链接设置了类似的格式，后面加了不同的icon，且鼠标悬浮时会显示不同颜色
- 对行内代码和键盘设置了同样的效果，因为觉得这两者之间区别不大
- 对引用，代码和嵌入块设置了类似的效果，增加主题元素的统一性
- 选中文字后字体的展开选项里边颜色有13种，设置7种颜色后，将其余选项设置为更改字体和添加下划线
- 选中文字后背景的展开选项最后1个（第13个），设置了挖空效果，鼠标悬浮可显示隐藏内容，可以用来复习关键词
- 对外观中的4种样式设置了便利贴效果（错误样式，警告样式，信息样式，成功样式）
	- 选中“引用”的内容后，再设置4种样式，有另外的样式效果

### 便利贴使用方法

8种样式

![image_4.png](https://tva1.sinaimg.cn/large/0082QUidly1gz54zevd3ij30yy0nkdnj.jpg)

#### 使用方法：

![image_5.png](https://tva1.sinaimg.cn/large/0082QUidly1gz54ztjqy9j30x50kwtgr.jpg)

鼠标左键单击文字左侧icon，然后选择“外观”中的4种样式



![image_6.png](https://tva1.sinaimg.cn/large/0082QUidly1gz55097zjzj30ud0jp7bz.jpg)

下方则先添加引用，再设置样式



### 自定义属性

> 自定义属性针对整个段落生效，不针对段落中的部分文字生效（只能是一个段落，不能按住Enter分行，要按住Ctrl+Enter）


> 自定义属性shift+鼠标左键，弹出窗口中，选择“添加”，属性名填入“f”，属性值填入下列代码，即可实现相应效果


|分类|名称|代码|
|---|---|---|
|字体|楷体|k|
| |宋体|s|
| |黑体|h|
| |微软雅黑|w|
| |华文行楷|xk|
| |隶书|l|
|下划线|虚线|x|
| |曲线/波浪线|q|
|文字竖排|竖排|sp|
|文本缩进|缩进|sj|
|文字大小|1.1倍|1.1|
| |1.2倍|1.2|
| |1.3倍|1.3|
| |1.4倍|1.4|
| |1.5倍|1.5|
| |1.75倍|1.75|
| |2倍|2|
|英文字母大小写|首字母大写|dx|
| |所有字母都大写|ddx|
|奥运主题|冰墩墩|ay|
| |雪容融|ay2|



### 注意事项

解压主题文件夹后，从下面网址下载仓耳今楷03-W04字体

https://www.ztxz.org.cn/canger/549.html
