# samplejgit


JGitを使ったサンプルのコマンドラインツールです

### Usage

ビルドツール
Maven 3.1.1
```
mvn package
```

実行方法
```
java -jar ./target/samplejgit-1.0-SNAPSHOT.jar COMMAND
```
COMMAND一覧
* -init
  - myrepoというフォルダを作成し，
  - git init

* -add
  - myrepo内の変更を全てステージングする
  - git add .

* -commit -m MESSAGE
  - myrepoフォルダ内をコミットする
  - git commit -m MESSAGE

* -status
  - リポジトリ内のファイルの変更を，一覧表示する
  - git status

* -diff
  - myrepoフォルダ内のファイルの差分を表示する
  - git diff

* -clone REMOTE_REPOSITORY
  - リモーチリポジトリをcloneする
  - git clone REMOTE_REPOSITORY
