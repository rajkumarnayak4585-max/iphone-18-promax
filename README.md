```html
<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Raj Kumar Nayak - iPhone</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #111, #444);
            color: white;
            text-align: center;
        }

        header {
            padding: 25px;
            background: #000;
        }

        .phone {
            width: 260px;
            height: 480px;
            margin: 35px auto;
            padding: 15px;
            background: black;
            border: 5px solid silver;
            border-radius: 40px;
            box-shadow: 0 0 25px #999;
            box-sizing: border-box;
        }

        .screen {
            height: 100%;
            border-radius: 27px;
            background: linear-gradient(#6dd5fa, #2980b9);
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }

        .screen h2 {
            font-size: 25px;
        }

        .screen p {
            font-size: 17px;
        }

        button {
            padding: 12px 20px;
            margin-top: 15px;
            border: none;
            border-radius: 25px;
            background: white;
            color: #111;
            font-size: 16px;
            cursor: pointer;
        }

        footer {
            padding: 20px;
        }
    </style>
</head>

<body>
    <header>
        <h1>📱 My iPhone Website</h1>
        <p>Created by Raj Kumar Nayak</p>
        <p>Class 9th</p>
    </header>

    <div class="phone">
        <div class="screen">
            <h2> iPhone</h2>
            <p>Welcome!</p>
            <p>Raj Kumar Nayak</p>
            <p>Class 9th Student</p>
            <button onclick="showMessage()">
                Click Me
            </button>
        </div>
    </div>

    <footer>
        <p>Made with ❤️ by Raj Kumar Nayak</p>
    </footer>

    <script>
        function showMessage() {
            alert("Hello! I am Raj Kumar Nayak, Class 9th student!");
        }
    </script>
</body>
</
