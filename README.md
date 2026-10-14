# $\LaTeX$ 英$\rightarrow$日翻訳ソフト

## 概要
英語で書かれた$\LaTeX$文書を日本語に翻訳するソフト。

## 使用方法

### フォルダ指定での翻訳

コンパイルできるフォルダを指定するとき：
```Powershell
latextranslate --source ${xxxx}
# For example,
# latextranslate --source arXiv-2610.06285v1
```

### arXivIDによる翻訳
arXivの`paper ID`を指定するとき：
```Powershell
latextranslate --arxiv ${xxxx}
# For example,
# latextranslate --arxiv 2610.06285
```