---
layout: archive
title: ""
permalink: /awards/
author_profile: true
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Awards</title>
    <style>
        /* General Body Style */
        body {
            font-family: 'Georgia', serif;
            background-color: #f0f7fa;
            margin: 0;
            padding: 0;
            color: #333;
        }

        /* Header styles for better alignment */
        h1, h2, h3, h4, h5, h6 {
            margin: 0em 0 0.5em;
            line-height: 1.2;
            font-family: -apple-system, ".SFNSText-Regular", "San Francisco", "Roboto", "Segoe UI", "Helvetica Neue", "Lucida Grande", Arial, sans-serif;
            font-weight: bold;
        }

        /* Main content container */
        .content {
            width: 100%; 
            max-width: 1100px; /* Slightly smaller width */
            margin: 20px auto; /* Compact margins */
            padding: 15px; /* More compact padding */
            background-color: #ffffff;
            border-radius: 10px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.08); /* Softer shadow */
        }

        .content h2 {
            font-size: 28px;
            color: #1e3d8f;
            font-weight: bold;
            margin-bottom: 15px; /* Smaller margin */
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

        /* Adjusted paragraph text size to be slightly smaller */
        .content p {
            font-size: 17px; /* Reduced by 0.5 from 18px */
            line-height: 1.6; /* Slightly tighter line-height */
            color: #333;
            margin-bottom: 15px; /* Smaller bottom margin */
            text-align: justify;
        }

        /* Styling for smaller text in certifications */
        .certification-card p {
            font-size: 16px; /* 0.5 smaller than the existing text */
        }

        /* Styling the links to remove underlines and adjust color */
        a:link, a:visited, a:hover, a:active {
            color: #1e3d8f;
            text-decoration: none; /* Removed underline */
        }

        a:hover {
            color: #003399; /* Change color on hover */
        }

        /* Style for Cards */
        .certification-layout {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(360px, 1fr)); /* Smaller card width */
            gap: 15px; /* Tighter gap */
            margin-top: 15px;
        }

        .certification-card {
            padding: 10px;
            background-color: #f9f9f9;
            border-radius: 8px; /* Slightly smaller border radius */
            box-shadow: 0 2px 6px rgba(0, 0, 0, 0.05); /* Softer shadow */
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .certification-card h5,
        .certification-card p,
        .certification-card small {
            font-family: 'Georgia', serif;
            color: #333;
        }

        .certification-card h5 {
            font-size: 18px;
            font-weight: bold;
            margin-bottom: 5px; /* Tighter spacing */
        }

        .certification-card small {
            font-size: 15px;
        }

        .certification-card:hover {
            transform: translateY(-3px); /* Subtle hover effect */
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1); /* Softer hover shadow */
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

        /* Flex layout for icon and text */
        .flex-row {
            display: flex;
            align-items: center;
            gap: 12px; /* Increase gap between icon and text */
        }

        .flex-row img {
            width: 45px; /* Slightly larger icon size */
            height: 45px;
            vertical-align: middle;
        }

        .flex-row h5 {
            margin: 0;
            line-height: 1.2;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .certification-layout {
                grid-template-columns: 1fr;
            }
        }

        /* Updated footer styling */
        footer {
            text-align: center;
            margin-top: 30px;
            font-size: 14px;
            color: #aaa;
            font-family: 'Georgia', serif;
            background-color: #f9f9f9; /* Uniform background color */
            padding: 20px 0;
            border-top: none; /* No separation */
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

<!-- Awards Section -->
<div class="content">
    <div class="certification-layout">
        <!-- Awards Section Separator -->
        <div class="separator">Awards Received</div>

        <!-- Awards Cards -->
        <div class="certification-card">
            <div class="education-card">
                <div class="flex-row">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/d/da/UTA_logomark.png" alt="UTA Logo">
                    <h5>STEM Tuition Support</h5>
                </div>
                <p>Honored with a renowned STEM scholarship covering all tuition and fees, alongside a Graduate Teaching Assistantship offer for academic excellence., Fall 2023 - Present<br><small><a href="https://www.uta.edu/academics/schools-colleges/engineering/academics/departments/cse/">The University of Texas at Arlington (UTA)</a></small></p>
            </div>
        </div>

        <div class="certification-card">
            <div class="education-card">
                <div class="flex-row">
                    <img src="https://seeklogo.com/images/B/bangladesh-university-of-professionals-bup-logo-5B259AB69E-seeklogo.com.png" alt="BUP Logo">
                    <h5>Chancellor's Gold Medal</h5>
                </div>
                <p>Recipient of the prestigious Chancellor's Gold Medal, awarded by the President of the People's Republic of Bangladesh, for achieving top honors at the master's level, 2020<br><small><a href="https://bup.edu.bd/academics/academic_details/464">Bangladesh University of Professionals (BUP)</a></small></p>
            </div>
        </div>

        <div class="certification-card">
            <div class="education-card">
                <div class="flex-row">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTad6HftSKi8pNuHC0HCWvGBGtHPqaItaxk1w&s" alt="JICA Logo">
                    <h5>IT Engineers Examinations (ITEE)</h5>
                </div>
                <p>Participated in a competitive examination to support the vision of Digital Bangladesh and earned the distinguished ITEE certification, awarded by JICA, 2010<br><small><a href="https://www.jica.go.jp/english/">Japan International Cooperation Agency (JICA)</a></small></p>
            </div>
        </div>

        <div class="certification-card">
            <div class="education-card">
                <div class="flex-row">
                    <img src="https://play-lh.googleusercontent.com/UfQw66njIZLmRcxcQivESKmgllkMXgDS2njDaUK_SCtL1iP9iCyOiwmVExMdzZV7XKtG" alt="Janata Bank Logo">
                    <h5>Gold Medal</h5>
                </div>
                <p>Received a distinguished gold medal for exceptional performance in 12th grade, awarded by the Janata Bank PLC Employees Benevolent Fund Managing Committee, 2007.<br><small><a href="https://www.jb.com.bd/">Janata Bank PLC</a></small></p>
            </div>
        </div>

    </div>
</div>

<!-- Affiliations Section -->
<div class="content">
    <div class="certification-layout">
        <!-- Affiliations Section Separator -->
        <div class="separator">Affiliations</div>

        <!-- Affiliation Cards (Merged Academic and Professional) -->
        <div class="certification-card">
            <div class="education-card">
                <div class="flex-row">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/d/da/UTA_logomark.png" alt="UTA Logo">
                    <h5>Student Affiliation</h5>
                </div>
                <p>Fall 2023 - Present<br><small><a href="https://www.uta.edu/academics/schools-colleges/engineering/academics/departments/cse/">The University of Texas at Arlington (UTA)</a></small></p>
            </div>
        </div>

        <div class="certification-card">
            <div class="education-card">
                <div class="flex-row">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSBn12ofDmB_Z0obKO8ohLuKUPY2P9ceUF0iw&s" alt="ISACA Logo">
                    <h5>Silver Member</h5>
                </div>
                <p>2017 - Present<br><small><a href="https://www.isaca.org/">Information Systems Audit and Control Association (ISACA)</a></small></p>
            </div>
        </div>

        <div class="certification-card">
            <div class="education-card">
                <div class="flex-row">
                    <img src="https://w7.pngwing.com/pngs/308/703/png-transparent-pmi-hd-logo-thumbnail.png" alt="PMI Logo">
                    <h5>Member</h5>
                </div>
                <p>2020 - Present<br><small><a href="https://my.pmi.org/">Project Management Institute (PMI)</a></small></p>
            </div>
        </div>

        <div class="certification-card">
            <div class="education-card">
                <div class="flex-row">
                    <img src="https://e7.pngegg.com/pngimages/768/788/png-clipart-ec-council-certified-ethical-hacker-computer-security-information-security-certified-ethical-hacker-emblem-label.png" alt="EC-Council Logo">
                    <h5>Member</h5>
                </div>
                <p>2016 - Present<br><small><a href="https://www.eccouncil.org/">EC-Council</a></small></p>
            </div>
        </div>

        <div class="certification-card">
            <div class="education-card">
                <div class="flex-row">
                    <img src="https://upload.wikimedia.org/wikipedia/en/thumb/0/06/Institution_of_Engineers%2C_Bangladesh_Emblem.svg/1200px-Institution_of_Engineers%2C_Bangladesh_Emblem.svg.png" alt="IEB Logo">
                    <h5>Life Member</h5>
                </div>
                <p>2013 - Present<br><small><a href="https://www.iebbd.org/">The Institution of Engineers, Bangladesh (IEB)</a></small></p>
            </div>
        </div>

        <div class="certification-card">
            <div class="education-card">
                <div class="flex-row">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c9/Bangladesh_Computer_Society.svg/1200px-Bangladesh_Computer_Society.svg.png" alt="BCS Logo">
                    <h5>Life Member</h5>
                </div>
                <p>2013 - Present<br><small><a href="https://www.bcsbd.org.bd/">Bangladesh Computer Society (BCS)</a></small></p>
            </div>
        </div>
    </div>
</div>

<footer>

</footer>

</body>
</html>
