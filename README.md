# Python駿河 公式サイト

　（メモ書きレベルですが、後ほど書き直します。

## 利用しているツール、インフラ

- Python3
- Pelican
- GitHub Actions
- GitHub Pages

## サイトの生成方法

- git clone します
- venv向け
  - `python -m venv .venv`
  - venvを有効
  - `pip install -r requirements.txt`
  - `make devserver` で更新前のサイトを確認できます
  - masterへコミット and Pushをして、GitHub Actionsを稼働させます