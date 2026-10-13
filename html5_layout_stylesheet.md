/* Reset CSS cơ bản */
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f9;
    color: #333;
    padding: 20px;
}

/* 1. Styling Header */
.header {
    background-color: #35424a;
    color: #ffffff;
    padding: 20px;
    text-align: center;
    border-bottom: 3px solid #e8491d;
}

/* 2. Styling Nav */
.navbar {
    background-color: #2c3e50;
}

.navbar ul {
    list-style: none;
    display: flex;
    justify-content: center;
}

.navbar li a {
    display: block;
    color: white;
    text-decoration: none;
    padding: 14px 20px;
}

.navbar li a:hover {
    background-color: #e8491d;
}

/* 3. Layout Main Container (Bố cục 2 cột với Flexbox) */
.main-container {
    display: flex;
    margin-top: 20px;
    gap: 20px;
}

/* Section (Nội dung chính chiếm 70% chiều rộng) */
.content-section {
    flex: 3;
    background: #ffffff;
    padding: 20px;
    border-radius: 5px;
}

.article-box {
    background: #eef2f5;
    padding: 15px;
    margin-top: 15px;
    border-left: 4px solid #35424a;
}

/* Aside (Sidebar chiếm 30% chiều rộng) */
.sidebar {
    flex: 1;
    background: #ffffff;
    padding: 20px;
    border-radius: 5px;
}

/* 4. Styling Footer */
.footer {
    background-color: #35424a;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 20px;
}

/* Responsive cho màn hình di động */
@media (max-width: 768px) {
    .main-container {
        flex-direction: column;
    }
}