<!DOCTYPE html>
<html lang="en">
<head>
    <?php
        if (!empty($_POST)) {
            require 'connection.php';
            $name = $_POST['name'];
            $email = $_POST['email'];
            $message = $_POST['message'];
            $sql = "INSERT INTO contact (name, email, message) VALUES ('$name', '$email', '$message')";
            $query = mysqli_query($db, $sql);
            
    }
    ?>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>My Portfolio</title>
    <style>
        /* Reset and base */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        body {
            background: linear-gradient(135deg, #1e3c72, #2a5298);
            color: #f0f0f0;
            line-height: 1.6;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
        }
        header {
            text-align: center;
            margin-bottom: 40px;
        }
        header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
            letter-spacing: 3px;
            color: #ffdd57;
            text-shadow: 0 0 8px #ffdd57;
        }
        header p {
            font-size: 1.2rem;
            color: #dcdcdc;
        }
        nav {
            margin-bottom: 40px;
        }
        nav a {
            color: #ffdd57;
            text-decoration: none;
            margin: 0 15px;
            font-weight: 700;
            font-size: 1.1rem;
            transition: color 0.3s ease;
        }
        nav a:hover {
            color: #fff;
            text-shadow: 0 0 8px #ffdd57;
        }
        section {
            width: 100%;
            max-width: 900px;
            background: rgba(255,255,255,0.05);
            border-radius: 12px;
            padding: 25px 30px;
            margin-bottom: 40px;
            box-shadow: 0 8px 25px rgba(0,0,0,0.4);
        }
        section h2 {
            color: #ffdd57;
            margin-bottom: 20px;
            font-size: 2rem;
            border-bottom: 2px solid #ffdd57;
            padding-bottom: 8px;
            letter-spacing: 1.5px;
        }
        #about p {
            font-size: 1.15rem;
            color: #ddd;
        }
        #projects .project {
            background: rgba(255,255,255,0.1);
            padding: 15px 20px;
            margin-bottom: 20px;
            border-radius: 10px;
            box-shadow: inset 0 0 10px #ffdd57;
            transition: transform 0.3s ease;
        }
        #projects .project:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px #ffdd57;
        }
        #projects .project h3 {
            margin-bottom: 8px;
            color: #ffe386;
        }
        #projects .project p {
            color: #eee;
        }
        #skills ul {
            list-style: none;
            display: flex;
            flex-wrap: wrap;
            gap: 12px;
            color: #eee;
        }
        #skills li {
            background: #ffdd57;
            color: #222;
            padding: 8px 15px;
            border-radius: 25px;
            font-weight: 600;
            box-shadow: 0 2px 10px rgba(0,0,0,0.15);
            transition: background-color 0.3s ease;
            cursor: default;
        }
        #skills li:hover {
            background-color: #ffd633;
        }
        form {
            display: flex;
            flex-direction: column;
            gap: 18px;
        }
        input[type="text"], input[type="email"], textarea {
            padding: 12px 15px;
            border-radius: 8px;
            border: none;
            outline: none;
            font-size: 1rem;
            transition: background-color 0.3s ease, box-shadow 0.3s ease;
            background: rgba(255,255,255,0.15);
            color: #fff;
            resize: vertical;
            box-shadow: inset 0 0 8px rgba(255, 221, 87, 0.7);
        }
        input[type="text"]:focus, input[type="email"]:focus, textarea:focus {
            background-color: #fff;
            color: #000;
            box-shadow: 0 0 10px #ffdd57;
        }
        button {
            background: #ffdd57;
            border: none;
            color: #222;
            font-weight: 700;
            font-size: 1.1rem;
            padding: 12px;
            border-radius: 12px;
            cursor: pointer;
            box-shadow: 0 8px 20px #ffdd57;
            transition: background-color 0.3s ease, box-shadow 0.3s ease;
        }
        button:hover {
            background-color: #f6c900;
            box-shadow: 0 8px 30px #f6c900;
        }
        footer {
            margin-top: auto;
            color: #aaa;
            font-size: 0.9rem;
            text-align: center;
            padding: 15px;
        }
        /* Responsive */
        @media (max-width: 600px) {
            header h1 {
                font-size: 2.4rem;
            }
            nav a {
                margin: 0 8px;
                font-size: 1rem;
            }
        }
        /* Smooth scroll behavior for nav */
        html {
            scroll-behavior: smooth;
        }
        /* Success and error message styling */
        .message {
            padding: 15px;
            margin-top: 12px;
            border-radius: 10px;
            font-weight: 600;
            text-align: center;
        }
        .success {
            background-color: #4bb543;
            color: white;
            box-shadow: 0 0 15px #4bb543;
        }
        .error {
            background-color: #e04b4b;
            color: white;
            box-shadow: 0 0 15px #e04b4b;
        }
    </style>
