<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tereza Blažková - Academic Website</title>
    <style>
        body {
            font-family: 'Courier New', Courier, monospace;
            background-color: #1a1a1a;
            color: #e0e0e0;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #0a0a0a;
            color: #e0e0e0;
            text-align: center;
            padding: 4rem 1rem;
            border-bottom: 5px solid #333;
            letter-spacing: 2px;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #222;
            border-bottom: 3px solid #444;
        }
        nav a {
            color: #e0e0e0;
            text-transform: uppercase;
            padding: 1rem 2rem;
            text-decoration: none;
            letter-spacing: 1.5px;
            font-weight: bold;
            transition: background-color 0.3s, color 0.3s;
        }
        nav a:hover {
            background-color: #444;
            color: #fff;
        }
        .container {
            max-width: 900px;
            margin: 3rem auto;
            padding: 0 1rem;
        }
        section {
            margin-bottom: 3rem;
            padding: 2rem;
            background-color: #111;
            border: 3px solid #333;
            box-shadow: 4px 4px 0px #555;
        }
        h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
            letter-spacing: 1px;
            text-transform: uppercase;
        }
        h2 {
            font-size: 1.8rem;
            margin-bottom: 1rem;
            letter-spacing: 1px;
            text-transform: uppercase;
            border-bottom: 2px solid #444;
            padding-bottom: 0.5rem;
        }
        p, ul {
            font-size: 1.1rem;
            line-height: 1.8;
        }
        ul {
            padding-left: 1.5rem;
        }
        a {
            color: #f4d03f;
            text-decoration: none;
            transition: color 0.3s;
        }
        a:hover {
            color: #fff;
        }
    </style>
</head>
<body>
    <header>
        <h1>Tereza Blažková</h1>
        <p>PhD Student at the University of Copenhagen</p>
    </header>
    <nav>
        <a href="#cv">CV</a>
        <a href="#publications">Publications</a>
        <a href="#blog">Blog</a>
    </nav>
    <div class="container">
        <section id="cv">
            <h2>CV</h2>
            <p>Your CV content goes here. You can add a link to download your CV as a PDF or provide details about your education and experience.</p>
            <a href="path/to/your/cv.pdf" download>Download CV (PDF)</a>
        </section>
        <section id="publications">
            <h2>Publications</h2>
            <ul>
                <li><a href="link-to-publication1">Publication Title 1</a> - Brief description or abstract.</li>
                <li><a href="link-to-publication2">Publication Title 2</a> - Brief description or abstract.</li>
                <!-- Add more publications as needed -->
            </ul>
        </section>
        <section id="blog">
            <h2>Blog</h2>
            <p>Your blog content goes here. You can write about your research, academic experiences, or other related topics.</p>
            <ul>
                <li><a href="link-to-blog-post1">Blog Post Title 1</a> - Brief summary of the post.</li>
                <li><a href="link-to-blog-post2">Blog Post Title 2</a> - Brief summary of the post.</li>
                <!-- Add more blog posts as needed -->
            </ul>
        </section>
    </div>
</body>
</html>
