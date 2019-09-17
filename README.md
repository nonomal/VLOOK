# 概况

VLOOK™ 是针对由 [Typora](https://www.typora.io)（目前最好的跨平台 Markdown 编辑器，没有之一）导出的 HTML 文件进行增强的插件。VLOOK™ 为开源软件，遵从 MIT 许可证。
VLOOK 插件主要包括：

- **排版增强**：针对 Typora 编辑模式，以及导出的 HTML 文件增加更实用、美观的文档排版与样式；
- **功能增强**：针对导出的 HTML 文件提供文档导航、评审演示、插图浏览、内容交互、信息缺失检测等功能。

有关 VLOOK 特性的详细介绍、样例及使用说明详见《[VLOOK 快速参考手册](https://madmaxchow.github.io/VLOOK/index.html)》<br/>
有关脚本化图表的详细介绍、样例及使用说明详见《[脚本化图表 for Markdown](https://madmaxchow.github.io/VLOOK/chart.html)》

---

# 主题样式

![内置主题样式](https://tva1.sinaimg.cn/large/006y8mN6gy1g6vex2odrxj33ji0u04c6.jpg)

- 针对 VLOOK 内置多套优化的主题样式（在导出 HTML 通过 Typora 的「主题」菜单选择名称以 VLOOK 打头的主题）；
  - **Hope 海洋之心**：[预览 ＞](https://madmaxchow.github.io/VLOOK/index.html)
  - **Joint 榫卯之美**：[预览 ＞](https://madmaxchow.github.io/VLOOK/theme-joint.html)
  - **Geek 极邃**：[预览 ＞](https://madmaxchow.github.io/VLOOK/theme-geek.html)
  - **Fancy 慕幻**：[预览 ＞](https://madmaxchow.github.io/VLOOK/theme-fancy.html)
- 所有主题的文档导出为 HTML 后，都支持`Light (明亮)`与`Dark (黑暗)`模式。

## 选择主题

- 将`released\theme`下所有 CSS 文件复制至 Typora 的主题目录（ Typora「偏好设置」中选择「外观」，点击<kbd>打开主题目录</kbd>定位到该目录）；
- 进入 Typora 的偏好设置，启用 Markdown 语法扩展下的所有选项（如：公式、上标、下标、高亮、图表等）；
- 重启 Typora，点击菜单`主题`，选择以`vlook-*`形式命名的主题，即可启用对应的 VLOOK 样式主题。

## 主题定制服务

- 主题定制，请加微信：**MaxChow**

---

# 应用插件

- 在 Typora 中将 Markdown 文件导出为`HTML`文件；
- 打开文件`released\VLOOK-TOOLBOX 插件.txt`，全选所有内容，并复制；
- 用纯文件编辑器（如：记事本、VS Code）打开该导出的 HTML 文件；
- 搜索「**<body>**」，并将复制的内容粘贴到 body 标签的「**>**」之后：
  ```
  <body ...>
  ← ← ← ← ← 复制的「VLOOK-TOOLBOX 插件」内容粘贴于此！
  ...
  </body>
  ```
+ 保存，大吉大利。

> 强烈建议使用 Chrome 或 Firefox 浏览器查看

---

# 字体

VLOOK 优先显示开源的思源黑体和思源宋体，建议下载安装获得更好的视觉体验；

- 思源黑体 / Noto Sans（[常规体](https://github.com/googlefonts/noto-cjk/blob/master/NotoSansCJKsc-Regular.otf)、[粗体](https://github.com/googlefonts/noto-cjk/blob/master/NotoSansCJKsc-Bold.otf)）
- 思源宋体 / Noto Serif（[常规体](https://github.com/googlefonts/noto-cjk/blob/master/NotoSerifCJKsc-Regular.otf)、[粗体](https://github.com/googlefonts/noto-cjk/blob/master/NotoSerifCJKsc-Bold.otf)）

---

# 打赏

**若喜欢 VLOOK™ 的话，可以请 Max 喝杯咖啡：**<br>
![微信支付](https://ws1.sinaimg.cn/large/006tKfTcgy1fsmnridvyxj303y04mt94.jpg)

---

# 目录说明

1. `docs`：VLOOK 快速参考手册及相关文档
2. `released`：发布版的主目录
    - `theme`：主题文件
3. `demo`：基于 VLOOK 主题的示例文件
4. `src`：源码目录
    - `dev`：开发测试用示例文件
    - `less`：主题 CSS 文件的源文件
    - `misc`：杂项文件，包括图标源文件、产品原型、主题图形素材设计源文件等

---

# Overview

VLOOK is a plugin for enhancements to HTML files exported by Typora. Includes two major features: Layout Enhancements and Feature Enhancements:

- **Layout enhancements**: Provides more user-friendly, beautiful document layout and style for the Typora editing mode and exported HTML files;
- **Feature enhancement**: Provides convenient reading accessibility functions such as document navigation, illustration browsing, content interaction, and validity detection for exported HTML files.

VLOOK™ is open source software and is compliant with the MIT license.

Detailed description of the features, as well as instructions for use, can be found in the "[VLOOK Quick Reference Manual](https://madmaxchow.github.io/VLOOK/index.html)".
