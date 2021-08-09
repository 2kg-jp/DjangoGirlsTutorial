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
    
