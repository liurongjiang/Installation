# pyquery 的安装

pyquery 是一个强大的网页解析工具，它提供了和 jQuery 类似的语法来解析 HTML 文档，支持 CSS 选择器，使用非常方便，本节我们了解下它的安装方式。

## 相关链接

* GitHub：[https://github.com/gawel/pyquery](https://github.com/gawel/pyquery)
* PyPi：[https://pypi.python.org/pypi/pyquery](https://pypi.python.org/pypi/pyquery)
* 官方文档：[http://pyquery.readthedocs.io](http://pyquery.readthedocs.io)

## 安装方法

### pip 安装

推荐使用 pip3 安装，命令如下：

```
pip3 install pyquery
```

命令执行完毕之后即可完成安装。

### wheel 安装

当然也可以到 PyPi 下载对应的 wheel 文件安装，[https://pypi.python.org/pypi/pyquery/#downloads](https://pypi.python.org/pypi/pyquery/#downloads)，如当前最新版本为 1.2.17，则下载的文件名称为 pyquery-1.2.17-py2.py3-none-any.whl，下载到本地再 pip3 安装即可，命令如下：

```
pip3 install pyquery-1.2.17-py2.py3-none-any.whl 
```

## 验证安装

安装完成之后，可以在 Python 命令行下测试。

```python
$ python3
>>> import pyquery
```

如果没有错误报出，则证明库已经安装好了。

