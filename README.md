# vim-color-theme-protect-eyes
vim用了这么几年。之前一直用黑底方案。
每天15/6个小时对着屏幕。眼睛最近抗议了。
已经过了装逼的年纪，还是保护亲爱的眼睛为要。
今天有空找了下没有现成的方案，根据http://bytefluent.com/vivify/ 定制，并自己完善了下。

>说明：此方案参考了Hbuilder的“绿柔”主题。

## 预览
![image](https://raw.githubusercontent.com/wsniper/vim-color-theme-protec-eyes/master/img/preview_.png)

----------------
# 配置说明
> 注意： 该配置是在Ubuntu14.04 下的GNOME终端 3.6.2做的。其他终端以及win系统没有测试。
> 话说，工具是拿来用的。不是拿来折腾的，时间就是... 因此本人只在自己工作环境做了测试。

1. 将 .vim/colors/corporation.vim 放入 ~/.vim/colors
2. 打开 ～/.vimrc
  如果你能找到,下面两行

  > colors=somename  (或 colorscheme=somename)   
  > background=somebackground
  
  则修改为：
  
  > colors=light   
  > background=corporation.vim
  
  若没有这两行，则直接添加上：
  > colors=light   
  > background=corporation.vim
  
3. 配置terminal 字体和背景。如下图：
![image](https://raw.githubusercontent.com/wsniper/vim-color-theme-protec-eyes/master/img/terminal-settings-0.png)
![image](https://raw.githubusercontent.com/wsniper/vim-color-theme-protec-eyes/master/img/terminal-settings-1.png)

  > 说明：若要保留终端的背景颜色，可不修改背景（尽管这样可能会在某些细节影响vim的整体协调）。
  >       另外， 若要字体更美观，可以直接在网上找courier New 字体安装。 
  
