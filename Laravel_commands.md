## マイグレーション

データベースのテーブル作成

/database/migrationsに作成される

"""
php artisan make:migration {{ファイル名（行う操作名createとか）}} --create={{テーブル名}}
"""

### Example

booksテーブルを作成する場合

"""
php artisan make:migration create_books_table --create=books
"""

## モデルの作成
データベースのテーブルに対応するモデル

/appに作成される

"""
php artisan make:model {{モデル名}}
"""

### Example

Bookモデルを作成する

"""
php artisan make:model Book
"""
