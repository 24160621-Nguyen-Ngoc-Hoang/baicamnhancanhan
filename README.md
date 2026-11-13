# Website cảm nhận sách – Nguyễn Ngọc Hoàng

## Cấu trúc thư mục

- `index.html`: Trang web chính.
- `css/style.css`: Toàn bộ giao diện và responsive.
- `js/script.js`: Tệp JavaScript để mở rộng tương tác sau này.

## Xem website trên máy tính

1. Giải nén tệp ZIP.
2. Mở thư mục `website_cam_nhan_tuoi_tho`.
3. Nhấp đúp vào `index.html` để mở bằng Chrome, Edge hoặc Firefox.

## Đăng website lên Internet

### Cách 1: Netlify (nhanh, không cần viết thêm mã)
1. Truy cập https://app.netlify.com/drop
2. Đăng nhập hoặc tạo tài khoản Netlify.
3. Kéo thả nguyên thư mục `website_cam_nhan_tuoi_tho` (hoặc giải nén ZIP rồi kéo thả thư mục) vào trang đó.
4. Chờ Netlify xuất bản và cung cấp đường link website.

### Cách 2: GitHub Pages
1. Tạo một repository mới trên GitHub.
2. Tải lên toàn bộ nội dung bên trong thư mục này, giữ nguyên cấu trúc `css/` và `js/`.
3. Vào **Settings → Pages**.
4. Chọn **Deploy from a branch**, chọn nhánh `main` và thư mục `/ (root)`, sau đó nhấn **Save**.
5. GitHub sẽ tạo đường link website sau khi triển khai xong.

## Lưu ý
- Giữ nguyên tên và vị trí các tệp/thư mục để đường dẫn CSS hoạt động.
- Website dùng Google Fonts nên cần kết nối Internet để tải kiểu chữ; nếu mất mạng, trình duyệt sẽ dùng font dự phòng.
- Bạn có thể chỉnh nội dung chữ trực tiếp trong `index.html` và màu sắc/bố cục trong `css/style.css`.
