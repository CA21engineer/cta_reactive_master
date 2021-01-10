# cta_reactive_master

CA Tech AccelでiOSアプリ開発におけるReactiveを理解していく学習リポジトリ

## Setup

以下のコマンドを叩くことで依存しているライブラリをインストールする

```
make setup
```

## Getting Started

1. このレポジトリをForkする

2. slackのGitHubの通知チャンネルに連携する

> slackの`#ios_コロンビア_github`にて`/github subscribe https://github.com/{GITHUB_USER_ID}/cta_reactive_master reviews,comments`を叩く

3. スケジュールに沿って開発を進め、随時PRを作成し、Approveをもらい次第Forkしたレポジトリにmergeする

## Schedule
| Date                    | Title                                                                                                 | Answer Branch           | 
| ----------------------- | ----------------------------------------------------------------------------------------------------- | ----------------------- | 
| 11/21(Sat) - 12/8(Tue)  | RxSwift を利用せずに API(https://newsapi.org/ )を叩いて一覧画面の作成、WebView を用いて詳細画面の作成             | [URL](https://github.com/CA21engineer/cta_reactive_master_answer)
| 12/8(Tue)               | Rx についての概要の説明を受ける                                                                             | -
| 12/8(Tue) - 12/22(Tue)  | Rx を用いて作成した画面を置き換える                                                                          | [URL](https://github.com/CA21engineer/cta_reactive_master_answer/tree/use-rxswift)
| 12/22(Tue)              | MVVM についての概要の説明を受ける                                                                           | -
| 11/22(Tue) - 12/29(Tue) | MVVM に置き換える                                                                                        |[URL](https://github.com/CA21engineer/cta_reactive_master_answer/tree/mvvm)
| -                       | (時間があったら)カスタマイズする(検索機能の追加(filter 処理),差分更新で実装するなど)                                 | -

*スケジュールは暫定的なものなので必要があれば随時更新する予定です。*

## CODING RULES

- base branchへの直接pushは禁止(いかなる場合でもPull Requestを作成し、担当の21卒学生からのApproveをもらうまではmergeしない)
- AutoLayoutを利用する(ViewController作成時はStoryboardではなく、xibを利用する)
- ライブラリを追加する際には基本的にCocoaPodsを利用する(CocoaPodsに対応してないものを利用する場合は相談してください)
- APIのレスポンスを受け取るときは `Decodable`で処理する

## ATENDEES

- [yamanetaisei](https://github.com/yamanetaisei)  
Repo URL: https://github.com/yamanetaisei/cta_reactive_master

- [Yoshitsugu-Antony-Kambara](https://github.com/Yoshitsugu-Antony-Kambara)  
Repo URL: https://github.com/Yoshitsugu-Antony-Kambara/cta_reactive_master
