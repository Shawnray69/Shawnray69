<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CoolBlog</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1em 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: #fff;
            padding: 14px 20px;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            background-color: #555;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 20px;
        }
        .blog-post {
            background: #fff;
            margin-bottom: 20px;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .blog-post h2 {
            color: #333;
        }
        .blog-post p {
            color: #666;
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
    <h1>Welcome to CoolBlog</h1>
    <p>Your go-to place for interesting blog posts</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#blog">Blog</a>
    <a href="#contact">Contact</a>
</nav>

<div class="container">
    <section id="home">
        <h2>Home</h2>
        <p>Welcome to CoolBlog! Here you'll find a variety of blog posts on different topics. Stay tuned for more updates!</p>
    </section>

    <section id="about">
        <h2>About</h2>
        <p>This is a place where you can share your thoughts, ideas, and experiences. Whether it's technology, travel, food, or personal stories, CoolBlog is here for you.</p>
    </section>

    <section id="blog">
        <h2>Blog</h2>
        <article class="blog-post">
            <h2>Sample Blog Post 1</h2>
            <p>Welcome to your first blog post! Start writing about your favorite topics and share them with the world.</p>
        </article>
        <article class="blog-post">
            <h2>Sample Blog Post 2</h2>
            <p>This is another example of a blog post. Customize this template to fit your needs and start blogging!</p>
        </article>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>If you have any questions or want to get in touch, feel free to reach out via social media or email.</p>
    </section>
</div>

<footer>
    <p>&copy; 2024 CoolBlog. All Rights Reserved.</p>
</footer>

</body>
</html>
