# Codespaces ♥️ Railsチュートリアル

本リポジトリは[Railsチュートリアル](https://railstutorial.jp/)の [GitHub Codespaces](https://github.co.jp/) 用テンプレートです。

![Codespaces のサンプル画面](https://github.com/yasslab/codespaces-railstutorial/blob/main/public/codespaces.png?raw=true)

本リポジトリは[2022年11月にリリース](https://www.publickey1.jp/blog/22/github_codespaces60jetbrainsjupyterlabide.html)された以下のGitHub公式Railsテンプレートを、Railsチュートリアル用にカスタマイズしたものです。

- [:octocat: github/codespaces-rails](https://github.com/github/codespaces-rails)
- [:newspaper: GitHub Codespacesが全ユーザーに無料提供へ、毎月60時間分 - Publickey](https://www.publickey1.jp/blog/22/github_codespaces60jetbrainsjupyterlabide.html)

またRailsチュートリアル用にカスタマイズされた本テンプレートでは、第1章・第2章・第3章の冒頭にある `rails new` および `Gemfile` の更新までが完了しており、`rails server` が立ち上がる状態から学習を始められます。

なお以下の拡張機能はデフォルトで入っています。より良い開発体験に繋がれば幸いです。(公式のデモ動画より引用)

- [:octocat: rubyide/vscode-ruby](https://github.com/rubyide/vscode-ruby):
  - Ruby コードのハイライトや折り畳みなどが可能になります
- [:octocat: castwide/vscode-solargraph](https://github.com/castwide/vscode-solargraph):
  - `if...end` や `do..end` などが自動的に補完されます
  - ![DEMO](https://github.com/yasslab/codespaces-railstutorial/blob/main/public/demo_solargraph.gif?raw=true)
- [:octocat: kaiwood/vscode-endwise](https://github.com/kaiwood/vscode-endwise):
  - `if...end` や `do..end` などが自動補完されます
  - ![DEMO](https://github.com/yasslab/codespaces-railstutorial/blob/main/public/demo_endwise.gif?raw=true)

RuboCop などの Linter 系はお好みで追加してください。デフォルトでは必要最低限の拡張機能に留めています。

<br>

## 必要なもの

- [Chrome](https://www.google.com/intl/ja/chrome/browser/) などのブラウザ（Chrome 推奨）
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
1.  `rails new` や `Gemfile` の更新、`rails server` が立ち上がるところまで（環境構築が終わるところまで）が完了している状態になるので、第1章・第2章・第3章の **コードを書くところから始められます!** 📝✨

<br>

## 制作

Copyright &copy; YassLab Inc.<br>
Railsチュートリアル運営チーム<br>
[https://railstutorial.jp/](https://railstutorial.jp/)
