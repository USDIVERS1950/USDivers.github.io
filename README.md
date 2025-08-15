<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Catalog Downloads</title>
<style>
    body {
        font-family: Arial, sans-serif;
        background: white;
        color: #333;
        text-align: center;
        padding: 50px;
    }
    h1 {
        margin-bottom: 30px;
        font-weight: normal;
    }
    .downloads {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
        gap: 20px;
        max-width: 600px;
        margin: auto;
    }
    .download-item {
        padding: 20px;
        border: 1px solid #eee;
        border-radius: 8px;
        background: white;
    }
    a.download-btn {
        display: inline-block;
        padding: 10px 20px;
        margin-top: 10px;
        background: #e0e0e0;
        color: #333;
        text-decoration: none;
        border-radius: 6px;
        font-size: 14px;
        transition: background 0.3s;
    }
    a.download-btn:hover {
        background: #cfcfcf;
    }
</style>
</head>
<body>

<h1>Download Catalog Assets</h1>
<div class="downloads">
    <div class="download-item">
        <h2>Item 1</h2>
        <a class="download-btn" href="files/item1.jpg" download>Download</a>
    </div>
    <div class="download-item">
        <h2>Item 2</h2>
        <a class="download-btn" href="files/item2.jpg" download>Download</a>
    </div>
    <div class="download-item">
        <h2>Item 3</h2>
        <a class="download-btn" href="files/item3.jpg" download>Download</a>
    </div>
    <div class="download-item">
        <h2>Item 4</h2>
        <a class="download-btn" href="files/item4.jpg" download>Download</a>
    </div>
</div>

</body>
</html>

