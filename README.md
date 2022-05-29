# Reactのチュートリアルをやってみよう

typescriptの勉強もついでに

## 環境準備手順

### ビルドと起動

    ```bash
    # ビルド
    docker-compose build

    #プロジェクト作成
    docker-compose run -w /src react-tutorial npx create-react-app app --template typescript --use-npm

    # 起動
    docker-compose up -d
    ```
