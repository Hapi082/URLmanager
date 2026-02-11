# URL Manager (Python / PySide6)

ExcelファイルでURLを管理できるWindows向けデスクトップアプリです。  
URL・タイトル・タグ・メモを登録し、検索/フィルタ/並び替えで素早く参照できます。

<img width="1843" height="1365" alt="スクリーンショット 2026-02-11 143216" src="https://github.com/user-attachments/assets/e1a87406-931f-4aa6-b8e5-293e7442d199" />


---

## 主な機能

- ✅ URLの追加 / 編集 / 削除
- ✅ タグの追加 / 削除（タグ管理画面）
- ✅ タグフィルタ（AND / OR 切替）
- ✅ キーワード検索（タイトル / URL / タグ）
- ✅ お気に入り（★）機能
- ✅ 並び替え
  - お気に入り順
  - 追加日順（昇順/降順）
  - 利用数順（昇順/降順）
  - URL順（昇順/降順）
  - カスタム順（ドラッグ＆ドロップ）
- ✅ GOボタンでURLをブラウザで開く（利用数を自動カウント）
- ✅ 追加日を表示
- ✅ URL追加/編集時にページタイトルを自動取得して表示
- ✅ 画像付きホバープレビュー（og:image / description を取得して表示）
- ✅ Excelへ自動保存（他PCとExcel共有でデータ同期可能）

---

## 技術スタック

- Python
- PySide6（Qt）
- openpyxl（Excel読み書き）
- requests / beautifulsoup4（タイトル・OGP取得）
- webbrowser（URL遷移）

---

## セットアップ

```bash
pip install -r requirements.txt

