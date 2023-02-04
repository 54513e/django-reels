# django-reels
INSTALLED_APPに
    'app',
    'graphene_django',
    'corsheaders' を追加
    
MIDDLEWAREに 'django.middleware.clickjacking.XFrameOptionsMiddleware', を追加

CSRF 対策を無効にするためにcsrf_exemptを使用。

CSRF 対策を無効にしないと、フロントエンドから GraphQL API をコールできなくなる
