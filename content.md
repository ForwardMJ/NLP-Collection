**1.Github表格及其内容居中(离线):**

1. 在Typora中先创建好表格(Ctrl+T)，然后点击`编辑`-->`复制为HTML代码`后再将其粘贴至Noteppd++，安装Tydy2插件后对其进行格式化;
2. 从格式化后的内容中直接删除`<head>...</head>`、将`<th>`和`<td>`中的`style='text-align:center;'`全部替换(Ctrl+F)为`align="center"`;
3. 在`<table>`中添加`align="center"`以保证表格整体居中，若需要为其添加标题，在`<table>`上添加`<p align="center">title</p>`即可;

<html>
    <body>
        <figure>
            <table align="center">
                <thead>
                    <tr>
                        <th align="center">候选者</th>
                        <th align="center">框架</th>
                        <th align="center">优点</th>
                        <th align="center">缺点</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="center">
                            <a href='https://github.com/PyUnit/pyunit-address'>Pyunit-Address</a>
                        </td>
                        <td align="center">Paddle</td>
                        <td align="center">1. 支持规则地址的自动补全和纠错；
                        <br />2. 默认使用全国五级地址库，统计时间为2019年；
                        <br />3. 对于非规则地址，提供了深度学习模型(Transformer)提取；</td>
                        <td align="center">实用性较高</td>
                    </tr>
                </tbody>
            </table>
        </figure>
    </body>
</html>

<html>
    <body>
        <figure>
            <table align="center">
                <thead>
                    <tr>
                        <th align="center">候选者</th>
                        <th align="center">框架</th>
                        <th align="center">优点</th>
                        <th align="center">缺点</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="center">
                            <a href='https://github.com/PyUnit/pyunit-address'>Pyunit-Address</a>
                        </td>
                        <td align="center">Paddle</td>
                        <td align="center">1. 支持规则地址的自动补全和纠错；
                        <br />2. 默认使用全国五级地址库，统计时间为2019年；
                        <br />3. 对于非规则地址，提供了DL模型(Transformer)；</td>
                        <td align="center">实用性较高</td>
                    </tr>
                    <tr>
                        <td align="center">
                            <a href='https://github.com/wodejiafeiyu/ccks2021-track3-top1'>CCKS2021-Track3</a>
                        </td>
                        <td align="center">PyTorch</td>
                        <td align="center">
                            <ul>
                                <li>第一点</li>
                                <li>第二点</li>
                                <li>第三点</li>
                            </ul>
                        </td>
                        <td align="center">实用性可以</td>
                    </tr>
                </tbody>
            </table>
        </figure>
    </body>
</html>

