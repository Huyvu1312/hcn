# Slide Tổng quan — Hệ thống Quản lý Chuỗi Điểm bán

Slide HTML dùng [Reveal.js](https://revealjs.com/) để trình bày tổng quan module `store_management`.

## Cách xem slide

### Cách 1: Mở trực tiếp bằng browser (đơn giản nhất)

```bash
open addons/store_management/docs/slides/index.html
```

Hoặc double-click file `index.html` trong Finder.

> Lưu ý: cần có kết nối Internet vì slide load Reveal.js, Font Awesome, Google Fonts từ CDN.

### Cách 2: Chạy local server (khuyên dùng — tránh lỗi CORS)

```bash
cd addons/store_management/docs/slides
python3 -m http.server 8080
```

Sau đó mở: <http://localhost:8080>

### Cách 3: Live Server (VSCode/Cursor)

1. Cài extension **Live Server** trong VSCode/Cursor
2. Click chuột phải vào `index.html` → **Open with Live Server**

## Điều khiển khi trình chiếu

| Phím | Chức năng |
|------|-----------|
| `→` / `Space` | Slide tiếp theo |
| `←` | Slide trước |
| `F` | Toàn màn hình (Fullscreen) |
| `Esc` / `O` | Xem tổng thể (Overview mode) |
| `S` | Mở Speaker View (notes) |
| `B` / `.` | Black screen (tạm dừng) |
| `?` | Xem tất cả phím tắt |

## Xuất PDF

1. Mở slide trong **Chrome/Edge**
2. Thêm `?print-pdf` vào URL: `index.html?print-pdf`
3. Mở Print dialog (`Cmd+P` / `Ctrl+P`)
4. Chọn **Save as PDF**
5. Đặt:
   - **Layout:** Landscape
   - **Paper size:** A4 hoặc Letter
   - **Margins:** None
   - **Background graphics:** ON ✓

## Cấu trúc nội dung

| # | Section | Nội dung |
|---|---------|----------|
| 1 | Title | Trang bìa giới thiệu |
| 2 | Agenda | Nội dung trình bày |
| 3 | 01 Bối cảnh | Câu chuyện kinh doanh |
| 4 | 01 Quy trình NV | Quy trình hiện tại — Nhân viên |
| 5 | 01 Quy trình QL | Quy trình hiện tại — Quản lý |
| 6 | 02 Khó khăn | Pain points 2 phía |
| 7 | 03 Giải pháp | Odoo ERP + Mobile App |
| 8 | 04 Kiến trúc | 3 nhóm người dùng |
| 9 | 04.1 Admin Odoo | Chi tiết admin hệ thống |
| 10 | 04.2 Admin CH | Chi tiết admin cửa hàng |
| 11 | 04.3 Mobile App | Chi tiết app nhân viên |
| 12 | 05 Giá trị | 3 góc nhìn (NV/QL/DN) |
| 13 | 05 So sánh | Before/After triển khai |
| 14 | Closing | Kết thúc |

## Tuỳ chỉnh

- **Nội dung slide:** Sửa file `index.html`
- **Phong cách / màu sắc:** Sửa file `styles.css` (palette tại `:root`)
- **Logo / hình ảnh:** Đặt vào cùng thư mục, reference bằng path tương đối
