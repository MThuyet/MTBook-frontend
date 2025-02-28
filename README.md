# Hướng dẫn cài đặt và chạy dự án

## 1. Môi trường chạy

- **Node.js v20.14.0**
  - Tải tại: [Node.js v20.14.0](https://nodejs.org/download/release/v20.14.0/)

## 2. Cài đặt dự án

### Bước 1: Clone code

```bash
git clone <repo-url>
cd <project-folder>
```

### Bước 2: Cài đặt thư viện

```bash
npm install
```

### Bước 3: Cấu hình biến môi trường

Tạo hoặc cập nhật file `.env.production` hoặc `.env.development` với nội dung sau:

```env
VITE_BACKEND_URL=https://mtbook-backend-8080.onrender.com
VITE_USER_CREATE_DEFAULT_PASSWORD=123456
VITE_BACKEND_PAYMENT_URL=https://mtbook-backend-8888-vnpay.onrender.com
VITE_GOOGLE_CLIENT_ID=1016145229341-2o9mo971og5tpvbgb2qm7c1euf5jks2a.apps.googleusercontent.com
```

### Bước 4: Chạy dự án

```bash
npm run dev
```

---

## 3. Tài khoản truy cập Admin

- **Email**: `adminThuyet@gmail.com`
- **Mật khẩu**: `123456`

---

## 4. Thông tin tài khoản test thanh toán VNPay

- **Ngân hàng**: NCB
- **Số thẻ**: `9704198526191432198`
- **Tên chủ thẻ**: `NGUYEN VAN A`
- **Ngày phát hành**: `07/15`
- **Mật khẩu OTP**: `123456`
