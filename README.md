# Django x Next.js で GraphQL を試すサンプルプロジェクト

Django で GraphQL の API サーバーを立てて、Next.js で作成した SPA から API を叩くアプリケーションです。
backend/frontend として、それぞれ下記の公開リポジトリを clone しています。

- backend
  https://github.com/tkc310/django_graphql
- frontend
  https://github.com/tkc310/next-csr

## Usage

- backend

```
$ cd backend
$ python3 manage.py migrate
$ python3 manage.py runserver 3001
$ open open http://localhost:3001/graphql

# add admin user
$ python3 manage.py createsuperuser
$ open http://localhost:3001/admin
```

- frontend

```
$ cd frontend
$ npm i
$ npm run build
$ npm run static
```
