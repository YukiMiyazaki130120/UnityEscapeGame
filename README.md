# UnityEscapeGame<br>
Unityで脱出ゲームを作成<br>

### 開発経緯
開発可能なものの幅を広げるため，大学同期を誘って共同開発  
少し凝ったものを作りたいと思い，**自作アセットでモノクロな世界観**を作成

### 制作物

<img width="342" alt="スクリーンショット 2024-05-04 0 49 34" src="https://github.com/user-attachments/assets/2186a354-1772-4204-a3f3-148cc5ba4420">

### 学んだこと
- オブジェクトの表示・非表示管理
- 自作アセットの活用方法
- SEの付与
- 画面遷移・管理方法

### [全体の流れ]
・Room1でヒント1を拾える<br>
→「969に注目(時計を見ろ)」というヒントでクローバーの鍵を取るためのヒント<br>
(ただし、はしごがないとクローバーの鍵は取ることができない)<br>
<br>
・Room2ではロッカーと棚がある<br>
→ロッカーでは「3251」で開く。中にはしごがある<br>
→棚では「仲間外れを探せ」というヒントのもと、日本語の本を探して開くとクローバーの鍵が手に入る<br>
<br>
・Room3ではヒント2の紙と最後のドアが存在する<br>
→ヒント2は音階に応じて数字が割り当てられている。<br>
→上がクローバー、下がダイヤの鍵を入れると開けられるようにしてある<br>
これで終わりかと思いきや最後にヒント2のパスコードを入力させる。<br>
<br>
・Room4では花の書かれた丸い空間と時計が存在する。その下には「Locker number is WYPG」と書いてある<br>
→花の色に対してその数をロッカーの数字に割り当てている(つまり3251)<br>
<br>
[これから追加したい機能]<br>
・サウンド機能の追加(素材はここが良いかも →「https://soundeffect-lab.info/」)<br>
  a.ゲーム中にずっと流れるBGMを流す(これとか良い雰囲気 →「[https://dova-s.jp/bgm/play17203.html](https://www.youtube.com/watch?v=v0lkdYsHQgg&list=PLiHL1bG4u2mTZ2R4Szc8st8L4rkS61fCQ&index=1)」)<br>
  b.ドアの開閉音<br>
  c.本の開閉音<br>
  d.物を見つけた時の気持ちの良いSE(鍵・ヒント・はしごなど)<br>
  e.物を取得した時の音<br>
  f.鍵を開ける時のSE(ドア・鍵)<br>
  g.ダイヤル式のロッカーをカチャカチャさせる音<br>
  h.はしごを置けた時のSE<br>
  i.カーソルを押して部屋移動をした時のSE<br>
  <br>
・点数機能の追加(時間が短いほど点数が高くなる)<br>
(画面の上の方に空間があるので、そこにタイムカウンターを常に表示しておく)<br>
<br>
・タイトル画面の追加・Ending画面からタイトル画面への遷移<br>
