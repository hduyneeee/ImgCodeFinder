<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ImgCodeFinder</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>📸 ImgCodeFinder</h1>

        <div class="upload-section">
            <input type="text" id="imageCode" placeholder="Nhập mã code">
            <input type="file" id="imageUpload">
            <button onclick="saveImage()">📥 Lưu Ảnh</button>
        </div>

        <div class="search-section">
            <input type="text" id="searchCode" placeholder="Nhập mã code tìm ảnh">
            <button onclick="searchImage()">🔍 Tìm Kiếm</button>
        </div>

        <div id="result"></div>
    </div>

    <script src="script.js"></script>
</body>
</html>
