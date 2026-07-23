# Nike Landing Page

Trang web Landing Page giới thiệu sản phẩm Nike, được xây dựng nhằm mục đích thực hành và rèn luyện kỹ năng phát triển giao diện web với React và Tailwind CSS.

---

## 🛠️ Công nghệ sử dụng

- **React 18** - Thư viện xây dựng giao diện người dùng
- **Vite** - Tool phát triển và đóng gói ứng dụng tốc độ cao
- **Tailwind CSS v3** - Framework CSS utility-first cho việc thiết kế giao diện
- **JavaScript (ES6+)**

---

## 📌 Các thành phần & Giao diện chính

Dự án bao gồm các phần chính:
- **Header / Navigation ([Nav.jsx](file:///d:/Projects/Fullstack/Nike/src/components/Nav.jsx))**: Thanh điều hướng responsive.
- **Hero Section ([Hero.jsx](file:///d:/Projects/Fullstack/Nike/src/sections/Hero.jsx))**: Giới thiệu bộ sưu tập nổi bật và chuyển đổi nhanh các mẫu giày.
- **Popular Products ([PopularProducts.jsx](file:///d:/Projects/Fullstack/Nike/src/sections/PopularProducts.jsx))**: Danh sách sản phẩm nổi bật.
- **Super Quality ([SuperQuality.jsx](file:///d:/Projects/Fullstack/Nike/src/sections/SuperQuality.jsx))**: Giới thiệu về chất lượng và thiết kế sản phẩm.
- **Services ([Services.jsx](file:///d:/Projects/Fullstack/Nike/src/sections/Services.jsx))**: Thẻ dịch vụ (giao hàng, thanh toán, hỗ trợ).
- **Special Offer ([SpecialOffer.jsx](file:///d:/Projects/Fullstack/Nike/src/sections/SpecialOffer.jsx))**: Thông tin ưu đãi đặc biệt.
- **Customer Reviews ([CustomerReviews.jsx](file:///d:/Projects/Fullstack/Nike/src/sections/CustomerReviews.jsx))**: Đánh giá từ người dùng.
- **Subscribe ([Subscribe.jsx](file:///d:/Projects/Fullstack/Nike/src/sections/Subscribe.jsx))**: Form đăng ký nhận bản tin.
- **Footer ([Footer.jsx](file:///d:/Projects/Fullstack/Nike/src/sections/Footer.jsx))**: Chân trang chứa liên kết và thông tin bản quyền.

---

## 📂 Cấu trúc thư mục

```text
Nike/
├── public/              # Tài nguyên tĩnh (favicon, icons,...)
├── src/
│   ├── assets/          # Hình ảnh sản phẩm, logo và biểu tượng
│   ├── components/      # Component tái sử dụng (Button, Card, Nav,...)
│   ├── constants/       # Dữ liệu tĩnh (danh sách sản phẩm, điều hướng,...)
│   ├── sections/        # Các phần giao diện chính của trang
│   ├── App.jsx          # Component gốc của ứng dụng
│   ├── index.css        # Cấu hình Tailwind CSS và phong cách chung
│   └── main.jsx         # File khởi chạy ứng dụng
├── index.html           # File HTML gốc
├── package.json         # Khai báo thư viện và script
├── tailwind.config.js   # Cấu hình màu sắc, phông chữ Tailwind
└── vite.config.js       # Cấu hình Vite
```

---

## 🚀 Hướng dẫn cài đặt & Chạy ứng dụng

### 1. Yêu cầu hệ thống
- **Node.js**: v16 trở lên
- **npm** (đi kèm theo Node.js) hoặc yarn / pnpm

### 2. Cài đặt dependencies

```bash
npm install
```

### 3. Chạy ở chế độ phát triển (Development)

```bash
npm run dev
```

Mở trình duyệt và truy cập `http://localhost:5173` (hoặc cổng hiển thị trong terminal).

### 4. Đóng gói cho Production

```bash
npm run build
```

Để xem trước bản build:

```bash
npm run preview
```

---

## 📝 Ghi chú

Dự án này là sản phẩm thực hành cá nhân nhằm rèn luyện kỹ năng cắt web, xây dựng bố cục responsive và quản lý component trong React.
