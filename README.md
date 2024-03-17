<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
        }
  
        nav {
            background-color: #A0F400;
            color: #333;
            padding: 20px 0;
            text-align: center;
        }
        nav a {
            text-decoration: none;
            color: #fff;
            margin: 0 10px;
        }
        nav a:hover {
            color: #A0F400; /* Change link color to green on hover */
        }
        
        section {
            padding: 20px;
        }
        .project {
            border: 1px solid #ccc;
            border-radius: 5px;
            padding: 10px;
            margin-bottom: 20px;
            background-color: #fff;
        }
        .project h2 {
            margin-top: 0;
        }
        
        /* Change text color of the About Me section */
        #about {
            color: #000; /* Change text color to black */
        }

       /* Style the LinkedIn icon */
        .linkedin-icon,
        .github-icon,
        .medium-icon,
        .email-icon {
            width: 40px; /* Adjust the size as needed */
            height: 40px;
            margin-right: 5px; /* Add some spacing */
            background-color: red; /* Set background color to red */
            border-radius: 50%; /* Make the icons circular */
            padding: 5px; /* Add some padding */
        }

        /* Center and style the footer */
        footer {
            text-align: center;
            padding: 10px;
            background-color: #A0F400;
            color: #000;
        }
    </style>
</head>
<body>

<nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <h2>About Me</h2>
    <p>Welcome! I'm passionate about creating innovative and user-friendly applications.</p>
</section>

<section id="skills">
    <h2>Skills</h2>
    <p>Here are some of the skills I possess:</p>
    <ul>
        <li>Java</li>
        <li>Kotlin</li>
        <li>Android SDK</li>
        <li>XML</li>
        <li>RESTful APIs</li>
        <!-- Add more skills as needed -->
    </ul>
</section>

<section id="projects">
    <h2>Projects</h2>
    <div class="project">
        <h2>Project 1</h2>
        <p>Description of Project 1</p>
    </div>
    <div class="project">
        <h2>Project 2</h2>
        <p>Description of Project 2</p>
    </div>
    <!-- Add more projects as needed -->
</section>

<section id="contact">
    <h2>Contact Me</h2>
    <p>If you'd like to get in touch, feel free to email me at <a href="mailto:yourname@example.com">yourname@example.com</a>.</p>

    <!-- LinkedIn Icon with Profile Link -->
    <a href="https://www.linkedin.com/in/your-linkedin-profile" target="_blank">
        <img src="linkedin_icon.png" alt="LinkedIn" width="40" height="40">
    </a>

    <!-- GitHub Icon with Profile Link -->
    <a href="https://github.com/your-github-profile" target="_blank">
        <img src="github_icon.png" alt="GitHub" width="40" height="40">
    </a>

    <!-- Medium Icon with Blog Link -->
    <a href="https://medium.com/@your-medium-profile" target="_blank">
        <img src="medium_icon.png" alt="Medium" width="40" height="40">
    </a>

    <!-- Email Icon with Email Link -->
    <a href="mailto:yourname@example.com" target="_blank">
        <img src="email_icon.png" alt="Email" width="40" height="40">
    </a>
</section>

<footer>
    <p>&copy; 2024 Dulanja Kristhombu</p>
</footer>

</body>
</html>
