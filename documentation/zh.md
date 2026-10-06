<!-- ELUCENIA technical documentation · indice-de-tobin · zh · no clinical/professional/rights approval -->

# Tobin 指数（浅快呼吸指数）

[条件、来源与许可](https://elucenia.org/zh/tools/indice-de-tobin)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 自主呼吸频率

`fr`

次呼吸/分钟 · 范围: 1–80

### 自主潮气量

`vt`

mL · 范围: 50–1500

## 方法版本

RSBI/Yang–Tobin 1991：f/VT，VT用升；不可误用mL

## 已记录的公式

f/VT = 呼吸频率（次/分钟）÷潮气量（L）。

## 限制与适用人群

RSBI作为机械通气脱机尝试结果的预测指标而研究。结果依赖测量条件及技术，不能单独确定气道保护能力或拔管安全性。有利的指数并不等同于保证成功。

## 参考文献

- [Yang KL, Tobin MJ. A prospective study of indexes predicting the outcome of trials of weaning from mechanical ventilation. N Engl J Med, 1991.](https://doi.org/10.1056/NEJM199105233242101)

- [Boles JM et al. Weaning from mechanical ventilation. Eur Respir J, 2007.](https://doi.org/10.1183/09031936.00010206)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

低于105：有利于脱机成功


### 2

105或更高：预测脱机失败


### 3

105或更高：预测脱机失败

