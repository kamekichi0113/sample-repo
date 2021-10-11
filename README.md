# sample-repo

git練習用

git remote -v
リモートリポのURLを確認する。

git config --global --list
configを確認する。

git branch
ブランチの一覧を表示する。現在の作業ブランチを確認する。

git branch <branch-name>
新しいブランチを切る。（ローカルリポジトリで）
長すぎないように、単語をつなげる場合は"-"でつなげる。

git checkout <branch-name>
git checkout -b <branch-name> とすると、作成して切り替えることが可能。

git add .
変更を追加

git commit -m <"commit message">

git log
コミットの履歴を一覧表示する。


■ pushする前にpullする。
アクティブブランチにpullされる。
git pull origin main
git push origin update-readme

■pullしてローカルリポを更新する
mainブランチに移動する
git checkout main
リモートリポのmainブランチをpullする
git pull origin main

