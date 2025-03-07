# SQLiteとFastAPIの連携

## 必要パッケージのインストール

`pip install -r requirements.txt`

## SQLiteのDBファイル生成

- 以下のコマンドでDBファイルを生成する
`python app/models.py`
- FastAPIを起動
`uvicorn app.main:app`
