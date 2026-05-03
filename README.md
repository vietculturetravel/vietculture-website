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
Tìm `+84 123 456 789` và `info@vietculture.vn` → thay bằng số/email thật của bạn.

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

## 🌐 Đăng lên internet (deploy)

Có nhiều cách đăng website lên mạng miễn phí:

**Cách dễ nhất — Netlify (miễn phí):**
1. Vào https://netlify.com → Đăng ký
2. Kéo thả thư mục `vietculture` vào trang Netlify
3. Xong! Bạn sẽ có một URL dạng `vietculture-xxxx.netlify.app`

**Cách 2 — Vercel:** Tương tự Netlify, vào https://vercel.com

**Cách 3 — Mua tên miền `vietculture.vn`:** Đăng ký tại các nhà cung cấp như Mắt Bão, PA Vietnam, GoDaddy... rồi trỏ về Netlify/Vercel.

## 🔧 Tính năng đã có

- ✅ Responsive (chạy tốt trên điện thoại, tablet, máy tính)
- ✅ Animation mượt mà khi scroll
- ✅ Menu sticky (cố định khi cuộn)
- ✅ Hover effects đẹp mắt
- ✅ Mobile menu (cơ bản)
- ✅ SEO meta tags cơ bản

## 💡 Có thể bổ sung sau

- Form liên hệ (cần backend hoặc dịch vụ như Formspree/Netlify Forms)
- Trang chi tiết từng tour
- Trang blog/tin tức
- Tích hợp Google Maps
- Tích hợp chat Messenger/Zalo
- Đa ngôn ngữ (Việt/Anh)
- Hệ thống đặt tour online

---

Mọi thắc mắc hoặc muốn nâng cấp thêm tính năng, cứ liên hệ Claude nhé! 🚀
