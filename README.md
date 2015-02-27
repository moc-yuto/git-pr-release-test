git-pr-release-test
===================
git-pr-release --release の挙動確認リポジトリ

production にマージすると、 [CircleCI](https://circleci.com/gh/hiroshi/git-pr-release-test) が自動的に `git-pr-release --release` を実行します。

確認手順
--------

git-pr-release を実行するときは以下のように `VERSION` 環境変数を指定してください。

```
VERSION=v4 bundle exec git-pr-release
```

VERSION の値は `--release` 時のタグ名になるのでタグ名として許可されているものにする。
