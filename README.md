
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Colin Haskins' Resume</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #77aaff 3px solid;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            position: relative;
            text-align: center;
            margin-bottom: 20px;
        }
        .menu-icon {
            display: none;
            font-size: 30px;
            cursor: pointer;
        }
        .menu {
            list-style: none;
            display: flex;
            justify-content: center;
            padding: 0;
        }
        .menu li {
            margin: 0 10px;
        }
        .menu a {
            text-decoration: none;
            color: #fff;
            font-size: 1.2em;
        }
        #menu-toggle {
            display: none;
        }
        .main-section {
            padding: 20px;
            background: #fff;
            margin-bottom: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .section-title {
            color: #333;
            border-bottom: #77aaff 2px solid;
            padding-bottom: 5px;
            font-size: 1.5em;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        ul li {
            padding: 5px 0;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        a {
            color: #77aaff;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .contact-info p {
            margin: 5px 0;
        }
        .contact-info a {
            color: #333;
        }
        .contact-info a:hover {
            color: #77aaff;
        }
        form {
            display: flex;
            flex-direction: column;
        }
        label {
            margin-top: 10px;
        }
        input, textarea, button {
            margin-top: 5px;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background-color: #77aaff;
            color: #fff;
            border: none;
            cursor: pointer;
            margin-top: 20px;
        }
        button:hover {
            background-color: #005f99;
        }
        @media (max-width: 600px) {
            .menu {
                display: none;
                flex-direction: column;
                width: 100%;
            }
            .menu-icon {
                display: block;
            }
            #menu-toggle:checked + .menu {
                display: flex;
            }
        }
        button#submit-btn {
            display: block; /* Ensure the button is displayed as a block element */
        }
        #contact-form {
    margin-bottom: 100px; /* Adjust the value as needed to create enough space under the button */
}
    </style>
</head>
<body>

<header>
    <h1>Colin Haskins</h1>
    <nav>
        <input type="checkbox" id="menu-toggle">
        <label for="menu-toggle" class="menu-icon">&#9776;</label>
        <ul class="menu">
            <li><a href="#contact">Contact</a></li>
            <li><a href="#objective">Objective</a></li>
            <li><a href="#profile">Profile</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#proficiencies">Proficiencies</a></li>
            <li><a href="#employment">Employment</a></li>
            <li><a href="#service">Service</a></li>
            <li><a href="#education">Education</a></li>
        </ul>
    </nav>
</header>

<div class="container">
    <section class="main-section" id="contact">
        <h2 class="section-title">Contact Information</h2>
        <div class="contact-info">
            <p>Phone: <a href="tel:+14782337845">(478) 233 7845</a></p>
            <p>Email: <a href="mailto:colinhaskins2022@gmail.com">colinhaskins000@gmail.com</a></p>
            <p>LinkedIn: <a href="https://www.linkedin.com/in/colin-haskins-a52005238/" target="_blank">Colin Haskins</a></p>
            <p>GitHub: <a href="https://github.com/colin-haskins" target="_blank">github.com/colin-haskins</a></p>
        </div>
    </section>

    <section class="main-section" id="objective">
        <h2 class="section-title">Objective</h2>
        <p>Success-driven and enthusiastic Computer Science student seeking an internship/co-op.</p>
    </section>

    <section class="main-section" id="profile">
        <h2 class="section-title">Profile</h2>
        <p>Currently enrolled in BS of Computer Science – Expected graduation: May 2025</p>
        <ul>
            <li>Member of the KSU Electric Vehicle Team – Autonomous Vehicles</li>
            <li>Won 1st place in the 2021 EVGrandPrix</li>
            <li>Assisted in operations vital to running the kart in competition</li>
            <li>Member of the KSU Solar Vehicle Team</li>
            <li>Competition car driver and operator</li>
            <li>Member of software team</li>
            <li>Assisted in the development of a dash GUI interface using Python</li>
        </ul>
    </section>

    <section class="main-section" id="skills">
        <h2 class="section-title">Skills Summary</h2>
        <ul>
            <li><img src="https://img.icons8.com/color/24/000000/java-coffee-cup-logo.png" alt="Java Icon"> Java</li>
            <li><img src="https://img.icons8.com/color/24/000000/python.png" alt="Python Icon"> Python</li>
            <li><img src="https://img.icons8.com/ios-filled/24/000000/sql.png" alt="SQL Icon"> SQL</li>
            <li>Technical Writing</li>
            <li>Large Language Models</li>
            <li>Electric Vehicle Development</li>
            <li>Problem Solving</li>
        </ul>
    </section>

    <section class="main-section" id="proficiencies">
        <h2 class="section-title">Technical Proficiencies</h2>
        <ul>
            <li>Platforms: Linux, Windows 10</li>
            <li>Tools: Java, C#, Python, SQL, Microsoft Office Suite (Word, Excel, PowerPoint, Outlook)</li>
        </ul>
    </section>

    <section class="main-section" id="employment">
        <h2 class="section-title">Employment History</h2>
        <h3>Chick-Fil-A - Milledgeville, GA</h3>
        <p>Back of House Employee | Aug 2020 – Nov 2020</p>
        <ul>
            <li>Responsible for keeping up with high paced orders for long periods of time</li>
            <li>Worked closely with people of different backgrounds under high stress situations</li>
            <li>Trained new employees</li>
            <li>Learned to work well with small and large teams</li>
        </ul>

        <h3>LOWES - Marietta, GA</h3>
        <p>Shipping and Receiving Employee | Summer 2023</p>
        <ul>
            <li>Gained certifications and skills using heavy machinery</li>
            <li>Stocked and organized large quantities of merchandise</li>
            <li>Became comfortable with extensive 12-hour night shifts</li>
        </ul>
    </section>

    <section class="main-section" id="service">
        <h2 class="section-title">Community Service</h2>
        <ul>
            <li>Food drives: Three Years - Milledgeville, GA</li>
            <li>Book drives: One Year - Milledgeville, GA</li>
            <li>Free lawn care services for local community - Milledgeville, GA</li>
        </ul>
    </section>

    <section class="main-section" id="education">
        <h2 class="section-title">Education</h2>
        <h3>Kennesaw State University - Kennesaw, GA</h3>
        <p>Bachelor of Science in Computer Science | Expected Graduation: May 2025</p>
    </section>

    <section class="main-section" id="contact-form">
        <h2 class="section-title">Contact Me</h2>
        <section class="main-section" id="contact-form">
            <h2 class="section-title">Contact Me</h2>
            <form action="https://formspree.io/f/mzbnqzav" method="POST">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="5" required></textarea>
                
                <button type="submit">Send</button>
            </form>
        </section>
    </section>
</div>

<footer>
    <p>&copy; 2024 Colin Haskins</p>
</footer>

</body>
</html>
