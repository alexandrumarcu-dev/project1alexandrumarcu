<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alexandru Marcu - Entrepreneur</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: #fff;
            padding: 1em 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 1em;
        }
        section {
            margin: 20px 0;
            padding: 20px;
            background: #fff;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #333;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .contact-form {
            display: flex;
            flex-direction: column;
        }
        .contact-form label {
            margin: 10px 0 5px;
        }
        .contact-form input, .contact-form textarea {
            padding: 10px;
            font-size: 1em;
            margin-bottom: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .contact-form button {
            padding: 10px;
            font-size: 1em;
            background: #333;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background: #555;
        }
    </style>
</head>
<body>
    <header>
        <h1>Alexandru Marcu</h1>
        <p>Entrepreneur | Instagram Expert</p>
    </header>

    <div class="container">
        <section id="about-me">
            <h2>About Me</h2>
            <p>At just 15 years old, I've achieved what many adults spend years striving for. My name is Alexandru Marcu. I'm a successful entrepreneur who has cracked the code to financial freedom using Instagram. My journey began with a simple idea, and today, I'm earning $3,000+/ month consistently. This course is a distillation of all the strategies, tips, and secrets that have propelled me to success. If I can do it, so can you!</p>
        </section>

        <section id="my-journey">
            <h2>My Journey</h2>
            <p>My entrepreneurial journey started with a passion for social media and a desire to share value with others. I experimented with various strategies, learning what worked and what didn't. Through perseverance and innovation, I developed a system that consistently generates income through Instagram. Now, I'm dedicated to teaching others how to replicate my success.</p>
        </section>

        <section id="success-stories">
            <h2>Success Stories</h2>
            <p>Here are some stories from people who have taken my course and achieved incredible results:</p>
            <ul>
                <li><strong>John Doe:</strong> "Thanks to Alexandru's strategies, I went from zero followers to 10,000 in just three months and now earn $2,000 a month from my Instagram account."</li>
                <li><strong>Jane Smith:</strong> "The course was a game-changer. I learned how to create engaging content and monetize my Instagram. I'm now making an extra $1,500 a month."</li>
            </ul>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>If you have any questions or want to learn more about my course, feel free to reach out!</p>
            <form class="contact-form">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="5" required></textarea>
                <button type="submit">Send</button>
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Alexandru Marcu. All Rights Reserved.</p>
    </footer>
</body>
</html>
