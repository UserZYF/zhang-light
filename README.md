### 相关说明

#### 字体

- 解压主题文件夹后，建议从下面网址下载仓耳今楷03-W04字体或者霞鹜文楷字体
  - 仓耳金楷字体地址：https://www.ztxz.org.cn/canger/549.html
    - 目前此字体存在的问题是输入“\”符号时，会和后面文字有距离
  - 霞鹜文楷字体地址：https://github.com/lxgw/LxgwWenKai/
  - 安装后可自动生效，不用做什么设置；如果没有立即生效，可以重启一下思源笔记

### 0.79版本

- 调整menu菜单高度，恢复为默认高度，否则可能会存在遮挡的情况
- menu菜单悬浮时没有背景颜色
- 将面包屑设置为毛玻璃样式（代码指导来自于Dark+主题作者）
- 其他一些细节

#### 0.78版本更新

- 将主题代码进行拆分，方便精确查找修改
- 修复不弹出通知的bug
- 无序列表前面的圆点大小
- 修改删除线样式（修改为灰色，增加透明度）
- 将第8种字体颜色（灰色）字重设置为正常
- 将左侧dock栏的active状态图标颜色设置为主题色（红色）
- 增加文档树无折叠文档前面的`·`的大小
- 修改列表中有4种外观样式时左侧竖线偏移的bug
- 修改待办事项的样式（现在的折叠样式有点不直观）
- 去掉设置界面中关闭按钮的底色（简单点）
- 参考flowus移动端侧栏的样式，修改zhang-light主题侧栏的渐变方向和颜色（可以多来几种颜色，渐变过渡更加自然）
- 修改高亮样式
- 鼠标在标签页悬浮时不改变背景颜色
- 修改块引用icon样式
  * 设置为图片
- 修改设置中按钮样式
  * 像OneNote主题那样

#### 0.77版本更新

- 文档中的第一个标题去掉顶部边距
- 修复文档树顶部的宽度和标签页宽度保持一致（通过margin修改）
- 调整表格为居左对齐
- 去掉设置界面选择框的底部边框
- 修复其他小问题

#### 0.76版本更新

- 修复标签页兼容性问题
- 修复标题折叠引起的编号错误的问题
- 增加导出PDF时在分割线和一级标题处分页
- 修复导出PDF时列表转思维导图“·”符号位置错乱问题
- 取消折叠标题中去除自动编号的设置

#### 0.75版本更新说明

- 以后将更新说明单独列为一个文件，不过仍旧会在 README 文档中展示最近更新的内容
- 修复头图按钮变灰导致文字看不清楚的bug
- 修改分割线样式，2像素灰色虚线，原本的动态分割线太占用资源就给去掉了

### 教程

