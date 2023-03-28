# Codespaces ♥️ Railsチュートリアル

本リポジトリは[Railsチュートリアル](https://railstutorial.jp/)の [GitHub Codespaces](https://github.co.jp/) 用テンプレートです。[2022年11月にリリース](https://www.publickey1.jp/blog/22/github_codespaces60jetbrainsjupyterlabide.html)されたGitHub公式のRailsテンプレートを、[Railsチュートリアル](https://railstutorial.jp)用にカスタマイズしたものです。

- [:octocat: github/codespaces-rails](https://github.com/github/codespaces-rails)
- [:newspaper: GitHub Codespacesが全ユーザーに無料提供へ、毎月60時間分 - Publickey](https://www.publickey1.jp/blog/22/github_codespaces60jetbrainsjupyterlabide.html)

本テンプレートは、Railsチュートリアルの第1章・第2章・第3章の冒頭にある `rails new` および `Gemfile` の更新まで（難しいとされる「環境構築」まで）が完了している状態となっており、**rails server が立ち上げられる状態から学習をスタートできます** 📝✨

![Codespaces のサンプル画面](https://github.com/yasslab/codespaces-railstutorial/blob/main/public/codespaces.png?raw=true)

<br>

## 拡張機能について
より良い学習体験に繋げるため、本テンプレートには以下の VS Code 拡張機能がデフォルトで入っています。

- [:octocat: rubyide/vscode-ruby](https://github.com/rubyide/vscode-ruby):
  - Ruby コードのハイライトや折り畳みなどが可能になります
- [:octocat: castwide/vscode-solargraph](https://github.com/castwide/vscode-solargraph):
  - Ruby コードの定義元が調べられるコードジャンプ機能や、Ruby の型情報を使ったコード補完、公式ドキュメントの表示機能などが使えます（以下は[公式のデモ動画](https://github.com/castwide/vscode-solargraph#readme)です）
  - ![DEMO](https://github.com/yasslab/codespaces-railstutorial/blob/main/public/demo_solargraph.gif?raw=true)

RuboCop によるコード整形、`if..end` 文の自動補完などの拡張機能はお好みで追加してください。本テンプレートでは必要最低限の拡張機能に留めています。

- [:octocat: misogi/vscode-ruby-rubocop](https://github.com/misogi/vscode-ruby-rubocop)
- [:octocat: kaiwood/vscode-endwise](https://github.com/kaiwood/vscode-endwise)
- [:octocat: mosapride/vscode-zenkaku](https://github.com/mosapride/vscode-zenkaku)

<br>

## 必要なもの

- [Chrome](https://www.google.com/intl/ja/chrome/browser/) などのブラウザ（Chrome だとより快適に動作します）
- [GitHub](https://github.co.jp/) のアカウント（もしまだであれば事前に準備をお願いします）
   [![GitHub Top](https://github.com/yasslab/codespaces-railstutorial/blob/main/public/codespaces-0-lp.png?raw=true)](https://github.co.jp/)

<br>

## 使い方

1. [Codespaces](https://github.com/codespaces) のページに行きます
1. 画面右の [New codespace ボタン](https://github.com/codespaces/new)をクリックします
   ![Codespaces Top](https://github.com/yasslab/codespaces-railstutorial/blob/main/public/codespaces-1-top.png?raw=true)
1. `Select a repository` をクリックし、`yasslab/codespaces-railstutorial` と入力します（他の項目は自動で補完されます）
   ![Codespaces Top](https://github.com/yasslab/codespaces-railstutorial/blob/main/public/codespaces-2-repo.png?raw=true)
1. 以下の画面になったら、右下の `Create codespace` ボタンを押します
   ![Codespaces Top](https://github.com/yasslab/codespaces-railstutorial/blob/main/public/codespaces-3-new.png?raw=true)
1. 環境構築が完了するのを待ちます（１〜２分ほど掛かります）
   ![Codespaces Top](https://github.com/yasslab/codespaces-railstutorial/blob/main/public/codespaces-4-build.png?raw=true)
1. Railsチュートリアルのロゴ画像が表示されたら完成です!
   ![Codespaces Top](https://github.com/yasslab/codespaces-railstutorial/blob/main/public/codespaces-5-goal.png?raw=true)
1.  `rails new` や `Gemfile` の更新、`rails server` を立ち上がるところまで（難しいとされる「環境構築」が終わるところまで）が完了している状態なので、**第1章・第2章・第3章のコードを書くところから始められます!** 📝✨

<br>

## 制作

Copyright &copy; YassLab Inc.<br>
Railsチュートリアル運営チーム<br>
[https://railstutorial.jp/](https://railstutorial.jp/)
