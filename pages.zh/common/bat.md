# bat

> 可以打印并且合并文件的命令。
> `cat` 的复制品，外加语法高亮和 Git 集成。
> 更多信息：<https://github.com/sharkdp/bat>.

- 文件内容打印：

`bat {{文件}}`

- 多文件合并到目标文件：

`bat {{文件1}} {{文件2}} > {{目标文件}}`

- 在指定文件后追加多个文件合并的内容：

`bat {{文件1}} {{文件2}} >> {{目标文件}}`

- 打印时，显示行号：

`bat --number {{文件}}`

- 高亮一个 `json` 文件：

`bat --language json {{文件.json}}`

- 受支持的语言清单：

`bat --list-languages`
