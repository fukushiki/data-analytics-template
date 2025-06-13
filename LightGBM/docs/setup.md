
# LightGBMテンプレート用 環境セットアップガイド

このドキュメントでは、LightGBM関連のJupyter Notebookを実行するためのPython環境セットアップ手順を説明します。

---

## 推奨環境

- **Python** 3.10以上
- **pip**
- **Jupyter Notebook**

---

## セットアップ手順

### 1. 仮想環境の作成と有効化

プロジェクトルートで以下のいずれかの方法を実行します。

#### venvの場合(推奨)

```bash
python -m venv .venv
source .venv/bin/activate
```

#### condaの場合
```bash
conda create -n foxhub-lightgbm python=3.10
conda activate foxhub-lightgbm
```

2. 必要なパッケージのインストール
requirements.txtを使用して依存パッケージをインストールします。

```bash
pip install -r templates/lightgbm/docs/requirements.txt
```

3. Jupyter Notebookの起動
以下のコマンドを実行してNotebookを起動します。

```bash
jupyter notebook templates/lightgbm/notebooks/
```

⚠️ 問い合わせ先
セットアップに関する質問・問題がある場合は以下にお問い合わせください。

Data Analytics CoE Team
data-team@example.com
Slack: #foxhub-support