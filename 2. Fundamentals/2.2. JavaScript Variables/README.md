### 問題 1: 変数の宣言
**問題:** JavaScriptで変数を宣言するキーワードを全て選べ．

- [ ] `const`
- [ ] `let`
- [ ] `var`
- [ ] `static`

<details>
<summary>正解</summary>
var, let
</details>

<details>
<summary>解説</summary>
`var` キーワードはJavaScriptで変数を宣言するための古い方法です。ES6以降では `let` や `const` キーワードの使用が推奨されていますが、古いスクリプトや一部のコンテキストではまだ `var` が使われることがあります。
</details>


### 問題 2: 定数の宣言
**問題:** 定数を宣言するにはどのキーワードを使用しますか？

- [ ] `let`
- [ ] `variable`
- [ ] `const`
- [ ] `static`

<details>
<summary>正解</summary>
const
</details>

<details>
<summary>解説</summary>
JavaScriptで定数を宣言するには `const` キーワードを使用します。一度 `const` で宣言された定数は再代入ができません。定数は宣言と同時に初期化する必要があります。
</details>

### 問題 3: 未定義と未宣言の変数
**問題:** 未定義の変数とはどのような変数ですか？

- [ ] 宣言されていない変数
- [ ] 宣言されたが初期化されていない変数
- [ ] 初期化されたが値が `undefined` の変数
- [ ] エラーを発生させる変数

<details>
<summary>正解</summary>
宣言されたが初期化されていない変数
</details>

<details>
<summary>解説</summary>
未定義の変数は、宣言はされていますが、値が割り当てられていないため `undefined` を返します。この状態は変数が存在することを示していますが、まだ値が設定されていないことを意味します。
</details>

### 問題 4: 未宣言の変数
**問題:** 未宣言の変数にアクセスしようとするとどのようなエラーが発生しますか？

- `TypeError`
- `SyntaxError`
- `ReferenceError`
- `InternalError`

<details>
<summary>正解</summary>
ReferenceError
</details>

<details>
<summary>解説</summary>
未宣言の変数にアクセスしようとすると、JavaScriptでは `ReferenceError` が発生します。これは、指定された変数がスコープ内で見つからない場合に発生するエラーです。
</details>

### 問題 5: 定数の変更試み
**問題:** 一度定義された定数の値を変更しようとするとどのようなエラーが発生しますか？

- `TypeError`
- `SyntaxError`
- `ReferenceError`
- `InternalError`

<details>
<summary>正解</summary>
TypeError
</details>

<details>
<summary>解説</summary>
JavaScriptで `const` キーワードを使用して定義された定数の値を変更しようとすると、`TypeError` が発生します。定数は再代入が禁止されているため、値の変更を試みるとエラーが発生するのです。
</details>