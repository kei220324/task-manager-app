# Project Management App

## 概要

プロジェクトとタスクを管理するアプリです。  
Reactでフロントエンドを構築し、
LaravelでREST APIを作成しています。

---

## 使用技術

- フロントエンド：React
- バックエンド：Laravel
- DB：MySQL
- 環境構築：Docker / docker-compose

---

## 主な機能

- プロジェクト作成
- タスク作成
- タスクの完了 / 未完了管理
- タスク数の集計表示

---

## リポジトリ構成

### Frontend
React を利用したフロントエンドです。

- 状態管理
- API通信
- モーダル管理
- 一覧 / 詳細画面実装

などを行っています。

### Backend
Laravel を利用したREST APIです。

- プロジェクト / タスク管理API
- withCount を利用した集計処理
- status算出
- N+1問題を意識したデータ取得

などを行っています。

---

## README

- [Frontend README](https://github.com/kei220324/project_management_frontend)
- [Backend README](https://github.com/kei220324/project_management_backend)

それぞれの詳細は各READMEに記載しています。
