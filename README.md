# y600导航页

#### 项目介绍
**y600导航页** 致力于简洁高效无广告的上网导航和搜索入口，支持后台添加链接、自定义搜索引擎，沉淀最具价值链接，全站无商业推广，简约而不简单。请支持原项目：https://github.com/LyLme/lylme_spage

 **原项目名称：** 六零导航页（HTML版）



 **演示站点：**[https://y600o.online/](https://y600o.online/)







#### 自定义链接

 修改 `index.html`文件约170行（代码内有注释）

**自定义链接格式：**

```html
<li class="col-3 col-sm-3 col-md-3 col-lg-1"><a rel="nofollow" href="链接地址" target="_blank"><img src="图标地址" / ><span>链接名称</span></a></li>
```

**自定义分组格式：**

```html
<ul class="mylist row">
	<li class="title"><img src="图标地址" / ><sapn>分组名称</sapn></li>
		分类下的链接.....
</ul>
```
注：img标签可以使用SVG图标代替，原项目教程：https://gitee.com/LyLme/lylme_spage/wikis/pages?sort_id=5472271&doc_id=2453225

```html
<img src="图标地址" / >
替换为
<svg>svg path代码</svg>
```




#### 修改说明

**LOGO修改：** 替换`img/logo.png`文件，或修改 `index.html`文件第10行

**背景修改：** 替换`img/background.jpg`文件，或修改 `index.html`文件第27行

**顶部导航菜单：** 修改 `index.html`文件约40行（代码内有注释）

**备案和版权：** 修改 `index.html`文件末尾（代码内有注释）

**网站统计：** 修改 `index.html`文件末尾（代码内有注释）

#### 自定义搜索引擎

 修改 `index.html`文件约60行（代码内有注释）

**注意：** `input`的`id`值和`label`的`for`值不能和其他搜索引擎重复
