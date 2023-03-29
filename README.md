# Codespaces ♥️ Railsチュートリアル

本リポジトリは[Railsチュートリアル](https://railstutorial.jp/)の [GitHub Codespaces](https://github.co.jp/) 用テンプレートです。[2022年11月にリリース](https://www.publickey1.jp/blog/22/github_codespaces60jetbrainsjupyterlabide.html)されたGitHub公式のRailsテンプレートを、[Railsチュートリアル](https://railstutorial.jp)用にカスタマイズしたものです。

- [:octocat: github/codespaces-rails](https://github.com/github/codespaces-rails)
- [:newspaper: GitHub Codespacesが全ユーザーに無料提供へ、毎月60時間分 - Publickey](https://www.publickey1.jp/blog/22/github_codespaces60jetbrainsjupyterlabide.html)

本テンプレートは、Railsチュートリアルの第1章・第2章・第3章の冒頭にある `rails new` および `Gemfile` の更新まで（難しいとされる「環境構築」まで）が完了している状態となっており、**rails server が立ち上げられる状態から学習をスタートできます** 📝✨

![Codespaces のサンプル画面](https://i.gyazo.com/b3af38fd1f8b2824791da9001a2bf6a0.png)

<!-- ![旧：Codespaces のサンプル画面](https://i.gyazo.com/af23bec87ce2b3d79613e16883700ecf.png) -->

<br>

## 拡張機能について
より良い学習体験に繋げるため、本テンプレートには以下の VS Code 拡張機能がデフォルトで入っています。

- [:octocat: rubyide/vscode-ruby](https://github.com/rubyide/vscode-ruby):
  - Ruby コードのハイライトや折り畳みなどが可能になります
- [:octocat: castwide/vscode-solargraph](https://github.com/castwide/vscode-solargraph):
  - Ruby コードの定義元が調べられるコードジャンプ機能や、Ruby の型情報を使ったコード補完、公式ドキュメントの表示機能などが使えます（以下は[公式のデモ動画](https://github.com/castwide/vscode-solargraph#readme)です）
  - ![Solargraph Official DEMO](https://i.gyazo.com/5fac6a81088d814a5b8354431239b03d.gif)

RuboCop によるコード整形、Ruby 公式デバッガーなどの拡張機能はお好みで追加してください。本テンプレートでは必要最低限の拡張機能に留めています。

- [:octocat: misogi/vscode-ruby-rubocop](https://github.com/misogi/vscode-ruby-rubocop)
- [:octocat: ruby/vscode-rdbg](https://github.com/ruby/vscode-rdbg)
- [:octocat: ruby-debug/ruby-debug-ide](https://github.com/ruby-debug/ruby-debug-ide)
- [:octocat: Shopify/vscode-shopify-ruby](https://github.com/Shopify/vscode-shopify-ruby)
- [:octocat: primer/github-vscode-theme](https://github.com/primer/github-vscode-theme)

<br>

## 必要なもの

- [Chrome](https://www.google.com/intl/ja/chrome/browser/) などのブラウザ（Chrome だとより快適に動作します）
- [GitHub](https://github.co.jp/) のアカウント（もしまだであれば事前に準備をお願いします）
  [![GitHub Top](https://i.gyazo.com/b5bad7bc8318837b67def1643a52b955.png)](https://github.co.jp/)

<br>

## 使い方

1. [Codespaces](https://github.com/codespaces) のページに行きます
1. 画面右の [New codespace ボタン](https://github.com/codespaces/new)をクリックします
   ![Codespaces Top](https://i.gyazo.com/ec618040bfe1a53c0458ab39503e661a.png)
1. `Select a repository` をクリックし、`yasslab/codespaces-railstutorial` と入力します（他の項目は自動で補完されます）
   ![Codespaces Top](https://i.gyazo.com/9d5e7d0f5be80486a27d62dd7d94c74d.png)
1. 以下の画面になったら、右下の `Create codespace` ボタンを押します
   ![Codespaces Top](https://i.gyazo.com/bb49c9993e4e355b287623c662e94ffc.png)
1. 環境構築が完了するのを待ちます（１〜２分ほど掛かります）
   ![Codespaces Top](https://i.gyazo.com/1dc81bccd2f416bc936cd60f348a6d7a.png)
1. Railsチュートリアルのロゴ画像が表示されたら完成です!
   ![Codespaces Top](https://i.gyazo.com/b3af38fd1f8b2824791da9001a2bf6a0.png)
1.  `rails new` や `Gemfile` の更新、`rails server` を立ち上がるところまで（難しいとされる「環境構築」が終わるところまで）が完了している状態なので、**第1章・第2章・第3章のコードを書くところから始められます!** 📝✨

<br>

## よくあるエラーと解決方法
<details>
  <summary><strong>ブラウザ別のエラー解決方法を見る（2023年3月時点）</strong></summary>
  <h3>Google Chrome - Webビューの読み込みエラー</h3>
  <img src='https://i.gyazo.com/c59a5e4c331e5a513860bc118526378d.png)' alt='Chrome のエラー例１' />
  <p><code>Error: Could not register service workers: NotSupportedError ...</code> などが表示され、「シンプルブラウザーは開いたけど何も表示されない」という場合があります。これは必要な Cookie が許可されていない場合に起こります。以下の例を参考に、サードパーティの Cookie を許可すると解決する場合が多いです。</p>
  <img src='https://i.gyazo.com/491d00e54d05da7d920816a2dbd53491.png' alt='Chrome のエラー例２' />
  <p>Cookie を許可しても解決しない場合は、シンプルブラウザーの右端にある「ブラウザーで開く」アイコンをクリックしてください。ブラウザの別タブで画面が表示され、こちらの画面でも現在の状態をご確認いただけます。</p>
  <img src='https://i.gyazo.com/289ea5dc51a0718161b59830c6e3d9ec.png' alt='Chrome のエラー例３' />
  <br><br><br>

  <h3>Firefox - Webビューの読み込みエラー</h3>
  <p>上記の Chrome と同様に、シンプルブラウザーの画面が表示されない事があります。アドレスバーにある強化型トラッキング防止機能のアイコンをクリックし、「オフ」にすることでプレビューが表示されるようになります。</p>
  <img src='https://i.gyazo.com/7a73af24e1d7fde7ebb2ad00fe4bca0a.png' alt='Firefox のエラー例１' />
  <p>上記の機能をオフにしても解決しない場合は、シンプルブラウザーではなく「新規ウィンドウでサイトを開く」をクリックしてください。ブラウザの別タブで画面が表示され、こちらの画面でも現在の状態をご確認いただけます。</p>
  <img src='https://i.gyazo.com/488b1f6f090372bbafd7b5590d56acdd.png' alt='Firefox のエラー例２' />
  <img src='https://i.gyazo.com/8884a98fe667819d8730efeb905265eb.png' alt='Firefox のエラー例３' />
  <br><br><br>

  <h3>Safari - 入力の遅延・アイコンの一部非表示</h3>
  <p>Safari では問題なくことが多いです。ただし、文字入力をしてから、Codespaces 上の画面に表示されるまでが遅い場合があります。また一部のアイコンが表示されない現象も確認できています。開発する上で問題になるわけではないですが、もし気になる場合は Google Chrome など他のブラウザをお試しください。</p>
  <img src='https://i.gyazo.com/a74db22c2faba07a44af284a08f1f21b.png' alt='Safari のエラー例１' />
</details>

<br><br>

## 制作・ライセンス

Copyright &copy; [YassLab](http://yasslab.jp/) Inc.<br>
Railsチュートリアル運営チーム<br>
[https://railstutorial.jp/](https://railstutorial.jp/)

<small>
  ソースコードのライセンスは <a href='https://github.com/yasslab/codespaces-railstutorial/blob/main/LICENSE'>LICENSE</a> をご確認ください。<br>
  ロゴ画像やデモ動画などは各制作者の著作物となります。
</small>
