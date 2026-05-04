

フォルダ構成
sample-python-project/
├── .venv/　             #Pythonの仮想環境
├── .vscode/             #VScodeの設定フォルダ
│   └── settings.json 
├── data/
│   ├── raw/             #生データ保管場所
│   └── processed/       #前処理・加工後のデータ
├── notebooks/           #Jupyter Notebookを置く場所、EDA用
├── src/                 #本番用のPythonコード置き場
├── tests/               #テストコード置き場
├── main.py              #エントリーポイント（実行用スクリプト）、処理をまとめて実行するためのファイル
├── pyproject.toml       #プロジェクトの設定ファイル、使用するライブラリを管理
├── uv.lock              #ライブラリのバージョンを固定するファイル
└── README.md