<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的个人网站</title>
    <style>
        body {
            font-family: 'Microsoft YaHei', sans-serif;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            line-height: 1.6;
            color: #333;
        }
        h1 {
            color: #2c3e50;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
        }
        .file-list {
            list-style-type: none;
            padding: 0;
        }
        .file-item {
            margin: 15px 0;
            padding: 10px;
            background-color: #f8f9fa;
            border-radius: 5px;
            transition: all 0.3s;
        }
        .file-item:hover {
            background-color: #e9ecef;
            transform: translateX(5px);
        }
        a {
            color: #2980b9;
            text-decoration: none;
            font-weight: bold;
        }
        a:hover {
            color: #3498db;
            text-decoration: underline;
        }
        .file-icon {
            margin-right: 10px;
            font-size: 1.2em;
        }
    </style>
</head>
<body>
    <h1>欢迎来到我的网站</h1>
    
    
    <h2>文件列表</h2>
    <ul class="file-list">
        <li class="file-item">
            <span class="file-icon">📄</span>
            查看信件 (letter.html)
        </li>
        <li class="file-item">
            <span class="file-icon">🎵</span>
            播放音乐 (music.mp3)
        </li>
    </ul>
</body>
</html>
