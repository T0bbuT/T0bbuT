# T0bbuT

データ分析・データ基盤まわりの仕事をしています。
データを取ってきて、整えて、使える形で渡すものを作るのが好きです。

## データ基盤
- [snowflake-dwh-lab](https://github.com/T0bbuT/snowflake-dwh-lab) — Snowflakeでメダリオン構成のDWHを構築。品質チェックとロード制御つき

## 機械学習・予測
- [signate_apple_hikkosi_analysis](https://github.com/T0bbuT/signate_apple_hikkosi_analysis) — 引越し件数の日次予測。右肩上がりの需要では木モデルが外挿できないことをEDAで確かめ、Prophetでトレンドを除いた残差を勾配ブースティングで学習する2段構成に。年単位の時系列CVで MAE 6.18件。[ノートブックを見る](https://t0bbut.github.io/signate_apple_hikkosi_analysis/EDA.html)
- [kaggle_house_price](https://github.com/T0bbuT/kaggle_house_price) — 住宅価格の回帰。線形モデル向けに分布を整え、コンペの指標に揃えたCVでOptuna調整。Lasso（CV RMSE 0.111、価格誤差 約8%）がLightGBMを上回った。GitHub Actionsでノートブックの再現性を検証

## ツール
- [ugohen](https://github.com/T0bbuT/ugohen) — pixivのうごイラを端末内でMP4/GIFに変換。[配布ページ](https://t0bbut.github.io/ugohen/)
- [irodrop](https://github.com/T0bbuT/irodrop) — 画像から色を拾うWebアプリ
- [ba-student-kuji](https://github.com/T0bbuT/ba-student-kuji) — ブルーアーカイブの生徒をランダムに表示する二次創作ネタ出し用ツール（非公式）。[アプリを開く](https://t0bbut.github.io/ba-student-kuji/)

## よく使うもの
Snowflake / SQL / Python（polars・pandas・scikit-learn・LightGBM）/ Tableau / JavaScript
