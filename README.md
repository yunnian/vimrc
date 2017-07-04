# vimrc
帮你的mac 配置好看的vim
下载vimrc文件
1. mv vimrc ~/.vimrc  //因为下载的文件是不带点的 
2. vim .vimrc
3. esc模式下 执行:BundleInstall 

4下载solarized 导入mac默认终端

vim中显示行行号区背景色与编辑区背景色能不能改成不一样
可以自己敲命令改，如2L，
也可以找现成货，如3L
or 自己改配色文件 ~/.vim/colors/xxx.vim的LineNr值.
622 行 s:fg_none .s:bg_none

16进制数表示颜色值（自己用gcolor查），fg前景为（文字），bg为背景，term控制vim，gui控制gvim
