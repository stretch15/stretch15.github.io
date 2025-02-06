#Its Popping and more!! balloons backdrops and decor! 
<html. itspoppinandmore.com
 lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Small Business</title>
    <style>
        body {
            background-color: lightblue; /* Change to your desired background color */
            background-image: url('ballons.jpg'); /* Replace with the correct path to your image */
            background-size: cover; /* Adjusts the image to cover the entire background */
            background-repeat: no-repeat; /* Prevents the image from repeating */
            background-position: center; /* Centers the background image */
            font-family: Arial, sans-serif; /* Sets a clean, professional font */
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white; /* Sets the text color to white */
        }
        .content {
            background: rgba(0, 0, 0, 0.5); /* Adds a semi-transparent background to the text */
            padding: 20px;
            border-radius: 10px;
        }
        .dropdown {
            margin-top: 20px;
        }
        .dropdown select {
            padding: 10px;
            font-size: 16px;
        }
    </style>
</head>
<body>
    <div class="content">
        <h1>ITS POPPIN and more!</h1>
        <p>Balloons, Backdrops, and decor</p>
        <div class="dropdown">
            <label for="services">Prices of Services:</label>
            <select id="services">
                <option value="balloons">Balloons - $50</option>
                <option value="backdrops">Backdrops - $100</option>
                <option value="decor">Decor - $150</option>
            </select>
        </div>
    </div>
</body>
</html>
