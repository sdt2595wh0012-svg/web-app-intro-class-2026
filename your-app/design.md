# 私のアプリ設計

## 1. 題材
作った料理、まだ作ったことのない料理を記録し、作った料理は評価をつけるアプリ

## 2. テーブル設計
テーブル名： cooks
カラム： id / title（料理名）/ finished （調理完了 0 or 1）

## 3. 変換表
todos → cooks, done → finished, todo.db → cooks.db, /todos → /cooks