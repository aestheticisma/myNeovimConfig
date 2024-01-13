# myNeovimConfig
some neovim config for myself

neovim version == v0.9.5

### KeyMaps

* 定义 ';' 为<Leader>键
    * 使用 `;w` 快速保存
    * 使用 `;q` 快速退出

* Ctrl + h/j/k/l 用于多窗口中切换光标位置

* 在Visual模式下，Tab 和 Shift + Tab 用于缩进和反缩进

* Ctrl + b 调用TreeToggle插件打开侧边目录栏

* telescope 快速检索插件
    * `;ff` : builtin.find_files
    * `;fg` : builtin.live_grep
    * `;fb` : builtin.buffers
    * `;fh` : builtin.help_tags

### Plugins

* 修改nvim/lua/plugins.lua文件后自动更新插件
    * 各个插件的具体配置规则位于 nvim/lua/config 中

* telescope 插件可能需要使用到 ripgrep

