# React 公式の勉強

https://react.dev/

## つまづきポイント

### 1.最初のnpm startでエラー
まずnpm startでエラーが出た<br>
エラー文：`react must be in scope when using jsx`<br>

Eslintが問題らしいが解決できず。<br>
`import React from "react";`を行頭に追記することで解決したが、古い記述方なので使用せずに解決したい<br>

### 2.<></>でエラー
この質問とまったく同じ状況になった。<br>
https://stackoverflow.com/questions/75368559/unexpected-token-at-of-a<br>
`<div></div>`で対応中
