﻿# Bonanse 


Bonanzaをベースに作った接待将棋用のプログラムです。
USIプロトコルに対応しておりhttp://www.geocities.jp/shogi_depot/doc/bonanza_usi.htm を参考に実装しています。
バイナリは近いうちに作るつもりです。
Bonanzaのfv.binとbook.bin、flip.csa、game.csaが必要です。
Bonanzaのページからダウンロードしてください。


[LevelControl.txtの書き方]

スペースで区切って数字を3つ書いてください。左から

限界値 ブレ幅 ステップ幅

(例1) 評価値0に近いものを選ぶ
0 0 0

(例2) 評価値-500に近いものを選ぶ
-500 0 0

(例3) 評価値100±200(ランダム)に近いものを選ぶ
100 400 0

(例4) 評価値-500以上なら最大で評価値100だけ間違える
-500 0 100

(例5 = デフォルト) 評価値-1200±150(ランダム)以上なら最大で評価値300だけ間違える
-1200 300 300

なお、ステップ幅を使用する場合はブレ幅も同じくらいに設定してください


[バージョン]

Version 1.0.1
プログラム名を変更

Version 1.0.0
初版