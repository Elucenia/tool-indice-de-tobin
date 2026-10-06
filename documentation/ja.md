<!-- ELUCENIA technical documentation · indice-de-tobin · ja · no clinical/professional/rights approval -->

# Tobin指数（浅速呼吸指数）

[条件・出典・許諾](https://elucenia.org/ja/tools/indice-de-tobin)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 自発呼吸数

`fr`

呼吸/分 · 範囲: 1–80

### 自発1回換気量

`vt`

mL · 範囲: 50–1500

## 方法の版

RSBI/Yang–Tobin 1991：f/VT、VTはL；mLと混同しない

## 記載された計算式

f/VT = 呼吸数（回/分）÷一回換気量（L）。

## 限界・対象集団

RSBIは、人工呼吸からの離脱試行の結果を予測する指標として研究されました。結果は測定の条件と手技に依存し、単独では気道保護能力や抜管の安全性を確定しません。良好な指数は、成功が保証されることと同等ではありません。

## 参考文献

- [Yang KL, Tobin MJ. A prospective study of indexes predicting the outcome of trials of weaning from mechanical ventilation. N Engl J Med, 1991.](https://doi.org/10.1056/NEJM199105233242101)

- [Boles JM et al. Weaning from mechanical ventilation. Eur Respir J, 2007.](https://doi.org/10.1183/09031936.00010206)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 記録された結果

以下の情報は、合成例に対する手法の出力を保持したものです。独立した臨床的検証を示すものではありません。

### 1

105未満：離脱成功を支持する


### 2

105以上：離脱失敗を予測する


### 3

105以上：離脱失敗を予測する

