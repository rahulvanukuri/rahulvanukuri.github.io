---
layout: archive
title: ""
permalink: /experiences/
author_profile: true
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Professional Experiences</title>
    <style>
        /* General Body Style */
        body {
            font-family: 'Georgia', serif;
            background-color: #f0f7fa;
            margin: 0;
            padding: 0;
            color: #333;
        }

        /* Header styles */
        h1, h2, h3, h4, h5, h6 {
            margin: 0 0 0.5em;
            line-height: 1.2;
            font-family: 'Georgia', serif;
            font-weight: bold;
        }

        /* Main content container */
        .content {
            width: 100%; 
            max-width: 1200px;
            margin: 30px auto;
            padding: 30px;
            background-color: #ffffff;
            border-radius: 15px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }

        .content h2 {
            font-size: 28px;
            color: #1e3d8f;
            font-weight: bold;
            margin-bottom: 15px;
            position: relative;
        }

        .content h2::after {
            content: '';
            display: block;
            width: 50%;
            height: 1px;
            background-color: #cccccc;
            margin-top: 8px;
            margin-left: 0;
        }

        .content p {
            font-size: 17px;
            line-height: 1.8;
            color: #333;
            margin-bottom: 20px;
            text-align: justify;
        }

        /* Experience card container with timeline */
        .experience-container {
            display: grid;
            grid-template-columns: 1fr;
            gap: 25px;
            position: relative;
            padding-left: 40px;
        }

        .experience-container::before {
            content: '';
            position: absolute;
            top: 0;
            left: 18px;
            width: 4px;
            height: 100%;
            background-color: #1e3d8f;
        }

        /* Experience card styling */
        .experience-card {
            background-color: #ffffff;
            border-radius: 10px;
            padding: 25px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            border-left: 6px solid #1e3d8f;
            position: relative;
        }

        .experience-card::before {
            content: '';
            position: absolute;
            top: 25px;
            left: -27px;
            width: 16px;
            height: 16px;
            background-color: #ffffff;
            border: 4px solid #1e3d8f;
            border-radius: 50%;
        }

        .experience-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.1);
        }

        .experience-card h3 {
            font-size: 22px;
            font-weight: bold;
            color: #1e3d8f;
            margin-bottom: 10px;
        }

        .experience-card h4 {
            font-size: 18px;
            font-weight: normal;
            margin-bottom: 15px;
            color: #666;
        }

        .experience-card h5 {
            font-size: 16px;
            color: #999;
            margin-bottom: 15px;
        }

        .experience-card img {
            width: 50px;
            height: 50px;
            object-fit: contain;
            float: right;
            margin-left: 15px;
        }

        .section-header {
            font-size: 17px;
            font-weight: bold;
            color: #1e3d8f;
            margin-bottom: 10px;
            border-bottom: 2px solid #cccccc;
            padding-bottom: 5px;
        }

        .section-content {
            font-size: 16px;
            line-height: 1.8;
            color: #333;
            margin-bottom: 15px;
        }

        /* Footer styles */
        footer {
            text-align: center;
            margin-top: 40px;
            font-size: 14px;
            color: #333;
            font-family: 'Georgia', serif;
            background-color: #f0f7fa;
            padding: 20px 0;
            border-top: 1px solid #cccccc;
        }

        footer .separator {
            font-size: 20px;
            font-weight: bold;
            color: #1e3d8f;
            margin-bottom: 15px;
        }

        footer .separator::after {
            content: '';
            display: block;
            width: 50px;
            height: 2px;
            background-color: #1e3d8f;
            margin: 10px auto;
        }

        footer .links {
            margin-bottom: 15px;
        }

        footer .links a {
            margin: 0 15px;
            color: #1e3d8f;
            text-decoration: none;
            font-size: 16px;
            font-weight: bold;
        }

        footer .links a:hover {
            text-decoration: underline;
        }

        footer .footer-note {
            color: #777;
            font-size: 14px;
        }

    </style>
</head>
<body>

<!-- Professional Experiences Section -->
<div class="content">
    <div class="separator">Professional Experiences</div>

    <!-- Timeline with cards -->
    <div class="experience-container">

        <!-- Role 1: Graduate Student Researcher -->
        <div class="experience-card">
            <h3>Graduate Student Researcher</h3>
            <h4>The University of Texas at Arlington (UTA) · Aug 2023 – Present</h4>
            <h5>Texas, USA</h5>
            <img src="https://upload.wikimedia.org/wikipedia/commons/d/da/UTA_logomark.png" alt="UTA Logo">
            <div class="section-header">Responsibilities</div>
            <p class="section-content">
                <li>Optimize resource usage of microservice applications in cloud computing.</li>
                <li>Develop Resource Manager on top of Kubernetes for microservices.</li>
                <li>Develop Reinforcement Learning Agents to improve task completion time.</li>
                <li>Identify root cause of microservice resource bottlenecks.</li>
            </p>
        </div>

        <!-- Role 2: Chief Information Security Officer (CISO) -->
        <div class="experience-card">
            <h3>Chief Information Security Officer (CISO)</h3>
            <h4>BRAC Bank PLC · Nov 2022 – Aug 2023</h4>
            <h5>Dhaka, Bangladesh</h5>
            <img src="https://play-lh.googleusercontent.com/alpY0C3iFPpBBULGdBBnR0i3mdMEk3M8GR35o7sWcg_OzVakagI11yxqokIGOYrbmcA" alt="BRAC Bank Logo">
            <div class="section-header">Responsibilities</div>
            <p class="section-content">
                <li>Led security initiatives, aligning goals with business objectives.</li>
                <li>Architected robust cybersecurity solutions to protect data.</li>
                <li>Directed Security Operation Center (SOC), ensuring 24x7 threat detection.</li>
                <li>Monitored and reported evolving security trends.</li>
            </p>
        </div>

        <!-- Role 3: Senior Security Analyst -->
        <div class="experience-card">
            <h3>Senior Security Analyst</h3>
            <h4>XYZ Company · Jan 2020 – Oct 2022 · New York, USA</h4>
            <img src="/path_to_image2.png" alt="XYZ Company Logo">
            <div class="section-header">Responsibilities</div>
            <p class="section-content">
                <li>Analyzed security incidents and conducted vulnerability assessments.</li>
                <li>Implemented automated security monitoring systems.</li>
                <li>Developed company-wide cybersecurity awareness training programs.</li>
            </p>
        </div>

        <!-- Role 4: Security Operations Manager -->
        <div class="experience-card">
            <h3>Security Operations Manager</h3>
            <h4>ABC Security Ltd. · Aug 2017 – Dec 2019 · London, UK</h4>
            <img src="/path_to_image3.png" alt="ABC Security Logo">
            <div class="section-header">Responsibilities</div>
            <p class="section-content">
                <li>Managed the security operations center and incident management protocols.</li>
                <li>Led improvements in operational efficiency through new security tools.</li>
            </p>
        </div>

        <!-- Add more roles as needed -->

    </div>
</div>

<footer>
    <div class="separator">Stay Connected</div>
    <div class="links">
        <a href="#">LinkedIn</a>
        <a href="#">GitHub</a>
        <a href="#">Twitter</a>
    </div>
    <div class="footer-note">
        &copy; 2024 Your Name. All rights reserved.
    </div>
</footer>

</body>
</html>
