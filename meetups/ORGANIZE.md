# Meetup organize workflow

毎月第１火曜日に開催するRepro Tech Meetupにおける開催までの流れをまとめる。
本templateを元に実施のissueを作成し、進捗を管理する。

# Template

## Prepare contents

- [ ] AI, CRE, DBなどテーマのcategoryを決定
- [ ] どのようなことについて話すか詳細案PR(`meetups/<num>/connpass.md`)作成し、関連メンバーで詳細を詰める
- [ ] 社外の有識者およびReproそれぞれから１名以上のspeakerのattend
- [ ] speakerへTwitterのbio程度の文章量の自己紹介文作成を依頼
- [ ] trelloにてdesignerへevent banner(660*270px)の作成依頼。このとき、design imageがつくよう背景知識も共有する。
- [ ] 必要に応じてスピーカーの都合に合わせ開催日を調整し、開催日を確定

Repro外の開場を手配する場合は、以下の点を確認しておくこと

- 最大の座席数
- マイク・プロジェクターの数などの設備
- wifi ssid/pwやアナウンス用のホワイトボード
- 受付用のテーブルの有無や配置
- 音響設備およびその接続
- 入館手続き
- お酒の搬入時間およびその経路
- フードの搬入時間およびその経路
- 入館が厳しい場合、フードの搬入対応をお願いすること可能化
- 準備開始可能時間および完全撤収時間
- その他制約があればヒアリング

## Publish Event

最低でも開催3W前に公開すること

