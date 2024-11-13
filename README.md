<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tereza Blažková - Academic Website</title>
    <style>
html, body {
    margin: 0;
    padding: 0;
    height: 100%;
    background-color: #5E716A;
    color: #fff;
    font-family: Arial, sans-serif;
    box-sizing: border-box;
}

header {
    background-color: #5E716A;
    color: #fff;
    padding: 1rem;
    text-align: center;
    border-radius: 8px 8px 0 0;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.header-container, .container {
    max-width: 800px;
    margin: 2rem auto;
    width: 100%;
}
nav {
    display: flex;
    justify-content: center;
    background-color: #5E716A;
    padding: 0.5rem;
    border-radius: 0 0 8px 8px;
    flex-wrap: wrap;
}

nav a {
    color: #fea585;
    padding: 1rem;
    text-decoration: none;
    flex: 1 1 auto;
    text-align: center;
}

@media (max-width: 600px) {
    nav a {
        padding: 0.5rem;
        font-size: 0.9rem;
    }
    .header-container, .container {
        margin: 1rem auto;
    }
    footer {
        font-size: 0.8rem;
    }
}

section {
    margin-bottom: 2rem;
    padding: 1rem;
    background-color: #5E716A;
    border-radius: 8px;
}

footer {
    text-align: center;
    padding: 1rem;
    background-color: #111;
    position: fixed;
    width: 100%;
    bottom: 0;
}

a {
    color: #fff;
    text-decoration: none;
}

a[href="https://tereza-blazkova.github.io/"] {
    display: none;
}
    </style>
</head>
<body>
    <div class="header-container">
        <header>
            <h1>Tereza Blažková</h1>
            <p>PhD Student in Social Data Science at the University of Copenhagen</p>
            <p><span style="background-color: pink; color: black;">(WEBSITE UNDER CONSTRUCTION)</span></p>
        </header>
        <nav>
            <a href="#about">About</a>
            <a href="#publications">Publications</a>
            <a href="#blog">Blog</a>
            <a href="#contact">Contact</a>
            <a href="#cv">CV</a>
        </nav>
    </div>
    <div class="container">
        <section id="about">
            <h2>About</h2>
            <p>Hi! My name is Tereza and...</p>
        </section>
        <section id="publications">
            <h2>Publications</h2>
            <p>Here is a list of my publications...</p>
        </section>
        <section id="blog">
            <h2>Blog</h2>
            <p>Welcome to my blog...</p>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>Feel free to reach out...</p>
        </section>
        <section id="cv">
            <h2>CV</h2>
            <p>View my CV here...</p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Tereza Blažková</p>
    </footer>
</body>
</html>
