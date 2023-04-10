# Uguisu
UguisuはJavaScript上で動作するプログラミング言語です。  
静的な型チェック機能を備えています。  

コード例
```text
fn calc(x: number): number {
    if x == 0 {
        return 1;
    } else {
        return calc(x - 1) * 2;
    }
}

fn main() {
    var value = 10;
    console.writeNum(calc(value));
}
```

## インストール
npmを使ってインストールしてください。
```
npm install -g uguisu-js
```

## リンク
- [Uguisu](https://github.com/uguisu-dev/uguisu)
- [Uguisu syntax support for vscode](https://github.com/uguisu-dev/vscode-uguisu)

## ニュース
### Uguisu 0.8 をリリース (2023-04-10)
先日2023/04/04にUguisu 0.8 がリリースされました:rocket:  
以下のDiscussionでは、追加された機能について紹介しています。  
https://github.com/uguisu-dev/uguisu/discussions/76

### サイトオープン (2023-04-10)
サイトを開設しました。ここではUguisuに関する情報を公開します。
