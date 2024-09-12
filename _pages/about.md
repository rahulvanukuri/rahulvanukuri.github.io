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
            font-family: 'Georgia', serif; /* Font matching the attached image */
            background-color: #f0f7fa;
            margin: 0;
            padding: 0;
            color: #333; /* Text color matching the attached image */
        }

        /* Main content container */
        .content {
            max-width: 800px;
            margin: 30px auto;
            background-color: #ffffff;
            border-radius: 10px;
            padding: 40px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
        }

        .content h2 {
            font-family: 'Georgia', serif;
            font-size: 28px; /* Matching font size */
            color: #1e3d8f; /* Matching blue color */
            font-weight: bold;
            margin-bottom: 20px;
            position: relative;
        }

        .content h2::after {
            content: '';
            display: block;
            width: 100%;
            height: 1px;
            background-color: #cccccc;
            margin-top: 10px;
        }

        .content p {
            font-size: 18px; /* Matching font size */
            line-height: 1.8;
            color: #333; /* Text color */
            margin-bottom: 20px;
            text-align: justify; /* Justified alignment */
        }

        .content a {
            color: #1e3d8f; /* Blue color for links */
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        .content a:hover {
            color: #003399;
        }

        /* Two-Column Layout for Education and Interests */
        .two-columns {
            display: flex;
            justify-content: space-between;
            margin-top: 40px;
        }

        /* Education Section */
        .education-section h3 {
            font-family: 'Georgia', serif;
            font-size: 24px; /* Matching font size */
            color: #1e3d8f; /* Blue color */
            font-weight: bold;
            margin-bottom: 20px;
        }

        .education-item {
            display: flex;
            align-items: flex-start;
            margin-bottom: 20px;
        }

        .education-item img {
            width: 24px;
            height: 24px;
            margin-right: 15px;
        }

        .education-item .details {
            font-size: 18px; /* Matching font size */
            color: #333;
            text-align: justify; /* Justified alignment */
        }

        .education-item .details small {
            display: block;
            color: #888;
            font-size: 14px;
        }

        /* Interests Section */
        .interests-section h3 {
            font-family: 'Georgia', serif;
            font-size: 24px; /* Matching font size */
            color: #1e3d8f; /* Blue color */
            font-weight: bold;
            margin-bottom: 20px;
        }

        .interests-section ul {
            list-style: none;
            padding: 0;
        }

        .interests-section ul li {
            font-size: 18px;
            margin-bottom: 10px;
            color: #333;
            text-align: justify; /* Justified alignment */
        }

        .interests-section ul li::before {
            content: "•";
            color: #1e3d8f; /* Matching blue color for bullet points */
            font-weight: bold;
            display: inline-block;
            width: 1em;
            margin-left: -1em;
        }

        /* Footer */
        footer {
            text-align: center;
            margin-top: 50px;
            font-size: 14px;
            color: #aaa;
        }

        /* Aesthetic Enhancements */
        .content .cv-link {
            display: inline-block;
            background-color: #007acc;
            color: #fff;
            padding: 12px 24px;
            border-radius: 5px;
            margin-top: 20px;
            text-decoration: none;
        }

        .content .cv-link:hover {
            background-color: #0056b3;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .two-columns {
                flex-direction: column;
            }

            .column {
                width: 100%;
                margin-bottom: 20px;
            }
        }
    </style>
</head>
<body>

<div class="content">
    <!-- Biography Section -->
    <h2>Biography</h2>
    <p>I’m a Ph.D. student in the Computer Science department at The University of Texas at Arlington, where <a href="#">Dr. Mohammad Atiqul Islam</a> serves as my doctoral advisor. My research focuses on high-performance computing, cybersecurity, machine learning, and resource autoscaling in cloud computing environments.</p>
    
  <p>Before starting my Ph.D., I accrued over 12 years of professional experience in Bangladesh in numerous critical roles, including Chief Information Security Officer (CISO) at <a href="https://www.bracbank.com/en/">BRAC Bank PLC</a> and IT auditor and security expert for several Bangladesh Government projects (<a href="https://www.cirt.gov.bd/">BGD e-GOV CIRT</a>) funded by the <a href="https://www.worldbank.org/">World Bank</a>. Additionally, I gained significant expertise in cybersecurity, risk management, and IT auditing through my work with <a href="https://www.ibm.com/us-en/">IBM Bangladesh</a> and <a href="https://kpmg.com/bd/en/home.html/">KPMG Bangladesh</a>, one of the Big Four accounting firms.</p>
    
    <a href="#" class="cv-link">Download my resumé / CV</a>

    <!-- Two-Column Layout for Interests and Education -->
    <div class="two-columns">
        <!-- Interests Section -->
        <div class="column interests-section">
            <h3>Interests</h3>
            <ul>
                <li>Cloud Computing</li>
                <li>Information and Cyber Security</li>
                <li>Microservices</li>
                <li>High Performance Computing (HPC)</li>
                <li>HPC in the Cloud (Converged Computing)</li>
                <li>Machine Learning for Systems</li>
                <li>Distributed Systems</li>
            </ul>
        </div>

<!-- Education Section -->
    <div class="education-section">
        <h3>Education</h3>
        <div class="education-item">
            <img src="https://img.icons8.com/ios-filled/50/000000/graduation-cap.png" alt="Graduation Cap">
            <div class="details">
                PhD in Computer Science and Engineering, August 2028 (Expected)
                <small><a href="https://www.uta.edu/academics/schools-colleges/engineering/academics/departments/cse/">The University of Texas at Arlington (UTA)</a></small>
            </div>
        </div>

        <div class="education-item">
            <img src="https://img.icons8.com/ios-filled/50/000000/graduation-cap.png" alt="Graduation Cap">
            <div class="details">
                MSc in Information Systems Security (MISS), 2018
                <small><a href="https://bup.edu.bd/academics/academic_details/464">Bangladesh University of Professionals (BUP)</a></small>
            </div>
        </div>

        <div class="education-item">
            <img src="https://img.icons8.com/ios-filled/50/000000/graduation-cap.png" alt="Graduation Cap">
            <div class="details">
                MBA in Management Information Systems (MIS), 2016
                <small><a href="https://www.fbs-du.com/mis.php">University of Dhaka (DU)</a></small>
            </div>
        </div>

        <div class="education-item">
            <img src="https://img.icons8.com/ios-filled/50/000000/graduation-cap.png" alt="Graduation Cap">
            <div class="details">
                BSc in Computer Science and Engineering, 2011
                <small><a href="https://cse.buet.ac.bd/">Bangladesh University of Engineering and Technology (BUET)</a></small>
            </div>
        </div>
    </div>
</div>

<footer>
    © 2024 by Mohammad Shahedur Rahman. All rights reserved.
</footer>

</body>
</html>
