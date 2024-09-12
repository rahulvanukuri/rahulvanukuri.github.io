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
            display: flex;
            max-width: 1200px; /* Increased width */
            margin: 50px auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            border-radius: 15px;
        }

        /* Profile section on the left */
        .profile-section {
            width: 25%; /* Adjusted to allow more width for the biography */
            text-align: center;
            padding-right: 30px;
            border-right: 1px solid #ddd;
        }

        .profile-section img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-bottom: 20px;
        }

        .profile-section h2 {
            font-size: 24px;
            margin-bottom: 10px;
        }

        .profile-section p {
            margin-bottom: 5px;
            font-size: 14px;
        }

        /* Biography section on the right */
        .biography-section {
            width: 75%; /* Increased biography section width */
            padding-left: 40px;
        }

        .biography-section h1 {
            font-size: 32px;
            margin-bottom: 20px;
            color: #222;
        }

        .biography-section p {
            text-align: justify;
            margin-bottom: 20px;
            font-size: 16px;
            line-height: 1.6; /* Improve readability */
            color: #555;
        }

        a {
            text-decoration: none;
            color: #007BFF;
        }

        a:hover {
            text-decoration: underline;
        }

        /* Responsive adjustments */
        @media (max-width: 768px) {
            .container {
                flex-direction: column;
                padding: 15px;
            }

            .profile-section {
                width: 100%;
                padding-right: 0;
                border-right: none;
                text-align: center;
            }

            .biography-section {
                width: 100%;
                padding-left: 0;
            }
        }
    </style>
</head>
<body>

<div class="container">
    <!-- Profile Section (Left Panel) -->
    <div class="profile-section">
        <img src="your-profile-image.jpg" alt="Profile Picture">
        <h2>Mohammad Shahedur Rahman</h2>
        <p>Ph.D. Student in Department of Computer Science at The University of Texas at Arlington</p>
        <p>Arlington, Texas</p>
        <p>
            <a href="mailto:email@example.com">Email</a><br>
            <a href="#">LinkedIn</a><br>
            <a href="#">GitHub</a><br>
            <a href="#">Google Scholar</a>
        </p>
    </div>

    <!-- Biography Section -->
    <div class="biography-section">
        <h1>Biography</h1>
        <p>I am a Ph.D. student in the Computer Science department at <a href="https://www.uta.edu/academics/schools-colleges/engineering/academics/departments/cse/">The University of Texas at Arlington (UTA)</a>, where <a href="https://crystal.uta.edu/~mislam/">Dr. Mohammad Atiqul Islam</a> serves as my doctoral advisor. My research focuses on high-performance computing, cybersecurity, machine learning, resource autoscaling, and microservices.</p>

        <p>Before starting my Ph.D., I accrued over 12 years of professional experience in Bangladesh in numerous critical roles including Chief Information Security Officer (CISO) at <a href="https://www.bracbank.com/en/">BRAC Bank PLC</a> and IT auditor and security expert for several Bangladesh Government projects (<a href="https://www.cirt.gov.bd/">BGD e-GOV CIRT</a>) funded by the <a href="https://www.worldbank.org/">World Bank</a>. Additionally, I gained significant expertise in cybersecurity, risk management, and IT auditing through my work with <a href="https://www.ibm.com/us-en/">IBM Bangladesh</a> and <a href="https://kpmg.com/bd/en/home.html/">KPMG Bangladesh</a>, one of the Big Four accounting firms.</p>

        <p>In 2011, I earned my B.Sc. in Computer Science and Engineering (CSE) from <a href="https://cse.buet.ac.bd/">Bangladesh University of Engineering and Technology (BUET)</a>. Later, I pursued a Master’s in Information Systems Security from <a href="https://bup.edu.bd/academics/academic_details/464">Bangladesh University of Professionals (BUP)</a> in 2018, where I graduated with a perfect CGPA and received the Presidential gold medal. Additionally, I completed an MBA from the <a href="https://www.fbs-du.com/mis.php">University of Dhaka (DU)</a> majoring in Management Information Systems (MIS). I began my Ph.D. journey in the Fall of 2023.</p>
    </div>
</div>

</body>
</html>
