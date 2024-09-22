---
layout: archive
title: ""
permalink: /projects/
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
            font-size: 20px;
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
            font-size: 15.5px;
            font-family: 'Georgia', serif;
            line-height: 1.6;
            color: #333;
            text-align: justify;
            margin-bottom: 13px;
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
            color: #333;
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
            font-family: 'Georgia', serif;
            line-height: 1.6;
            color: #333;
            text-align: justify;
            margin-bottom: 13px;
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
    <h2>Noteworthy Completed Projects and Key Involvements</h2>
    <div class="separator"></div>

    <!-- Experience cards -->
    <div class="experience-container">

        <!-- Role 1: Graduate Student Researcher -->
        <div class="experience-card">
            <h3>Graduate Student Researcher</h3>
            <h4>Role: Graduate Student Researcher -<a href="https://www.uta.edu/academics/schools-colleges/engineering/academics/departments/cse/" target="_blank">The University of Texas at Arlington (UTA)</a></h4>
            <div class="section-header">Responsibilities</div>
            <ul class="section-content">
                <li>Optimized resource allocation and scaling strategies for microservice-based cloud applications, enhancing computational efficiency and overall system performance.</li>
                <li>Designed and implemented a Kubernetes-based Resource Manager to orchestrate microservices, dynamically improving deployment scalability and operational resilience.</li>
                <li>Identified and mitigated critical resource bottlenecks in microservices architecture, ensuring peak performance across distributed cloud environments.</li>
            </ul>
        </div>

        <!-- Role 2: Implementation of Extended Detection and Response (XDR) Tools -->
        <div class="experience-card">
            <h3>Implementation of Extended Detection and Response (XDR) Tools</h3>
            <h4>Role: Project Manager - <a href="https://www.bracbank.com/en" target="_blank">BRAC Bank PLC</a></h4> 
            <div class="section-header">Particulars</div>
            <ul class="section-content">
                <li>Strengthened cybersecurity posture by automating detection, fostering collaboration across teams, and driving continuous threat-hunting and system improvements.</li>
                <li>Directed the strategic adoption and deployment of XDR solutions, aligning with business objectives and integrating with existing security tools to enhance threat detection and response.</li>
                <li>Orchestrated vendor selection, contract negotiations, and seamless XDR integration, ensuring efficient data collection, governance, and operational optimization.</li>
            </ul>
        </div>

        <!-- Role 3: Advanced Ransomware Prevention and Early Detection -->
        <div class="experience-card">
            <h3>Advanced Ransomware Prevention and Early Detection</h3>
            <h4>Role: Project Manager - <a href="https://www.bracbank.com/en" target="_blank">BRAC Bank PLC</a></h4> 
            <div class="section-header">Particulars</div>
            <ul class="section-content">
                <li>Proactively secured systems by patching vulnerabilities, leveraging threat intelligence, maintaining offline backups, minimizing ransomware risks, and ensuring swift recovery.</li>
                <li>Implemented a multi-layered security architecture, including firewalls, EDR, and DDoS mitigation, to enhance ransomware defense and ensure early threat detection and response.</li>
                <li>Led employee training and developed a comprehensive incident response plan, empowering staff to act as the first line of defense and ensuring coordinated responses to ransomware attacks.</li>
            </ul>
        </div>

        <!-- Role 4: National IT Security Consultant -->
        <div class="experience-card">
            <h3><a href="https://www.cirt.gov.bd/" target="_blank">Bangladesh (BGD) e-GOV CIRT</a></h3>
            <h4>Role: Team Member - <a href="https://bcc.gov.bd/" target="_blank">Bangladesh Computer Council</a> Funded Projects by <a href="https://www.worldbank.org/" target="_blank">World Bank Group</a></h4> 
            <div class="section-header">Responsibilities</div>
            <ul class="section-content">
                <li>Collaborated in establishing a Cybersecurity Research Wing, assisting with incident response policies, infrastructure setup, and partnerships with international CERTs to enhance e-government security.</li>
                <li>Worked alongside in developing the National Cyber Security Strategy and Risk Assessment Framework, supporting efforts to strengthen cyber defenses and aiding implementation across government agencies.</li>
                <li>Supported the setup of a Digital Forensic Lab, providing input on tools, assisting in investigator training, and ensuring compliance with legal requirements for cybercrime investigations.</li>
                <li>Participated in Vulnerability Assessments for Bangladesh Bank, helping identify risks, recommending remediation actions, and offering security insights for system improvements.</li>
                <li>Assisted in deploying Cyber Sensors in Critical Infrastructures, contributing to risk assessments and implementing monitoring systems to safeguard vital sectors from cyber threats.</li>
            </ul>
        </div>

                <!-- Role 4: National IT Security Consultant -->
        <div class="experience-card">
            <h3>National IT Security Consultant</h3>
            <h4><a href="https://bcc.gov.bd/" target="_blank">Bangladesh Computer Council</a> Funded Projects by <a href="https://www.worldbank.org/" target="_blank">World Bank Group</a></h4> 
            <div class="section-header">Responsibilities</div>
            <ul class="section-content">
                <li>Served as a key strategist in strengthening Bangladesh's cybersecurity landscape through comprehensive initiatives addressing technical and strategic challenges.</li>
                <li>Demonstrated expertise in cyber threats, risk management, infrastructure development, and policy formulation, which is critical in advancing the nation's cybersecurity posture.</li>
                <li>Contributed to building a resilient cybersecurity defense ecosystem for the Government of Bangladesh, enhancing technical capabilities and fostering security awareness across various sectors.</li>
                <li>Acted as a pivotal force in shaping national cybersecurity policies and awareness efforts, collaborating with government agencies, financial institutions, law enforcement agencies (LEAs), critical infrastructures, academia, and civil societies.</li>
            </ul>
        </div>

        <!-- Additional roles omitted for brevity -->

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
