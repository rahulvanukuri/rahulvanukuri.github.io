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

        .experience-header {
            display: flex;
            align-items: center;
            margin-bottom: 10px;
        }

        .experience-header img {
            width: 50px;
            height: 50px;
            margin-right: 20px;
        }

        .experience-header h5 {
            font-size: 18px;
            margin: 0;
            font-weight: bold;
            color: #333;
            font-family: 'Georgia', serif;
        }

        .experience-header p {
            font-size: 16px;
            margin: 0;
            color: #333;
        }

        /* Styled bullet points with smaller size */
        .experience-content ul {
            margin: 0;
            padding-left: 20px;
        }

        .experience-content ul li {
            margin-bottom: 10px;
            font-size: 15px;
            color: #333;
            list-style-type: none;
            position: relative;
            padding-left: 20px;
            font-family: 'Georgia', serif;
        }

        .experience-content ul li::before {
            content: '•';
            position: absolute;
            left: 0;
            color: #1e3d8f;
            font-size: 20px;
            line-height: 16px;
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
                width: 40px;
                height: 40px;
            }

            .experience-header h5 {
                font-size: 16px;
            }

            .experience-content ul li {
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
            <span>&#8226;</span>
            <h5 style="margin-left: 10px;">Project Management</h5>
        </div>
        <div class="experience-content">
            <div style="display: flex; align-items: center; gap: 15px;">
                <img src="https://wiki.agileana.com/images/6/68/PMP_project_management_professional_certification_badge.png" alt="PMP Icon" style="width: 80px; height: 80px;">
                <p>Project Management Professional (PMP)</p>
            </div>
            <ul>
                <li>Develop Resource Manager on top of Kubernetes for microservices.</li>
                <li>Identify root cause of the resource bottlenecks of microservices.</li>
                <li>Develop Reinforcement Learning Agents to improve task completion time in mobile computation offloading.</li>
            </ul>
        </div>
    </div>

    <!-- Experience Card 2 -->
    <div class="experience-card">
        <div class="experience-header">
            <img src="https://play-lh.googleusercontent.com/alpY0C3iFPpBBULGdBBnR0i3mdMEk3M8GR35o7sWcg_OzVakagI11yxqokIGOYrbmcA" alt="BRAC Bank Logo">
            <div>
                <h5>Chief Information Security Officer (CISO)</h5>
                <small><a href="https://www.bracbank.com/en">BRAC Bank PLC</a></small>
                <small>Nov 2022 – Aug 2023 · Dhaka, Bangladesh</small>
            </div>
        </div>
        <div class="experience-content">
            <ul>
                <li>Led the Information Security team to enhance the cybersecurity posture of the organization.</li>
                <li>Developed and implemented strategies for managing and mitigating cybersecurity risks.</li>
                <li>Oversaw the compliance of IT systems with security standards and regulations.</li>
                <li>Collaborated with international partners to ensure the security of cross-border data exchanges.</li>
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
