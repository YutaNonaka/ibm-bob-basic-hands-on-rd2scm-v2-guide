# 準備と設定（Lab 3・4 を実施しない場合）

チュートリアルに必要なリソースを準備し、IBM Bobの基本操作を理解します。

※ Lab 3・4 を実施する場合は、[こちら](preparation-and-setup-with-lab3-4.md)を参照してください。

## 環境準備


### 1. チュートリアルデータの取得

#### 1-1. GitHubリポジトリへアクセス

Webブラウザを開き、リポジトリにアクセスします
- URL: https://github.com/YutaNonaka/ibm-bob-basic-hands-on-rd2scm-v2

#### 1-2. データのダウンロード

1. 「Code」ボタンをクリックして展開
2. 「Download ZIP」をクリック

![](/Image/preparation-and-setup-without-lab3-4/image.png)

「ibm-bob-basic-hands-on-rd2scm-v2-main.zip」という名前のファイルがダウンロードされます。

#### 1-3. ファイルの展開

1. ダウンロードフォルダに移動
2. 「ibm-bob-basic-hands-on-rd2scm-v2-main.zip」を右クリック
3. 「すべてのファイルを展開」(Windows) または「展開」(Mac) をクリック

注意: .zipファイルではなく、展開後のフォルダを使用します。

![](/Image/preparation-and-setup-without-lab3-4/image-1.png)

#### 1-4. 作業ディレクトリへ移動

展開後の「ibm-bob-basic-hands-on-rd2scm-v2-main」フォルダを、作業しやすい場所（デスクトップなど）にコピーします。

**手順:**

1. 「ibm-bob-basic-hands-on-rd2scm-v2-main」フォルダをコピー
2. デスクトップまたは任意の作業場所にペースト

### 2. IBM Bobの設定

#### 2-1. IBM Bobの起動

デスクトップまたはアプリケーションフォルダから、IBM Bobを起動します。

#### 2-2. プロジェクトフォルダを開く

##### 2-2-1. フォルダーを開く

1. IBM Bob左上の「ファイル」メニューをクリック
2. 「フォルダーを開く」を選択

![](/Image/preparation-and-setup-without-lab3-4/image-2.png)

##### 2-2-2. フォルダーを選択

1. 先ほどコピーした「ibm-bob-basic-hands-on-rd2scm-v2-main」フォルダに移動
2. 「ibm-bob-basic-hands-on-rd2scm-v2-main」フォルダを選択
3. 「フォルダーの選択」をクリック

![](/Image/preparation-and-setup-without-lab3-4/image-3.png)

### 3. ファイルの確認

IBM Bob画面左側のEXPLORERに「IBM-BOB-BASIC-HANDS-ON-RD2SCM-V2-MAIN」が表示され、以下のファイル・フォルダが確認できます：

- specs
  - plan-template.md
  - spec-template.md
- .bobignore
- AGENTS.md
- Bob.svg
- PROMPT.md
- PROMPT2.md
- qa.md

![](/Image/preparation-and-setup-without-lab3-4/image-4.png)

各ファイルをクリックして内容を確認してみましょう。確認後は、タブ右上の「×」ボタンで閉じます。

## ファイル構成の確認

プロジェクトフォルダには以下のファイル・フォルダが含まれています：

| ファイル名 | 説明 |
|-----------|------|
| plan-template.md | 具体的な作業内容を定義する実装計画書の雛形 |
| spec-template.md | 要件と仕様を定義する仕様書の雛形 |
| .bobignore | Bobに確認させないファイルを指定 |
| AGENTS.md | Bobの挙動を指定します |
| Bob.svg | LAB2用のBobのキャラクター画像。FAQサイトに挿入します |
| PROMPT.md | LAB1用のプロンプト集 |
| PROMPT2.md | LAB2用のプロンプト例 |
| qa.md | FAQ質問集（英語）。日本語に翻訳してサイトに表示します |

注意: PROMPT.md、PROMPT2.mdはチャット画面へコピー&ペーストして使用するため、.bobignoreに記載されています。

## チェックリスト

準備と設定が完了したら、以下を確認してください：

- 作業ディレクトリにフォルダをコピー済み
- IBM Bobを起動済み
- プロジェクトフォルダをBobで開いた
- ファイル一覧を確認済み


## 次のステップ

準備と設定が完了したら、IBM Bobの画面構成と基本操作を学びましょう！

前へ: [はじめに](../README.md) | 次へ: [IBM Bobの画面構成と基本操作](https://r-nakayamasan.github.io/bob-workshop-draft/02_bob_interface/)
