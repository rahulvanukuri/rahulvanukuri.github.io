---
permalink: /
redirect_from: 
  - /biography/
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biography</title>
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

        .content h2 {
            font-size: 28px;
            color: #1e3d8f;
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
            font-size: 18px;
            line-height: 1.8;
            color: #333;
            margin-bottom: 20px;
            text-align: justify;
        }

        .content a {
            color: #1e3d8f;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        .content a:hover {
            color: #003399;
        }

        /* Style for Biography and Interests (Unchanged) */
        .certification-layout {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(400px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .certification-card {
            padding: 10px;
            background-color: #f9f9f9;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            font-family: 'Georgia', serif;
        }

        .certification-card h5,
        .certification-card p,
        .certification-card small {
            font-family: 'Georgia', serif;
            color: #333;
        }

        .certification-card h5 {
            font-size: 14px; /* Font size for headings */
            font-weight: bold; /* Keeping the heading bold */
        }

        .certification-card p {
            font-size: 14px; /* Font size for regular text */
        }

        .certification-card small {
            font-size: 14px; /* Font size for small text */
        }

        .certification-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
        }

        .separator {
            grid-column: 1 / -1;
            text-align: center;
            font-size: 18px;
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

        /* New Style for Education Section (as per your uploaded image) */
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

        .education-card h5 {
            font-family: 'Georgia', serif;
            font-size: 15px; /* Matching font size to Interests section */
            font-weight: bold;
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

        /* Styling for Download CV link */
        .cv-link-wrapper {
            display: flex;
            align-items: center;
            margin-top: 20px;
        }

        .cv-link-wrapper img {
            width: 20px;
            height: 20px;
            margin-right: 10px;
        }

        .cv-link-wrapper a {
            font-size: 14px;
            font-family: 'Georgia', serif;
            color: #333;
            text-decoration: none;
        }

        .cv-link-wrapper a:hover {
            color: #1e3d8f;
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
            .certification-layout {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

<div class="content">
    <!-- Full-width Biography Card -->
    <div class="certification-layout">
        <div class="separator">Biography</div>
        <!-- Biography Card without the Icon -->
        <div class="certification-card" style="grid-column: 1 / -1;">
            <div>
                <p>I’m a Masters student in the Computer Science department at The University of Texas at Arlington, where <a href="https://www.uta.edu/academics/faculty/profile?username=royd3" target="_blank">Dr. Debshri Roy</a> is my doctoral advisor. My research focuses on Large language Models, Communication Signal analysis, machine learning, and spectograms and different Generative AI models.</p>
               <p> Before starting my masters, I accrued over 1 years of professional experience in India in numerous critical roles, including Data Engineer at <a href="https://eessqadv.adp.com/eess/default.htm">ADP</a> and Analyst  at Deliotte. Additionally, I gained significant expertise in React js and Django, Machine Learning , and Large language models through my work with <a href="https://www.ibm.com/us-en/">Twist Lab and ciruculum</a> and <a href="https://www2.deloitte.com/in/en.html">Deloitte</a>, one of the Big Four accounting firms.</p>
                
                <!-- New Download CV section -->
                <div class="cv-link-wrapper">
                    <img src="https://www.oiml.org/en/ressources/icons/download-button.jpg/@@images/3139e560-3f59-4ee9-a5e4-71f0ee9535eb.png" alt="Download Icon">
                    <a href="#" class="cv-link" target="_blank">Download my resumé / CV</a>
                </div>
            </div>
        </div>
    </div>

    <!-- Card Layout for Interests -->
    <div class="certification-layout">
        <!-- Interests Section Separator -->
        <div class="separator">Interests</div>
        <!-- Interests Card 1 --!>
        <div class="certification-card">
            <div>
                <li>Machine Learning</li>
                <li>Distributed Systems</li>
                <li>Large Language models</li> 
            </div>
        </div>

        <!-- Interests Card 2 -->
        <div class="certification-card">
            <div>
                <li>React js</li> 
                <li>Django</li> 
                <li>Diffusion models & transformers</li>
            </div>
        </div>
    </div>

    <!-- New Style for Education Section -->
    <div class="education-layout">
        <!-- Education Section Separator -->
        <div class="separator">
            <span>Education</span>
        </div>

        <!-- Education Card 1 -->
        <div class="education-card">
            <img src="https://upload.wikimedia.org/wikipedia/commons/d/da/UTA_logomark.png" alt="Graduation Cap">
            <div>
                <h5>Masters in Computer Science and Engineering </h5>
                <p>Expected - 2025<br><small><a href="https://www.uta.edu/academics/schools-colleges/engineering/academics/departments/cse/" target="_blank">The University of Texas at Arlington (UTA)</a></small></p>
            </div>
        </div>


        <!-- Education Card 2 -->
        <div class="education-card">
            <img src="https://upload.wikimedia.org/wikipedia/en/6/68/Chaitanya_Bharathi_Institute_of_Technology_logo.png" alt="UnderGraduation Cap">
            <div>
                <h5>Undergraduate in Information Technology</h5>
                <p>2023<br><small><a href="https://www.cbit.org.in/departments/information-technology/about" target="_blank">Chaitanya Bharathi Institute of Technology</a></small></p>
            </div>
        </div>


<footer>
    © 2024 by Rahul Vanukuri. All rights reserved.
</footer>

</body>
</html>
