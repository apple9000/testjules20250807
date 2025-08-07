# GitHub PagesでWebページを公開する手順

このドキュメントでは、作成した `index.html` と `style.css` を使って、GitHub Pagesで自分だけのWebページを公開する手順を解説します。

## 前提条件

- GitHubのアカウントを持っていること。（持っていない場合は、[公式サイト](https://github.com/join)から無料で作成できます）

## 公開までのステップ

### 1. 新しいリポジトリを作成する

まず、Webページのファイルを保管するための場所（リポジトリ）をGitHub上に作成します。

1.  [GitHub](https://github.com/)にログインし、画面右上の「+」アイコンをクリックし、ドロップダウンメニューから `New repository` を選択します。
2.  **Repository name:** 好きなリポジトリ名を入力します。（例: `jules-showcase-page`）
3.  **Description (optional):** リポジトリの説明を任意で入力します。（例: `Julesの活用事例を紹介するWebページ`）
4.  `Public` を選択します。（GitHub Pagesの無料プランでは、Publicリポジトリである必要があります）
5.  `Initialize this repository with:` のセクションで `Add a README file` にチェックを入れます。
6.  `Create repository` ボタンをクリックします。

### 2. 作成したファイルをアップロードする

次に、ローカルで作成した `index.html` と `style.css` を、今作成したリポジトリにアップロードします。

1.  作成したリポジトリのページを開きます。
2.  `Add file` ボタンをクリックし、ドロップダウンメニューから `Upload files` を選択します。
3.  `drag and drop` と書かれたエリアに、あなたのコンピュータ上にある `index.html` と `style.css` の2つのファイルをドラッグ＆ドロップします。
4.  ファイルがアップロードされると、ページ下部の `Commit changes` というフォームが表示されます。
5.  特に変更がなければ、そのまま緑色の `Commit changes` ボタンをクリックします。

### 3. GitHub Pagesを有効にする

最後に、アップロードしたファイルを使ってWebページを公開する設定をします。

1.  リポジトリのページの上部にある `Settings` タブをクリックします。
2.  左側のメニューから `Pages` を選択します。
3.  `Build and deployment` の下にある `Source` で、`Deploy from a branch` を選択します。（通常はデフォルトで選択されています）
4.  `Branch` のセクションで、ブランチが `main`（または `master`）に設定されていることを確認します。フォルダは `/(root)` のままで大丈夫です。
5.  `Save` ボタンをクリックします。

### 4. 公開されたページを確認する

設定は以上です！

-   `Save` をクリックしてから、GitHubがWebページをビルドして公開するまで、通常1〜2分かかります。
-   同じ `Settings` > `Pages` の画面をリロードすると、ページ上部に `Your site is live at https://<あなたのユーザー名>.github.io/<リポジトリ名>/` のように、公開されたページのURLが表示されます。
-   このURLにアクセスして、作成したWebページが正しく表示されているか確認しましょう。

以上で、あなたのJules活用事例Webページがインターネット上に公開されました！
