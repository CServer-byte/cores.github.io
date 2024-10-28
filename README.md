<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <video src="Testing/something/Tests/Quatsch/youtubeDownloader/video_path/Never Gonna Give You Up.mp4"></video>
    <h1>Ein Fehler ist aufgetreten!</h1>
    <button onclick="btnClick()">Erneut initialisieren</button>
    <style>
        video {
            width: 100%;
            max-height: 100%;
            display: none;
        }
        button {
            border: none;
            width: 90px;
            border-radius: 4px;
            background-color: red;
            color: white;
        }
    </style>
    <script>
        function hideError(){
            document.querySelector('h1').style.display = 'none'
            document.querySelector('button').style.display = 'none'
        }
        function btnClick(){
            hideError()
            document.querySelector('video').style.display = 'unset'
            document.querySelector('video').play()
        }
    </script>
</body>
</html>
