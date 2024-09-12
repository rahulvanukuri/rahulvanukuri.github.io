---
permalink: /
redirect_from: 
  - /about/
  - /about.html
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohammad Shahedur Rahman</title>
    <style>
        /* General Body Style */
        body {
            font-family: 'Roboto', Arial, sans-serif;
            background-color: #f0f7fa;
            margin: 0;
            padding: 0;
        }

        /* Main layout container */
        .container {
            display: flex;
            justify-content: center;
            align-items: flex-start;
            max-width: 1200px;
            margin: 30px auto;
            padding: 0 20px;
        }

        /* Sidebar */
        .sidebar {
            width: 300px;
            background-color: #ffffff;
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
            text-align: center;
            margin-right: 20px;
        }

        .sidebar img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-bottom: 20px;
        }

        .sidebar h1 {
            font-size: 22px;
            margin: 10px 0;
        }

        .sidebar p {
            font-size: 16px;
            margin-bottom: 20px;
            color: #555;
        }

        .sidebar a {
            color: #007acc;
            text-decoration: none;
            display: block;
            font-weight: bold;
            margin-bottom: 10px;
        }

        .sidebar .social-icons {
            margin-top: 20px;
        }

        .sidebar .social-icons a {
            font-size: 24px;
            margin: 0 10px;
            color: #007acc;
        }

        .social-icons a:hover {
            color: #0056b3;
        }

        /* Main content area */
        .content {
            flex-grow: 1;
            background-color: #ffffff;
            border-radius: 10px;
            padding: 40px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
        }

        .content h2 {
            font-family: 'Poppins', sans-serif;
            font-size: 36px;
            color: #333;
            font-weight: 700;
            margin-bottom: 40px;
            position: relative;
        }

        .content h2::after {
            content: '';
            display: block;
            width: 60px;
            height: 4px;
            background-color: #007acc;
            margin-top: 10px;
        }

        .content p {
            font-size: 18px;
            line-height: 1.8;
            color: #555;
            margin-bottom: 20px;
        }

        .content a {
            color: #007acc;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        .content a:hover {
            color: #0056b3;
        }

        /* Interests and Education Section */
        .two-columns {
            display: flex;
            justify-content: space-between;
            margin-top: 40px;
        }

        .column {
            width: 48%;
        }

        .column h3 {
            font-size: 24px;
            margin-bottom: 20px;
        }

        .column ul {
            list-style: none;
            padding: 0;
        }

        .column ul li {
            margin-bottom: 10px;
            font-size: 18px;
        }

        .column ul li::before {
            content: "•";
            color: #007acc;
            font-weight: bold;
            display: inline-block;
            width: 1em;
            margin-left: -1em;
        }

        /* Footer */
        footer {
            text-align: center;
            margin-top: 50px;
            font-size: 14px;
            color: #aaa;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .container {
                flex-direction: column;
                align-items: center;
            }

            .sidebar {
                margin-bottom: 20px;
            }

            .two-columns {
                flex-direction: column;
            }

            .column {
                width: 100%;
                margin-bottom: 20px;
            }
        }
    </style>
</head>
<body>

<div class="container">
    <!-- Sidebar with image and contact details -->
    <div class="sidebar">
        <img src="https://via.placeholder.com/150" alt="Your Profile Picture">
        <h1>Mohammad Shahedur Rahman</h1>
        <p>PhD Student in Computer Science<br>at The University of Texas at Arlington</p>
        <a href="#">The University of Texas at Arlington</a>

        <div class="social-icons">
            <a href="mailto:email@example.com">✉️</a>
            <a href="#">🔗</a>
            <a href="#">🐱</a>
            <a href="#">🔍</a>
            <a href="#">💼</a>
        </div>
    </div>

    <!-- Main content area for biography and details -->
    <div class="content">
        <h2>Biography</h2>
        <p>I’m a Ph.D. student in the Computer Science department at <a href="https://www.uta.edu/">The University of Texas at Arlington</a>, where <a href="#">Dr. Mohammad Atiqul Islam</a> serves as my doctoral advisor. My research focuses on high-performance computing, cybersecurity, machine learning, and resource autoscaling in cloud computing environments.</p>
        
        <p>Before starting my Ph.D., I accrued over 12 years of professional experience in cybersecurity, including serving as the Chief Information Security Officer (CISO) at BRAC Bank PLC, where I managed several large-scale projects. I hold a Master’s degree in Information Systems Security and an MBA from the University of Dhaka.</p>
        
        <a href="#" download>Download my resumé / CV</a>

        <!-- Interests and Education Section -->
        <div class="two-columns">
            <div class="column">
                <h3>Interests</h3>
                <ul>
                    <li>Cloud Computing</li>
                    <li>Microservices</li>
                    <li>High Performance Computing (HPC)</li>
                    <li>Machine Learning for Systems</li>
                    <li>Distributed Systems</li>
                </ul>
            </div>

            <div class="column">
                <h3>Education</h3>
                <ul>
                    <li>PhD in Computer Science, 2024 (Expected)<br>The University of Texas at Arlington</li>
                    <li>MSc in Information Systems Security, 2018<br>Bangladesh University of Professionals (BUP)</li>
                    <li>BSc in Computer Science, 2011<br>Bangladesh University of Engineering & Technology (BUET)</li>
                </ul>
            </div>
        </div>
    </div>
</div>

<footer>
    © 2024 by Mohammad Shahedur Rahman. All rights reserved.
</footer>

</body>
</html>
