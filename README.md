<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tereza Blažková - Academic Website</title>
    <style>
/* Reset margin and padding on the whole page */
html, body {
    margin: 0;
    padding: 0;
    height: 100%;
    background-color: #5E716A;
    color: #fff;
    font-family: Arial, sans-serif;
    box-sizing: border-box;
}

/* Ensure no extra border, outline, or box-shadow on the header */
header {
    background-color: #333;
    color: #fff;
    padding: 1rem;
    text-align: center;
    margin: 0;
    border: none; /* Ensure no borders */
    outline: none; /* Remove any outlines */
    box-shadow: none; /* Remove any box-shadow */
    border-radius: 8px 8px 0 0; /* Rounded corners */
}

/* Reset margin and padding for all elements to avoid extra lines */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Container styling for header and nav */
.header-container, .container {
    max-width: 800px;
    margin: 2rem auto;
    width: 100%;
}

nav {
    display: flex;
    justify-content: center;
    background-color: #333;
    padding: 0.5rem;
    margin: 0;
    border: none;
    border-radius: 0 0 8px 8px;
    flex-wrap: wrap;
}

nav a {
    color: #fea585;
    padding: 1rem;
    text-decoration: none;
    display: block;
    transition: background-color 0.3s;
}

nav a:hover {
    background-color: #444;
}

/* Section styling */
section {
    margin-bottom: 2rem;
    padding: 1rem;
    background-color: #333;
    border-radius: 8px;
}

h1, h2 {
    color: #fff;
    margin: 0;
}

p {
    margin: 0.5rem 0;
}

footer {
    text-align: center;
    padding: 1rem;
    background-color: #111;
    color: #fff;
    position: fixed;
    width: 100%;
    bottom: 0;
}

/* Additional styling for white text */
a {
    color: #fff;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

/* Hide unwanted link generated by GitHub Pages */
a[href="https://tereza-blazkova.github.io/"] {
    display: none;
}

/* Media query for smaller screens */
@media (max-width: 600px) {
    body {
        font-size: 0.9rem;
    }
    header {
        padding: 0.5rem;
    }
    nav a {
        padding: 0.5rem;
    }
    .container {
        padding: 1rem;
    }
    footer {
        font-size: 0.8rem;
    }
}
    </style>
</head>
<body>
    <!-- Container to wrap the header and nav elements for uniform width -->
    <div class="header-container">
        <header>
            <h1>Tereza Blažková</h1>
            <!--     <h1>(WEBSITE UNDER CONSTRUCTION)</h1> -->
            <p>PhD Student in Social Data Science at the University of Copenhagen</p>
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
            <p>Hi! My name is Tereza and I am a PhD student in Social Data Science at the University of Copenhagen. My research focuses on the use of data for improving educational outcomes and on algorithm audits. My academic interests revolve around responsible AI, algorithmic fairness, algorithm auditing, data governance, education data science and sustainability. I am particularly interested in using qualitative and quantitative mixed methods approach to ensure that an algorithm design corresponds to the needs of the environment in which it operates.</p>
        </section>
        <section id="publications">
            <h2>Publications</h2>
            <ul>
                <li>Tereza Blazkova, Esben Rahbek Gjerdrum Pedersen, Kirsti Reitan Andersen, Francesco Rosati - <a href="https://www.sciencedirect.com/science/article/pii/S0959652623034182" style="color: #fea585;">Greenwashing debates on Twitter: Stakeholders and critical topics</a></li>
                <li>Tereza Blazkova, Esben Rahbek Gjerdrum Pedersen, Kirsti Reitan Andersen - <a>Sentiments and Sustainability: Stakeholder Perceptions of Sustainable Fashion on Social Media</a> (Under review)</li>
            </ul>
        </section>
        <section id="blog">
            <h2>Blog</h2>
            <ul>
                <li><a href="my-motivation.html" style="color: #fea585;">My motivation to have a personal website</a> - A brief overview of why I created this website and what I hope to achieve with it.</li>
            </ul>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <ul>
                <li>Email: <a href="mailto:tebla@sodas.ku.dk" style="color: #fea585;">tebla@sodas.ku.dk</a></li>
                <li>LinkedIn: <a href="https://www.linkedin.com/in/tblazkova/" style="color: #fea585;">linkedin.com/in/tblazkova/</a></li>
                <li>Google Scholar: <a href="https://scholar.google.com/citations?user=BPCG6uoAAAAJ&hl=cs" style="color: #fea585;">Google Scholar profile</a></li>
                <li>X: <a href="https://twitter.com/tereza_blazek" style="color: #fea585;">@tereza_blazek</a></li>
            </ul>
        </section>
        <section id="cv">
            <h2>CV</h2>
            <p>You can view or download my CV using the links below:</p>
            <!-- Link to view the CV in the browser -->
            <a href="cv.pdf" target="_blank" style="color: #fea585;">View CV (PDF)</a>
            <br>
            <!-- Link to download the CV -->
            <a href="cv.pdf" download style="color: #fea585;">Download CV (PDF)</a>
        </section>
    </div>
</body>
</html>
