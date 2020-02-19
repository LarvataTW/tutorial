# Git

## 基礎使用

### 必修

- https://www.codecademy.com/courses/learn-git/lessons/git-workflow/exercises/hello-git
- https://www.katacoda.com/courses/git
- https://zlargon.gitbooks.io/git-tutorial/content/

### 選修

- http://gitready.com/
- https://www.codecademy.com/learn/learn-git
- http://www.imooc.com/view/208
- http://www.git-tower.com/learn/git/
- https://www.atlassian.com/git/tutorials/
- https://nic-hartley.github.io/git-gud/
- http://www.ndpsoftware.com/git-cheatsheet.html
- https://github.com/doggy8088/Learn-Git-in-30-days/blob/master/zh-tw/README.md

### Git Branch

http://pcottle.github.io/learnGitBranching/
https://learngitbranching.js.org/

### .gitignore

http://www.html-js.com/article/The-GitHub-TipsGitignore
https://github.com/github/gitignore

## 流程

### git-flow

http://danielkummer.github.io/git-flow-cheatsheet/index.zh_TW.html ***(必修)***

#### git-flow 外掛

git-flow 的實現有輔助的工具，它其實是一連串的 git 指令組合整合到工具裡面，
如此一來，就可以用 git flow feature start 這樣的指令來達成 git-flow 的流程。

工具有兩套：
1. https://github.com/nvie/gitflow (原始的，但已經停止維護)
2. https://github.com/petervanderdoes/gitflow-avh (新版的，有在維護，流程上有些許不一樣，有的人喜歡有的人不喜歡)

安裝 git-flow 輔助外掛 "brew install git-flow-avh":https://github.com/petervanderdoes/gitflow-avh/wiki/Installing-on-Mac-OS-X

#### git-flow auto-compeletion

因為 git-flow 的自動補齊 (auto-compeletion) 跟 git 自帶的有衝突，因此 git 安裝的時候要拿掉它自帶的補齊功能。

    $ brew uninstall git
    $ brew install git --without-completions

在 macOS 的 Homebrew 安裝的 git 裡面有自帶的 auto completions 會跟 git flow auto completions 衝突，
因此需要額外處理：
- https://github.com/Homebrew/homebrew-core/commit/f710a1395f44224e4bcc3518ee9c13a0dc850be1
- https://github.com/robbyrussell/oh-my-zsh/issues/1717
- https://github.com/sorin-ionescu/prezto/issues/993

### GitLab Flow

- https://about.gitlab.com/blog/2014/09/29/gitlab-flow/
- http://www.ruanyifeng.com/blog/2015/12/git-workflow.html
