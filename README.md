# 中文标点符号替换为英文 (Chinese punctuation to english for vscode)

一个将中文标点符号替换为英文的 vscode 扩展, 为了排版的需要, 会自动在 `,.?:;!` 后面添加一个额外的空格.

A vscode extension of converting Chinese punctuation to English, it also adds one blank after each of `, . ? : ; !` punctuations for the better format.

## Usage

Use the **To english punctuation** command from the Command palette to convert it.

在命令面板中使用**To english punctuation**命令来转换标点符号. 当前只支持以下标点符号中英文的映射:

```javascript
[
  // 逗号
  ["，", ", "],

  // 句号
  ["。", ". "],

  // 问号
  ["？", "?"],

  // 顿号
  ["、", ", "],

  //冒号
  ["：", ": "],

  // 分好
  ["；", "; "],

  // 感叹号
  ["！", "!"],

  // 双引号
  ["“", '"'],
  ["”", '"'],

  // 单引号
  ["‘", "'"],
  ["’", "'"],

  // 圆括号
  ["（", "("],
  ["）", ")"],

  // 花括号
  ["｛", "{"],
  ["｝", "}"],

  // 尖括号
  ["《", "<"],
  ["》", ">"],
];
```

## contribution

If you're interested in contributing to, fork the [repo](https://github.com/buuug7/chinese-punctuation-to-english-vsocode.git) and submit pull requests.
