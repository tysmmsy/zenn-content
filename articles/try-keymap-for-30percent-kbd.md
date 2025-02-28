---
title: "[自作キーボード] 30%キーボードのキーマップについて"
emoji: "⌨"
type: "idea" # tech: 技術記事 / idea: アイデア
topics: ["自作キーボード", "keyboard", "キーマップ", "キー配列"]
published: true
---

※この記事は[しずかなインターネット](https://sizu.me/dawne/posts/b5akh175kv72)に投稿したものを加筆修正したものです

# 30%キーボードなんて自分には縁のない話だ

と自作キーボード沼に足を踏み入れた頃は思っていました。

%にフォーカスしたキーボードの変遷を紹介すると

- 60% → 40% → 40%を30%にして修行 → 30%(36キー)

で落ち着きました。

60%から入沼して自然と40％台になりましたが、30%に突入する前は一定期間トレーニングしています。(30%の使いたいキーボードがあったため)

# キーマップの煮詰め方、考え方について影響を受けた記事

https://salicylic-acid3.hatenablog.com/entry/via-keymap-setup

今では変えることのできない

- 親指スペース/エンター
- Lの横にハイフンを配置
- 数字キーの配置

を学んだ最初の記事。初自作キーボードの[7sPro](https://shop.yushakobo.jp/products/7spro?srsltid=AfmBOorSQBS7k_kbEgS9AIcOzvrs3VY3v4lgw-yT_iElM1cCyZJ_K0Yz)を携えてうんうんと唸りつつ自分に合うキーマップを探っていました。

https://docs.dailycraft.jp/keyboards/claw44/keymap.html

40%キーボードを使いはじめてから[Daily Craft Keyboard](https://shop.dailycraft.jp/)さんの記事を読んで

- どのレイヤーに何の役割を持たせるか
- 記号のグルーピング（左右対称で記号を配置 など）

を学び、このあたりで手に馴染むキーマップの考え方を確立しました。

# 36キー キーマップの紹介

仕事柄コーディングの機会が多く、Ctrl/Tab/Shiftといった修飾キーや記号キーを意識せず打てるか に重きを置いています。(Windows JIS配列設定をメインで使っています)

30%トレーニング中はかなり違和感がありましたが、結局慣れということで今ではしっくりきています。

キーマップ編集にはVialを使っていますが、主にLayer/Toggle機能しか使っていません(TapDanceの活用例を教えていただけると嬉しいです)

## レイヤー0 (アルファベット)

![alt text](/images/try-keymap-for-30percent-kbd/layer-0.webp)

レイヤー0はアルファベットレイヤーです
アルファベット部にはToggle等を仕込まず、そのまま配置することを重視しています。
というのも私のケースでは色々やろうとした結果、タイプミスが増えてしまったためです。
トラックボール付きの自作を使っていた時は”A長押しでマウスボタンレイヤーに移る”を付与していました。

## レイヤー1 (記号)

![alt text](/images/try-keymap-for-30percent-kbd/layer-1.webp)
レイヤー1は記号レイヤーです
前述した記号のグルーピングに沿って左右対称に配置。Esc/Tabも同じタイミングで使う機会が多いためここに置いています。

## レイヤー2 (移動/数字)

![alt text](/images/try-keymap-for-30percent-kbd/layer-2.webp)
レイヤー2は移動/数字レイヤーです
数字キーの配置には当時「なるほど そうすればよかったんだ…」と感動した記憶があります。コピペも一緒に使いたいことがあるためスキマに配置しています。

## レイヤー3 (ファンクション/メディア)

![alt text](/images/try-keymap-for-30percent-kbd/layer-3.webp)
レイヤー3はファンクション/メディアレイヤーです
画面共有するときに拡大したいシーンがあるためセットで配置したりしています。右側のファンクションは置いているもののF11, 12あたりしか使っていないため練り直す余地があります。

# 終わりに

40%でゴールかと思いましたが、30%試行錯誤中の「ここをこうすればイケそう」「これならもっとキー数減らせる」に達成感があり、とても楽しかったです。

毎回キー数を減らす度に「これ以上減ることはない」と思っていますが、さすがにここがゴールかと思い記事にしました。
