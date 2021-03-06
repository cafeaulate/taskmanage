# README

## アプリケーション名
* taskmanage

## アプリケーション概要
* 日々発生する突発的、短納期のタスクを管理する
* 短納期タスクをタスク一覧に表示させ、完了したものは完了タスク一覧へ表示領域を変更することで残タスクを視覚的にわかりやすくする
* 納期が迫っているものに対しては表示文字を赤字にすることでアラートする
* 過去に完了したタスクは履歴から時系列順に確認することができる

## URL

## 利用方法
* フォームにタスクタイトル、タスク詳細(任意)、納期を記入し送信する
* タスク一覧に記載されているタスクが完了したら、そのタスクの詳細表示ページからタスク完了を実行し表示領域を完了タスク一覧に遷移させる

## 目指した課題解決
* 突発的に発生するタスクを視覚化し漏れがないようにする
* 納期が近いタスクをアラートすることでタスク処理の順番を間違えないようにする

## 洗い出した要件
* タスク投稿機能
* 一覧表示機能
* 詳細表示機能
* タスク完了機能
* アラート機能
* リセット機能
* 履歴表示機能
* 履歴詳細表示機能

## 実装した機能についての画像やGIFおよびその説明

## 実装予定の機能

## データベース設計
* tasks テーブル

| Column             | Type       | Options                   |
| ------------------ | ---------- | ------------------------- |
| title              | text       | null: false               |
| detail             | text       |                           |
| delivery           | date       | null: false               |


## ローカルでの動作方法
