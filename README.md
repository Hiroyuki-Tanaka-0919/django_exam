# Django 練習用（Windows編）

- 書名：Django4 Webアプリ開発 実装ハンドブック
- 著者：チーム・カルポ

## 開発環境

- OS：Windows 11 Pro (26H2)
- コンソール：PowerShell 7.6.6 
- Pythonの管理：Python Install Manager
- Pythonのバージョン：Python 3.8.10
- 仮想環境の管理：uv 0.13.7
- フレームワーク：Django 4.0.2
- データベース：SQLite3 3.35.5

## プロジェクトのダウンロード
```
> git clone https://github.com/Hiroyuki-Tanaka-0919/django_exam.git
> cd django_exam
```
## Python Install Managerの導入
```
winget install 9NQ7512CXL7T
```
## Pythonの導入(3.8.10)
```
> py install 3.8
> py list
```
## uvの導入
```
> winget install --id astral-sh.uv --exact
> uv --version
```
## uvでプロジェクトを初期化する(簡易版)
```
> uv init --no-package
```
## 仮想環境の設定(※アクティベートの自動化)
```
> Get-ChildItem -Force
```
## パッケージの追加
```
> uv add -r requirements.txt
```
## DataBaseの初期化
```
> uv run manage.py migrate
```
## Djangoの起動
```
> uv run manage.py runserver
```
## サイトの表示
- ブラウザを起動して http://127.0.0.1:8000 に移動

## Djangoの停止
```
> Ctrl + C
```
## とりあえずchap04で動作確認
```
> cd .\chap04\blogproject
> uv run manage.py migrate ※初回のみ
> uv run manage.py runserver
- ブラウザを起動して http://127.0.0.1:8000 に移動
> Ctrl + C ※サーバーの停止
```

## 進捗
- 2026/08/30：第1章～第3章まで完了
- 2026/08/31：第4章～第5章まで完了
- 2026/09/01：第6章まで完了
- 2026/09/03：第7章～第8章まで完了
- 2026/11/12：仮想環境の管理をuvに変更
