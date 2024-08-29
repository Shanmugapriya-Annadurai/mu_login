//html code

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login - Muu Furniture Store</title>
    <link rel="stylesheet" href="/CSS/login.css">
</head>
<body>

<header>
    <div class="container">
        <h1><a href="Home.html">Muu Furniture Store</a></h1>
        <nav>
            <ul>
                <li><a href="Home.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="login.html">Login</a></li>
            </ul>
        </nav>
    </div>
</header>

<div class="main-container">
    <section class="login">
        <div class="container">
            <h2>Login</h2>
            <form action="/submit-login" method="POST">
                <div class="form-group">
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="password">Password:</label>
                    <input type="password" id="password" name="password" required>
                </div>
                <button type="submit" class="btn">Login</button>
            </form>
            <p>Don't have an account? <a href="register.html">Register here</a>.</p>
        </div>
    </section>
</div>

<footer>
    <div class="container">
        <p>&copy; 2024 Muu Furniture Store. All rights reserved.</p>
    </div>
</footer>

</body>
</html>




//css code 

/* Basic Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body and HTML should take full height */
html, body {
    height: 100%;
    display: flex;
    flex-direction: column;
}

/* Main container to take full height minus header and footer */
.main-container {
    flex: 1;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 20px;
}

/* Header */
header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header h1 a {
    color: #fff;
    text-decoration: none;
}

header nav ul {
    list-style-type: none;
}

header nav ul li {
    display: inline-block;
    margin-right: 20px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

/* Login Section */
.login {
    padding: 50px 0;
    text-align: center;
}

.login .container {
    max-width: 400px;
    margin: 0 auto;
    padding: 0 20px;
}

.login h2 {
    font-size: 2.5em;
    margin-bottom: 20px;
    color: #333;
}

.login form {
    display: flex;
    flex-direction: column;
}

.login .form-group {
    margin-bottom: 15px;
    text-align: left;
}

.login .form-group label {
    display: block;
    margin-bottom: 5px;
    color: #666;
}

.login .form-group input {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 1em;
}

.login .btn {
    padding: 10px 20px;
    background-color: #f39c12;
    color: #fff;
    border: none;
    border-radius: 5px;
    font-size: 1em;
    cursor: pointer;
}

.login .btn:hover {
    background-color: #e67e22;
}

.login p {
    margin-top: 20px;
    color: #352e2e;
}

.login p a {
    color: #e67e22;
    text-decoration: none;
}

.login p a:hover {
    text-decoration: underline;
}

/* Background Image for Body */
body {
    background-image: url('/Source/gray-sofa-white-living-room-interior-with-copy-space-3d-rendering.jpg');
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
}

/* Footer */
footer {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
    flex-shrink: 0; /* Ensures footer does not shrink */
}

footer .container {
    display: flex;
    justify-content: center;
    align-items: center;
}

footer nav ul {
    list-style-type: none;
}

footer nav ul li {
    display: inline-block;
    margin-right: 20px;
}

footer nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}
body{
    background-image: url('/Source/WhatsApp\ Image\ 2024-07-26\ at\ 20.54.49_3dddd8fe.jpg');
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
}
