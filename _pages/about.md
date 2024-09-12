---
permalink: /
redirect_from: 
  - /about/
  - /about.html
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Biography</title>
    <style>
        /* General Style */
        body {
            font-family: 'Roboto', Arial, sans-serif;
            background: linear-gradient(135deg, #e9f8ff, #f7f7f7);
            color: #333;
            margin: 0;
            padding: 0;
            display: flex;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
        }

        .container {
            max-width: 1000px;
            margin: 30px;
            padding: 40px;
            background: #ffffff;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            animation: fadeIn 1s ease-in-out;
        }

        /* Fade In Animation */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* Headings */
        h2 {
            text-align: center;
            font-family: 'Poppins', sans-serif;
            font-size: 38px;
            color: #333;
            font-weight: 800;
            letter-spacing: 1px;
            margin-bottom: 30px;
            position: relative;
        }

        h2::after {
            content: '';
            display: block;
            width: 80px;
            height: 3px;
            background: #00aaff;
            margin: 10px auto;
        }

        p {
            text-align: justify;
            font-size: 18px;
            line-height: 1.8;
            color: #555;
            margin-bottom: 25px;
        }

        a {
            color: #00aaff;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease, border-bottom 0.3s ease;
            border-bottom: 2px solid transparent;
        }

        a:hover {
            color: #007acc;
            border-bottom: 2px solid #007acc;
        }

        /* Career Highlights Section */
        .highlight-list {
            list-style-type: none;
            padding: 0;
        }

        .highlight-item {
            display: flex;
            align-items: flex-start;
            padding: 15px;
            margin-bottom: 20px;
            border-radius: 10px;
            background-color: #f9f9f9;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.05);
            transition: box-shadow 0.3s ease, transform 0.3s ease;
        }

        .highlight-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.1);
        }

        .highlight-item strong {
            font-size: 18px;
            color: #333;
            min-width: 160px;
            margin-right: 15px;
        }

        .highlight-item p {
            font-size: 16px;
            color: #666;
            margin: 0;
        }

        /* Call to Action Button */
        .cta {
            text-align: center;
            margin-top: 50px;
        }

        .cta a {
            display: inline-block;
            padding: 15px 35px;
            background-color: #00aaff;
            color: white;
            font-size: 18px;
            font-weight: bold;
            border-radius: 50px;
            text-decoration: none;
            transition: background-color 0.3s ease, transform 0.2s ease;
            box-shadow: 0 6px 20px rgba(0, 170, 255, 0.2);
        }

        .cta a:hover {
            background-color: #007acc;
            transform: translateY(-3px);
        }

        footer {
            text-align: center;
            margin-top: 50px;
            font-size: 14px;
            color: #aaa;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            h2 {
                font-size: 30px;
            }

            p {
                font-size: 16px;
            }

            .highlight-item strong {
                font-size: 16px;
                min-width: 120px;
            }

            .cta a {
                font-size: 16px;
                padding: 12px 28px;
            }
        }
    </style>
</head>
<body>

<div class="container">
    <!-- Biography Section -->
    <h2>Biography</h2>
    <p>I am a Ph.D. student in the Computer Science department at <a href="https://www.uta.edu/academics/schools-colleges/engineering/academics/departments/cse/">The University of Texas at Arlington (UTA)</a>, where <a href="https://crystal.uta.edu/~mislam/">Dr. Mohammad Atiqul Islam</a> serves as my doctoral advisor. My research focuses on high-performance computing, cybersecurity, machine learning, resource autoscaling, and microservices.</p>

    <p>Before starting my Ph.D., I accrued over 12 years of professional experience in Bangladesh in numerous critical roles, including Chief Information Security Officer (CISO) at <a href="https://www.bracbank.com/en/">BRAC Bank PLC</a> and IT auditor and security expert for several Bangladesh Government projects (<a href="https://www.cirt.gov.bd/">BGD e-GOV CIRT</a>) funded by the <a href="https://www.worldbank.org/">World Bank</a>. Additionally, I gained significant expertise in cybersecurity, risk management, and IT auditing through my work with <a href="https://www.ibm.com/us-en/">IBM Bangladesh</a> and <a href="https://kpmg.com/bd/en/home.html/">KPMG Bangladesh</a>, one of the Big Four accounting firms.</p>

    <p>In 2011, I earned my B.Sc. in Computer Science and Engineering (CSE) from <a href="https://cse.buet.ac.bd/">Bangladesh University of Engineering and Technology (BUET)</a>. Later, I pursued a Master’s in Information Systems Security (MISS) from <a href="https://bup.edu.bd/academics/academic_details/464">Bangladesh University of Professionals (BUP)</a> in 2018, where I graduated with a perfect CGPA and received the Presidential gold medal. Additionally, I completed an MBA from the <a href="https://www.fbs-du.com/mis.php">University of Dhaka (DU)</a> majoring in Management Information Systems (MIS). I began my Ph.D. journey in the Fall of 2023.</p>

    <!-- Career Highlights Section -->
    <h2>Career Highlights</h2>
    <ul class="highlight-list">
        <li class="highlight-item">
            <strong>August 2023:</strong>
            <p>Began my Ph.D. journey at the Rigorous Design Lab (RiDL) at the University of Texas at Arlington.</p>
        </li>
        <li class="highlight-item">
            <strong>January 2020:</strong>
            <p>Awarded a gold medal by the University Chancellor (President of the People's Republic of Bangladesh) for achieving a perfect CGPA of 4.0 in my master's degree.</p>
        </li>
        <li class="highlight-item">
            <strong>October 2010:</strong>
            <p>Earned the Information Technology Engineers Examination for Digital Bangladesh Certificate, conducted by the Japan International Cooperation Agency (JICA).</p>
        </li>
        <li class="highlight-item">
            <strong>March 2007:</strong>
            <p>Awarded a gold medal from the Governor of the Central Bank of Bangladesh (Bangladesh Bank) for outstanding performance in the Higher Secondary Certificate Exam (12th Grade).</p>
        </li>
    </ul>

    <!-- Call to Action Section -->
    <div class="cta">
        <p>Feel free to reach out if you have any questions or would like to collaborate on research projects!</p>
        <a href="mailto:email@example.com">Contact Me</a>
    </div>
</div>

<footer>
    © 2024 by [Your Name]. All rights reserved.
</footer>

</body>
</html>
