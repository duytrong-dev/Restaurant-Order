# Backend Restaurant order webapp

Trong file `server/.env` có thuộc tính `COOKIE_MODE`, hãy set `true` nếu bạn muốn dùng cookie cho việc authentication ở server

## Công nghệ sử dụng

Node.js + Fastify + Sqlite

## Cài đặt

```bash
cd server
npm i
npm run dev
```
Or

```bash
npm run build
npm run start
```

Muốn xem thông tin database

```bash
npx prisma studio
```

Nó sẽ chạy ở url [http://localhost:5555](http://localhost:5555)

## Tài khoản

Tài khoản admin: admin@order.com | 123456
Tài khoản user:
- phuminhdat@gmail.com | 123123
- buianhson@gmail.com | 123123
- ngocbichhuynh@gmail.com | 123123
- binhnguyen@gmail.com | 123123


## Config ENV
PORT=4000
DATABASE_URL="file:./dev.db"
ACCESS_TOKEN_SECRET=
ACCESS_TOKEN_EXPIRES_IN=1h
REFRESH_TOKEN_EXPIRES_IN=1d
GUEST_ACCESS_TOKEN_EXPIRES_IN=15m
GUEST_REFRESH_TOKEN_EXPIRES_IN=12h
REFRESH_TOKEN_SECRET=
REFRESH_TOKEN_EXPIRES_IN=1d
INITIAL_EMAIL_OWNER=admin@order.com
INITIAL_PASSWORD_OWNER=123456
DOMAIN=localhost
PROTOCOL=http
UPLOAD_FOLDER=uploads