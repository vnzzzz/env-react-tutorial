# Reactチュートリアルの実行環境

実行環境（開発環境）の準備

## 環境準備手順

1. ビルドと起動

    ```bash
    # ビルド
    docker-compose build

    #プロジェクト作成
    docker-compose run -w /src react-tutorial npx create-react-app app --template typescript --use-npm

    # 起動
    docker-compose up -d
    ```

1. ブラウザにアクセス
    ``にアクセスする
