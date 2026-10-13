# Thực hành: Tạo bố cục hai cột bằng Float và Clear

## Cách chạy
1. Giải nén file ZIP.
2. Mở `index.html` bằng Chrome.
3. Quan sát cột trái màu xanh nhạt và cột phải màu xanh lá nhạt.
4. Thu nhỏ cửa sổ trình duyệt để kiểm tra giao diện trên màn hình nhỏ.

## Yêu cầu đã thực hiện
- Cột trái dùng `float: left` và `width: 60%`.
- Cột phải dùng `float: right` và `width: 38%`.
- Dùng `box-sizing: border-box` để tính cả padding trong chiều rộng.
- Dùng clearfix (`::after` với `clear: both`) cho vùng chứa.
- Phần nội dung bên dưới dùng `clear: both`.
- Có responsive CSS để hai cột xếp chồng trên màn hình nhỏ.
