# Trang Chủ Giản Lược

Bài thực hành tạo giao diện trang chủ bằng HTML và CSS.

## Tệp trong dự án
- `index.html`: cấu trúc trang, header, sidebar trái, nội dung chính và sidebar phải.
- `style.css`: giao diện, Flexbox, header cố định, z-index và responsive.

## Cách chạy
1. Giải nén thư mục.
2. Mở `index.html` bằng trình duyệt (Chrome/Edge).
3. Cuộn trang để kiểm tra header vẫn cố định.

## Đẩy lên GitHub
Mở Terminal/CMD tại thư mục dự án rồi chạy:

```bash
git init
git add index.html style.css README.md
git commit -m "Create simplified homepage layout"
git branch -M main
git remote add origin https://github.com/USERNAME/REPOSITORY.git
git push -u origin main
```

Thay `USERNAME/REPOSITORY` bằng đường dẫn repository GitHub của bạn. Nếu repository đã có sẵn remote, không chạy lại lệnh `git remote add origin`; hãy dùng `git remote -v` để kiểm tra.
