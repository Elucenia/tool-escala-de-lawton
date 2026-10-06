<!-- ELUCENIA technical documentation · escala-de-lawton · zh · no clinical/professional/rights approval -->

# Lawton-Brody 量表（工具性日常生活活动）

[条件、来源与许可](https://elucenia.org/zh/tools/escala-de-lawton)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 电话

`tel`

- `a` — 主动使用电话（查找并拨打号码）
- `b` — 可拨打部分熟悉号码
- `c` — 可接听，但不能拨号
- `d` — 不使用电话

### 购物

`compras`

- `a` — 可独自完成所有购物
- `b` — 仅能独自完成少量购物
- `c` — 任何购物均需陪同
- `d` — 无法购物

### 准备餐食

`comida`

- `a` — 可独自计划、准备并提供适当膳食
- `b` — 提供食材后可准备饭菜
- `c` — 可加热并提供现成饭菜，但膳食不适当
- `d` — 需他人准备并提供饭菜

### 家务

`casa`

- `a` — 可独自做家务，或仅在重体力家务中偶尔需要帮助
- `b` — 可做轻家务（洗碗、整理床铺）
- `c` — 可做轻家务，但不能保持适当清洁
- `d` — 所有家务均需帮助
- `e` — 不参与任何家务

### 洗衣

`roupa`

- `a` — 可洗所有个人衣物
- `b` — 可洗小件衣物
- `c` — 所有衣物均由他人清洗

### 交通出行

`transp`

- `a` — 可独自乘坐公共交通或驾车
- `b` — 可独自乘出租车或网约车，但不使用公共交通
- `c` — 需陪同才能乘坐公共交通
- `d` — 仅能在他人帮助下乘出租车或汽车
- `e` — 不外出

### 用药

`remedio`

- `a` — 可独自按正确剂量和时间服药
- `b` — 他人预先分好剂量后可服药
- `c` — 无法独自服药

### 财务管理

`dinheiro`

- `a` — 可独自管理财务
- `b` — 可完成日常购物，但银行事务和大额购物需帮助
- `c` — 无法处理金钱事务

## 方法版本

Lawton–Brody 1969：本地8领域改编，各0–1，总分0–8适用两性；不是原始按性别版

## 已记录的公式

按所述等级，每项1分（独立）或0分（依赖）：

电话：前三等级1分。

购物、备餐：仅首等级1分。

家务：除“不参与”外均1分。

洗衣：前两等级1分。

交通：前三等级1分。

用药：仅首等级1分。

财务：前两等级1分。

总分0（依赖）至8（独立）。

## 限制与适用人群

本Lawton版本评估八项工具性日常生活活动，按HIGN 2019指导对所有性别使用0至8分总分；不采用过去男性仅计五项的评分。所查指导不建议对入住机构的老年人使用该工具。本人或知情者的回答反映感知功能，并不证明每项任务的实际完成能力；可能高估或低估能力，且无法发现细微变化。请记录回答者和评估背景。

## 参考文献

- [Lawton MP, Brody EM. Assessment of older people: self-maintaining and instrumental activities of daily living. Gerontologist, 1969.](https://doi.org/10.1093/geront/9.3_Part_1.179)

- [HIGN,TryThis23,revised2019](https://hign.org/sites/default/files/2020-06/Try_This_General_Assessment_23.pdf)

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

工具性日常活动独立


### 2

3 项活动依赖：购物、用药、财务


### 3

6 项活动依赖：购物、备餐、家务、洗衣、交通、用药

