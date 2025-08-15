
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Keti Kvizhinadze</title>
    <style>
        /* Reset default margins and height */
        html, body {
            margin: 0;
            padding: 0;
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            background: #1e1e1e; /* Dark background for effect */
            font-family: 'Arial', sans-serif;
        }

        h1 {
            font-size: 6vw; /* Responsive font size for mobile */
            background: linear-gradient(90deg, #ff6ec4, #7873f5);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-align: center;
            text-shadow: 2px 2px 10px rgba(0,0,0,0.5);
            animation: glow 2s ease-in-out infinite alternate;
        }

        /* Glow animation */
        @keyframes glow {
            0% {
                text-shadow: 2px 2px 10px rgba(0,0,0,0.5);
            }
            50% {
                text-shadow: 2px 2px 20px rgba(255,110,196,0.7), 0 0 30px rgba(120,115,245,0.5);
            }
            100% {
                text-shadow: 2px 2px 10px rgba(0,0,0,0.5);
            }
        }

        /* Make text scale a bit on hover (optional effect) */
        h1:hover {
            transform: scale(1.1);
            transition: transform 0.3s ease-in-out;
        }
    </style>
</head>
<body>
    <h1>Keti Kvizhinadze</h1>
    ![Keti](keti.jpg)

   

</body>
</html>
