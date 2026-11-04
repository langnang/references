# JavaScript 类型转换 {docsify-ignore-all}

## JavaScript 类型转换表

下表显示了将不同的 JavaScript 值转换为 Number、String 和 Boolean 的结果：

| 原始值             | 转换为数字 | 转换为字符串        | 转换为布尔值 |
| ------------------ | ---------- | ------------------- | ------------ |
| false              | 0          | "false"             | false        |
| true               | 1          | "true"              | true         |
| 0                  | 0          | "0"                 | false        |
| 1                  | 1          | "1"                 | true         |
| "0"                | 0          | "0"                 | true         |
| "1"                | 1          | "1"                 | true         |
| NaN                | NaN        | "NaN"               | false        |
| Infinity           | Infinity   | "Infinity"          | true         |
| \-Infinity         | \-Infinity | "-Infinity"         | true         |
| ""                 | 0          | ""                  | false        |
| "20"               | 20         | "20"                | true         |
| "twenty"           | NaN        | "twenty"            | true         |
| \[ \]              | 0          | ""                  | true         |
| \[20\]             | 20         | "20"                | true         |
| \[10,20\]          | NaN        | "10,20"             | true         |
| \["twenty"\]       | NaN        | "twenty"            | true         |
| \["ten","twenty"\] | NaN        | "ten,twenty"        | true         |
| function(){}       | NaN        | "function(){}"      | true         |
| { }                | NaN        | "\[object Object\]" | true         |
| null               | 0          | "null"              | false        |
| undefined          | NaN        | "undefined"         | false        |

!> 注意：引号 ("") 中的值表示字符串值。红色值表示程序员可能不希望的值。
