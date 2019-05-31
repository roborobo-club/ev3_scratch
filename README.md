Scratch X EV3 拡張
==================

Scratch X で EV3 を操作する拡張ブロックの日本語化のため、[kaspesla](https://github.com/kaspesla) 氏のリポジトリをフォークしたプロジェクトです。

以前までは日本語化のため拡張ブロック自体を日本語にしていましたが、今は Scratch X 本体の翻訳機能を用いています。



## 使い方
### [推奨] カスタムした Scratch X を使用する方法

ブラウザで [https://ariharananami.github.io/scratchx/?url=https://ariharananami.github.io/ev3_scratch/ev3_scratch.js#scratch](https://ariharananami.github.io/scratchx/?url=https://ariharananami.github.io/ev3_scratch/ev3_scratch.js#scratch) を開きます。Scratch X 自体の言語を日本語にすると、日本語表記で EV3 ブロックを扱えます。また、ひらがな表記にも対応しています。

※ この方法では、[Scratch X 本体側](https://github.com/ariharananami/scratchx) によって英語表記の EV3 ブロックを日本語にしています。Scratch X 本体で日本語化しているため、現在ではこのリポジトリの ev3_scratch.js でなく kaspesla 氏オリジナルの EV3 拡張ブロックを使用しても動作に変わりはありません。


### 拡張ブロックを直接日本語にする方法

ブラウザで [http://scratchx.org/?url=https://ariharananami.github.io/ev3_scratch/ev3_scratch_ja.js](http://scratchx.org/?url=https://ariharananami.github.io/ev3_scratch/ev3_scratch_ja.js) を開くことで日本語化された EV3 ブロックを使用することができます。

この方法では ev3_scratch_ja.js を使用していることに注意してください。拡張ブロックを直接書き換えた  ev3_scratch_ja.js を使用するため、Scratch X 本体は公式の scratchx.org でも日本語表記に出来ます。



## 環境

kaspesla 氏オリジナルの EV3 拡張ブロックが動く環境で、本拡張ブロックも動きます。対応は保証できませんが、きちんとしたテストは行っていないので、日本語化に伴うバグなどを発見したら Pull Request や Issue のほどお願いします。
