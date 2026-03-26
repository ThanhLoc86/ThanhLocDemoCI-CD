# Thanh Loc Demo - Node.js Web App

Trang web đơn giản được xây dựng bằng Node.js, sẵn sàng cho CI/CD deployment.

## Yêu cầu
- Node.js (phiên bản 14 trở lên)
- npm

## Hướng dẫn cài đặt

```bash
# 1. Cài đặt dependencies
npm install

# 2. Chạy ứng dụng
npm start
```

Mở trình duyệt và truy cập: `http://localhost:3000`

## Cấu trúc dự án

```
ThanhLocDemoCI-CD/
├── app.js                 # File server chính
├── package.json           # Dependencies
├── public/
│   └── index.html        # Trang web chính
├── .gitignore
└── README.md
```

## API Endpoints

- `GET /` - Trang chủ
- `GET /api/status` - Kiểm tra trạng thái ứng dụng

## Tiếp theo

Sau khi kiểm tra ứng dụng chạy bình thường, bạn có thể:
1. Tạo Dockerfile
2. Deploy lên Docker Hub
3. Thiết lập GitHub Actions CI/CD
