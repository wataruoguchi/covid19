# 貢献の仕方

コントリビューターの皆様、本プロジェクトにご参加いただきありがとうございます！！


本サイトの開発に参加してくださる方に対して、参加方法をお伝えします。

## Issue へのコメントや Pull Request について
* Issue へのコメントはご自由にどうぞ！新しい質問や提案なども受け付けます。
* Issue を追加する場合、既に同様の Issue が無いか検索をしてから作成してください。
* Pull Request を送る場合、可能であれば対応する Issue 番号を追記してください。（テンプレートを利用してください）

## ブランチ運用について

### 大まかな開発の流れ

1. forkして個人リポジトリを作成する
2. forkした個人リポジトリでdevelopmentブランチから派生した開発ブランチを作成
3. 2で開発をする
4. 開発が終わったら開発ブランチをpush
5. 開発ブランチ -> codeforsapporo/covid19のdevelopmentブランチへのPull Requestを作成する
6. 5を誰かがレビュー。問題なければcodeforsapporo/covid19のdevelopmentブランチにmergeされる👍
7. 自動で開発用サイト http://133.242.52.161:58000 が更新されます。

#### 補足
- 5の後、動作確認用のサーバが自動的に立ち上がる設定になっています。動作確認、レビューに使用してください。

### 大まかなリリースの流れ

1. developmentブランチからmasterブランチへのPull Requestを作成する
2. 1をmergeする
3. 自動で本番サイト https://stopcovid19.hokkaido.dev

#### 補足
- 本番環境はキャッシュが設定されているため、反映に5分〜10分程度かかる事があります


## 参加にあたって
* コミュニケーションにあたっては、Code for Japan の [行動規範](https://www.codeforsapporo.org/slack/) もご確認ください。
* 自分ができそうな Issue に誰もアサインされていない場合、Issueに「やります！」等とコメントしてから開発をはじめてください。
* Issue に関連した質問等は、Slack より Issue 内のコメントを活用しましょう
* 提案なども受け付けます！積極的に新しく Issue を作ってください。

## 参考情報
* [東京都 新型コロナウイルス対策サイトへの貢献方法を解説(Qiita)](https://qiita.com/FPC_COMMUNITY/items/b9cc072813dc2231b2b2)
* [東京都新型コロナウイルス感染症対策サイトをforkしてnetlifyでdev環境を立ち上げる手順](https://tech.moyashidaisuke.com/entry/covid19-netlify)

本 ドキュメント の更新も大歓迎です！
