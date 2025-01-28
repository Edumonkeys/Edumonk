---
{"dg-publish":true,"permalink":"/home/","contentClasses":"","tags":["gardenEntry"],"noteIcon":true}
---

# <div style="font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;">Edumonkeys</div>
## [[About \|:luc_menu:]] When Good to Go 

# good,

dfkjshjk
# Journals

How can i helpYu

# Find Yourself
 the Great Journey Begins in the World of thd contents management

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Funky Card View</title>
    <link href="https://fonts.googleapis.com/css2?family=Recoleta:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Recoleta', sans-serif;
            background: #dcdcdc; /* Light gray background */
            padding: 20px;
        }
        .card-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            width: 700px;
            margin: 0 auto;
            gap: 20px;
        }
        .card {
            width: 300px;
            height: 350px;
            background: #f0f8ff; /* Light gray background */
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            overflow: hidden;
            transition: transform 0.3s, box-shadow 0.3s, background 0.3s;
            cursor: pointer;
            position: relative;
        }
        .card:hover {
            transform: translateY(-10px);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.4);
        }
        .card .card-header {
            padding: 20px;
            color: black; /* Changed to black */
            text-align: center;
            font-size: 20px;
            font-weight: bold;
        }
        .card .card-body {
            padding: 15px;
            color: black; /* Changed to black */
            text-align: center;
            font-size: 16px;
        }
        .card:nth-child(1):hover, .card:nth-child(2):hover {
            background: linear-gradient(135deg, #FF7F50, #FFD700); /* Funky color */
        }
        .card:nth-child(3):hover, .card:nth-child(4):hover {
            background: linear-gradient(135deg, #7FFFD4, #1E90FF); /* Funky color */
        }
        .card:nth-child(5):hover, .card:nth-child(6):hover {
            background: linear-gradient(135deg, #FF69B4, #8A2BE2); /* Funky color */
        }

        /* Adjust card layout when in two columns (Parallel up and down) */
        @media (min-width: 600px) {
            .card-container {
                display: grid;
                grid-template-columns: repeat(2, 1fr);
                gap: 20px;
            }
        }
    </style>
</head>
<body>

    <div class="card-container">
        <!-- Card 1 -->
        <div class="card">
            <div class="card-header">Funky Card 1</div>
            <div class="card-body">Hover to see the magic!</div>
        </div>

        <!-- Card 2 -->
        <div class="card">
            <div class="card-header">Funky Card 2</div>
            <div class="card-body">Hover to see the magic!</div>
        </div>

        <!-- Card 3 -->
        <div class="card">
            <div class="card-header">Funky Card 3</div>
            <div class="card-body">Hover to see the magic!</div>
        </div>

        <!-- Card 4 -->
        <div class="card">
            <div class="card-header">Funky Card 4</div>
            <div class="card-body">Hover to see the magic!</div>
        </div>

        <!-- Card 5 -->
        <div class="card">
            <div class="card-header">Funky Card 5</div>
            <div class="card-body">Hover to see the magic!</div>
        </div>

        <!-- Card 6 -->
        <div class="card">
            <div class="card-header">Funky Card 6</div>
            <div class="card-body">Hover to see the magic!</div>
        </div>

        <!-- Card 7 (Optional) -->
        <div class="card">
            <div class="card-header">Funky Card 7</div>
            <div class="card-body">Hover to see the magic!</div>
        </div>
    </div>

</body>
</html>,
