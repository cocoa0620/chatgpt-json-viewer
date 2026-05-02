---

# ChatGPT JSON Viewer

A browser-based viewer for ChatGPT export data.

This tool reads your ChatGPT export conversation JSON files and lets you browse your conversations and images directly in your browser, with a dedicated image gallery view.

* Browse all images included in your export
* Designed for easy browsing, even with large exports

---

## 🌐 Live Demo

* Japanese: [https://cocoa0620.github.io/chatgpt-json-viewer/](https://cocoa0620.github.io/chatgpt-json-viewer/)
* English: [https://cocoa0620.github.io/chatgpt-json-viewer/index_en.html](https://cocoa0620.github.io/chatgpt-json-viewer/index_en.html)

---

## 🚀 How to use

1. Export your data from ChatGPT
   (Settings → Data Controls → Export)

2. Download the ZIP file from the email

3. Unzip the file

4. Open the viewer and select one of the following:

### ① Load JSON only (fast)

* Select `conversations.json` or `conversations-*.json`
* Faster loading
* Images are not available

### ② Load full export folder (full features)

* Select the extracted export folder
* Includes images and attachments
* Slower depending on size

The folder picker supports both older exports with `conversations.json` and newer split exports such as `conversations-000.json`, `conversations-001.json`, and so on.

---

## ✨ Features

### 💬 Chat View

* Conversation list
* Full text view
* Search (list & content)
* Pin conversations
* Conversation size indicator

### 🖼 Image View

* Browse all images included in your export
* Separate views for:

  * User images
  * GPT-generated images
* Quick filter:

  * All / User / GPT-generated
* Thumbnail grid with click-to-expand
* Supports PNG, JPG, WEBP, and GIF

---

## 📸 Screenshots

### Image View

![image-view](images/Sample3.png)

### List view

![list](images/Sample2.png)

### Detail view

![detail](images/Sample1.png)

---

## 📝 Notes

* Works entirely in your browser (no data upload)

* You can select the unzipped export folder directly. Conversation files are detected automatically.

* Image-to-chat mapping is not fully reconstructed
  (images are shown in a separate gallery view for better usability)

---

## 🌍 Browser Support

This tool uses folder selection (File System Access API / webkitdirectory).

Tested:

* Google Chrome (recommended)
* Microsoft Edge

Not fully supported:

* Firefox
* Safari

---

## 📱 Mobile Support

* JSON loading: supported
* Folder loading: not supported on most mobile browsers
* Image view: not available in JSON mode

For full features, use desktop Chrome or Edge.

---

## 🔒 Privacy

This tool runs entirely in your browser.

* No data is uploaded
* No server communication
* Your files stay on your device

---

## 💡 Why Image View?

ChatGPT export data does not always provide a reliable link between messages and image files.

Instead of forcing incomplete reconstruction, this tool provides a dedicated image gallery for easier browsing.

---

# 🇯🇵 日本語

## ChatGPT JSON Viewer

ChatGPTのエクスポートデータをブラウザ上で閲覧できるツールです。

会話JSONファイルを読み込み、チャットと画像を簡単に確認できます。画像は専用のギャラリービューでまとめて表示されます。

* エクスポート内の画像を一覧表示
* 大量データでも見やすい設計

---

## 🚀 使い方

1. ChatGPTからデータをエクスポート
   （設定 → Data Controls → Export）

2. メールで届いたZIPをダウンロード

3. ZIPファイルを解凍

4. ビューアを開き、以下のどちらかを選択

### ① JSONのみ読み込み（高速）

* `conversations.json` または `conversations-*.json` を選択
* 読み込みが速い
* 画像は表示されません

### ② フォルダ読み込み（完全版）

* 解凍したフォルダをそのまま選択
* 画像や添付ファイルも表示可能
* データ量によっては時間がかかります

旧形式（conversations.json）と新形式（分割JSON）の両方に対応しています。

---

## ✨ 機能

### 💬 チャットビュー

* 会話一覧
* 本文表示
* 検索（一覧・本文）
* ピン留め
* 会話サイズ表示

### 🖼 画像ビュー

* エクスポート内の画像を一覧表示
* ユーザー画像 / GPT生成画像の分類
* フィルター（すべて / ユーザー / GPT）
* サムネイル表示（クリックで拡大）
* PNG / JPG / WEBP / GIF対応

---

## 📝 注意

* すべてブラウザ内で動作します（データ送信なし）

* 解凍したフォルダを直接選択できます

* 画像とメッセージの完全な対応付けは行っていません
  （代わりに画像専用ビューで見やすく表示します）

---

## 🌍 対応ブラウザ

このツールはフォルダ選択機能を使用しています。

動作確認済み:

* Google Chrome（推奨）
* Microsoft Edge

未対応・制限あり:

* Firefox
* Safari

---

## 📱 モバイル対応

* JSON読み込み: 可能
* フォルダ読み込み: 多くのブラウザで未対応
* 画像表示: JSONモードでは不可

フル機能を使う場合はPC版ChromeまたはEdgeを推奨します。

---

## 🔒 プライバシー

このツールはブラウザ内で完結します。

* データは外部に送信されません
* サーバー通信なし
* ファイルは端末内に保持されます

---

## 💡 画像ビューについて

ChatGPTのエクスポートデータでは、メッセージと画像の対応関係が完全には保証されていません。

そのため、このツールでは無理に対応付けを行わず、画像専用のギャラリービューとして提供しています。

---

