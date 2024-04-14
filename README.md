[イメージ画像]

### URL

### サービス概要

### 開発背景

### ディレクトリ構成
```
money-compass/
├── docker-compose.yml
├── dev-env/
│   ├── Dockerfile-client
│   ├── Dockerfile-server
│   ├── vscde-server.sh
│   └── README.md
├── client/
│   ├── public/
│   │   ├── favicon.ico
│   │   └── index.html
│   ├── src/
│   │   ├── App.vue
│   │   ├── components/
│   │   │   ├── Header.vue
│   │   │   ├── Footer.vue
│   │   │   └── Sidebar.vue
│   │   ├── pages/
│   │   │   ├── Home.vue
│   │   │   ├── About.vue
│   │   │   └── Simulator.vue
│   │   ├── router.js
│   │   ├── store/
│   │   │   ├── index.js
│   │   │   └── modules/
│   │   │       └── auth.js
│   │   ├── main.js
│   │   └── styles/
│   │       ├── global.css
│   │       ├── components.css
│   │       └── pages.css
│   └── package.json
├── server/
│   ├── cmd/
│   │   ├── main.go
│   ├── internal/
│   │   ├── api/
│   │   │   ├── auth.go
│   │   │   ├── simulation.go
│   │   │   └── user.go
│   │   ├── config/
│   │   │   ├── config.go
│   │   │   └── env.go
│   │   ├── database/
│   │   │   ├── db.go
│   │   │   └── models.go
│   │   └── logger.go
│   └── go.mod
├── README.md
└── LICENSE
```