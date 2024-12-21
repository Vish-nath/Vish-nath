<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Vishwanath H</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        /* Basic Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f4f4f9;
            color: #333;
            line-height: 1.6;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
        }



        /* Smooth Scroll */
        html {
            scroll-behavior: smooth;
        }

        /* Navbar Styling */
        nav {
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            background-color: #2C3E50;
            padding: 15px;
            z-index: 1000;
            display: flex;
            justify-content: center;
        }

        nav a {
            color: white;
            margin: 0 20px;
            font-size: 18px;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: #18BC9C;
        }

        /* Main Section */
        .container {
            text-align: center;
            max-width: 1200px;
            margin: 50px auto;
            padding: 20px;
        }

        h1 {
            font-size: 3rem;
            margin-bottom: 20px;
            color: #2C3E50;
            animation: fadeIn 2s ease-in-out;
        }

        h2 {
            color: #18BC9C;
            margin-bottom: 30px;
        }

        .content-section {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin-top: 50px;
        }

        /* Skills Section */
        .skill-bar {
            width: 100%;
            background-color: #e1e1e1;
            border-radius: 10px;
            height: 20px;
            overflow: hidden;
        }

        .skill-bar span {
            display: block;
            height: 100%;
            background-color: #18BC9C;
            transition: width 1s ease-in-out;
        }

        /* Animations */
        @keyframes fadeIn {
            0% {
                opacity: 0;
                transform: translateY(50px);
            }

            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .bounce {
            animation: bounce 1.5s infinite;
        }

        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% {
                transform: translateY(0);
            }
            40% {
                transform: translateY(-10px);
            }
            60% {
                transform: translateY(-5px);
            }
        }

        /* Contact Form */
        .contact-form {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-top: 50px;
        }

        .contact-form input,
        .contact-form textarea {
            width: 100%;
            max-width: 400px;
            margin: 10px 0;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 16px;
        }

        .contact-form button {
            background-color: #18BC9C;
            color: white;
            border: none;
            padding: 12px 20px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            transition: background-color 0.3s ease;
        }

        .contact-form button:hover {
            background-color: #16a085;
        }

        /* Footer */
        footer {
            margin-top: 50px;
            color: #7f8c8d;
            font-size: 14px;
        }

        footer a {
            color: #18BC9C;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }

        /* Responsive Design */
        @media screen and (max-width: 768px) {
            .content-section {
                grid-template-columns: 1fr;
            }
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

    <div class="container">
        <div style="text-align: center;"><h1 class="bounce">Hello, I'm Vishwanath!</h1>
        <h2>Creative and Active Learner</h2>
        <div id="about" class="content-section">
<div style="text-align: right;"><img src="Polish_20241014_2144235990.jpg" alt="Vishwanath H" style="width: 300px; height: auto; img-align: centre; border: 5px solid #18BC9C; border-radius: 15px;" ></div></div>
  
            <div>
                <h3>About Me</h3>
                <p>I am an interested active learner passionate about becoming A Security Analyst. I am pursuing to learn JAVA, and I love creating interactive, creative, user-friendly applications, and software.</p>
            </div>
            <div>
                <h3>Experience</h3>
                <p>5+ years of experience in AIOTRIX, working with various technologies like JAVA, HTML, CSS, JavaScript, React, and Node.js.</p>
            </div>
        </div>

        <div id="skills">
            <h1>SKILLS</h1>
            <div class="skill-bar">
                <span style="width: 90%;"></span>
            </div>
  <p>JAVA</p>
	    <div class="skill-bar">
 	    	<span style="width: 80%;"></span>
		</div>
            <p>HTML/CSS</p>
            <div class="skill-bar">
                <span style="width: 70%;"></span>
            </div>
            <p>JavaScript</p>
            <div class="skill-bar">
                <span style="width: 87%;"></span>
            </div>
	  
            <p>React.js</p>
        </div>

        <div id="projects" class="content-section">
            <div>
                <h3>Projects</h3>
                <ul>
                    <li>Project 1: Portfolio Website</li>
                    <li>Project 2: AI based on System Security</li>
                    <li>Project 3: Blogging Platform</li>
                </ul>
            </div>
            <div>
                <h3>Technologies</h3>
                <ul><span style="text-align: centre;">
<li>JAVA</li>
                    <li>React.js</li>
                    <li>Node.js</li>
                    <li>MongoDB</li>
                    <li>Express</li>
                    <li>CSS3</li>
                </ul></span>
            </div>
        </div>

        <div id="contact" class="contact-form">
            <h3>Contact Me</h3>
<p><a href="mailto:vishwahesamani@gmail.com" target="_blank">SEND AN EMAIL!</a></p>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" rows="4" required></textarea>
            <button type="submit">Send Message</button>
        </div>

        <footer>
            <p>© 2024 Vishwanath H | <img src="https://static-00.iconduck.com/assets.00/linkedin-icon-512x512-vkm0drb1.png" width="25" height="25" alt="Linked icon"><a href="https://www.linkedin.com/in/vishwanath-h-300b63251?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">LinkedIn</a> |  <img src="https://t3.ftcdn.net/jpg/04/52/18/48/360_F_452184858_iZXfI1h2BdKB5i9cDwpu9Ue1il8Mxxfq.jpg" width="25" height="25" alt="Linked icon"><a href="https://github.com/Vish-nath">GitHub</a> | <img src="https://t4.ftcdn.net/jpg/08/12/25/07/360_F_812250737_7d1yi3P1mmRqWfJBX2ptzSSiUkUIe3YR.jpg" width="25" height="25" alt="Linked icon"><a href="https://www.instagram.com/vish._nath/">Instagram</a> | 

<div class="container">
        <div class="header">
          
            <div class="contact">
             <div>Email: vishwahesamani@gmail.com</div>
                <div>Phone: +91 95380 51758</div></div> 
</a></p>
        </footer>
    </div>

    <script>
        // Animating Skill Bars
        window.onload = function () {
            const skillBars = document.querySelectorAll('.skill-bar span');
            skillBars.forEach(function (bar) {
                bar.style.width = bar.style.width; // Trigger the animation
            });
        };
    </script>
</body>

</html>
