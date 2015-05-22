1.替换mac 系统自带的vim7.3
brew install vim --with-lua
2.防止中文输出乱码
vim ~/.vimrc.local
language message zh_CN.utf-8
3.解决上下左右变ABCD的问题
vim ~/.vimrc.bundles.local
"解决了上下左右变ABCD的问题
Bundle 'spf13/vim-autoclose'