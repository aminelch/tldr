# fd

> `find` 的替代工具。
> 旨在比 `find` 更快且更易于使用。
> 更多信息：<https://github.com/sharkdp/fd>.

- 递归查找当前目录中匹配特定模式的文件：

`fd "{{字符串|正则表达式}}"`

- 查找以特定字符串开头的文件：

`fd "{{^字符串}}"`

- 查找具有特定扩展名的文件：

`fd --extension {{txt}}`

- 在特定目录中查找文件：

`fd "{{字符串|正则表达式}}" {{路径/到/目录}}`

- 在搜索中包含被忽略和隐藏的文件：

`fd --hidden --no-ignore "{{字符串|正则表达式}}"`

- 对每个返回的搜索结果执行命令：

`fd "{{字符串|正则表达式}}" --exec {{命令}}`
