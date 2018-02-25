# Git

初期化

~~~
git init
~~~

~~~
git status
git add -A
git commit -m message
~~~

~~~
git clone [repository PATH] [new repository PATH]
~~~

ブランチの作成とチェックアウトを行う
~~~
git branch <branchName>
git checkout <branchName>
~~~
or
~~~
git checkout -b <branch>
~~~

リモートの最新状態を取得
~~~
git fetch -p
~~~

~~~
git config --global --add pull.ff only

git config --global --add merge.ff false
--ff
git config --global --add pull.ff only

git log --graph --oneline
git log --pretty='format:%C(yellow)%h %C(green)%cd %C(reset)%s %C(red)%d %C(cyan)[%an]' --date=iso
~~~