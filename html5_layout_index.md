<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bài tập Tạo layout với HTML5 & CSS</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header: Phần đầu trang -->
    <header class="header">
        <h1>Header (Tiêu đề website)</h1>
    </header>

    <!-- Nav: Thanh điều hướng -->
    <nav class="navbar">
        <ul>
            <li><a href="#">Trang chủ</a></li>
            <li><a href="#">Giới thiệu</a></li>
            <li><a href="#">Dịch vụ</a></li>
            <li><a href="#">Liên hệ</a></li>
        </ul>
    </nav>

    <!-- Container chứa phần nội dung chính và thanh bên -->
    <div class="main-container">
        
        <!-- Section: Khu vực chứa các bài viết/nội dung chính -->
        <section class="content-section">
            <h2>Nội dung chính (Section)</h2>
            
            <article class="article-box">
                <h3>Bài viết 1 (Article)</h3>
                <p>Đây là nội dung của bài viết thứ nhất. Thẻ article dùng để đóng gói một nội dung độc lập, có thể tái sử dụng.</p>
            </article>

            <article class="article-box">
                <h3>Bài viết 2 (Article)</h3>
                <p>Đây là nội dung của bài viết thứ hai. Các thẻ HTML5 giúp cấu trúc trang web rõ ràng và tối ưu cho SEO.</p>
            </article>
        </section>

        <!-- Aside: Thanh bên chứa thông tin phụ -->
        <aside class="sidebar">
            <h3>Thanh bên (Aside)</h3>
            <p>Chứa thông tin bổ sung, danh mục, hoặc quảng cáo.</p>
        </aside>

    </div>

    <!-- Footer: Phần chân trang -->
    <footer class="footer">
        <p>&copy; 2026 Layout HTML5 & CSS. Bản quyền thuộc về tác giả.</p>
    </footer>

</body>
</html>