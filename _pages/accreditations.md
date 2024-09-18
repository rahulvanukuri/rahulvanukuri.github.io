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
            display: flex;
            align-items: center;
            padding: 10px;
            background-color: #f9f9f9;
            border-radius: 8px;
            box-shadow: 0 2px 6px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .certification-card img {
            width: 40px;
            height: 40px;
            object-fit: contain;
            margin-right: 15px;
        }

        .certification-card h6 {
            font-size: 16px;
            font-weight: normal;
            margin: 0;
        }

        .certification-card:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
        }

        /* Section Separator */
        .separator {
            grid-column: 1 / -1;
            text-align: center;
            font-size: 22px;
            font-weight: bold;
            color: #1e3d8f;
            margin-top: 10px;
            margin-bottom: 10px;
        }

        .separator::after {
            content: '';
            display: block;
            width: 50%;
            height: 1px;
            background-color: #cccccc;
            margin: 5px auto;
        }

        @media (max-width: 768px) {
            .certification-layout {
                grid-template-columns: 1fr;
            }
        }

        footer {
            text-align: center;
            margin-top: 30px;
            font-size: 14px;
            color: #aaa;
            font-family: 'Georgia', serif;
            background-color: #f9f9f9;
            padding: 20px 0;
        }

        footer .links {
            margin-bottom: 10px;
        }

        footer .links a {
            margin: 0 10px;
            color: #333;
        }

        footer .links a:hover {
            text-decoration: underline;
        }

    </style>
</head>
<body>

<!-- Accreditations & Credentials Section -->
<div class="content">
    <div class="separator">Project Management</div>

    <!-- Two-Column Layout for Cards -->
    <div class="certification-layout">
        <div class="certification-card">
            <img src="https://wiki.agileana.com/images/6/68/PMP_project_management_professional_certification_badge.png" alt="PMP Icon">
            <h6>Project Management Professional (PMP)</h6>
        </div>

        <div class="certification-card">
            <img src="https://wc1.prod3.arlocdn.net/p/7c28b8671fc8478d801c44160b25a0eb/d/f7ziOhu7VbzFHhE3q3MP3PRvpUEiqRjaosR9HGwJQ1C11rfD/PRINCE2%20-%20Practioner-720x480pix.png" alt="PRINCE2 Practitioner Icon">
            <h6>PRINCE2 Practitioner</h6>
        </div>
    </div>
</div>

<!-- Governance, Risk & Compliance Section -->
<div class="content">
    <div class="separator">Governance, Risk & Compliance</div>

    <!-- Two-Column Layout for Cards -->
    <div class="certification-layout">
        <div class="certification-card">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTad6HftSKi8pNuHC0HCWvGBGtHPqaItaxk1w&s" alt="Governance Icon">
            <h6>Governance Certification</h6>
        </div>

        <div class="certification-card">
            <img src="https://some-path-to-certification-icon.png" alt="Risk Management Icon">
            <h6>Risk Management Practitioner</h6>
        </div>
    </div>
</div>

<!-- IT Audit Section -->
<div class="content">
    <div class="separator">IT Audit</div>

    <!-- Two-Column Layout for Cards -->
    <div class="certification-layout">
        <div class="certification-card">
            <img src="https://some-path-to-certification-icon.png" alt="IT Audit Icon">
            <h6>Certified IT Auditor</h6>
        </div>

        <div class="certification-card">
            <img src="https://some-path-to-certification-icon.png" alt="IT Compliance Icon">
            <h6>Certified IT Compliance Auditor</h6>
        </div>
    </div>
</div>

<!-- Information & Cyber Security Section -->
<div class="content">
    <div class="separator">Information & Cyber Security</div>

    <!-- Two-Column Layout for Cards -->
    <div class="certification-layout">
        <div class="certification-card">
            <img src="https://some-path-to-certification-icon.png" alt="Cyber Security Icon">
            <h6>Cyber Security Certification</h6>
        </div>

        <div class="certification-card">
            <img src="https://some-path-to-certification-icon.png" alt="InfoSec Icon">
            <h6>Information Security Certification</h6>
        </div>
    </div>
</div>

<footer>
    <div class="links">
        <a href="#">Sitemap</a> | <a href="#">GitHub</a> | <a href="#">RSS</a>
    </div>
    © 2024 Mohammad Shahedur Rahman. Powered by Jekyll & AcademicPages, a fork of Minimal Mistakes.
</footer>

</body>
</html>
