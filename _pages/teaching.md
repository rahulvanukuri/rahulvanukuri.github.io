---
layout: archive
title: ""
permalink: /teaching/
author_profile: true
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Teaching Assistantship</title>
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
            width: 80%; /* Centered width for better readability */
            margin: 0 auto;
            padding: 20px;
            background-color: #ffffff;
            border-radius: 10px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }

        .content h2 {
            font-size: 28px;
            color: #1e3d8f;
            font-weight: bold;
            margin-bottom: 20px;
            text-align: center;
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

        /* Bullet Style for Course Titles */
        .bullet {
            display: inline-block;
            background-color: #1e3d8f;
            width: 12px;
            height: 12px;
            border-radius: 50%;
            margin-right: 10px;
        }

        /* Certification Layout */
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
        }

        .certification-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
        }

        .separator {
            text-align: center;
            font-size: 22px;
            font-weight: bold;
            color: #1e3d8f;
            margin-top: 30px;
            margin-bottom: 30px;
        }

        .separator::after {
            content: '';
            display: block;
            width: 60%;
            height: 1px;
            background-color: #cccccc;
            margin: 10px auto;
        }

        /* Education Section Layout */
        .education-layout {
            display: grid;
            grid-template-columns: 1fr;
            gap: 20px;
            margin-top: 20px;
        }

        .education-card {
            padding: 20px;
            background-color: #f9f9f9;
            border-radius: 10px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
            display: flex;
            align-items: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .education-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
        }

        .education-card h5 {
            font-family: 'Georgia', serif;
            font-size: 18px;
            font-weight: bold;
            color: #1e3d8f;
            margin-bottom: 10px;
        }

        .education-card h4 {
            font-size: 16px;
            color: #666;
            margin-bottom: 15px;
        }

        .education-card p {
            font-size: 16px;
            color: #333;
            margin-bottom: 0;
        }

        /* Footer styling */
        footer {
            text-align: center;
            margin-top: 40px;
            font-size: 14px;
            color: #aaa;
            padding: 20px 0;
            border-top: 1px solid #cccccc;
        }

        /* Responsive Design for mobile */
        @media (max-width: 768px) {
            .content {
                width: 95%; /* Adjust content width for smaller screens */
            }
        }
    </style>
</head>
<body>

    <!-- Main content container -->
    <div class="content">
        <!-- Teaching Assistantship Section -->
        <h2>Teaching Assistantship</h2>

        <!-- Education Section Layout -->
        <div class="education-layout">
            <!-- Education Card 1 -->
            <div class="education-card">
                <div>
                    <span class="bullet"></span><h5 style="display: inline-block;">CSE 1310. Introduction To Computers & Programming</h5>
                    <h4>Fall 2023</h4>
                    <p>An introduction to the computer, algorithmic process, and programming using basic control and data structures, using a procedural language. Prerequisite: C</p>
                </div>
            </div>

            <!-- Education Card 2 -->
            <div class="education-card">
                <div>
                    <span class="bullet"></span><h5 style="display: inline-block;">CSE 1106. Introduction To Computer Science And Engineering</h5>
                    <h4>Spring 2024</h4>
                    <p>A practical approach to hands-on computer hardware and software systems in a laboratory environment. Students will be exposed to basic engineering concepts such as simple circuits, digital logic, embedded controllers, computer networking, software design, and Linux operating systems. Prerequisite: C</p>
                </div>
            </div>

            <!-- Education Card 3 -->
            <div class="education-card">
                <div>
                    <span class="bullet"></span><h5 style="display: inline-block;">CSE 5307. Programming Language Concepts</h5>
                    <h4>Summer 2024</h4>
                    <p>Study and evaluation of concepts in programming language for modern computer systems. Programming projects are selected from string-based, symbolic, algorithmic, and object-oriented languages.</p>
                </div>
            </div>

            <!-- Education Card 4 -->
            <div class="education-card">
                <div>
                    <span class="bullet"></span><h5 style="display: inline-block;">CSE 2312. Computer Organization & Assembly Language Programming</h5>
                    <h4>Fall 2024</h4>
                    <p>Computer organization from the software viewpoint, including instruction set architectures, memory addressing, integer and floating-point representation and arithmetic, instruction pipelining, cache, memory virtualization, and I/O. The relationship of higher-level programming languages to assembly language and instruction set architecture is also explored. Prerequisite: C</p>
                </div>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer>
        © 2024 Your Name. All rights reserved.
    </footer>

</body>
</html>
