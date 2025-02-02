# Sahiladevi.github.io
Create and Deploy A Resume with GitHub Pages
Due Date: Friday 2/21/2025 at 11:55pm

Overview
In this assignment you will be updating an existing resume template built with HTML and CSS. Please read the directions carefully.

Instructions

Prerequisites

Before you begin, ensure you have the following installed:

Git: Version control system to clone and manage the repository.
GitHub: make sure you have an account to sync your repositories to.
Code Editor: Any code editor like Visual Studio Code

Tasks

1. Go to GitHub Pages and follow the directions to create a special repository to easily host a static site.
2. After you have finished those steps, open the project in VS Code and replace the contents of `index.html` with the code below.
3. Update placeholder text for the resume with your own information.
4. Stage your changes.
5. Make your commit and push to GitHub

index.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>Resume Template</title>
    </head>

    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        h1,
        h2 {
            color: #007bff;
        }
        .header {
            text-align: center;
        }
        .header h1 {
            margin: 10px 0;
        }
        .contact {
            margin: 10px 0;
            font-size: 14px;
        }
        .contact a {
            color: #007bff;
            text-decoration: none;
        }
        .section {
            margin: 20px 0;
        }
        .section h2 {
            margin-bottom: 10px;
            border-bottom: 2px solid #007bff;
            padding-bottom: 5px;
        }
        .item {
            margin-bottom: 15px;
        }
        .item h3 {
            margin: 0;
            font-size: 18px;
            color: #555;
        }
        .item p {
            margin: 5px 0;
            font-size: 14px;
        }
        .skills ul {
            list-style: none;
            padding: 0;
        }
        .skills ul li {
            display: inline-block;
            background: #007bff;
            color: #fff;
            padding: 5px 10px;
            margin: 5px 5px 5px 0;
            border-radius: 4px;
        }
    </style>

    <body>
        <main class="container">
            <section class="header">
                <h1>Your Name</h1>
                <p class="contact">
                    Email:
                    <a href="mailto:yourname@example.com"
                        >yourname@example.com</a
                    >
                    | Phone: (123) 456-7890 | LinkedIn:
                    <a href="#">linkedin.com/in/yourname</a>
                </p>
            </section>
            <section class="section">
                <h2>Summary</h2>
                <p>
                    A brief summary about yourself, your skills, and what you
                    bring to the table. Keep it concise and impactful.
                </p>
            </section>
            <section class="section">
                <h2>Work Experience</h2>
                <div class="item">
                    <h3>Job Title - Company Name</h3>
                    <p>Dates of Employment</p>
                    <p>
                        Brief description of your responsibilities and
                        achievements in this role.
                    </p>
                </div>
                <div class="item">
                    <h3>Job Title - Company Name</h3>
                    <p>Dates of Employment</p>
                    <p>
                        Brief description of your responsibilities and
                        achievements in this role.
                    </p>
                </div>
            </section>
            <div class="section">
                <h2>Education</h2>
                <div class="item">
                    <h3>Degree - School Name</h3>
                    <p>Year of Graduation</p>
                </div>
                <div class="item">
                    <h3>Degree - School Name</h3>
                    <p>Year of Graduation</p>
                </div>
            </section>
            <section class="section">
                <h2>Skills</h2>
                <div class="skills">
                    <ul>
                        <li>HTML</li>
                        <li>CSS</li>
                        <li>JavaScript</li>
                        <li>Python</li>
                        <li>Team Leadership</li>
                    </ul>
                </div>
            </section>
            <section class="section">
                <h2>Projects</h2>
                <div class="item">
                    <h3>Project Name</h3>
                    <p>
                        Brief description of the project, the technologies used,
                        and your role in the project.
                    </p>
                </div>
                <div class="item">
                    <h3>Project Name</h3>
                    <p>
                        Brief description of the project, the technologies used,
                        and your role in the project.
                    </p>
                </div>
            </section>
        </main>
    </body>
</html>

Submitting Your Work

After completing the assignment, make sure to commit your changes and push them back to your own repository and turn in the GitHub link in Open Class
