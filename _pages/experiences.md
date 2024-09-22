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
            background-color: #ffffff;
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
            max-width: 1100px;
            margin: 30px auto;
            padding: 20px;
            background-color: #ffffff;
            border-radius: 15px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }

        /* Custom separator for the headline */
        .content h1::after {
            content: '';
            display: block;
            width: 60%;
            height: 2px;
            background-color: #1e3d8f;
            margin-top: 8px;
            margin-left: 0;
        }

        .content h2 {
            font-size: 24px;
            color: #1e3d8f;
            font-weight: bold;
            margin-bottom: 15px;
            text-align: center;
            position: relative;
        }

        .content h2::after {
            content: '';
            display: block;
            width: 60%;
            height: 1px;
            background-color: #cccccc;
            margin: 10px auto;
        }

        .content p, .content li {
            font-size: 15.5px; /* Ensures consistent font size for all text */
            font-family: 'Georgia', serif; /* Ensure the same font family */
            line-height: 1.6;
            color: #333;
            text-align: justify;
            margin-bottom: 13px; /* Consistent spacing */
        }

        /* Bullet point formatting */
        ul {
            list-style: disc;
            margin-left: 1px;
        }

        ul li {
            text-align: justify;
            margin-bottom: 10px;
        }

        ul li::marker {
            font-weight: bold;
        }

        /* Experience card container without timeline */
        .experience-container {
            display: grid;
            grid-template-columns: 1fr;
            gap: 20px;
            position: relative;
            padding-left: 0;
        }

        /* Experience card styling */
        .experience-card {
            background-color: #f9f9f9;
            border-radius: 12px;
            padding: 15px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            border-left: 5px solid #1e3d8f;
            position: relative;
        }

        .experience-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.1);
        }

        .experience-card h3 {
            font-size: 18px;
            font-weight: bold;
            color: #1e3d8f;
            margin-bottom: 8px;
        }

        .experience-card h4 {
            font-size: 16px;
            font-weight: normal;
            margin-bottom: 8px;
            color: #666;
        }

        .experience-card h5 {
            font-size: 14px;
            color: #999;
            margin-bottom: 6px;
        }

        .experience-card img {
            width: 45px;
            height: 45px;
            object-fit: contain;
            float: right;
            margin-left: 15px;
        }

        .section-header {
            font-size: 16px;
            font-weight: bold;
            color: #1e3d8f;
            margin-bottom: 6px;
            border-bottom: 2px solid #cccccc;
            padding-bottom: 3px;
        }

        .section-content {
            font-size: 14px;
            font-family: 'Georgia', serif; /* Ensure this is consistent */
            line-height: 1.6;
            color: #333;
            text-align: justify;
            margin-bottom: 13px; /* Moderate gap between list items */
        }

        /* Links styling */
        a {
            color: #1e3d8f;
            text-decoration: none;
        }

        a:link, a:visited {
            color: #1e3d8f;
            text-decoration: none;
        }

        a:hover, a:active {
            color: #003399;
            text-decoration: none;
        }

        /* Footer styles */
        footer {
            text-align: center;
            margin-top: 40px;
            font-size: 14px;
            color: #333;
            font-family: 'Georgia', serif;
            background-color: #ffffff;
            padding: 20px 0;
            border-top: 1px solid #cccccc;
        }

        footer .separator {
            font-size: 18px;
            font-weight: bold;
            color: #1e3d8f;
            margin-bottom: 15px;
        }

        footer .separator::after {
            content: '';
            display: block;
            width: 40px;
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
    <h2>Building a Strong Foundation with 12+ Years of Professional Expertise</h2>
    <div class="separator"></div>

    <!-- Experience cards -->
    <div class="experience-container">

        <!-- Role 1: Graduate Student Researcher -->
        <div class="experience-card">
            <h3>Graduate Student Researcher</h3>
            <h4><a href="https://www.uta.edu/academics/schools-colleges/engineering/academics/departments/cse/">The University of Texas at Arlington (UTA)</a> · Aug 2023 – Present</h4>
            <h5>Texas, USA</h5>
            <img src="https://upload.wikimedia.org/wikipedia/commons/d/da/UTA_logomark.png" alt="UTA Logo">
            <div class="section-header">Responsibilities</div>
            <ul class="section-content">
                <li>Optimized resource allocation and scaling strategies for microservice-based cloud applications, enhancing computational efficiency and overall system performance.</li>
                <li>Designed and implemented a Kubernetes-based Resource Manager to orchestrate microservices, dynamically improving deployment scalability and operational resilience.</li>
                <li>Identified and mitigated critical resource bottlenecks in microservices architecture, ensuring peak performance across distributed cloud environments.</li>
            </ul>
            <div class="section-header">Contributions</div>
            <ul class="section-content">
                <li>Implemented early SLO violation detection to streamline CPU utilization, driving greater resource efficiency, reducing unnecessary CPU overhead, and saving costs.</li>
            </ul>
        </div>

        <!-- Role 2: Chief Information Security Officer (CISO) -->
        <div class="experience-card">
            <h3>Chief Information Security Officer (CISO)</h3>
            <h4><a href="https://www.bracbank.com/en">BRAC Bank PLC</a> · Nov 2022 – Aug 2023</h4> 
            <h5>Dhaka, Bangladesh</h5>
            <img src="https://play-lh.googleusercontent.com/alpY0C3iFPpBBULGdBBnR0i3mdMEk3M8GR35o7sWcg_OzVakagI11yxqokIGOYrbmcA" alt="BRAC Bank Logo">
            <div class="section-header">Responsibilities</div>
            <ul class="section-content">
                <li>Led tactical security initiatives, aligning goals with business objectives while driving policy creation, risk assessment, knowledge training, and incident response.</li>
                <li>Architected robust cybersecurity solutions to protect data, counter emerging threats, and ensure compliance while proactively monitoring and reporting evolving security trends.</li>
                <li>Fostered strategic stakeholder relationships, effectively communicated security insights, and shared best practices to elevate organizational cybersecurity awareness.</li>
                <li>Led the SOC, ensuring 24x7 threat detection, breach containment, and operational excellence through advanced security techniques.</li>
            </ul>
            <div class="section-header">Contributions</div>
            <ul class="section-content">
                <li>Directed the deployment of advanced Ransomware prevention and Extended Detection and Response (XDR) systems, ensuring stakeholders can operate seamlessly while protecting the bank’s reputation and business continuity.</li>     
                <li>Augmented cybersecurity protocols across 187 branches, 33 sub-branches, and 1,041 agent-banking outlets, safeguarding operations from evolving threats and ensuring uninterrupted service.</li>
                <li>Strengthened BRAC Bank’s position as a member of the Global Alliance for Banking on Values (GABV), aligning with global standards in secure and sustainable banking, reinforcing its leadership in the financial industry.</li>
            </ul>
        </div>

        <!-- Role 3: National IT Security Consultant -->
        <div class="experience-card">
            <h3>National IT Security Consultant</h3>
            <h4><a href="https://bcc.gov.bd/">Bangladesh Computer Council</a> · Jan 2020 – Oct 2022</h4> 
            <h5>Dhaka, Bangladesh</h5>
            <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Bangladesh_Computer_Council_Logo.svg" alt="Bangladesh Computer Council Logo">
            <div class="section-header">Responsibilities</div>
            <ul class="section-content">
                <li>Analyzed security incidents and conducted vulnerability assessments.</li>
                <li>Implemented automated security monitoring systems.</li>
                <li>Developed company-wide cybersecurity awareness training programs.</li>
            </ul>
            <div class="section-header">Contributions</div>
            <ul class="section-content">
                <li>Architected robust cybersecurity solutions to protect data, counter emerging threats, and ensure compliance while proactively monitoring and reporting evolving security trends.</li>
            </ul>
        </div>

    </div>
</div>

<footer>
    <div class="separator"></div>
    <div class="links">
    </div>
    <div class="footer-note">
    </div>
</footer>

</body>
</html>