</head>
<body>
<?php
// Initialize variables for form
$nameErr = $emailErr = $messageErr = "";
$successMsg = "";
if ($_SERVER["REQUEST_METHOD"] == "POST") {
    // Simple form sanitizing and validation
    $valid = true;
    if (empty($_POST["name"])) {
        $nameErr = "Name is required";
        $valid = false;
    } else {
        $name = htmlspecialchars(strip_tags($_POST["name"]));
    }
    if (empty($_POST["email"])) {
        $emailErr = "Email is required";
        $valid = false;
    } else if (!filter_var($_POST["email"], FILTER_VALIDATE_EMAIL)) {
        $emailErr = "Invalid email format";
        $valid = false;
    } else {
        $email = htmlspecialchars(strip_tags($_POST["email"]));
    }
    if (empty($_POST["message"])) {
        $messageErr = "Message cannot be empty";
        $valid = false;
    } else {
        $message = htmlspecialchars(strip_tags($_POST["message"]));
    }
    if ($valid) {
        // For real usage, email sending or storing to DB would happen here.
        // For demo, just show success message.
        $successMsg = "Thank you, $name! Your message has been received.";
        // Clear fields to avoid resubmission confusion
        $name = $email = $message = "";
    }
}
?>
<header>
    <h1>Fahmi Daffa Afrizal</h1>
    <p>Front End Developer & Web Enthusiast</p>
</header>
<nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#skills">Skills</a>
    <a href="#contact">Contact</a>
</nav>
<main>
    <section id="about">
        <h2>About Me</h2>
        <p>
            I am a student from SMK Negeri 1 Surabaya majoring in software engineering. My last education was from elementary school, middle school, and now in vocational high school.
        </p>
    </section>
    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Portfolio Website</h3>
            <p>My personal portfolio to showcase my skills and projects. Built with HTML, CSS, JavaScript, and PHP backend for contact form.</p>
        </div>
        <div class="project">
            <h3>Task Manager App</h3>
            <p>A web-based task management system featuring CRUD operations, user authentication, and data persistence using localStorage.</p>
        </div>
    </section>
    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML5</li> <li>CSS3</li> <li>JavaScript</li> <li>PHP</li> <li>MySQL</li>
        </ul>
    </section>
    <section id="contact">
        <h2>Contact Me</h2>
        <?php if ($successMsg): ?>
            <div class="message success"><?php echo $successMsg; ?></div>
        <?php endif; ?>
        <form method="post" action="" novalidate>
            <label for="name">Name</label>
            <input type="text" id="name" name="name" aria-describedby="name-error" />
            <?php if ($nameErr): ?><div class="message error" id="name-error"><?php echo $nameErr; ?></div><?php endif; ?>

            <label for="email">Email</label>
            <input type="email" id="email" name="email"  aria-describedby="email-error" />
            <?php if ($emailErr): ?><div class="message error" id="email-error"><?php echo $emailErr; ?></div><?php endif; ?>

            <label for="message">Message</label>
            <textarea id="message" name="message" rows="5" aria-describedby="message-error">

            </textarea>
            <?php if ($messageErr): ?><div class="message error" id="message-error"><?php echo $messageErr; ?></div><?php endif; ?>

            <button type="submit">Send Message</button>
        </form>
    </section>
</main>
<footer>
    &copy; <?php echo date("Y"); ?> Fahmi Daffa Afrizal. All rights reserved.
</footer>
<script>
    // Smooth highlight nav links on scroll
    const sections = document.querySelectorAll('section');
    const navLinks = document.querySelectorAll('nav a');
    window.addEventListener('scroll', () => {
        let current = '';
        sections.forEach(section => {
            const sectionTop = section.offsetTop - 80;
            if (pageYOffset >= sectionTop) {
                current = section.getAttribute('id');
            }
        });
        navLinks.forEach(link => {
            link.classList.remove('active');
            if (link.getAttribute('href') === '#' + current) {
                link.classList.add('active');
            }
        });
    });

    // Add active class style
    const style = document.createElement('style');
    style.textContent = `
        nav a.active {
            color: white !important;
            text-shadow: 0 0 12px #ffdd57;
            font-weight: 900;
        }
    `;
    document.head.appendChild(style);
</script>
</body>
</html> 

