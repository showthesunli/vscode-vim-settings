# VSCode中Vim插件的配置

本仓库是针对VSCode中Vim插件的配置，目的是为了在VSCode中使用Vim更加顺手。

## 用法

[keybindings.json](./keybindings.json)修改了VSCode的默认快捷键绑定，使用`ctrl/cmd + shift + p`，打开`Perferences: Open Keyboard Shortcuts(JSON)`，将内容粘贴进即可使用。

[setting.json](./settings.json)仅修改了Vim插件相关的用户设置使用`ctrl/cmd + shift + p`，打开`Perferences: Open User Settings(JSON)`，将内容粘贴进对应的位置即可。

**修改以上配置文件之前，请备份原始文件！**

## 说明

使用此配置，请确保你已经对Vim有足够了解。所有的修改的配置项在配置文件中都有详细的说明。这里只对关键的修改和好用操作做出说明，以方便快速上手。

- `jj` `jk`快速退出`insert`模式
- `<leader>+h/<leader>+l`快速跳转到行首/行尾非空字符
- ``<leader>+\`(反引号)``聚焦到终端