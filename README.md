```
my-project/
├── 📁 api/                          # Backend
│   ├── 📄 server.js                 # Điểm vào chính
│   ├── 📁 config/
│   │   └── 📄 db.js                 # Kết nối MongoDB
│   ├── 📁 models/
│   │   └── 📄 account.model.js      # Mongoose model
│   ├── 📁 controllers/
│   │   └── 📄 account.controller.js # Xử lý HTTP request
│   ├── 📁 services/
│   │   └── 📄 account.service.js    # Logic nghiệp vụ
│   ├── 📁 routes/
│   │   └── 📄 account.routes.js     # Khai báo routes
│   ├── 📁 middlewares/
│   │   └── 📄 errorHandler.js       # Xử lý lỗi
│   ├── 📄 package.json
│   └── 🐳 Dockerfile
│
├── 📁 solution/                     # Frontend
│   ├── 📄 index.html
│   └── 🐳 Dockerfile
│
└── 🐳 docker-compose.yml
```
