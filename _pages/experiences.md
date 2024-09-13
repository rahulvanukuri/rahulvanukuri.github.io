---
layout: archive
title: "Experiences"
permalink: /experiences/
author_profile: true
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Experiences</title>
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
        }

        .experience-header img {
            width: 50px;
            height: 50px;
            margin-right: 20px;
        }

        .experience-header h5 {
            font-size: 18px; /* Matching font size to your specified font */
            margin: 0;
            font-weight: bold; /* Making it bold */
            color: #333;
        }

        .experience-header small {
            display: block;
            font-size: 14px;
            color: #666;
        }

        .experience-content {
            margin-top: 15px;
        }

        /* Styled bullet points with smaller size */
        .experience-content ul {
            margin: 0;
            padding-left: 20px;
        }

        .experience-content ul li {
            margin-bottom: 10px;
            font-size: 15px; /* 1 size smaller */
            color: #333;
            list-style-type: none;
            position: relative;
            padding-left: 20px;
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
    <!-- Experiences Section -->
    <div class="separator">Experiences</div>

    <!-- Experience Card 1 -->
    <div class="experience-card">
        <div class="experience-header">
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/6d/LLNL-Logo-Black-Text.png" alt="Lawrence Livermore National Lab Logo">
            <div>
                <h5>Computing Scholar Graduate Intern</h5>
                <small>Lawrence Livermore National Laboratory</small>
                <small>May 2023 – Aug 2023 · Livermore, California</small>
            </div>
        </div>
        <div class="experience-content">
            <ul>
                <li>Develop Autoscaling mechanism for ML and HPC Workflows and Cloud Environments (AWS, GCP).</li>
                <li>Enable Autoscaling into HPC frameworks such as Flux Framework with Cloud.</li>
                <li>Enable HPC and Cloud Computing convergence (Deploying lightweight Kubernetes instances with Flux in nested mode).</li>
                <li>Develop tools to automate the deployment and elasticity of HPC Apps and the cloud.</li>
                <li>Tools and Technologies: Python, AWS API, BOTO3, Terraform, Bash.</li>
            </ul>
        </div>
    </div>

    <!-- Experience Card 2 -->
    <div class="experience-card">
        <div class="experience-header">
            <img src="https://upload.wikimedia.org/wikipedia/commons/d/da/UTA_logomark.png" alt="UTA Logo">
            <div>
                <h5>Graduate Student Researcher</h5> <!-- Bold and resized title -->
                <small>The University of Texas at Arlington</small>
                <small>Sep 2019 – Present · Texas</small>
            </div>
        </div>
        <div class="experience-content">
            <ul>
                <li>Optimize resource usage of microservice applications in cloud computing.</li>
                <li>Develop Resource Manager on top of Kubernetes for microservices.</li>
                <li>Identify root cause of the resource bottlenecks of microservices.</li>
                <li>Develop Reinforcement Learning Agents to improve task completion time in mobile computation offloading.</li>
            </ul>
        </div>
    </div>
</div>

<footer>
    © 2024 by Mohammad Shahedur Rahman. All rights reserved.
</footer>

</body>
</html>
