---
layout: default
title: People
---

<head>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css" rel="stylesheet">
</head>

<main>
    <div class="staff-page">
        <div class="staff-member">
            <div class="staff-content">
                <img src="img/people/Reiko Chen-2.jpg" alt="Reiko Chen">
                <div class="staff-description">
                    <h2>Reiko Chen</h2>
                    <h3>Founder, Web Developer</h3>
                    <p>Reiko is an undergraduate at the University of Michigan studying Computer Science who is currently exploring different topics in computer science including web development and machine learning.
                    </p>
                    <a href="mailto:reikoc@umich.edu" class="email-button">
                        <i class="fa fa-envelope"></i> reikoc@umich.edu
                    </a>
                    <a href="https://www.linkedin.com/in/reikoc1735/" class="linkedin-button">
                        <i class="fab fa-linkedin"></i>
                    </a>
                </div>
            </div>
        </div>
        <div class="staff-member">
            <div class="staff-content">
                <img src="img/people/Wei-X-headshot-768x768.jpg" alt="Xin Wei">
                <div class="staff-description">
                    <h2>Xin Wei</h2>
                    <h3>Founder, Mentor</h3>
                    <p>Xin’s research interests include risk, reliability, and resilience analysis of natural hazards under climate change, leveraging interdisciplinary approaches such as remote sensing, geospatial modeling, data-driven and physics-based models. Before joining the University of Michigan, he earned his PhD in Civil Engineering from Shanghai Jiao Tong University under the supervision of Prof. Lulu Zhang. He was also a visiting scholar in Prof. Paolo Gardoni’s group at the University of Illinois Urbana-Champaign.</p>
                    <a href="mailto:xincwei@umich.edu" class="email-button">
                        <i class="fa fa-envelope"></i> xincwei@umich.edu
                    </a>
                    <a href="https://www.linkedin.com/in/xin-wei-calvin" class="linkedin-button">
                        <i class="fab fa-linkedin"></i>
                    </a>
                </div>
            </div>
        </div>
        <div class="staff-member">
            <div class="staff-content">
                <img src="img/people/M8.JPG" alt="Margaret Gereghty">
                <div class="staff-description">
                    <h2>Margaret Gereghty</h2>
                    <h3>Founder, Designer</h3>
                    <p>Margaret Gereghty is a senior studying Civil Engineering at the University of Michigan, with a minor in Computer Science. Next year, she will begin graduate school in Structural Engineering, where she plans to focus on existing structures and rehabilitation.</p>
                    <a href="mailto:gereghty@umich.edu" class="email-button">
                        <i class="fa fa-envelope"></i> gereghty@umich.edu
                    </a>
                    <a href="http://linkedin.com/in/margaret-gereghty-2623b625b" class="linkedin-button">
                        <i class="fab fa-linkedin"></i>
                    </a>
                </div>
            </div>
        </div>
        <!-- Add more staff-member sections as needed -->
    </div>
</main>

<style>
.staff-page {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    padding: 20px;
}

.staff-member {
    padding: 20px;
    border-radius: 8px;
    display: flex;
    flex-direction: row;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    background-color: #F0F0F0;
}

.staff-content {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 15px;
    text-align: center;
}

.staff-description {
    flex: 1;
    text-align: left;
    word-wrap: break-word;
}

.staff-description h2 {
    margin: 0;
    font-size: 1.5em;
    color: #333;
}

.staff-description h3 {
    margin: 0;
    font-size: 15px;
    color: #444;
}

.staff-description p {
    margin: 5px 0 10px;
    color: #555;
}

.staff-description .email-button,
.staff-description .linkedin-button {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    background-color: #7DBA87;
    color: #1C375F;
    padding: 10px 15px;
    text-decoration: none;
    border-radius: 4px;
    transition: background-color 0.3s;
    margin: 5px;
}

.staff-description .email-button:hover,
.staff-description .linkedin-button:hover {
    background-color: #468EA6;
}

.staff-content img {
    width: 150px;
    height: 150px;
    object-fit: cover;
    border-radius: 50%;
    border: 4px solid #0A2A3A;
}

@media (max-width: 992px) {
    .staff-page {
        grid-template-columns: repeat(2, 1fr);
    }
}

@media (max-width: 600px) {
    .staff-page {
        grid-template-columns: 1fr;
    }
}
</style>