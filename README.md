# Life with Datadog
ref: https://docs.google.com/spreadsheets/d/1WNrkHBpaNaYeCH_7gWtZX5OGK2FU40xTxW1NHKQq444/edit#gid=0

2021-01-25(Sun) 15:00 - 15:25

## Abstract

一番好きな SaaS は何か？と聞かれたらどう答えますか？私はダントツで Monitoring SaaS の Datadog です。サービスの安定運用のために Monitoring は必要不可欠ですが、多様な Monitoring SaaS あるいは OSS がある中でなぜ Datadog なのでしょうか。本発表では、前半部分でなぜ私が Datadog が一番好きなのかを、GUI、機能、サポートなど様々な切り口から説明します。後半では具体的な活用事例を紹介します。Kubernetes HPA を組み合わせた Autoscaling のような細かい事例から、SLO や monitor それ自身をチームでどのように運用しているかを説明します。本発表で Datadog そのものの良さと、どのように Datadog とともに生活していくかを持ち帰ってもらえると幸いです。	

## Target

システム運用者、Monitoring SaaS に興味があるひと、Datadog に興味があるひと

---

## Outline
* 自己紹介
* Datadog とは何か
* Datadog の好きなところ
  * サポート、サポート、サポート！
  * リッチな GUI
  * SLO 機能
* Datadog との生活
  * Monitor Summary を毎日見ている
  * Weekly Summary を毎週見ている
  * Alfread と組み合わせて monitor, dashboard, SLO はすぐ開けるようにしている
* Datadog との生活 応用編
  * Custom Metrics の活用
  * Datadog の Cost との付き合い方

## Audience Takeaway
* まったく使ってないひと向け：なんか良さそうと思ってもらう
* 既に使っているがなんとなく使っている人向け
  * 安定した Datadog 生活へのヒントを得てもらう
  * 応用機能を実現するためのヒントを得てもらう

## Contents
TODO: miro 使う？ keynote?

### 自己紹介
* Takeshi Kondo
* (Twitter: @chaspy_ / GitHub:@chaspy)
* Lead Software Engineer, Site Reliability at Quipper
* Japan Datadog User Group Organizer
* Datadog 好きすぎて最近 Software Design にDatadog のハンズオン寄稿しました
* https://chaspy.me

### Datadog とは何か
Monitoring SaaS. NewRelic や Mackere のお友達。

### Datadog の好きなところ
  * サポート、サポート、サポート！
  * リッチな GUI
  * SLO 機能

### Datadog との生活
  * Monitor Summary を毎日見ている
  * Weekly Summary を毎週見ている
  * Alfread と組み合わせてmonitor, dashboard, SLO はすぐ開けるようにしている

### Datadog との生活 応用編
  * Custom Metrics の活用
  * Datadog の Cost との付き合い方
