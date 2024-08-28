<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> ㅇㅇ </title>
    <script>
        function showImage(imageUrl) {
            document.getElementById('displayedImage').src = imageUrl;
        }
    </script>
</head>
<body>
    <h1 style="text-align: center; font-size: 50px;">사랑해</h1>

    <!-- Links to display images -->
    <p style="text-align: center;">
        <a href="#" onclick="showImage('https://i.pinimg.com/474x/0b/fb/76/0bfb763ce24b11ea734f0b483057452e.jpg'); return false;">이유 1</a> |
        <a href="#" onclick="showImage('https://i.pinimg.com/474x/d3/3a/d4/d33ad47a68b8a9f27b99f26dda227437.jpg'); return false;">이유 2</a>
    </p>

    <!-- Placeholder for the images -->
    <div style="text-align: center;">
        <img id="displayedImage" src="" alt="Choose a reason" style="max-width: 100%; height: auto; margin-top: 20px;" />
    </div>
</body>
</html>
