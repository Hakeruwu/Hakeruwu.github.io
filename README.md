<!DOCTYPE html>
<html>
<head>
    <title>GitHub Clicker</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background: #0d1117;
            color: white;
            padding-top: 100px;
        }

        button {
            font-size: 25px;
            padding: 20px 40px;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            background: #238636;
            color: white;
        }

        button:hover {
            background: #2ea043;
        }

        #count {
            font-size: 50px;
            margin: 20px;
        }
    </style>
</head>

<body>

    <h1>GitHub Clicker</h1>

    <div id="count">0</div>

    <button onclick="clickGit()">💻 Commit!</button>

    <script>
        let commits = 0;

        function clickGit() {
            commits++;
            document.getElementById("count").textContent = commits;
        }
    </script>

</body>
</html>
