<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Website</title>
    <style>
        /* Basic CSS for the layout */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #444;
            text-align: center;
            padding: 10px 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            width: 80%;
            margin: 20px auto;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Simple Website</h1>
    </header>
    <nav>
        <a href="/">Home</a>
        <a href="/contact.html">Contact</a>
    </nav>
    <div class="container">
        <h2>Welcome to our website!</h2>
        <p>This is a simple website with a homepage and a contact page.</p>
    </div>
    <footer>
        &copy; 2024 Simple Website
    </footer>
</body>
</html>
