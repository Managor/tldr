# ln

> 创建指向文件和目录的链接。
> 更多信息：<https://www.gnu.org/software/coreutils/manual/html_node/ln-invocation.html>.

- 创建指向文件或目录的符号链接：

`ln {{[-s|--symbolic]}} {{/路径/到/文件或目录}} {{路径/到/符号链接}}`

- 覆盖现有的符号链接以指向其他文件：

`ln {{[-sf|--symbolic --force]}} {{/路径/到/新文件}} {{路径/到/符号链接}}`

- 创建文件的硬链接：

`ln {{/路径/到/文件}} {{路径/到/硬链接}}`
