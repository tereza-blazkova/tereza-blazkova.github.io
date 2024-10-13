<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tereza Blažková - Academic Website</title>
    <style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    background-color: #5E716A;
    color: #fff;
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

.page-container {
    max-width: 800px;
    margin: 0 auto;
    padding: 2rem 1rem;
}

header {
    background-color: #333;
    padding: 2rem;
    text-align: center;
    border-radius: 8px 8px 0 0;
}

nav {
    background-color: #333;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    padding: 0.5rem;
    border-radius: 0 0 8px 8px;
}

nav a {
    color: #fea585;
    padding: 0.5rem 1rem;
    text-decoration: none;
    transition: background-color 0.3s;
}

nav a:hover {
    background-color: #444;
}

main {
    margin-top: 2rem;
}

section {
    background-color: #333;
    padding: 2rem;
    margin-bottom: 2rem;
    border-radius: 8px;
}

h1, h2 {
    margin-bottom: 1rem;
}

ul {
    list-style-type: none;
}

a {
    color: #fea585;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

footer {
    background-color: #111;
    color: #fff;
    text-align: center;
    padding: 1rem;
    position: fixed;
    bottom: 0;
    width: 100%;
}

@media (max-width: 600px) {
    body {
        font-size: 0.9rem;
    }
    .page-container {
        padding: 1rem;
    }
    header, section {
        padding: 1rem;
    }
    nav a {
        padding: 0.5rem;
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
