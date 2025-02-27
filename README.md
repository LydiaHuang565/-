
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>和我一直在一起好不好？</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1 id="question">和我一直在一起好不好？</h1>
        <div class="buttons">
            <button id="yes">好呀！</button>
            <button id="no">不要</button>
        </div>
    </div>

    <script>
        document.getElementById("no").addEventListener("mouseover", function() {
            let btn = this;
            btn.style.position = "absolute";
            btn.style.left = Math.random() * window.innerWidth + "px";
            btn.style.top = Math.random() * window.innerHeight + "px";
        });
        
        document.getElementById("yes").addEventListener("click", function() {
            document.getElementById("question").innerText = "耶！我们永远在一起！💖 半周年快乐";
        });
    </script>
</body>
</html>
