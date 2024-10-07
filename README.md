/* Grundlegendes Styling */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #F5F5F5;
    color: #333;
}

.container {
    width: 90%;
    margin: 0 auto;
    max-width: 1200px;
}

header {
    background-color: #3B3B3B;
    color: #FFFFFF;
    padding: 20px 0;
}

.logo img {
    width: 150px;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
    gap: 20px;
}

nav ul li a {
    color: #FFFFFF;
    text-decoration: none;
    font-size: 16px;
}

.hero {
    background-color: #2D2A26;
    color: #FFFFFF;
    text-align: center;
    padding: 100px 0;
    background: url('hero-image.jpg') no-repeat center center;
    background-size: cover;
}

.hero h1 {
    font-size: 3rem;
    margin-bottom: 20px;
}

.hero p {
    font-size: 1.5rem;
    margin-bottom: 40px;
}

.cta-btn {
    background-color: #B89C5E;
    color: #FFFFFF;
    padding: 15px 30px;
    text-decoration: none;
    font-size: 1.2rem;
    border-radius: 5px;
}

.cta-btn:hover {
    background-color: #A87D4E;
}

.services, .projects, .contact {
    padding: 80px 0;
}

h2 {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 40px;
    color: #3B3B3B;
}

.service-cards {
    display: flex;
    justify-content: space-around;
}

.service {
    background-color: #FFFFFF;
    padding: 20px;
    border: 1px solid #CCC;
    border-radius: 10px;
    width: 30%;
    text-align: center;
}

.projects .project-gallery {
    display: flex;
    justify-content: space-around;
}

.project {
    width: 30%;
}

.project img {
    width: 100%;
    border-radius: 10px;
}

.contact form {
    display: flex;
    flex-direction: column;
    gap: 20px;
}

input, textarea {
    width: 100%;
    padding: 15px;
    border: 1px solid #CCC;
    border-radius: 5px;
}

button {
    padding: 15px;
    background-color: #B89C5E;
    color: #FFFFFF;
    border: none;
    cursor: pointer;
}

footer {
    background-color: #3B3B3B;
    color: #FFFFFF;
    text-align: center;
    padding: 20px 0;
}

footer p {
    margin: 10px 0;
}

footer a {
    color: #FFFFFF;
    text-decoration: none;
}

footer a:hover {
    text-decoration: underline;
}
