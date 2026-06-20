# KYOTO CITY 3D

## 概要

京都駅・京都タワー・東寺・水族館・鴨川・御所・八坂神社・清水寺などを巡れる3D都市シミュレーターです。

## 操作方法

- ドラッグで視点回転
- ピンチ/ホイールでズーム
- スティックで移動
- 「街を歩く」で一人称視点モード
- 観光地ボタンで各スポットへ移動
- 時間スライダーで昼夜変更

## 特徴

- Three.jsによる3D描画
- 京都の主要スポットを配置
- 昼夜サイクル
- 車・新幹線・歩行者の移動
- スマホ操作対応

## 公開URL

https://mypaceotoko.github.io/kyoto-city-simulator/

## GitHub Pages での公開

このリポジトリは `index.html` のみで動作する静的HTMLサイトです。React/Vite/Next.js などのビルド工程や `package.json` は不要です。

GitHub Pages では、リポジトリの **Settings > Pages** から Source を `Deploy from a branch`、Branch を `main`、Folder を `/ (root)` に設定してください。

## ライセンス

MIT License

## 更新メモ

- 京都御所・京都御苑、清水寺、八坂神社・祇園エリアのランドマーク造形と周辺街並みを強化しました。
- 築地塀、門、砂利庭、懸造りの柱、三重塔、朱塗り社殿、提灯、町家店舗、参道、樹林、街灯などを追加し、京都駅周辺に近い密度感を目指しています。
- 繰り返しの樹木や街並みは軽量な低ポリゴン形状・一部 InstancedMesh を活用し、GitHub Pages でそのまま動く単一 HTML 構成を維持しています。
