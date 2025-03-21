---
layout: page
title: プロセス
---

OSS Gateオンボーディングはある程度短い期間に集中的に実施することを想定しています。長い期間が必要になると関係者の稼働を確保することが難しくなる可能性が高いからです。たとえば、大学生の夏休みの期間（1-2ヶ月）くらいを想定しています。

このプロセスは現時点で完成されたものではなく、実施して得られた知見を反映して改良していく予定です。

## 大まかな流れ

それぞれの項目の詳細は後述しますが、大きく次のような流れになります。

  1. 運営：定期的に先輩向け募集要項の書き方説明会を開催
     * Webサイトの説明だけで十分理解できた先輩は参加する必要はない
  2. 先輩：開発者が増えて欲しいOSS用の募集要項を書く
  3. 先輩・運営：適切に新人に内容を伝えるために募集要項のブラッシュアップ
  4. 先輩・運営：適切な新人に情報が届くように募集要項を告知
  5. 運営：定期的に新人向けのOSS Gateオンボーディング説明会を開催
     * Webサイトの説明だけで十分理解できた新人は参加する必要はない
  6. 新人：開発に参加したいOSS用の募集要項に応募
  7. 先輩：応募の中から新人を選考
     * 運営：必要に応じて支援
  8. 先輩・新人・運営：募集要項の進め方に沿って進行
  9. 先輩・新人：成果発表
  10. 新人：引き続き対象OSSの開発に参加

## 応募

まず、先輩が以下の募集要項をまとめて興味のある新人・アシスタント・スポンサーを募集します。募集中の要項は[トップページ]({{ site.baseurl }}{% link index.md %})で確認できます。

  * タイトル
  * 先輩の名前
  * 開発対象の概要
  * 対象OSSの開発に参加することで新人が得られること
  * 対象OSSと先輩の関わり
  * 進め方（後述）
  * 期間終了時に先輩が新人に期待すること
  * 支援期間
  * 必要な報酬
  * 募集期間

例：[Apache Arrow Flight GLibの開発]({{ site.baseurl }}{% link proposals/2021-07/kou-apache-arrow-flight-glib/index.md %})

募集要項は`https://github.com/oss-gate/on-boarding/tree/main/proposals/${開始時期}/${先輩のID}-${募集要項のID}/index.md`に置きます。たとえば、↑の例では https://github.com/oss-gate/on-boarding/tree/main/proposals/2021-07/kou-apache-arrow-flight-glib/index.md になります。変数になっている部分はそれぞれ次の値になっています。

  * 開始時期：`2021-07`
  * 先輩のID：`kou`
  * 募集要項のID：`apache-arrow-flight-glib`

新人は興味のある募集要項があったら以下の情報をまとめて応募締切までに応募します。次の内容をまとめてメールで`on-boarding@oss-gate.org`に送ってください。

  * 名前（GitHubのIDなどOSS Gateオンボーディング内で困らないものであれば本名でなくても構いません。）
  * 対象募集要項のURL
  * 応募動機
  * 現時点での自分のOSS開発に関する知識・経験
  * 活動予定時間
  * どこでこの活動を知ったか

アシスタントは興味のある募集要項があったら以下の情報をまとめて応募締め切りまでに新人と同じ方法で応募します。なお、現時点ではアシスタントはまだ募集しません。何度か実施して慣れてきてから募集する予定です。新人が、将来、アシスタント・先輩になることを期待しています。

  * 名前（GitHubのIDなどOSS Gateオンボーディング内で困らないものであれば本名でなくても構いません。）
  * 対象募集要項
  * 対象OSSとの関わり
  * 応募動機
  * 現時点での自分のOSS開発に関する知識・経験

スポンサー関連の扱いはまだ決まっていません。どのような仕組みだと都合がよいかみえてくるまでは個別に相談させてください。興味のある企業は kou@clear-code.com にメールしてください。

## 進め方

先輩は募集要項にまとめた進め方に沿ってOSS Gateオンボーディングを進めます。

詳細はそれぞれの対象OSSに合わせますが、大きな流れは次のようにします。

  * 作業をした日は新人・アシスタント・先輩は日報を書く
    * 詳細：[日報]({{ site.baseurl }}{% link process/daily-report/index.md %})
  * おおよそ1週間に1回以上は新人・アシスタント・先輩は次の話をする機会を設ける
    * 現状を共有
    * 現状の課題の解決
    * ↑を踏まえた今後の進め方の調整
  * プロジェクトの全体の期間に合わせて定期的に（例えば1ヶ月に1回）新人・アシスタント・先輩は現時点で目的をどれだけ達成しているかをまとめて https://github.com/oss-gate/on-boarding にpushする
  * 支援期間の最終日までに新人・アシスタント・先輩は今回の支援で目的をどれだけ達成したかをまとめて https://github.com/oss-gate/on-boarding にpushする
  * 支援期間がおわったら新人・アシスタント・先輩・運営（とりあえず現時点では須藤）で今回の支援について次の話をする機会を設ける
    * 今回の支援はどうだったか
    * 今回の支援の課題
    * ↑を踏まえて次回の支援で変更するとよさそうなことはなにか
