**1.Github表格居中(本地):**

1. 在Typora中先创建好表格(Ctrl+T)，然后点击`编辑`-->`复制为HTML代码`后再将其粘贴至Noteppd++，安装Tydy2插件后对其进行格式化;
2. 从格式化后的内容中直接删除`<head>...</head>`、将`<th>`和`<td>`中的`style='text-align:center;'`全部替换(Ctrl+F)为`align="center"`;
3. 在`<table>`中添加`align="center"`以保证表格整体居中，如果需要为表格添加居中标题，在其中添加`<p align="center">table_title</p>`即可;
