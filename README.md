<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Portfolio of Nikhil Patil - AI & Machine Learning Engineer">
    <title>Nikhil Patil - AI & ML Engineer</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
            perspective: 1000px; /* Adds perspective for 3D elements */
        }

        header h1 {
            margin: 0;
            transform: rotateX(15deg); /* Creates a 3D tilt effect */
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
            padding: 1rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
        }

        nav a {
            color: white;
            margin: 0 1rem;
            text-decoration: none;
            font-weight: bold;
            transform: perspective(500px) translateZ(15px);
            transition: transform 0.3s ease;
        }

        nav a:hover {
            transform: perspective(500px) translateZ(25px); /* Pops forward on hover */
        }

        section {
            padding: 2rem;
            margin: 2rem;
            background-color: white;
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.1);
            transform-style: preserve-3d;
            transition: transform 0.5s ease, box-shadow 0.5s ease;
        }

        section:hover {
            transform: perspective(500px) rotateY(3deg) translateZ(10px); /* 3D Rotation effect */
            box-shadow: 0 12px 25px rgba(0, 0, 0, 0.2); /* Deepens shadow on hover */
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
            transform: rotateX(10deg);
        }

        h2 {
            color: #444;
            transform: translateZ(10px);
        }

        .contact-info, .education-info {
            display: flex;
            justify-content: space-between;
            transform: translateZ(10px);
        }

        .skills, .hobbies, .languages {
            list-style-type: none;
            padding: 0;
        }

        .skills li, .hobbies li, .languages li {
            transform: perspective(400px) translateZ(5px);
            transition: transform 0.3s ease;
        }

        .skills li:hover, .hobbies li:hover, .languages li:hover {
            transform: perspective(400px) translateZ(15px); /* Pops forward on hover */
        }

        /* 3D button styling */
        nav a, button {
            padding: 10px 20px;
            background-color: #0066cc;
            border: none;
            color: white;
            border-radius: 5px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            cursor: pointer;
        }

        button {
            margin-top: 10px;
            transform: perspective(500px) translateZ(15px);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        button:hover {
            transform: perspective(500px) translateZ(25px); /* Pops forward on hover */
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.3);
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Nikhil Patil</h1>
        <p>Artificial Intelligence & Machine Learning Engineer</p>
    </header>

    <!-- Navigation Bar -->
    <nav>
        <a href="#about">About Me</a>
        <a href="#projects">Projects</a>
        <a href="#skills">Skills</a>
        <a href="#education">Education</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>I am a third-year student pursuing a Bachelor's degree in Artificial Intelligence and Machine Learning. I am passionate about applying my knowledge in Python and Java to solve real-world problems. I have worked on various projects that demonstrate my skills in AI and software development.</p>
        <div class="contact-info">
            <p><strong>Phone:</strong> 9307157591</p>
            <p><strong>Email:</strong> inquirynikpatil@gmail.com</p>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Projects</h2>
        <div>
            <h3>Parkments - Software Developer</h3>
            <p>A revolutionary application where parking seekers find parking spots in nearby apartments or houses. The owners get rewarded for renting out their parking spots.</p>
        </div>
        <div>
            <h3>TopicTube - Software Developer</h3>
            <p>This application analyzes YouTube content to help users find specific topics and organizes them from basic to advanced levels based on the user's understanding.</p>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2>Skills</h2>
        <h3>Technical Skills</h3>
        <ul class="skills">
            <li>Python (Beginner)</li>
            <li>Java (Beginner)</li>
            <li>Natural Language Processing (NLP)</li>
            <li>Machine Learning</li>
            <li>Managerial Skills</li>
        </ul>
        <h3>Soft Skills</h3>
        <ul class="skills">
            <li>Team Management</li>
            <li>Leadership</li>
            <li>Stock Market Analysis</li>
            <li>Anchoring Events</li>
        </ul>
    </section>

    <!-- Education Section -->
    <section id="education">
        <h2>Education</h2>
        <div class="education-info">
            <div>
                <p><strong>Alard College of Engineering and Management, Pune</strong></p>
                <p>Bachelor’s in Artificial Intelligence & Machine Learning (2021-2025)</p>
            </div>
            <div>
                <p><strong>M.J. College, Jalgaon</strong></p>
                <p>12th Science (PCM), 83%</p>
            </div>
            <div>
                <p><strong>L.N.S.V. High School, Jalgaon</strong></p>
                <p>10th, 79.80%</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact</h2>
        <p>Feel free to reach out to me via phone or email for any inquiries or collaboration opportunities!</p>
        <div class="contact-info">
            <p><strong>Phone:</strong> 9307157591</p>
            <p><strong>Email:</strong> inquirynikpatil@gmail.com</p>
        </div>
        <button>Send Message</button>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Nikhil Patil. All Rights Reserved.</p>
    </footer>

</body>
</html>
