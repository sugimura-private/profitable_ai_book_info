# まえがき
# 1 業務と機械学習プロジェクト
## 1.1 本書の目的
## 1.2 必要な専門性と本書の対象読者
## 1.3 機械学習の開発プロセス
## 1.4 これからの業務専門家に望ましいスキル
## 1.5 本書の構成

# 2 機械学習モデルの処理パターン
## 2.1 AIと機械学習の関係
## 2.2 機械学習の三つの処理パターン
## 2.3 教師あり学習の処理パターン
### 2.3.1 分類
### 2.3.2 回帰
### 2.3.3 時系列分析
## 2.4 教師なし学習の処理パターン
### 2.4.1 アソシエーション分析
### 2.4.2 クラスタリング
### 2.4.3 次元圧縮
## 2.5 処理パターンの選択フロー
## 2.6 ディープラーニングと構造化データ・非構造化データ

# 3 機械学習モデルの開発手順
## 3.1 モデルの開発フロー
## 3.2 例題データ・目的の説明
### 3.2.1 例題データの説明
### 3.2.2 モデルの目的
## 3.3 モデルの実装
### 3.3.1 (1) データ読み込み
### 3.3.2 (2) データ確認
### 3.3.3 (3) データ前処理
### 3.3.4 (4) データ分離
### 3.3.5 (5) アルゴリズム選択
### 3.3.6 (6) 学習
### 3.3.7 (7) 予測
### 3.3.8 (8) 評価
### 3.3.9 (9) チューニング
### コラム 公開データセットについて

# 4 機械学習モデル開発の重要ポイント

## 4.1 データ確認
### 4.1.1 数値的・統計的に分析する方法
### 4.1.2 視覚的に分析・確認する方法
## 4.2 データ前処理
### 4.2.1 不要な項目の削除
### 4.2.2 欠損値の対応
### 4.2.3 2値ラベルの数値化
### 4.2.4 多値ラベルの数値化
### 4.2.5 正規化
### 4.2.6 その他のデータ前処理

## 4.3 アルゴリズム選択
### 4.3.1 分類の代表的なアルゴリズムとその特徴
### 4.3.2 サンプルコードで用いるデータ
### 4.3.3 ロジスティック回帰
### 4.3.4 サポートベクターマシン(カーネル)
### 4.3.5 ニューラルネットワーク
### 4.3.6 決定木
### 4.3.7 ランダムフォレスト
### 4.3.8 XGBoost
### 4.3.9 アルゴリズムの選択方法

## 4.4 評価
### 4.4.1 混同行列
### 4.4.2 精度・適合率・再現率・F値
### 4.4.3 確率値と閾値
### 4.4.4 PR曲線とROC曲線
### 4.4.5 入力項目の重要度
### 4.4.6 回帰のモデルの評価方法

## 4.5 チューニング
### 4.5.1 アルゴリズムの選択
### 4.5.2 ハイパーパラメータの最適化
### 4.5.3 交差検定法
### 4.5.4 グリッドサーチ
### 4.5.5 その他のチューニング

# 5 業務要件と処理パターン
## 5.1 営業成約予測 (分類)
### 5.1.1 処理パターンと想定される業務利用シーン
### 5.1.2 例題のデータ説明とユースケース
### 5.1.3 モデルの概要
### 5.1.4 データ読み込みからデータ確認まで
### 5.1.5 データ前処理とデータ分割
### 5.1.6 アルゴリズム選択
### 5.1.7 学習・予測・評価
### 5.1.8 チューニング
### 5.1.9 重要度分析
### コラム 欠陥・疾患判定モデルの実現について

## 5.2 天候による売り上げ予測 (回帰)
### 5.2.1 処理パターンと想定される業務利用シーン
### 5.2.2 例題のデータ説明とユースケース
### 5.2.3 モデルの概要
### 5.2.4 データ読み込みからデータ確認まで
### 5.2.5 データ前処理とデータ分割
### 5.2.6 アルゴリズム選択
### 5.2.7 学習・予測
### 5.2.8 評価
### 5.2.9 チューニング
### 5.2.10 重要度分析

## 5.3 季節などの周期性で売り上げ予測 (時系列分析)
### 5.3.1 処理パターンと想定される業務利用シーン
### 5.3.2 例題のデータ説明とユースケース
### 5.3.3 モデルの概要
### 5.3.4 データ読み込みからデータ確認まで
### 5.3.5 データ前処理とデータ分割
### 5.3.6 アルゴリズム選択
### 5.3.7 学習・予測
### 5.3.8 評価
### 5.3.9 チューニング(ステップ1)
### 5.3.10 チューニング(ステップ2)
### 5.3.11 「回帰」「時系列」の処理パターンの選択
### コラム「アイスクリーム購買予測」で時系列分析

## 5.4 お薦め商品の提案 (アソシエーション分析)
### 5.4.1 処理パターンと想定される業務利用シーン
### 5.4.2 例題のデータ説明とユースケース
### 5.4.3 モデルの概要
### 5.4.4 データ読み込みからデータ確認まで
### 5.4.5 データ前処理
### 5.4.6 アルゴリズムの選択と分析
### 5.4.7 チューニング
### 5.4.8 関係グラフの視覚化
### 5.4.9 より発展した分析
### コラム　「おむつとビール」の都市伝説
## 5.5 顧客層に応じた販売戦略 (クラスタリング、次元圧縮)
### 5.5.1 処理パターンと想定される業務利用シーン
### 5.5.2 例題のデータ説明とユースケース
### 5.5.3 モデルの概要
### 5.5.4 データ読み込みからデータ確認まで
### 5.5.5 クラスタリングの実施
### 5.5.6 クラスタリング結果の分析
### 5.5.7 次元圧縮の実施
### 5.5.8 次元圧縮の活用方法

 
# 6 AIプロジェクトを成功させる上流工程のツボ
## 6.1 機械学習の適用領域の選択
### 6.1.1 処理パターンのあてはめが肝要
### 6.1.2 教師あり学習は正解データの入手が命
### 6.1.3 AIに100%は期待するな
## 6.2 業務データの入手・確認
### 6.2.1 データの所在確認
### 6.2.2 部門を跨がるデータ連係の課題
### 6.2.3 データの品質
### 6.2.4 One-Hotエンコーディングの問題
### コラム 機械学習モデルの自動構築ツールについて



# 講座1 Google Colaboratory 基本操作

# 講座2 機械学習のためのPython入門
## 講座2.1 NumPy入門
## 講座2.2 pandas入門
## 講座2.3 matplotlib入門

## 索引

[メインページに戻る](../README.md)

