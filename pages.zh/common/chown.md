# chown

> 修改用户和用户组对文件或目录的所有权。
> 更多信息：<https://www.gnu.org/software/coreutils/manual/html_node/chown-invocation.html>.

- 修改文件或目录的所有者：

`chown {{用户}} {{路径/到/文件或目录}}`

- 修改文件或目录的所有者及所属组：

`chown {{用户}}:{{用户组}} {{路径/到/文件或目录}}`

- 将所有者用户和用户组都更改为 `user`：

`chown {{user}}: {{路径/到/文件_或_目录}}`

- 递归修改目录及其子目录和文件的所有者：

`chown {{[-R|--recursive]}} {{用户}} {{路径/到/目录}}`

- 修改符号链接的所有者：

`chown {{[-h|--no-dereference]}} {{用户}} {{路径/到/符号链接}}`

- 修改文件或目录的所有者与参考文件相同：

`chown --reference {{路径/到/参考文件}} {{路径/到/文件或目录}}`
