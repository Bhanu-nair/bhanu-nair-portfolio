# bhanu-nair-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            color: #333;
        }

        header {
            background-color: #343a40;
            color: #fff;
            padding: 20px 0;
            text-align: center;
            position: sticky;
            top: 0;
            width: 100%;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            z-index: 1000;
        }

        header .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1000px;
            margin: 0 auto;
            padding: 0 20px;
        }

        header .logo {
            width: 50px;
        }

        nav ul {
            list-style: none;
            display: flex;
        }

        nav ul li {
            margin: 0 10px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        nav ul li a:hover {
            text-decoration: underline;
        }

        .hero {
            background-color: #6c757d;
            color: #fff;
            padding: 60px 20px;
            text-align: center;
        }

        .hero h1 {
            margin: 0;
            font-size: 3rem;
        }

        .hero p {
            margin: 10px 0;
            font-size: 1.5rem;
        }

        .hero .btn {
            display: inline-block;
            padding: 10px 20px;
            background-color: #007bff;
            color: #fff;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 20px;
        }

        section {
            margin: 20px;
            padding: 20px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease-in-out;
        }

        section:hover {
            transform: scale(1.02);
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
        }

        h2 {
            border-bottom: 2px solid #007bff;
            padding-bottom: 10px;
        }

        .skills {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }

        .skills .skill {
            flex: 0 0 30%;
            margin: 10px;
            padding: 10px;
            background-color: #e9ecef;
            border-radius: 5px;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        form {
            display: flex;
            flex-direction: column;
        }

        label, input, textarea, button {
            margin-bottom: 10px;
        }

        button {
            background-color: #007bff;
            color: #fff;
            border: none;
            border-radius: 5px;
            padding: 10px 20px;
            cursor: pointer;
        }

        button:hover {
            background-color: #0056b3;
        }

        #toTopButton {
            position: fixed;
            bottom: 20px;
            right: 20px;
            padding: 10px 20px;
            background-color: #343a40;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        #toTopButton:hover {
            background-color: #495057;
        }

        /* Responsive Design */
        @media (max-width: 600px) {
            body {
                font-size: 14px;
            }

            header .container {
                flex-direction: column;
            }

            nav ul {
                flex-direction: column;
                margin-top: 10px;
            }

            section {
                margin: 10px;
                padding: 10px;
            }

            .skills .skill {
                flex: 0 0 100%;
            }

            #toTopButton {
                bottom: 10px;
                right: 10px;
                padding: 8px 16px;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            
            <h1>BHANU A NAIR</h1>
            <nav>
                <ul>
                    <li><a href="#about-me">About Me</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#portfolio">Projects</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <div class="hero">
        <h1>BHANU A NAIR</h1>
        <p>"Crafting Visions, Coding Dreams"</p>
        <a href="#contact" class="btn">Hire Me</a>
    </div>
    <section id="about-me">
        <div class="container">
            <h2>About Me</h2>
            <p>Hello! I'm BHANU A NAIR, an aspiring web developer with a passion for creating websites. I've been learning HTML, CSS, and JavaScript, and I'm excited to continue growing my skills.</p>
            <p>My recent project, Astrobotic Frontier, helped me understand the basics of web development. I'm eager to take on new challenges and build more projects .</p>
            <p>When I'm not coding, you can find me exploring new technologies and learning as much as I can. I'm looking forward to bringing my enthusiasm and creativity to new projects and collaborations.</p>
        </div>
    </section>
    <section id="skills">
        <div class="container">
            <h2>Skills</h2>
            <div class="skills">
                <div class="skill">
                    <h3>HTML</h3>
                </div>
                <div class="skill">
                    <h3>CSS</h3>
                </div>
                <div class="skill">
                    <h3>JavaScript</h3>
                </div>
                <!-- Add more skills as needed -->
            </div>
        </div>
    </section>
    <section id="portfolio">
        <div class="container">
            <h2>Projects</h2>
            <div class="project">
                <h3>Astrobotic Frontier</h3>
                <p>Description: A web application developed for the NASA International Space Apps Challenge, aimed at exploring space missions and providing insightful data on astrobotic activities.</p>
                <p>Technologies Used: HTML, CSS, JavaScript, React</p>
                <p>Role: Frontend Developer</p>
                <p>Features:</p>
                <ul>
                    <li>Interactive user interface to explore various space missions.</li>
                    <li>Real-time data visualization using APIs from NASA.</li>
                    <li>User-friendly design to enhance the exploration experience.</li>
                </ul>
                <p>Challenges:</p>
                <ul>
                    <li>Implementing real-time data updates.</li>
                    <li>Ensuring cross-browser compatibility and responsiveness.</li>
                    <li>Optimizing performance for a seamless user experience.</li>
                </ul>
                <p>Achievements:</p>
                <ul>
                    <li>Successfully presented at the NASA International Space Apps Challenge.</li>
                    <li>Positive feedback from judges and participants.</li>
                    <li>Enhanced understanding of space missions and data visualization techniques.</li>
                </ul>
                <a href="https://bhanu-nair.github.io/AstroBotics_Frontier/" target="_blank">View Project</a>
            </div>
        </div>
    </section>
        
    
    
    <section id="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email">
                <label for="message">Message:</label>
                <textarea id="message" name="message"></textarea>
                <button type="submit">Send</button>
            </form>
        </div>
    </section>
    <button id="toTopButton">Back to Top</button>
    <script>
        document.addEventListener("DOMContentLoaded", function() {
            const toTopButton = document.getElementById("toTopButton");
            toTopButton.style.display = "none"; // Initially hidden

            window.addEventListener("scroll", function() {
                if (window.scrollY > 300) {
                    toTopButton.style.display = "block";
                } else {
                    toTopButton.style.display = "none";
                }
            });

            toTopButton.addEventListener("click", function() {
                window.scrollTo({ top: 0, behavior: "smooth" });
            });
        });
    </script>
</body>
</html>
