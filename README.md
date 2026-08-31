# Django 練習用（Windows編）

- 書名：Django4 Webアプリ開発 実装ハンドブック
- 著者：チーム・カルポ

## 開発環境

- Windows 11 Pro (25H2)
- Python 3.8.10
- Django 4.0.2
- SQLite3 3.35.5

## ダウンロード
```
> git clone https://github.com/Hiroyuki-Tanaka-0919/django_exam.git
> cd django_exam
```
## 仮想環境の設定と有効化
```
> py -3.8 -m venv venv
> .\venv\Scripts\activate.ps1
```
## Djangoのインストール
```
> py -3.8 -m pip install -r requirements.txt
```
## DataBaseの初期化
```
> py -3.8 manage.py migrate
```
## Djangoの起動
```
> py -3.8 manage.py runserver
```
## サイトの表示
```
http://127.0.0.1:8000
```
## Djangoの停止
```
> Ctrl + C
```
## 仮想環境の終了
```
> deactivate
```

## 進捗
- 2026/08/30：第1章～第3章まで完了
