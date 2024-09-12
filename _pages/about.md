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

        /* Education Section */
        .education-section {
            margin-top: 40px;
        }

        .education-section h3 {
            font-size: 24px;
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
            font-size: 18px;
            color: #333;
        }

        .education-item .details small {
            display: block;
            color: #888;
            font-size: 14px;
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
    <p>I’m a Ph.D. student in the Computer Science department at <a href="https://www.uta.edu/">The University of Texas at Arlington</a>, where <a href="#">Dr. Mohammad Atiqul Islam</a> serves as my doctoral advisor. My research focuses on high-performance computing, cybersecurity, machine learning, and resource autoscaling in cloud computing environments.</p>
    
    <p>Before starting my Ph.D., I accrued over 12 years of professional experience in cybersecurity, including serving as the Chief Information Security Officer (CISO) at BRAC Bank PLC, where I managed several large-scale projects. I hold a Master’s degree in Information Systems Security and an MBA from the University of Dhaka.</p>
    
    <a href="#" class="cv-link">Download my resumé / CV</a>

    <!-- Education Section -->
    <div class="education-section">
        <h3>Education</h3>
        <div class="education-item">
            <img src="https://img.icons8.com/ios-filled/50/000000/graduation-cap.png" alt="Graduation Cap">
            <div class="details">
                PhD in Computer Science and Engineering, August 2024 (Expected)
                <small>The University of Texas at Arlington</small>
            </div>
        </div>

        <div class="education-item">
            <img src="https://img.icons8.com/ios-filled/50/000000/graduation-cap.png" alt="Graduation Cap">
            <div class="details">
                MSc in Information Systems Security, 2018
                <small>Bangladesh University of Professionals (BUP)</small>
            </div>
        </div>

        <div class="education-item">
            <img src="https://img.icons8.com/ios-filled/50/000000/graduation-cap.png" alt="Graduation Cap">
            <div class="details">
                BSc in Computer Science and Engineering, 2011
                <small>Bangladesh University of Engineering & Technology (BUET)</small>
            </div>
        </div>
    </div>
</div>

<footer>
    © 2024 by Mohammad Shahedur Rahman. All rights reserved.
</footer>

</body>
</html>
