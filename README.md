# octocat.github.io
<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>コジーのサイト</title>

   <style>
        body {
            background-color: #f0f0f0;
            font-family: sans-serif;
            text-align: center;
            padding-top: 100px;
        }

        h1 {
            color: blue;
        }

        button {
            font-size: 20px;
            padding: 10px 20px;
        }
    </style>
</head>
<body>

  <h1 id="title">こんにちは コジー</h1>

   <button onclick="changeText()">
        押してみる
    </button>

  <script>
        function changeText() {
            document.getElementById("title").innerHTML =
            "JavaScriptが動いた！";
        }
    </script>

</body>
</html>
