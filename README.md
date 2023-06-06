# OBS_Counter

<!-- repo url. -->
[Releases]: https://img.shields.io/github/v/release/Ohno-Tk/OBS_GoodMorningCounter?logo=github
[Downloads]: https://img.shields.io/github/downloads/Ohno-Tk/OBS_GoodMorningCounter/total?logo=github
[Stars]: https://img.shields.io/github/stars/Ohno-Tk/OBS_GoodMorningCounter?style=social

<!-- development tool url. -->
[License]: https://img.shields.io/badge/license-MIT-blue.svg
[HTML-image]: https://img.shields.io/badge/-Html5-E34F26.svg?logo=html5&logoColor=white&style=flat
[CSS-image]: https://img.shields.io/badge/-Css3-1572B6.svg?logo=css3&style=flat
[JavaScript-image]: https://img.shields.io/badge/-Javascript-F7DF1E.svg?logo=javascript&logoColor=black
[jQuery-image]: https://img.shields.io/badge/Jquery-3.3.1-0769AD.svg?logo=jquery&style=flat
[VSCode-image]: https://img.shields.io/badge/-Visual%20studio%20code-007ACC.svg?logo=visualstudiocode&style=flat


<!-- badge. -->
<div align="center">

  <!-- repo info -->
  [![License]](/.github/LICENSE) [![Releases]](https://github.com/Ohno-Tk/OBS_Counter/releases) ![Downloads] ![Stars]

  <!-- development tool -->
  ![HTML-image] ![CSS-image] ![JavaScript-image] ![jQuery-image] ![VSCode-image]
</div>

## Table of Contents(目次)
- Users(ユーザー向け)
  - [Screenshot](#screenshot)
  - [Features(セールスポイントなど)](#features)
  - [Release Notes (リリースノート)](#release-notes)
- Developer(開発者向け)
  - [Coding Rule (コーディング規約)](#coding-rule)
  - [Development Process (開発プロセス)](#development-process)
    - [Commit Message Title Rule (コミットメッセージ規約)](#commit-message-title-rule)
    - [Pull Request(PRの作成方法)](#pull-request)
- [License(ライセンス)](#license)

## Screenshot
obsで表示できるカウンター
<div align="center">
  <img width="500" src="https://github.com/Ohno-Tk/OBS_GoodMorningCounter/assets/51406176/646ba219-9e61-449e-aac3-2a00cd30ea31">
</div>

## Features
- OBSで表示できる。


## Coding Rule
- [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#Protocol)
- [Google JavaScript スタイルガイド - 日本語訳](https://w.atwiki.jp/aias-jsstyleguide2/)

## Commit Message Title Rule
```
                        commit title
        commit type         /
                \           |
                 feat: add template url parameter to events
```
`commit type` としては次のようなものがあります。

- feat
    - 新しい機能など。
    - 更新履歴に載るような新しいページを追加。
- fix
    - 意味が変わる修正。
    - 更新履歴に載るような修正。
- docs
    - 基本的には使わない。
    - README.mdやCONTRIBUTING.mdや本体のプロジェクト全体のドキュメントについて。
- refactor
    - 意味が変わらない修正。
    - 更新履歴に載らないような修正。
- style
    - スペースやインデントの調整。
    - Lintエラーの修正など。
- perf
    - パフォーマンス改善。
- test
    - テストに関して。
- chore
    - その他。
    - typoの修正など。

`commit type`は、迷ったらとりあえず`chore`と書きます。
`scope`も省略して問題ないので以下のような形でも問題ありません。

```
chore: コミットメッセージ
```

## Development Process
### Pull Request
Pull Requestはいつでも歓迎しています。

1. まず Issue を作る。
1. Issue に対応したブランチを作る。
1. 作ったブランチからマージしたいブランチへ Pull Request を送る。
1. Pull Request をレビューする。
1. 修正点があれば修正する。
1. マージする。

## License
Released 2023 by Ohno-Tk
