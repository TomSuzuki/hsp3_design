# 同名メソッド 弾幕
ファイル一つのサンプルより若干複雑です。
描画をきれいにするために`a2d`を使用しています。
弾処理の説明なので、不要なものは省いています。

## ファイルについて
- `main.hsp` ...このファイルから実行します。
- `game.hsp` ...ゲームを制御します。
- `common.hsp` ...その他の関数です。
- `bulletInterface.hsp` ...弾の制御を行う基盤モジュール。
- `bulletType1.hsp`, `bulletType2.hsp`, `bulletType3.hsp` ...弾の実装モジュール。

## メモ
- プログラム上に数値が多いですが、定義ファイルを作って`#const`などを使用すると書き換えが簡単にできます。
- 円の塗りつぶし処理は多分重いので、バッファからコピーのほうがいいと思う。
