# task-manager-app

## 概要

タスクを管理するためのアプリです。
プロジェクトごとにタスクを作成・管理できます。

## 構成

* frontend（React）
* backend（Laravel API）

## リポジトリ

* フロントエンド
  https://github.com/kei220324/project_management_frontend

* バックエンド
  https://github.com/kei220324/project_management_backend

## 使用技術

* フロントエンド：React
* バックエンド：Laravel
* DB：MySQL
* 環境構築：Docker / docker-compose

## 主な機能

* プロジェクト作成
* タスク作成
* タスクの完了/未完了管理
* タスク数の集計表示

## 工夫した点

* タスクの状態からプロジェクトのステータスを算出する設計にした
* N+1問題を防ぐために withCount / loadCount を使用
* APIとフロントの責務を分離した設計

## 今後の改善

* 認証機能の追加
* UI/UXの改善
