{{toc}}

h1. Linux

h2. [Session 0] 命令列 (Command Line)

* 課程：
https://www.codecademy.com/learn/learn-the-command-line (必修)
https://www.udacity.com/course/viewer#!/c-ud595 (選修)

* 投影片：
iTerm https://docs.google.com/presentation/d/1r3TLQvWuqwCx7VIB7pFAexMoUAuCPSqBi7F01-W5YLQ/edit#slide=id.p4
CLI https://docs.google.com/presentation/d/1RyH1a7IUh4_qRwK7KKAN1y78Wh9dz41_yrEfZBBobs8/edit?usp=sharing
Vim + Tmux https://docs.google.com/presentation/d/1ciC55arWbUdAHFUlf5ZBCqqV013hdpmMb2Do9qvN3D0/edit#slide=id.gbe125895f_0_45
PuTTY https://docs.google.com/presentation/d/1nJalBZD2oPP8qp84HQkDfatyD66dDEbF1EbHK6C-KCU/edit#slide=id.i0

* 補充教材：
CONQUERING THE COMMAND LINE http://conqueringthecommandline.com/book/basics

h2.  [Session 1] 安裝與簡易使用

* 課程
# http://www.imooc.com/view/175 (第一章與第二章必修)
# http://www.imooc.com/view/111 (選修)
# https://serversforhackers.com/series/start-here (必修)

* 閱讀
# "電腦基礎":http://linux.vbird.org/linux_desktop/0110linuxbasic.php (必修)
# "Linux 基礎文件":http://linux.vbird.org/linux_basic/ (必修)
# "Linux 架站文件":http://linux.vbird.org/linux_server/ (選修)

* 問題
# 請說明你最喜歡哪一套 Linux 作業系統
# 請安裝一套你喜歡的 Linux 作業系統
# 請說明你的硬碟分割空間的策略為何
# 為什麼 Linux 版本這麼多？ 
# Fedora 跟 RHEL, CentOS 的關係為何 ？

* 作業
# https://github.com/crazyangelo/Cathedral-and-Bazaar/blob/master/Bazaar.md 開源世界的核心概念文件，請熟讀後，撰寫一篇 blog 心得。
#  http://blog.vgod.tw/category/divine-code/  vgod 的追求神乎其技的程式設計之道  ，請熟讀後(尤其是 第十篇 )，撰寫一篇 blog 心得。

h2. [Session 2]  安裝生產力套件

* 安裝與使用：
# htop - 觀察主機負載情況
# guake - 便捷的 Terminal 視窗工具
# tmux - 平鋪式視窗管理工具 ***必修***
# mosh - UDP 的 SSH Client
# the_silver_searcher - 搜尋程式、關鍵字、檔案用的好工具

* 作業
# 編寫一份 tmux 跟 mosh 以及 the_silver_searcher 的使用筆記
# 錄製使用各個指令的操作過程上傳到 asciinema.org

h2. [Session 3] 調整 Shell 環境

* 閱讀
# 附件的 Linux Hack 101
# http://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience/
# https://github.com/jlevy/the-art-of-command-line/blob/master/README-zh.md
# https://github.com/Idnan/bash-guide

* 作業
# 根據 linux hack 101 中的內容調整你的 bashrc ，並展示你調整過後的 bashrc 。
# 請到 gist.github.com 貼上你的 bashrc 的內容，並將網址回應到作業的 issue 中。
# 請安裝使用 zsh ( http://icarus4.logdown.com/posts/177661-from-bash-to-zsh-setup-tips )
# 請安裝使用 tmux plugin 管理器 ( https://github.com/tmux-plugins/tpm )
# tmux 可以安裝許多 plugin ( http://www.sitepoint.com/10-killer-tmux-tips/ )， 請安裝使用後撰寫一篇文章告訴大家你挑了哪些，以及為什麼 ?

h2. [Session 4]  安裝 LAMP 環境 / LNMP (Nginx)

Linux + Apache + MySQL + PHP

* 閱讀
# http://linux.vbird.org/linux_server/0360apache.php
# http://serversforhackers.com/series/lamplemp
# http://www.imooc.com/view/170

* 作業
# 請安裝 LAMP 且在瀏覽器展示首頁。
# 請展示 phpinfo(); 運作的頁面。
