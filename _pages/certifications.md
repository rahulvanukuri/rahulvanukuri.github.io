---
layout: archive
title: ""
permalink: /certifications/
author_profile: true
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: 'Georgia', serif;
            background-color: #f7f7f7;
            color: #333;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        .separator {
            grid-column: 1 / -1;
            text-align: center;
            font-size: 24px; /* Matching Biography section */
            font-family: 'Georgia', serif;
            font-weight: bold;
            color: #1e3d8f; /* Blue color as in Biography */
            margin-top: 20px;
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

        .certifications-list {
            list-style-type: none;
            padding: 0;
            margin: 40px auto;
            max-width: 800px;
        }

        .certifications-list li {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
            padding: 10px;
            border-radius: 10px;
            background-color: #f9f9f9;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .certifications-list li:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.15);
        }

        .certifications-list li img {
            width: 50px;
            height: 50px;
            margin-right: 15px;
        }

        .certifications-list li p {
            margin: 0;
            font-size: 16px;
            color: #333;
        }
    </style>
</head>
<body>

<!-- Certifications Section -->
<div class="separator">Certifications</div>
<ul class="certifications-list">
    <li>
        <img src="https://upload.wikimedia.org/wikipedia/commons/9/95/CertifiedInformationSystemsSecurityProfessional_CISSP.png" alt="CISSP">
        <p>Certified Information Systems Security Professional (CISSP)</p>
    </li>

    <li>
        <img src="https://upload.wikimedia.org/wikipedia/commons/7/72/CertifiedEthicalHacker_CEH.png" alt="CEH">
        <p>Certified Ethical Hacker (CEH)</p>
    </li>

    <li>
        <img src="https://upload.wikimedia.org/wikipedia/commons/3/35/CertifiedInformationSecurityManager_CISM.png" alt="CISM">
        <p>Certified Information Security Manager (CISM)</p>
    </li>

    <li>
        <img src="https://upload.wikimedia.org/wikipedia/commons/8/88/CertifiedCloudSecurityProfessional_CCSP.png" alt="CCSP">
        <p>Certified Cloud Security Professional (CCSP)</p>
    </li>

    <li>
        <img src="https://upload.wikimedia.org/wikipedia/commons/9/9f/ProjectManagementProfessional_PMP.png" alt="PMP">
        <p>Project Management Professional (PMP)</p>
    </li>
</ul>

</body>
</html>
