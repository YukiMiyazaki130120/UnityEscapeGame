# UnityEscapeGame
Unityで脱出ゲームを作成
[全体の流れ]
・Room1でヒント1を拾える
→「969に注目(時計を見ろ)」というヒントでクローバーの鍵を取るためのヒント
(ただし、はしごがないとクローバーの鍵は取ることができない)

・Room2ではロッカーと棚がある
→ロッカーでは「3251」で開く。中にはしごがある
→棚では「仲間外れを探せ」というヒントのもと、日本語の本を探して開くとクローバーの鍵が手に入る

・Room3ではヒント2の紙と最後のドアが存在する
→ヒント2は音階に応じて数字が割り当てられている。
→上がクローバー、下がダイヤの鍵を入れると開けられるようにしてある
これで終わりかと思いきや最後にヒント2のパスコードを入力させる。

・Room4では花の書かれた丸い空間と時計が存在する。その下には「Locker number is WYPG」と書いてある
→花の色に対してその数をロッカーの数字に割り当てている(つまり3251)

[これから追加したい機能]
・点数機能の追加(時間が短いほど点数が高くなる)
(画面の上の方に空間があるので、そこにタイムカウンターを常に表示しておく)

・タイトル画面の追加・Ending画面からタイトル画面への遷移
