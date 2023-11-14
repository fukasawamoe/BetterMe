
# yoriyoi

■ 画面遷移図 Figma:
https://www.figma.com/file/tXrmXSDfquZQ29ewXxRQ1z/%E7%84%A1%E9%A1%8C?type=design&node-id=0-1&mode=design&t=HdGvAfIzmxwtVfQi-0

■ 画面遷移図 ER図:
[![Image from Gyazo](https://i.gyazo.com/f7d21364ecce1198cdc42c4fd3d4c571.png)](https://gyazo.com/f7d21364ecce1198cdc42c4fd3d4c571)

## サービス概要
---
現在のあなたからあなたの理想とするあなたへ改善のサポートを行います。

## 想定されるユーザー層
---
生活習慣が乱れがちな方
自分の生活パターンの習慣付けを行いたい方
今の生活の中でもっとタイムマネジメント力を付けたい方
RUNTEQ生（自分を含め夜型になってしまう方が多いので）

## サービスコンセプト
---
このアプリは生活習慣が乱れがちなユーザーに向けて、ユーザーにとっての理想的な生活習慣を
身につけていくサポートを行います。
具体的には、ユーザーの目標や優先事項に基づいてスケジュールを作成できる機能。
目標設定や進捗管理の機能を提供し、ユーザーが目標に向かって進んでいることを可視化する機能。

サービスの売りや差別化ポイントは以下となります。

- 1から自分で全てのスケジューリングを作ることなく、1日の雛形が完成します（いくつかの雛形をもとにスケジュールの作成をサポートします）
- 生活の習慣化が難しい部分は”できた”ボタンの実装を行い、ポイントやバッヂなどを獲得できる仕組みを導入します（それか執事からの一言など）
- 応援や励ましのメッセージ（ここは時間と技術力の相談です。理想はLINE連携で執事のようなキャラクターがスケージュール管理を行なって
  時には褒めたり、たしなめたりする機能を実装したいです）

以上のようにこのアプリはユーザーの理想とする自分へ近づけるお手伝いをすることを目指しています。


## 実装を予定している機能
---
### MVP
* 会員登録
* ログイン機能
* 理想の生活習慣のスケジュール作成
* 目標作成・頑張ること作成
* 時間に合わせたタスクの通知
* マイページ
* aiからのタスク通知（webアプリ内）

### その後の機能
* 各ユーザーの目標達成状況（クリアできた日数/登録日）（達成状況90％以上で執事からの一言が付く「ぼっちゃま/お嬢様は大変優秀です」など）
* カスタムでaiからの通知が届く
* LINE連携機能（LINEで起床時間や達成できていない場合に1時間ごとに通知を送る）
* ユーザーの好きなキャラクターで設定ができる（カスタム）
* 達成状況を一目でわかるようにグラフ化
* 一週間ごとの達成状況へのコメント
* RUNTEQからの提案　フルコミット生への理想の生活（このまま設定できるようにしたいですキャラクターは限りなく校長に近い何かです。
  らんてくんは難しいと思うので）
