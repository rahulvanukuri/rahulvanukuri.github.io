---
permalink: /
redirect_from: 
  - /awards/
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Education</title>
    <style>
        /* General Body Style */
        body {
            font-family: 'Georgia', serif;
            background-color: #f0f7fa;
            margin: 0;
            padding: 0;
            color: #333;
        }

        /* Main content container */
        .content {
            width: 128%;
            margin: 0;
            padding: 10px;
            padding-bottom: 20px; /* Added padding at the bottom */
            background-color: #ffffff;
            border-radius: 10px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }

        .separator {
            grid-column: 1 / -1;
            text-align: center;
            font-size: 22px;
            font-weight: bold;
            color: #1e3d8f;
            margin-top: 0px;
            margin-bottom: 0px;
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

        /* New Style for Education Section */
        .education-layout {
            display: grid;
            grid-template-columns: 1fr;
            gap: 20px;
            margin-top: 20px;
        }

        .education-card {
            padding: 15px;
            background-color: #f9f9f9;
            border-radius: 10px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            display: flex;
            align-items: center;
        }

        .education-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
        }

        /* Removing bold styling from h5 */
        .education-card h5 {
            font-family: 'Georgia', serif;
            font-size: 18px;
            font-weight: normal; /* Set to normal to remove bold */
            color: #333;
            margin: 0;
        }

        .education-card small {
            font-size: 14px;
            color: #666;
        }

        .education-card img {
            width: 40px;
            height: 40px;
            margin-right: 20px;
        }

        .education-card p {
            font-size: 16px;
            color: #333;
            margin: 0;
        }

        /* Footer */
        footer {
            text-align: center;
            margin-top: 50px;
            font-size: 14px;
            color: #aaa;
            position: relative; /* Ensure the footer is positioned relative to the content */
            clear: both; /* Clear any floating elements */
            padding: 20px 0; /* Add padding to the footer */
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .education-layout {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

<div class="content">
    <!-- Education Section Separator -->
    <div class="separator">Award Received</div>

    <!-- Education Section -->
    <div class="education-layout">
        <!-- Education Card 1 -->
        <div class="education-card">
            <img src="https://upload.wikimedia.org/wikipedia/commons/d/da/UTA_logomark.png" alt="UTA Logo">
            <div>
                <h5>PhD in Computer Science and Engineering</h5>
                <p>Expected - 2028<br><small><a href="https://www.uta.edu/academics/schools-colleges/engineering/academics/departments/cse/">The University of Texas at Arlington (UTA)</a></small></p>
            </div>
        </div>

        <!-- Education Card 2 -->
        <div class="education-card">
            <img src="https://seeklogo.com/images/B/bangladesh-university-of-professionals-bup-logo-5B259AB69E-seeklogo.com.png" alt="BUP Logo">
            <div>
                <h5>MSc in Information Systems Security (MISS)</h5>
                <p>2018<br><small><a href="https://bup.edu.bd/academics/academic_details/464">Bangladesh University of Professionals (BUP)</a></small></p>
            </div>
        </div>

        <!-- Education Card 3 -->
        <div class="education-card">
            <img src="https://upload.wikimedia.org/wikipedia/en/c/cb/Dhaka_University_logo.svg" alt="Dhaka University Logo">
            <div>
                <h5>MBA in Management Information Systems</h5>
                <p>2016<br><small><a href="https://www.fbs-du.com/mis.php">University of Dhaka (DU)</a></small></p>
            </div>
        </div>

        <!-- Education Card 4 -->
        <div class="education-card">
            <img src="https://upload.wikimedia.org/wikipedia/en/thumb/d/da/BUET_LOGO.svg/1200px-BUET_LOGO.svg.png" alt="BUET Logo">
            <div>
                <h5>BSc in Computer Science and Engineering</h5>
                <p>2011<br><small><a href="https://cse.buet.ac.bd/">Bangladesh University of Engineering and Technology (BUET)</a></small></p>
            </div>
        </div>
    </div>
</div>

<footer>
    © 2024 by Mohammad Shahedur Rahman. All rights reserved.
</footer>

</body>
</html>
