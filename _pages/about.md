---
permalink: /
title: "Biography"
excerpt: "Biography"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <!-- Link to Google Fonts for Nunito -->
    <link href="https://fonts.googleapis.com/css2?family=Nunito:wght@300;400;600;800&display=swap" rel="stylesheet">

    <style>
        body {
            font-family: 'Nunito', sans-serif; /* Use the Nunito font */
            margin: 0;
            padding: 0;
            background-color: #f4f7f6;
            color: #333;
            line-height: 1.7;
        }
        
        .container {
            max-width: 1200px;
            margin: 30px auto; /* Reduced margin for better vertical alignment */
            padding: 40px;
            background-color: white;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            border-radius: 15px;
        }
        
        h1, h2 {
            color: #222;
            text-align: center;
            font-weight: 800; /* Bolder headings */
            font-size: 36px;
            margin-bottom: 20px;
        }
        
        p {
            text-align: justify;
            margin-bottom: 20px;
            font-size: 18px;
            color: #555;
        }
        
        a {
            text-decoration: none;
            color: #007BFF;
            font-weight: bold;
            transition: color 0.3s ease;
        }
        
        a:hover {
            color: #0056b3;
        }

        /* Layout for biography content */
        .bio-layout {
            display: flex;
            align-items: flex-start; /* Align biography on the same line as the image */
            gap: 30px; /* Add space between the image and biography */
        }

        .bio-image {
            width: 30%; /* Set a fixed width for the image section */
        }
        
        .bio-content {
            width: 70%; /* Biography will take up remaining space */
        }
        
        /* News section styling */
        .news-section {
            margin-top: 50px;
            padding-top: 30px;
        }

        .news-item {
            display: flex;
            align-items: center;
            padding: 15px;
            margin-bottom: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .news-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.15);
        }

        .news-item strong {
            font-size: 18px;
            color: #333;
            flex: 0 0 150px;
            text-align: left;
        }

        .news-item p {
            margin: 0;
            font-size: 16px;
            color: #555;
            text-align: left;
            flex: 1;
        }

        /* Call-to-action section */
        .cta {
            text-align: center;
            margin-top: 40px;
        }

        .cta p {
            font-size: 1.3em;
            color: #007BFF;
            margin-bottom: 20px;
        }

        .cta a {
            font-size: 1.1em;
            color: #fff;
            background-color: #007BFF;
            padding: 12px 25px;
            border-radius: 30px;
            text-decoration: none;
            display: inline-block;
            transition: background-color 0.3s ease, transform 0.2s;
        }

        .cta a:hover {
            background-color: #0056b3;
            transform: translateY(-2px);
        }

        .cta a:active {
            transform: translateY(0);
        }

        /* Responsive design adjustments */
        @media (max-width: 768px) {
            .container {
                padding: 15px;
            }

            h1, h2 {
                font-size: 28px;
            }

            .cta a {
                padding: 10px 20px;
            }

            .news-item strong {
                flex: 0 0 120px;
                font-size: 16px;
            }

            .news-item p {
                font-size: 14px;
            }

            .bio-layout {
                flex-direction: column; /* Stack image and content vertically on smaller screens */
            }

            .bio-image, .bio-content {
                width: 100%; /* Make both sections take full width */
            }
        }
    </style>
</head>
<body>

<div class="container">
    <!-- Biography Layout -->
    <div class="bio-layout">
        <div class="bio-image">
            <!-- Add your profile picture here (example image link) -->
            <img src="your-image-link.png" alt="Profile Picture" style="border-radius: 50%; width: 100%;">
        </div>
        <div class="bio-content">
            <h1>Biography</h1>
            <p>I am a Ph.D. student in the Computer Science department at <a href="https://www.uta.edu/academics/schools-colleges/engineering/academics/departments/cse/">The University of Texas at Arlington (UTA)</a>, where <a href="https://crystal.uta.edu/~mislam/">Dr. Mohammad Atiqul Islam</a> serves as my doctoral advisor. My research focuses on high-performance computing, cybersecurity, machine learning, resource autoscaling, and microservices.</p>

            <p>Before starting my Ph.D., I accrued over 12 years of professional experience in Bangladesh in numerous critical roles including Chief Information Security Officer (CISO) at <a href="https://www.bracbank.com/">BRAC Bank PLC</a> and IT auditor and security expert for several Bangladesh Government projects (<a href="https://www.cirt.gov.bd/">BGD e-GOV CIRT</a>) funded by the <a href="https://www.worldbank.org/">World Bank</a>. Additionally, I gained significant expertise in cybersecurity, risk management, and IT auditing through my work with <a href="https://www.ibm.com/">IBM Bangladesh</a> and <a href="https://home.kpmg/xx/en/home.html">KPMG Bangladesh</a>, one of the Big Four accounting firms.</p>

            <p>In 2011, I earned my B.Sc. in Computer Science and Engineering (CSE) from <a href="https://cse.buet.ac.bd/">Bangladesh University of Engineering and Technology (BUET)</a>. Later, I pursued a Master’s in Information Systems Security from <a href="https://bup.edu.bd/academics/academic_details/464">Bangladesh University of Professionals (BUP)</a> in 2018, where I graduated with a perfect CGPA and received the Presidential gold medal. Additionally, I completed an MBA from the <a href="https://www.fbs-du.com/mis.php">University of Dhaka (DU)</a> majoring in Management Information Systems (MIS). I began my Ph.D. journey in the Fall of 2023.</p>
        </div>
    </div>

    <!-- Career Highlights Section -->
    <div class="news-section">
        <h2>Career Highlights</h2>
        <div class="news">
            <div class="news-item">
                <strong>August 2023:</strong>
                <p>Began my Ph.D. journey at the Rigorous Design Lab (RiDL) at the University of Texas at Arlington.</p>
            </div>
            <div class="news-item">
                <strong>January 2020:</strong>
                <p>Awarded a gold medal by the University Chancellor (President of the People's Republic of Bangladesh) for achieving a perfect CGPA of 4.0 in my master's degree.</p>
            </div>
            <div class="news-item">
                <strong>October 2010:</strong>
                <p>Earned the Information Technology Engineers Examination for Digital Bangladesh Certificate, conducted by the Japan International Cooperation Agency (JICA).</p>
            </div>
            <div class="news-item">
                <strong>March 2007:</strong>
                <p>Awarded a gold medal from the Governor of the Central Bank of Bangladesh (Bangladesh Bank) for outstanding performance in the Higher Secondary Certificate Exam (12th Grade).</p>
            </div>
        </div>
    </div>

    <!-- Call-to-Action -->
    <div class="cta">
        <p>Feel free to reach out if you have any questions or would like to collaborate on research projects!</p>
        <a href="mailto:your.email@example.com">Contact Me</a>
    </div>
</div>

</body>
</html>
