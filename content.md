**1.Github表格居中(本地):**

1. Typora中先创建好自己想要的表格(Ctrl+T)并将其以HTML格式导出; 
2. 直接使用Noteppd++或其他文本编辑工具，如Sublime打开.html文件，使用Tydy2(插件安装)对其进行格式化;
3. 从格式化后的内容中直接删除`<head>...</head>`、将`<th>`和`<td>`中的`style='text-align:center;'`全部替换(Ctrl+F)为`align="center"`并且在`<table>`中添加`align="center"`;
4. 删除`<body>`中的`class`标签，如果需要为表格添加居中标题，在`<table>`上面添加`<p align="center"></p>`即可;
