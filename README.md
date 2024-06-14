<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home Page</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Montserrat', sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f0f0;
        }
        h1 {
            margin-bottom: 40px;
            font-size: 2.5em;
            color: #333;
        }
        .button-container {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
            justify-content: center;
        }
        .button-container a {
            display: inline-block;
            padding: 15px 30px;
            text-decoration: none;
            color: white;
            background-color: #007BFF;
            border-radius: 50px;
            font-size: 1.2em;
            font-weight: 700;
            transition: background-color 0.3s, transform 0.3s;
        }
        .button-container a:hover {
            background-color: #0056b3;
            transform: scale(1.05);
        }
		
    </style>
</head>
<body>
    <h1>Welcome to My Home Page</h1>
    <div class="button-container">
        <a href="unicolm.html">Unicolm Store</a>
        <a href="resume.html">Resume</a>
        <a href="COR.html">Certificate of Registration (COR)</a>
        <a href="restaurant.html">Restaurant</a>
    </div>
</body>
</html>
