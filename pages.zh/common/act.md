# act

> 使用 Docker 本地运行 GitHub Actions.
> 更多信息：<https://manned.org/act>.

- 列出可用的 actions 清单：

`act -l`

- 运行默认 event：

`act`

- 运行指定 event：

`act {{event_type}}`

- 运行指定 action：

`act -a {{action_id}}`

- 非实际运行 actions（也就是 dry-run 模式）：

`act -n`

- 展示详细记录：

`act -v`

- 运行指定 workflow：

`act push -W {{workflow 的路径}}`
