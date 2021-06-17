# rktabot
陸上会計予定通知アプリ(Rikujo-Kaikeiyotei-Tsuchi-App:RKTA)

# 機能
- アプリ利用者で予定を追加・管理
- アドミンユーザを共有して予定を管理
  - 利用者は身内のみであったため，この点に関するセキュリティリスクは低い
- 予定が近づいてくるとLINEで通知が来る．
- LINEユーザごとに通知の設定が可能（LINEでカルーセル上のボタンを押すことで設定可能）
  - 定期的な予定通知を受け取るかどうか．（毎週月曜日の朝に通知）
  - 普通の予定（大会の予定など）を受け取るかどうか
  - 会計の予定を受け取るかどうか
- その他，お遊び機能

# 使用技術
- DJango (Python)
- HTML
- Javascript
- css
- LINE bot API
