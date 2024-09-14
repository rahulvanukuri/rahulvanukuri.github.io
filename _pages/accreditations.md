---
layout: archive
title: ""
permalink: /accreditations/
author_profile: true
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Accreditations</title>
    <style>
        /* General Body Style */
        body {
            font-family: 'Georgia', serif;
            background-color: #f0f7fa;
            margin: 0;
            padding: 0;
            color: #333;
        }

        /* Main content container */
        .content {
            width: 128%;
            margin: 0 auto;
            padding: 20px;
            max-width: 1000px;
        }

        /* Style for Separator */
        .separator {
            text-align: center;
            font-size: 22px;
            font-weight: bold;
            color: #1e3d8f;
            margin-top: 0px;
            margin-bottom: 20px;
            position: relative;
        }

        .separator::after {
            content: '';
            display: block;
            width: 60%;
            height: 1px;
            background-color: #cccccc;
            margin: 10px auto;
        }

        /* Experience Card Styling */
        .experience-card {
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            padding: 20px;
            margin-bottom: 20px;
            transition: box-shadow 0.3s ease;
        }

        .experience-card:hover {
            box-shadow: 0 6px 16px rgba(0, 0, 0, 0.1);
        }

        /* Using Icon as a Bullet */
        .experience-header {
            display: flex;
            align-items: center;
            margin-bottom: 10px;
        }

        .experience-header img {
            width: 35px;
            height: 35px;
            margin-right: 15px;
        }

        .experience-header h6 {
            font-size: 17px;
            font-weight: normal;
            margin: 0;
            color: #333;
            font-family: 'Georgia', serif;
        }

        /* Styled content with icon as bullet */
        .experience-content ul {
            list-style: none;
            padding-left: 0;
        }

        .experience-content ul li {
            display: flex;
            align-items: center;
            margin-bottom: 10px;
            font-size: 15px;
            color: #333;
            font-family: 'Georgia', serif;
        }

        .experience-content ul li img {
            width: 35px;
            height: 35px;
            margin-right: 10px;
        }

        .experience-content ul li p {
            margin: 0;
            font-size: 15px;
            color: #333;
        }

        /* Footer */
        footer {
            text-align: center;
            margin-top: 50px;
            font-size: 14px;
            color: #aaa;
            font-family: 'Georgia', serif;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .experience-header img {
                width: 30px;
                height: 30px;
            }

            .experience-header h6 {
                font-size: 16px;
            }

            .experience-content ul li img {
                width: 30px;
                height: 30px;
            }

            .experience-content ul li p {
                font-size: 14px;
            }
        }
    </style>
</head>
<body>

<div class="content">
    <!-- Accreditations Section -->
    <div class="separator">Accreditations</div>

    <!-- Experience Card 1 -->
    <div class="experience-card">
        <div class="experience-header">
            <img src="https://wiki.agileana.com/images/6/68/PMP_project_management_professional_certification_badge.png" alt="PMP Icon">
            <h6>Project Management Professional (PMP)</h6>
        </div>
        <div class="experience-content">
            <ul>
                <li>
                    <img src="https://wiki.agileana.com/images/6/68/PMP_project_management_professional_certification_badge.png" alt="PMP Icon">
                    <p>Develop Resource Manager on top of Kubernetes for microservices.</p>
                </li>
                <li>
                    <img src="https://wiki.agileana.com/images/6/68/PMP_project_management_professional_certification_badge.png" alt="PMP Icon">
                    <p>Identify root cause of the resource bottlenecks of microservices.</p>
                </li>
                <li>
                    <img src="https://wiki.agileana.com/images/6/68/PMP_project_management_professional_certification_badge.png" alt="PMP Icon">
                    <p>Develop Reinforcement Learning Agents to improve task completion time in mobile computation offloading.</p>
                </li>
            </ul>
        </div>
    </div>

    <!-- More cards would go here -->

</div>

<footer>
    © 2024 by Mohammad Shahedur Rahman. All rights reserved.
</footer>

</body>
</html>
