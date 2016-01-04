# bce.sty

学士論文のための LaTeX テンプレート（研究室Only）

## Usage

`foobar.tex` が置いてあるディレクトリに `bce.sty` を置き，`foobar.tex` のプリアンブルに以下を記述します．

```
\usepackage{bce}
```

また，表紙を作成するには以下を記述したあとで`\begin{document}`の直下に
`\maketitle`します．

```
\title{...}%タイトル
\snumber{...}%学籍番号
\author{...}%名前
\teacher{...　准教授}%教員
\syear{YYYY}%年度
```

詳細は `sample.tex` を参照してください．

## Package Dependencies

- `amsmath`, `amssymb`
- `color`
- `[dvipdfmx]hyperref`
- `pxjahyper`
- `fancyhdr`
- `titlesec`
- `newtxtext`, `newtxmath`

最新の [TeX Live](https://www.tug.org/texlive/) をインストールされていればこれらのパッケージはすべてインストールされていますが，
もし存在しなければ `bce.sty` と同じディレクトリにスタイルファイルをダウンロードし保存してください．
