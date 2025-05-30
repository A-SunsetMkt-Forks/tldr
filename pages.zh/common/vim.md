# vim

> Vi IMproved，一个程序员的文本编辑器，提供为不同类型的文档修改设计的多种模式。
> 按 `<i>` 进入插入模式。`<Esc>` 返回正常模式，正常模式允许使用 Vim 命令。
> 更多信息：<https://www.vim.org>.

- 打开文档：

`vim {{文件}}`

- 打开文件的指定行数：

`vim +{{行数}} {{文件}}`

- 查看 Vim 的使用说明：

`<:>help<Enter>`

- 保存并退出：

`{{<Esc><Z><Z>|<Esc><:>x<Enter>|<Esc><:>wq<Enter>}}`

- 撤销上一个操作：

`<Esc><u>`

- 用特征（pattern）在文件中搜寻，按下 `<n>`/`<N>` 切换至上 / 下一个结果：

`</>{{特征}}<Enter>`

- 对整个文件使用正则表达式进行替换：

`<:>%s/{{正则表达式}}/{{替换字}}/g<Enter>`

- 显示行号：

`<:>set nu<Enter>`
