# DjangoGirlsTutorial

## 参考リンク
### 公式
* [Django Girls - start your journey with programming](https://djangogirls.org/)
    * [Django Girls Tutorial 日本語版](https://tutorial.djangogirls.org/ja/)


## 作業メモ
* pip
  * requirementsファイル出力
    ```commandline
    pip freeze > reuirements.txt
    ```
  * requirementsファイルによるインストール
    ```commandline
    pip install -r requirements.txt
    ```
    
### Django
* [プロジェクトを作成しよう！ · HonKit](https://tutorial.djangogirls.org/ja/django_start_project/)
  * プロジェクト作成
    ```commandline
    django-admin.exe startproject mysite .
    ```

  * DB作成
    ```commandline
    python manage.py migrate
    ```

  * アプリケーション作成
    ```commandline
    python manage.py startapp blog
    ```
    
  * データベースにモデルのテーブルを追加
    ```commandline
    python manage.py makemigrations blog
    ```
    
    ```commandline
    python manage.py migrate blog
    ```

  * 管理ユーザ作成
    ```commandline
    python manage.py createsuperuser
    ```
    * 管理ユーザ
      * ユーザ名： admin
      * パスワード： pass
      * メールアドレス： admin@example.com

  * 管理画面URL
    * http://127.0.0.1:8000/admin/

  * Django shellの起動
    ```commandline
    python manage.py shell
    ```

