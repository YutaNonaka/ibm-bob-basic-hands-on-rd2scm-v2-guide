# 準備と設定

チュートリアルに必要なリソースを準備し、IBM Bobの基本操作を理解します。

※ Lab 3・4 を実施しない場合は、[こちら](preparation-and-setup-without-lab3-4.md) を参照してください。

## 環境準備

#### 1. チュートリアルデータの取得

##### 1-1. GitHubリポジトリのFork

既存のリポジトリを自分のGitHubアカウントにForkします。

**手順:**

1. Webブラウザで既存のリポジトリにアクセスする
   - URL: https://github.com/YutaNonaka/ibm-bob-basic-hands-on-rd2scm-v2
2. GitHub画面右上の「Fork」ボタンをクリック
3. Fork先のアカウントを選択（通常は自分のアカウント）
4. 「Create fork」をクリック

![](/Image/preparation-and-setup-with-lab3-4/image.png)

![](/Image/preparation-and-setup-with-lab3-4/image-1.png)

##### 1-1-2. devブランチの作成

Forkしたリポジトリのmainブランチから、新しくdevブランチを作成します。

**手順:**

1. Forkしたリポジトリのページで、ブランチドロップダウン（「main」と表示されている部分）をクリック
2. テキストボックスに「dev」と入力
3. 「Create branch: dev from 'main'」をクリック

![](/Image/preparation-and-setup-with-lab3-4/image-2.png)

![](/Image/preparation-and-setup-with-lab3-4/image-3.png)

##### 1-1-3. IBM Bobの起動

デスクトップまたはアプリケーションフォルダから、IBM Bobを起動します。

##### 1-1-4. GitHubリポジトリのクローン

Forkしたリポジトリのdevブランチをローカルにクローンします。

**手順:**

1. コマンドパレットを開く
   - Windows/Linux: `Ctrl+Shift+P`
   - Mac: `Cmd+Shift+P`
2. 「Git: Clone」と入力して選択する
3. 自分のGitHubに戻り、「<>Code」ボタンから、Forkしたリポジトリ（自分のアカウント）のHTTPSのURLを取得する
3. Bobに戻り、Forkしたリポジトリ（自分のアカウント）のURLを入力する
   - 例: `https://github.com/[あなたのユーザー名]/ibm-bob-basic-hands-on-rd2scm-v2.git`
4. クローン先のディレクトリを選択する
5. クローンが完了すると、「リポジトリを開きますか？」と聞かれるので「開く」をクリックする

![](/Image/preparation-and-setup/Slide8.jpg)
![](/Image/preparation-and-setup/Slide10.jpg)


##### 1-5. プロジェクトフォルダの別の開き方（1-1-4 手順5でフォルダを開けた方は1-6.へ進んでください)


###### 1-5-1. フォルダーを開く

1. IBM Bob画面左上の「ファイル」メニューをクリック
2. 「フォルダーを開く」を選択

###### 1-1-5-2. フォルダーを選択

1. 先ほどクローンした「ibm-bob-basic-hands-on-rd2scm-v2」フォルダに移動
2. 「ibm-bob-basic-hands-on-rd2scm-v2」フォルダを選択
3. 「フォルダーの選択」をクリック

##### 1-1-6. devブランチに切り替える

1. IBM Bob画面左下に表示されている現在のブランチ名（「main」）をクリック
2. 上部に表示されるブランチ一覧から「origin/dev」を選択

※IBM Bob画面左下にブランチ名が表示されない場合は以下の手順を実施後、1.に戻ってください。
1. ソース管理パネルを開く
2. 「リポジトリを開く」をクリック
3. 対象のリポジトリを選択
![](/Image/preparation-and-setup/image-4.png)





### 3. ファイルの確認

IBM Bob画面左側のEXPLORERに「Hands-on」が表示され、以下のファイルが確認できます：

- specs> plan-template.md
- specs> spec-template.md
- .bobignore
- AGENTS.md
- Bob.svg
- PROMPT.md
- PROMPT2.md
- qa.md

各ファイルをクリックして内容を確認してみましょう。確認後は、タブ右上の「×」ボタンで閉じます。

## ファイル構成の確認

プロジェクトフォルダには以下のファイルが含まれています：

| ファイル名 | 説明 |
|-----------|------|
| plan-template.md | 具体的な作業内容を定義する実装計画書の雛形 |
| spec-template.md | 要件と仕様を定義する仕様書の雛形　|
| .bobignore | Bobに確認させないファイルを指定 |
| AGENTS.md | Bobの挙動を指定します |
| Bob.svg | LAB2用のBobのキャラクター画像。FAQサイトに挿入します |
| PROMPT.md | LAB1用のプロンプト集 |
| PROMPT2.md | LAB2用のプロンプト例 |
| qa.md| FAQ質問集（英語）。日本語に翻訳してサイトに表示します |

注意: PROMPT.md、PROMPT2.mdはチャット画面へコピー&ペーストして使用するため、.bobignoreに記載されています。

## チェックリスト

準備と設定が完了したら、以下を確認してください：

- クローン、または、作業ディレクトリにフォルダをコピー済み
- IBM Bobを起動済み
- プロジェクトフォルダをBobで開いた
- ファイル一覧を確認済み
- Bob画面左下のブランチ名が「dev」になっている


## 次のステップ

準備と設定が完了したら、IBM Bobの画面構成と基本操作を学びましょう！

前へ: [はじめに](README.md) | 次へ: [IBM Bobの画面構成と基本操作](https://r-nakayamasan.github.io/bob-workshop-draft/02_bob_interface/)