- [ ] speakerより自己紹介文を回収
- [ ] connpassへ公開準備を行い、speakerに最終チェックを依頼。期間は1日程度設ける。
- [ ] 必要に応じてspeaker陣で目的やテーマについての意識合わせ、開催に伴う懸念点の払拭を目的としたkick-off (15min) on video chatを開催する
- [ ] [Repro Tech connpass](https://repro-tech.connpass.com/)の公開

## Promotion

- [ ] announce.md, meetup.md, wantedly.mdなどのプロモーション資料の準備
- [ ] [Repro meetup group event](https://www.meetup.com/reproio/)
- [ ] [Repro wantedly feed](https://www.wantedly.com/companies/repro/feed)
- [ ] [Repro linkedin](https://www.linkedin.com/company/repro-inc-/)
- [ ] [Repro facebook group event](https://www.facebook.com/pg/reproio/events/)
- [ ] [Repro connpass group message](https://repro.connpass.com/)
- [ ] PR担当にtrelloより依頼 / [Repro facebook group](https://www.facebook.com/reproio/), Repro slack, [reproio twitter](https://twitter.com/reproio?lang=en)
- [ ] Speakerにtwitter, facebookなどのSNSでの拡散

## 1 week before

- [ ] LT枠が埋まっていなかったら知り合いに打診
- [ ] 必要に応じてconnpassの増枠
- [ ] LTを含むSpeakerよりタイトルを受領
- [ ] 各種SNS feedより再度告知
- [ ] 前回のKPTも活かしたintrocution, closing資料の準備

LTを含むSpeakerよりタイトルを受領

```
イベント開催が迫ってまいりましたので、そろそろ発表タイトルを公開したいなぁと思っています✨

仮でも構いませんので、タイトルを共有頂けたら嬉しいです🙏
```


## 1 day before

- [ ] Repro以外の会場の場合、以下をpackingする
    - novelty
        - Repro ステッカー * 100-200枚
        - Repro Tシャツ S*1, M*2, L*2, XL*1
    - (option)Route Announce
        - 道案内用の紙 * 1-2
        - 譜面スタンド
    - Acceptance
        - Reproテーブルクロス * 1枚
        - クロス固定用洗濯ばさみ * 1set
        - 8口電源タップ * 1個
        - name strap(はがきサイズ) * 100個
        - name card(はがきサイズ) * 100枚
        - サインペン * 5本
    - LT
        - タイムキープ用キッチンタイマー
        - 残り時間表示用のプラカード(1,2,3,5 min to end)
    - party
        - 太めのサインペン * 1本
        - 養生テープ * 1 roll
        - 45Lゴミ袋 * 1 set
        - ウェットティッシュ * 1 set
    - Sound
        - chrome cast audio(先方の音響設備利用するとき) * 1
        - google home(音響設備がないとき用) * 1
- 在庫状況に応じて以下を発注
    - [ ] ビール、チューハイ、ハイボールなどの飲み物の発注
        - 必要なお酒ケース数 = `開催1日前の申込者数 * 当日キャンセルしない率 0.9 * 実参加率 0.7 * 一人あたりの平均消費缶 1.8 / 24`
        - 注文比率: `(ビール : チューハイ : ハイボール(オプション)) = (3 : 1 : 1)`
        - ソフトドリンクは烏龍茶を1boxのみ
    - [ ] 乾き物の発注
        - 柿ピーなど小袋のものを数種(ノーマル柿ピー & わさび柿ピー)を合計申し込み者数分
- スタッフ分担(優先度順)
    - [ ] 会のファシリテート(質問、タイムキープ) * 1名
        - 場合によっては分担する
    - [ ] アテンド * 1-2名
    - [ ] 会場誘導・登壇者のサポート・フード発注・展開 * 1名
        - 会場の広さによっては会場誘導にもう1名必要となる可能性がある
    - [ ] (option) 実況およびTwitter Timeline表示担当
- [ ] connpassより以下メッセージを送る

```txt
subject: Repro Tech Meetup #<num> <theme>
To: Event Admins, Presenter, Attendees, Waitlist
Body:
この度はRepro Tech Meetupへご応募頂きありがとうございます！
開始スケジュールや場所は以下のとおりです。

## 開場・開始

開場: 19:00
スタート: 19:30

## 場所

東京都渋谷区代々木1丁目36-4 全理連ビル 6階
google map: https://goo.gl/maps/t7NtRv4rUv92

LTされる方はテーマをconnpass feedに投稿いただけると嬉しいです。

それではイベントでお会い出来ることを楽しみにしています✨
```

## イベント当日の作業

カクヤスより飲み物受け取りのため、社外の会場でイベントをする場合は1h前(18:00)より以下の作業を行う
なお、スタッフはなるべく散らばって座ること。

- 会場設営(開場1h前, Reproの場合は30min前)
    - (option) 道案内スタンドの設置
    - 受付
        - 長テーブルの配置
        - クロス、stickerの配置
        - 受付デスクもしくは近くテーブルにビールやおつまみの配置
        - ネームカードと用紙および記述スペースの確保
    - ネームカードへの記述内容
        - handle and name
        - 好きなこと
        - 名刺も挟んでもらう
    - 音響設備
        - wifiへchrome cast audioを接続し、chrome cast audioより音楽を流す
    - 座席
        - 背中を向けて座らない & 座席の間が空き過ぎないようにする。ただし、この作業は原状復帰までの時間が十分に確保できるときに限る
    - アナウンス
        - 設営完了後、その状態をSNSに拡散し開場していることを知らせる
    - (Option) Timeline
        - 複数ディスプレイもしくはプロジェクターを利用可能な場合は、TwitterなどのタイムラインおよびWifi SSID/PW, Hashtagを表示
- LT準備
    - キッチンタイマーの案内
    - 登壇者・LT社については接続確認の案内
- アテンド
    - connpass ID もしくは名前を確認し、connpass上のアテンドをする
    - connpass未申し込み者は、その場で申し込んでもらう
    - stickerやお酒を案内
    - 奥から詰めて座ってもらうよう案内
- 開始
    - 必要に応じて開始を5-10min遅らせる
    - 実参加人数に合わせ、ピザを発注 (5-7名/枚)
- セッション開始
    - キッチンタイマーによる登壇者自身のtime keep
    - スタッフ側もでのtime keepも実施。必要に応じてプラカードによる通知
    - 時間が大きく押し気味の場合は、前半の部終了後の休憩時間(ask me anything 的な時間) or 全発表終了後の懇親会にてやってもらう
- 懇親前
    - Tシャツプレセント大会
    - 会場参加者の力を借りてピザとお酒を展開

## イベント終了後

- [ ] 主催にてKPTの実施し、次回の改善点を決定

# Other Tips

### キッチンタイマー

登壇者は、お酒を入れていると特にプレートを見ない。
通知が音の場合発表の妨げとなるため、光もしくは振動で知らせることのできるタイマーが望ましい。

e.g.

- https://www.amazon.co.jp/dp/b01mg33zdb/
- https://www.amazon.co.jp/dp/b06zzr2f4y/

### ネームカード

名札を準備して、互いに名前もしくはハンドルがわかるようにする。
なお、サイズは名前やhandleは大きく表示されていることが望ましいため、はがきサイズを推奨。

必要に応じて[サービス](https://yoshiko-pg.github.io/your-name/)を利用することで、参加者のネームカードを自動生成することもできる。

[ペーパーリストバンド](https://www.askul.co.jp/v/83133/) を利用したロール表示も良い。


