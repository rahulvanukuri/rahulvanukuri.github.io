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
            background-color: #ffffff; /* Changed to white */
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
            background-color: #ffffff; /* Kept white for content container */
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
            font-size: 26px;
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
            font-size: 16px;
            line-height: 1.6;
            color: #333;
            margin-bottom: 15px;
            text-align: justify;
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
            background-color: #f9f9f9; /* Changed to light grey */
            border-radius: 12px;
            padding: 15px; /* Adjusted padding to make it more compact */
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
            font-size: 20px;
            font-weight: bold;
            color: #1e3d8f;
            margin-bottom: 8px;
        }

        .experience-card h4 {
            font-size: 16px;
            font-weight: normal;
            margin-bottom: 8px; /* Adjusted margin for compactness */
            color: #666;
        }

        .experience-card h5 {
            font-size: 14px;
            color: #999;
            margin-bottom: 6px; /* Reduced bottom margin */
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
            margin-bottom: 6px; /* Reduced margin for compactness */
            border-bottom: 2px solid #cccccc;
            padding-bottom: 3px; /* Reduced padding for compact look */
        }

        .section-content {
            font-size: 15px;
            line-height: 1.5; /* Slightly reduced line-height */
            color: #333;
            margin-bottom: 10px; /* Reduced bottom margin */
        }

        /* Footer styles */
        footer {
            text-align: center;
            margin-top: 40px;
            font-size: 14px;
            color: #333;
            font-family: 'Georgia', serif;
            background-color: #ffffff; /* Changed to white */
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
    <h1>Comprehensive Expertise Shaped by Over 12 Years of Professional Experience</h1>
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
            <p class="section-content">
                <li>Optimize resource usage of microservice applications in cloud computing.</li>
                <li>Develop Resource Manager on top of Kubernetes for microservices.</li>
                <li>Develop Reinforcement Learning Agents to improve task completion time.</li>
                <li>Identify root cause of microservice resource bottlenecks.</li>
            </p>
            <div class="section-header">Contributions</div>
            <p class="section-content">Architected robust cybersecurity solutions to protect data, counter emerging threats, and ensure compliance while proactively monitoring and reporting evolving security trends.</p>
        </div>

        <!-- Role 2: Chief Information Security Officer (CISO) -->
        <div class="experience-card">
            <h3>Chief Information Security Officer (CISO)</h3>
            <h4><a href="https://www.bracbank.com/en">BRAC Bank PLC</a> · Nov 2022 – Aug 2023</h4> 
            <h5>Dhaka, Bangladesh</h5>
            <img src="https://play-lh.googleusercontent.com/alpY0C3iFPpBBULGdBBnR0i3mdMEk3M8GR35o7sWcg_OzVakagI11yxqokIGOYrbmcA" alt="BRAC Bank Logo">
            <div class="section-header">Responsibilities</div>
            <p class="section-content">
                <li>Led security initiatives, aligning goals with business objectives.</li>
                <li>Architected robust cybersecurity solutions to protect data.</li>
                <li>Directed Security Operation Center (SOC), ensuring 24x7 threat detection.</li>
                <li>Monitored and reported evolving security trends.</li>
            </p>
            <div class="section-header">Contributions</div>
            <p class="section-content">Architected robust cybersecurity solutions to protect data, counter emerging threats, and ensure compliance while proactively monitoring and reporting evolving security trends.</p>
        </div>

        <!-- Role 3: Senior Security Analyst -->
        <div class="experience-card">
            <h3>National IT Security Consultant</h3>
            <h4><a href="https://bcc.gov.bd/"Bangladesh Computer Concil</a> · Jan 2020 – Oct 2022</h4> 
            <h5>Dhaka, Bangladesh</h5>
            <img src="https://cdn.theorg.com/8dd5dc74-0208-4028-86eb-e8e613160865_thumb.jpg" alt="XYZ Company Logo">
            <div class="section-header">Responsibilities</div>
            <p class="section-content">
                <li>Analyzed security incidents and conducted vulnerability assessments.</li>
                <li>Implemented automated security monitoring systems.</li>
                <li>Developed company-wide cybersecurity awareness training programs.</li>
            </p>
            <div class="section-header">Contributions</div>
            <p class="section-content">Architected robust cybersecurity solutions to protect data, counter emerging threats, and ensure compliance while proactively monitoring and reporting evolving security trends.</p>
        </div>

                <!-- Role 4: Senior Security Analyst -->
        <div class="experience-card">
            <h3>Assistant Vice President</h3>
            <h4><a href="https://www.ebl.com.bd/"Eastern Bank PLC</a> · Nov 2016 – Dec 2018</h4> 
            <h5>Dhaka, Bangladesh</h5>
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/29/EBL_Registered_Corporate_Logo.svg/963px-EBL_Registered_Corporate_Logo.svg.png" alt="XYZ Company Logo">
            <div class="section-header">Responsibilities</div>
            <p class="section-content">
                <li>Analyzed security incidents and conducted vulnerability assessments.</li>
                <li>Implemented automated security monitoring systems.</li>
                <li>Developed company-wide cybersecurity awareness training programs.</li>
            </p>
            <div class="section-header">Contributions</div>
            <p class="section-content">Architected robust cybersecurity solutions to protect data, counter emerging threats, and ensure compliance while proactively monitoring and reporting evolving security trends.</p>
        </div>

                <!-- Role 3: Senior Security Analyst -->
        <div class="experience-card">
            <h3>National IT Security Consultant</h3>
            <h4><a href="https://bcc.gov.bd/"Bangladesh Computer Concil</a> · Jan 2020 – Oct 2022</h4> 
            <h5>Dhaka, Bangladesh</h5>
            <img src="https://cdn.theorg.com/8dd5dc74-0208-4028-86eb-e8e613160865_thumb.jpg" alt="XYZ Company Logo">
            <div class="section-header">Responsibilities</div>
            <p class="section-content">
                <li>Analyzed security incidents and conducted vulnerability assessments.</li>
                <li>Implemented automated security monitoring systems.</li>
                <li>Developed company-wide cybersecurity awareness training programs.</li>
            </p>
            <div class="section-header">Contributions</div>
            <p class="section-content">Architected robust cybersecurity solutions to protect data, counter emerging threats, and ensure compliance while proactively monitoring and reporting evolving security trends.</p>
        </div>

                <!-- Role 3: Senior Security Analyst -->
        <div class="experience-card">
            <h3>National IT Security Consultant</h3>
            <h4><a href="https://bcc.gov.bd/"Bangladesh Computer Concil</a> · Jan 2020 – Oct 2022</h4> 
            <h5>Dhaka, Bangladesh</h5>
            <img src="https://cdn.theorg.com/8dd5dc74-0208-4028-86eb-e8e613160865_thumb.jpg" alt="XYZ Company Logo">
            <div class="section-header">Responsibilities</div>
            <p class="section-content">
                <li>Analyzed security incidents and conducted vulnerability assessments.</li>
                <li>Implemented automated security monitoring systems.</li>
                <li>Developed company-wide cybersecurity awareness training programs.</li>
            </p>
            <div class="section-header">Contributions</div>
            <p class="section-content">Architected robust cybersecurity solutions to protect data, counter emerging threats, and ensure compliance while proactively monitoring and reporting evolving security trends.</p>
        </div>

                <!-- Role 3: Senior Security Analyst -->
        <div class="experience-card">
            <h3>National IT Security Consultant</h3>
            <h4><a href="https://bcc.gov.bd/"Bangladesh Computer Concil</a> · Jan 2020 – Oct 2022</h4> 
            <h5>Dhaka, Bangladesh</h5>
            <img src="https://cdn.theorg.com/8dd5dc74-0208-4028-86eb-e8e613160865_thumb.jpg" alt="XYZ Company Logo">
            <div class="section-header">Responsibilities</div>
            <p class="section-content">
                <li>Analyzed security incidents and conducted vulnerability assessments.</li>
                <li>Implemented automated security monitoring systems.</li>
                <li>Developed company-wide cybersecurity awareness training programs.</li>
            </p>
            <div class="section-header">Contributions</div>
            <p class="section-content">Architected robust cybersecurity solutions to protect data, counter emerging threats, and ensure compliance while proactively monitoring and reporting evolving security trends.</p>
        </div>

        <!-- Add more roles as needed -->

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
 · Aug 2023 – Present</h4>
            <h5>Texas, USA</h5>
            <img src="https://upload.wikimedia.org/wikipedia/commons/d/da/UTA_logomark.png" alt="UTA Logo">
            <div class="section-header">Responsibilities</div>
            <p class="section-content">
                <li>Optimize resource usage of microservice applications in cloud computing.</li>
                <li>Develop Resource Manager on top of Kubernetes for microservices.</li>
                <li>Develop Reinforcement Learning Agents to improve task completion time.</li>
                <li>Identify root cause of microservice resource bottlenecks.</li>
            </p>
            <div class="section-header">Contributions</div>
            <p class="section-content">Architected robust cybersecurity solutions to protect data, counter emerging threats, and ensure compliance while proactively monitoring and reporting evolving security trends.</p>
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
            <div class="section-header">Contributions</div>
            <p class="section-content">Architected robust cybersecurity solutions to protect data, counter emerging threats, and ensure compliance while proactively monitoring and reporting evolving security trends.</p>
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
            <div class="section-header">Contributions</div>
            <p class="section-content">Architected robust cybersecurity solutions to protect data, counter emerging threats, and ensure compliance while proactively monitoring and reporting evolving security trends.</p>
        </div>

        <!-- Add more roles as needed -->

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
