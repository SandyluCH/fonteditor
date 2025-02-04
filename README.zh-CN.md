Fonteditor Online Font Editor
==========

[English](./README.md) | [中文](./README.zh-CN.md)

使用`Fonteditor`在线编辑、转换、预览字体文件。

支持导入的字体格式有 ttf, woff, woff2, svg font, eot, otf等字体格式，支持ttf, woff, woff2等格式字体导出。

[线上地址](https://kekee000.github.io/fonteditor/)

[Fontstore](http://fontstore.baidu.com/static/editor/index.html)

![Fonteditor](./fonteditor-zh.jpg)

### 开发:

```
npm install && npm run dev
```

* `index.tpl`为入口模板文件，根据`index.tpl`生成`index.html`和`index-en.html`入口文件。
* jszip模块3.0 api有变动，若要升级，需要测试和修改导出zip模式

此模式可操作字体编辑导入ttf预览等

### 编译:

```
npm run build
```

### 测试:

```
npm run test
```

### DEMO:

```
npm run demo
```

### 相关项目

+ Fonteditor Core Lib: [fonteditor-core](https://github.com/kekee000/fonteditor-core)
+ fontmin: [fontmin](https://github.com/ecomfe/fontmin)

## release log:


1. 2014-10-7 ttf管理器发布.

2. 2014-10-19 ttf编辑器发布.

3. 2014-10-28 ttf编辑器增加路径合集、交集、差集.

4. 2014-11-10 ttf编辑器增加svg arc 指令，增加路径切割.

5. 2014-11-10 ttf编辑器增加智能吸附，增加编辑器设置.

6. 2014-12-7 ttf编辑器增加百度编辑器样式.

7. 2014-12-13 ttf编辑器增加列表和查看器命令栏，增加glyf点吸附.

8. 2014-12-13 ttf编辑器增加设置保存.

9. 2014-12-25 圣诞新装发布.

10. 2015-1-8 增加svg circle, ellipse, polygon, path 导入, 自动变换导入轮廓.

11. 2015-1-26 改变项目存储方式为IndexedDB.

12. 2015-1-29 增加移动方向键改变glyf顺序.

13. 2015-2-5 添加轮廓支持拖拽曲线，支持`ctrl+Z`回退.

14. 2015-3-12 修复路径合并，修复路径split，修复项目管理.

15. 2015-3-12 增加字形图像导入功能.

16. 2015-4-9 增加图像导入参数设置，优化导入图形.

17. 2015-4-12 增加同步字体功能.

18. 2015-4-27 增加otf字体读取和转换ttf功能.

19. 2015-5-29 增加英文版本.

20. 2015-7-19 拆分fonteditor-core模块，以便于开发和维护.

21. 2015-8-9 增加按照unicode排序功能，增加菜单状态.

22. 2016-1-5 增加复合字形编辑和复制功能.

23. 2016-2-25 增加字形导出svg和png功能.

24. 2016-3-7 将path的布尔操作库替换成paper.js的路径库.

25. 2016-3-20 增加字体同步的拉取和推送，增加自动更新同步版本.

26. 2016-3-22 增加字形旋转吸附，调整配色.

27. 2016-4-18 更新新lib库，优化错误提示体验.

28. 2019-10-14 使用es6 module 进行重构.

29. 2019-10-24 支持woff2读取和写入, 发布Ver2.
