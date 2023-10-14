# octanet
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Travel-Z - Explore the World</title>
    <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">
                TREkTripper
            </div>
            <div class="menu">
                <a href="#" class="active">Home</a>
                <a href="#">Destinations</a>
                <a href="#">Packages</a>
                <a href="#">About Us</a>
                <a href="#">Blog</a>
                <a href="#"class="active">Contact</a>
            </div>
        </nav>

        <div class="container">
            <div class="left">
                <h1>Explore the World with TREkTripper</h1>
                <p>Welcome to TREkTripper, your gateway to unforgettable adventures. Discover amazing destinations, find the perfect travel packages, and make memories that last a lifetime.</p>
                <a href="#" class="cta-button">Start Exploring</a>
            </div>
        </div>
    </header>
</body>
</html>
#css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
}

header {
    width: 100%;
    height: 100vh;
    background-image: url('1ebf481e3ea32a22191ea6292d46dbee.jpg');
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    color: #fff;
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
}

nav {
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 70px;
}

.logo {
    
    font-size: 70px;
    font-weight: bold;
    letter-spacing: 2px;
    color: rgb(186, 180, 13);
    
}

.menu a {
    text-decoration: none;
    font-size: 16px;
    color: #0b0a0a;
    padding: 10px 20px;
    margin: 5px;
    border-radius: 20px 0px 20px 0px;
}

.menu a.active {
    background-color: #4318af;
}

.container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
}

.left {
    max-width: 600px;
    padding: 0 20px;
    text-align: center;
    color: rgb(249, 248, 248);
}

.left h1 {
    font-size: 36px;
    margin-bottom: 20px;
}

.left p {
    font-size: 18px;
    margin-bottom: 20px;
}

.cta-button {
    background-color: #4318af;
    padding: 15px 30px;
    color: #fff;
    text-decoration: none;
    border-radius: 10px;
    font-weight: bold;
    font-size: 18px;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.cta-button:hover {
    background-color: #281fab;
}
