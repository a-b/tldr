# expand

> 解压一个或多个cab文件.

- 将单文件cab文件解压到指定目录:

`expand {{cab文件路径}} {{指定的目录}}`

- 列出cab文件中的所有文件:

`expand {{cab文件路径}} {{指定的目录}} -d`

- 从cab文件中解压所有的文件:

`expand {{cab文件路径}} {{指定的目录}} -f:*`

- 从cab文件中解压一个特定的文件:

`expand {{cab文件路径}} {{指定的目录}} -f:{{文件名}}`

- 解压缩时忽略目录结构，并将它们添加到单个目录中:

`expand {{cab文件路径}} {{指定的目录}} -i`
