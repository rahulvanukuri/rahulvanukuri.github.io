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
    <title>Accreditations & Credentials</title>
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
            max-width: 1100px;
            margin: 20px auto;
            padding: 15px;
            background-color: #ffffff;
            border-radius: 10px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.08);
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
            width: 100%;
            height: 1px;
            background-color: #cccccc;
            margin-top: 8px;
        }

        .content p {
            font-size: 17px;
            line-height: 1.6;
            color: #333;
            margin-bottom: 15px;
            text-align: justify;
        }

        /* Certifications Grid Layout */
        .certification-layout {
            display: grid;
            grid-template-columns: repeat(2, 1fr); /* Two cards per row */
            gap: 15px;
            margin-top: 15px;
        }

        /* Certification card styling */
        .certification-card {
            background-color: #f9f9f9;
            border-radius: 8px;
            box-shadow: 0 2px 6px rgba(0, 0, 0, 0.05);
            margin-bottom: 15px;
            padding: 15px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .certification-card:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
        }

        .certification-card h3 {
            font-size: 20px;
            font-weight: bold;
            color: #1e3d8f;
        }

        .certification-card h4 {
            font-size: 18px;
            font-weight: normal;
            margin-bottom: 10px;
            color: #666;
        }

        .certification-card img {
            width: 40px;
            height: 40px;
            object-fit: contain;
            margin-right: 15px;
        }

        .section-header {
            font-size: 16px;
            font-weight: bold;
            color: #1e3d8f;
            margin-bottom: 10px;
        }

        .section-content {
            font-size: 16px;
            line-height: 1.6;
            color: #333;
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

<!-- Accreditations & Credentials Section -->
<div class="content">
    <div class="separator">Professional Roles</div>

    <!-- Seven sets -->
    {% for i in (1..7) %}
    <div class="certification-card">
        <!-- Section 1: Title and Image -->
        <div class="section-header">Chief Information Security Officer (CISO)</div>
        <h4>BRAC Bank PLC · Nov 2022 – Aug 2023 · Dhaka, Bangladesh</h4>
        <img src="/path_to_image/file-XTQxGfreDJG87CPJniV7h0Bm.png" alt="BRAC Bank Logo">

        <!-- Section 2: Responsibilities -->
        <div class="section-header">Responsibilities</div>
        <p class="section-content">Spearheaded tactical security initiatives, aligning goals with business objectives while driving policy creation, risk assessment, knowledge training, and incident response.</p>

        <!-- Section 3: Contributions -->
        <div class="section-header">Contributions</div>
        <p class="section-content">Architected robust cybersecurity solutions to protect data, counter emerging threats, and ensure compliance while proactively monitoring and reporting evolving security trends.</p>

        <!-- Section 4: Projects -->
        <div class="section-header">Projects</div>
        <p class="section-content">Led the SOC, ensuring 24x7 threat detection, breach containment, and operational excellence through advanced security techniques. Fostered strategic stakeholder relationships and shared best practices to elevate organizational cybersecurity knowledge.</p>
    </div>
    {% endfor %}
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
