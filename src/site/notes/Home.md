---
{"dg-publish":true,"permalink":"/home/","tags":["gardenEntry"]}
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Theme Switcher</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            transition: background-color 0.3s, color 0.3s;
        }
        /* Light theme styles */
        .light-mode {
            background-color: #ffffff;
            color: #333333;
        }
        /* Dark theme styles */
        .dark-mode {
            background-color: #333333;
            color: #ffffff;
        }
        button {
            position: fixed;
            top: 20px;
            right: 20px;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body class="light-mode">
    <button onclick="toggleTheme()">Switch to Dark Mode</button>

    <h1>Welcome to My Digital Garden</h1>
    <p>This is a sample page where you can switch between light and dark themes!</p>

    <script>
        function toggleTheme() {
            var body = document.body;
            var button = document.querySelector('button');
            if (body.classList.contains('light-mode')) {
                body.classList.remove('light-mode');
                body.classList.add('dark-mode');
                button.textContent = 'Switch to Light Mode';
            } else {
                body.classList.remove('dark-mode');
                body.classList.add('light-mode');
                button.textContent = 'Switch to Dark Mode';
            }
        }
    </script>
</body>
</html>

