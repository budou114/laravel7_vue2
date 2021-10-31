# 環境構築
1. プロジェクトをローカルにクローンする
   
    ```
    $ git clone [LaravelプロジェクトのURL]
    ```
2. 作成したプロジェクトのディレクトリに移動する
    ```
    $ cd [プロジェクト名]
    ```
4. vendorディレクトリの作成
    ```
    $ composer install
    ```
4. .envのファイルをコピーする
    ```
    $ cp .env.example .env
    ```
5. アプリケーションキーの初期化を実行する
    ```
    $ php artisan key:generate
    ```
6. マイグレーションコマンドの実行(データベースは作成してある前提)
    ```
    $ php artisan migrate
    ```