- 自己在 B 站做了一些教程，大家感兴趣的可以移步我的 B 站主页观看
  - [思源笔记视频教程](https://space.bilibili.com/250665585/video)

### 反馈方法

- 如果有什么建议或者反馈，欢迎访问我的 GitHub 主页；也可以通过 QQ 邮箱进行反馈 3466181911@qq.com

### 自定义属性

- 自定义属性 shift+鼠标左键，弹出窗口中，选择“添加”，左侧填入属性，右侧填入属性值，即可实现相应效果
  - 自定义属性针对整个段落生效，不能针对段落中的部分文字生效
  - 属性可以叠加，中间用空格隔开即可（不需要加逗号，顿号等）

#### 块的自定义属性


|名称|属性|属性值|
|---|---|---|
|楷体|f|k|
|宋体|f|s|
|黑体|f|h|
|微软雅黑|f|w|
|华文行楷|f|xk|
|隶书|f|l|
|文字下划线虚线|f|x|
|文字下划线曲线/波浪线|f|q|
|文本竖排|f|sp|
|文本缩进|f|sj|
|文本加粗|f|bold/jc（加粗）|
|1.1倍文字大小|f|1.1|
|1.2倍文字大小|f|1.2|
|1.3倍文字大小|f|1.3|
|1.4倍文字大小|f|1.4|
|1.5倍文字大小|f|1.5|
|1.75倍文字大小|f|1.75|
|2倍文字大小|f|2|
|英文首字母大写|f|dx|
|英文所有字母都大写|f|ddx|
|弹幕|f|dm|
|列表转化为表格|f|bg|
|列表转化为导图|f|dt|
|增加超级块之间间距|f|super/cjk（超级块）|
|超级块不显示边框|f|superno/cjkno|
|块增加边框|f|bk（边框）|
|表格自动宽度|f|auto|
|表格居中|table|center|
|表头和表行格式一致|f|biaotou（表头）|
|去掉图片边框和阴影|f|pic|

#### 便利贴效果

| 便利贴             | 代码 | 值         |
| ------------------ | ---- | ---------- |
| 浅色红             | q    | blt1       |
| 浅色黄             | q    | blt2       |
| 浅色蓝             | q    | blt3       |
| 浅色绿             | q    | blt4       |
| 深色红             | s    | blt1       |
| 深色黄             | s    | blt2       |
| 深色蓝             | s    | blt3       |
| 深色绿             | s    | blt4       |
| 冰墩墩             | f    | ay（奥运） |
| 雪容融             | f    | ay2        |
| 黄色径向渐变便利贴 | f    | jb（渐变） |

#### 文档的自定义属性

| 名称                         | 属性 | 属性值                    |
| ---------------------------- | ---- | ------------------------- |
| 去除自动编号                 | f    | bh                        |
| 去除标题下方圆角矩形         | f    | bt                        |
| 修改文档字体为鸿蒙字体       | f    | hm/hw                     |
| 修改文档字体为微软雅黑       | f    | yh                        |
| 修改背景为护眼色-绿豆沙      | f    | green                     |
| 修改背景为护眼色-WPS护眼绿   | f    | green1                    |
| 修改背景为护眼色-青草绿      | f    | green2                    |
| 修改背景为护眼色-杏仁黄      | f    | yellow                    |
| 修改背景为护眼色-极光灰      | f    | gray                      |
| 修改背景为护眼色-瑞雪白      | f    | white                     |
| 限制文档中图片宽度           | f    | picwidth/tpkd（图片宽度） |
| 去掉本文档网络图片左上角图标 | f    | picno                     |

### 主题截图

![preview.png](https://tva1.sinaimg.cn/large/0082QUidly1h2e3atpvxnj31hc0u0qc4.jpg)

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gzsgda4t7aj31hc0smkao.jpg)

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gzsge4flubj31hc0sm1be.jpg)

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1h03bwdngb1j31hc0sm1kx.jpg)

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gzsi13jfipj31hc0sm13h.jpg)

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gzsi5wv36wj31hc0smgx2.jpg)

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gzsi34942uj31hc0smdq5.jpg)

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gzshllc8bsj31hc0sm18t.jpg)

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gzshr7al8jj31hc0smdvk.jpg)

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gzshswsij6j31hc0smqnu.jpg)

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gzshutksjfj31hc0smkgl.jpg)

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gzshvow6okj31hc0sm1j3.jpg)

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gzshzlzbpsj31hc0sm1kx.jpg)

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gzsi8fsqejj31hc0smaui.jpg)

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gzsibhzoegj31hc0smkdc.jpg)



### 感谢列表

| 主题/插件                    | 作者          | 说明                                                         |
| ---------------------------- | ------------- | ------------------------------------------------------------ |
| Tsundoku Light               | Achuan-2      | 本主题基于 Tsundoku Light 主题进行开发修改，借鉴了代码块样式,icon图标等 |
| Obsidian-Orange              | echoxu        | 使用了 Orange 主题中的字体配色                               |
| BluePrint-From-Tsundoku-main | COPPOLO       | 使用了主题中的格子背景                                       |
| Concise Light                | mindstudy     | 在九炎大佬的基础上，和萌新，Roy，mindstudy一起完善了无序列表转表格的功能 |
| notion-theme                 | Roy           | Js脚本，列表转思维导图的功能                                 |
| dark+                        | Zuoqiu-Yingyi | 列表转思维导图的功能                                         |
| cc-markmap                   | leolee        | 提供了很多帮助                                               |

### 个人推荐码

rsGjU7S
