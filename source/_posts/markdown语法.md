---
title: markdown语法
date: 2018-12-25 09:47:10
tags:
- 语法
- markdown
cover_picture: /images/linux.jpg
---
# 标题相关
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

# 字体加粗
 要加粗的左右用两个*包裹
 **字体加粗效果**
## 斜体
 文本左右用一个*

 *字体倾斜效果*

# 加粗倾斜
左右分别*包裹

***加粗倾斜***

# 删除线
左右用2个~包裹

~~删除线效果~~

# 分割线
三个或者三个以上的-或者*
---

# 超链接
[跳转到百度](http://www.baidu.com)
[跳转内容](目标地址)

# 图片
![图片的alt](图片的scr)
alt:图片加载失败时显示的文字
src:图片的链接/路径
![表情包](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1545713620021&di=2583c993c3e6a68dc45b765c6c2fd356&imgtype=0&src=http%3A%2F%2Ff.hiphotos.baidu.com%2Fimage%2Fpic%2Fitem%2Fd1160924ab18972b016d358bedcd7b899e510a1f.jpg)
![图](/表情包/1.jpg)

# 图片超链接
[![图](/表情包/1.jpg)](http://www.baidu.com)

# 代码片段
```javascript
for(let i=0;1 < 5;i++){
    console.log(i);
}

```

```html
<img src="/表情包/1.jpg">

```

<img src="/表情包/1.jpg">

# 列表
无序列表用-+*开始
-列表1
-列表2
-列表3

有序列表

1.列表1
2.列表2
3.列表3

# 表格

姓名|性别|课程方向
-|-|-
张三|男|web前端
李四|女|UI
王麻子|男|Linux云计算