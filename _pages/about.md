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
    <title>Mohammad Shahedur Rahman</title>
    <style>
        /* General Body Style */
        body {
            font-family: 'Roboto', Arial, sans-serif;
            background-color: #f0f7fa;
            margin: 0;
            padding: 0;
        }

        /* Main layout container */
        .main-container {
            display: flex;
            min-height: 100vh;
            width: 100%;
        }

        /* Sidebar Styles */
        .sidebar {
            width: 300px;
            background-color: #ffffff;
            padding: 30px 20px;
            box-shadow: 2px 0 10px rgba(0, 0, 0, 0.1);
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .sidebar img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            margin-bottom: 20px;
        }

        .sidebar h1 {
            font-size: 24px;
            color: #333;
            text-align: center;
            margin: 10px 0;
        }

        .sidebar p {
            font-size: 16px;
            text-align: center;
            color: #555;
            margin-bottom: 20px;
        }

        .sidebar ul {
            list-style: none;
            padding: 0;
            text-align: center;
        }

        .sidebar ul li {
            margin-bottom: 10px;
        }

        .sidebar ul li a {
            color: #007acc;
            text-decoration: none;
            font-size: 16px;
        }

        /* Main content area */
        .content {
            flex-grow: 1;
            padding: 50px;
            background-color: #f7f9fc;
        }

        .content h2 {
            font-family: 'Poppins', sans-serif;
            font-size: 36px;
            color: #333;
            font-weight: 700;
            margin-bottom: 40px;
            position: relative;
        }

        .content h2::after {
            content: '';
            display: block;
            width: 60px;
            height: 4px;
            background-color: #007acc;
            margin-top: 10px;
        }

        .content p {
            font-size: 18px;
            line-height: 1.8;
            color: #555;
            margin-bottom: 20px;
        }

        .content a {
            color: #007acc;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        .content a:hover {
            color: #0056b3;
        }

        /* Career Highlights section */
        .highlight-list {
            list-style: none;
            padding: 0;
        }

        .highlight-item {
            background-color: #ffffff;
            border-radius: 8px;
            padding: 20px;
            margin-bottom: 20px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.05);
            transition: transform 0.2s ease, box-shadow 0.2s ease;
        }

        .highlight-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
        }

        .highlight-item strong {
            font-size: 18px;
            color: #007acc;
        }

        /* Footer */
        footer {
            text-align: center;
            font-size: 14px;
            color: #aaa;
            margin-top: 50px;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .main-container {
                flex-direction: column;
            }

            .sidebar {
                width: 100%;
                box-shadow: none;
            }

            .content {
                padding: 30px;
            }
        }
    </style>
</head>
<body>

<div class="main-container">
    <!-- Sidebar with image and contact details -->
    <div class="sidebar">
        <img src="https://via.placeholder.com/120" alt="Your Profile Picture">
        <h1>Mohammad Shahedur Rahman</h1>
        <p>Ph.D. Student in Computer Science<br>at University of Texas at Arlington</p>
        <ul>
            <li><a href="#">Arlington, Texas</a></li>
            <li><a href="mailto:email@example.com">Email</a></li>
            <li><a href="#">LinkedIn</a></li>
            <li><a href="#">Github</a></li>
            <li><a href="#">Google Scholar</a></li>
        </ul>
    </div>

    <!-- Main content area for biography and career highlights -->
    <div class="content">
        <h2>Biography</h2>
        <p>I am a Ph.D. student in the Computer Science department at <a href="https://www.uta.edu/academics/schools-colleges/engineering/academics/departments/cse/">The University of Texas at Arlington (UTA)</a>, where <a href="https://crystal.uta.edu/~mislam/">Dr. Mohammad Atiqul Islam</a> serves as my doctoral advisor. My research focuses on high-performance computing, cybersecurity, machine learning, resource autoscaling, and microservices.</p>

        <p>Before starting my Ph.D., I accrued over 12 years of professional experience in Bangladesh in numerous critical roles, including Chief Information Security Officer (CISO) at <a href="https://www.bracbank.com/en/">BRAC Bank PLC</a> and IT auditor and security expert for several Bangladesh Government projects (<a href="https://www.cirt.gov.bd/">BGD e-GOV CIRT</a>) funded by the <a href="https://www.worldbank.org/">World Bank</a>. Additionally, I gained significant expertise in cybersecurity, risk management, and IT auditing through my work with <a href="https://www.ibm.com/us-en/">IBM Bangladesh</a> and <a href="https://kpmg.com/bd/en/home.html/">KPMG Bangladesh</a>, one of the Big Four accounting firms.</p>

        <p>In 2011, I earned my B.Sc. in Computer Science and Engineering (CSE) from <a href="https://cse.buet.ac.bd/">Bangladesh University of Engineering and Technology (BUET)</a>. Later, I pursued a Master’s in Information Systems Security (MISS) from <a href="https://bup.edu.bd/academics/academic_details/464">Bangladesh University of Professionals (BUP)</a> in 2018, where I graduated with a perfect CGPA and received the Presidential gold medal. Additionally, I completed an MBA from the <a href="https://www.fbs-du.com/mis.php">University of Dhaka (DU)</a> majoring in Management Information Systems (MIS). I began my Ph.D. journey in the Fall of 2023.</p>

        <h2>Career Highlights</h2>
        <ul class="highlight-list">
            <li class="highlight-item">
                <strong>August 2023:</strong> Began my Ph.D. journey at the Rigorous Design Lab (RiDL) at the University of Texas at Arlington.
            </li>
            <li class="highlight-item">
                <strong>January 2020:</strong> Awarded a gold medal by the University Chancellor (President of the People's Republic of Bangladesh) for achieving a perfect CGPA of 4.0 in my master's degree.
            </li>
            <li class="highlight-item">
                <strong>October 2010:</strong> Earned the Information Technology Engineers Examination for Digital Bangladesh Certificate, conducted by the Japan International Cooperation Agency (JICA).
            </li>
            <li class="highlight-item">
                <strong>March 2007:</strong> Awarded a gold medal from the Governor of the Central Bank of Bangladesh (Bangladesh Bank) for outstanding performance in the Higher Secondary Certificate Exam (12th Grade).
            </li>
        </ul>

        <footer>
            © 2024 by Mohammad Shahedur Rahman. All rights reserved.
        </footer>
    </div>
</div>

</body>
</html>
