---
title: 宇宙栽培試行のための栽培ロボット起動記録
tags: 宇宙開発
author: busyoucow
slide: false
license: CC0
copyright: reserved
---

<div class="page"/>

<div class="page"/>

# アブストラクション
この原稿は、秘密結社オープンフォースより供与された栽培ロボット(https://qiita.com/nanbuwks/items/3d807e30e71e893c94eb)を起動し
現在行っている発芽試験に活用を試行する記録である。

# はじめに
粘土…いや年度が変わり能登半島被災地救援活動も一区切りつけた2025年4月初旬、全世界の株式がトランプショックにて大暴落いや乱高下かと大騒ぎな昨今。
年度末に出展したメイカーズスペース長岡の件がひと段落して落ち着いてカフェオレを飲んでいたら、オープンフォース総統(@nanbuwks)より連絡があった。
「次のイベント出展原稿を作成せよ」
それはイベント初日から三日前の出来事であった…

# 栽培ロボット概要
秘密結社オープンフォースより供与された栽培ロボット(https://qiita.com/nanbuwks/items/3d807e30e71e893c94eb)を使用する。

現在はアップデートが行われており基板レイアウト変更や表面実装部品等の事前実装が済んだ状態になっておりその組み立ては
(https://qiita.com/nanbuwks/items/e667d432a697669dcc93)(https://qiita.com/nanbuwks/items/37bffef16036937eecc3)にて解説している…

<img alt="picture 0" src="images/efe6b7dff1452612fae2b9e63ed69f5a6bc48300449121e0939301e1dda3548e.jpg" width="200" />  

…いつものごとくそれらの記事を読んで分かる方々にはこの記事は無用である

# 実際に組み立ててみる

電子部品や電装品は以前執筆した記事(https://github.com/busyoucow/robotWired)にて組み上げたため今回は水の通るパイプをつなげてみた 左手で持っているのが栽培瓶側に入れる給排水パイプと水位センサーである
<img alt="picture 1" src="images/35c5f65881d3e893b5707d72d5a603ecec23db3bf61538367e0af006e13ebe26.jpg" width="200" />  

右手で持っているのがマイコン給電用USB-Cケーブルと給水タンク(今回はペットボトル使用)に入れる給排水パイプである
中央に二つ並ぶモータ付きポンプは(https://qiita.com/nanbuwks/items/37bffef16036937eecc3)にある通り中央軸に近い方が水の出る側、遠い方が水を吸い込む側である 外側にあるポンプが給水ポンプとして使用し内側にあるポンプが排水ポンプとして使用する為パイプの接続には気を付けたい
またパイプを切る長さや配置も気を使い長さが足りなくなったり長すぎて折れてしまわないよう(中心部に1本折れている)気を付けたい
<img alt="picture 2" src="images/d681464151c9f70f829f051132d9e09ce052082671fa7af76c5c589e65ab3e2d.jpg" width="200" />  

実際にはこのように入れて液肥入り水を供給し交換する これで面倒な瓶を傾けての水替え作業ともおさらばか…？
<img alt="picture 3" src="images/73212a4eeb0df54376ddee90319dd2e1e00ddbae02de8ab9556aab5913cc29df.jpg" width="200" />  


# さぁ起動…？

したいところだが、展示会に持参してオープンフォース総統のロボット基板に使ったACアダプター(12V)を回収し忘れたため送って貰った 

しかし ~~郵政省の陰謀~~ 日本郵便の運用判断により当方へ投かんされず保管され欲しい時に間に合わなかった 国内物流の危機を感じる

## 必要な備品が到着し起動試験…

写真には栽培用ボトルが写っているが今回は使用せず

右側の空ペットボトルへと別のボトルから給水できるか起動試験を行った

<img alt="picture 4" src="images/a26e3fd0f8f8454bc80c32bfc851676e41543d406a0ebbdc5af6be72c933962f.jpg" width="200" />  

<img alt="picture 5" src="images/dbe8c18fa7561fb8c7b8076b42f049ab6c0c54974f67232e677809dbad68aa70.jpg" width="200" />  



# 水漏れとの闘い
<img alt="picture 6" src="images/99c223117bc7f58d4e10167f0c99b6dce0d26bf0aa58597cafcbb1ec5acbc0e3.jpg" width="200" />  

<img alt="picture 7" src="images/20527677bd92f0a2c9ce1a89f11c532902ba757c061bf02b5813fd934c7517cf.jpg" width="200" />  

<img alt="picture 8" src="images/58735a308d1779df13bc5f29e6930fcc1c7b07acfaa19f2c76cb6332fcf4c1e4.jpg" width="200" />  

<img alt="picture 9" src="images/6d0d2ad6789999f5dc455fc8e6934113adc9a11590b013b12caa65e45372be62.jpg" width="200" />  


# 終わりに

水と電気は漏電の可能性があるため相性が悪い 今回は未実装だが実際に通水する際にはインシュロックにてパイプ接続部を固定する必要がある
以前オープンフォース総統の栽培ロボットを運用していた際に水漏れが発生して展示会会場が大変な事になったりもした(その経験から基板レイアウトを変更してもらっている)

今後栽培ロボットを活用して水耕栽培試験で大変な作業になる水替えを自動化できるよう願って筆を置くものとする

