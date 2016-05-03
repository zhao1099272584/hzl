---
layout: post
title:  "xhtm复习文档2"
date:   2016-05-03 19:06:05
categories: HTML 
tags: HTML 
---

* content
{:toc}

这里主要是讲述XHTML的学习内容，继续上一章没有写完的内容。





## HTNL表格基本格式

```html
	<table>		用来声明表格的开始
		<tr>	用来设置表格的行
			<th>...</th>		用来设置标题的栏位
		</tr>
		<tr>
			<td>...</td>		用来设置数据的栏位
		</tr>
	</table>
```

**`<tahle>`标签下的属性**

```html
属性				属性值					说明
 border				 像素        设置表格的边线
 cellspacing 		 像素		 绝对设置,存储格框线宽度
					百分比		 相对设置,存储格框线宽度
 cellpadding		 像素		 绝对设置,数据与框线的距离
					百分比		 相对设置,数据与框线的距离
 width 				 像素		 绝对设置,像素表示表格宽度
					百分比		 相对设置,百分比表表格宽度
 height				 像素        绝对设置,像素表示表格宽度
					百分比		 绝对设置,百分比表表格宽度
 align				 left			 表格往左靠(默认)
					center		 表格往中靠
					right		     表格网右靠
 bgcolor			英文/十六	 表格的背景颜色
 background          URL         表格的背景图片
 summary			字符串		 用来描述表格数据说明
 bordercolor		英文/十六	 边框的颜色
 bordercolorlight	同上		 边框的亮色
 bordercolordark	   同上		 边框的暗色

4.3 ·<table>·标签下的边框设置

```html
		 属性名称			属性值			说明
		frame				void			不要显现表格的边线
							above			只要显现出表格的上边线
							below			只显现出表格的下边线
							hsides			只显示表格的上下边线
							vsides			只显现表格的左右边线
							lhs				只显现表格的左边线
							rhs				只显现表格的右边线											 border/box      会显现出表格的所有边线

		rules				rows           只显示出横行的格框线
							cols			只显示出直行的格框线
							all				显示全部格框线
							groups          表示列组合水平部分
							none			不显示任何格框线
```

























	