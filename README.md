<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Wish</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #fce4ec;
            margin: 0;
        }
        .birthday-card {
            text-align: center;
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .birthday-card h1 {
            color: #e91e63;
            font-size: 2.5em;
        }
        .birthday-card p {
            color: #333;
            font-size: 1.2em;
        }
        .birthday-card a {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #e91e63;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1em;
            transition: background-color 0.3s ease;
        }
        .birthday-card a:hover {
            background-color: #c2185b;
        }
        .hidden {
            display: none;
        }
        .message {
            margin-top: 20px;
            font-size: 1.5em;
            color: #e91e63;
        }
    </style>
</head>
<body>

<div class="birthday-card">
    <h1>🎉 Happy Birthday! 🎉</h1>
    <p>Click the button below to reveal a special message!</p>
    <a href="#" onclick="showMessage()">Click Me!</a>
    <div id="birthdayMessage" class="hidden message">
        Wishing you a day filled with love, laughter, and joy! 🎂🎈
    </div>
</div>

<script>
    function showMessage() {
        document.getElementById('birthdayMessage').classList.remove('hidden');
    }
</script>

</body>
</html># birthday-wish.html
