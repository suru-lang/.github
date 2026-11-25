<p align="center"><a href="README.md">English</a> | 日本語</p>

<p align="center">
  <img src="suruzou.png" alt="するぞう" width="140">
</p>

<h1 align="center">する — コードを、日本語で。</h1>

<p align="center">
  「<b>する</b>」は、日本語で書く、型のある関数型プログラミング言語です。<br>
  引数は格助詞で区別し、型は書かなくても推論し、プログラムは速いネイティブのバイナリになります。<br>
  <i>suru is a typed, functional programming language you write in Japanese.</i>
</p>

<p align="center">
  <a href="https://suru-lang.github.io/ja/">サイト</a> ·
  <a href="https://suru-lang.github.io/ja/tutorial.html">入門</a> ·
  <a href="https://suru-lang.github.io/">English</a>
</p>

## ちょっとだけ

```
a を b で 割った数にする とは a / b
10 を 2 で 割った数にする
2 で 10 を 割った数にする    # 助詞で決まるので同じ

n を 階乗する とは
  もし n が 0 ならば 1
  そうでなければ n * （n - 1 を 階乗する）
10 を 階乗する
```

```
5
5
3628800
```

## 入れ方

| 方法 | コマンド |
| --- | --- |
| pip | `pip install suru-lang` |
| Homebrew(macOS・Linux) | `brew install suru-lang/suru/suru` |
| VS Code | [Marketplace の「する」](https://marketplace.visualstudio.com/items?itemName=suru-lang.suru) |
| バイナリ | [GitHub Releases](https://github.com/suru-lang/suru/releases) |

## リポジトリ

| リポジトリ | 中身 |
| --- | --- |
| [suru](https://github.com/suru-lang/suru) | 本体: インタプリタ・コンパイラ・標準ライブラリ・ビルドツール kumu・VS Code 拡張 |
| [http](https://github.com/suru-lang/http) | HTTP のサーバーとクライアント、WebSocket |
| [sqlite](https://github.com/suru-lang/sqlite) | SQLite のデータベース |
| [regex](https://github.com/suru-lang/regex) | PCRE2 の正規表現 |
| [gui-sdl3](https://github.com/suru-lang/gui-sdl3) | SDL3 で窓を開いて描く GUI のライブラリ「画面」 |
| [ohanashi-ollama](https://github.com/suru-lang/ohanashi-ollama) | Ollama の LLM とブラウザで話す Web アプリ(する で書いたもの) |
| [suru-lang.github.io](https://github.com/suru-lang/suru-lang.github.io) | 公式サイト |

ライブラリは kumu で足します(例: `kumu 追加 github.com/suru-lang/http`)。
