---
title: "Obsidian Syncを使いつつGit連携するときのメモ"
emoji: "🦔"
type: "idea" # tech: 技術記事 / idea: アイデア
topics: ["obsidian", "plugin", "GitHub"]
published: false
---

## はじめに

最近ノート系のアプリケーションを片っ端から触っていました。

- Notion
- Heptabase
- Inkdrop

などなど...

中でもObsidianを触っていて「これだ！」と感じ、思い切ってObsidian Sync(他端末と同期するため)を契約しました。
Obsidian Syncを使わずとも同期は可能ですが、iPhone, iPadとの連携をよりスムーズにしたい＆色々ラクしたくなり試しに契約したところ、とても快適で満足しています。

## Git連携しつつObsidian Syncも使いたい

Obsidianの数あるプラグインのうち、Git連携でObsidianのデータをリポジトリで管理できるものがあります。
Git連携しつつObsidian Syncを使っている人はあまりいないのかもしれませんが（記事が見当たらなかった）作業手順を残します。

前提条件としては以下です

- Obsidian Git pluginの設定が済んでいること
- GitHubにObsidian用のリポジトリが存在していること

### 手順

1. リポジトリをCloneしておく

2. Obsidian Syncから保管庫を開く
![alt text](/images/try-obsidian-sync-and-git-relation/Obsidian-2025-02-16-19.01.12@2x.png)

3. vaultを接続（Obsidian Syncの設定が済んでいない場合は設定してください）
![alt text](/images/try-obsidian-sync-and-git-relation/Obsidian-2025-02-16-19.02.40.png)

4.ロケーションにリポジトリを指定してvaultの名称を設定し、作成します
![alt text](/images/try-obsidian-sync-and-git-relation/Obsidian-2025-02-16-19.03.07.png)

これで完了です。Git pluginが使えることを確認しましょう。

## さいごに

新しい環境でセットアップする際、初手Syncから開いてしまい「あれ、Git連携どうやるんだっけな。。」となったためメモとして残しました。
