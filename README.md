# COSMIC VIEW — iPhone Safari テスト版

このフォルダはGitHub Pagesで画面を確認するためのテスト用コピーです。元の編集版は含めず、記録データの移行もしていません。

## テスト版の注意

- GitHub Pagesは公開サイトです。HTMLと質問内容、アプリのコードは誰でも見られます。
- 実際の悩み、個人情報、普段の記録は入力しないでください。架空のテスト内容だけを使ってください。
- テスト版の記録は、開いたブラウザー内にのみ保存されます。サーバーやSupabaseには送信しません。
- 元アプリと保存先が混ざらないよう、テスト版は専用のIndexedDB名とブラウザー設定キーを使います。
- Cinzelフォントと天文計算ライブラリは、それぞれGoogle FontsとjsDelivrから読み込みます。インターネット接続が必要です。

## GitHubで公開する手順

1. GitHubで右上の「＋」を押し、「New repository」を選びます。
2. 新しい専用リポジトリ名に `cosmic-view-iphone-test` を入力します。既存の `cosmic-view-preview` は使わず、上書きしません。
3. 「Public」を選び、「Add a README file」は選ばずに「Create repository」を押します。
4. 新しいリポジトリで「Add file」→「Upload files」を選び、このフォルダの `index.html` と `README.md` を追加します。
5. 「Commit changes」を押して保存します。
6. リポジトリの「Settings」→「Pages」を開きます。
7. 「Build and deployment」の「Source」で「Deploy from a branch」を選びます。
8. 「Branch」で `main` と `/ (root)` を選び、「Save」を押します。
9. 同じ「Pages」画面に公開先が表示されたら、「Visit site」を押して開きます。
10. iPhoneのSafariで公開先を開きます。ホーム画面に追加するときは、Safariの共有ボタンから「ホーム画面に追加」を選びます。

予定URL：`https://minamiishii1234567-art.github.io/cosmic-view-iphone-test/`

リポジトリ名やGitHubアカウント名が変わるとURLも変わります。GitHub Pagesの公開設定を保存した後、「Settings」→「Pages」に表示されたURLを使ってください。

## ローカルでの確認

GitHubへアップロードする前に、`index.html` をブラウザーで開いて表示確認できます。公開URLとローカルファイルは別の保存領域です。
