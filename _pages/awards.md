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
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        /* Main content container */
        .content {
            width: 128%;
            margin: 0 auto;
            padding: 20px;
            max-width: 1000px;
            flex: 1;
        }

        /* Section Separator */
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

        /* Awards Card Style */
        .certification-card {
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            padding: 20px;
            margin-bottom: 20px;
            transition: box-shadow 0.3s ease;
        }

        .certification-card:hover {
            box-shadow: 0 6px 16px rgba(0, 0, 0, 0.1);
        }

        .flex-row {
            display: flex;
            align-items: center;
            gap: 12px;
        }

        .flex-row img {
            width: 45px;
            height: 45px;
            vertical-align: middle;
        }

        .flex-row h5 {
            margin: 0;
            font-size: 18px;
            font-weight: bold;
            line-height: 1.2;
        }

        .certification-card p,
        .certification-card small {
            font-family: 'Georgia', serif;
            color: #333;
        }

        .certification-card p {
            font-size: 16px;
            margin-top: 10px;
        }

        /* Adjusting anchor links */
        a:link, a:visited, a:hover, a:active {
            color: #1e3d8f;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        /* Footer Section */
        footer {
            text-align: center;
            font-size: 14px;
            color: #aaa;
            padding: 20px 0;
            background: linear-gradient(to top, #f0f7fa, #ffffff);
            border-top: 1px solid #ccc;
            margin-top: 40px;
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

        /* Responsive Design */
        @media (max-width: 768px) {
            .flex-row {
                flex-direction: column;
                align-items: flex-start;
            }

            .flex-row img {
                width: 40px;
                height: 40px;
            }

            .flex-row h5 {
                font-size: 16px;
            }

            .certification-card p {
                font-size: 14px;
            }
        }
    </style>
</head>
<body>

<!-- Awards Section -->
<div class="content">
    <div class="separator">Awards Received</div>

    <!-- Award Card 1 -->
    <div class="certification-card">
        <div class="flex-row">
            <img src="https://upload.wikimedia.org/wikipedia/commons/d/da/UTA_logomark.png" alt="UTA Logo">
            <h5>STEM Tuition Support</h5>
        </div>
        <p>Honored with a renowned STEM scholarship covering all tuition and fees, alongside a Graduate Teaching Assistantship offer for academic excellence., Fall 2023 - Present<br><small><a href="https://www.uta.edu/academics/schools-colleges/engineering/academics/departments/cse/">The University of Texas at Arlington (UTA)</a></small></p>
    </div>

    <!-- Award Card 2 -->
    <div class="certification-card">
        <div class="flex-row">
            <img src="https://seeklogo.com/images/B/bangladesh-university-of-professionals-bup-logo-5B259AB69E-seeklogo.com.png" alt="BUP Logo">
            <h5>Chancellor's Gold Medal</h5>
        </div>
        <p>Recipient of the prestigious Chancellor's Gold Medal, awarded by the President of the People's Republic of Bangladesh, for achieving top honors at the master's level, 2020<br><small><a href="https://bup.edu.bd/academics/academic_details/464">Bangladesh University of Professionals (BUP)</a></small></p>
    </div>

    <!-- Award Card 3 -->
    <div class="certification-card">
        <div class="flex-row">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTad6HftSKi8pNuHC0HCWvGBGtHPqaItaxk1w&s" alt="JICA Logo">
            <h5>IT Engineers Examinations (ITEE)</h5>
        </div>
        <p>Participated in a competitive examination to support the vision of Digital Bangladesh and earned the distinguished ITEE certification, awarded by JICA, 2010<br><small><a href="https://www.jica.go.jp/english/">Japan International Cooperation Agency (JICA)</a></small></p>
    </div>

    <!-- Award Card 4 -->
    <div class="certification-card">
        <div class="flex-row">
            <img src="https://play-lh.googleusercontent.com/UfQw66njIZLmRcxcQivESKmgllkMXgDS2njDaUK_SCtL1iP9iCyOiwmVExMdzZV7XKtG" alt="Janata Bank Logo">
            <h5>Gold Medal</h5>
        </div>
        <p>Received a distinguished gold medal for exceptional performance in 12th grade, awarded by the Janata Bank PLC Employees Benevolent Fund Managing Committee, 2007.<br><small><a href="https://www.jb.com.bd/">Janata Bank PLC</a></small></p>
    </div>

</div>

<!-- Footer Section -->
<footer>
    <div class="links">
        <a href="#">Sitemap</a> | <a href="#">GitHub</a> | <a href="#">RSS</a>
    </div>
    © 2024 Mohammad Shahedur Rahman. Powered by Jekyll & AcademicPages, a fork of Minimal Mistakes.
</footer>

</body>
</html>
