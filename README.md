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

Copyright &copy; YassLab Inc.<br>
Railsチュートリアル運営チーム<br>
[https://railstutorial.jp/](https://railstutorial.jp/)
