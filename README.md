# Laravel-CleanArchitecture
## 概要
- クリーンアーキテクチャについて学んだことをLalavelで実践
- 簡単なアプリケーションを作りながらフロントの学習も並行で実践

## 使用技術
- バックエンド
    - PHP8系
        - laravel8系
- フロントエンド
    - React
- インフラ
    - ECS
    - Fargate
    - 出来たらteraformで構成管理したい

## 参考資料
- https://qiita.com/nrslib/items/a5f902c4defc83bd46b8

## コンテナ起動手順
```
./vendor/bin/sail up -d
```

## アプリケーション概要
### 機能一覧
- ログイン・ログアウト
- ユーザー一覧の表示
- ユーザー登録
- マイページ
    - ユーザー情報の編集
    - 退会