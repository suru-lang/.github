<p align="center">English | <a href="README_jp.md">日本語</a></p>

<p align="center">
  <img src="suruzou.png" alt="Suruzou, the mascot" width="140">
</p>

<h1 align="center">suru — code, in Japanese.</h1>

<p align="center">
  <b>Suru</b> (「する」, "to do") is a typed, functional programming language you write in Japanese.<br>
  Arguments are marked with case particles, types are inferred without being written, and programs compile to fast native binaries.<br>
  <i>「する」は、日本語で書く、型のある関数型プログラミング言語です。</i>
</p>

<p align="center">
  <a href="https://suru-lang.github.io/">Site</a> ·
  <a href="https://suru-lang.github.io/tutorial.html">Tutorial</a> ·
  <a href="https://suru-lang.github.io/ja/">日本語</a>
</p>

## A taste

```
a を b で 割った数にする とは a / b
10 を 2 で 割った数にする
2 で 10 を 割った数にする    # the same: the particles decide the arguments

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

## Installing

| Method | Command |
| --- | --- |
| pip | `pip install suru-lang` |
| Homebrew (macOS, Linux) | `brew install suru-lang/suru/suru` |
| VS Code | [「する」 on the Marketplace](https://marketplace.visualstudio.com/items?itemName=suru-lang.suru) |
| Binaries | [GitHub Releases](https://github.com/suru-lang/suru/releases) |

## Repositories

| Repository | Contents |
| --- | --- |
| [suru](https://github.com/suru-lang/suru) | The core: interpreter, compiler, standard library, the build tool kumu, VS Code extension |
| [http](https://github.com/suru-lang/http) | HTTP server and client, WebSocket |
| [sqlite](https://github.com/suru-lang/sqlite) | SQLite databases |
| [regex](https://github.com/suru-lang/regex) | PCRE2 regular expressions |
| [gui-sdl3](https://github.com/suru-lang/gui-sdl3) | 「画面」, a GUI library that opens windows and draws with SDL3 |
| [ohanashi-ollama](https://github.com/suru-lang/ohanashi-ollama) | A web app for chatting with Ollama LLMs in the browser (written in Suru) |
| [suru-lang.github.io](https://github.com/suru-lang/suru-lang.github.io) | The official site |

Libraries are added with kumu (for example, `kumu 追加 github.com/suru-lang/http`).
