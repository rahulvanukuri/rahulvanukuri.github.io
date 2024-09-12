body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f7f6; /* Light background */
    color: #333;
}

.container {
    max-width: 100%; /* Make the biography section wider */
    margin: 50px auto;
    padding: 30px;
    background-color: #ffffff; /* White background for contrast */
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
    background-color: #007BFF; /* Bright blue for the button */
    color: white;
    font-size: 18px;
    border-radius: 50px;
    text-decoration: none;
    transition: background-color 0.3s ease, transform 0.2s ease;
}

.cta a:hover {
    background-color: #0056b3; /* Darker blue on hover */
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
