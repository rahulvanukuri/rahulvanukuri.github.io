---
permalink: /
title: "Biography"
excerpt: "Biography"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f7f6;
            color: #333;
        }

        .container {
            max-width: 1200px;
            margin: 50px auto;
            padding: 20px;
            background-color: white;
            border-radius: 15px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        h2 {
            text-align: center;
            font-weight: 700;
            color: #222;
            font-size: 28px;
            margin-bottom: 25px;
        }

        p {
            text-align: justify;
            font-size: 18px;
            line-height: 1.7;
            color: #555;
            margin-bottom: 25px;
        }

        a {
            color: #007BFF;
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            color: #0056b3;
            text-decoration: underline;
        }

        /* Career Highlights section */
        .highlights-section {
            margin-top: 50px;
        }

        .highlight-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .highlight-card {
            padding: 20px;
            background-color: #f9f9f9;
            border-radius: 10px;
            transition: transform 0.3s, box-shadow 0.3s;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .highlight-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }

        .highlight-card strong {
            display: block;
            font-size: 18px;
            margin-bottom: 10px;
            color: #333;
        }

        /* Call to Action Button */
        .cta {
            text-align: center;
            margin-top: 50px;
        }

        .cta a {
            display: inline-block;
            padding: 15px 30px;
            background-color: #007BFF;
            color: white;
            font-size: 18px;
            border-radius: 50px;
            text-decoration: none;
            transition: background-color 0.3s ease, transform 0.2s ease;
        }

        .cta a:hover {
            background-color: #0056b3;
            transform: translateY(-3px);
        }

        /* Make it responsive */
        @media (max-width: 768px) {
            h2 {
                font-size: 24px;
            }

            p {
                font-size: 16px;
            }

            .highlight-card {
                padding: 15px;
            }

            .cta a {
                font-size: 16px;
                padding: 10px 20px;
            }
        }

    </style>
</head>
<body>

<div class="container">
    <!-- Biography Section -->
    <div class="biography-section">
        <p>I am a Ph.D. student in the Computer Science department at <a href="https://www.uta.edu/academics/schools-colleges/engineering/academics/departments/cse/">The University of Texas at Arlington (UTA)</a>, where <a href="https://crystal.uta.edu/~mislam/">Dr. Mohammad Atiqul Islam</a> serves as my doctoral advisor. My research focuses on high-performance computing, cybersecurity, machine learning, resource autoscaling, and microservices.</p>

        <p>Before starting my Ph.D., I accrued over 12 years of professional experience in Bangladesh in numerous critical roles including Chief Information Security Officer (CISO) at <a href="https://www.bracbank.com/en/">BRAC Bank PLC</a> and IT auditor and security expert for several Bangladesh Government projects (<a href="https://www.cirt.gov.bd/">BGD e-GOV CIRT</a>) funded by the <a href="https://www.worldbank.org/">World Bank</a>. Additionally, I gained significant expertise in cybersecurity, risk management, and IT auditing through my work with <a href="https://www.ibm.com/us-en/">IBM Bangladesh</a> and <a href="https://kpmg.com/bd/en/home.html/">KPMG Bangladesh</a>, one of the Big Four accounting firms.</p>

        <p>In 2011, I earned my B.Sc. in Computer Science and Engineering (CSE) from <a href="https://cse.buet.ac.bd/">Bangladesh University of Engineering and Technology (BUET)</a>. Later, I pursued a Master’s in Information Systems Security from <a href="https://bup.edu.bd/academics/academic_details/464">Bangladesh University of Professionals (BUP)</a> in 2018, where I graduated with a perfect CGPA and received the Presidential gold medal. Additionally, I completed an MBA from the <a href="https://www.fbs-du.com/mis.php">University of Dhaka (DU)</a> majoring in Management Information Systems (MIS). I began my Ph.D. journey in the Fall of 2023.</p>

        <!-- Career Highlights Section -->
        <div class="highlights-section">
            <h2>Career Highlights</h2>
            <div class="highlight-grid">
                <div class="highlight-card">
                    <strong>August 2023:</strong>
                    <p>Began my Ph.D. journey at the Rigorous Design Lab (RiDL) at the University of Texas at Arlington.</p>
                </div>

                <div class="highlight-card">
                    <strong>January 2020:</strong>
                    <p>Awarded a gold medal by the University Chancellor (President of the People's Republic of Bangladesh) for achieving a perfect CGPA of 4.0 in my master's degree.</p>
                </div>

                <div class="highlight-card">
                    <strong>October 2010:</strong>
                    <p>Earned the Information Technology Engineers Examination for Digital Bangladesh Certificate, conducted by the Japan International Cooperation Agency (JICA).</p>
                </div>

                <div class="highlight-card">
                    <strong>March 2007:</strong>
                    <p>Awarded a gold medal from the Governor of the Central Bank of Bangladesh (Bangladesh Bank) for outstanding performance in the Higher Secondary Certificate Exam (12th Grade).</p>
                </div>
            </div>
        </div>

        <!-- Call to Action Section -->
        <div class="cta">
            <p>Feel free to reach out if you have any questions or would like to collaborate on research projects!</p>
            <a href="mailto:email@example.com">Contact Me</a>
        </div>
    </div>
</div>

</body>
</html>
