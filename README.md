# 🌅 Viet Culture Website

Website giới thiệu cho **Công ty TNHH Du lịch và Dịch vụ Viet Culture**.

## 📁 Cấu trúc file

```
vietculture/
├── index.html          # File chính (HTML + CSS + JS gộp trong 1 file)
├── assets/
│   ├── logo.png        # Logo đầy đủ (có chữ Viet Culture)
│   └── logo-icon.jpg   # Logo icon (chỉ biểu tượng mặt trời + chim)
└── README.md           # File hướng dẫn này
```

## 🚀 Cách chạy website

**Cách 1 — Mở trực tiếp:** Click đúp vào file `index.html` để mở bằng trình duyệt.

**Cách 2 — Dùng Live Server (khuyên dùng khi phát triển):**
- Cài VS Code → cài extension "Live Server"
- Chuột phải vào `index.html` → Open with Live Server

## 🎨 Thiết kế

- **Phông chữ:** Playfair Display (tiêu đề - sang trọng) + Be Vietnam Pro (nội dung - hỗ trợ tiếng Việt tốt)
- **Màu chính:**
  - Xanh dương `#1A56DB` (từ logo)
  - Vàng mặt trời `#FFD60A` (từ logo)
  - Navy `#0A1628` (text)
- **Phong cách:** Sang trọng, hiện đại, trẻ trung — phù hợp công ty du lịch cao cấp

## 📝 Cách chỉnh sửa nội dung

Mở file `index.html` bằng trình soạn thảo (Notepad, VS Code, Sublime...). Tìm và sửa các phần sau:

### 1. Thông tin liên hệ
Tìm `+84 964000344` và `vietculture24@gmail.com` → thay bằng số/email thật của bạn.

### 2. Số liệu thống kê (Hero)
Tìm `500+`, `50+`, `10+` → đổi theo số thật của công ty.

### 3. Đổi điểm đến
Tìm phần `<!-- ============ DESTINATIONS ============ -->` để chỉnh sửa các tour.

### 4. Đổi đánh giá khách hàng
Tìm phần `<!-- ============ TESTIMONIALS ============ -->`.

### 5. Đổi ảnh
- Ảnh trong website đang dùng từ Unsplash (miễn phí). Để dùng ảnh riêng:
  - Copy ảnh của bạn vào thư mục `assets/`
  - Đổi đường dẫn `src="https://images.unsplash.com/..."` thành `src="assets/ten-anh.jpg"`

### 6. Đổi link mạng xã hội
Trong phần Footer, tìm `<a href="#" aria-label="Facebook">` → thay `#` bằng URL thật.

