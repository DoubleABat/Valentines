# Hey Loser
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Be My Valentine?</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            text-align: center;
            background-color: #ffebee; /* Light pink background */
            margin: 0;
            padding: 0;
        }
        .container {
            margin-top: 50px;
            padding: 20px;
            background-color: #ffffff; /* White container */
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            display: inline-block;
            position: relative;
            max-width: 400px; /* Limiting container width for better readability */
            margin: 0 auto; /* Centering container */
        }
        h1 {
            color: #e91e63; /* Pink text */
            font-size: 36px;
            margin-bottom: 10px;
        }
        p {
            font-size: 18px;
            color: #9c27b0; /* Purple text */
            margin-bottom: 20px;
            line-height: 1.6; /* Increased line height for better readability */
        }
        button {
            padding: 12px 24px; /* Slightly larger button padding */
            font-size: 18px; /* Increased button font size */
            background-color: #e91e63; /* Pink button */
            color: white; /* White text */
            border: none;
            cursor: pointer;
            border-radius: 30px; /* Rounder button corners */
            margin: 10px;
            transition: background-color 0.3s;
        }
        button:hover {
            background-color: #c2185b; /* Darker pink on hover */
        }
        .heart {
            font-size: 50px;
            color: #e91e63; /* Pink heart */
            margin-bottom: 20px;
        }
        .hearts-container {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            overflow: hidden;
            z-index: -1;
        }
        .heart {
            position: absolute;
            width: 100px;
            height: 100px;
            opacity: 0;
            animation: fall 4s linear infinite;
            transform: rotate(45deg);
        }
        .heart::after {
            content: "❤️";
        }
        @keyframes fall {
            0% {
                transform: translateY(-100vh) rotate(45deg);
                opacity: 1;
            }
            100% {
                transform: translateY(100vh) rotate(45deg);
                opacity: 0;
            }
        }
    </style>
</head>
<body>
    <div class="hearts-container">
        <!-- Add multiple hearts for a cuter effect -->
        <div class="heart" style="left: 10%; animation-delay: 0s;"></div>
        <div class="heart" style="left: 20%; animation-delay: 1s;"></div>
        <div class="heart" style="left: 30%; animation-delay: 2s;"></div>
        <div class="heart" style="left: 40%; animation-delay: 3s;"></div>
        <div class="heart" style="left: 50%; animation-delay: 4s;"></div>
        <div class="heart" style="left: 60%; animation-delay: 5s;"></div>
        <div class="heart" style="left: 70%; animation-delay: 6s;"></div>
        <div class="heart" style="left: 80%; animation-delay: 7s;"></div>
        <div class="heart" style="left: 90%; animation-delay: 8s;"></div>
    </div>
    <div class="container">
        <span class="heart">❤️</span>
        <h1>Will You Be My Valentine?</h1>
        <p>Hey Baby♥️</p>
        <p>I know you're on the other side of the world but,</p>
        <p>Will you make me the happiest person by being my Valentine?
Ayma Ciel Larroza</p>
        <button onclick="alert('I love you:)')">Yes</button>
        <button onclick="alert('What did you expect?:p')">Yes</button>
    </div>
</body>
</html>
